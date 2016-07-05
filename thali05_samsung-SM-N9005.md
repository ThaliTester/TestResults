#### Test 7214543196063dc_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
07-05 14:04:38.136   302   302 E SMD     : DCD ON
,07-05 14:04:38.426  7373  7373 D AndroidRuntime: 
07-05 14:04:38.426  7373  7373 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 14:04:38.426  7373  7373 D AndroidRuntime: CheckJNI is OFF
07-05 14:04:38.426  7373  7373 D AndroidRuntime: readGMSProperty: start
07-05 14:04:38.426  7373  7373 D AndroidRuntime: readGMSProperty: already setted!!
07-05 14:04:38.436  7373  7373 D AndroidRuntime: readGMSProperty: end
07-05 14:04:38.436  7373  7373 D AndroidRuntime: addProductProperty: start
07-05 14:04:38.565  7373  7373 E AffinityControl: AffinityControl: registerfunction enter
07-05 14:04:38.586  7373  7373 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 14:04:38.596   920  1445 E PersonaManagerService: inState():  stateMachine is null !!
07-05 14:04:38.596   920  1445 I PersonaManagerService: PersonaId don't exist
07-05 14:04:38.596   920  1445 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-05 14:04:38.596   920  1445 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
07-05 14:04:38.596   920  1445 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 14:04:38.596   920  1445 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-05 14:04:38.606   920  1445 W ActivityManager: mDVFSHelper.acquire()
07-05 14:04:38.606   920  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:38.606   920  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:38.606   920  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:38.606   920  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:38.645  7387  7387 E Zygote  : MountEmulatedStorage()
07-05 14:04:38.645  7387  7387 E Zygote  : v2
07-05 14:04:38.645  7387  7387 I libpersona: KNOX_SDCARD checking this for 10079
07-05 14:04:38.645  7387  7387 I libpersona: KNOX_SDCARD not a persona
07-05 14:04:38.645   920  1445 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7387 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 14:04:38.655  7387  7387 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 14:04:38.655  7387  7387 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 14:04:38.655  7387  7387 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-05 14:04:38.655  7373  7373 D AndroidRuntime: Shutting down VM
07-05 14:04:38.675  7387  7387 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:38.685  7387  7387 D ActivityThread: Added TimaKeyStore provider
07-05 14:04:38.695   920  3072 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 14:04:38.705  7387  7387 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-05 14:04:38.715  1446  1446 D SurfaceWidgetView: destroyHardwareResources():19904590
07-05 14:04:38.755   266  1063 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
07-05 14:04:38.755   266   344 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
07-05 14:04:38.775  1819  1842 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
07-05 14:04:38.775  1446  1446 V ActivityThread: updateVisibility : ActivityRecord{361b806e token=android.os.BinderProxy@1e2ef9af {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-05 14:04:38.775  1446  1446 D Launcher: onTrimMemory. Level: 20
07-05 14:04:38.775  7387  7387 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-05 14:04:38.785  7387  7387 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
07-05 14:04:38.795  7387  7387 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1822-1824)
07-05 14:04:38.795  7387  7387 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:04:38.815  7387  7387 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {109c2838}
07-05 14:04:38.815  7387  7387 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:04:38.815  7387  7387 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 14:04:38.835  7387  7387 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 14:04:38.845  7387  7387 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 14:04:38.845  7387  7387 E SysUtils: ApplicationContext is null in ApplicationStatus
07-05 14:04:38.855  7387  7387 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-05 14:04:38.865  7387  7387 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-05 14:04:38.865  7387  7387 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
07-05 14:04:38.865  7387  7387 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-05 14:04:38.865  7387  7387 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-05 14:04:38.865  7387  7387 I Adreno-EGL: Build Date: 11/19/14 Wed
07-05 14:04:38.865  7387  7387 I Adreno-EGL: Local Branch: mybranch5813579
07-05 14:04:38.865  7387  7387 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-05 14:04:38.865  7387  7387 I Adreno-EGL: Local Patches: NONE
07-05 14:04:38.865  7387  7387 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-05 14:04:39.015  7387  7426 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-05 14:04:39.065  7387  7387 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 14:04:39.085  7387  7387 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-05 14:04:39.095  7387  7387 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-05 14:04:39.105  7387  7387 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 14:04:39.105  7387  7387 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 14:04:39.195  7387  7387 D Activity: performCreate Call secproduct feature valuefalse
07-05 14:04:39.195  7387  7387 D Activity: performCreate Call debug elastic valuetrue
,07-05 14:04:39.195   920  1007 W ActivityManager: Activity pause timeout for ActivityRecord{2b7cf5fa u0 com.test.thalitest/.MainActivity t23}
,07-05 14:04:39.215  7387  7441 D OpenGLRenderer: Render dirty regions requested: true
,07-05 14:04:39.215   920  1445 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-05 14:04:39.215   920  1445 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-05 14:04:39.215   920   920 D PersonaManagerService: getPersonasForUser(): returning null!
07-05 14:04:39.215   920  1445 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-05 14:04:39.215   920   920 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,07-05 14:04:39.235  7387  7387 V ActivityThread: updateVisibility : ActivityRecord{232070b2 token=android.os.BinderProxy@3760ba14 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-05 14:04:39.255   266   266 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,07-05 14:04:39.275  7387  7441 I OpenGLRenderer: Initialized EGL, version 1.4
,07-05 14:04:39.285  7387  7441 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xafb6e038 ,&mEglDisplay = 1 , &mEglConfig = 8 
,07-05 14:04:39.285  7387  7441 D OpenGLRenderer: Enabling debug mode 0
,07-05 14:04:39.335  7387  7387 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3760ba14 time:152362
,07-05 14:04:39.335   920  1057 W ActivityManager: mDVFSHelper.release()
07-05 14:04:39.335   920  1057 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2b7cf5fa u0 com.test.thalitest/.MainActivity t23} time:152362
,07-05 14:04:39.345   920  1057 D MultiWindowConverter: This application or window do not support multiwindow
,07-05 14:04:39.405  7387  7387 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7387
,07-05 14:04:39.555  7387  7387 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 14:04:39.725  7387  7447 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1279579520
,07-05 14:04:39.745  7387  7447 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 14:04:39.745  7387  7447 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 14:04:39.745  7387  7447 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 14:04:39.745  7387  7447 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 14:04:39.745  7387  7447 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 14:04:39.745  7387  7447 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28326a62 added. We now have 1 listener(s)
,07-05 14:04:39.745  7387  7447 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:2A:28:2D
,07-05 14:04:39.755  7387  7447 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,07-05 14:04:39.755  7387  7447 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-05 14:04:39.755  7387  7447 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-05 14:04:39.765  7387  7447 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 14:04:39.765  7387  7447 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 14:04:39.765  7387  7447 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 14:04:39.765  7387  7447 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:2A:28:2D
07-05 14:04:39.765  7387  7447 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 14:04:39.765  7387  7447 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 14:04:39.765  7387  7447 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 14:04:39.765  7387  7447 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 14:04:39.765  7387  7447 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 14:04:39.765  7387  7447 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 14:04:39.765  7387  7447 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-05 14:04:39.765  7387  7447 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa35729 added. We now have 1 listener(s)
,07-05 14:04:39.765  7387  7447 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-05 14:04:39.775  7387  7447 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,07-05 14:04:39.775  7387  7447 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-05 14:04:39.775  7387  7447 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-05 14:04:39.845   920  1464 I art     : Explicit concurrent mark sweep GC freed 155879(8MB) AllocSpace objects, 14(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.297ms total 137.473ms
,07-05 14:04:39.845  7387  7447 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 14:04:39.845  7387  7447 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:2A:28:2D
,07-05 14:04:39.845   920  1445 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:39.875  7387  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:39.875  7387  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:39.875  7387  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 14:04:39.875  7387  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:39.875  7387  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:39.875  7387  7447 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:04:39.875  7387  7447 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:04:39.875  7387  7447 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 14:04:39.875  7387  7447 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 14:04:39.875  7387  7447 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 14:04:39.875  7387  7447 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-05 14:04:39.875   920  1236 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:39.875  7387  7387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 14:04:39.875   920  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:39.875  7387  7387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 14:04:39.915  7387  7387 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 14:04:40.305   920  3072 D SSRM:n  : SIOP:: AP = 370, PST = 382, CUR = 450
,07-05 14:04:40.655  7387  7400 I art     : Background sticky concurrent mark sweep GC freed 69483(4MB) AllocSpace objects, 14(1492KB) LOS objects, 21% free, 20MB/25MB, paused 1.013ms total 104.023ms
,07-05 14:04:40.905  7387  7457 W jxcore-log: Initializing JXcore engine
,07-05 14:04:40.905  7387  7457 W jxcore-log: JXcore engine is ready
,07-05 14:04:40.965  1954  1954 E auditd  : In denial and Property audit_ondenial is set to 1 
07-05 14:04:40.965  1954  1954 E audit   : type=1400 msg=audit(1467720280.955:203): avc:  denied  { ioctl } for  pid=7457 comm="Thread-1269" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,07-05 14:04:40.965  1954  1954 E audit   :  SEPF_SM-N9005_5.0-1_0032
07-05 14:04:40.965  1954  1954 E audit   : 
07-05 14:04:40.965  1954  1954 E audit   : type=1300 msg=audit(1467720280.955:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9ad008d8 items=0 ppid=343 ppcomm=main pid=7457 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1269" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-05 14:04:40.965  1954  1954 E audit   : type=1320 msg=audit(1467720280.955:203): 
,07-05 14:04:40.965   920  1038 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
,07-05 14:04:40.965   920  1038 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,07-05 14:04:40.975   920  1038 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,07-05 14:04:40.985  6840  6840 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-05 14:04:40.985  6840  6840 D SecurityLogAgent:  SeDenialReceiver : File path = null
,07-05 14:04:40.985  7387  7457 W jxcore-log: Starting JXcore engine
,07-05 14:04:41.095  7387  7457 W jxcore-log: Platform android
07-05 14:04:41.095  7387  7457 W jxcore-log: 
07-05 14:04:41.105  7387  7457 W jxcore-log: Process ARCH arm
07-05 14:04:41.105  7387  7457 W jxcore-log: 
,07-05 14:04:41.135   302   302 E SMD     : DCD ON
,07-05 14:04:41.315  7387  7457 I jxcore-log: JXcore Cordova bridge is ready!
07-05 14:04:41.315  7387  7457 I jxcore-log: 
07-05 14:04:41.315  7387  7457 W jxcore-log: JXcore engine is started
,07-05 14:04:41.325  7387  7447 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-05 14:04:41.325  7387  7387 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-05 14:04:41.705   920  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:04:41.705   920  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:04:41.705   920  1623 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 14:04:41.705   920  1623 D BatteryService: stay LED for fully charged
07-05 14:04:41.705   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:04:41.705   920   920 I MotionRecognitionService: Plugged
07-05 14:04:41.705   920   920 I MotionRecognitionService: setPowerConnected  = true
07-05 14:04:41.715  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:04:41.715  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:04:41.715  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:04:41.715  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:04:41.715  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:04:41.715  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:04:41.715  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:04:41.715  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:04:43.835   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:04:44.135   302   302 E SMD     : DCD ON
,07-05 14:04:47.135   302   302 E SMD     : DCD ON
,07-05 14:04:47.435   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:48.435   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:48.655   920  1064 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-05 14:04:49.435   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:50.135   302   302 E SMD     : DCD ON
,07-05 14:04:50.365   920  3072 D SSRM:n  : SIOP:: AP = 390, PST = 377, CUR = 450
,07-05 14:04:50.435   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:51.225  7387  7457 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-05 14:04:51.225  7387  7457 I jxcore-log: 
,07-05 14:04:51.225  7387  7457 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-05 14:04:51.225  7387  7457 I jxcore-log: 
,07-05 14:04:51.225   920  1662 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:51.235  7387  7457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:51.235  7387  7457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:51.235  7387  7457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 14:04:51.235  7387  7457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:51.235  7387  7457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:51.235  7387  7457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:04:51.235  7387  7457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:04:51.235  7387  7457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 14:04:51.235  7387  7457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-05 14:04:51.235  7387  7457 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-05 14:04:51.235  7387  7457 I jxcore-log: 
,07-05 14:04:51.235  7387  7457 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-05 14:04:51.235  7387  7457 I jxcore-log: 
,07-05 14:04:51.435   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:51.605  7387  7457 I jxcore-log: Unit Test app is loaded
07-05 14:04:51.605  7387  7457 I jxcore-log: 
,07-05 14:04:51.605  7387  7387 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-05 14:04:51.615  7387  7457 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-05 14:04:51.615  7387  7457 I jxcore-log: 
,07-05 14:04:51.615  7387  7457 I jxcore-log: My device name is: samsung-SM-N9005
07-05 14:04:51.615  7387  7457 I jxcore-log: 
,07-05 14:04:51.745   920  1520 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:04:51.745   920  1520 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:04:51.745   920  1520 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 14:04:51.745   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:04:51.745   920  1520 D BatteryService: stay LED for fully charged
,07-05 14:04:51.745  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:51.745   920   920 I MotionRecognitionService: Plugged
07-05 14:04:51.745   920   920 I MotionRecognitionService: setPowerConnected  = true
07-05 14:04:51.745  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:04:51.745  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:04:51.745  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:04:51.745  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:04:51.745  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:04:51.755  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:04:51.755  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:04:52.435   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 14:04:53.135   302   302 E SMD     : DCD ON
,07-05 14:04:55.405  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-05 14:04:55.405  7387  7457 I jxcore-log: 
,07-05 14:04:55.575   920  1340 E Watchdog: !@Sync 5
,07-05 14:04:55.795  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-05 14:04:55.795  7387  7457 I jxcore-log: 
,07-05 14:04:55.815  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-05 14:04:55.815  7387  7457 I jxcore-log: 
,07-05 14:04:55.825  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-05 14:04:55.825  7387  7457 I jxcore-log: 
,07-05 14:04:55.835  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-05 14:04:55.835  7387  7457 I jxcore-log: 
,07-05 14:04:55.845  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-05 14:04:55.845  7387  7457 I jxcore-log: 
,07-05 14:04:56.135   302   302 E SMD     : DCD ON
,07-05 14:04:57.725  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-05 14:04:57.725  7387  7457 I jxcore-log: 
,07-05 14:04:57.735  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-05 14:04:57.735  7387  7457 I jxcore-log: 
,07-05 14:04:57.745  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-05 14:04:57.745  7387  7457 I jxcore-log: 
,07-05 14:04:57.895  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-05 14:04:57.895  7387  7457 I jxcore-log: 
,07-05 14:04:57.975  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-05 14:04:57.975  7387  7457 I jxcore-log: 
,07-05 14:04:58.035  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-05 14:04:58.035  7387  7457 I jxcore-log: 
,07-05 14:04:58.045  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-05 14:04:58.045  7387  7457 I jxcore-log: 
,07-05 14:04:58.225  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-05 14:04:58.225  7387  7457 I jxcore-log: 
,07-05 14:04:58.245  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-05 14:04:58.245  7387  7457 I jxcore-log: 
,07-05 14:04:58.255  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-05 14:04:58.255  7387  7457 I jxcore-log: 
,07-05 14:04:58.255  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-05 14:04:58.255  7387  7457 I jxcore-log: 
,07-05 14:04:58.275  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-05 14:04:58.275  7387  7457 I jxcore-log: 
,07-05 14:04:58.295  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-05 14:04:58.295  7387  7457 I jxcore-log: 
,07-05 14:04:58.375  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-05 14:04:58.375  7387  7457 I jxcore-log: 
,07-05 14:04:58.385  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-05 14:04:58.385  7387  7457 I jxcore-log: 
,07-05 14:04:58.405  7387  7457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-05 14:04:58.405  7387  7457 I jxcore-log: 
,07-05 14:04:58.415  7387  7457 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-05 14:04:58.415  7387  7457 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-05 14:04:58.415  7387  7457 I jxcore-log: 
,07-05 14:04:59.135   302   302 E SMD     : DCD ON
,07-05 14:04:59.995   920  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:05:00.435   920  3072 D SSRM:n  : SIOP:: AP = 380, PST = 373, CUR = 450
,07-05 14:05:02.135   302   302 E SMD     : DCD ON
,07-05 14:05:02.185   920  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:05:02.235   920  1520 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:05:02.235   920  1236 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:05:02.235   920  1236 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:05:02.235   920  1236 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 14:05:02.235   920  1236 D BatteryService: stay LED for fully charged
,07-05 14:05:02.255  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:05:02.255  1198  1198 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:05:02.255   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:05:02.265   920   920 I MotionRecognitionService: Plugged
,07-05 14:05:02.265   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:05:02.265  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:05:02.265  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:05:02.275  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:05:02.275  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:02.285  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:05:02.285  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
07-05 14:05:02.285  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:02.285  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:02.295  1198  1198 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:05:02.295  1198  1198 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:05:02.325   920  1520 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-05 14:05:02.325   920  1520 D ActivityManager: caller:android.app.ApplicationThreadProxy@3d759d03, r.packageName :com.google.android.gms
,07-05 14:05:02.385  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:05:02.385  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:05:03.845   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:05:05.135   302   302 E SMD     : DCD ON
,07-05 14:05:08.135   302   302 E SMD     : DCD ON
,07-05 14:05:08.725   920  1059 I PowerManagerService: [PWL] Off : 140s ago
,07-05 14:05:10.495   920  3072 D SSRM:n  : SIOP:: AP = 360, PST = 371, CUR = 450
,07-05 14:05:11.145   302   302 E SMD     : DCD ON
,07-05 14:05:12.315   920  1662 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:12.315   920  1662 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:05:12.315   920  1662 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:05:12.315   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:05:12.315  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:05:12.315  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:05:12.315   920   920 I MotionRecognitionService: Plugged
,07-05 14:05:12.315   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:05:12.325  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:05:12.325  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:05:12.325  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:05:12.335   920  1662 D BatteryService: stay LED for fully charged
,07-05 14:05:12.335  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:12.335  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:05:12.335  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:12.445   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:13.455   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:14.145   302   302 E SMD     : DCD ON
,07-05 14:05:14.445   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:15.445   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:16.445   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:17.145   302   302 E SMD     : DCD ON
,07-05 14:05:17.455   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 14:05:20.145   302   302 E SMD     : DCD ON
,07-05 14:05:20.555   920  3072 D SSRM:n  : SIOP:: AP = 350, PST = 369, CUR = 450
,07-05 14:05:22.375   920   936 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:22.585   289   289 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6c01090
,07-05 14:05:22.585   289   289 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: R/W request received
07-05 14:05:22.585   289   289 I rmt_storage: wakelock acquired: 1, error no: 42
,07-05 14:05:22.595   289   651 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1228406016)
,07-05 14:05:22.675   289   651 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Bytes written = 1572864
,07-05 14:05:22.675   289   651 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Send response: res=0 err=0
07-05 14:05:22.675   289   651 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1228406016) wakelock released: 1, error no: 0
07-05 14:05:22.675   289   651 I rmt_storage: 
,07-05 14:05:22.675   289   289 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6c01090
,07-05 14:05:23.145   302   302 E SMD     : DCD ON
,07-05 14:05:23.845   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:05:25.575   920  1340 E Watchdog: !@Sync 6
,07-05 14:05:26.155   302   302 E SMD     : DCD ON
,07-05 14:05:29.145   302   302 E SMD     : DCD ON
,07-05 14:05:30.595   920  3072 D SSRM:n  : SIOP:: AP = 350, PST = 368, CUR = 450
,07-05 14:05:32.145   302   302 E SMD     : DCD ON
,07-05 14:05:32.435   920  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:35.145   302   302 E SMD     : DCD ON
,07-05 14:05:38.145   302   302 E SMD     : DCD ON
,07-05 14:05:40.665   920  3072 D SSRM:n  : SIOP:: AP = 350, PST = 367, CUR = 450
,07-05 14:05:41.145   302   302 E SMD     : DCD ON
,07-05 14:05:42.455   355   355 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 14:05:42.455   355   355 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 14:05:42.495   920  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:42.505   920  1144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:05:42.505   920  1144 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:05:42.505   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:05:42.515  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:05:42.515  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:05:42.525   920   920 I MotionRecognitionService: Plugged
,07-05 14:05:42.525   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:05:42.525  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:42.525  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:42.525  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:05:42.525  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:05:42.525  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:05:42.525   920  1144 D BatteryService: stay LED for fully charged
07-05 14:05:42.525  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:05:43.845   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:05:44.155   302   302 E SMD     : DCD ON
,07-05 14:05:47.165   302   302 E SMD     : DCD ON
,07-05 14:05:48.745   920  1059 I PowerManagerService: [PWL] Off : 180s ago
,07-05 14:05:50.155   302   302 E SMD     : DCD ON
,07-05 14:05:50.745   920  3072 D SSRM:n  : SIOP:: AP = 340, PST = 365, CUR = 450
,07-05 14:05:52.455   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:52.555   920  1706 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:53.165   302   302 E SMD     : DCD ON
,07-05 14:05:53.455   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:54.455   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:55.455   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:55.575   920  1340 E Watchdog: !@Sync 7
,07-05 14:05:56.155   302   302 E SMD     : DCD ON
,07-05 14:05:56.465   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:57.465   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 14:05:59.165   302   302 E SMD     : DCD ON
,07-05 14:05:59.995   920  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:06:00.835   920  3072 D SSRM:n  : SIOP:: AP = 340, PST = 359, CUR = 450
,07-05 14:06:02.155   302   302 E SMD     : DCD ON
,07-05 14:06:02.465   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:02.625   920  1464 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:02.625   920  1464 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:06:02.625   920  1464 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:06:02.635   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:06:02.635   920   920 I MotionRecognitionService: Plugged
,07-05 14:06:02.635   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:06:02.635  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:02.645  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:06:02.645  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:06:02.655  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:06:02.655  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:02.655   920  1464 D BatteryService: stay LED for fully charged
,07-05 14:06:02.655  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:06:02.655  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:02.655  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:03.465   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:03.845   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:06:04.475   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:05.165   302   302 E SMD     : DCD ON
,07-05 14:06:05.475   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:06.475   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:07.465   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 14:06:08.155   302   302 E SMD     : DCD ON
,07-05 14:06:10.895   920  3072 D SSRM:n  : SIOP:: AP = 340, PST = 357, CUR = 450
,07-05 14:06:11.165   302   302 E SMD     : DCD ON
,07-05 14:06:14.155   302   302 E SMD     : DCD ON
,07-05 14:06:17.155   302   302 E SMD     : DCD ON
,07-05 14:06:17.475   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:18.325   920  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:06:18.345  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:06:18.345  1198  1198 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:06:18.345  1198  1198 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:06:18.345  1198  1198 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:06:18.375   920   936 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:18.375   920   936 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:06:18.375   920   936 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:06:18.375   920   936 D BatteryService: stay LED for fully charged
07-05 14:06:18.375   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:06:18.385   920   920 I MotionRecognitionService: Plugged
,07-05 14:06:18.385   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:06:18.385  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:06:18.385  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:06:18.395  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:18.395  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:06:18.395  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:18.395  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:18.395  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:18.395  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:18.445  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:06:18.455  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:06:18.465   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:19.475   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:20.165   302   302 E SMD     : DCD ON
,07-05 14:06:20.465   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:20.945   920  3072 D SSRM:n  : SIOP:: AP = 340, PST = 354, CUR = 450
,07-05 14:06:21.475   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:22.475   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 14:06:23.165   302   302 E SMD     : DCD ON
,07-05 14:06:23.855   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:06:25.575   920  1340 E Watchdog: !@Sync 8
,07-05 14:06:26.165   302   302 E SMD     : DCD ON
,07-05 14:06:28.435   920  1706 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:28.435   920  1706 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:06:28.435   920  1706 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:06:28.435   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:06:28.445  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:28.455  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:28.455   920   920 I MotionRecognitionService: Plugged
,07-05 14:06:28.455   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:06:28.465   920  1706 D BatteryService: stay LED for fully charged
,07-05 14:06:28.475  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:06:28.485  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:06:28.485  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:06:28.495  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:28.495  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:28.495  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:29.175   302   302 E SMD     : DCD ON
,07-05 14:06:30.985   920  3072 D SSRM:n  : SIOP:: AP = 340, PST = 349, CUR = 450
,07-05 14:06:32.165   302   302 E SMD     : DCD ON
,07-05 14:06:33.745   920  1059 I PowerManagerService: [PWL] Off : 225s ago
,07-05 14:06:35.165   302   302 E SMD     : DCD ON
,07-05 14:06:37.475   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:38.165   302   302 E SMD     : DCD ON
,07-05 14:06:38.475   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:38.485   920  1236 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:38.495   920  1236 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:06:38.495   920  1236 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:06:38.495   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:06:38.505  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:38.505  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:38.505   920   920 I MotionRecognitionService: Plugged
,07-05 14:06:38.505   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:06:38.515   920  1236 D BatteryService: stay LED for fully charged
,07-05 14:06:38.515  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:06:38.525  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:38.525  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:38.525  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:06:38.525  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:06:38.525  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:39.485   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:40.475   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:41.035   920  3072 D SSRM:n  : SIOP:: AP = 340, PST = 345, CUR = 450
,07-05 14:06:41.175   302   302 E SMD     : DCD ON
,07-05 14:06:41.475   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:42.485   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 14:06:43.865   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:06:44.175   302   302 E SMD     : DCD ON
,07-05 14:06:47.165   302   302 E SMD     : DCD ON
,07-05 14:06:48.555   920  1706 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:50.175   302   302 E SMD     : DCD ON
,07-05 14:06:51.085   920  3072 D SSRM:n  : SIOP:: AP = 330, PST = 342, CUR = 450
,07-05 14:06:53.175   302   302 E SMD     : DCD ON
,07-05 14:06:55.595   920  1340 E Watchdog: !@Sync 9
,07-05 14:06:56.175   302   302 E SMD     : DCD ON
,07-05 14:06:58.605   920  1561 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:59.175   302   302 E SMD     : DCD ON
,07-05 14:06:59.995   920  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:07:01.135   920  3072 D SSRM:n  : SIOP:: AP = 330, PST = 340, CUR = 450
,07-05 14:07:02.175   302   302 E SMD     : DCD ON
,07-05 14:07:02.485   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:03.475   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:03.865   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:07:04.475   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:05.185   302   302 E SMD     : DCD ON
,07-05 14:07:05.485   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:06.485   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:07.485   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 14:07:08.185   302   302 E SMD     : DCD ON
,07-05 14:07:08.675   920  1520 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:08.675   920  1520 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:07:08.675   920  1520 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:07:08.675   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:07:08.685  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:07:08.685  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:07:08.695   920   920 I MotionRecognitionService: Plugged
,07-05 14:07:08.695   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:07:08.695   920  1520 D BatteryService: stay LED for fully charged
,07-05 14:07:08.705  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:07:08.715  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:08.715  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:08.715  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:07:08.725  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:07:08.725  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:11.175   302   302 E SMD     : DCD ON
,07-05 14:07:11.185   920  3072 D SSRM:n  : SIOP:: AP = 330, PST = 338, CUR = 450
,07-05 14:07:14.185   302   302 E SMD     : DCD ON
,07-05 14:07:17.175   302   302 E SMD     : DCD ON
,07-05 14:07:18.725   920  1445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:18.735   920  1445 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:07:18.735   920  1445 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:07:18.735   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:07:18.745  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:07:18.745  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:07:18.755   920   920 I MotionRecognitionService: Plugged
,07-05 14:07:18.755   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:07:18.755   920  1445 D BatteryService: stay LED for fully charged
,07-05 14:07:18.755  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:07:18.765  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:07:18.765  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:07:18.775  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:18.775  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:07:18.775  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:20.175   302   302 E SMD     : DCD ON
,07-05 14:07:21.225   920  3072 D SSRM:n  : SIOP:: AP = 330, PST = 336, CUR = 450
,07-05 14:07:23.035   920  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 14:07:23.035   920  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:07:23.045   920  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:07:23.055   920  1102 I TLC_TIMA_PKM_initialize: initializing...
,07-05 14:07:23.055   920  1102 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
07-05 14:07:23.055   920  1102 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,07-05 14:07:23.055   920  1102 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
07-05 14:07:23.055   920  1102 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,07-05 14:07:23.055   920  1102 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-05 14:07:23.065   920  1102 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,07-05 14:07:23.065   920  1102 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,07-05 14:07:23.065   920  1102 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-05 14:07:23.065   920  1102 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:07:23.105   920  1102 D QSEECOMAPI: : Loaded image: APP id = 2
,07-05 14:07:23.115   920  1102 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-05 14:07:23.125   920  1102 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-05 14:07:23.185   302   302 E SMD     : DCD ON
,07-05 14:07:23.745   920  1059 I PowerManagerService: [PWL] Off : 275s ago
,07-05 14:07:23.745   920  1059 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,07-05 14:07:23.745   920  1059 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,07-05 14:07:23.745   920  1059 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=920, ws=null) (elapsedTime=698)
,07-05 14:07:23.865   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:07:25.585   920  1340 E Watchdog: !@Sync 10
,07-05 14:07:26.005   920  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 14:07:26.005   920  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:07:26.025   920  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:07:26.035   920  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:07:26.195   302   302 E SMD     : DCD ON
,07-05 14:07:28.795   920  1520 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:28.795   920  1520 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:07:28.795   920  1520 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:07:28.795   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:07:28.805  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:07:28.805  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:07:28.805   920   920 I MotionRecognitionService: Plugged
,07-05 14:07:28.815   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:07:28.815   920  1520 D BatteryService: stay LED for fully charged
,07-05 14:07:28.825  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:07:28.835  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:28.835  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:28.835  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:07:28.835  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:07:28.845  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:29.185   302   302 E SMD     : DCD ON
,07-05 14:07:31.275   920  3072 D SSRM:n  : SIOP:: AP = 330, PST = 335, CUR = 450
,07-05 14:07:32.195   302   302 E SMD     : DCD ON
,07-05 14:07:32.485   355   355 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 14:07:32.485   355   355 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 14:07:35.185   302   302 E SMD     : DCD ON
,07-05 14:07:38.185   302   302 E SMD     : DCD ON
,07-05 14:07:41.195   302   302 E SMD     : DCD ON
,07-05 14:07:41.325   920  3072 D SSRM:n  : SIOP:: AP = 330, PST = 334, CUR = 450
,07-05 14:07:42.965   920  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:07:42.975   920  1007 D ActivityManager: startProcessLocked calleePkgName: com.blurb.checkout, hostingType: broadcast
,07-05 14:07:42.975   920  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:07:42.985   920  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:07:42.985   920  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:07:42.985   920  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:07:43.015   920  1561 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:43.055   920  1007 I ActivityManager: Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7535 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 14:07:43.055  7535  7535 E Zygote  : MountEmulatedStorage()
,07-05 14:07:43.055  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:07:43.075  7535  7535 E Zygote  : v2
,07-05 14:07:43.075  7535  7535 I libpersona: KNOX_SDCARD checking this for 10096
07-05 14:07:43.075  7535  7535 I libpersona: KNOX_SDCARD not a persona
,07-05 14:07:43.075  1198  1198 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:07:43.085  7535  7535 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 14:07:43.085  7535  7535 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 14:07:43.085  7535  7535 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-05 14:07:43.095  1198  1198 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-05 14:07:43.095  1198  1198 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:07:43.125  7535  7535 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:07:43.125  7535  7535 D ActivityThread: Added TimaKeyStore provider
,07-05 14:07:43.145  7535  7535 D ResourcesManager: creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,07-05 14:07:43.165  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:07:43.175   920  1623 D ActivityManager: startService callerProcessName:com.blurb.checkout, calleePkgName: com.blurb.checkout
,07-05 14:07:43.175   920  1623 D ActivityManager: caller:android.app.ApplicationThreadProxy@2974d975, r.packageName :com.blurb.checkout
,07-05 14:07:43.175  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:07:43.235   920  1445 I ActivityManager: Killing 6765:com.samsung.android.scloud.sync/u0a76 (adj 15): emptyCount ##41
,07-05 14:07:43.875   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:07:44.185   302   302 E SMD     : DCD ON
,07-05 14:07:47.195   302   302 E SMD     : DCD ON
,07-05 14:07:47.485   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:48.485   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:49.495   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:50.195   302   302 E SMD     : DCD ON
,07-05 14:07:50.495   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:51.375   920  3072 D SSRM:n  : SIOP:: AP = 330, PST = 333, CUR = 450
,07-05 14:07:51.485   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:52.495   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 14:07:53.085   920  1464 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:53.185   302   302 E SMD     : DCD ON
,07-05 14:07:55.595   920  1340 E Watchdog: !@Sync 11
,07-05 14:07:56.185   302   302 E SMD     : DCD ON
,07-05 14:07:57.495   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:58.505   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:59.195   302   302 E SMD     : DCD ON
,07-05 14:07:59.505   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:59.985   920  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:08:00.495   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:01.415   920  3072 D SSRM:n  : SIOP:: AP = 330, PST = 332, CUR = 450
,07-05 14:08:01.495   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:02.195   302   302 E SMD     : DCD ON
,07-05 14:08:02.505   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 14:08:03.145   920  1561 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:03.145   920  1561 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:08:03.145   920  1561 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 14:08:03.145   920  1561 D BatteryService: stay LED for fully charged
,07-05 14:08:03.145   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:08:03.145  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:08:03.145  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:08:03.155   920   920 I MotionRecognitionService: Plugged
,07-05 14:08:03.155   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:08:03.165  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:08:03.165  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:03.165  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:08:03.165  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
07-05 14:08:03.165  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:03.165  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:03.885   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:08:05.195   302   302 E SMD     : DCD ON
,07-05 14:08:08.205   302   302 E SMD     : DCD ON
,07-05 14:08:11.195   302   302 E SMD     : DCD ON
,07-05 14:08:11.465   920  3072 D SSRM:n  : SIOP:: AP = 330, PST = 331, CUR = 450
,07-05 14:08:12.495   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:13.205   920  1706 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:13.205   920  1706 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:08:13.205   920  1706 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:08:13.215   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:08:13.215  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:08:13.215  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:08:13.225   920   920 I MotionRecognitionService: Plugged
,07-05 14:08:13.225   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:08:13.225   920  1706 D BatteryService: stay LED for fully charged
,07-05 14:08:13.225  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:08:13.235  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:13.235  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:08:13.235  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:13.235  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:08:13.235  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:08:13.495   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:14.195   302   302 E SMD     : DCD ON
,07-05 14:08:14.505   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:15.505   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:16.505   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:17.205   302   302 E SMD     : DCD ON
,07-05 14:08:17.515   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 14:08:18.745   920  1059 I PowerManagerService: [PWL] Off : 330s ago
,07-05 14:08:20.195   302   302 E SMD     : DCD ON
,07-05 14:08:21.555   920  3072 D SSRM:n  : SIOP:: AP = 330, PST = 330, CUR = 450
,07-05 14:08:23.205   302   302 E SMD     : DCD ON
,07-05 14:08:23.265   920  1561 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:23.265   920  1561 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:08:23.265   920  1561 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 14:08:23.265   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:08:23.275  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:08:23.275  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:08:23.275   920   920 I MotionRecognitionService: Plugged
,07-05 14:08:23.275   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:08:23.285   920  1561 D BatteryService: stay LED for fully charged
,07-05 14:08:23.295  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:08:23.295  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:23.295  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:08:23.305  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:08:23.305  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:23.305  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:23.875   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:08:25.595   920  1340 E Watchdog: !@Sync 12
,07-05 14:08:26.205   302   302 E SMD     : DCD ON
,07-05 14:08:29.205   302   302 E SMD     : DCD ON
,07-05 14:08:31.605   920  3072 D SSRM:n  : SIOP:: AP = 330, PST = 330, CUR = 450
,07-05 14:08:32.215   302   302 E SMD     : DCD ON
,07-05 14:08:32.505   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:33.325   920  1706 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:33.505   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:34.515   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:35.205   302   302 E SMD     : DCD ON
,07-05 14:08:35.505   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:36.505   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:37.515   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 14:08:38.205   302   302 E SMD     : DCD ON
,07-05 14:08:41.205   302   302 E SMD     : DCD ON
,07-05 14:08:41.655   920  3072 D SSRM:n  : SIOP:: AP = 330, PST = 330, CUR = 450
,07-05 14:08:43.385   920  1445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:43.385   920  1445 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:08:43.385   920  1445 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:08:43.385   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:08:43.395  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:08:43.395  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:08:43.405   920   920 I MotionRecognitionService: Plugged
,07-05 14:08:43.405   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:08:43.405   920  1445 D BatteryService: stay LED for fully charged
,07-05 14:08:43.405  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:08:43.415  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:08:43.415  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:08:43.425  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:43.425  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:08:43.425  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:43.885   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:08:44.215   302   302 E SMD     : DCD ON
,07-05 14:08:47.215   302   302 E SMD     : DCD ON
,07-05 14:08:50.205   302   302 E SMD     : DCD ON
,07-05 14:08:51.705   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 329, CUR = 450
,07-05 14:08:53.205   302   302 E SMD     : DCD ON
,07-05 14:08:53.445   920  1662 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:53.445   920  1662 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:08:53.445   920  1662 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:08:53.445   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:08:53.455  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:08:53.455  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:08:53.465   920   920 I MotionRecognitionService: Plugged
,07-05 14:08:53.475   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:08:53.475   920  1662 D BatteryService: stay LED for fully charged
,07-05 14:08:53.475  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:08:53.485  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:53.485  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:08:53.485  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:53.485  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:08:53.485  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:08:55.595   920  1340 E Watchdog: !@Sync 13
,07-05 14:08:56.215   302   302 E SMD     : DCD ON
,07-05 14:08:57.515   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:58.525   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:59.215   302   302 E SMD     : DCD ON
,07-05 14:08:59.515   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:00.525   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:01.525   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:01.745   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 328, CUR = 450
,07-05 14:09:02.225   302   302 E SMD     : DCD ON
,07-05 14:09:02.525   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 14:09:03.505   920  1445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:03.505   920  1445 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:09:03.505   920  1445 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:09:03.515   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:09:03.515  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:09:03.515  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:09:03.525   920   920 I MotionRecognitionService: Plugged
,07-05 14:09:03.525   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:09:03.525   920  1445 D BatteryService: stay LED for fully charged
,07-05 14:09:03.535  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:09:03.545  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:09:03.545  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:09:03.545  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:03.545  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:09:03.545  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:03.885   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:09:05.215   302   302 E SMD     : DCD ON
,07-05 14:09:08.215   302   302 E SMD     : DCD ON
,07-05 14:09:11.225   302   302 E SMD     : DCD ON
,07-05 14:09:11.805   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 327, CUR = 450
,07-05 14:09:13.565   920  1662 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:13.575   920  1662 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:09:13.575   920  1662 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:09:13.575   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:09:13.585  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:09:13.585  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:09:13.595  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:09:13.595  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:09:13.595   920   920 I MotionRecognitionService: Plugged
,07-05 14:09:13.595   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:09:13.595  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:13.605   920  1662 D BatteryService: stay LED for fully charged
,07-05 14:09:13.605  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:13.605  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:13.605  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:09:14.215   302   302 E SMD     : DCD ON
,07-05 14:09:17.225   302   302 E SMD     : DCD ON
,07-05 14:09:18.755   920  1059 I PowerManagerService: [PWL] Off : 390s ago
,07-05 14:09:20.225   302   302 E SMD     : DCD ON
,07-05 14:09:21.855   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 326, CUR = 450
,07-05 14:09:23.215   302   302 E SMD     : DCD ON
,07-05 14:09:23.625   920  1445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:23.895   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:09:25.595   920  1340 E Watchdog: !@Sync 14
,07-05 14:09:26.225   302   302 E SMD     : DCD ON
,07-05 14:09:27.515   355   355 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 14:09:27.515   355   355 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 14:09:29.215   302   302 E SMD     : DCD ON
,07-05 14:09:31.905   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 325, CUR = 450
,07-05 14:09:32.225   302   302 E SMD     : DCD ON
,07-05 14:09:33.685   920   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:33.685   920   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:09:33.685   920   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:09:33.695   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:09:33.695  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:09:33.705  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:09:33.705   920   920 I MotionRecognitionService: Plugged
,07-05 14:09:33.705   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:09:33.705   920   935 D BatteryService: stay LED for fully charged
,07-05 14:09:33.715  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:09:33.735  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:33.735  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:33.735  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:09:33.735  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:09:33.745  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:35.215   302   302 E SMD     : DCD ON
,07-05 14:09:38.235   302   302 E SMD     : DCD ON
,07-05 14:09:41.235   302   302 E SMD     : DCD ON
,07-05 14:09:41.945   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 324, CUR = 450
,07-05 14:09:43.745   920  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:43.745   920  1359 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:09:43.745   920  1359 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:09:43.745   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:09:43.755  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:09:43.755  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:09:43.765   920   920 I MotionRecognitionService: Plugged
,07-05 14:09:43.765   920   920 I MotionRecognitionService: setPowerConnected  = true
07-05 14:09:43.765   920  1359 D BatteryService: stay LED for fully charged
,07-05 14:09:43.775  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:09:43.775  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:09:43.775  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:09:43.785  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:43.795  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:43.795  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:43.905   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:09:44.235   302   302 E SMD     : DCD ON
,07-05 14:09:47.225   302   302 E SMD     : DCD ON
,07-05 14:09:47.525   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:48.525   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:49.525   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:50.235   302   302 E SMD     : DCD ON
,07-05 14:09:50.525   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:51.535   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:51.995   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 323, CUR = 450
,07-05 14:09:52.525   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 14:09:53.225   302   302 E SMD     : DCD ON
,07-05 14:09:53.805   920  1706 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:53.805   920  1706 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:09:53.805   920  1706 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:09:53.815   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:09:53.815  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:09:53.815  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:09:53.825   920   920 I MotionRecognitionService: Plugged
,07-05 14:09:53.825   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:09:53.825   920  1706 D BatteryService: stay LED for fully charged
,07-05 14:09:53.835  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:09:53.845  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:09:53.845  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:09:53.855  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:53.855  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:53.855  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:55.605   920  1340 E Watchdog: !@Sync 15
,07-05 14:09:56.225   302   302 E SMD     : DCD ON
,07-05 14:09:57.535   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:58.525   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:59.235   302   302 E SMD     : DCD ON
,07-05 14:09:59.525   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:00.535   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:01.525   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:02.045   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 450
,07-05 14:10:02.225   302   302 E SMD     : DCD ON
,07-05 14:10:02.535   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 14:10:03.865   920  1561 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:10:03.875   920  1561 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:10:03.875   920  1561 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:10:03.875   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:10:03.885  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:10:03.885  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:10:03.895  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:10:03.895  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:10:03.895   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-05 14:10:03.895   920   920 I MotionRecognitionService: Plugged
,07-05 14:10:03.895   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:10:03.895  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:03.895  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:10:03.895  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:03.895   920  1561 D BatteryService: stay LED for fully charged
,07-05 14:10:03.905  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:10:05.235   302   302 E SMD     : DCD ON
,07-05 14:10:08.235   302   302 E SMD     : DCD ON
,07-05 14:10:11.235   302   302 E SMD     : DCD ON
,07-05 14:10:12.095   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 450
,07-05 14:10:12.535   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:13.535   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:13.815   351   351 I bootchecker: bootchecker wake up!!
,07-05 14:10:13.915   920  1706 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:10:14.235   302   302 E SMD     : DCD ON
,07-05 14:10:14.535   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:15.535   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:16.545   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:17.235   302   302 E SMD     : DCD ON
,07-05 14:10:17.535   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 14:10:20.235   302   302 E SMD     : DCD ON
,07-05 14:10:22.135   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:10:23.235   302   302 E SMD     : DCD ON
,07-05 14:10:23.755   920  1059 I PowerManagerService: [PWL] Off : 455s ago
,07-05 14:10:23.905   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:10:23.985   920  1445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:10:23.985   920  1445 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:10:23.985   920  1445 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:10:23.985   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:10:23.995  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:10:23.995  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:10:24.005   920   920 I MotionRecognitionService: Plugged
,07-05 14:10:24.005   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:10:24.015   920  1445 D BatteryService: stay LED for fully charged
,07-05 14:10:24.015  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:10:24.025  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:24.025  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:10:24.035  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:10:24.035  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:24.045  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:25.605   920  1340 E Watchdog: !@Sync 16
,07-05 14:10:26.235   302   302 E SMD     : DCD ON
,07-05 14:10:29.235   302   302 E SMD     : DCD ON
,07-05 14:10:32.185   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:10:32.235   302   302 E SMD     : DCD ON
,07-05 14:10:32.535   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:33.535   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:34.045   920  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:10:34.045   920  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:10:34.045   920  3816 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 14:10:34.045   920  3816 D BatteryService: stay LED for fully charged
,07-05 14:10:34.045   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:10:34.045  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:10:34.045  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:10:34.045   920   920 I MotionRecognitionService: Plugged
,07-05 14:10:34.045   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:10:34.055  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:10:34.055  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:34.065  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:10:34.065  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
07-05 14:10:34.065  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:34.065  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:34.535   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:35.245   302   302 E SMD     : DCD ON
,07-05 14:10:35.545   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:36.555   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:37.545   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 14:10:38.245   302   302 E SMD     : DCD ON
,07-05 14:10:41.235   302   302 E SMD     : DCD ON
,07-05 14:10:42.235   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:10:43.905   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:10:44.095   920  1445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:10:44.235   302   302 E SMD     : DCD ON
,07-05 14:10:47.245   302   302 E SMD     : DCD ON
,07-05 14:10:50.245   302   302 E SMD     : DCD ON
,07-05 14:10:52.325   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:10:53.255   302   302 E SMD     : DCD ON
,07-05 14:10:54.155   920   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:10:54.155   920   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:10:54.165   920   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:10:54.165   920   935 D BatteryService: stay LED for fully charged
,07-05 14:10:54.165   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:10:54.165  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:10:54.175  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:10:54.175  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:10:54.175  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:10:54.175  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:10:54.175  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:54.175  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:10:54.175  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 14:10:54.185   920   920 I MotionRecognitionService: Plugged
07-05 14:10:54.185   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:10:55.605   920  1340 E Watchdog: !@Sync 17
,07-05 14:10:56.255   302   302 E SMD     : DCD ON
,07-05 14:10:57.555   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:58.555   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:59.245   302   302 E SMD     : DCD ON
,07-05 14:10:59.555   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:11:00.545   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:11:01.555   355   355 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:11:02.245   302   302 E SMD     : DCD ON
,07-05 14:11:02.375   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:11:02.545   355   355 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 14:11:03.905   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:11:04.215   920  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:11:04.225   920  1359 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:11:04.225   920  1359 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 14:11:04.225   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:11:04.225   920   920 I MotionRecognitionService: Plugged
,07-05 14:11:04.225  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:11:04.225  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:11:04.225   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:11:04.235  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:11:04.235   920  1359 D BatteryService: stay LED for fully charged
,07-05 14:11:04.235  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:11:04.235  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:11:04.245  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:04.245  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:04.255  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:05.245   302   302 E SMD     : DCD ON
,07-05 14:11:08.255   302   302 E SMD     : DCD ON
,07-05 14:11:11.255   302   302 E SMD     : DCD ON
,07-05 14:11:12.425   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:11:14.245   302   302 E SMD     : DCD ON
,07-05 14:11:14.275   920   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:11:14.275   920   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:11:14.285   920   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 14:11:14.285   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:11:14.285   920   920 I MotionRecognitionService: Plugged
,07-05 14:11:14.285   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:11:14.285  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:11:14.295  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:11:14.295  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:11:14.295  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:11:14.295  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:11:14.295  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:14.295   920   935 D BatteryService: stay LED for fully charged
,07-05 14:11:14.305  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:14.305  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:17.255   302   302 E SMD     : DCD ON
,07-05 14:11:20.255   302   302 E SMD     : DCD ON
,07-05 14:11:22.475   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:11:23.245   302   302 E SMD     : DCD ON
,07-05 14:11:23.925   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:11:24.335   920  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:11:24.345   920  1359 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:11:24.345   920  1359 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 14:11:24.345   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:11:24.345  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:11:24.345  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:11:24.345   920   920 I MotionRecognitionService: Plugged
07-05 14:11:24.345   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:11:24.355  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:11:24.355   920  1359 D BatteryService: stay LED for fully charged
,07-05 14:11:24.355  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:24.355  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:24.365  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:11:24.365  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
07-05 14:11:24.365  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:25.605   920  1340 E Watchdog: !@Sync 18
,07-05 14:11:26.255   302   302 E SMD     : DCD ON
,07-05 14:11:27.545   355   355 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 14:11:27.545   355   355 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 14:11:29.265   302   302 E SMD     : DCD ON
,07-05 14:11:32.255   302   302 E SMD     : DCD ON
,07-05 14:11:32.525   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:11:33.765   920  1059 I PowerManagerService: [PWL] Off : 525s ago
,07-05 14:11:34.395   920  1520 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:11:34.395   920  1520 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:11:34.395   920  1520 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:11:34.405   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:11:34.405   920   920 I MotionRecognitionService: Plugged
,07-05 14:11:34.405   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:11:34.405  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:11:34.415  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:11:34.415  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:11:34.415  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:11:34.415  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:11:34.415  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:11:34.415   920  1520 D BatteryService: stay LED for fully charged
,07-05 14:11:34.415  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:34.425  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:35.255   302   302 E SMD     : DCD ON
,07-05 14:11:38.255   302   302 E SMD     : DCD ON
,07-05 14:11:41.255   302   302 E SMD     : DCD ON
,07-05 14:11:42.565   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:11:43.925   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:11:44.255   302   302 E SMD     : DCD ON
,07-05 14:11:44.445   920  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:11:47.255   302   302 E SMD     : DCD ON
,07-05 14:11:50.255   302   302 E SMD     : DCD ON
,07-05 14:11:52.565   355   355 I Atfwd_Daemon: Stop the daemon....
,07-05 14:11:52.655   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:11:53.255   302   302 E SMD     : DCD ON
,07-05 14:11:54.505   920  1236 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:11:54.515   920  1236 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:11:54.515   920  1236 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:11:54.515   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:11:54.525  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:11:54.525  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:11:54.525   920   920 I MotionRecognitionService: Plugged
,07-05 14:11:54.535   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:11:54.535  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:54.535  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:11:54.535  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:54.535   920  1236 D BatteryService: stay LED for fully charged
07-05 14:11:54.535  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:11:54.535  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:11:54.535  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:11:55.625   920  1340 E Watchdog: !@Sync 19
,07-05 14:11:56.265   302   302 E SMD     : DCD ON
,07-05 14:11:59.255   302   302 E SMD     : DCD ON
,07-05 14:12:02.265   302   302 E SMD     : DCD ON
,07-05 14:12:02.705   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:12:03.925   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:12:04.565   920  1464 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:12:04.565   920  1464 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:12:04.565   920  1464 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:12:04.565   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:12:04.575  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:12:04.575   920   920 I MotionRecognitionService: Plugged
,07-05 14:12:04.575  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:12:04.585   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:12:04.585   920  1464 D BatteryService: stay LED for fully charged
,07-05 14:12:04.585  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:12:04.595  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:04.595  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:12:04.595  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:12:04.605  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:04.605  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:05.275   302   302 E SMD     : DCD ON
,07-05 14:12:08.265   302   302 E SMD     : DCD ON
,07-05 14:12:11.275   302   302 E SMD     : DCD ON
,07-05 14:12:12.755   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:12:14.265   302   302 E SMD     : DCD ON
,07-05 14:12:14.625   920   936 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:12:14.625   920   936 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:12:14.625   920   936 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:12:14.625   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:12:14.635  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:12:14.635  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:12:14.645   920   920 I MotionRecognitionService: Plugged
,07-05 14:12:14.645   920   920 I MotionRecognitionService: setPowerConnected  = true
07-05 14:12:14.645   920   936 D BatteryService: stay LED for fully charged
,07-05 14:12:14.645  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:12:14.655  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:12:14.655  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:12:14.665  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:14.665  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:12:14.665  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:17.265   302   302 E SMD     : DCD ON
,07-05 14:12:20.265   302   302 E SMD     : DCD ON
,07-05 14:12:22.805   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:12:23.035   920  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 14:12:23.035   920  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
07-05 14:12:23.035   920  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:12:23.265   302   302 E SMD     : DCD ON
,07-05 14:12:23.925   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:12:24.685   920  1464 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:12:25.615   920  1340 E Watchdog: !@Sync 20
,07-05 14:12:25.925   920  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 14:12:25.925   920  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:12:25.935   920  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:12:25.945   920  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:12:26.265   302   302 E SMD     : DCD ON
,07-05 14:12:29.275   302   302 E SMD     : DCD ON
,07-05 14:12:32.275   302   302 E SMD     : DCD ON
,07-05 14:12:32.845   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:12:34.745   920  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:12:34.745   920  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:12:34.755   920  1623 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:12:34.755   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:12:34.765  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:12:34.765  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:12:34.765   920   920 I MotionRecognitionService: Plugged
,07-05 14:12:34.765   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:12:34.765   920  1623 D BatteryService: stay LED for fully charged
,07-05 14:12:34.775  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:12:34.795  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:12:34.795  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:12:34.805  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:34.805  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:34.805  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:35.265   302   302 E SMD     : DCD ON
,07-05 14:12:38.275   302   302 E SMD     : DCD ON
,07-05 14:12:41.275   302   302 E SMD     : DCD ON
,07-05 14:12:42.895   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:12:43.925   920  3107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:12:44.275   302   302 E SMD     : DCD ON
,07-05 14:12:44.805   920  1706 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:12:44.805   920  1706 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:12:44.805   920  1706 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:12:44.815   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:12:44.815  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:12:44.825  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:12:44.825   920   920 I MotionRecognitionService: Plugged
,07-05 14:12:44.825   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:12:44.825   920  1706 D BatteryService: stay LED for fully charged
,07-05 14:12:44.835  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:12:44.845  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:44.845  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:12:44.845  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:12:44.865  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:44.865  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:47.285   302   302 E SMD     : DCD ON
,07-05 14:12:48.755   920  1059 I PowerManagerService: [PWL] Off : 600s ago
,07-05 14:12:50.275   302   302 E SMD     : DCD ON
,07-05 14:12:52.955   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:12:53.275   302   302 E SMD     : DCD ON
,07-05 14:12:54.865   920  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:12:55.625   920  1340 E Watchdog: !@Sync 21
,07-05 14:12:56.285   302   302 E SMD     : DCD ON
,07-05 14:12:59.275   302   302 E SMD     : DCD ON
,07-05 14:13:02.285   302   302 E SMD     : DCD ON
,07-05 14:13:03.005   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:13:04.925   920  1662 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:13:04.925   920  1662 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:13:04.925   920  1662 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:13:04.925   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:13:04.935  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:13:04.945  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:13:04.945   920   920 I MotionRecognitionService: Plugged
07-05 14:13:04.945   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:13:04.945   920  1662 D BatteryService: stay LED for fully charged
,07-05 14:13:04.945  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:13:04.955  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:13:04.955  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:13:04.965  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:04.965  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:13:04.965  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:05.275   302   302 E SMD     : DCD ON
,07-05 14:13:08.275   302   302 E SMD     : DCD ON
,07-05 14:13:11.275   302   302 E SMD     : DCD ON
,07-05 14:13:13.055   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 14:13:14.275   302   302 E SMD     : DCD ON
,07-05 14:13:14.985   920  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:13:17.285   302   302 E SMD     : DCD ON
,07-05 14:13:20.285   302   302 E SMD     : DCD ON
,07-05 14:13:23.095   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 450
,07-05 14:13:23.285   302   302 E SMD     : DCD ON
,07-05 14:13:25.045   920  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:13:25.045   920  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:13:25.045   920  3816 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:13:25.055   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:13:25.055  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:13:25.065  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:13:25.065   920   920 I MotionRecognitionService: Plugged
,07-05 14:13:25.065   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:13:25.065   920  3816 D BatteryService: stay LED for fully charged
,07-05 14:13:25.075  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:13:25.085  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:25.085  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:13:25.085  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:13:25.105  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:25.105  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:25.625   920  1340 E Watchdog: !@Sync 22
,07-05 14:13:26.295   302   302 E SMD     : DCD ON
,07-05 14:13:29.295   302   302 E SMD     : DCD ON
,07-05 14:13:32.285   302   302 E SMD     : DCD ON
,07-05 14:13:33.145   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 318, CUR = 450
,07-05 14:13:35.105   920  1445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:13:35.105   920  1445 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:13:35.105   920  1445 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:13:35.105   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:13:35.115  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:13:35.115  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:13:35.115   920   920 I MotionRecognitionService: Plugged
,07-05 14:13:35.125   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:13:35.125   920  1445 D BatteryService: stay LED for fully charged
,07-05 14:13:35.125  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:13:35.135  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:13:35.135  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:13:35.145  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:35.145  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:13:35.145  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:35.295   302   302 E SMD     : DCD ON
,07-05 14:13:38.295   302   302 E SMD     : DCD ON
,07-05 14:13:41.285   302   302 E SMD     : DCD ON
,07-05 14:13:43.195   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 450
,07-05 14:13:44.285   302   302 E SMD     : DCD ON
,07-05 14:13:45.165   920  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:13:47.295   302   302 E SMD     : DCD ON
,07-05 14:13:50.295   302   302 E SMD     : DCD ON
,07-05 14:13:53.245   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 450
,07-05 14:13:53.305   302   302 E SMD     : DCD ON
,07-05 14:13:55.225   920  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:13:55.225   920  1359 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:13:55.225   920  1359 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:13:55.225   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:13:55.235  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:13:55.235  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:13:55.235   920   920 I MotionRecognitionService: Plugged
,07-05 14:13:55.245   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:13:55.245   920  1359 D BatteryService: stay LED for fully charged
,07-05 14:13:55.245  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:13:55.255  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:13:55.255  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:13:55.265  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:55.265  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:13:55.265  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:55.625   920  1340 E Watchdog: !@Sync 23
,07-05 14:13:56.305   302   302 E SMD     : DCD ON
,07-05 14:13:59.295   302   302 E SMD     : DCD ON
,07-05 14:14:02.295   302   302 E SMD     : DCD ON
,07-05 14:14:03.285   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 450
,07-05 14:14:05.285   920   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:14:05.295   920   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:14:05.295   920   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:14:05.295   302   302 E SMD     : DCD ON
,07-05 14:14:05.295   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:14:05.305  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:14:05.305  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:14:05.305   920   920 I MotionRecognitionService: Plugged
07-05 14:14:05.305   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:14:05.315  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:14:05.315  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:05.315  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:14:05.315  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:14:05.315  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:14:05.315   920   935 D BatteryService: stay LED for fully charged
,07-05 14:14:05.315  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:08.305   302   302 E SMD     : DCD ON
,07-05 14:14:08.775   920  1059 I PowerManagerService: [PWL] Off : 680s ago
,07-05 14:14:11.295   302   302 E SMD     : DCD ON
,07-05 14:14:13.335   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 450
,07-05 14:14:14.305   302   302 E SMD     : DCD ON
,07-05 14:14:15.345   920  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:14:15.345   920  1359 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:14:15.345   920  1359 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:14:15.345   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:14:15.355  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:14:15.355  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:14:15.355   920   920 I MotionRecognitionService: Plugged
,07-05 14:14:15.365   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:14:15.365   920  1359 D BatteryService: stay LED for fully charged
,07-05 14:14:15.365  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:14:15.375  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:14:15.375  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:14:15.385  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:15.385  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:14:15.385  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:17.305   302   302 E SMD     : DCD ON
,07-05 14:14:20.295   302   302 E SMD     : DCD ON
,07-05 14:14:23.305   302   302 E SMD     : DCD ON,
,07-05 14:14:23.425   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 450
,07-05 14:14:25.395   920  2038 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:14:25.635   920  1340 E Watchdog: !@Sync 24
,07-05 14:14:26.305   302   302 E SMD     : DCD ON
,07-05 14:14:29.305   302   302 E SMD     : DCD ON
,07-05 14:14:32.315   302   302 E SMD     : DCD ON
,07-05 14:14:33.055   920  1122 D InputReader: Input event: value=1
,07-05 14:14:33.055   920  1122 D InputReader: !@notifyKey(172), action=0
,07-05 14:14:33.055   920  1122 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=0
,07-05 14:14:33.055   920  1122 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 920  pkgName : WAKEUP_BOOSTER@32
,07-05 14:14:33.055   920  1122 E SamsungWindowManager: mCoreNumLockHelper.acquire
,07-05 14:14:33.065   920  1122 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 920) eventTime = 746080 event = 1
,07-05 14:14:33.065   920  1122 I PowerManagerService: !@[ps] Screen__On  - 1 :  wakeUpWithReason: 1 (uid: 1000 pid: 920)
,07-05 14:14:33.065   920  1122 I PowerManagerService: Waking up from sleep (uid 1000)...
07-05 14:14:33.065   920  1122 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
07-05 14:14:33.065   920  1122 D PowerManagerService: [s] UserActivityState : 0 -> 1
,07-05 14:14:33.065   920  1172 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@22bb7d71)
07-05 14:14:33.065   920  1122 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
07-05 14:14:33.065   920  1122 D InputManager-JNI: !@handleInterceptActions(172), action=0, wmActions=0
07-05 14:14:33.065   920  1122 D InputManager-JNI: Disable repeat for home key when device wake up
07-05 14:14:33.065   920  1059 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-05 14:14:33.065   920  1047 D SContextService: 	.registerCallback : 1, client=
07-05 14:14:33.065  1198  1219 D KeyguardViewMediator: onScreenTurnedOn, seq = 3
07-05 14:14:33.065   920  1047 W CAE     : setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
07-05 14:14:33.065  1198  1219 D KeyguardViewMediator: notifyScreenOnLocked
07-05 14:14:33.065   920  1047 I CAE     : setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,07-05 14:14:33.065  1198  1198 D KeyguardViewMediator: handleNotifyScreenOn
07-05 14:14:33.065   920  1059 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-05 14:14:33.065   920  1059 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 14:14:33.065  1198  1198 D StatusBarKeyguardViewManager: onScreenTurnedOn()
07-05 14:14:33.065  1198  1198 D KeyguardViewBase: screen on, instance 2e920e4e
07-05 14:14:33.065   920  1177 D PowerManagerService: !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
,07-05 14:14:33.065   920  1177 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
07-05 14:14:33.065   920  1177 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
,07-05 14:14:33.065   920  1177 I QCOM PowerHAL: Got set_interactive hint
,07-05 14:14:33.075   920  1047 I CAE     : setCAProperty(ContextAwareService.java:469) - result : true
07-05 14:14:33.075   920  1047 W CAE     : setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
07-05 14:14:33.075   920  1047 D SContextService: sendAttribute() : service = Auto Rotation
07-05 14:14:33.075  1198  1198 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
07-05 14:14:33.075  1198  1198 D KeyguardSecurityView: showSecurityScreen(None)
07-05 14:14:33.075  1198  1198 D KeyguardUnlockView: outRect: Rect(0, 99 - 1080, 1920)
,07-05 14:14:33.075  1198  1198 D KeyguardUnlockView: isValidRect: true
07-05 14:14:33.075  1198  1198 I WaterColor Keyguard: showUnlockAffordance
07-05 14:14:33.075   920  1047 W CAE     : registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
07-05 14:14:33.075  1198  1198 D VisualEffectCircleUnlockEffect: KeyguardEffectViewNone : screenTurnedOn
07-05 14:14:33.075   920  1047 V CAE     : start(ContextProvider.java:126)
07-05 14:14:33.075  1198  1198 I WaterColor Keyguard: screenTurnedOn
07-05 14:14:33.075  1198  1198 D SecKeyguardCircleView: onScreenTurnedOn
,07-05 14:14:33.075  1198  1542 D TEST    : run!!!
07-05 14:14:33.075  1198  1542 I WaterColorEffect_View: showAffordanceEffect
07-05 14:14:33.075  1198  1542 I WaterColor_Renderer: clearEffect()
07-05 14:14:33.075   920  1047 V CAE     : clear(AutoRotationRunner.java:182)
07-05 14:14:33.075   920  1047 V CAE     : enable(AutoRotationRunner.java:158)
,07-05 14:14:33.075   920  1047 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
07-05 14:14:33.075   920  1047 D SensorHubManager: SendSensorHubData: send data = -79, 7, 0, 0
,07-05 14:14:33.075   920  1236 E Sensors : Acc old sensor_state 8192, new sensor_state : 8193 en : 1
,07-05 14:14:33.075   266   266 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6962000
,07-05 14:14:33.075   266   266 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-05 14:14:33.085   317   317 D Sensorhubs: sendContextData: -79, 7, 0, 0
,07-05 14:14:33.085   920  1057 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,07-05 14:14:33.085   920   920 V ActivityManager: Display changed displayId=0
,07-05 14:14:33.085   920  1172 D InputManager-JNI: setDeviceInteractive: 1
,07-05 14:14:33.095  1198  1542 I WaterColor_Renderer: dirty mode
,07-05 14:14:33.095   920  7601 D InputManager-JNI: sysfs_write +: /sys/class/input/event4/device/enabled: 1
,07-05 14:14:33.105  1198  1198 D SensorManager: registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
,07-05 14:14:33.105   920  7603 D InputManager-JNI: sysfs_write +: /sys/class/input/event2/device/enabled: 1
,07-05 14:14:33.105   920  1047 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
07-05 14:14:33.105   920  1047 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,07-05 14:14:33.105   920  7602 D InputManager-JNI: sysfs_write +: /sys/class/input/event3/device/enabled: 1
07-05 14:14:33.105   920  7602 D InputManager-JNI: sysfs_write -: /sys/class/input/event3/device/enabled: 1
,07-05 14:14:33.115  1198  1198 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
,07-05 14:14:33.115  1198  1198 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1845 should be AT_MOST
,07-05 14:14:33.125   920  1464 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,07-05 14:14:33.125  1198  1198 D StatusBarKeyguardViewManager: callback.onShown()
07-05 14:14:33.125  1198  1198 D KeyguardViewMediator: handleKeyguardDoneDrawing
,07-05 14:14:33.155  1198  1198 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
,07-05 14:14:33.155   920   920 D LightsService: [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 920) 
,07-05 14:14:33.155  1198  1198 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1845 should be AT_MOST
,07-05 14:14:33.155   920  1047 D CAE     : doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
07-05 14:14:33.155   920   920 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
07-05 14:14:33.155   920  1093 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
07-05 14:14:33.155   920  1093 D lights  : led_pattern : 0 +
,07-05 14:14:33.155   920  1093 D lights  : led_pattern : 0 -
07-05 14:14:33.155   920  1093 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
07-05 14:14:33.155   920   920 D BatteryService: turn off LED
07-05 14:14:33.155   920  1047 I CAE     : displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
07-05 14:14:33.165   920  1047 D CAE     : showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,07-05 14:14:33.165   920  1047 I CAE     : showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@3474d398, Service : AUTO_ROTATION(1)
07-05 14:14:33.165   920  1047 W CAE     : registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
07-05 14:14:33.165   920  1047 D SContextService: addSContextService() : service = Auto Rotation
07-05 14:14:33.165   920  1047 D SContextService: ===== SContext Service List =====
07-05 14:14:33.165   920  1047 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@2dc697f1, Service : Auto Rotation
07-05 14:14:33.165   920  1047 D SContextManager:   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@20730756, service=Auto Rotation
,07-05 14:14:33.165   920   920 I CAE     : handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,07-05 14:14:33.165   920   920 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
07-05 14:14:33.165   920   920 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
07-05 14:14:33.165   920   920 D SensorHubManager: SendSensorHubData: send data = -76, 13, -47, 0
07-05 14:14:33.165   317   560 D Sensorhubs: sendContextData: -76, 13, -47, 0
,07-05 14:14:33.175   920   920 D InputMethodManagerService: [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,07-05 14:14:33.175   920   920 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
,07-05 14:14:33.175  1198  1198 D QSpanel : label top:23
07-05 14:14:33.175  1198  1198 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-05 14:14:33.175  1198  1198 D QSpanel : label top:23
07-05 14:14:33.175  1198  1198 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-05 14:14:33.175  1198  1198 D QSpanel : label top:23
07-05 14:14:33.175  1198  1198 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-05 14:14:33.175  1198  1198 D QSpanel : label top:0
07-05 14:14:33.175  1198  1198 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-05 14:14:33.175  1198  1198 D QSpanel : label top:23
07-05 14:14:33.175  1198  1198 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-05 14:14:33.175  1198  1198 D QSpanel : label top:0
07-05 14:14:33.175  1198  1198 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-05 14:14:33.175  1198  1198 D QSpanel : label top:0
07-05 14:14:33.175  1198  1198 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-05 14:14:33.175  1198  1198 D QSpanel : label top:0
07-05 14:14:33.175  1198  1198 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-05 14:14:33.175  1198  1198 D QSpanel : label top:0
07-05 14:14:33.175  1198  1198 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-05 14:14:33.175  1198  1198 D QSpanel : label top:0
07-05 14:14:33.175  1198  1198 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-05 14:14:33.175   920  1126 E MotionRecognitionService:  handler : SCREEN_ON end
,07-05 14:14:33.175   920   920 D NotificationService: ACTION_SCREEN_ON
07-05 14:14:33.175   920   920 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 920) 
07-05 14:14:33.175   920   920 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,07-05 14:14:33.175   920  1093 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
07-05 14:14:33.175   920  1093 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-05 14:14:33.185   308   657 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-05 14:14:33.185   308   657 V voice   : voice_set_parameters: enter: screen_state=on
07-05 14:14:33.185   308   657 V voice   : voice_set_parameters: exit with code(-2)
07-05 14:14:33.185   308   657 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-05 14:14:33.185   308   657 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-05 14:14:33.185   308   657 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-05 14:14:33.185   308   657 V audio_hw_primary: adev_set_parameters: exit
,07-05 14:14:33.185   920   920 I SecExternalDisplayIntents_Java: Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,07-05 14:14:33.195   920  1149 E native  : do suspend false
,07-05 14:14:33.195  1289  1289 I wpa_supplicant: reset timer : RESET_TIMER 1
07-05 14:14:33.195  1289  1289 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-05 14:14:33.195  1289  1289 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-05 14:14:33.205  1289  1289 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-05 14:14:33.205   920  1059 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-05 14:14:33.205   920  1059 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:14:33.205   920  7601 D InputManager-JNI: sysfs_write -: /sys/class/input/event4/device/enabled: 1
,07-05 14:14:33.245   920  1122 D InputReader: Input event: value=0
07-05 14:14:33.245   920  1122 D InputReader: !@notifyKey(172), action=1
07-05 14:14:33.245   920  1122 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=1
,07-05 14:14:33.245   920  1122 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 920  tag : WAKEUP_BOOSTER@32
,07-05 14:14:33.245   920  1122 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 920  pkgName : WAKEUP_BOOSTER@32
07-05 14:14:33.245   920  1122 E SamsungWindowManager: mCoreNumLockHelper.acquire
,07-05 14:14:33.245   920  1122 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 920) eventTime = 746270 event = 1
07-05 14:14:33.245   920  1122 D InputManager-JNI: !@handleInterceptActions(172), action=1, wmActions=1
,07-05 14:14:33.255   920  1121 D VoIPInterfaceManager: isVoIPRinging()...
,07-05 14:14:33.255   920  1121 D VoIPInterfaceManager: isVoIPRunningAndDeregi()...
07-05 14:14:33.255   920  1121 D VoIPInterfaceManager: Not exist call session
,07-05 14:14:33.255   920  1121 D PersonaManager: isKioskContainerExistOnDevice
,07-05 14:14:33.315   266   509 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,07-05 14:14:33.315   266   266 E qdexternal: writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
07-05 14:14:33.315   266   266 D qdhwcomposer: hwc_blank: Done unblanking display: 0
07-05 14:14:33.315   920  1177 D SurfaceControl: Excessive delay in setPowerMode(): 248ms
07-05 14:14:33.315   920  1177 D PowerManagerService: Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 252ms
07-05 14:14:33.315   920  1057 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
,07-05 14:14:33.315  1198  1198 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 8 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x3 gsm|lte level=3
07-05 14:14:33.315   920  1057 D IpRemoteDisplayController: Bridge Server is not available
07-05 14:14:33.315  1198  1198 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 8 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x3 gsm|lte
07-05 14:14:33.315  1198  1198 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=3
07-05 14:14:33.315  1198  1198 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_3 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_3 mContentDescriptionPhoneSignal = Three bars of phone signal
07-05 14:14:33.315  1198  1198 D StatusBar.NetworkController: refreshViews connected={ wifi } level=3 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId=0x7f020134/com.android.systemui:drawable/ic_qs_signal_3 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 14:14:33.315  1198  1198 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 14:14:33.315  1198  1198 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 8 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x3 gsm|lte level=3
07-05 14:14:33.315  1198  1198 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 8 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x3 gsm|lte
07-05 14:14:33.315  1198  1198 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=3
07-05 14:14:33.315  1198  1198 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_3 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_3 mContentDescriptionPhoneSignal = Three bars of phone signal
,07-05 14:14:33.325  1198  1198 D StatusBar.NetworkController: refreshViews connected={ wifi } level=3 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId=0x7f020134/com.android.systemui:drawable/ic_qs_signal_3 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 14:14:33.325  1198  1198 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 14:14:33.325  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 14:14:33.325   920  1047 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
07-05 14:14:33.325   920  1059 I DisplayPowerController: Unblocked screen on after 261 ms
07-05 14:14:33.325   920  1059 D DisplayPowerState: !@ ColorFade exit
07-05 14:14:33.325  1198  1198 D KeyguardViewMediator: handleKeyguardDoneDrawing
07-05 14:14:33.325  1198  1198 D StatusBar.NetworkController: refreshViews connected={ wifi } level=3 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId=0x7f020134/com.android.systemui:drawable/ic_qs_signal_3 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 14:14:33.325  1198  1198 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 14:14:33.325  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:33.325  1198  1198 D StatusBar.NetworkController: applyOpen
07-05 14:14:33.335  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:33.335  1198  1198 D StatusBar.NetworkController: applyOpen
07-05 14:14:33.335  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:33.335  1198  1198 D StatusBar.NetworkController: applyOpen
07-05 14:14:33.335  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:33.335  1198  1198 D StatusBar.NetworkController: applyOpen
07-05 14:14:33.335   266   344 I SurfaceFlinger: id=10 Removed DolorFade (8/8)
07-05 14:14:33.335  1198  1198 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 14:14:33.335  1198  1198 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-05 14:14:33.345  1198  1198 I KeyguardEffectViewController: *** don't update sliding image ***
07-05 14:14:33.345   920  1003 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
07-05 14:14:33.345   920   920 D PersonaManagerService: ACTION_SCREEN_ON onReceive
07-05 14:14:33.345   920  1067 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
07-05 14:14:33.345   266  1063 I SurfaceFlinger: id=10 Removed DolorFade (-2/8)
07-05 14:14:33.355   920  1059 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-05 14:14:33.355   920  1059 D DisplayPowerController: getFinalBrightness : 255 -> 255
,07-05 14:14:33.355   920  1059 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 14:14:33.355   920  1176 D lights  : lcd : 255 +
07-05 14:14:33.355  1415  1415 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_LOCKED by isKeyguardLocked()
07-05 14:14:33.355  1415  1415 D NativeNfcManager: power state=3
07-05 14:14:33.365  1415  7610 D NfcService: call the applyRouting
07-05 14:14:33.365  1819  1819 D accuweather: [Accuweather J]>>> SWW:67 [0:0] =============== BR act = androidintentactionSCREEN_ON
07-05 14:14:33.365  1819  1819 D accuweather: [Accuweather J]>>> SWW:70 [0:0] =============== androidintentactionSCREEN_ON instance : [0]1
07-05 14:14:33.375   920  1176 D lights  : lcd : 255 -
07-05 14:14:33.375   920  1059 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-05 14:14:33.375   920  1059 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 14:14:33.375   920  1059 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 14:14:33.375   920  1059 D PowerManagerService: SecHardwareInterface.setBatteryADC : true
07-05 14:14:33.375   920  1059 D PowerManagerService: [input device light] setInputDeviceLightOn is called : 1
07-05 14:14:33.375   920  1173 D PowerManagerService: [input device light] handleInputDeviceLightOn
07-05 14:14:33.375   920  1173 D lights  : button : 1 +
07-05 14:14:33.375  1746  1746 I SamsungIME: getNextShiftState() cursorCapsMode : 0
07-05 14:14:33.385   920  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@35404fd6, r.packageName :com.google.android.gms
,07-05 14:14:33.405   920  3072 D SSRM:a  : DeviceInfo:: 000100100000
07-05 14:14:33.405   920  3072 D SSRM:a  : SettingsAirViewInfo:: 010100000
,07-05 14:14:33.405  1415  7610 D NfcService: index : 0
,07-05 14:14:33.405  1415  7610 D NfcService: index : 1
07-05 14:14:33.405  1415  7610 D NfcService: index : 2
,07-05 14:14:33.405   920  3072 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:14:33.415   920  1173 D lights  : button : 1 -
,07-05 14:14:33.415  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:14:33.415  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:14:33.415  4717  4717 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:43 [0:0] onReceive() action : androidintentactionSCREEN_ON
,07-05 14:14:33.415  4717  4717 E com.samsung.app: [MSC]>>>News_Daemon(E) DR:71 [0:0] [NameNotFoundException] process restart With Widget !!!!!
,07-05 14:14:33.425  4717  4717 W com.samsung.app: [MSC]>>>News_Daemon(E) U:95 [0:0]  ::::::::: Available Internal MemorySize ::::::::: = 25752600k
,07-05 14:14:33.425  4717  4717 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:104 [0:0] checkPackageNameList is Empty
,07-05 14:14:33.425  4717  4717 I com.samsung.app: [MSC]>>>News_Daemon(E) DR:110 [0:0] serviceStatus = 0 checkPackageNameList = 0
,07-05 14:14:33.425  4717  4717 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:145 [0:0] [CARS][AUTOREFRESHKEY] --> 0
07-05 14:14:33.425  4717  4717 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:146 [0:0] [CARS][NRT] = 0
07-05 14:14:33.425  4717  4717 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:147 [0:0] [CARS][DT] = 1467720873442
,07-05 14:14:33.445   920  7603 D InputManager-JNI: sysfs_write -: /sys/class/input/event2/device/enabled: 1
,07-05 14:14:33.445   920  1172 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-05 14:14:33.445   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 450
,07-05 14:14:33.455  4717  4717 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,07-05 14:14:33.455  4717  4717 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
07-05 14:14:33.455  4717  4717 D comsamsunglog: [MSC_Accu_Daemon]>>> daemonapp [Version : 150820735400 ] [ 1 ] 
07-05 14:14:33.455  4717  4717 D comsamsunglog: [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
,07-05 14:14:33.455  4717  4717 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
07-05 14:14:33.455  4717  4717 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-05 14:14:33.455  4717  4717 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,07-05 14:14:33.465  4717  4717 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 14:14:33.465  4717  4717 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 14:14:33.465  4717  4717 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 14:14:33.465  4717  4717 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 14:14:33.465  4717  4717 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,07-05 14:14:33.465  4717  4717 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:616 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
07-05 14:14:33.465  4717  4717 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 14:14:33.465  4717  4717 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:618 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,07-05 14:14:33.475  4717  4717 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:619 [0:0] [ASO][NUT] = 07/05/2016 04:28 PM
,07-05 14:14:33.475  4717  4717 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:620 [0:0] [ASO][CT] = 07/05/2016 02:14 PM
,07-05 14:14:33.475  4717  4717 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-05 14:14:33.475  4717  4717 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,07-05 14:14:33.515   920  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:14:33.515   920  7618 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-05 14:14:33.515   920  7618 D NetworkStatsFactory: UpdateStatsForKnox
,07-05 14:14:33.525   920   920 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-05 14:14:33.535  1198  1198 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 8 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte level=2
,07-05 14:14:33.535  1198  1198 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 8 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte
07-05 14:14:33.535  1198  1198 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=2
07-05 14:14:33.535  1198  1198 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_2 mContentDescriptionPhoneSignal = Two bars of phone signal
,07-05 14:14:33.535  1198  1198 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 14:14:33.535  1198  1198 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 14:14:33.535  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:33.535  1198  1198 D StatusBar.NetworkController: applyOpen
,07-05 14:14:33.535  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:33.535  1198  1198 D StatusBar.NetworkController: applyOpen
,07-05 14:14:33.535   920  7618 D NetworkStatsFactory: UpdateStatsForKnox
,07-05 14:14:33.535  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:33.545  1198  1198 D StatusBar.NetworkController: applyOpen
,07-05 14:14:33.545  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:33.545  1198  1198 D StatusBar.NetworkController: applyOpen
,07-05 14:14:33.575  1198  1198 I WaterColorEffect_View: showAffordanceEffect Renderer.handleTouchEvent(0, 540, 1009
,07-05 14:14:33.575  1198  1198 I WaterColor_Renderer: Renderer handleTouchEvent action = 0
,07-05 14:14:33.575   920  7618 I BatteryStatsDumper: Screen bin #0: time=0 power=0.0
07-05 14:14:33.575   920  7618 I BatteryStatsDumper: Screen bin #1: time=0 power=0.0
07-05 14:14:33.575   920  7618 I BatteryStatsDumper: Screen bin #2: time=0 power=0.0
07-05 14:14:33.575   920  7618 I BatteryStatsDumper: Screen bin #3: time=0 power=0.0
07-05 14:14:33.575   920  7618 I BatteryStatsDumper: Screen bin #4: time=6426 power=0.366282
07-05 14:14:33.575   920  7618 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-05 14:14:33.955   920  7618 I BatteryStatsDumper: Writing to database completed
,07-05 14:14:34.225   920  1093 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,07-05 14:14:34.225   920  1093 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-05 14:14:34.245   920   920 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 920  tag : WAKEUP_BOOSTER@32
,07-05 14:14:34.575  1198  1542 I WaterColor_Renderer: fps 59.88024
,07-05 14:14:34.745  1198  1542 I WaterColor_Renderer: dirty mode
,07-05 14:14:34.745  1198  1542 I WaterColor_Renderer: fps 60.81081
,07-05 14:14:34.875   920  1173 D PowerManagerService: [input device light] handleInputDeviceLightOff
,07-05 14:14:34.875   920  1173 D lights  : button : 0 +
,07-05 14:14:34.915   920  1173 D lights  : button : 0 -
,07-05 14:14:35.315   302   302 E SMD     : DCD ON
,07-05 14:14:35.455   920   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:14:35.455   920   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:14:35.455   920   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:14:35.455   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:14:35.465   920   920 I MotionRecognitionService: Plugged
,07-05 14:14:35.465   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:14:35.465  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:14:35.475  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:14:35.475  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:14:35.485  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
07-05 14:14:35.485  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 14:14:35.485  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:14:35.485  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:35.485  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:37.195  1289  1289 I wpa_supplicant: nl80211: Received scan results (15 BSSes)
,07-05 14:14:37.225   920  1148 D WifiP2pService: InactiveState{ what=147461 },
07-05 14:14:37.225   920  1148 D WifiP2pService: P2pEnabledState{ what=147461 }
07-05 14:14:37.225   920  1148 D WifiP2pService: DefaultState{ what=147461 }
,07-05 14:14:38.095  1198  1198 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
,07-05 14:14:38.095  1198  1198 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1845 should be AT_MOST
,07-05 14:14:38.145  1198  1198 D KeyguardViewMediator: handleKeyguardDoneDrawing
,07-05 14:14:38.305   302   302 E SMD     : DCD ON
,07-05 14:14:39.265  1198  1198 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:14:39.265  1198  1198 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:14:39.275  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:39.275  1198  1198 D StatusBar.NetworkController: applyOpen
,07-05 14:14:39.285  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:39.295  1198  1198 D StatusBar.NetworkController: applyOpen
,07-05 14:14:39.295  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:39.295  1198  1198 D StatusBar.NetworkController: applyOpen
,07-05 14:14:39.305  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:39.305  1198  1198 D StatusBar.NetworkController: applyOpen
,07-05 14:14:40.295  1198  1198 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:14:40.295  1198  1198 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:14:40.305  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:40.315  1198  1198 D StatusBar.NetworkController: applyOpen
,07-05 14:14:40.315  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:40.315  1198  1198 D StatusBar.NetworkController: applyOpen,
,07-05 14:14:40.325  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:40.325  1198  1198 D StatusBar.NetworkController: applyOpen
,07-05 14:14:40.335  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:40.335  1198  1198 D StatusBar.NetworkController: applyOpen
,07-05 14:14:41.315   302   302 E SMD     : DCD ON
,07-05 14:14:42.325  1198  1198 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:14:42.325  1198  1198 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:14:42.335  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:42.345  1198  1198 D StatusBar.NetworkController: applyOpen
,07-05 14:14:42.345  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:42.345  1198  1198 D StatusBar.NetworkController: applyOpen
,07-05 14:14:42.345  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:42.345  1198  1198 D StatusBar.NetworkController: applyOpen
,07-05 14:14:42.355  1198  1198 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:42.355  1198  1198 D StatusBar.NetworkController: applyOpen
,07-05 14:14:43.055   920  1059 D PowerManagerService: [s] UserActivityState : 1 -> 4
,07-05 14:14:43.055   920  1059 I PowerManagerService: !@[ps] Screen__Off - 1 : timeout (0x4) (2)
,07-05 14:14:43.055   920  1059 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-05 14:14:43.055   920  1172 D InputManager-JNI: setDeviceInteractive: 0
,07-05 14:14:43.065   920  1059 D DisplayPowerController: getFinalBrightness : 20 -> 20
,07-05 14:14:43.065   920  1059 D DisplayPowerController: animation target = 20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:14:43.075   920  1059 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,07-05 14:14:43.075   920  1059 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,07-05 14:14:43.085   920  1059 D PowerManagerService: SecHardwareInterface.setBatteryADC : false
,07-05 14:14:43.085   920  1059 D PowerManagerService: handleSandman : startDream()
,07-05 14:14:43.085   920  1059 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
07-05 14:14:43.085   920  1059 I PowerManagerService: Sleeping (uid 1000)...
07-05 14:14:43.085   920  1059 D PowerManagerService: [s] UserActivityState : 4 -> 0
,07-05 14:14:43.085   920  1059 D PowerManagerService: [input device light] setInputDeviceLightOn is called : 0
,07-05 14:14:43.085   920  1173 D PowerManagerService: [input device light] handleInputDeviceLightOff
,07-05 14:14:43.085   266   266 I SurfaceFlinger: id=14 createSurf (1080x1920),2 flag=404, DolorFade
,07-05 14:14:43.095   920  7639 D InputManager-JNI: sysfs_write +: /sys/class/input/event3/device/enabled: 0
,07-05 14:14:43.095   920  7640 D InputManager-JNI: sysfs_write +: /sys/class/input/event2/device/enabled: 0
07-05 14:14:43.095   920  7638 D InputManager-JNI: sysfs_write +: /sys/class/input/event4/device/enabled: 0
07-05 14:14:43.095   920  7639 D InputManager-JNI: sysfs_write -: /sys/class/input/event3/device/enabled: 0
,07-05 14:14:43.095   920  7638 D InputManager-JNI: sysfs_write -: /sys/class/input/event4/device/enabled: 0
,07-05 14:14:43.095   920  7640 D InputManager-JNI: sysfs_write -: /sys/class/input/event2/device/enabled: 0
,07-05 14:14:43.095   920  1172 D SContextService: 	.unregisterCallback : 1, client=
07-05 14:14:43.095   920  1172 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@2dc697f1, Service = Auto Rotation, used = 1
,07-05 14:14:43.095   920  1172 W CAE     : unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,07-05 14:14:43.095   920  1172 V CAE     : stop(ContextProvider.java:149)
,07-05 14:14:43.115   920  1172 V CAE     : clear(AutoRotationRunner.java:182)
,07-05 14:14:43.115   920  1172 V CAE     : disable(AutoRotationRunner.java:171)
,07-05 14:14:43.115   920  1172 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,07-05 14:14:43.115   920  1172 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
07-05 14:14:43.115   317   317 D Sensorhubs: sendContextData: -78, 7, 0, 0
,07-05 14:14:43.135   920  1172 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-05 14:14:43.135   920  1172 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,07-05 14:14:43.155   920  1059 D DisplayPowerController: ColorFade: onAnimationStart
,07-05 14:14:43.155   920  1059 D DisplayPowerController: getFinalBrightness : 255 -> 0
07-05 14:14:43.155   920  1059 D DisplayPowerController: animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:14:43.155   920  1176 D lights  : lcd : 235 +
,07-05 14:14:43.185   920  1172 D CAE     : doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,07-05 14:14:43.185   920  1172 I CAE     : displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
07-05 14:14:43.185   920  1172 D CAE     : showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,07-05 14:14:43.185   920  1172 W CAE     : unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
07-05 14:14:43.185   920  1172 D SContextService: removeSContextService() : service = Auto Rotation
07-05 14:14:43.185   920  1172 D SContextService: ===== SContext Service List =====
07-05 14:14:43.185   920  1172 D SContextManager:   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@20730756, service=Auto Rotation
,07-05 14:14:43.185  1198  1219 D KeyguardViewMediator: onScreenTurnedOff(3)
07-05 14:14:43.185  1198  1219 I KeyguardEffectViewController: *** KeyguardEffectView getInstanceIfExists ***
07-05 14:14:43.185  1198  1219 D KeyguardEffectViewController: changeWallpaperByScreenOff()
07-05 14:14:43.185  1198  1219 D KeyguardViewMediator: notifyScreenOffLocked
,07-05 14:14:43.185  1198  1219 E KeyguardViewMediator: resetStateLocked
07-05 14:14:43.185  1198  1198 D KeyguardViewMediator: handleNotifyScreenOff
07-05 14:14:43.195  1198  1198 D KeyguardViewBase: screen off, instance 2e920e4e at 756220
,07-05 14:14:43.195  1198  1198 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=true)
,07-05 14:14:43.195  1198  1198 D KeyguardSecurityView: showSecurityScreen(None)
07-05 14:14:43.195  1198  1198 D PersonaManager: isKioskContainerExistOnDevice
,07-05 14:14:43.195  1198  1198 D KeyguardViewMediator: Kiosk container not exists on device.
07-05 14:14:43.195  1198  1198 D KeyguardViewMediator: handleReset
,07-05 14:14:43.195  1198  1198 D KeyguardEffectViewUtil: wallpaperType :1
07-05 14:14:43.195   920   920 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 920) 
07-05 14:14:43.195   920   920 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,07-05 14:14:43.195  1198  1198 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
07-05 14:14:43.195  1198  1198 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
07-05 14:14:43.195   920   920 E LightSensor: Light old sensor_state 8193, new sensor_state : 8705 en : 1
07-05 14:14:43.195  1198  1198 D PhoneStatusBar: updateKeyguardState :1
,07-05 14:14:43.195  1198  1198 D StatusBar: LSSN:1
,07-05 14:14:43.205  1198  1198 D StatusBar: fullBouncer=false
,07-05 14:14:43.205  1198  1198 D StatusBar: SLN:S
07-05 14:14:43.205  1198  1198 E LSO     : LSO Service is not yet ready!!!
07-05 14:14:43.205  1198  1198 D StatusBar-QSPanel: setSingleLine:true
07-05 14:14:43.205   920  1176 D lights  : lcd : 235 -
07-05 14:14:43.205   920  1176 D lights  : lcd : 55 +
,07-05 14:14:43.205  1198  1198 D StatusBar-QSPanel: updateButtonInfo mButtonWidth : 206 mColumns:5 orien: 1 displayWidth:1032
,07-05 14:14:43.205  1198  1198 D StatusBar-QSPanel: setSingleLine height:0
07-05 14:14:43.205  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 14:14:43.205   920  1176 D lights  : lcd : 55 -
,07-05 14:14:43.205  1198  1198 D STATUSBAR-PhoneStatusBar: showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
,07-05 14:14:43.205  1198  1198 I PhoneStatusBar: Icon Only
07-05 14:14:43.205  1198  1198 I StatusBar: Icon Only
,07-05 14:14:43.205  1198  1198 D PanelView: There is/are notification(s) 
07-05 14:14:43.205  1198  1198 D PhoneStatusBar: updateQSpanelHeight: 279 height:591
,07-05 14:14:43.205   920   920 D SensorManager: registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
07-05 14:14:43.205   920   920 D BatteryService: turn on LED for fully charged
,07-05 14:14:43.215  1198  1198 D PanelView: setQsHeight mQsMin:0 mQsMax:705 mQsEx:0.0mQsPeek:591
07-05 14:14:43.215  1198  1198 I KeyguardEffectViewController: setKeyguardShowing = true
07-05 14:14:43.215  1198  1198 D KeyguardEffectViewController: reset()
07-05 14:14:43.215  1198  1198 D VisualEffectCircleUnlockEffect: KeyguardEffectViewNone : reset
07-05 14:14:43.215  1198  1198 I WaterColor Keyguard: reset
,07-05 14:14:43.215  1198  1542 I WaterColor_Renderer: clearEffect()
,07-05 14:14:43.215  1198  1542 I WaterColor_Renderer: dirty mode
,07-05 14:14:43.215  1198  1198 D KeyguardEffectViewController: isFestivalActivated()false
07-05 14:14:43.215  1198  1198 I KeyguardEffectViewController: setFestivalKeyguardShowing = true ,:false
07-05 14:14:43.215  1198  1198 D KeyguardEffectViewController: isFestivalActivated()false
,07-05 14:14:43.215  1198  1198 D PersonaManager: isKioskContainerExistOnDevice
07-05 14:14:43.215  1198  1198 I PhoneStatusBar: Icon Only
07-05 14:14:43.215  1198  1198 I StatusBar: Icon Only
,07-05 14:14:43.215   920   920 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
07-05 14:14:43.215   920   920 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,07-05 14:14:43.215   920   920 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
07-05 14:14:43.215   920   920 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
07-05 14:14:43.215   317   560 D Sensorhubs: sendContextData: -76, 13, -46, 0
07-05 14:14:43.215  1198  1198 D PanelView: There is/are notification(s) 
,07-05 14:14:43.215  1198  1198 D PanelView: There is/are notification(s) 
,07-05 14:14:43.225  1198  1198 D PhoneStatusBar: updateKeyguardPreviousState :1
,07-05 14:14:43.225  1198  1198 D PhoneStatusBar: makeExpandedVisible:true
,07-05 14:14:43.225  1198  1198 D KeyguardEffectViewUtil: wallpaperType :1
07-05 14:14:43.225  1198  1198 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
07-05 14:14:43.225  1198  1198 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-05 14:14:43.225   920   936 D SecContentProvider2: uri = 14 selection = getSealedState
07-05 14:14:43.225   920   936 D SecContentProvider2: mCursor = null
07-05 14:14:43.225   920   920 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 12, 14, 43,
,07-05 14:14:43.225  1198  1198 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME recent clock search >
07-05 14:14:43.225   920   920 D SensorHubManager: SendSensorHubData: send data = -63, 14, 12, 14, 43
07-05 14:14:43.225   920  3816 D SecContentProvider2: uri = 14 selection = getSealedState
07-05 14:14:43.225   920  3816 D SecContentProvider2: mCursor = null
07-05 14:14:43.225   317   317 D Sensorhubs: sendContextData: -63, 14, 12, 14, 43
,07-05 14:14:43.225   920  1236 D SecContentProvider2: uri = 14 selection = getSealedState
07-05 14:14:43.225   920  1236 D SecContentProvider2: mCursor = null
,07-05 14:14:43.225   920  2038 D SecContentProvider2: uri = 14 selection = getSealedState
07-05 14:14:43.225   920  2038 D SecContentProvider2: mCursor = null
,07-05 14:14:43.225  1198  1198 D StatusBar-DoNotDistrub: isDisableAlert isDormantModeOn:false isNotificationDisabled:true
,07-05 14:14:43.235  1198  1198 D KeyguardProperties: isIgnoreNationalRoaming() = false
,07-05 14:14:43.235  1198  1198 D PhoneStatusBar: HomeCitySettingsDialog available = false, show = true
07-05 14:14:43.235  1198  1198 V KeyguardUpdateMonitor: *** unregister callback for com.android.keyguard.sec.SecKeyguardCircleView$1@2280a676
07-05 14:14:43.235   920  1464 E Sensors : Acc old sensor_state 8705, new sensor_state : 8704 en : 0
,07-05 14:14:43.235   920   920 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,07-05 14:14:43.235   920  1126 E MotionRecognitionService:  handler : SCREEN_OFF end 
,07-05 14:14:43.235   920  1176 D lights  : lcd : 0 +
07-05 14:14:43.235   920  1059 D DisplayPowerController: getFinalBrightness : 255 -> 0
07-05 14:14:43.235  1198  1198 D SensorManager: unregisterListener ::   
07-05 14:14:43.235   920  1059 D DisplayPowerController: animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:14:43.245  1198  1198 D KeyguardUnlockEventHandler: cleanUp()
,07-05 14:14:43.245  1198  1198 I SecAttributionInfoView: onDetachedFromWindow
,07-05 14:14:43.245  1198  1198 V KeyguardUpdateMonitor: *** unregister callback for com.android.keyguard.KeyguardSimpleHostView$1@2537047f
,07-05 14:14:43.245  1198  1198 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardSimpleHostView$1@3250f481
07-05 14:14:43.245  1198  1198 V KeyguardUpdateMonitor: *** unregister callback for null
,07-05 14:14:43.245   920   920 D NotificationService: ACTION_SCREEN_OFF
,07-05 14:14:43.245   920   920 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 920) 
07-05 14:14:43.245   920   920 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,07-05 14:14:43.245  1198  1198 D KeyguardSecurityView: AUTO_WIPE = false , IT Policy = false
07-05 14:14:43.245  1198  1198 I KeyguardSecurityView: addAttributionInfoViewIfNecessary
,07-05 14:14:43.245   308   308 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-05 14:14:43.245   308   308 V voice   : voice_set_parameters: enter: screen_state=off
07-05 14:14:43.245   308   308 V voice   : voice_set_parameters: exit with code(-2)
07-05 14:14:43.255  1198  1198 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
07-05 14:14:43.255  1198  1198 D KeyguardSecurityView: showSecurityScreen(None)
07-05 14:14:43.255  1198  1198 V KeyguardSecurityView: inflating id = 2130968634
07-05 14:14:43.255   308   308 V msm8974_platform: platform_set_parameters: enter: screen_state=off
,07-05 14:14:43.255   308   308 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-05 14:14:43.255   308   308 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-05 14:14:43.255   308   308 V audio_hw_primary: adev_set_parameters: exit
,07-05 14:14:43.255   920  1149 E native  : do suspend true
,07-05 14:14:43.255  1198  1198 D SecKeyguardBottomAreaView: mUseBackUp= falsemUseCenteredMessageArea= false
,07-05 14:14:43.255  1198  1198 D SecKeyguardBottomAreaView: shortcut value[0-off / 1-camera] = 1
07-05 14:14:43.255  1198  1198 D SecKeyguardBottomAreaView: mKidsModeEnabled= false
,07-05 14:14:43.265  1198  1198 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardMessageArea$2@1757bd
07-05 14:14:43.265  1198  1198 V KeyguardUpdateMonitor: *** unregister callback for null
,07-05 14:14:43.265   920   920 I SecExternalDisplayIntents_Java: Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,07-05 14:14:43.265   920   920 I BackgroundCompactionService: Schedule Type1 BGCompaction
,07-05 14:14:43.275   920  1176 D lights  : lcd : 0 -
,07-05 14:14:43.295   920  1057 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
,07-05 14:14:43.295   920  1057 D IpRemoteDisplayController: Bridge Server is not available
,07-05 14:14:43.305  1198  1198 D KeyguardUnlockView: mIsHelpTextEnabled= true
,07-05 14:14:43.305  1198  1198 D KeyguardUnlockView: hideBouncer mBouncerHelpText != null
,07-05 14:14:43.305  1198  1198 D KeyguardEffectViewUtil: wallpaperType :1
07-05 14:14:43.305  1198  1198 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
07-05 14:14:43.305  1198  1198 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-05 14:14:43.305  1198  1198 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.sec.SecKeyguardCircleView$1@23fcb936
07-05 14:14:43.305  1198  1198 V KeyguardUpdateMonitor: *** unregister callback for null
,07-05 14:14:43.315  1198  1198 I SecAttributionInfoView: onAttachedToWindow
,07-05 14:14:43.315  1198  1198 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
07-05 14:14:43.315  1198  1198 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,07-05 14:14:43.315  1198  1198 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,07-05 14:14:43.315  1198  1198 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,07-05 14:14:43.315  1198  1198 D VisualEffectCircleUnlockEffect: KeyguardEffectViewNone : screenTurnedOff
07-05 14:14:43.315  1198  1198 I WaterColor Keyguard: screenTurnedOff
,07-05 14:14:43.315  1198  1542 I WaterColor_Renderer: clearEffect()
07-05 14:14:43.325  1198  1198 D SecKeyguardCircleView: onScreenTurnedOff
07-05 14:14:43.325  1198  1542 I WaterColor_Renderer: dirty mode
,07-05 14:14:43.325  1198  1198 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
,07-05 14:14:43.325  1198  1198 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1845 should be AT_MOST
,07-05 14:14:43.335  1198  1198 D QSpanel : label top:23
,07-05 14:14:43.335  1198  1198 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-05 14:14:43.335  1198  1198 D QSpanel : label top:23
07-05 14:14:43.335  1198  1198 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-05 14:14:43.335  1198  1198 D QSpanel : label top:23
07-05 14:14:43.335  1198  1198 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
,07-05 14:14:43.335  1198  1198 D QSpanel : label top:0
07-05 14:14:43.335  1198  1198 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-05 14:14:43.335  1198  1198 D QSpanel : label top:23
07-05 14:14:43.335  1198  1198 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-05 14:14:43.335  1198  1198 D QSpanel : label top:0
,07-05 14:14:43.335  1198  1198 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-05 14:14:43.335  1198  1198 D QSpanel : label top:0
07-05 14:14:43.335  1198  1198 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-05 14:14:43.335  1198  1198 D QSpanel : label top:0
,07-05 14:14:43.335  1198  1198 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-05 14:14:43.335  1198  1198 D QSpanel : label top:0
07-05 14:14:43.335  1198  1198 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-05 14:14:43.335  1198  1198 D QSpanel : label top:0
07-05 14:14:43.335  1198  1198 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-05 14:14:43.335  1198  1198 D ScrimController: updateScrimKeyguard() mDozing=false, mBouncerShowing=false
,07-05 14:14:43.345  1198  1198 D VolumePanel.23ad57f3: forceTimeout delay=0 callers=com.android.systemui.volume.VolumePanel.postDismiss:2103 com.android.systemui.volume.VolumePanel$8.onReceive:1167 android.app.LoadedApk$ReceiverDispatcher$Args.run:923 
,07-05 14:14:43.345  1198  1198 D KeyguardViewMediator: handleKeyguardDoneDrawing
,07-05 14:14:43.355   920  1059 D DisplayPowerState: !@ ColorFade entry
07-05 14:14:43.355   920  1059 D DisplayPowerController: ColorFade: onAnimationEnd
,07-05 14:14:43.355  1198  1198 D VolumePanel: mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
07-05 14:14:43.355  1198  1198 D VolumePanel: mCoverBroadcastReceiver: Screen OFF start
07-05 14:14:43.355  1198  1198 D VolumePanel: mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,07-05 14:14:43.355  1198  1198 D VolumePanel: mCoverBroadcastReceiver: Screen OFF end
07-05 14:14:43.355  1198  1198 D VolumePanel: mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,07-05 14:14:43.355   920  1003 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,07-05 14:14:43.365   920   920 D PersonaManagerService: ACTION_SCREEN_OFF onReceive
07-05 14:14:43.365   920  1067 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
,07-05 14:14:43.375   920  1059 D DisplayPowerController: getFinalBrightness : 0 -> 0
,07-05 14:14:43.375  1415  1415 D NativeNfcManager: power state=2
07-05 14:14:43.375   920  1059 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 14:14:43.375   920  1059 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-05 14:14:43.375   920  1059 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:14:43.375   920  1059 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-05 14:14:43.375   920  1059 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 14:14:43.375   920  1057 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-05 14:14:43.375   920   920 V ActivityManager: Display changed displayId=0
,07-05 14:14:43.375   920  1059 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 14:14:43.375   920  1059 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,07-05 14:14:43.385  1198  1198 D STATUSBAR-PhoneStatusBar:      ACTION_SCREEN_OFF is finished!!!! 
,07-05 14:14:43.385   266   266 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6962000
07-05 14:14:43.385   266   266 D qdhwcomposer: hwc_blank: Blanking display: 0
07-05 14:14:43.385  1415  7658 D NfcService: call the applyRouting
,07-05 14:14:43.395  1198  1198 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 8 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte level=2
07-05 14:14:43.395  1198  1198 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 8 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte
07-05 14:14:43.395  1198  1198 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=2
07-05 14:14:43.395  1198  1198 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_2 mContentDescriptionPhoneSignal = Two bars of phone signal
,07-05 14:14:43.395  1198  1198 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 14:14:43.395  1198  1198 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:14:43.395  1819  1819 D accuweather: [Accuweather J]>>> SWW:81 [0:0] =============== BR act = androidintentactionSCREEN_OFF
,07-05 14:14:43.405   920  1236 D ActivityManager: caller:android.app.ApplicationThreadProxy@2948454f, r.packageName :com.google.android.gms
,07-05 14:14:43.415  1415  7658 D NfcService: index : 0
07-05 14:14:43.415  1415  7658 D NfcService: index : 1
07-05 14:14:43.415  1415  7658 D NfcService: index : 2
,07-05 14:14:43.415   920  3072 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:14:43.425   920  1561 W BroadcastQueue: Skipping deliver [sec] BroadcastRecord{2fdc4dc u-1 android.intent.action.SCREEN_OFF} to ReceiverList{335e6e13 1198 com.android.systemui/10067/u0 remote:257f8502}: filter unregistered
,07-05 14:14:43.445   920  3800 W ActivityManager: getTasks: caller 10102 does not hold GET_TASKS; limiting output
,07-05 14:14:43.445   920  1520 W ActivityManager: getTasks: caller 10102 does not hold GET_TASKS; limiting output
,07-05 14:14:43.445   920  1172 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-05 14:14:43.455   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 312, CUR = 450
,07-05 14:14:43.515   920  1093 D LightsService: [SvcLED]  onSensorChanged::light value = 22
,07-05 14:14:43.525   920  1093 E LightSensor: Light old sensor_state 8704, new sensor_state : 8192 en : 0
,07-05 14:14:43.525   920  1093 D SensorManager: unregisterListener ::   
,07-05 14:14:43.525   920  1093 D lights  : led_pattern : 5 +
,07-05 14:14:43.525   920  1093 D lights  : led_pattern : 5 -
07-05 14:14:43.525   920  1093 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-05 14:14:43.655   266   509 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
07-05 14:14:43.655   266   266 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-05 14:14:43.655   920  1177 D SurfaceControl: Excessive delay in setPowerMode(): 280ms
07-05 14:14:43.655   920  1177 D PowerManagerService: !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
07-05 14:14:43.655   920  1177 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
07-05 14:14:43.655   920  1177 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
07-05 14:14:43.655   920  1177 I QCOM PowerHAL: Got set_interactive hint
,07-05 14:14:43.655   920  1177 D PowerManagerService: Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 287ms
07-05 14:14:43.655   920  1059 I PowerManagerService: [PWL] Off : 0s ago
,07-05 14:14:44.305   302   302 E SMD     : DCD ON
,07-05 14:14:45.505   920  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:14:45.515   920  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:14:45.515   920  1319 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:14:45.515   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:14:45.525  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:14:45.535  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:14:45.535   920   920 I MotionRecognitionService: Plugged
,07-05 14:14:45.535   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:14:45.545   920  1319 D BatteryService: stay LED for fully charged
,07-05 14:14:45.555  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:14:45.565  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:45.575  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:14:45.575  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:14:45.585  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:45.585  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:47.305   302   302 E SMD     : DCD ON
,07-05 14:14:48.335  1198  1198 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
,07-05 14:14:48.335  1198  1198 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1845 should be AT_MOST
,07-05 14:14:48.665   920  1059 I PowerManagerService: [PWL] Off : 5s ago
,07-05 14:14:50.315   302   302 E SMD     : DCD ON
,07-05 14:14:53.315   302   302 E SMD     : DCD ON
,07-05 14:14:53.505   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 312, CUR = 450
,07-05 14:14:55.635   920  1340 E Watchdog: !@Sync 25
,07-05 14:14:56.285   920  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:14:56.305   302   302 E SMD     : DCD ON
,07-05 14:14:56.335   920   936 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:14:58.675   920  1059 I PowerManagerService: [PWL] Off : 15s ago
,07-05 14:14:59.305   302   302 E SMD     : DCD ON
,07-05 14:14:59.985   920  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:15:02.315   302   302 E SMD     : DCD ON
,07-05 14:15:03.555   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 313, CUR = 450
,07-05 14:15:05.315   302   302 E SMD     : DCD ON
,07-05 14:15:06.395   920  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:15:08.315   302   302 E SMD     : DCD ON
,07-05 14:15:11.325   302   302 E SMD     : DCD ON
,07-05 14:15:13.595   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 314, CUR = 450
,07-05 14:15:13.675   920  1059 I PowerManagerService: [PWL] Off : 30s ago
,07-05 14:15:14.325   302   302 E SMD     : DCD ON
,07-05 14:15:16.455   920  1464 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:15:16.455   920  1464 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:15:16.455   920  1464 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:15:16.465   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:15:16.465  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:15:16.475  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:15:16.475   920   920 I MotionRecognitionService: Plugged
,07-05 14:15:16.485   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:15:16.485   920  1464 D BatteryService: stay LED for fully charged
,07-05 14:15:16.485  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:15:16.495  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:15:16.495  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:15:16.505  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:16.505  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:15:16.505  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:17.315   302   302 E SMD     : DCD ON
,07-05 14:15:20.325   302   302 E SMD     : DCD ON
,07-05 14:15:23.315   302   302 E SMD     : DCD ON
,07-05 14:15:23.645   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 450
,07-05 14:15:25.635   920  1340 E Watchdog: !@Sync 26
,07-05 14:15:26.325   302   302 E SMD     : DCD ON
,07-05 14:15:26.515   920  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:15:26.515   920  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:15:26.515   920  1319 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:15:26.525   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:15:26.535  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:15:26.535  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:15:26.535   920   920 I MotionRecognitionService: Plugged
,07-05 14:15:26.545   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:15:26.545   920  1319 D BatteryService: stay LED for fully charged
,07-05 14:15:26.565  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:15:26.585  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:26.585  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:15:26.585  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:15:26.595  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:26.595  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:29.315   302   302 E SMD     : DCD ON
,07-05 14:15:32.325   302   302 E SMD     : DCD ON
,07-05 14:15:33.675   920  1059 I PowerManagerService: [PWL] Off : 50s ago
,07-05 14:15:33.715   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 450
,07-05 14:15:35.315   302   302 E SMD     : DCD ON
,07-05 14:15:36.575   920  1464 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:15:38.325   302   302 E SMD     : DCD ON
,07-05 14:15:41.335   302   302 E SMD     : DCD ON
,07-05 14:15:43.755   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 450
,07-05 14:15:44.325   302   302 E SMD     : DCD ON
,07-05 14:15:47.325   302   302 E SMD     : DCD ON
,07-05 14:15:49.905   920  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:15:49.975   920  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:15:49.985  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:15:49.985  1198  1198 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:15:49.995  1198  1198 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:15:49.995  1198  1198 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:15:50.015   920   920 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
,07-05 14:15:50.055   920   920 I BackgroundCompactionService: onStart. jobID=801
,07-05 14:15:50.055   920   920 I BackgroundCompactionService: onStart done. jobID=801
,07-05 14:15:50.075   920  7675 I BackgroundCompactionService: Execute BGCompaction (type1). (1 times)
,07-05 14:15:50.075   920  7675 I BackgroundCompactionService: compact_memory command done
,07-05 14:15:50.095  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:15:50.115  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:15:50.145   920  1236 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:15:50.155   920  1236 D ActivityManager: caller:android.app.ApplicationThreadProxy@15019912, r.packageName :com.google.android.gms
,07-05 14:15:50.255  1654  1731 I art     : Explicit concurrent mark sweep GC freed 14746(816KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 18MB/31MB, paused 1.062ms total 37.250ms
,07-05 14:15:50.265  2292  7688 I EventLogService: Aggregate from 1467719101054 (log), 1467719101054 (data)
,07-05 14:15:50.325   302   302 E SMD     : DCD ON
,07-05 14:15:53.325   302   302 E SMD     : DCD ON
,07-05 14:15:53.815   920  3072 D SSRM:n  : SIOP:: AP = 320, PST = 315, CUR = 450
,07-05 14:15:55.635   920  1340 E Watchdog: !@Sync 27
,07-05 14:15:56.335   302   302 E SMD     : DCD ON
,07-05 14:15:58.685   920  1059 I PowerManagerService: [PWL] Off : 75s ago
,07-05 14:15:59.335   302   302 E SMD     : DCD ON
,07-05 14:15:59.995   920  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:16:00.055   920  1561 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:00.055   920  1561 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:16:00.055   920  1561 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:16:00.065   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:16:00.075   920   920 I MotionRecognitionService: Plugged
,07-05 14:16:00.075   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:16:00.085   920  1561 D BatteryService: stay LED for fully charged
,07-05 14:16:00.095  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:16:00.095  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:16:00.105  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:16:00.125  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:00.125  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:16:00.125  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:16:00.125  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:00.135  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:02.335   302   302 E SMD     : DCD ON
,07-05 14:16:03.855   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 450
,07-05 14:16:05.325   302   302 E SMD     : DCD ON
,07-05 14:16:08.335   302   302 E SMD     : DCD ON
,07-05 14:16:10.115   920   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:11.335   302   302 E SMD     : DCD ON
,07-05 14:16:13.905   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 450
,07-05 14:16:14.335   302   302 E SMD     : DCD ON
,07-05 14:16:17.335   302   302 E SMD     : DCD ON
,07-05 14:16:20.175   920  1464 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:20.185   920  1464 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:16:20.185   920  1464 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:16:20.185   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:16:20.195  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:16:20.195  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:16:20.205   920   920 I MotionRecognitionService: Plugged
,07-05 14:16:20.205   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:16:20.215   920  1464 D BatteryService: stay LED for fully charged
,07-05 14:16:20.225  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:16:20.235  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:20.235  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:16:20.235  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:16:20.245  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:16:20.245  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:20.335   302   302 E SMD     : DCD ON
,07-05 14:16:23.345   302   302 E SMD     : DCD ON
,07-05 14:16:23.955   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 450
,07-05 14:16:25.635   920  1340 E Watchdog: !@Sync 28
,07-05 14:16:26.345   302   302 E SMD     : DCD ON
,07-05 14:16:28.675   920  1059 I PowerManagerService: [PWL] Off : 105s ago
,07-05 14:16:29.335   302   302 E SMD     : DCD ON
,07-05 14:16:30.235   920  1662 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:30.235   920  1662 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:16:30.245   920  1662 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:16:30.245   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:16:30.255  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:16:30.255  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:16:30.265   920   920 I MotionRecognitionService: Plugged
,07-05 14:16:30.265   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:16:30.275   920  1662 D BatteryService: stay LED for fully charged
,07-05 14:16:30.285  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:16:30.285  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:16:30.295  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:16:30.305  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:30.305  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:30.305  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:32.335   302   302 E SMD     : DCD ON
,07-05 14:16:34.005   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 450
,07-05 14:16:35.345   302   302 E SMD     : DCD ON
,07-05 14:16:38.335   302   302 E SMD     : DCD ON
,07-05 14:16:41.335   302   302 E SMD     : DCD ON
,07-05 14:16:43.285   920  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:16:43.305  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:16:43.315  1198  1198 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:16:43.315  1198  1198 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:16:43.325  1198  1198 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:16:43.355   920  1662 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:43.355   920  1662 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:16:43.355   920  1662 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:16:43.355   920  1662 D BatteryService: stay LED for fully charged
,07-05 14:16:43.355   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:16:43.365  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:16:43.375  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:16:43.375  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:16:43.375  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:16:43.375  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:43.375  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:43.375  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:43.375   920   920 I MotionRecognitionService: Plugged
,07-05 14:16:43.375   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:16:43.385  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:16:43.435  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:16:43.435  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:16:44.045   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 450
,07-05 14:16:44.345   302   302 E SMD     : DCD ON
,07-05 14:16:47.345   302   302 E SMD     : DCD ON
,07-05 14:16:50.345   302   302 E SMD     : DCD ON
,07-05 14:16:53.345   302   302 E SMD     : DCD ON
,07-05 14:16:53.405   920  1706 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:53.405   920  1706 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:16:53.415   920  1706 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:16:53.415   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:16:53.425  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:16:53.425  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:16:53.435   920   920 I MotionRecognitionService: Plugged
,07-05 14:16:53.435   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:16:53.445   920  1706 D BatteryService: stay LED for fully charged
,07-05 14:16:53.455  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:16:53.465  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:53.475  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:53.475  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:16:53.485  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:16:53.485  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:54.095   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,07-05 14:16:55.645   920  1340 E Watchdog: !@Sync 29
,07-05 14:16:56.355   302   302 E SMD     : DCD ON
,07-05 14:16:59.345   302   302 E SMD     : DCD ON
,07-05 14:16:59.985   920  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:17:02.345   302   302 E SMD     : DCD ON
,07-05 14:17:03.465   920  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:17:03.675   920  1059 I PowerManagerService: [PWL] Off : 140s ago
,07-05 14:17:04.145   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,07-05 14:17:05.345   302   302 E SMD     : DCD ON
,07-05 14:17:08.345   302   302 E SMD     : DCD ON
,07-05 14:17:11.355   302   302 E SMD     : DCD ON
,07-05 14:17:13.525   920  1520 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:17:13.525   920  1520 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:17:13.525   920  1520 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:17:13.535   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:17:13.545   920   920 I MotionRecognitionService: Plugged
,07-05 14:17:13.545  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:17:13.545  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:17:13.555   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:17:13.555   920  1520 D BatteryService: stay LED for fully charged
,07-05 14:17:13.575  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:17:13.585  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:13.585  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:17:13.585  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:17:13.605  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:13.605  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:14.185   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,07-05 14:17:14.355   302   302 E SMD     : DCD ON
,07-05 14:17:17.355   302   302 E SMD     : DCD ON
,07-05 14:17:20.345   302   302 E SMD     : DCD ON
,07-05 14:17:23.045   920  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 14:17:23.045   920  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:17:23.045   920  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:17:23.355   302   302 E SMD     : DCD ON
,07-05 14:17:23.595   920  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:17:24.285   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,07-05 14:17:25.645   920  1340 E Watchdog: !@Sync 30
,07-05 14:17:26.055   920  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 14:17:26.055   920  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:17:26.065   920  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:17:26.065   920  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:17:26.355   302   302 E SMD     : DCD ON
,07-05 14:17:29.355   302   302 E SMD     : DCD ON
,07-05 14:17:32.365   302   302 E SMD     : DCD ON
,07-05 14:17:33.645   920  1561 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:17:33.645   920  1561 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:17:33.655   920  1561 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:17:33.655   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:17:33.665  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:17:33.665  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:17:33.675   920   920 I MotionRecognitionService: Plugged
,07-05 14:17:33.675   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:17:33.675   920  1561 D BatteryService: stay LED for fully charged,
,07-05 14:17:33.685  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:17:33.695  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:17:33.695  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:17:33.715  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:33.715  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:17:33.715  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:34.335   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:17:35.365   302   302 E SMD     : DCD ON
,07-05 14:17:38.365   302   302 E SMD     : DCD ON
,07-05 14:17:41.365   302   302 E SMD     : DCD ON
,07-05 14:17:43.685   920  1059 I PowerManagerService: [PWL] Off : 180s ago
,07-05 14:17:44.365   302   302 E SMD     : DCD ON
,07-05 14:17:44.405   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:17:45.285   920  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:17:45.335  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:17:45.335  1198  1198 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:17:45.345  1198  1198 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:17:45.345  1198  1198 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:17:45.355   920  2038 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:17:45.355   920  2038 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:17:45.355   920  2038 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 14:17:45.355   920  2038 D BatteryService: stay LED for fully charged
,07-05 14:17:45.355   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:17:45.365  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:17:45.365  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:17:45.365  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:17:45.385   920   920 I MotionRecognitionService: Plugged
,07-05 14:17:45.385   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:17:45.395  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:17:45.395  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:45.395  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:45.405  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:45.405  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:17:45.455  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:17:45.455  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:17:46.555  1654  4073 D GCM     : Message class com.google.f.a.a.i
,07-05 14:17:46.555   920  3800 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:17:46.565   920  1236 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:17:47.355   302   302 E SMD     : DCD ON
,07-05 14:17:50.355   302   302 E SMD     : DCD ON
,07-05 14:17:53.365   302   302 E SMD     : DCD ON
,07-05 14:17:54.455   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:17:55.405   920  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:17:55.645   920  1340 E Watchdog: !@Sync 31
,07-05 14:17:56.355   302   302 E SMD     : DCD ON
,07-05 14:17:59.365   302   302 E SMD     : DCD ON
,07-05 14:17:59.995   920  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:18:02.375   302   302 E SMD     : DCD ON
,07-05 14:18:04.505   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:18:05.365   302   302 E SMD     : DCD ON
,07-05 14:18:05.465   920  1236 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:08.365   302   302 E SMD     : DCD ON
,07-05 14:18:11.365   302   302 E SMD     : DCD ON
,07-05 14:18:14.375   302   302 E SMD     : DCD ON
,07-05 14:18:14.545   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:18:15.525   920  1464 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:15.525   920  1464 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:18:15.535   920  1464 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:18:15.535   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:18:15.545  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:18:15.545  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:18:15.555   920   920 I MotionRecognitionService: Plugged
,07-05 14:18:15.555   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:18:15.555   920  1464 D BatteryService: stay LED for fully charged
,07-05 14:18:15.575  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:18:15.585  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:15.585  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:18:15.585  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:18:15.585  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:18:15.585  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:17.365   302   302 E SMD     : DCD ON
,07-05 14:18:20.365   302   302 E SMD     : DCD ON
,07-05 14:18:23.365   302   302 E SMD     : DCD ON
,07-05 14:18:24.595   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:18:25.585   920   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:25.585   920   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:18:25.585   920   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:18:25.595   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:18:25.605  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:18:25.605  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:18:25.605   920   920 I MotionRecognitionService: Plugged
,07-05 14:18:25.615   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:18:25.615   920   935 D BatteryService: stay LED for fully charged
,07-05 14:18:25.635  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:18:25.635  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:25.635  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:18:25.635  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:25.645  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:18:25.645  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:18:25.665   920  1340 E Watchdog: !@Sync 32
,07-05 14:18:26.365   302   302 E SMD     : DCD ON
,07-05 14:18:28.685   920  1059 I PowerManagerService: [PWL] Off : 225s ago
,07-05 14:18:29.365   302   302 E SMD     : DCD ON
,07-05 14:18:32.365   302   302 E SMD     : DCD ON
,07-05 14:18:34.645   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:18:35.375   302   302 E SMD     : DCD ON
,07-05 14:18:35.645   920  1464 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:35.645   920  1464 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:18:35.655   920  1464 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:18:35.655   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:18:35.665  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:18:35.665  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:18:35.675   920   920 I MotionRecognitionService: Plugged
,07-05 14:18:35.675   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:18:35.685   920  1464 D BatteryService: stay LED for fully charged
,07-05 14:18:35.685  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:18:35.695  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:18:35.695  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:18:35.705  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:35.705  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:18:35.705  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:38.385   302   302 E SMD     : DCD ON
,07-05 14:18:41.375   302   302 E SMD     : DCD ON
,07-05 14:18:44.375   302   302 E SMD     : DCD ON
,07-05 14:18:44.685   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:18:45.705   920   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:45.705   920   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:18:45.715   920   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:18:45.715   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:18:45.725   920   920 I MotionRecognitionService: Plugged
,07-05 14:18:45.725  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:18:45.725  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:18:45.735   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:18:45.735   920   935 D BatteryService: stay LED for fully charged
,07-05 14:18:45.755  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:18:45.755  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:45.775  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:18:45.775  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:18:45.775  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:45.785  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:47.375   302   302 E SMD     : DCD ON
,07-05 14:18:50.385   302   302 E SMD     : DCD ON
,07-05 14:18:53.375   302   302 E SMD     : DCD ON
,07-05 14:18:54.735   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:18:55.665   920  1340 E Watchdog: !@Sync 33
,07-05 14:18:55.765   920  1464 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:55.765   920  1464 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:18:55.775   920  1464 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:18:55.775   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:18:55.785  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:18:55.785  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:18:55.795   920   920 I MotionRecognitionService: Plugged
,07-05 14:18:55.795   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:18:55.805   920  1464 D BatteryService: stay LED for fully charged
,07-05 14:18:55.815  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:18:55.835  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:55.835  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:18:55.835  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:18:55.845  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:55.855  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:56.375   302   302 E SMD     : DCD ON
,07-05 14:18:59.375   302   302 E SMD     : DCD ON
,07-05 14:19:02.385   302   302 E SMD     : DCD ON
,07-05 14:19:04.785   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:19:05.375   302   302 E SMD     : DCD ON
,07-05 14:19:05.825   920   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:19:05.825   920   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:19:05.835   920   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:19:05.835   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:19:05.845  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:19:05.845  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:19:05.855   920   920 I MotionRecognitionService: Plugged
,07-05 14:19:05.855   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:19:05.865   920   935 D BatteryService: stay LED for fully charged
,07-05 14:19:05.875  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:19:05.885  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:19:05.885  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:19:05.885  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:05.885  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:19:05.895  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:08.375   302   302 E SMD     : DCD ON
,07-05 14:19:11.385   302   302 E SMD     : DCD ON
,07-05 14:19:14.385   302   302 E SMD     : DCD ON
,07-05 14:19:14.825   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:19:15.885   920  1464 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:19:17.385   302   302 E SMD     : DCD ON
,07-05 14:19:18.685   920  1059 I PowerManagerService: [PWL] Off : 275s ago
,07-05 14:19:20.385   302   302 E SMD     : DCD ON
,07-05 14:19:23.385   302   302 E SMD     : DCD ON
,07-05 14:19:24.925   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:19:25.655   920  1340 E Watchdog: !@Sync 34
,07-05 14:19:25.945   920  2038 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:19:26.385   302   302 E SMD     : DCD ON
,07-05 14:19:29.385   302   302 E SMD     : DCD ON
,07-05 14:19:32.385   302   302 E SMD     : DCD ON
,07-05 14:19:34.975   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:19:35.395   302   302 E SMD     : DCD ON
,07-05 14:19:36.005   920  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:19:36.005   920  1359 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:19:36.015   920  1359 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:19:36.015   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:19:36.025  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:19:36.025  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:19:36.025   920   920 I MotionRecognitionService: Plugged
,07-05 14:19:36.035   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:19:36.035   920  1359 D BatteryService: stay LED for fully charged
,07-05 14:19:36.055  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:19:36.055  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:36.065  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:19:36.075  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:19:36.075  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:36.085  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:38.395   302   302 E SMD     : DCD ON
,07-05 14:19:41.385   302   302 E SMD     : DCD ON
,07-05 14:19:44.395   302   302 E SMD     : DCD ON
,07-05 14:19:45.015   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:19:46.065   920  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:19:46.065   920  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:19:46.075   920  1623 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:19:46.075   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:19:46.085  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:19:46.085  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:19:46.095   920   920 I MotionRecognitionService: Plugged
,07-05 14:19:46.095   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:19:46.105   920  1623 D BatteryService: stay LED for fully charged
,07-05 14:19:46.115  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:19:46.135  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:19:46.135  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:19:46.135  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:19:46.135  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:46.155  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:47.385   302   302 E SMD     : DCD ON
,07-05 14:19:50.395   302   302 E SMD     : DCD ON
,07-05 14:19:53.395   302   302 E SMD     : DCD ON
,07-05 14:19:55.065   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:19:55.655   920  1340 E Watchdog: !@Sync 35
,07-05 14:19:56.125   920  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:19:56.125   920  1359 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:19:56.125   920  1359 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:19:56.135   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:19:56.145   920   920 I MotionRecognitionService: Plugged
,07-05 14:19:56.145   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:19:56.145  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:19:56.155  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:19:56.155   920  1359 D BatteryService: stay LED for fully charged
,07-05 14:19:56.175  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:19:56.185  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:56.185  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:56.185  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:19:56.185  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:19:56.205  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:56.405   302   302 E SMD     : DCD ON
,07-05 14:19:59.405   302   302 E SMD     : DCD ON
,07-05 14:20:02.395   302   302 E SMD     : DCD ON
,07-05 14:20:05.115   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:20:05.395   302   302 E SMD     : DCD ON
,07-05 14:20:06.185   920  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:20:08.395   302   302 E SMD     : DCD ON
,07-05 14:20:11.405   302   302 E SMD     : DCD ON
,07-05 14:20:13.685   920  1059 I PowerManagerService: [PWL] Off : 330s ago
,07-05 14:20:14.405   302   302 E SMD     : DCD ON
,07-05 14:20:15.155   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:20:16.265   920  1236 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:20:16.265   920  1236 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:20:16.275   920  1236 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:20:16.275   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:20:16.285  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:20:16.285  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:20:16.285   920   920 I MotionRecognitionService: Plugged
,07-05 14:20:16.285   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:20:16.295  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:20:16.295   920  1236 D BatteryService: stay LED for fully charged
,07-05 14:20:16.295  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:20:16.295  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:20:16.305  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:16.315  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:16.315  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:17.395   302   302 E SMD     : DCD ON
,07-05 14:20:20.395   302   302 E SMD     : DCD ON
,07-05 14:20:23.395   302   302 E SMD     : DCD ON
,07-05 14:20:25.205   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:20:25.675   920  1340 E Watchdog: !@Sync 36
,07-05 14:20:26.315   920  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:20:26.325   920  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:20:26.325   920  3816 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:20:26.325   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:20:26.335  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:20:26.345  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:20:26.345   920   920 I MotionRecognitionService: Plugged
,07-05 14:20:26.345   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:20:26.355   920  3816 D BatteryService: stay LED for fully charged
,07-05 14:20:26.375  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:20:26.385  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:26.385  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:26.385  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:20:26.385  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:20:26.405  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:26.405   302   302 E SMD     : DCD ON
,07-05 14:20:29.405   302   302 E SMD     : DCD ON
,07-05 14:20:32.415   302   302 E SMD     : DCD ON
,07-05 14:20:35.255   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:20:35.405   302   302 E SMD     : DCD ON
,07-05 14:20:36.375   920  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:20:38.415   302   302 E SMD     : DCD ON
,07-05 14:20:41.405   302   302 E SMD     : DCD ON
,07-05 14:20:44.415   302   302 E SMD     : DCD ON
,07-05 14:20:45.305   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:20:46.435   920  1464 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:20:46.435   920  1464 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:20:46.445   920  1464 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:20:46.445   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:20:46.455  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:20:46.455  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:20:46.465   920   920 I MotionRecognitionService: Plugged
,07-05 14:20:46.465   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:20:46.475   920  1464 D BatteryService: stay LED for fully charged
,07-05 14:20:46.485  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:20:46.485  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:20:46.495  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:20:46.515  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:46.515  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:20:46.515  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:47.415   302   302 E SMD     : DCD ON
,07-05 14:20:50.405   302   302 E SMD     : DCD ON
,07-05 14:20:53.405   302   302 E SMD     : DCD ON
,07-05 14:20:55.345   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:20:55.665   920  1340 E Watchdog: !@Sync 37
,07-05 14:20:56.405   302   302 E SMD     : DCD ON
,07-05 14:20:56.495   920   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:20:56.495   920   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:20:56.495   920   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:20:56.505   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:20:56.515  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:20:56.515  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:20:56.515   920   920 I MotionRecognitionService: Plugged
,07-05 14:20:56.525   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:20:56.525   920   935 D BatteryService: stay LED for fully charged
,07-05 14:20:56.535  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:20:56.545  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:20:56.545  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:20:56.555  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:56.555  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:20:56.555  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:59.415   302   302 E SMD     : DCD ON
,07-05 14:20:59.995   920  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:21:00.025  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:21:00.025  1198  1198 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:21:00.035  1198  1198 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:21:00.045  1198  1198 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:21:00.145  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:21:00.155  1198  1198 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:21:02.405   302   302 E SMD     : DCD ON
,07-05 14:21:05.395   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:21:05.415   302   302 E SMD     : DCD ON
,07-05 14:21:06.555   920   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:21:08.425   302   302 E SMD     : DCD ON
,07-05 14:21:11.425   302   302 E SMD     : DCD ON
,07-05 14:21:13.705   920  1059 I PowerManagerService: [PWL] Off : 390s ago
,07-05 14:21:14.415   302   302 E SMD     : DCD ON
,07-05 14:21:15.445   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:21:15.635   920   933 I art     : Background sticky concurrent mark sweep GC freed 110261(9MB) AllocSpace objects, 308(5MB) LOS objects, 17% free, 37MB/45MB, paused 4.073ms total 182.194ms
,07-05 14:21:16.615   920  1520 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:21:16.615   920  1520 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:21:16.625   920  1520 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:21:16.625   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:21:16.635  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:21:16.635  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:21:16.645   920   920 I MotionRecognitionService: Plugged
,07-05 14:21:16.645   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:21:16.655   920  1520 D BatteryService: stay LED for fully charged
,07-05 14:21:16.665  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:21:16.685  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:16.685  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:16.685  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:21:16.685  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:21:16.695  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:17.425   302   302 E SMD     : DCD ON
,07-05 14:21:20.415   302   302 E SMD     : DCD ON
,07-05 14:21:23.415   302   302 E SMD     : DCD ON
,07-05 14:21:25.485   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:21:25.675   920  1340 E Watchdog: !@Sync 38
,07-05 14:21:26.415   302   302 E SMD     : DCD ON
,07-05 14:21:26.675   920  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:21:26.675   920  1144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:21:26.685   920  1144 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:21:26.685   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:21:26.695  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:21:26.695  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:21:26.705   920   920 I MotionRecognitionService: Plugged
,07-05 14:21:26.705   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:21:26.715   920  1144 D BatteryService: stay LED for fully charged
,07-05 14:21:26.725  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:21:26.735  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:26.735  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:21:26.735  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:21:26.735  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:26.735  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:29.425   302   302 E SMD     : DCD ON
,07-05 14:21:32.415   302   302 E SMD     : DCD ON
,07-05 14:21:35.425   302   302 E SMD     : DCD ON
,07-05 14:21:35.535   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:21:36.735   920  1520 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:21:38.425   302   302 E SMD     : DCD ON
,07-05 14:21:41.425   302   302 E SMD     : DCD ON
,07-05 14:21:44.425   302   302 E SMD     : DCD ON
,07-05 14:21:45.585   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:21:46.795   920  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:21:47.425   302   302 E SMD     : DCD ON
,07-05 14:21:50.435   302   302 E SMD     : DCD ON
,07-05 14:21:53.425   302   302 E SMD     : DCD ON
,07-05 14:21:55.675   920  1340 E Watchdog: !@Sync 39
,07-05 14:21:55.685   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:21:56.425   302   302 E SMD     : DCD ON
,07-05 14:21:56.855   920  1662 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:21:56.865   920  1662 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:21:56.865   920  1662 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:21:56.865   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:21:56.875   920   920 I MotionRecognitionService: Plugged
,07-05 14:21:56.875  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:21:56.885  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:21:56.885   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:21:56.885   920  1662 D BatteryService: stay LED for fully charged
,07-05 14:21:56.905  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:21:56.915  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:56.925  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:21:56.925  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:21:56.935  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:56.935  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:59.435   302   302 E SMD     : DCD ON
,07-05 14:21:59.995   920  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:22:02.425   302   302 E SMD     : DCD ON
,07-05 14:22:05.425   302   302 E SMD     : DCD ON
,07-05 14:22:05.725   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:22:06.915   920  1236 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:22:08.435   302   302 E SMD     : DCD ON
,07-05 14:22:11.425   302   302 E SMD     : DCD ON
,07-05 14:22:14.425   302   302 E SMD     : DCD ON
,07-05 14:22:15.775   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:22:16.985   920   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:22:16.985   920   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:22:16.985   920   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:22:16.995   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:22:16.995  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:22:17.005  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:22:17.005   920   920 I MotionRecognitionService: Plugged
,07-05 14:22:17.025   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:22:17.035   920   935 D BatteryService: stay LED for fully charged
,07-05 14:22:17.035  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:22:17.045  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:22:17.045  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:22:17.055  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:17.055  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:22:17.055  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:17.435   302   302 E SMD     : DCD ON
,07-05 14:22:18.695   920  1059 I PowerManagerService: [PWL] Off : 455s ago
,07-05 14:22:20.445   302   302 E SMD     : DCD ON
,07-05 14:22:23.035   920  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 14:22:23.035   920  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:22:23.035   920  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:22:23.435   920  1003 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 14:22:23.435   302   302 E SMD     : DCD ON
,07-05 14:22:23.505   920  1125 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,07-05 14:22:23.505   920  1125 I ApplicationUsage: Updating Usage Statistics in DB @ 1467721343521
,07-05 14:22:23.515   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:23.515   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.515   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:23.515   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-05 14:22:23.515   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,07-05 14:22:23.515   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,07-05 14:22:23.515   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.515   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.515   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.515   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.515   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.525   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.525   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.525   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-05 14:22:23.525   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
07-05 14:22:23.525   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,07-05 14:22:23.525   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.525   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.525   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.525   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.525   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:23.525   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.525   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.525   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,07-05 14:22:23.525   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
07-05 14:22:23.525   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
07-05 14:22:23.525   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.525   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:23.525   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.525   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.525   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.525   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.525   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:23.525   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,07-05 14:22:23.535   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
07-05 14:22:23.535   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,07-05 14:22:23.535   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.535   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.535   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.535   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.535   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.535   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.535   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.535   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:23.535   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.535   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.535   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.535   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.535   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.535   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.535   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.535   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.535   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.535   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:23.535   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.545   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.545   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.545   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.545   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:23.545   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.545   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.545   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:23.545   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.545   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.545   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:23.545   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.545   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.545   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.545   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.545   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.545   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:23.545   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.545   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.545   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.545   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.555   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.555   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.555   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.555   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.555   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:23.555   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:23.555   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.555   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.555   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.555   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.555   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.555   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.555   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.555   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.555   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.555   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:23.555   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.555   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.555   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.555   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.555   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.555   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.555   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.555   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.555   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.555   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:23.565   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:23.565   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.565   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.565   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.565   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.565   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.565   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.565   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.565   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.565   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:23.565   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.565   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.565   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.565   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.565   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.565   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.565   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.565   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.565   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.565   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:23.565   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:23.565   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.565   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.565   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.565   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.565   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:23.565   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.565   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
07-05 14:22:23.565   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:23.565   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.565   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.575   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:23.575   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.575   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.575   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.575   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.575   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.575   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.575   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:23.575   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.575   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.575   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:23.575   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.575   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.575   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.575   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.575   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.575   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.575   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.575   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.575   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.575   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:23.575   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.575   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.575   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.575   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.575   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:23.585   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.585   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.585   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.585   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.585   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:23.585   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.585   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.585   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.585   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.585   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.585   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.585   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.585   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.585   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.585   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:23.585   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.585   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.585   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.585   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.585   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.585   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.585   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.585   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.585   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.585   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:23.585   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.585   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.595   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.595   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:23.595   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.595   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.595   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:23.595   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.595   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:23.595   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.595   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.595   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:23.595   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.595   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.595   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:23.595   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.595   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.595   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.595   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.605   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.605   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.605   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:23.605   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.605   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.605   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:23.605   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.605   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.605   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:23.605   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.605   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.605   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:23.605   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.605   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.605   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.605   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.605   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.605   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.605   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.605   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.605   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.605   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.605   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:23.605   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.605   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.605   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.605   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.605   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:23.605   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:23.615   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.615   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.615   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.615   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.615   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.615   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.615   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:23.615   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.615   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:23.615   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:23.615   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.615   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.615   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.615   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.615   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.615   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:23.615   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.615   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.615   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.625   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.625   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.625   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:23.625   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.625   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.625   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:23.625   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.625   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.625   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:23.625   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.625   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:23.625   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:23.625   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.625   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.625   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.625   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.625   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.625   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.635   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.635   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.635   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.635   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.635   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.635   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:23.635   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.635   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.635   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:23.635   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.635   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:23.635   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.635   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.635   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:23.635   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.635   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.635   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:23.635   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.635   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.645   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:23.645   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.645   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.645   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.645   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.645   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.645   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.645   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:23.645   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.645   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.645   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.645   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.645   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.645   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.645   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.645   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.645   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.645   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.645   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.645   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.645   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.645   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.645   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.645   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.645   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.645   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.645   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.655   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.655   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.655   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.655   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.655   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:23.655   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:23.655   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.655   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.655   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.655   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.655   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.655   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.655   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.655   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.655   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.655   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.655   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.655   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.655   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.655   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.655   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.655   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:23.655   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.655   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.655   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.655   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.655   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.665   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.665   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:23.665   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.665   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.665   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.665   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.665   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.665   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.665   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.665   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.665   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.665   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.665   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.665   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.665   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.665   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.665   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.665   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.665   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.665   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:23.665   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.665   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.665   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.665   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.665   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.665   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.675   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:23.675   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.675   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.675   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.675   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.675   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.675   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:23.675   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.675   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.675   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.675   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.675   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.675   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:23.675   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:23.675   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.675   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:23.675   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.675   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.675   920  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:23.675   920  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:23.675   920  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:23.675   920  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:23.675   920  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:23.675   920  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:23.675   920  1125 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1467721343694
,07-05 14:22:25.675   920  1340 E Watchdog: !@Sync 40
,07-05 14:22:25.865   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:22:26.005   920  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 14:22:26.005   920  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:22:26.025   920  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:22:26.025   920  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:22:26.445   302   302 E SMD     : DCD ON
,07-05 14:22:27.035   920  3800 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:22:27.035   920  3800 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:22:27.045   920  3800 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:22:27.045   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:22:27.055  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:22:27.055  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:22:27.055   920   920 I MotionRecognitionService: Plugged
,07-05 14:22:27.065   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:22:27.065   920  3800 D BatteryService: stay LED for fully charged
,07-05 14:22:27.085  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:22:27.085  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:27.085  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:22:27.095  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:22:27.105  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:27.105  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:29.445   302   302 E SMD     : DCD ON
,07-05 14:22:32.445   302   302 E SMD     : DCD ON
,07-05 14:22:35.435   302   302 E SMD     : DCD ON
,07-05 14:22:35.925   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:22:37.095   920   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:22:37.095   920   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:22:37.105   920   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:22:37.105   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:22:37.115   920   920 I MotionRecognitionService: Plugged
,07-05 14:22:37.115  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:22:37.125  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:22:37.125   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:22:37.135   920   935 D BatteryService: stay LED for fully charged
,07-05 14:22:37.135  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:22:37.145  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:22:37.145  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:22:37.155  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:37.155  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:22:37.155  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:38.435   302   302 E SMD     : DCD ON
,07-05 14:22:41.445   302   302 E SMD     : DCD ON
,07-05 14:22:44.435   302   302 E SMD     : DCD ON
,07-05 14:22:45.975   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:22:47.155   920  3800 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:22:47.155   920  3800 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:22:47.165   920  3800 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:22:47.165   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:22:47.175  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:22:47.175  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:22:47.185   920   920 I MotionRecognitionService: Plugged
,07-05 14:22:47.185   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:22:47.185   920  3800 D BatteryService: stay LED for fully charged
,07-05 14:22:47.195  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:22:47.205  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:47.215  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:22:47.225  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:22:47.225  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:47.235  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:47.435   302   302 E SMD     : DCD ON
,07-05 14:22:50.435   302   302 E SMD     : DCD ON
,07-05 14:22:53.445   302   302 E SMD     : DCD ON
,07-05 14:22:55.675   920  1340 E Watchdog: !@Sync 41
,07-05 14:22:56.025   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:22:56.455   302   302 E SMD     : DCD ON
,07-05 14:22:57.215   920   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:22:59.455   302   302 E SMD     : DCD ON
,07-05 14:23:02.445   302   302 E SMD     : DCD ON
,07-05 14:23:05.455   302   302 E SMD     : DCD ON
,07-05 14:23:06.065   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:23:07.275   920  1520 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:23:07.275   920  1520 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:23:07.285   920  1520 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:23:07.285   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:23:07.295   920   920 I MotionRecognitionService: Plugged
,07-05 14:23:07.295  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:23:07.295  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:23:07.305   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:23:07.315   920  1520 D BatteryService: stay LED for fully charged
,07-05 14:23:07.325  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:23:07.335  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:07.335  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:07.335  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:23:07.335  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:23:07.345  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:08.445   302   302 E SMD     : DCD ON
,07-05 14:23:11.455   302   302 E SMD     : DCD ON
,07-05 14:23:14.455   302   302 E SMD     : DCD ON
,07-05 14:23:16.115   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:23:17.335   920  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:23:17.455   302   302 E SMD     : DCD ON
,07-05 14:23:20.455   302   302 E SMD     : DCD ON
,07-05 14:23:23.445   302   302 E SMD     : DCD ON
,07-05 14:23:25.685   920  1340 E Watchdog: !@Sync 42
,07-05 14:23:26.165   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:23:26.455   302   302 E SMD     : DCD ON
,07-05 14:23:27.395   920  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:23:27.395   920  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:23:27.395   920  3816 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:23:27.405   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:23:27.415  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:23:27.415  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:23:27.415   920   920 I MotionRecognitionService: Plugged
,07-05 14:23:27.425   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:23:27.425   920  3816 D BatteryService: stay LED for fully charged
,07-05 14:23:27.435  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:23:27.445  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:23:27.445  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:23:27.465  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:27.465  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:23:27.465  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:28.705   920  1059 I PowerManagerService: [PWL] Off : 525s ago
,07-05 14:23:29.455   302   302 E SMD     : DCD ON
,07-05 14:23:32.455   302   302 E SMD     : DCD ON
,07-05 14:23:35.465   302   302 E SMD     : DCD ON
,07-05 14:23:36.225   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:23:37.455   920  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:23:37.455   920  1359 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:23:37.455   920  1359 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:23:37.465   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:23:37.475  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:23:37.475  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:23:37.475   920   920 I MotionRecognitionService: Plugged
,07-05 14:23:37.485   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:23:37.485   920  1359 D BatteryService: stay LED for fully charged
,07-05 14:23:37.505  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:23:37.515  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:37.515  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:23:37.525  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:23:37.525  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:37.535  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:38.455   302   302 E SMD     : DCD ON
,07-05 14:23:41.455   302   302 E SMD     : DCD ON
,07-05 14:23:44.465   302   302 E SMD     : DCD ON
,07-05 14:23:46.285   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:23:47.465   302   302 E SMD     : DCD ON
,07-05 14:23:47.515   920  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:23:47.515   920  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:23:47.525   920  3816 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:23:47.525   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:23:47.535  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:23:47.535  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:23:47.545   920   920 I MotionRecognitionService: Plugged
,07-05 14:23:47.545   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:23:47.555   920  3816 D BatteryService: stay LED for fully charged
,07-05 14:23:47.565  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:23:47.585  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 14:23:47.585  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:47.585  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:23:47.585  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:23:47.595  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:50.465   302   302 E SMD     : DCD ON
,07-05 14:23:53.455   302   302 E SMD     : DCD ON
,07-05 14:23:55.685   920  1340 E Watchdog: !@Sync 43
,07-05 14:23:56.335   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:23:56.465   302   302 E SMD     : DCD ON
,07-05 14:23:57.575   920  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:23:59.465   302   302 E SMD     : DCD ON
,07-05 14:24:02.455   302   302 E SMD     : DCD ON
,07-05 14:24:05.465   302   302 E SMD     : DCD ON
,07-05 14:24:06.375   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:24:07.635   920  1662 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:24:08.465   302   302 E SMD     : DCD ON
,07-05 14:24:11.475   302   302 E SMD     : DCD ON
,07-05 14:24:14.465   302   302 E SMD     : DCD ON
,07-05 14:24:16.425   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:24:17.475   302   302 E SMD     : DCD ON
,07-05 14:24:17.695   920  3800 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:24:17.695   920  3800 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:24:17.695   920  3800 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:24:17.705   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:24:17.705  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:24:17.715  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:24:17.715   920   920 I MotionRecognitionService: Plugged
,07-05 14:24:17.725   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:24:17.725   920  3800 D BatteryService: stay LED for fully charged
,07-05 14:24:17.735  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:24:17.745  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:24:17.745  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:24:17.755  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:17.755  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:24:17.755  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:20.475   302   302 E SMD     : DCD ON
,07-05 14:24:23.475   302   302 E SMD     : DCD ON
,07-05 14:24:25.685   920  1340 E Watchdog: !@Sync 44
,07-05 14:24:26.475   302   302 E SMD     : DCD ON
,07-05 14:24:26.515   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:24:27.755   920   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:24:27.755   920   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:24:27.755   920   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:24:27.765   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:24:27.775  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:24:27.775  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:24:27.775   920   920 I MotionRecognitionService: Plugged
,07-05 14:24:27.785   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:24:27.785   920   935 D BatteryService: stay LED for fully charged
,07-05 14:24:27.805  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:24:27.805  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:27.815  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:27.825  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:24:27.825  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:24:27.825  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:29.475   302   302 E SMD     : DCD ON
,07-05 14:24:32.475   302   302 E SMD     : DCD ON
,07-05 14:24:35.465   302   302 E SMD     : DCD ON
,07-05 14:24:36.555   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:24:37.815   920  3800 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:24:38.475   302   302 E SMD     : DCD ON
,07-05 14:24:41.475   302   302 E SMD     : DCD ON
,07-05 14:24:43.695   920  1059 I PowerManagerService: [PWL] Off : 600s ago
,07-05 14:24:44.475   302   302 E SMD     : DCD ON
,07-05 14:24:46.605   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 14:24:47.475   302   302 E SMD     : DCD ON
,07-05 14:24:47.875   920  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:24:47.885   920  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:24:47.885   920  1319 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:24:47.885   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:24:47.895  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:24:47.895  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:24:47.905   920   920 I MotionRecognitionService: Plugged
,07-05 14:24:47.905   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:24:47.915   920  1319 D BatteryService: stay LED for fully charged
,07-05 14:24:47.925  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:24:47.935  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:47.935  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:47.935  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:24:47.935  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:24:47.945  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:50.485   302   302 E SMD     : DCD ON
,07-05 14:24:53.485   302   302 E SMD     : DCD ON
,07-05 14:24:55.695   920  1340 E Watchdog: !@Sync 45
,07-05 14:24:56.475   302   302 E SMD     : DCD ON
,07-05 14:24:56.655   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450
,07-05 14:24:57.935   920  2038 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:24:59.475   302   302 E SMD     : DCD ON
,07-05 14:25:02.485   302   302 E SMD     : DCD ON
,07-05 14:25:05.475   302   302 E SMD     : DCD ON
,07-05 14:25:06.695   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450
,07-05 14:25:07.995   920  1445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:25:07.995   920  1445 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:25:07.995   920  1445 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:25:08.005   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:25:08.015  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:25:08.015  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:25:08.015   920   920 I MotionRecognitionService: Plugged
,07-05 14:25:08.025   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:25:08.025   920  1445 D BatteryService: stay LED for fully charged
,07-05 14:25:08.035  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:25:08.045  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:25:08.045  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:25:08.065  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:08.065  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:25:08.065  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:08.475   302   302 E SMD     : DCD ON
,07-05 14:25:11.485   302   302 E SMD     : DCD ON
,07-05 14:25:14.485   302   302 E SMD     : DCD ON
,07-05 14:25:16.745   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450
,07-05 14:25:17.495   302   302 E SMD     : DCD ON
,07-05 14:25:18.055   920  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:25:18.055   920  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:25:18.055   920  1623 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:25:18.065   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:25:18.075  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:25:18.075  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:25:18.085   920   920 I MotionRecognitionService: Plugged
,07-05 14:25:18.085   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:25:18.085   920  1623 D BatteryService: stay LED for fully charged
,07-05 14:25:18.105  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:25:18.115  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:18.115  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:25:18.115  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:25:18.135  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:18.135  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:20.495   302   302 E SMD     : DCD ON
,07-05 14:25:23.485   302   302 E SMD     : DCD ON
,07-05 14:25:25.695   920  1340 E Watchdog: !@Sync 46
,07-05 14:25:26.495   302   302 E SMD     : DCD ON
,07-05 14:25:26.795   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450
,07-05 14:25:28.115   920  1445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:25:28.115   920  1445 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:25:28.115   920  1445 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:25:28.125   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:25:28.135  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:25:28.135  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:25:28.135   920   920 I MotionRecognitionService: Plugged
,07-05 14:25:28.145   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:25:28.145   920  1445 D BatteryService: stay LED for fully charged
,07-05 14:25:28.165  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:25:28.175  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:28.185  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:25:28.185  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:25:28.185  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:28.195  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:29.495   302   302 E SMD     : DCD ON
,07-05 14:25:32.485   302   302 E SMD     : DCD ON
,07-05 14:25:35.485   302   302 E SMD     : DCD ON
,07-05 14:25:36.845   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450
,07-05 14:25:38.175   920  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:25:38.175   920  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:25:38.175   920  1623 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:25:38.185   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:25:38.195  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:25:38.195  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:25:38.195   920   920 I MotionRecognitionService: Plugged
,07-05 14:25:38.205   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:25:38.215   920  1623 D BatteryService: stay LED for fully charged
,07-05 14:25:38.225  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:25:38.235  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:38.235  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:38.235  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:25:38.235  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:25:38.255  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:38.485   302   302 E SMD     : DCD ON
,07-05 14:25:41.485   302   302 E SMD     : DCD ON
,07-05 14:25:44.495   302   302 E SMD     : DCD ON
,07-05 14:25:46.925   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450
,07-05 14:25:47.485   302   302 E SMD     : DCD ON
,07-05 14:25:48.235   920  1445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:25:48.235   920  1445 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:25:48.235   920  1445 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:25:48.245   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:25:48.255  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:25:48.255  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:25:48.255   920   920 I MotionRecognitionService: Plugged
,07-05 14:25:48.265   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:25:48.275   920  1445 D BatteryService: stay LED for fully charged
,07-05 14:25:48.285  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:25:48.285  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:48.285  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:48.295  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:25:48.295  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:25:48.305  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:50.495   302   302 E SMD     : DCD ON
,07-05 14:25:53.505   302   302 E SMD     : DCD ON
,07-05 14:25:55.705   920  1340 E Watchdog: !@Sync 47
,07-05 14:25:56.505   302   302 E SMD     : DCD ON
,07-05 14:25:56.975   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,07-05 14:25:58.295   920  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:25:58.295   920  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:25:58.295   920  1623 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:25:58.305   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:25:58.315  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:25:58.315  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:25:58.315   920   920 I MotionRecognitionService: Plugged
,07-05 14:25:58.325   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:25:58.325   920  1623 D BatteryService: stay LED for fully charged
,07-05 14:25:58.335  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:25:58.345  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:25:58.345  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:25:58.365  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:58.365  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:25:58.365  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:59.495   302   302 E SMD     : DCD ON
,07-05 14:26:02.505   302   302 E SMD     : DCD ON
,07-05 14:26:03.705   920  1059 I PowerManagerService: [PWL] Off : 680s ago
,07-05 14:26:05.505   302   302 E SMD     : DCD ON
,07-05 14:26:07.035   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-05 14:26:08.355   920  1445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:26:08.355   920  1445 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:26:08.355   920  1445 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:26:08.365   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:26:08.375  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:26:08.375  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:26:08.375   920   920 I MotionRecognitionService: Plugged
,07-05 14:26:08.385   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:26:08.385   920  1445 D BatteryService: stay LED for fully charged
,07-05 14:26:08.395  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:26:08.405  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:08.415  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:08.415  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:26:08.425  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:26:08.425  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:08.495   302   302 E SMD     : DCD ON
,07-05 14:26:11.495   302   302 E SMD     : DCD ON
,07-05 14:26:14.495   302   302 E SMD     : DCD ON
,07-05 14:26:17.095   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 14:26:17.495   302   302 E SMD     : DCD ON
,07-05 14:26:18.415   920  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:26:20.495   302   302 E SMD     : DCD ON
,07-05 14:26:23.505   302   302 E SMD     : DCD ON
,07-05 14:26:25.705   920  1340 E Watchdog: !@Sync 48
,07-05 14:26:26.495   302   302 E SMD     : DCD ON
,07-05 14:26:27.145   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 14:26:28.475   920   936 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:26:29.505   302   302 E SMD     : DCD ON
,07-05 14:26:32.515   302   302 E SMD     : DCD ON
,07-05 14:26:35.515   302   302 E SMD     : DCD ON
,07-05 14:26:37.195   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 14:26:38.515   302   302 E SMD     : DCD ON
,07-05 14:26:38.535   920  1464 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:26:38.535   920  1464 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:26:38.535   920  1464 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:26:38.545   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:26:38.545  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:26:38.555  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:26:38.555   920   920 I MotionRecognitionService: Plugged
,07-05 14:26:38.565   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:26:38.565   920  1464 D BatteryService: stay LED for fully charged
,07-05 14:26:38.585  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:26:38.585  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:26:38.585  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:26:38.585  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:38.595  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:26:38.595  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:41.515   302   302 E SMD     : DCD ON
,07-05 14:26:44.515   302   302 E SMD     : DCD ON
,07-05 14:26:47.235   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 14:26:47.515   302   302 E SMD     : DCD ON
,07-05 14:26:48.595   920  1561 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:26:50.505   302   302 E SMD     : DCD ON
,07-05 14:26:53.505   302   302 E SMD     : DCD ON
,07-05 14:26:55.715   920  1340 E Watchdog: !@Sync 49
,07-05 14:26:56.505   302   302 E SMD     : DCD ON
,07-05 14:26:57.285   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 14:26:58.645   920  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:26:58.655   920  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:26:58.655   920  1319 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:26:58.655   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:26:58.665  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:26:58.675  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:26:58.675   920   920 I MotionRecognitionService: Plugged
,07-05 14:26:58.675   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:26:58.685   920  1319 D BatteryService: stay LED for fully charged
,07-05 14:26:58.685  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:26:58.695  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:26:58.695  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:26:58.705  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:58.705  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:26:58.705  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:59.505   302   302 E SMD     : DCD ON
,07-05 14:27:02.505   302   302 E SMD     : DCD ON
,07-05 14:27:05.515   302   302 E SMD     : DCD ON
,07-05 14:27:07.335   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 14:27:08.525   302   302 E SMD     : DCD ON
,07-05 14:27:08.715   920  2038 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:27:11.525   302   302 E SMD     : DCD ON
,07-05 14:27:14.515   302   302 E SMD     : DCD ON
,07-05 14:27:17.375   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 14:27:17.525   302   302 E SMD     : DCD ON
,07-05 14:27:18.775   920  1445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:27:18.775   920  1445 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:27:18.775   920  1445 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:27:18.785   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:27:18.795  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:27:18.795  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:27:18.795   920   920 I MotionRecognitionService: Plugged
,07-05 14:27:18.805   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:27:18.805   920  1445 D BatteryService: stay LED for fully charged
,07-05 14:27:18.825  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:27:18.835  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:27:18.835  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:27:18.835  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:27:18.835  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:27:18.855  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:27:20.525   302   302 E SMD     : DCD ON
,07-05 14:27:23.045   920  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 14:27:23.045   920  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:27:23.045   920  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:27:23.515   302   302 E SMD     : DCD ON
,07-05 14:27:25.715   920  1340 E Watchdog: !@Sync 50
,07-05 14:27:26.025   920  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 14:27:26.025   920  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:27:26.035   920  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:27:26.045   920  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:27:26.515   302   302 E SMD     : DCD ON
,07-05 14:27:27.425   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 301, CUR = 450
,07-05 14:27:28.705   920  1059 I PowerManagerService: [PWL] Off : 765s ago
,07-05 14:27:28.835   920  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:27:29.515   302   302 E SMD     : DCD ON
,07-05 14:27:32.515   302   302 E SMD     : DCD ON
,07-05 14:27:35.525   302   302 E SMD     : DCD ON
,07-05 14:27:37.475   920  3072 D SSRM:n  : SIOP:: AP = 310, PST = 302, CUR = 450
,07-05 14:27:38.515   302   302 E SMD     : DCD ON
,07-05 14:27:38.895   920   936 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:27:38.895   920   936 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:27:38.905   920   936 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:27:38.905   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:27:38.915  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:27:38.915  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:27:38.925   920   920 I MotionRecognitionService: Plugged
,07-05 14:27:38.925   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:27:38.925   920   936 D BatteryService: stay LED for fully charged
,07-05 14:27:38.935  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:27:38.945  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:27:38.945  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:27:38.965  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:27:38.965  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:27:38.965  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:27:41.525   302   302 E SMD     : DCD ON
,07-05 14:27:44.535   302   302 E SMD     : DCD ON
,07-05 14:27:47.525   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-05 14:27:47.525   302   302 E SMD     : DCD ON
,07-05 14:27:50.075   920  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:27:50.135   920  3816 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:27:50.135   920  3816 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:27:50.145   920  3816 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 14:27:50.145   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:27:50.155  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:27:50.155  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:27:50.165   920   920 I MotionRecognitionService: Plugged
,07-05 14:27:50.165   920   920 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:27:50.175   920  3816 D BatteryService: stay LED for fully charged
,07-05 14:27:50.185  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:27:50.195  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:27:50.195  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:27:50.215  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:27:50.215  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:27:50.215  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:27:50.525   302   302 E SMD     : DCD ON
,07-05 14:27:53.535   302   302 E SMD     : DCD ON
,07-05 14:27:55.725   920  1340 E Watchdog: !@Sync 51
,07-05 14:27:56.535   302   302 E SMD     : DCD ON
,07-05 14:27:57.575   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-05 14:27:59.535   302   302 E SMD     : DCD ON
,07-05 14:28:00.195   920  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:28:02.525   302   302 E SMD     : DCD ON
,07-05 14:28:05.525   302   302 E SMD     : DCD ON
,07-05 14:28:07.615   920  3072 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-05 14:28:08.535   302   302 E SMD     : DCD ON
,TIME-OUT KILL (timeout was 1400000ms),07-05 14:28:09.315  7767  7767 D AndroidRuntime: 
07-05 14:28:09.315  7767  7767 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 14:28:09.325  7767  7767 D AndroidRuntime: CheckJNI is OFF
07-05 14:28:09.325  7767  7767 D AndroidRuntime: readGMSProperty: start
07-05 14:28:09.325  7767  7767 D AndroidRuntime: readGMSProperty: already setted!!
07-05 14:28:09.325  7767  7767 D AndroidRuntime: readGMSProperty: end
07-05 14:28:09.325  7767  7767 D AndroidRuntime: addProductProperty: start
07-05 14:28:09.585  7767  7767 E AffinityControl: AffinityControl: registerfunction enter
07-05 14:28:09.625  7767  7767 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-05 14:28:09.635   920  1662 D PackageManager: START PACKAGE DELETE: observer{14810616}
07-05 14:28:09.635   920  1662 D PackageManager: pkg{<packageName>}
07-05 14:28:09.635   920  1662 D PackageManager: user{0}
07-05 14:28:09.635   920  1662 D PackageManager: caller{2000}
07-05 14:28:09.635   920  1662 D PackageManager: flags{2}
07-05 14:28:09.635   920  1662 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-05 14:28:09.635   920  1662 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-05 14:28:09.635   920  1662 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-05 14:28:09.635   920  1662 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 14:28:09.635   920  1662 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 14:28:09.645   920  1064 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-05 14:28:09.645   920  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-05 14:28:09.645   920  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-05 14:28:09.645   920  1064 D ApplicationPolicy: getApplicationUninstallationEnabled
07-05 14:28:09.645   920  1064 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-05 14:28:09.645   920  1064 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
07-05 14:28:09.645   920  1007 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
07-05 14:28:09.645   920  1007 I ActivityManager: Killing 7387:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
07-05 14:28:09.645   920  1007 I ActivityManager:   Force finishing activity ActivityRecord{2b7cf5fa u0 com.test.thalitest/.MainActivity t23}
07-05 14:28:09.655   920  1007 D FocusedStackFrame: Set to : 0
07-05 14:28:09.675   266   344 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
07-05 14:28:09.675   266   344 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
07-05 14:28:09.805   920  3072 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 14:28:09.825   920  1064 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
07-05 14:28:09.905  5297  5297 I art     : Explicit concurrent mark sweep GC freed 4547(254KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 15MB/26MB, paused 506us total 43.574ms
07-05 14:28:09.915   920  3276 E libprocessgroup: failed to kill 1 processes for processgroup 7387
07-05 14:28:09.915  1514  1514 I art     : Explicit concurrent mark sweep GC freed 490(31KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 19MB/32MB, paused 766us total 48.745ms
07-05 14:28:09.925   920  1057 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
07-05 14:28:09.925  1746  1746 E SamsungIME: mOCRHelper is null
07-05 14:28:09.935  1446  1446 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
07-05 14:28:09.935  1446  1446 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 14:28:09.935  1446  1446 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-05 14:28:09.935  1446  1446 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
07-05 14:28:09.935   920  1122 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-05 14:28:09.935  1446  1446 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 14:28:09.935  1446  1446 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 14:28:09.935  1446  1446 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-05 14:28:09.935  2010  2363 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-05 14:28:09.935  1415  1415 D RegisteredServicesCache: empty dynamic service
07-05 14:28:09.945  1446  1446 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
07-05 14:28:09.945  1446  1446 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 14:28:09.945  1446  1446 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-05 14:28:09.955  6784  6784 I art     : Explicit concurrent mark sweep GC freed 298(26KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 456us total 123.395ms
07-05 14:28:09.965  6238  6238 I art     : Explicit concurrent mark sweep GC freed 20203(2MB) AllocSpace objects, 2(40KB) LOS objects, 31% free, 17MB/25MB, paused 709us total 126.393ms
07-05 14:28:09.965  4300  4300 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-05 14:28:09.975   920  1146 V NetworkStats: removeUidsLocked() for UIDs [10079]
07-05 14:28:09.975   920  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 14:28:09.975   920  1146 V NetworkStats: performPollLocked(flags=0x3)
07-05 14:28:09.975   920  1146 D NetworkStatsFactory: UpdateStatsForKnox
07-05 14:28:09.975   920  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 14:28:09.985   920  1146 V NetworkStats: performPollLocked() took 7ms
07-05 14:28:09.985   920  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 14:28:09.985   920  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 14:28:09.985   920  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 14:28:09.985  4300  4300 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1467721689983
07-05 14:28:09.995  7262  7262 I art     : Explicit concurrent mark sweep GC freed 5016(355KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 536us total 154.520ms
07-05 14:28:09.995  4300  4300 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
07-05 14:28:10.005  4300  4300 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
07-05 14:28:10.055   920   920 I art     : Explicit concurrent mark sweep GC freed 70834(5MB) AllocSpace objects, 134(2MB) LOS objects, 30% free, 36MB/52MB, paused 3.057ms total 200.424ms
07-05 14:28:10.065   920   920 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
07-05 14:28:10.065   920  1064 I art     : WaitForGcToComplete blocked for 83.650ms for cause Explicit
07-05 14:28:10.085   920   920 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
07-05 14:28:10.095   920   920 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
07-05 14:28:10.095   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
07-05 14:28:10.105   920  3800 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-05 14:28:10.105   920  3800 D SecContentProvider2: mCursor = null
07-05 14:28:10.105   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
07-05 14:28:10.105   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
07-05 14:28:10.115   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
07-05 14:28:10.125   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
07-05 14:28:10.135   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
07-05 14:28:10.145   920   920 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
07-05 14:28:10.155   920   920 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
07-05 14:28:10.155   920   920 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
07-05 14:28:10.165  4300  4300 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
07-05 14:28:10.175   920   920 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
07-05 14:28:10.175   920   920 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
07-05 14:28:10.175   920   920 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
07-05 14:28:10.175   920   920 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
07-05 14:28:10.175  4300  4300 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
07-05 14:28:10.175   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
07-05 14:28:10.185  6818  6818 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
07-05 14:28:10.185   920  1464 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-05 14:28:10.185   920  1464 D ActivityManager: caller:android.app.ApplicationThreadProxy@218e0759, r.packageName :com.sec.esdk.elm
07-05 14:28:10.185   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
07-05 14:28:10.185   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
07-05 14:28:10.195  6818  6818 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
07-05 14:28:10.195   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
07-05 14:28:10.195  3590  3590 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
07-05 14:28:10.195  3590  3590 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 14:28:10.195  3590  3590 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
07-05 14:28:10.195  3590  3590 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-05 14:28:10.195  3590  3590 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-05 14:28:10.195  3590  3590 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-05 14:28:10.195  3590  3590 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-05 14:28:10.195  3590  3590 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:28:10.195  3590  3590 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:28:10.195  3590  3590 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-05 14:28:10.195  3590  3590 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:28:10.195  3590  3590 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 14:28:10.195  3590  3590 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-05 14:28:10.195  3590  3590 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-05 14:28:10.195   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
07-05 14:28:10.195   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
07-05 14:28:10.205   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
07-05 14:28:10.205   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
07-05 14:28:10.215   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
07-05 14:28:10.215  6818  6818 D elm:14491: ElmAgentService : onCreate()
07-05 14:28:10.215  6818  7796 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-05 14:28:10.215  6818  7796 D elm:14491: MainReceiver.listeningToPackageRemoved()
07-05 14:28:10.215  6818  7796 D elm:14491: MDMBridge.getInstance()
07-05 14:28:10.215  6818  7796 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
07-05 14:28:10.215  6818  7796 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
07-05 14:28:10.215   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
07-05 14:28:10.225  1654  1654 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-05 14:28:10.225  1654  1654 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
07-05 14:28:10.225   920   920 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
07-05 14:28:10.225   920  3800 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 14:28:10.225  6818  6818 D elm:14491: ElmAgentService : onDestroy().
07-05 14:28:10.225   920   920 D RCPManagerService: PackageReceiver onReceive()
07-05 14:28:10.225   920   920 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
07-05 14:28:10.225   920   920 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-05 14:28:10.225   920   920 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 14:28:10.235   920   920 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-05 14:28:10.235   920   920 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-05 14:28:10.235   920   920 V EnterpriseBillingPolicy: uID is 10079
07-05 14:28:10.235   920   920 V EnterpriseBillingPolicy: Removed Packageuid is0
07-05 14:28:10.235   920   920 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-05 14:28:10.235   920   920 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
07-05 14:28:10.235   920   920 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-05 14:28:10.235   920   920 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-05 14:28:10.235   920   920 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-05 14:28:10.235   920   920 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-05 14:28:10.235   920  1179 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
07-05 14:28:10.235   920  3072 D SSRM:aY : MSG_TYPE_APP_REMOVED::
07-05 14:28:10.235   920   920 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
07-05 14:28:10.235   920  1144 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-05 14:28:10.235   920  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@384dbc94, r.packageName :com.google.android.gms
07-05 14:28:10.245   920  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:28:10.245   920  1359 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:28:10.245   920  1359 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 14:28:10.245   920  1359 D BatteryService: stay LED for fully charged
07-05 14:28:10.245  2292  2292 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
07-05 14:28:10.245  2292  2292 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
07-05 14:28:10.245  2292  2292 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-05 14:28:10.245  2292  2292 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-05 14:28:10.255  2292  7798 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-05 14:28:10.255  2292  7798 D AccountUtils: Clearing selected account for com.test.thalitest
07-05 14:28:10.255   920  1319 D ActivityManager: caller:android.app.ApplicationThreadProxy@27940e00, r.packageName :com.google.android.gms
07-05 14:28:10.255  2292  2292 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
07-05 14:28:10.255  2292  2292 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
07-05 14:28:10.255  2292  2292 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-05 14:28:10.255  2292  2292 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-05 14:28:10.275   920  1464 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e2c0a2c, r.packageName :com.google.android.gms
07-05 14:28:10.275   920   920 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:28:10.275   920   920 I MotionRecognitionService: Plugged
07-05 14:28:10.275   920   920 I MotionRecognitionService: setPowerConnected  = true
07-05 14:28:10.275  1198  1198 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:28:10.285  1198  1198 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:28:10.285  1198  1198 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 14:28:10.285  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:28:10.285  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:28:10.285  3005  3005 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:28:10.285  3005  3205 D HeadsetStateMachine: Disconnected process message: 10
07-05 14:28:10.285  1198  1198 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:28:10.285  7018  7018 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
07-05 14:28:10.285   920  2038 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:28:10.285   920  2038 D ActivityManager: caller:android.app.ApplicationThreadProxy@35659d18, r.packageName :com.google.android.gms
07-05 14:28:10.285  7018  7018 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
07-05 14:28:10.285  7018  7018 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
07-05 14:28:10.285  2292  7798 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
07-05 14:28:10.295   920  1359 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
07-05 14:28:10.305  7033  7033 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-05 14:28:10.305  7033  7033 I PCWCLIENTTRACE_PushUtil: sales region : global
07-05 14:28:10.305  7033  7033 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-05 14:28:10.305  7033  7033 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
07-05 14:28:10.315   920  3800 D ActivityManager: caller:android.app.ApplicationThreadProxy@2f27c5ad, r.packageName :com.google.android.gms
07-05 14:28:10.325   920  3800 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:28:10.325   920  3800 D ActivityManager: caller:android.app.ApplicationThreadProxy@9903c73, r.packageName :com.google.android.gms
07-05 14:28:10.335   920  1561 D ActivityManager: startService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.sec.android.app.shealth
07-05 14:28:10.335   920  1561 D ActivityManager: caller:android.app.ApplicationThreadProxy@2b280fa9, r.packageName :com.sec.android.app.shealth
07-05 14:28:10.335   920  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
07-05 14:28:10.345   920  1064 I art     : Explicit concurrent mark sweep GC freed 18057(1026KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 36MB/52MB, paused 2.954ms total 284.251ms
07-05 14:28:10.365   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
07-05 14:28:10.365  2292  7803 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
07-05 14:28:10.365  2292  7803 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
07-05 14:28:10.375   920  1445 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:28:10.375   920  1445 D ActivityManager: caller:android.app.ApplicationThreadProxy@3b5c565c, r.packageName :com.google.android.gms
07-05 14:28:10.375  2292  7803 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
07-05 14:28:10.375  2292  7803 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
07-05 14:28:10.385  1654  1654 I ConfigService: onCreate
07-05 14:28:10.385  1654  1654 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-05 14:28:10.385  2292  7803 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
07-05 14:28:10.385  2292  7803 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
07-05 14:28:10.385  2292  7803 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
07-05 14:28:10.385   920  3800 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:28:10.385   920  3800 D ActivityManager: caller:android.app.ApplicationThreadProxy@2c86e6c7, r.packageName :com.google.android.gms
07-05 14:28:10.395  2292  2292 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-05 14:28:10.395   920   936 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
07-05 14:28:10.395  1654  1654 I ConfigService: onBind returning update interface
07-05 14:28:10.395   920   936 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:28:10.395   920   936 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:28:10.395   920   936 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:28:10.395   920   936 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:28:10.405   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
07-05 14:28:10.415  2292  7803 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
07-05 14:28:10.415  2292  7803 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
07-05 14:28:10.415  2292  7803 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
07-05 14:28:10.415   920  1003 D EnterpriseDeviceManagerService: Package has changed for user 0
07-05 14:28:10.415   920  1003 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-05 14:28:10.425   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
07-05 14:28:10.425   920  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
07-05 14:28:10.435  7808  7808 E Zygote  : MountEmulatedStorage()
07-05 14:28:10.435  7808  7808 E Zygote  : v2
07-05 14:28:10.435  7808  7808 I libpersona: KNOX_SDCARD checking this for 10043
07-05 14:28:10.435  7808  7808 I libpersona: KNOX_SDCARD not a persona
07-05 14:28:10.445   920  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:28:10.445   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
07-05 14:28:10.445   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
07-05 14:28:10.445   920   936 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7808 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 14:28:10.445   920  1064 D PackageManager: delete codoeFile: 
07-05 14:28:10.455  1654  1654 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-05 14:28:10.455  1654  1654 I ConfigService: onBind returning service broker
07-05 14:28:10.455   920  2038 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:28:10.455   920  1064 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
07-05 14:28:10.455   920  1064 I AASA_removePackage: UID=10079 Target=com.test.thalitest
07-05 14:28:10.455   920  2038 D ActivityManager: caller:android.app.ApplicationThreadProxy@18ca45ea, r.packageName :com.google.android.gms
07-05 14:28:10.455   920  1064 D PackageManager: result of delete: 1{14810616}
07-05 14:28:10.455   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
07-05 14:28:10.455   920  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:28:10.455   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
07-05 14:28:10.465   920  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
07-05 14:28:10.465   920  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:28:10.465   920  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
07-05 14:28:10.465   920  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:28:10.465   920  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
07-05 14:28:10.475   920  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:28:10.475  7808  7808 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 14:28:10.475  7808  7808 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 14:28:10.475   920  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:28:10.475   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
07-05 14:28:10.475  7808  7808 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-05 14:28:10.475  2292  7814 I PeopleContactsSync: CP2 sync disabled
07-05 14:28:10.475   920  1623 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:28:10.475   920  1623 D ActivityManager: caller:android.app.ApplicationThreadProxy@36bd9e8d, r.packageName :com.google.android.gms
07-05 14:28:10.485  2292  2292 I ConfigFetchService: service connected
07-05 14:28:10.485   920  1144 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
07-05 14:28:10.485   920  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@83cf053, r.packageName :com.samsung.android.app.galaxyfinder
07-05 14:28:10.485  7767  7767 D AndroidRuntime: Shutting down VM
07-05 14:28:10.485   920  1359 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:28:10.485   920  1359 D ActivityManager: caller:android.app.ApplicationThreadProxy@65dcd90, r.packageName :com.google.android.gms
07-05 14:28:10.495  2292  4110 I Icing   : doRemovePackageData com.test.thalitest
07-05 14:28:10.495  2292  7804 W BaseAppContext: Using Auth Proxy for data requests.
07-05 14:28:10.495  7808  7808 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:28:10.495  7808  7808 D ActivityThread: Added TimaKeyStore provider
07-05 14:28:10.505   920  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:28:10.505   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
07-05 14:28:10.505   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
07-05 14:28:10.515  2292  7804 W BaseAppContext: Using Auth Proxy for data requests.
07-05 14:28:10.515   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
07-05 14:28:10.515  7808  7808 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
07-05 14:28:10.515   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
07-05 14:28:10.525   920  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:28:10.525   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
07-05 14:28:10.525  1446  1446 D SurfaceWidgetView: destroyHardwareResources():19904590
07-05 14:28:10.525  1446  1446 D Launcher: onRestart, Launcher: 911062903
07-05 14:28:10.525  1446  1446 D Launcher: onStart, Launcher: 911062903
07-05 14:28:10.525  1446  1446 D Launcher.HomeView: onStart
07-05 14:28:10.525  1446  1446 V ActivityThread: updateVisibility : ActivityRecord{361b806e token=android.os.BinderProxy@1e2ef9af {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-05 14:28:10.525  1819  1833 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
07-05 14:28:10.525  1819  2000 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
07-05 14:28:10.525  1819  2000 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
07-05 14:28:10.535   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
07-05 14:28:10.545   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
07-05 14:28:10.545   266   266 I SurfaceFlinger: id=15 createSurf (1080x1920),1 flag=4, Mauncher
07-05 14:28:10.555   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
07-05 14:28:10.555   920  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:28:10.555   920  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:28:10.555   920  1003 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
07-05 14:28:10.555   920  1003 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-05 14:28:10.555   920  1003 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 14:28:10.555   920  1003 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 14:28:10.565   920  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:28:10.565   920  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
07-05 14:28:10.565  7808  7808 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
07-05 14:28:10.565  7808  7808 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
07-05 14:28:10.565   920  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:28:10.565   920  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
07-05 14:28:10.565   920  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:28:10.565   920  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
07-05 14:28:10.575  7808  7808 D SPPClientService: PushLog.txt file is not deleted.
07-05 14:28:10.575  7808  7808 D SPPClientService: PushLog.txt file is not deleted.
07-05 14:28:10.575  7808  7808 D SPPClientService: ============PushLog. stop!
07-05 14:28:10.575   920  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:28:10.575   920  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-05 14:28:10.575   920  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk

```
