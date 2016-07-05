#### Test 72145431fb64fa4_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system,
07-05 12:50:37.885   916  1061 I PowerManagerService: [PWL] Off : 105s ago
--------- beginning of main
07-05 12:50:38.164  7412  7412 D AndroidRuntime: 
07-05 12:50:38.164  7412  7412 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 12:50:38.164  7412  7412 D AndroidRuntime: CheckJNI is OFF
07-05 12:50:38.164  7412  7412 D AndroidRuntime: readGMSProperty: start
07-05 12:50:38.164  7412  7412 D AndroidRuntime: readGMSProperty: already setted!!
07-05 12:50:38.164  7412  7412 D AndroidRuntime: readGMSProperty: end
07-05 12:50:38.164  7412  7412 D AndroidRuntime: addProductProperty: start
07-05 12:50:38.294  7412  7412 E AffinityControl: AffinityControl: registerfunction enter
07-05 12:50:38.304   303   303 E SMD     : DCD ON
07-05 12:50:38.314  7412  7412 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 12:50:38.324   916  1713 E PersonaManagerService: inState():  stateMachine is null !!
07-05 12:50:38.324   916  1713 I PersonaManagerService: PersonaId don't exist
07-05 12:50:38.324   916  1713 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-05 12:50:38.324   916  1713 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 12:50:38.324   916  1713 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 12:50:38.324   916  1713 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-05 12:50:38.334   916  1713 W ActivityManager: mDVFSHelper.acquire()
07-05 12:50:38.334   916  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:38.334   916  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:38.334   916  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:38.334   916  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:38.374  7427  7427 E Zygote  : MountEmulatedStorage()
07-05 12:50:38.374  7427  7427 E Zygote  : v2
07-05 12:50:38.374  7427  7427 I libpersona: KNOX_SDCARD checking this for 10079
07-05 12:50:38.374  7427  7427 I libpersona: KNOX_SDCARD not a persona
07-05 12:50:38.374   916  1713 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7427 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 12:50:38.394  7427  7427 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 12:50:38.394  7427  7427 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 12:50:38.394  7412  7412 D AndroidRuntime: Shutting down VM
07-05 12:50:38.394  7427  7427 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-05 12:50:38.414  7427  7427 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:50:38.414  7427  7427 D ActivityThread: Added TimaKeyStore provider
07-05 12:50:38.434   916  3260 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 12:50:38.444  7427  7427 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-05 12:50:38.454  1448  1448 D SurfaceWidgetView: destroyHardwareResources():764520145
07-05 12:50:38.524  7427  7427 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-05 12:50:38.524  7427  7427 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
07-05 12:50:38.524   266   982 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
07-05 12:50:38.524   266   345 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
07-05 12:50:38.524  1759  1769 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
07-05 12:50:38.524  1448  1448 V ActivityThread: updateVisibility : ActivityRecord{3c4af118 token=android.os.BinderProxy@909659b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-05 12:50:38.524  1448  1448 D Launcher: onTrimMemory. Level: 20
07-05 12:50:38.544  7427  7427 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8464-8467)
07-05 12:50:38.544  7427  7427 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:50:38.564  7427  7427 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2febdde3}
07-05 12:50:38.564  7427  7427 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:50:38.564  7427  7427 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 12:50:38.604  7427  7427 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 12:50:38.604  7427  7427 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:50:38.604  7427  7427 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-05 12:50:38.644  7427  7427 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-05 12:50:38.644  7427  7427 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-05 12:50:38.644  7427  7427 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-05 12:50:38.654  7427  7427 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-05 12:50:38.654  7427  7427 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-05 12:50:38.654  7427  7427 I Adreno-EGL: Build Date: 11/19/14 Wed
07-05 12:50:38.654  7427  7427 I Adreno-EGL: Local Branch: mybranch5813579
07-05 12:50:38.654  7427  7427 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-05 12:50:38.654  7427  7427 I Adreno-EGL: Local Patches: NONE
07-05 12:50:38.654  7427  7427 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-05 12:50:38.804  7427  7459 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-05 12:50:38.834  7427  7427 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:50:38.854  7427  7427 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-05 12:50:38.864  7427  7427 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-05 12:50:38.874  7427  7427 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:50:38.874  7427  7427 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:50:38.934   916  1008 W ActivityManager: Activity pause timeout for ActivityRecord{155e3d6f u0 com.test.thalitest/.MainActivity t23}
,07-05 12:50:38.964  7427  7427 D Activity: performCreate Call secproduct feature valuefalse
07-05 12:50:38.974  7427  7427 D Activity: performCreate Call debug elastic valuetrue
,07-05 12:50:38.994  7427  7473 D OpenGLRenderer: Render dirty regions requested: true
,07-05 12:50:39.004   916  1517 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-05 12:50:39.004   916  1517 D KnoxTimeoutHandler: postActiveUserChange for user 0
,07-05 12:50:39.004   916  1517 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-05 12:50:39.004   916   916 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,07-05 12:50:39.004   916   916 D PersonaManagerService: getPersonasForUser(): returning null!
,07-05 12:50:39.024  7427  7427 V ActivityThread: updateVisibility : ActivityRecord{18f37bc5 token=android.os.BinderProxy@2cbb2c2f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-05 12:50:39.044   266   266 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,07-05 12:50:39.054  7427  7473 I OpenGLRenderer: Initialized EGL, version 1.4
,07-05 12:50:39.064  7427  7473 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xaf76e038 ,&mEglDisplay = 1 , &mEglConfig = 8 
,07-05 12:50:39.064  7427  7473 D OpenGLRenderer: Enabling debug mode 0
,07-05 12:50:39.094  7427  7427 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2cbb2c2f time:149019
,07-05 12:50:39.124   916  1059 W ActivityManager: mDVFSHelper.release()
07-05 12:50:39.124   916  1059 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{155e3d6f u0 com.test.thalitest/.MainActivity t23} time:149043
,07-05 12:50:39.124   916  1059 D MultiWindowConverter: This application or window do not support multiwindow
,07-05 12:50:39.184  7427  7427 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7427
,07-05 12:50:39.344  7427  7427 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 12:50:39.454  7427  7479 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258382720
,07-05 12:50:39.464  7427  7479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 12:50:39.464  7427  7479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 12:50:39.464  7427  7479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 12:50:39.464  7427  7479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 12:50:39.464  7427  7479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 12:50:39.464  7427  7479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1003e035 added. We now have 1 listener(s)
,07-05 12:50:39.474  7427  7479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:2A:28:2D
,07-05 12:50:39.474  7427  7479 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,07-05 12:50:39.484  7427  7479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-05 12:50:39.484  7427  7479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 12:50:39.494  7427  7479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 12:50:39.494  7427  7479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 12:50:39.494  7427  7479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 12:50:39.494  7427  7479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:2A:28:2D
07-05 12:50:39.494  7427  7479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 12:50:39.494  7427  7479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 12:50:39.494  7427  7479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 12:50:39.494  7427  7479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 12:50:39.494  7427  7479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 12:50:39.494  7427  7479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 12:50:39.494  7427  7479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 12:50:39.494  7427  7479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c499958 added. We now have 1 listener(s)
07-05 12:50:39.494  7427  7479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-05 12:50:39.514  7427  7479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,07-05 12:50:39.514  7427  7479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-05 12:50:39.514  7427  7479 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-05 12:50:39.524  7427  7479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 12:50:39.524  7427  7479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:2A:28:2D
,07-05 12:50:39.534   916  1713 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 12:50:39.544  7427  7479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 12:50:39.544  7427  7479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:50:39.544  7427  7479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 12:50:39.544  7427  7479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 12:50:39.544  7427  7479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 12:50:39.544  7427  7479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 12:50:39.544  7427  7479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 12:50:39.544  7427  7479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 12:50:39.544  7427  7479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 12:50:39.544  7427  7479 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-05 12:50:39.544   916  3588 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 12:50:39.544  7427  7479 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-05 12:50:39.544  7427  7427 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 12:50:39.544   916  1239 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 12:50:39.544  7427  7427 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 12:50:39.584  7427  7427 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 12:50:40.494  7427  7484 W jxcore-log: Initializing JXcore engine
07-05 12:50:40.494  7427  7484 W jxcore-log: JXcore engine is ready
,07-05 12:50:40.554  1934  1934 E auditd  : In denial and Property audit_ondenial is set to 1 
07-05 12:50:40.554  1934  1934 E audit   : type=1400 msg=audit(1467715840.554:203): avc:  denied  { ioctl } for  pid=7484 comm="Thread-1259" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-05 12:50:40.554  1934  1934 E audit   :  SEPF_SM-N9005_5.0-1_0032
07-05 12:50:40.554  1934  1934 E audit   : 
07-05 12:50:40.554   916  1042 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
,07-05 12:50:40.564   916  1042 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,07-05 12:50:40.564  1934  1934 E audit   : type=1300 msg=audit(1467715840.554:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9c1008d8 items=0 ppid=344 ppcomm=main pid=7484 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1259" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-05 12:50:40.564  1934  1934 E audit   : type=1320 msg=audit(1467715840.554:203): 
,07-05 12:50:40.564   916  1008 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,07-05 12:50:40.564   916  1042 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
07-05 12:50:40.564   916  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:40.564   916  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:40.564   916  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:40.564   916  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:40.584  7427  7484 W jxcore-log: Starting JXcore engine
,07-05 12:50:40.624  7486  7486 E Zygote  : MountEmulatedStorage()
07-05 12:50:40.624   916  1008 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7486 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-05 12:50:40.624  7486  7486 E Zygote  : v2
07-05 12:50:40.634  7486  7486 I libpersona: KNOX_SDCARD checking this for 1000
,07-05 12:50:40.634  7486  7486 I libpersona: KNOX_SDCARD not a persona
,07-05 12:50:40.654  7486  7486 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-05 12:50:40.654  7486  7486 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-05 12:50:40.654  7486  7486 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 12:50:40.704  7427  7484 W jxcore-log: Platform android
07-05 12:50:40.704  7427  7484 W jxcore-log: 
,07-05 12:50:40.704  7427  7484 W jxcore-log: Process ARCH arm
07-05 12:50:40.704  7427  7484 W jxcore-log: 
07-05 12:50:40.704  7486  7486 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 12:50:40.704  7486  7486 D ActivityThread: Added TimaKeyStore provider
,07-05 12:50:40.744  7486  7486 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,07-05 12:50:40.754  7486  7486 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-05 12:50:40.754  7486  7486 D SecurityLogAgent:  SeDenialReceiver : File path = null
,07-05 12:50:40.754   916  1420 I ActivityManager: Killing 6669:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 15): emptyCount ##41
,07-05 12:50:40.954  7427  7484 I jxcore-log: JXcore Cordova bridge is ready!
07-05 12:50:40.954  7427  7484 I jxcore-log: 
,07-05 12:50:40.954  7427  7484 W jxcore-log: JXcore engine is started
,07-05 12:50:40.964  7427  7479 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-05 12:50:40.974  7427  7427 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-05 12:50:41.234   916  2110 I art     : Explicit concurrent mark sweep GC freed 152662(8MB) AllocSpace objects, 14(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.608ms total 141.165ms
,07-05 12:50:41.304   303   303 E SMD     : DCD ON
,07-05 12:50:42.174   916   932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 12:50:42.174   916   932 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 12:50:42.174   916   932 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:50:42.174   916   932 D BatteryService: stay LED for fully charged
07-05 12:50:42.174   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:50:42.184   916   916 I MotionRecognitionService: Plugged,
07-05 12:50:42.184   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:50:42.184  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:50:42.184  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:50:42.194  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:50:42.204  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:50:42.204  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:50:42.204  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:50:42.204  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:50:42.224  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:50:43.994   916  3260 D SSRM:n  : SIOP:: AP = 360, PST = 359, CUR = 450
,07-05 12:50:44.304   303   303 E SMD     : DCD ON
,07-05 12:50:45.274   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:50:47.304   303   303 E SMD     : DCD ON
,07-05 12:50:48.374   916  1065 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-05 12:50:50.304   303   303 E SMD     : DCD ON
,07-05 12:50:50.524   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:50:50.834  7427  7484 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-05 12:50:50.834  7427  7484 I jxcore-log: 
,07-05 12:50:50.844  7427  7484 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-05 12:50:50.844  7427  7484 I jxcore-log: 
,07-05 12:50:50.844   916  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 12:50:50.844  7427  7484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 12:50:50.844  7427  7484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:50:50.844  7427  7484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 12:50:50.844  7427  7484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 12:50:50.844  7427  7484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 12:50:50.844  7427  7484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 12:50:50.844  7427  7484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 12:50:50.844  7427  7484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 12:50:50.844  7427  7484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-05 12:50:50.844  7427  7484 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-05 12:50:50.844  7427  7484 I jxcore-log: 
,07-05 12:50:50.844  7427  7484 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
07-05 12:50:50.844  7427  7484 I jxcore-log: 
,07-05 12:50:51.214  7427  7484 I jxcore-log: Unit Test app is loaded,
07-05 12:50:51.214  7427  7484 I jxcore-log: 
,07-05 12:50:51.214  7427  7484 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-05 12:50:51.214  7427  7484 I jxcore-log: 
,07-05 12:50:51.224  7427  7484 I jxcore-log: My device name is: samsung-SM-N9005
07-05 12:50:51.224  7427  7484 I jxcore-log: 
,07-05 12:50:51.224  7427  7484 I jxcore-log: WARN testUtils: myNameCallback not set!
07-05 12:50:51.224  7427  7484 I jxcore-log: 
,07-05 12:50:51.234  7427  7427 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-05 12:50:51.524   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:50:52.244   916   932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:50:52.244   916   932 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:50:52.254   916   932 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:50:52.254   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:50:52.254   916   932 D BatteryService: stay LED for fully charged
,07-05 12:50:52.254  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:50:52.254  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 12:50:52.254   916   916 I MotionRecognitionService: Plugged
07-05 12:50:52.254   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:50:52.254  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:50:52.254  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:50:52.254  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:50:52.254  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:50:52.254  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:50:52.254  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:50:52.524   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:50:53.314   303   303 E SMD     : DCD ON
,07-05 12:50:53.524   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:50:54.034   916  3260 D SSRM:n  : SIOP:: AP = 380, PST = 357, CUR = 450
,07-05 12:50:54.524   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:50:54.974  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-05 12:50:54.974  7427  7484 I jxcore-log: 
,07-05 12:50:55.374  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-05 12:50:55.374  7427  7484 I jxcore-log: 
,07-05 12:50:55.394  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-05 12:50:55.394  7427  7484 I jxcore-log: 
,07-05 12:50:55.404  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-05 12:50:55.404  7427  7484 I jxcore-log: 
,07-05 12:50:55.414  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-05 12:50:55.414  7427  7484 I jxcore-log: 
,07-05 12:50:55.414  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-05 12:50:55.414  7427  7484 I jxcore-log: 
,07-05 12:50:55.524   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:50:56.314   303   303 E SMD     : DCD ON
,07-05 12:50:57.314  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-05 12:50:57.314  7427  7484 I jxcore-log: 
,07-05 12:50:57.324  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-05 12:50:57.324  7427  7484 I jxcore-log: 
,07-05 12:50:57.334  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-05 12:50:57.334  7427  7484 I jxcore-log: 
,07-05 12:50:57.484  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-05 12:50:57.484  7427  7484 I jxcore-log: 
,07-05 12:50:57.564  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-05 12:50:57.564  7427  7484 I jxcore-log: 
,07-05 12:50:57.624  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-05 12:50:57.624  7427  7484 I jxcore-log: 
,07-05 12:50:57.624  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-05 12:50:57.624  7427  7484 I jxcore-log: 
,07-05 12:50:57.814  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-05 12:50:57.814  7427  7484 I jxcore-log: 
,07-05 12:50:57.834  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-05 12:50:57.834  7427  7484 I jxcore-log: 
,07-05 12:50:57.834  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-05 12:50:57.834  7427  7484 I jxcore-log: 
,07-05 12:50:57.844  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-05 12:50:57.844  7427  7484 I jxcore-log: 
,07-05 12:50:57.854  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-05 12:50:57.854  7427  7484 I jxcore-log: 
,07-05 12:50:57.874  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-05 12:50:57.874  7427  7484 I jxcore-log: 
,07-05 12:50:57.964  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-05 12:50:57.964  7427  7484 I jxcore-log: 
,07-05 12:50:57.964  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-05 12:50:57.964  7427  7484 I jxcore-log: 
,07-05 12:50:57.994  7427  7484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-05 12:50:57.994  7427  7484 I jxcore-log: 
,07-05 12:50:58.004  7427  7484 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-05 12:50:58.004  7427  7484 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-05 12:50:58.004  7427  7484 I jxcore-log: 
,07-05 12:50:58.634   916  1321 E Watchdog: !@Sync 5
,07-05 12:50:59.314   303   303 E SMD     : DCD ON
,07-05 12:50:59.984   916  1113 V AlarmManager: waitForAlarm result :8
,07-05 12:51:02.324   303   303 E SMD     : DCD ON
,07-05 12:51:02.484   916  1113 V AlarmManager: waitForAlarm result :4
,07-05 12:51:02.544  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 12:51:02.544  1196  1196 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 12:51:02.554   916   934 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 12:51:02.554   916  1239 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:51:02.554   916  1239 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:51:02.554  1196  1196 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 12:51:02.554  1196  1196 I KeyguardEffectViewController: *** don't update sliding image ***
07-05 12:51:02.554   916  1239 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:51:02.554   916  1239 D BatteryService: stay LED for fully charged
,07-05 12:51:02.554   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:51:02.574   916   916 I MotionRecognitionService: Plugged
,07-05 12:51:02.574   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:51:02.584  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:51:02.584  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:51:02.584  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:51:02.584  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:51:02.594  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:51:02.594  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:51:02.594  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:51:02.594  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:51:02.624   916  4028 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-05 12:51:02.624   916  4028 D ActivityManager: caller:android.app.ApplicationThreadProxy@3792e574, r.packageName :com.google.android.gms
,07-05 12:51:02.654  1196  1196 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:51:02.664  1196  1196 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:51:04.074   916  3260 D SSRM:n  : SIOP:: AP = 350, PST = 354, CUR = 450
,07-05 12:51:05.284   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:51:05.314   303   303 E SMD     : DCD ON
,07-05 12:51:08.314   303   303 E SMD     : DCD ON
,07-05 12:51:11.314   303   303 E SMD     : DCD ON
,07-05 12:51:12.604   916  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:51:12.894   916  1061 I PowerManagerService: [PWL] Off : 140s ago
,07-05 12:51:14.124   916  3260 D SSRM:n  : SIOP:: AP = 340, PST = 352, CUR = 450
,07-05 12:51:14.324   303   303 E SMD     : DCD ON
,07-05 12:51:15.524   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:51:16.534   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:51:17.314   303   303 E SMD     : DCD ON
,07-05 12:51:17.544   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:51:18.534   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:51:19.534   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:51:20.324   303   303 E SMD     : DCD ON
,07-05 12:51:20.534   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 12:51:22.664   916  1517 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:51:22.674   916  1517 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:51:22.674   916  1517 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:51:22.674   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:51:22.674   916   916 I MotionRecognitionService: Plugged
,07-05 12:51:22.674   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:51:22.684  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:51:22.684  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:51:22.684  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:51:22.684  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:51:22.694  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:51:22.694   916  1517 D BatteryService: stay LED for fully charged
,07-05 12:51:22.694  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:51:22.694  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:51:22.694  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:51:23.314   303   303 E SMD     : DCD ON
,07-05 12:51:24.174   916  3260 D SSRM:n  : SIOP:: AP = 330, PST = 350, CUR = 450
,07-05 12:51:25.274   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:51:26.314   303   303 E SMD     : DCD ON
,07-05 12:51:28.634   916  1321 E Watchdog: !@Sync 6
,07-05 12:51:29.324   303   303 E SMD     : DCD ON
,07-05 12:51:32.334   303   303 E SMD     : DCD ON
,07-05 12:51:32.724   916  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:51:34.224   916  3260 D SSRM:n  : SIOP:: AP = 330, PST = 349, CUR = 450
,07-05 12:51:35.324   303   303 E SMD     : DCD ON
,07-05 12:51:38.334   303   303 E SMD     : DCD ON
,07-05 12:51:41.324   303   303 E SMD     : DCD ON
,07-05 12:51:42.784   916  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:51:42.794   916  2110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:51:42.794   916  2110 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:51:42.794   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:51:42.794  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:51:42.794  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:51:42.804   916   916 I MotionRecognitionService: Plugged
,07-05 12:51:42.804   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:51:42.804  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:51:42.804   916  2110 D BatteryService: stay LED for fully charged
,07-05 12:51:42.804  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:51:42.814  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:51:42.814  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:51:42.814  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:51:42.814  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:51:44.274   916  3260 D SSRM:n  : SIOP:: AP = 320, PST = 347, CUR = 450
,07-05 12:51:44.334   303   303 E SMD     : DCD ON
,07-05 12:51:45.284   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:51:45.544   363   363 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 12:51:45.544   363   363 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 12:51:47.324   303   303 E SMD     : DCD ON
,07-05 12:51:50.324   303   303 E SMD     : DCD ON
,07-05 12:51:52.854   916  1364 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:51:52.854   916  1364 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:51:52.854   916  1364 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:51:52.854   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:51:52.864   916   916 I MotionRecognitionService: Plugged
,07-05 12:51:52.864   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:51:52.864  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:51:52.874  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:51:52.874   916  1364 D BatteryService: stay LED for fully charged
,07-05 12:51:52.874  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:51:52.884  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:51:52.884  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:51:52.884   916  1061 I PowerManagerService: [PWL] Off : 180s ago
07-05 12:51:52.894  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:51:52.894  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:51:52.894  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:51:53.334   303   303 E SMD     : DCD ON
,07-05 12:51:54.314   916  3260 D SSRM:n  : SIOP:: AP = 320, PST = 343, CUR = 450
,07-05 12:51:55.534   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:51:56.334   303   303 E SMD     : DCD ON
,07-05 12:51:56.544   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:51:57.544   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:51:58.544   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:51:58.654   916  1321 E Watchdog: !@Sync 7
,07-05 12:51:59.324   303   303 E SMD     : DCD ON
,07-05 12:51:59.554   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:51:59.994   916  1113 V AlarmManager: waitForAlarm result :8
,07-05 12:52:00.554   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 12:52:02.324   303   303 E SMD     : DCD ON
,07-05 12:52:02.914   916  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:52:02.914   916  2110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:52:02.914   916  2110 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:52:02.924   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:52:02.924  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:52:02.924  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:52:02.934   916   916 I MotionRecognitionService: Plugged
,07-05 12:52:02.934   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:52:02.934   916  2110 D BatteryService: stay LED for fully charged
,07-05 12:52:02.934  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:52:02.944  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:52:02.944  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:52:02.954  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:52:02.954  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:52:02.954  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:52:04.364   916  3260 D SSRM:n  : SIOP:: AP = 320, PST = 339, CUR = 450
,07-05 12:52:05.284   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:52:05.344   303   303 E SMD     : DCD ON
,07-05 12:52:05.544   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:52:06.554   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:52:07.554   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:52:08.334   303   303 E SMD     : DCD ON
,07-05 12:52:08.544   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:52:09.544   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:52:10.544   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 12:52:11.344   303   303 E SMD     : DCD ON
,07-05 12:52:12.974   916  1364 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:52:12.974   916  1364 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:52:12.974   916  1364 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:52:12.974   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:52:12.984  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:52:12.984  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:52:12.994   916   916 I MotionRecognitionService: Plugged
,07-05 12:52:12.994   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:52:12.994  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:52:12.994   916  1364 D BatteryService: stay LED for fully charged
,07-05 12:52:13.004  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:52:13.004  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:52:13.014  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:52:13.014  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:52:13.014  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:52:14.344   303   303 E SMD     : DCD ON
,07-05 12:52:14.414   916  3260 D SSRM:n  : SIOP:: AP = 320, PST = 337, CUR = 450
,07-05 12:52:17.334   303   303 E SMD     : DCD ON
,07-05 12:52:20.344   303   303 E SMD     : DCD ON
,07-05 12:52:20.544   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:52:21.554   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:52:22.554   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:52:23.034   916  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:52:23.034   916  2110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:52:23.034   916  2110 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:52:23.044   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:52:23.044  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:52:23.054  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:52:23.054   916   916 I MotionRecognitionService: Plugged
,07-05 12:52:23.054   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:52:23.054   916  2110 D BatteryService: stay LED for fully charged
,07-05 12:52:23.064  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:52:23.074  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:52:23.074  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:52:23.074  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:52:23.084  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:52:23.094  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:52:23.344   303   303 E SMD     : DCD ON
,07-05 12:52:23.554   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:52:24.464   916  3260 D SSRM:n  : SIOP:: AP = 320, PST = 333, CUR = 450
,07-05 12:52:24.554   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:52:25.284   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:52:25.554   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 12:52:26.344   303   303 E SMD     : DCD ON
,07-05 12:52:28.654   916  1321 E Watchdog: !@Sync 8
,07-05 12:52:29.344   303   303 E SMD     : DCD ON
,07-05 12:52:32.344   303   303 E SMD     : DCD ON
,07-05 12:52:33.094   916  1364 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:52:33.104   916  1364 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:52:33.104   916  1364 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:52:33.104   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:52:33.114  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:52:33.114  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:52:33.124   916   916 I MotionRecognitionService: Plugged
,07-05 12:52:33.124   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:52:33.124  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:52:33.124   916  1364 D BatteryService: stay LED for fully charged
,07-05 12:52:33.124  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:52:33.124  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:52:33.124  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:52:33.134  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:52:33.134  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:52:34.504   916  3260 D SSRM:n  : SIOP:: AP = 320, PST = 327, CUR = 450
,07-05 12:52:35.334   303   303 E SMD     : DCD ON
,07-05 12:52:37.884   916  1061 I PowerManagerService: [PWL] Off : 225s ago
,07-05 12:52:38.334   303   303 E SMD     : DCD ON
,07-05 12:52:40.554   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:52:41.344   303   303 E SMD     : DCD ON
,07-05 12:52:41.564   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:52:42.564   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:52:43.154   916  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:52:43.154   916  2110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:52:43.154   916  2110 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:52:43.164   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:52:43.164  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:52:43.174  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:52:43.174   916   916 I MotionRecognitionService: Plugged
,07-05 12:52:43.174   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:52:43.184  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:52:43.184   916  2110 D BatteryService: stay LED for fully charged
,07-05 12:52:43.194  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:52:43.194  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:52:43.194  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:52:43.214  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:52:43.214  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:52:43.554   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:52:44.354   303   303 E SMD     : DCD ON
,07-05 12:52:44.554   916  3260 D SSRM:n  : SIOP:: AP = 320, PST = 324, CUR = 450
,07-05 12:52:44.564   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:52:45.304   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:52:45.564   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:52:47.344   303   303 E SMD     : DCD ON
,07-05 12:52:50.344   303   303 E SMD     : DCD ON
,07-05 12:52:53.214   916  1239 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:52:53.354   303   303 E SMD     : DCD ON
,07-05 12:52:54.604   916  3260 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 450
,07-05 12:52:56.354   303   303 E SMD     : DCD ON
,07-05 12:52:58.644   916  1321 E Watchdog: !@Sync 9
,07-05 12:52:59.344   303   303 E SMD     : DCD ON
,07-05 12:53:02.354   303   303 E SMD     : DCD ON
,07-05 12:53:04.654   916  3260 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 450
,07-05 12:53:05.294   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:53:05.344   303   303 E SMD     : DCD ON
,07-05 12:53:05.574   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:53:06.564   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:53:07.574   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:53:08.344   303   303 E SMD     : DCD ON
,07-05 12:53:08.564   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:53:09.434   916  1113 V AlarmManager: waitForAlarm result :4
,07-05 12:53:09.454  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 12:53:09.454  1196  1196 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 12:53:09.454  1196  1196 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 12:53:09.454  1196  1196 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 12:53:09.474   916   932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:53:09.474   916   932 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 12:53:09.474   916   932 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:53:09.474   916   932 D BatteryService: stay LED for fully charged
,07-05 12:53:09.484   916  1419 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 12:53:09.514   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:53:09.514  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:53:09.514  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:53:09.524   916   916 I MotionRecognitionService: Plugged
,07-05 12:53:09.524   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:53:09.524  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:53:09.534  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:53:09.534  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:53:09.534  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:53:09.534  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:53:09.554  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:53:09.554   916  1419 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-05 12:53:09.554   916  1419 D ActivityManager: caller:android.app.ApplicationThreadProxy@2627e399, r.packageName :com.google.android.gms
,07-05 12:53:09.554  1196  1196 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:53:09.564  1196  1196 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:53:09.564   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:53:09.604   916  3588 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 12:53:10.564   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 12:53:11.344   303   303 E SMD     : DCD ON
,07-05 12:53:14.354   303   303 E SMD     : DCD ON
,07-05 12:53:14.704   916  3260 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 12:53:17.354   303   303 E SMD     : DCD ON
,07-05 12:53:19.544   916  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:53:20.364   303   303 E SMD     : DCD ON
,07-05 12:53:23.364   303   303 E SMD     : DCD ON
,07-05 12:53:24.744   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 450
,07-05 12:53:25.304   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:53:25.874   916  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 12:53:25.874   916  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 12:53:25.874   916  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 12:53:25.884   916  1102 I TLC_TIMA_PKM_initialize: initializing...
,07-05 12:53:25.884   916  1102 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,07-05 12:53:25.884   916  1102 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,07-05 12:53:25.894   916  1102 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,07-05 12:53:25.894   916  1102 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,07-05 12:53:25.894   916  1102 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-05 12:53:25.894   916  1102 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,07-05 12:53:25.894   916  1102 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080,
07-05 12:53:25.904   916  1102 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-05 12:53:25.904   916  1102 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 12:53:25.924   916  1102 D QSEECOMAPI: : Loaded image: APP id = 2
,07-05 12:53:25.934   916  1102 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-05 12:53:25.934   916  1102 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-05 12:53:26.354   303   303 E SMD     : DCD ON
,07-05 12:53:27.884   916  1061 I PowerManagerService: [PWL] Off : 275s ago
,07-05 12:53:27.884   916  1061 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,07-05 12:53:27.894   916  1061 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,07-05 12:53:27.894   916  1061 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=916, ws=null) (elapsedTime=2016)
,07-05 12:53:28.654   916  1321 E Watchdog: !@Sync 10
,07-05 12:53:28.774   916  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 12:53:28.774   916  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 12:53:28.784   916  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:53:28.784   916  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:53:29.354   303   303 E SMD     : DCD ON
,07-05 12:53:29.594   916   932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:53:29.604   916   932 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:53:29.604   916   932 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:53:29.604   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:53:29.614   916   916 I MotionRecognitionService: Plugged
,07-05 12:53:29.614   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:53:29.624  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:53:29.624  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:53:29.624   916   932 D BatteryService: stay LED for fully charged
,07-05 12:53:29.634  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:53:29.644  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:53:29.644  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:53:29.644  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:53:29.654  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:53:29.664  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:53:32.364   303   303 E SMD     : DCD ON
,07-05 12:53:34.794   916  3260 D SSRM:n  : SIOP:: AP = 320, PST = 319, CUR = 450
,07-05 12:53:35.354   303   303 E SMD     : DCD ON
,07-05 12:53:35.574   363   363 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 12:53:35.574   363   363 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 12:53:38.354   303   303 E SMD     : DCD ON
,07-05 12:53:41.354   303   303 E SMD     : DCD ON
,07-05 12:53:44.364   303   303 E SMD     : DCD ON
,07-05 12:53:44.674   916  1113 V AlarmManager: waitForAlarm result :4
,07-05 12:53:44.684   916  1008 D ActivityManager: startProcessLocked calleePkgName: com.blurb.checkout, hostingType: broadcast
,07-05 12:53:44.684   916  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:53:44.684   916  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:53:44.684   916  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:53:44.684   916  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:53:44.724   916  1420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:53:44.724   916  1420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:53:44.734   916  1420 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:53:44.734   916  1420 D BatteryService: stay LED for fully charged
07-05 12:53:44.734   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:53:44.754   916  1008 I ActivityManager: Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7591 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 12:53:44.764  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:53:44.764  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:53:44.764   916   916 I MotionRecognitionService: Plugged
07-05 12:53:44.764   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:53:44.774  7591  7591 E Zygote  : MountEmulatedStorage()
,07-05 12:53:44.774  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:53:44.784  7591  7591 E Zygote  : v2
07-05 12:53:44.784  7591  7591 I libpersona: KNOX_SDCARD checking this for 10096
07-05 12:53:44.784  7591  7591 I libpersona: KNOX_SDCARD not a persona
,07-05 12:53:44.784  7591  7591 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 12:53:44.784  7591  7591 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 12:53:44.784  7591  7591 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-05 12:53:44.794  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:53:44.794  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:53:44.814  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:53:44.814  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:53:44.814  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:53:44.834   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 318, CUR = 450
,07-05 12:53:44.844  7591  7591 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 12:53:44.844  7591  7591 D ActivityThread: Added TimaKeyStore provider
,07-05 12:53:44.884  7591  7591 D ResourcesManager: creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,07-05 12:53:44.894   916  1451 D ActivityManager: startService callerProcessName:com.blurb.checkout, calleePkgName: com.blurb.checkout
07-05 12:53:44.894   916  1451 D ActivityManager: caller:android.app.ApplicationThreadProxy@e116f0c, r.packageName :com.blurb.checkout
,07-05 12:53:44.934   916  1364 I ActivityManager: Killing 6689:com.android.calendar/u0a172 (adj 15): emptyCount ##41
,07-05 12:53:45.304   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:53:47.354   303   303 E SMD     : DCD ON
,07-05 12:53:50.354   303   303 E SMD     : DCD ON
,07-05 12:53:50.574   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:53:51.574   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:53:52.584   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:53:53.374   303   303 E SMD     : DCD ON
,07-05 12:53:53.574   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:53:54.574   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:53:54.794   916  3344 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:53:54.804   916  3344 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:53:54.804   916  3344 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:53:54.804   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:53:54.804   916   916 I MotionRecognitionService: Plugged
,07-05 12:53:54.804   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:53:54.814  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:53:54.814  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:53:54.814  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:53:54.814  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:53:54.814   916  3344 D BatteryService: stay LED for fully charged
,07-05 12:53:54.824  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:53:54.824  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:53:54.824  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:53:54.824  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:53:54.864   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 450
,07-05 12:53:55.584   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 12:53:56.364   303   303 E SMD     : DCD ON
,07-05 12:53:58.654   916  1321 E Watchdog: !@Sync 11
,07-05 12:53:59.364   303   303 E SMD     : DCD ON
,07-05 12:53:59.984   916  1113 V AlarmManager: waitForAlarm result :8
,07-05 12:54:00.574   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:54:01.584   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:54:02.364   303   303 E SMD     : DCD ON
,07-05 12:54:02.574   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:54:03.584   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:54:04.584   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:54:04.864   916   932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:54:04.924   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 450
,07-05 12:54:05.304   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:54:05.364   303   303 E SMD     : DCD ON
,07-05 12:54:05.584   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 12:54:08.364   303   303 E SMD     : DCD ON
,07-05 12:54:11.364   303   303 E SMD     : DCD ON
,07-05 12:54:14.364   303   303 E SMD     : DCD ON
,07-05 12:54:14.924   916  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:54:14.934   916  1451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:54:14.934   916  1451 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:54:14.934   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:54:14.944   916   916 I MotionRecognitionService: Plugged
,07-05 12:54:14.944   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:54:14.944  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:54:14.944  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:54:14.954  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:54:14.954  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:54:14.954   916  1451 D BatteryService: stay LED for fully charged
07-05 12:54:14.954  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:54:14.954  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:54:14.954  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:54:14.964  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:54:15.004   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 450
,07-05 12:54:15.584   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:54:16.594   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:54:17.364   303   303 E SMD     : DCD ON
,07-05 12:54:17.584   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:54:18.594   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:54:19.584   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:54:20.364   303   303 E SMD     : DCD ON
,07-05 12:54:20.594   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 12:54:22.894   916  1061 I PowerManagerService: [PWL] Off : 330s ago
,07-05 12:54:23.374   303   303 E SMD     : DCD ON
,07-05 12:54:24.984   916   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:54:24.984   916   934 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:54:24.984   916   934 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:54:24.984   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:54:24.994  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:54:24.994  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:54:25.004   916   916 I MotionRecognitionService: Plugged
07-05 12:54:25.004   916   916 I MotionRecognitionService: setPowerConnected  = true
07-05 12:54:25.004   916   934 D BatteryService: stay LED for fully charged
,07-05 12:54:25.014  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:54:25.024  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:54:25.024  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:54:25.024  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:54:25.034  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:54:25.034  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:54:25.044   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 450
,07-05 12:54:25.314   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:54:26.364   303   303 E SMD     : DCD ON
,07-05 12:54:28.664   916  1321 E Watchdog: !@Sync 12
,07-05 12:54:29.374   303   303 E SMD     : DCD ON
,07-05 12:54:32.374   303   303 E SMD     : DCD ON
,07-05 12:54:35.044   916  1420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:54:35.044   916  1420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:54:35.044   916  1420 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:54:35.044   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:54:35.054  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:54:35.054  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:54:35.064   916   916 I MotionRecognitionService: Plugged
,07-05 12:54:35.064   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:54:35.064   916  1420 D BatteryService: stay LED for fully charged
,07-05 12:54:35.064  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:54:35.074  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:54:35.074  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:54:35.084  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:54:35.084  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:54:35.084  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:54:35.104   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 450
,07-05 12:54:35.384   303   303 E SMD     : DCD ON
,07-05 12:54:35.594   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:54:36.594   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:54:37.594   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:54:38.384   303   303 E SMD     : DCD ON
,07-05 12:54:38.594   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:54:39.604   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:54:40.604   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:54:41.384   303   303 E SMD     : DCD ON
,07-05 12:54:44.384   303   303 E SMD     : DCD ON
,07-05 12:54:45.104   916   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:54:45.104   916   934 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:54:45.104   916   934 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:54:45.104   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:54:45.114  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:54:45.124  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:54:45.124   916   916 I MotionRecognitionService: Plugged
,07-05 12:54:45.124   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:54:45.124   916   934 D BatteryService: stay LED for fully charged
,07-05 12:54:45.134  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:54:45.144  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:54:45.144  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:54:45.164  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:54:45.164  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:54:45.164  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:54:45.174   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 450
,07-05 12:54:45.314   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:54:47.384   303   303 E SMD     : DCD ON
,07-05 12:54:50.374   303   303 E SMD     : DCD ON
,07-05 12:54:53.384   303   303 E SMD     : DCD ON
,07-05 12:54:55.164   916  1420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:54:55.164   916  1420 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:54:55.164   916  1420 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:54:55.164   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:54:55.174  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:54:55.174  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:54:55.174   916   916 I MotionRecognitionService: Plugged
,07-05 12:54:55.184   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:54:55.184   916  1420 D BatteryService: stay LED for fully charged
,07-05 12:54:55.184  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:54:55.194  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:54:55.194  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:54:55.204  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:54:55.204  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:54:55.204  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:54:55.224   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,07-05 12:54:56.384   303   303 E SMD     : DCD ON
,07-05 12:54:58.654   916  1321 E Watchdog: !@Sync 13
,07-05 12:54:59.384   303   303 E SMD     : DCD ON
,07-05 12:55:00.594   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:55:01.604   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:55:02.374   303   303 E SMD     : DCD ON
,07-05 12:55:02.604   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:55:03.604   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:55:04.594   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:55:05.224   916   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:55:05.224   916   934 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:55:05.224   916   934 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:55:05.224   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:55:05.234  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:55:05.234  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:55:05.244   916   916 I MotionRecognitionService: Plugged
,07-05 12:55:05.244   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:55:05.244   916   934 D BatteryService: stay LED for fully charged
,07-05 12:55:05.244  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:55:05.254  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:55:05.254  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:55:05.264  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:55:05.264  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:55:05.264  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:55:05.284   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,07-05 12:55:05.324   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:55:05.384   303   303 E SMD     : DCD ON
,07-05 12:55:05.604   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 12:55:08.384   303   303 E SMD     : DCD ON
,07-05 12:55:11.394   303   303 E SMD     : DCD ON
,07-05 12:55:14.394   303   303 E SMD     : DCD ON
,07-05 12:55:15.284   916  1420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:55:15.324   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:55:17.384   303   303 E SMD     : DCD ON
,07-05 12:55:20.384   303   303 E SMD     : DCD ON
,07-05 12:55:22.894   916  1061 I PowerManagerService: [PWL] Off : 390s ago
,07-05 12:55:23.384   303   303 E SMD     : DCD ON
,07-05 12:55:25.334   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:55:25.354   916  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:55:25.354   916  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:55:25.354   916  1476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:55:25.364   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:55:25.364   916   916 I MotionRecognitionService: Plugged
,07-05 12:55:25.364   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:55:25.364  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:55:25.374  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:55:25.374  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:55:25.374   916  1476 D BatteryService: stay LED for fully charged
,07-05 12:55:25.374  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:55:25.374  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:55:25.384  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:55:25.384  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:55:25.384  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:55:25.384   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:55:26.384   303   303 E SMD     : DCD ON
,07-05 12:55:28.664   916  1321 E Watchdog: !@Sync 14
,07-05 12:55:29.394   303   303 E SMD     : DCD ON
,07-05 12:55:30.604   363   363 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 12:55:30.604   363   363 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 12:55:32.394   303   303 E SMD     : DCD ON
,07-05 12:55:35.384   303   303 E SMD     : DCD ON
,07-05 12:55:35.404   916  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:55:35.404   916  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:55:35.414   916  4028 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:55:35.414   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:55:35.424  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:55:35.424  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:55:35.424   916   916 I MotionRecognitionService: Plugged
07-05 12:55:35.424   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:55:35.424   916  4028 D BatteryService: stay LED for fully charged
,07-05 12:55:35.424  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:55:35.434  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:55:35.434  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:55:35.444   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:55:35.444  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:55:35.444  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:55:35.444  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:55:38.384   303   303 E SMD     : DCD ON
,07-05 12:55:41.394   303   303 E SMD     : DCD ON
,07-05 12:55:44.404   303   303 E SMD     : DCD ON
,07-05 12:55:45.334   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:55:45.464   916  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:55:45.474   916  2110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:55:45.474   916  2110 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:55:45.474   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:55:45.484  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:55:45.484   916   916 I MotionRecognitionService: Plugged
,07-05 12:55:45.484  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:55:45.484   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:55:45.494  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:55:45.494  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:55:45.494  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:55:45.494  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:55:45.494  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:55:45.494   916  2110 D BatteryService: stay LED for fully charged
,07-05 12:55:45.504   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:55:45.514  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:55:47.404   303   303 E SMD     : DCD ON
,07-05 12:55:50.394   303   303 E SMD     : DCD ON
,07-05 12:55:50.614   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:55:51.604   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:55:52.604   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:55:53.404   303   303 E SMD     : DCD ON
,07-05 12:55:53.614   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:55:54.614   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:55:55.524   916  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:55:55.564   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:55:55.604   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 12:55:56.404   303   303 E SMD     : DCD ON
,07-05 12:55:58.664   916  1321 E Watchdog: !@Sync 15
,07-05 12:55:59.394   303   303 E SMD     : DCD ON
,07-05 12:56:00.614   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:56:01.604   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:56:02.404   303   303 E SMD     : DCD ON
,07-05 12:56:02.614   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:56:03.624   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:56:04.614   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:56:05.334   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:56:05.394   303   303 E SMD     : DCD ON
,07-05 12:56:05.584   916  1239 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:56:05.594   916  1239 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:56:05.594   916  1239 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:56:05.594   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:56:05.604   916   916 I MotionRecognitionService: Plugged
,07-05 12:56:05.604   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:56:05.604  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:56:05.604  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:56:05.614  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:56:05.614   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 12:56:05.614  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:56:05.614  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:56:05.614  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:56:05.614  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:56:05.624  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:56:05.624   916  1239 D BatteryService: stay LED for fully charged
,07-05 12:56:05.624   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:56:08.394   303   303 E SMD     : DCD ON
,07-05 12:56:11.394   303   303 E SMD     : DCD ON
,07-05 12:56:14.394   303   303 E SMD     : DCD ON
,07-05 12:56:15.624   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:56:15.644   916  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:56:15.644   916  1482 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:56:15.644   916  1482 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:56:15.644   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:56:15.654  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:56:15.654  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:56:15.664   916   916 I MotionRecognitionService: Plugged
,07-05 12:56:15.664   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:56:15.664   916  1482 D BatteryService: stay LED for fully charged
,07-05 12:56:15.674  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:56:15.674  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:56:15.674  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:56:15.674  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:56:15.674  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:56:15.674  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:56:15.684   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:56:16.624   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:56:17.044   359   359 I bootchecker: bootchecker wake up!!
,07-05 12:56:17.404   303   303 E SMD     : DCD ON
,07-05 12:56:17.624   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:56:18.624   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:56:19.614   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:56:20.414   303   303 E SMD     : DCD ON
,07-05 12:56:20.624   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 12:56:23.404   303   303 E SMD     : DCD ON
,07-05 12:56:25.354   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:56:25.704   916  1364 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:56:25.734   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:56:26.404   303   303 E SMD     : DCD ON
,07-05 12:56:27.904   916  1061 I PowerManagerService: [PWL] Off : 455s ago
,07-05 12:56:28.674   916  1321 E Watchdog: !@Sync 16
,07-05 12:56:29.414   303   303 E SMD     : DCD ON
,07-05 12:56:32.404   303   303 E SMD     : DCD ON
,07-05 12:56:35.404   303   303 E SMD     : DCD ON
,07-05 12:56:35.624   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:56:35.764   916   932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:56:35.774   916   932 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:56:35.774   916   932 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:56:35.774   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:56:35.784  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:56:35.784  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:56:35.784   916   916 I MotionRecognitionService: Plugged
,07-05 12:56:35.784   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:56:35.794   916   932 D BatteryService: stay LED for fully charged
,07-05 12:56:35.794  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:56:35.804  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:56:35.814   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:56:35.814  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:56:35.814  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:56:35.824  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:56:35.824  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:56:36.624   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:56:37.624   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:56:38.404   303   303 E SMD     : DCD ON
,07-05 12:56:38.624   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:56:39.634   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:56:40.624   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:56:41.414   303   303 E SMD     : DCD ON
,07-05 12:56:44.414   303   303 E SMD     : DCD ON
,07-05 12:56:45.344   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:56:45.824   916  3344 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:56:45.864   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:56:47.414   303   303 E SMD     : DCD ON
,07-05 12:56:50.404   303   303 E SMD     : DCD ON
,07-05 12:56:53.414   303   303 E SMD     : DCD ON
,07-05 12:56:55.884   916   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:56:55.924   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:56:56.414   303   303 E SMD     : DCD ON
,07-05 12:56:58.674   916  1321 E Watchdog: !@Sync 17
,07-05 12:56:59.414   303   303 E SMD     : DCD ON
,07-05 12:57:00.624   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:57:01.624   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:57:02.414   303   303 E SMD     : DCD ON
,07-05 12:57:02.634   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:57:03.644   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:57:04.644   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:57:05.344   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:57:05.414   303   303 E SMD     : DCD ON
,07-05 12:57:05.634   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 12:57:05.944   916  1419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:57:05.944   916  1419 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:57:05.944   916  1419 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:57:05.954   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:57:05.964  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:57:05.964  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:57:05.964   916   916 I MotionRecognitionService: Plugged
07-05 12:57:05.964   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:57:05.964   916  1419 D BatteryService: stay LED for fully charged
,07-05 12:57:05.964  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:57:05.974  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:57:05.974  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:57:05.984   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:57:05.984  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:57:05.984  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:57:05.984  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:57:08.424   303   303 E SMD     : DCD ON
,07-05 12:57:11.424   303   303 E SMD     : DCD ON
,07-05 12:57:14.424   303   303 E SMD     : DCD ON
,07-05 12:57:16.004   916  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:57:16.004   916  2110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:57:16.004   916  2110 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:57:16.014   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:57:16.024  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:57:16.024  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:57:16.024   916   916 I MotionRecognitionService: Plugged
07-05 12:57:16.024   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:57:16.024   916  2110 D BatteryService: stay LED for fully charged
,07-05 12:57:16.024  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:57:16.034  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:57:16.034  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:57:16.044   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:57:16.044  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:57:16.044  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:57:16.044  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:57:17.424   303   303 E SMD     : DCD ON
,07-05 12:57:20.424   303   303 E SMD     : DCD ON
,07-05 12:57:23.414   303   303 E SMD     : DCD ON
,07-05 12:57:25.364   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:57:26.064   916  1419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:57:26.104   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450
,07-05 12:57:26.424   303   303 E SMD     : DCD ON
,07-05 12:57:28.684   916  1321 E Watchdog: !@Sync 18
,07-05 12:57:29.424   303   303 E SMD     : DCD ON
,07-05 12:57:30.644   363   363 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 12:57:30.644   363   363 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 12:57:32.424   303   303 E SMD     : DCD ON
,07-05 12:57:35.424   303   303 E SMD     : DCD ON
,07-05 12:57:36.124   916  1239 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:57:36.124   916  1239 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:57:36.124   916  1239 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:57:36.134   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:57:36.134   916   916 I MotionRecognitionService: Plugged
,07-05 12:57:36.144  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:57:36.144  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:57:36.144   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:57:36.144   916  1239 D BatteryService: stay LED for fully charged
,07-05 12:57:36.154  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:57:36.164   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450
,07-05 12:57:36.174  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:57:36.174  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:57:36.184  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:57:36.184  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:57:36.184  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:57:37.904   916  1061 I PowerManagerService: [PWL] Off : 525s ago
,07-05 12:57:38.434   303   303 E SMD     : DCD ON
,07-05 12:57:41.424   303   303 E SMD     : DCD ON
,07-05 12:57:44.434   303   303 E SMD     : DCD ON
,07-05 12:57:45.354   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:57:46.184   916  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:57:46.194   916  1223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:57:46.194   916  1223 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:57:46.194   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:57:46.204  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:57:46.204   916   916 I MotionRecognitionService: Plugged
,07-05 12:57:46.204  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:57:46.204   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:57:46.214   916  1223 D BatteryService: stay LED for fully charged
,07-05 12:57:46.214  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:57:46.214  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:57:46.214  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:57:46.214  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:57:46.214  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:57:46.214  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:57:46.254   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450
,07-05 12:57:47.434   303   303 E SMD     : DCD ON
,07-05 12:57:50.434   303   303 E SMD     : DCD ON
,07-05 12:57:53.424   303   303 E SMD     : DCD ON
,07-05 12:57:55.644   363   363 I Atfwd_Daemon: Stop the daemon....
,07-05 12:57:56.244   916  1239 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:57:56.254   916  1239 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:57:56.254   916  1239 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:57:56.254   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:57:56.264  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:57:56.264  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:57:56.274  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:57:56.274  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:57:56.274   916   916 I MotionRecognitionService: Plugged
07-05 12:57:56.274   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:57:56.274  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:57:56.274  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:57:56.274  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:57:56.274  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:57:56.274   916  1239 D BatteryService: stay LED for fully charged
,07-05 12:57:56.304   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450
,07-05 12:57:56.424   303   303 E SMD     : DCD ON
,07-05 12:57:58.674   916  1321 E Watchdog: !@Sync 19
,07-05 12:57:59.434   303   303 E SMD     : DCD ON
,07-05 12:58:02.434   303   303 E SMD     : DCD ON
,07-05 12:58:05.354   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:58:05.434   303   303 E SMD     : DCD ON
,07-05 12:58:06.304   916  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:58:06.304   916  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:58:06.304   916  4028 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:58:06.304   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:58:06.314  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:58:06.314  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:58:06.314   916   916 I MotionRecognitionService: Plugged
,07-05 12:58:06.324   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:58:06.324   916  4028 D BatteryService: stay LED for fully charged
,07-05 12:58:06.324  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:58:06.334  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:58:06.334  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:58:06.344  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:58:06.344  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:58:06.344  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:58:06.364   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450
,07-05 12:58:08.434   303   303 E SMD     : DCD ON
,07-05 12:58:11.444   303   303 E SMD     : DCD ON
,07-05 12:58:14.444   303   303 E SMD     : DCD ON
,07-05 12:58:16.364   916  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:58:16.414   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450
,07-05 12:58:17.444   303   303 E SMD     : DCD ON
,07-05 12:58:20.434   303   303 E SMD     : DCD ON
,07-05 12:58:23.434   303   303 E SMD     : DCD ON
,07-05 12:58:25.364   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:58:25.864   916  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 12:58:25.864   916  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 12:58:25.864   916  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 12:58:26.434   916  3588 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:58:26.434   303   303 E SMD     : DCD ON
,07-05 12:58:26.484   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,07-05 12:58:28.684   916  1321 E Watchdog: !@Sync 20
,07-05 12:58:28.754   916  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 12:58:28.754   916  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 12:58:28.764   916  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:58:28.774   916  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:58:29.434   303   303 E SMD     : DCD ON
,07-05 12:58:32.444   303   303 E SMD     : DCD ON
,07-05 12:58:35.444   303   303 E SMD     : DCD ON
,07-05 12:58:36.494   916  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:58:36.494   916  1451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:58:36.494   916  1451 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:58:36.504   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:58:36.504   916   916 I MotionRecognitionService: Plugged
,07-05 12:58:36.504   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:58:36.504  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:58:36.514  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:58:36.514  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:58:36.514  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:58:36.524  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:58:36.524   916  1451 D BatteryService: stay LED for fully charged
07-05 12:58:36.524  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:58:36.534  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:58:36.534  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:58:36.544   916  3260 D SSRM:n  : SIOP:: AP = 310, PST = 303, CUR = 450
,07-05 12:58:38.444   303   303 E SMD     : DCD ON
,07-05 12:58:41.444   303   303 E SMD     : DCD ON
,07-05 12:58:44.444   303   303 E SMD     : DCD ON
,07-05 12:58:45.364   916  3273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:58:46.554   916  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:58:46.554   916  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:58:46.564   916  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:58:46.564   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:58:46.564   916   916 I MotionRecognitionService: Plugged
,07-05 12:58:46.564  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:58:46.564  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:58:46.564   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:58:46.574  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:58:46.574  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:58:46.574   916  1713 D BatteryService: stay LED for fully charged
,07-05 12:58:46.574  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:58:46.584  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:58:46.584  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:58:46.594  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:58:46.604   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-05 12:58:47.444   303   303 E SMD     : DCD ON
,07-05 12:58:50.444   303   303 E SMD     : DCD ON
,07-05 12:58:52.914   916  1061 I PowerManagerService: [PWL] Off : 600s ago
,07-05 12:58:53.444   303   303 E SMD     : DCD ON
,07-05 12:58:56.454   303   303 E SMD     : DCD ON
,07-05 12:58:56.614   916  3344 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:58:56.614   916  3344 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:58:56.624   916  3344 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:58:56.624   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:58:56.624  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:58:56.634  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:58:56.634  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:58:56.634   916   916 I MotionRecognitionService: Plugged
,07-05 12:58:56.634  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:58:56.634   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:58:56.634  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:58:56.634   916  3344 D BatteryService: stay LED for fully charged
,07-05 12:58:56.644  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:58:56.644  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:58:56.644  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:58:56.664   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:58:58.694   916  1321 E Watchdog: !@Sync 21
,07-05 12:58:59.444   303   303 E SMD     : DCD ON
,07-05 12:59:02.454   303   303 E SMD     : DCD ON
,07-05 12:59:05.444   303   303 E SMD     : DCD ON
,07-05 12:59:06.674   916  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:59:06.684   916  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:59:06.684   916  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:59:06.684   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:59:06.684  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:59:06.694   916   916 I MotionRecognitionService: Plugged
,07-05 12:59:06.694   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:59:06.694  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:59:06.694  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:59:06.694  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:59:06.694   916  1713 D BatteryService: stay LED for fully charged
,07-05 12:59:06.704  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:59:06.704  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:59:06.704  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:59:06.704  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:59:06.724   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:59:08.444   303   303 E SMD     : DCD ON
,07-05 12:59:11.454   303   303 E SMD     : DCD ON
,07-05 12:59:14.444   303   303 E SMD     : DCD ON
,07-05 12:59:16.734   916  1517 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:59:16.734   916  1517 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:59:16.744   916  1517 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:59:16.744   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:59:16.744  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:59:16.744  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:59:16.744   916   916 I MotionRecognitionService: Plugged
07-05 12:59:16.744   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:59:16.754  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:59:16.754  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:59:16.754  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:59:16.754   916  1517 D BatteryService: stay LED for fully charged
,07-05 12:59:16.764  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:59:16.764  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:59:16.764  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:59:16.784   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:59:17.454   303   303 E SMD     : DCD ON
,07-05 12:59:20.464   303   303 E SMD     : DCD ON
,07-05 12:59:23.454   303   303 E SMD     : DCD ON
,07-05 12:59:26.464   303   303 E SMD     : DCD ON
,07-05 12:59:26.794   916  3588 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:59:26.844   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:59:28.694   916  1321 E Watchdog: !@Sync 22
,07-05 12:59:29.464   303   303 E SMD     : DCD ON
,07-05 12:59:32.464   303   303 E SMD     : DCD ON
,07-05 12:59:35.464   303   303 E SMD     : DCD ON
,07-05 12:59:36.854   916  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:59:36.864   916  1451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:59:36.864   916  1451 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:59:36.864   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:59:36.864   916   916 I MotionRecognitionService: Plugged
,07-05 12:59:36.864  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:59:36.864  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:59:36.864   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:59:36.874  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:59:36.874   916  1451 D BatteryService: stay LED for fully charged
,07-05 12:59:36.874  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:59:36.874  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:59:36.884  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:59:36.884  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:59:36.894  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:59:36.904   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:59:38.454   303   303 E SMD     : DCD ON
,07-05 12:59:41.454   303   303 E SMD     : DCD ON
,07-05 12:59:44.454   303   303 E SMD     : DCD ON
,07-05 12:59:46.914   916   932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:59:46.924   916   932 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:59:46.924   916   932 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:59:46.924   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:59:46.924   916   916 I MotionRecognitionService: Plugged
,07-05 12:59:46.924   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:59:46.934  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:59:46.934  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:59:46.934  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:59:46.934  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:59:46.934  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:59:46.934   916   932 D BatteryService: stay LED for fully charged
,07-05 12:59:46.944  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:59:46.944  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:59:46.944  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:59:46.964   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:59:47.454   303   303 E SMD     : DCD ON
,07-05 12:59:50.454   303   303 E SMD     : DCD ON
,07-05 12:59:53.454   303   303 E SMD     : DCD ON
,07-05 12:59:56.464   303   303 E SMD     : DCD ON
,07-05 12:59:56.974   916  3344 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:59:56.974   916  3344 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:59:56.984   916  3344 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:59:56.984   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:59:56.984   916   916 I MotionRecognitionService: Plugged
,07-05 12:59:56.984   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:59:56.984  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:59:56.994  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:59:56.994  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:59:56.994   916  3344 D BatteryService: stay LED for fully charged
,07-05 12:59:56.994  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:59:57.004  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:59:57.004  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:59:57.004  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:59:57.004  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:59:57.024   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:59:58.684   916  1321 E Watchdog: !@Sync 23
,07-05 12:59:59.464   303   303 E SMD     : DCD ON
,07-05 13:00:02.464   303   303 E SMD     : DCD ON
,07-05 13:00:05.464   303   303 E SMD     : DCD ON
,07-05 13:00:07.034   916  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:00:07.034   916  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:00:07.044   916  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:00:07.044   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:00:07.044   916   916 I MotionRecognitionService: Plugged
,07-05 13:00:07.044   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:00:07.044  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:00:07.054  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:00:07.054  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:00:07.054  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:00:07.054  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:00:07.054   916  1713 D BatteryService: stay LED for fully charged
07-05 13:00:07.054  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:00:07.064  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:00:07.064  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:00:07.084   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 13:00:08.464   303   303 E SMD     : DCD ON
,07-05 13:00:11.474   303   303 E SMD     : DCD ON
,07-05 13:00:12.924   916  1061 I PowerManagerService: [PWL] Off : 680s ago
,07-05 13:00:14.474   303   303 E SMD     : DCD ON
,07-05 13:00:17.094   916  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:00:17.094   916  1451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:00:17.104   916  1451 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:00:17.104   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:00:17.104   916   916 I MotionRecognitionService: Plugged
,07-05 13:00:17.104   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:00:17.104  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:00:17.114  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:00:17.114  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:00:17.114  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:00:17.114   916  1451 D BatteryService: stay LED for fully charged
,07-05 13:00:17.114  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:00:17.114  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:00:17.124  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:00:17.124  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:00:17.144   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:00:17.474   303   303 E SMD     : DCD ON
,07-05 13:00:20.464   303   303 E SMD     : DCD ON
,07-05 13:00:23.464   303   303 E SMD     : DCD ON
,07-05 13:00:26.474   303   303 E SMD     : DCD ON
,07-05 13:00:27.154   916  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:00:27.154   916  1223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:00:27.164   916  1223 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:00:27.164   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:00:27.174  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:00:27.174   916   916 I MotionRecognitionService: Plugged
,07-05 13:00:27.174   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:00:27.174  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:00:27.184   916  1223 D BatteryService: stay LED for fully charged
,07-05 13:00:27.184  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:00:27.194  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:00:27.194  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:00:27.194  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:00:27.194  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:00:27.204  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:00:27.214   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:00:28.694   916  1321 E Watchdog: !@Sync 24
,07-05 13:00:29.474   303   303 E SMD     : DCD ON
,07-05 13:00:32.474   303   303 E SMD     : DCD ON
,07-05 13:00:35.474   303   303 E SMD     : DCD ON
,07-05 13:00:37.214   916  1239 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
07-05 13:00:37.224   916  1239 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 13:00:37.224   916  1239 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:00:37.224   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:00:37.224  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:00:37.224  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 13:00:37.224   916   916 I MotionRecognitionService: Plugged
,07-05 13:00:37.224   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:00:37.234   916  1239 D BatteryService: stay LED for fully charged
,07-05 13:00:37.234  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:00:37.234  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:00:37.244  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:00:37.244  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:00:37.244  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:00:37.244  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:00:37.274   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:00:38.474   303   303 E SMD     : DCD ON
,07-05 13:00:41.474   303   303 E SMD     : DCD ON
,07-05 13:00:44.474   303   303 E SMD     : DCD ON
,07-05 13:00:47.284   916  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:00:47.324   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:00:47.474   303   303 E SMD     : DCD ON
,07-05 13:00:50.474   303   303 E SMD     : DCD ON
,07-05 13:00:53.474   303   303 E SMD     : DCD ON
,07-05 13:00:56.484   303   303 E SMD     : DCD ON
,07-05 13:00:57.344   916  1517 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:00:57.344   916  1517 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:00:57.344   916  1517 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:00:57.354   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:00:57.354  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:00:57.364  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:00:57.364   916   916 I MotionRecognitionService: Plugged
,07-05 13:00:57.364   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:00:57.374   916  1517 D BatteryService: stay LED for fully charged
,07-05 13:00:57.374  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:00:57.384  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:00:57.394  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:00:57.394  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:00:57.404  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:00:57.404  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:00:57.424   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:00:58.704   916  1321 E Watchdog: !@Sync 25
,07-05 13:00:59.474   303   303 E SMD     : DCD ON
,07-05 13:01:02.474   303   303 E SMD     : DCD ON
,07-05 13:01:05.484   303   303 E SMD     : DCD ON
,07-05 13:01:07.404   916  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:01:07.404   916  1482 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:01:07.404   916  1482 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:01:07.404   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:01:07.414  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:01:07.414  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:01:07.424   916   916 I MotionRecognitionService: Plugged
,07-05 13:01:07.424   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:01:07.424   916  1482 D BatteryService: stay LED for fully charged
,07-05 13:01:07.424  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:01:07.434  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:01:07.434  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:01:07.444  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:07.444  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:07.444  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:07.484   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:01:08.484   303   303 E SMD     : DCD ON
,07-05 13:01:11.494   303   303 E SMD     : DCD ON
,07-05 13:01:14.484   303   303 E SMD     : DCD ON
,07-05 13:01:17.464   916  1517 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:01:17.464   916  1517 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:01:17.464   916  1517 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:01:17.464   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:01:17.474  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:01:17.474  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:01:17.484   916   916 I MotionRecognitionService: Plugged
,07-05 13:01:17.484   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:01:17.484   303   303 E SMD     : DCD ON
07-05 13:01:17.484   916  1517 D BatteryService: stay LED for fully charged
,07-05 13:01:17.484  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:01:17.494  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:01:17.494  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:01:17.504  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:17.504  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:17.504  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:17.534   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:01:20.494   303   303 E SMD     : DCD ON
,07-05 13:01:23.484   303   303 E SMD     : DCD ON
,07-05 13:01:26.484   303   303 E SMD     : DCD ON
,07-05 13:01:27.584   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:01:28.514   916  1113 V AlarmManager: waitForAlarm result :8
,07-05 13:01:28.564   916  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:01:28.574   916  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:01:28.574   916  4028 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:01:28.574   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:01:28.584  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:01:28.584  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:01:28.584   916   916 I MotionRecognitionService: Plugged
,07-05 13:01:28.584   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:01:28.584  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:01:28.594   916  4028 D BatteryService: stay LED for fully charged
,07-05 13:01:28.594  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:28.594  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:28.594  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:01:28.594  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:01:28.604  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:28.704   916  1321 E Watchdog: !@Sync 26
,07-05 13:01:29.494   303   303 E SMD     : DCD ON
,07-05 13:01:32.494   303   303 E SMD     : DCD ON
,07-05 13:01:35.484   303   303 E SMD     : DCD ON
,07-05 13:01:37.644   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:01:37.924   916  1061 I PowerManagerService: [PWL] Off : 765s ago
,07-05 13:01:38.494   303   303 E SMD     : DCD ON
,07-05 13:01:38.634   916  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:01:38.634   916  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:01:38.634   916  1476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:01:38.644   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:01:38.644   916   916 I MotionRecognitionService: Plugged
,07-05 13:01:38.644   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:01:38.654  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:01:38.654  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:01:38.654  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:01:38.654  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:01:38.654  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:01:38.664   916  1476 D BatteryService: stay LED for fully charged
07-05 13:01:38.664  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:38.664  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:38.664  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:41.494   303   303 E SMD     : DCD ON
,07-05 13:01:44.484   303   303 E SMD     : DCD ON
,07-05 13:01:47.494   303   303 E SMD     : DCD ON
,07-05 13:01:47.694   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:01:48.694   916  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:01:48.704   916  1223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:01:48.704   916  1223 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:01:48.704   916  1223 D BatteryService: stay LED for fully charged
,07-05 13:01:48.704   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:01:48.714  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:01:48.714  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:01:48.714   916   916 I MotionRecognitionService: Plugged
07-05 13:01:48.714   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:01:48.714  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:48.714  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:48.724  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:01:48.724  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:01:48.724  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:01:48.734  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:50.494   303   303 E SMD     : DCD ON
,07-05 13:01:53.494   303   303 E SMD     : DCD ON
,07-05 13:01:56.504   303   303 E SMD     : DCD ON
,07-05 13:01:57.734   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:01:58.714   916  1321 E Watchdog: !@Sync 27
,07-05 13:01:58.764   916  1239 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:01:58.764   916  1239 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:01:58.764   916  1239 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:01:58.764   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:01:58.774  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:01:58.774  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:01:58.784   916   916 I MotionRecognitionService: Plugged
07-05 13:01:58.784   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:01:58.784   916  1239 D BatteryService: stay LED for fully charged
,07-05 13:01:58.784  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:01:58.794  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:58.794  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:01:58.794  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:01:58.804  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:58.804  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:01:59.504   303   303 E SMD     : DCD ON
,07-05 13:02:02.504   303   303 E SMD     : DCD ON
,07-05 13:02:05.494   303   303 E SMD     : DCD ON
,07-05 13:02:07.784   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:02:08.504   303   303 E SMD     : DCD ON
,07-05 13:02:08.824   916  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:02:08.824   916  1223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 13:02:08.824   916  1223 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:02:08.824   916  1223 D BatteryService: stay LED for fully charged
,07-05 13:02:08.824   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:02:08.824  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:02:08.824  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:02:08.824   916   916 I MotionRecognitionService: Plugged
,07-05 13:02:08.834   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:02:08.834  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:02:08.844  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:02:08.844  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:02:08.844  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:02:08.844  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:02:08.844  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:02:11.494   303   303 E SMD     : DCD ON
,07-05 13:02:14.494   303   303 E SMD     : DCD ON
,07-05 13:02:17.494   303   303 E SMD     : DCD ON
,07-05 13:02:17.834   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:02:18.884   916  1239 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:02:18.884   916  1239 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:02:18.884   916  1239 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:02:18.894   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:02:18.894  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:02:18.904  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:02:18.904   916   916 I MotionRecognitionService: Plugged
,07-05 13:02:18.904   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:02:18.904   916  1239 D BatteryService: stay LED for fully charged
,07-05 13:02:18.904  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:02:18.914  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:02:18.914  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:02:18.914  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:02:18.914  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:02:18.914  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:02:20.494   303   303 E SMD     : DCD ON
,07-05 13:02:23.514   303   303 E SMD     : DCD ON
,07-05 13:02:26.504   303   303 E SMD     : DCD ON
,07-05 13:02:27.884   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:02:28.714   916  1321 E Watchdog: !@Sync 28
,07-05 13:02:28.944   916  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:02:28.944   916  1223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:02:28.954   916  1223 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:02:28.954   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:02:28.964  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:02:28.964  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:02:28.964   916   916 I MotionRecognitionService: Plugged
,07-05 13:02:28.964   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:02:28.964   916  1223 D BatteryService: stay LED for fully charged
,07-05 13:02:28.974  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:02:28.984  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:02:28.984  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:02:28.994  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:02:29.004  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:02:29.004  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:02:29.514   303   303 E SMD     : DCD ON
,07-05 13:02:32.514   303   303 E SMD     : DCD ON
,07-05 13:02:35.504   303   303 E SMD     : DCD ON
,07-05 13:02:37.934   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:02:38.514   303   303 E SMD     : DCD ON
,07-05 13:02:39.004   916  1239 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:02:39.004   916  1239 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:02:39.004   916  1239 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:02:39.014   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:02:39.014  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:02:39.024  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:02:39.024   916   916 I MotionRecognitionService: Plugged
07-05 13:02:39.024   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:02:39.024   916  1239 D BatteryService: stay LED for fully charged
,07-05 13:02:39.034  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:02:39.034  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:02:39.034  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:02:39.034  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:02:39.034  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:02:39.034  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:02:41.514   303   303 E SMD     : DCD ON
,07-05 13:02:44.504   303   303 E SMD     : DCD ON
,07-05 13:02:47.514   303   303 E SMD     : DCD ON
,07-05 13:02:47.984   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:02:49.054   916  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:02:50.514   303   303 E SMD     : DCD ON
,07-05 13:02:53.504   303   303 E SMD     : DCD ON
,07-05 13:02:56.504   303   303 E SMD     : DCD ON
,07-05 13:02:58.044   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:02:58.714   916  1321 E Watchdog: !@Sync 29
,07-05 13:02:59.124   916  1364 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:02:59.124   916  1364 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:02:59.124   916  1364 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:02:59.124   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:02:59.134   916   916 I MotionRecognitionService: Plugged
,07-05 13:02:59.134  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:02:59.144  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:02:59.144   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:02:59.144   916  1364 D BatteryService: stay LED for fully charged
,07-05 13:02:59.154  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:02:59.164  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:02:59.164  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:02:59.164  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:02:59.174  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:02:59.174  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:02:59.514   303   303 E SMD     : DCD ON
,07-05 13:03:02.524   303   303 E SMD     : DCD ON
,07-05 13:03:05.514   303   303 E SMD     : DCD ON
,07-05 13:03:07.924   916  1061 I PowerManagerService: [PWL] Off : 855s ago
,07-05 13:03:08.094   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:03:08.524   303   303 E SMD     : DCD ON
,07-05 13:03:09.184   916  3588 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:03:09.184   916  3588 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:03:09.184   916  3588 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:03:09.194   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:03:09.194  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:03:09.204  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:03:09.204   916   916 I MotionRecognitionService: Plugged
,07-05 13:03:09.204   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:03:09.204   916  3588 D BatteryService: stay LED for fully charged
,07-05 13:03:09.214  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:03:09.224  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:03:09.224  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:03:09.224  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:03:09.234  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:03:09.234  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:03:11.524   303   303 E SMD     : DCD ON
,07-05 13:03:14.514   303   303 E SMD     : DCD ON
,07-05 13:03:17.514   303   303 E SMD     : DCD ON
,07-05 13:03:18.134   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:03:19.244   916  1364 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:03:19.244   916  1364 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:03:19.244   916  1364 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:03:19.244   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:03:19.254  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:03:19.254  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:03:19.264   916   916 I MotionRecognitionService: Plugged
,07-05 13:03:19.264   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:03:19.264   916  1364 D BatteryService: stay LED for fully charged
,07-05 13:03:19.264  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:03:19.274  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:03:19.274  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:03:19.284  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:03:19.284  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:03:19.284  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:03:20.524   303   303 E SMD     : DCD ON
,07-05 13:03:23.524   303   303 E SMD     : DCD ON
,07-05 13:03:25.864   916  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 13:03:25.864   916  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 13:03:25.874   916  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 13:03:26.524   303   303 E SMD     : DCD ON
,07-05 13:03:28.214   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:03:28.714   916  1321 E Watchdog: !@Sync 30
,07-05 13:03:28.834   916  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 13:03:28.834   916  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 13:03:28.834   916  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 13:03:28.844   916  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 13:03:29.304   916  3588 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:03:29.524   303   303 E SMD     : DCD ON
,07-05 13:03:32.514   303   303 E SMD     : DCD ON
,07-05 13:03:35.524   303   303 E SMD     : DCD ON
,07-05 13:03:38.264   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:03:38.534   303   303 E SMD     : DCD ON
,07-05 13:03:39.364   916  3344 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:03:41.534   303   303 E SMD     : DCD ON
,07-05 13:03:44.524   303   303 E SMD     : DCD ON
,07-05 13:03:47.524   303   303 E SMD     : DCD ON
,07-05 13:03:48.314   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:03:49.424   916  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:03:49.424   916  2110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:03:49.424   916  2110 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:03:49.424   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:03:49.434  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:03:49.434  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:03:49.444   916   916 I MotionRecognitionService: Plugged
,07-05 13:03:49.444   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:03:49.444   916  2110 D BatteryService: stay LED for fully charged
,07-05 13:03:49.444  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:03:49.454  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:03:49.454  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:03:49.464  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:03:49.464  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:03:49.464  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:03:50.524   303   303 E SMD     : DCD ON
,07-05 13:03:53.524   303   303 E SMD     : DCD ON
,07-05 13:03:56.524   303   303 E SMD     : DCD ON
,07-05 13:03:58.394   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:03:58.724   916  1321 E Watchdog: !@Sync 31
,07-05 13:03:59.484   916  1419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:03:59.484   916  1419 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:03:59.484   916  1419 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:03:59.494   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:03:59.494  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:03:59.504  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:03:59.504   916   916 I MotionRecognitionService: Plugged
,07-05 13:03:59.504   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:03:59.504   916  1419 D BatteryService: stay LED for fully charged
,07-05 13:03:59.514  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:03:59.524  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:03:59.524   303   303 E SMD     : DCD ON
,07-05 13:03:59.524  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:03:59.534  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:03:59.544  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:03:59.544  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:04:02.524   303   303 E SMD     : DCD ON
,07-05 13:04:05.524   303   303 E SMD     : DCD ON
,07-05 13:04:08.444   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:04:08.534   303   303 E SMD     : DCD ON
,07-05 13:04:09.544   916  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:04:11.524   303   303 E SMD     : DCD ON
,07-05 13:04:14.534   303   303 E SMD     : DCD ON
,07-05 13:04:17.534   303   303 E SMD     : DCD ON
,07-05 13:04:18.494   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:04:19.604   916  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:04:20.534   303   303 E SMD     : DCD ON
,07-05 13:04:23.534   303   303 E SMD     : DCD ON
,07-05 13:04:26.544   303   303 E SMD     : DCD ON
,07-05 13:04:28.564   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:04:28.724   916  1321 E Watchdog: !@Sync 32
,07-05 13:04:29.534   303   303 E SMD     : DCD ON
,07-05 13:04:29.664   916  1364 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:04:29.664   916  1364 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:04:29.664   916  1364 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:04:29.664   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:04:29.674  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:04:29.674  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:04:29.684   916   916 I MotionRecognitionService: Plugged
,07-05 13:04:29.684   916   916 I MotionRecognitionService: setPowerConnected  = true
07-05 13:04:29.684   916  1364 D BatteryService: stay LED for fully charged
,07-05 13:04:29.684  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:04:29.694  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:04:29.694  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:04:29.694  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:04:29.704  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:04:29.704  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:04:32.534   303   303 E SMD     : DCD ON
,07-05 13:04:35.534   303   303 E SMD     : DCD ON
,07-05 13:04:38.534   303   303 E SMD     : DCD ON
,07-05 13:04:38.614   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:04:39.714   916  3588 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:04:41.544   303   303 E SMD     : DCD ON
,07-05 13:04:42.924   916  1061 I PowerManagerService: [PWL] Off : 950s ago
,07-05 13:04:44.534   303   303 E SMD     : DCD ON
,07-05 13:04:47.544   303   303 E SMD     : DCD ON
,07-05 13:04:48.664   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:04:49.774   916  3344 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:04:49.784   916  3344 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 13:04:49.784   916  3344 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:04:49.784   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:04:49.784  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:04:49.784  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 13:04:49.784   916   916 I MotionRecognitionService: Plugged
,07-05 13:04:49.784   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:04:49.794   916  3344 D BatteryService: stay LED for fully charged
,07-05 13:04:49.794  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:04:49.794  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:04:49.794  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:04:49.804  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:04:49.804  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:04:49.824  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:04:50.544   303   303 E SMD     : DCD ON
,07-05 13:04:53.544   303   303 E SMD     : DCD ON
,07-05 13:04:56.544   303   303 E SMD     : DCD ON
,07-05 13:04:58.704   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:04:58.734   916  1321 E Watchdog: !@Sync 33
,07-05 13:04:59.554   303   303 E SMD     : DCD ON
,07-05 13:04:59.844   916   932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:04:59.844   916   932 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:04:59.844   916   932 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:04:59.844   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:04:59.854   916   916 I MotionRecognitionService: Plugged
,07-05 13:04:59.854  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:04:59.864  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:04:59.864   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:04:59.864   916   932 D BatteryService: stay LED for fully charged
,07-05 13:04:59.874  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:04:59.884  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:04:59.884  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:04:59.884  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:04:59.904  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:04:59.904  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:05:02.544   303   303 E SMD     : DCD ON
,07-05 13:05:05.544   303   303 E SMD     : DCD ON
,07-05 13:05:08.554   303   303 E SMD     : DCD ON
,07-05 13:05:08.754   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:05:09.904   916  3344 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:05:09.904   916  3344 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:05:09.904   916  3344 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:05:09.904   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:05:09.914  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:05:09.914  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:05:09.924   916  3344 D BatteryService: stay LED for fully charged
,07-05 13:05:09.924   916   916 I MotionRecognitionService: Plugged
07-05 13:05:09.924   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:05:09.924  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:05:09.934  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:05:09.934  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:05:09.944  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:05:09.944  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:05:09.944  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:05:11.544   303   303 E SMD     : DCD ON
,07-05 13:05:14.554   303   303 E SMD     : DCD ON
,07-05 13:05:17.554   303   303 E SMD     : DCD ON
,07-05 13:05:18.804   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:05:20.544   303   303 E SMD     : DCD ON
,07-05 13:05:23.544   303   303 E SMD     : DCD ON
,07-05 13:05:26.554   303   303 E SMD     : DCD ON
,07-05 13:05:28.354   916  1113 V AlarmManager: waitForAlarm result :4
,07-05 13:05:28.374  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 13:05:28.374  1196  1196 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 13:05:28.374   916   916 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-05 13:05:28.384  1196  1196 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 13:05:28.384  1196  1196 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 13:05:28.394   916   916 E LightSensor: Light old sensor_state 8192, new sensor_state : 8704 en : 1
,07-05 13:05:28.404   916  1364 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:05:28.404   916  1364 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 13:05:28.404   916  1364 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:05:28.404   916  1364 D BatteryService: stay LED for fully charged
,07-05 13:05:28.424   916   916 D SensorManager: registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,07-05 13:05:28.424   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:05:28.434  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:05:28.434  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:05:28.434  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:05:28.444  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:05:28.444  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:05:28.444  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:05:28.444  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:05:28.464  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:05:28.474   916   916 I MotionRecognitionService: Plugged
,07-05 13:05:28.474   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:05:28.484  1196  1196 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 13:05:28.484  1196  1196 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 13:05:28.494   916  2110 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 13:05:28.494   916  2110 D ActivityManager: caller:android.app.ApplicationThreadProxy@2d817237, r.packageName :com.google.android.gms
,07-05 13:05:28.534  2202  7669 I EventLogService: Aggregate from 1467714928303 (log), 1467714928303 (data)
,07-05 13:05:28.624  4077  4401 D GCM     : Message class com.google.f.a.a.i
,07-05 13:05:28.624   916  3344 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 13:05:28.624   916  1517 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 13:05:28.734   916  1321 E Watchdog: !@Sync 34
,07-05 13:05:28.774   916  1093 D LightsService: [SvcLED]  onSensorChanged::light value = 0
07-05 13:05:28.774   916  1093 E LightSensor: Light old sensor_state 8704, new sensor_state : 8192 en : 0
,07-05 13:05:28.784   916  1093 D SensorManager: unregisterListener ::   
07-05 13:05:28.784   916  1093 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-05 13:05:28.844   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:05:29.554   303   303 E SMD     : DCD ON
,07-05 13:05:32.554   303   303 E SMD     : DCD ON
,07-05 13:05:35.554   303   303 E SMD     : DCD ON
,07-05 13:05:38.464   916   932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:05:38.564   303   303 E SMD     : DCD ON
,07-05 13:05:38.884   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:05:41.554   303   303 E SMD     : DCD ON
,07-05 13:05:44.564   303   303 E SMD     : DCD ON
,07-05 13:05:47.554   303   303 E SMD     : DCD ON
,07-05 13:05:48.524   916  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:05:48.534   916  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:05:48.534   916  4028 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:05:48.534   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:05:48.544  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:05:48.544   916   916 I MotionRecognitionService: Plugged
,07-05 13:05:48.554  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:05:48.554  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
07-05 13:05:48.554   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:05:48.554  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:05:48.554   916  4028 D BatteryService: stay LED for fully charged
,07-05 13:05:48.554  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:05:48.554  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:05:48.554  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:05:48.554  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:05:48.934   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:05:50.564   303   303 E SMD     : DCD ON
,07-05 13:05:53.564   303   303 E SMD     : DCD ON
,07-05 13:05:56.564   303   303 E SMD     : DCD ON
,07-05 13:05:58.584   916  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:05:58.594   916  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:05:58.594   916  1476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:05:58.594   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:05:58.604  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:05:58.604  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:05:58.604  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:05:58.614   916   916 I MotionRecognitionService: Plugged
,07-05 13:05:58.614   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:05:58.614  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:05:58.614  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:05:58.614   916  1476 D BatteryService: stay LED for fully charged
07-05 13:05:58.614  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:05:58.614  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:05:58.614  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:05:58.734   916  1321 E Watchdog: !@Sync 35
,07-05 13:05:58.984   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:05:59.564   303   303 E SMD     : DCD ON
,07-05 13:05:59.984   916  1113 V AlarmManager: waitForAlarm result :8
,07-05 13:06:02.574   303   303 E SMD     : DCD ON
,07-05 13:06:05.564   303   303 E SMD     : DCD ON
,07-05 13:06:08.564   303   303 E SMD     : DCD ON
,07-05 13:06:08.644   916  3344 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:06:08.644   916  3344 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:06:08.654   916  3344 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:06:08.654   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:06:08.654  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:06:08.664  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:06:08.664   916   916 I MotionRecognitionService: Plugged
,07-05 13:06:08.674   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:06:08.674   916  3344 D BatteryService: stay LED for fully charged
,07-05 13:06:08.674  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:06:08.684  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:06:08.694  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:06:08.694  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:06:08.704  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:06:08.704  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:06:09.034   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:06:11.574   303   303 E SMD     : DCD ON
,07-05 13:06:14.564   303   303 E SMD     : DCD ON
,07-05 13:06:17.564   303   303 E SMD     : DCD ON
,07-05 13:06:18.704   916  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:06:18.704   916  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:06:18.714   916  1476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:06:18.714   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:06:18.714   916   916 I MotionRecognitionService: Plugged
,07-05 13:06:18.724   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:06:18.724  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:06:18.724  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:06:18.724   916  1476 D BatteryService: stay LED for fully charged
,07-05 13:06:18.744  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:06:18.754  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:06:18.754  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:06:18.754  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:06:18.754  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:06:18.754  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:06:19.084   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:06:20.564   303   303 E SMD     : DCD ON
,07-05 13:06:22.924   916  1061 I PowerManagerService: [PWL] Off : 1050s ago
,07-05 13:06:23.564   303   303 E SMD     : DCD ON
,07-05 13:06:26.564   303   303 E SMD     : DCD ON
,07-05 13:06:28.744   916  1321 E Watchdog: !@Sync 36
,07-05 13:06:28.764   916  3344 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:06:29.134   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:06:29.564   303   303 E SMD     : DCD ON
,07-05 13:06:32.574   303   303 E SMD     : DCD ON
,07-05 13:06:35.574   303   303 E SMD     : DCD ON
,07-05 13:06:38.584   303   303 E SMD     : DCD ON
,07-05 13:06:38.824   916  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:06:38.834   916  1451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:06:38.834   916  1451 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:06:38.834   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:06:38.844  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:06:38.844  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:06:38.854   916   916 I MotionRecognitionService: Plugged
,07-05 13:06:38.854   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:06:38.854  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:06:38.854  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:06:38.854  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:06:38.854   916  1451 D BatteryService: stay LED for fully charged
07-05 13:06:38.854  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:06:38.854  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:06:38.854  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:06:39.184   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:06:41.574   303   303 E SMD     : DCD ON
,07-05 13:06:44.574   303   303 E SMD     : DCD ON
,07-05 13:06:47.584   303   303 E SMD     : DCD ON
,07-05 13:06:48.894   916  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:06:48.894   916  2110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:06:48.894   916  2110 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:06:48.904   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:06:48.904   916   916 I MotionRecognitionService: Plugged
,07-05 13:06:48.904  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:06:48.904  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:06:48.914  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:06:48.914   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:06:48.914  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:06:48.914  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:06:48.914  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:06:48.914   916  2110 D BatteryService: stay LED for fully charged
,07-05 13:06:48.914  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:06:48.924  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:06:49.234   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:06:50.584   303   303 E SMD     : DCD ON
,07-05 13:06:53.574   303   303 E SMD     : DCD ON
,07-05 13:06:56.574   303   303 E SMD     : DCD ON
,07-05 13:06:58.734   916  1321 E Watchdog: !@Sync 37
,07-05 13:06:58.954   916  1364 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:06:58.964   916  1364 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:06:58.964   916  1364 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:06:58.964   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:06:58.964   916   916 I MotionRecognitionService: Plugged
,07-05 13:06:58.964   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:06:58.974  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:06:58.974  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:06:58.974  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:06:58.974  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:06:58.974  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:06:58.974   916  1364 D BatteryService: stay LED for fully charged
,07-05 13:06:58.984  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:06:58.984  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:06:58.984  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:06:59.304   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:06:59.574   303   303 E SMD     : DCD ON
,07-05 13:07:02.574   303   303 E SMD     : DCD ON
,07-05 13:07:05.584   303   303 E SMD     : DCD ON
,07-05 13:07:08.574   303   303 E SMD     : DCD ON
,07-05 13:07:09.014   916  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:07:09.364   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:07:11.584   303   303 E SMD     : DCD ON
,07-05 13:07:14.594   303   303 E SMD     : DCD ON
,07-05 13:07:17.584   303   303 E SMD     : DCD ON
,07-05 13:07:19.074   916  1419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:07:19.074   916  1419 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:07:19.074   916  1419 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:07:19.084   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:07:19.084   916   916 I MotionRecognitionService: Plugged
,07-05 13:07:19.084   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:07:19.084  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:07:19.094  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:07:19.094  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:07:19.094  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:07:19.094   916  1419 D BatteryService: stay LED for fully charged
,07-05 13:07:19.094  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:07:19.094  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:07:19.094  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:07:19.104  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:07:19.414   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:07:20.584   303   303 E SMD     : DCD ON
,07-05 13:07:23.594   303   303 E SMD     : DCD ON
,07-05 13:07:26.584   303   303 E SMD     : DCD ON
,07-05 13:07:28.744   916  1321 E Watchdog: !@Sync 38
,07-05 13:07:29.134   916   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:07:29.464   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:07:29.584   303   303 E SMD     : DCD ON
,07-05 13:07:32.584   303   303 E SMD     : DCD ON
,07-05 13:07:35.594   303   303 E SMD     : DCD ON
,07-05 13:07:38.594   303   303 E SMD     : DCD ON
,07-05 13:07:39.194   916  3588 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:07:39.204   916  3588 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:07:39.204   916  3588 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:07:39.204   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:07:39.214  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:07:39.214   916   916 I MotionRecognitionService: Plugged
,07-05 13:07:39.214  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 13:07:39.214   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:07:39.214   916  3588 D BatteryService: stay LED for fully charged
,07-05 13:07:39.224  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:07:39.234  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:07:39.234  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:07:39.234  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:07:39.234  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:07:39.244  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:07:39.514   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:07:41.594   303   303 E SMD     : DCD ON
,07-05 13:07:44.584   303   303 E SMD     : DCD ON
,07-05 13:07:47.594   303   303 E SMD     : DCD ON
,07-05 13:07:49.254   916  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:07:49.254   916  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:07:49.254   916  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:07:49.254   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:07:49.264   916   916 I MotionRecognitionService: Plugged
,07-05 13:07:49.264   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:07:49.264  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:07:49.264  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:07:49.274   916  1713 D BatteryService: stay LED for fully charged
,07-05 13:07:49.274  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:07:49.274  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:07:49.274  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:07:49.274  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:07:49.274  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:07:49.274  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:07:49.564   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:07:50.604   303   303 E SMD     : DCD ON
,07-05 13:07:53.604   303   303 E SMD     : DCD ON
,07-05 13:07:56.594   303   303 E SMD     : DCD ON
,07-05 13:07:58.734   916  1321 E Watchdog: !@Sync 39
,07-05 13:07:59.314   916  3588 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:07:59.594   303   303 E SMD     : DCD ON
,07-05 13:07:59.644   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:08:02.594   303   303 E SMD     : DCD ON
,07-05 13:08:05.594   303   303 E SMD     : DCD ON
,07-05 13:08:07.934   916  1061 I PowerManagerService: [PWL] Off : 1155s ago
,07-05 13:08:08.604   303   303 E SMD     : DCD ON
,07-05 13:08:09.374   916  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:08:09.384   916  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:08:09.384   916  1476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:08:09.384   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:08:09.384   916   916 I MotionRecognitionService: Plugged
,07-05 13:08:09.384   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:08:09.384  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:08:09.394  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:08:09.394   916  1476 D BatteryService: stay LED for fully charged
,07-05 13:08:09.394  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:08:09.394  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:08:09.394  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:08:09.404  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:08:09.404  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:08:09.404  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:08:09.684   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:08:11.604   303   303 E SMD     : DCD ON
,07-05 13:08:14.594   303   303 E SMD     : DCD ON
,07-05 13:08:17.594   303   303 E SMD     : DCD ON
,07-05 13:08:19.434   916  3344 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:08:19.734   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:08:20.594   303   303 E SMD     : DCD ON
,07-05 13:08:23.604   303   303 E SMD     : DCD ON
,07-05 13:08:25.874   916  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 13:08:25.874   916  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 13:08:25.874   916  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 13:08:26.574   916  1003 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 13:08:26.604   303   303 E SMD     : DCD ON
,07-05 13:08:26.634   916  1125 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,07-05 13:08:26.634   916  1125 I ApplicationUsage: Updating Usage Statistics in DB @ 1467716906645
,07-05 13:08:26.634   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 13:08:26.634   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 13:08:26.634   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 13:08:26.634   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-05 13:08:26.634   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
07-05 13:08:26.634   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
07-05 13:08:26.634   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.634   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.634   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 13:08:26.634   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.634   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.634   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.634   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.634   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,07-05 13:08:26.644   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
07-05 13:08:26.644   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
07-05 13:08:26.644   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.644   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.644   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.644   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 13:08:26.644   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.644   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 13:08:26.644   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 13:08:26.644   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-05 13:08:26.644   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
07-05 13:08:26.644   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
07-05 13:08:26.644   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.644   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 13:08:26.644   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.644   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.644   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.644   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 13:08:26.644   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.644   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-05 13:08:26.644   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
07-05 13:08:26.644   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
07-05 13:08:26.644   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 13:08:26.644   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 13:08:26.654   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 13:08:26.654   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.654   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.654   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 13:08:26.654   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.654   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.654   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.654   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 13:08:26.654   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.654   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.654   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.654   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 13:08:26.654   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.654   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.654   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.654   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.654   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 13:08:26.654   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.654   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.654   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 13:08:26.654   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 13:08:26.654   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.654   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.654   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.654   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 13:08:26.654   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.654   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.654   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.654   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 13:08:26.664   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.664   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.664   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.664   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.664   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 13:08:26.664   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.664   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.664   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.664   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.664   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 13:08:26.664   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 13:08:26.664   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 13:08:26.664   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.664   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.664   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.664   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 13:08:26.664   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.664   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.664   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.664   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.664   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 13:08:26.664   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.664   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.664   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.664   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 13:08:26.664   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.664   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.664   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.664   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.664   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 13:08:26.674   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.674   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.674   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.674   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.674   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.674   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.674   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.674   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.674   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.674   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.674   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.674   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.674   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.674   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.674   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.674   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.674   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.674   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.674   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.674   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.674   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.674   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.674   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.684   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.684   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.684   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.684   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.684   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.684   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.684   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.684   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.684   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.684   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.684   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.684   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.684   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.684   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.684   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.684   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.684   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.684   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.684   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.684   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.684   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.684   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.694   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.694   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.694   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
07-05 13:08:26.694   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.694   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.694   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.694   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.694   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.694   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.694   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.694   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.694   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.694   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.694   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.694   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.694   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.694   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.694   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.694   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.694   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.704   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.704   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.704   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.704   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.704   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.704   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.704   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.704   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 13:08:26.704   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.704   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.704   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.704   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.704   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.704   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.704   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.704   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.704   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.704   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.704   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.704   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.704   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.704   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.704   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.704   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.704   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.704   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.704   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.704   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.714   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.714   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.714   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.714   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.714   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.714   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.714   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.714   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.714   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.714   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.714   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.714   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.714   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.714   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.714   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.714   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.714   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.714   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.714   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.714   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.714   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.714   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.714   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.714   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.714   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.714   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.724   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.724   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.724   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.724   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.724   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.724   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.724   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.724   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.724   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.724   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.724   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.724   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.724   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.724   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.724   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.724   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.724   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.724   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.724   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.724   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.724   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.724   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.724   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.724   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.724   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.724   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.724   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.724   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.734   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.734   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.734   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.734   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.734   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.734   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.734   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.734   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.734   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.734   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.734   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.734   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.734   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.734   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.734   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.734   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.734   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.734   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.734   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.734   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.734   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.734   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.734   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.734   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.734   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.734   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.734   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.734   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.734   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.734   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.744   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.744   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.744   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.744   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.744   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.744   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.744   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.744   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.744   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.744   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.744   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.744   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.744   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.744   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.744   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.744   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.744   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.744   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.744   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.744   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.744   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.754   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.754   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.754   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.754   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.754   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.754   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.754   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.754   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.754   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.754   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.754   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.754   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.754   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.754   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.754   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.754   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.764   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.764   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.764   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.764   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.764   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.764   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.764   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.764   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
07-05 13:08:26.764   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.764   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.764   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.764   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.764   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.764   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.764   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.764   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.764   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.764   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.764   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.764   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.764   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.764   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.764   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.764   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.764   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.764   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.764   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.764   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.764   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.764   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.764   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.764   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.774   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.774   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.774   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.774   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.774   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.774   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.774   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.774   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.774   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.774   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.774   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.774   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.774   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.774   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.774   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.774   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.774   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.774   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.774   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.774   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.774   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.774   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.774   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.774   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.784   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.784   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.784   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.784   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.784   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.784   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.784   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.784   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.784   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.784   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.784   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.784   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.784   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.784   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.784   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.784   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.794   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.794   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.794   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.794   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.794   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.794   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.794   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.794   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.794   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.794   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.794   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.794   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.794   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.804   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.804   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.804   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.804   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.804   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.804   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.804   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.804   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.804   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.804   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.804   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.804   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.814   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.814   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.814   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.814   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.814   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.814   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.814   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.814   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.814   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.814   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.814   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.814   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.814   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.814   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.814   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.814   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.814   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.814   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.814   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.814   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.814   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.814   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.814   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.824   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.824   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.824   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.824   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.824   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.824   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.824   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.824   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.824   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 13:08:26.824   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.824   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.824   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.824   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.824   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.824   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.824   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.824   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.824   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 13:08:26.824   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.824   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.824   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.824   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.834   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 13:08:26.834   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:08:26.834   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.834   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.834   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.834   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 13:08:26.834   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 13:08:26.834   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.834   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.834   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.834   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.834   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 13:08:26.834   916  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 13:08:26.834   916  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 13:08:26.834   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 13:08:26.834   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 13:08:26.834   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,07-05 13:08:26.834   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 13:08:26.834   916  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 13:08:26.834   916  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:08:26.834   916  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:08:26.834   916  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 13:08:26.834   916  1125 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1467716906849
,07-05 13:08:28.594   916  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 13:08:28.594   916  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 13:08:28.604   916  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 13:08:28.614   916  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 13:08:28.754   916  1321 E Watchdog: !@Sync 40
,07-05 13:08:29.494   916  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:08:29.494   916  1451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:08:29.494   916  1451 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:08:29.494   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:08:29.504  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:08:29.504   916   916 I MotionRecognitionService: Plugged
,07-05 13:08:29.504   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:08:29.514  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:08:29.514  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:08:29.514  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:08:29.514  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:08:29.514   916  1451 D BatteryService: stay LED for fully charged
,07-05 13:08:29.514  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:08:29.514  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:08:29.514  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:08:29.604   303   303 E SMD     : DCD ON
,07-05 13:08:29.784   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:08:32.604   303   303 E SMD     : DCD ON
,07-05 13:08:35.614   303   303 E SMD     : DCD ON
,07-05 13:08:38.614   303   303 E SMD     : DCD ON
,07-05 13:08:39.554   916  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:08:39.834   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:08:41.614   303   303 E SMD     : DCD ON
,07-05 13:08:44.604   303   303 E SMD     : DCD ON
,07-05 13:08:47.614   303   303 E SMD     : DCD ON
,07-05 13:08:49.614   916  1420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:08:49.884   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:08:50.614   303   303 E SMD     : DCD ON
,07-05 13:08:53.604   303   303 E SMD     : DCD ON
,07-05 13:08:56.614   303   303 E SMD     : DCD ON
,07-05 13:08:58.754   916  1321 E Watchdog: !@Sync 41
,07-05 13:08:59.614   303   303 E SMD     : DCD ON
,07-05 13:08:59.674   916  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:08:59.684   916  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:08:59.684   916  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:08:59.684   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:08:59.684   916   916 I MotionRecognitionService: Plugged
,07-05 13:08:59.684   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:08:59.694  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:08:59.694  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:08:59.694   916  1713 D BatteryService: stay LED for fully charged
,07-05 13:08:59.694  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:08:59.694  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:08:59.694  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:08:59.694  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:08:59.704  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
07-05 13:08:59.704  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:08:59.924   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:09:02.624   303   303 E SMD     : DCD ON
,07-05 13:09:05.614   303   303 E SMD     : DCD ON
,07-05 13:09:08.624   303   303 E SMD     : DCD ON
,07-05 13:09:09.734   916  3588 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:09:09.974   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:09:11.624   303   303 E SMD     : DCD ON
,07-05 13:09:14.614   303   303 E SMD     : DCD ON
,07-05 13:09:17.624   303   303 E SMD     : DCD ON
,07-05 13:09:19.794   916  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:09:19.794   916  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:09:19.794   916  1476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:09:19.804   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:09:19.804   916   916 I MotionRecognitionService: Plugged
,07-05 13:09:19.804   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:09:19.814  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:09:19.814  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:09:19.814  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:09:19.814  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:09:19.814  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:09:19.814   916  1476 D BatteryService: stay LED for fully charged
,07-05 13:09:19.814  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:09:19.824  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:09:19.824  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:09:20.024   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:09:20.614   303   303 E SMD     : DCD ON
,07-05 13:09:23.624   303   303 E SMD     : DCD ON
,07-05 13:09:26.614   303   303 E SMD     : DCD ON
,07-05 13:09:28.744   916  1321 E Watchdog: !@Sync 42
,07-05 13:09:29.624   303   303 E SMD     : DCD ON
,07-05 13:09:29.854   916  3344 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:09:29.854   916  3344 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:09:29.854   916  3344 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:09:29.864   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:09:29.864   916   916 I MotionRecognitionService: Plugged
,07-05 13:09:29.864   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:09:29.864  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:09:29.874  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:09:29.874  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:09:29.874  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:09:29.874  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:09:29.874  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:09:29.874   916  3344 D BatteryService: stay LED for fully charged
,07-05 13:09:29.874  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:09:29.884  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:09:30.074   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:09:32.624   303   303 E SMD     : DCD ON
,07-05 13:09:35.624   303   303 E SMD     : DCD ON
,07-05 13:09:38.634   303   303 E SMD     : DCD ON
,07-05 13:09:39.914   916   932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:09:40.124   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:09:41.624   303   303 E SMD     : DCD ON
,07-05 13:09:44.624   303   303 E SMD     : DCD ON
,07-05 13:09:47.634   303   303 E SMD     : DCD ON
,07-05 13:09:49.974   916  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:09:49.974   916  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:09:49.984   916  4028 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:09:49.984   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:09:49.984   916   916 I MotionRecognitionService: Plugged
,07-05 13:09:49.984   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:09:49.994  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:09:49.994  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:09:49.994  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:09:49.994  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:09:49.994  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:09:49.994   916  4028 D BatteryService: stay LED for fully charged
,07-05 13:09:49.994  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:09:50.004  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:09:50.004  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:09:50.174   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:09:50.634   303   303 E SMD     : DCD ON
,07-05 13:09:53.624   303   303 E SMD     : DCD ON
,07-05 13:09:56.634   303   303 E SMD     : DCD ON
,07-05 13:09:57.934   916  1061 I PowerManagerService: [PWL] Off : 1265s ago
,07-05 13:09:58.754   916  1321 E Watchdog: !@Sync 43
,07-05 13:09:59.634   303   303 E SMD     : DCD ON
,07-05 13:10:00.034   916  1364 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:10:00.034   916  1364 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:10:00.034   916  1364 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:10:00.044   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,07-05 13:10:00.044  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:10:00.044  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:10:00.044   916   916 I MotionRecognitionService: Plugged
07-05 13:10:00.044   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:10:00.054  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:10:00.054  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:10:00.054  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:10:00.054  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:10:00.054   916  1364 D BatteryService: stay LED for fully charged
07-05 13:10:00.054  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:10:00.064  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:10:00.224   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:10:02.644   303   303 E SMD     : DCD ON
,07-05 13:10:05.634   303   303 E SMD     : DCD ON
,07-05 13:10:08.634   303   303 E SMD     : DCD ON
,07-05 13:10:10.094   916  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:10:10.104   916  2110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:10:10.104   916  2110 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:10:10.104   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:10:10.104   916   916 I MotionRecognitionService: Plugged
,07-05 13:10:10.104   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:10:10.114  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:10:10.114  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:10:10.114   916  2110 D BatteryService: stay LED for fully charged
,07-05 13:10:10.114  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:10:10.114  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:10:10.114  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:10:10.124  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:10:10.124  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:10:10.124  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:10:10.274   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:10:11.634   303   303 E SMD     : DCD ON
,07-05 13:10:14.634   303   303 E SMD     : DCD ON
,07-05 13:10:17.634   303   303 E SMD     : DCD ON
,07-05 13:10:20.154   916  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:10:20.324   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:10:20.644   303   303 E SMD     : DCD ON
,07-05 13:10:23.644   303   303 E SMD     : DCD ON
,07-05 13:10:26.644   303   303 E SMD     : DCD ON
,07-05 13:10:28.764   916  1321 E Watchdog: !@Sync 44
,07-05 13:10:29.644   303   303 E SMD     : DCD ON
,07-05 13:10:30.224   916   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:10:30.364   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:10:32.634   303   303 E SMD     : DCD ON
,07-05 13:10:35.654   303   303 E SMD     : DCD ON
,07-05 13:10:38.644   303   303 E SMD     : DCD ON
,07-05 13:10:40.294   916  3588 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:10:40.294   916  3588 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:10:40.294   916  3588 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:10:40.294   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:10:40.304  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:10:40.304   916   916 I MotionRecognitionService: Plugged
,07-05 13:10:40.304  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 13:10:40.304   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:10:40.314   916  3588 D BatteryService: stay LED for fully charged
,07-05 13:10:40.324  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:10:40.324  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:10:40.334  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:10:40.334  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:10:40.334  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:10:40.334  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:10:40.414   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:10:41.644   303   303 E SMD     : DCD ON
,07-05 13:10:44.654   303   303 E SMD     : DCD ON
,07-05 13:10:47.644   303   303 E SMD     : DCD ON
,07-05 13:10:50.344   916  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:10:50.354   916  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:10:50.354   916  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:10:50.354   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:10:50.364  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:10:50.364  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:10:50.374   916   916 I MotionRecognitionService: Plugged
,07-05 13:10:50.374   916  1713 D BatteryService: stay LED for fully charged
,07-05 13:10:50.374   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:10:50.374  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:10:50.384  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:10:50.384  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:10:50.394  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:10:50.394  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:10:50.404  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:10:50.464   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:10:50.654   303   303 E SMD     : DCD ON
,07-05 13:10:53.654   303   303 E SMD     : DCD ON
,07-05 13:10:56.644   303   303 E SMD     : DCD ON
,07-05 13:10:58.774   916  1321 E Watchdog: !@Sync 45
,07-05 13:10:59.644   303   303 E SMD     : DCD ON
,07-05 13:11:00.404   916  3588 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:11:00.524   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:11:02.644   303   303 E SMD     : DCD ON
,07-05 13:11:05.644   303   303 E SMD     : DCD ON
,07-05 13:11:08.644   303   303 E SMD     : DCD ON
,07-05 13:11:10.464   916   932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:11:10.564   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:11:11.654   303   303 E SMD     : DCD ON
,07-05 13:11:14.654   303   303 E SMD     : DCD ON
,07-05 13:11:17.654   303   303 E SMD     : DCD ON
,07-05 13:11:20.514   916  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:11:20.644   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:11:20.654   303   303 E SMD     : DCD ON
,07-05 13:11:23.664   303   303 E SMD     : DCD ON
,07-05 13:11:26.654   303   303 E SMD     : DCD ON
,07-05 13:11:28.784   916  1321 E Watchdog: !@Sync 46
,07-05 13:11:29.664   303   303 E SMD     : DCD ON
,07-05 13:11:30.584   916  1420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:11:30.704   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:11:32.654   303   303 E SMD     : DCD ON
,07-05 13:11:35.664   303   303 E SMD     : DCD ON
,07-05 13:11:38.664   303   303 E SMD     : DCD ON
,07-05 13:11:40.634   916  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:11:40.644   916  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:11:40.644   916  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:11:40.644   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:11:40.644   916   916 I MotionRecognitionService: Plugged
,07-05 13:11:40.644   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:11:40.644  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:11:40.654  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:11:40.654  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:11:40.654   916  1713 D BatteryService: stay LED for fully charged
,07-05 13:11:40.654  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:11:40.654  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:11:40.664  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:11:40.664  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:11:40.664  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:11:40.744   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:11:41.654   303   303 E SMD     : DCD ON
,07-05 13:11:44.664   303   303 E SMD     : DCD ON
,07-05 13:11:47.674   303   303 E SMD     : DCD ON
,07-05 13:11:50.674   303   303 E SMD     : DCD ON
,07-05 13:11:50.694   916  3588 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:11:50.824   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:11:52.944   916  1061 I PowerManagerService: [PWL] Off : 1380s ago
,07-05 13:11:53.664   303   303 E SMD     : DCD ON
,07-05 13:11:56.664   303   303 E SMD     : DCD ON
,07-05 13:11:58.774   916  1321 E Watchdog: !@Sync 47
,07-05 13:11:59.664   303   303 E SMD     : DCD ON
,07-05 13:12:00.754   916   932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:12:00.764   916   932 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:12:00.764   916   932 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:12:00.764   916   932 D BatteryService: stay LED for fully charged
,07-05 13:12:00.764   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:12:00.774  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:12:00.774  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:12:00.774  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:12:00.774  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:12:00.784  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:12:00.784  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:12:00.784  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:12:00.784   916   916 I MotionRecognitionService: Plugged
07-05 13:12:00.784  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:12:00.784   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:12:00.864   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:12:02.664   303   303 E SMD     : DCD ON
,07-05 13:12:05.674   303   303 E SMD     : DCD ON
,07-05 13:12:08.664   303   303 E SMD     : DCD ON
,07-05 13:12:10.824   916  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:12:10.824   916  1223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 13:12:10.824   916  1223 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:12:10.824   916  1223 D BatteryService: stay LED for fully charged
,07-05 13:12:10.824   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:12:10.824  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:12:10.824  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 13:12:10.824   916   916 I MotionRecognitionService: Plugged
,07-05 13:12:10.824   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:12:10.834  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:12:10.834  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:12:10.844  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:12:10.844  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 13:12:10.844  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:12:10.844  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:12:10.904   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:12:11.674   303   303 E SMD     : DCD ON
,07-05 13:12:14.664   303   303 E SMD     : DCD ON
,07-05 13:12:17.664   303   303 E SMD     : DCD ON
,07-05 13:12:20.674   303   303 E SMD     : DCD ON
,07-05 13:12:20.874   916   932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:12:20.884   916   932 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:12:20.884   916   932 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:12:20.884   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:12:20.884   916   916 I MotionRecognitionService: Plugged
,07-05 13:12:20.884  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:12:20.894  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:12:20.894   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:12:20.894  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:12:20.894  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:12:20.894   916   932 D BatteryService: stay LED for fully charged
07-05 13:12:20.894  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:12:20.904  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:12:20.904  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:12:20.904  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:12:20.934   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:12:23.674   303   303 E SMD     : DCD ON
,07-05 13:12:26.684   303   303 E SMD     : DCD ON
,07-05 13:12:28.784   916  1321 E Watchdog: !@Sync 48
,07-05 13:12:29.674   303   303 E SMD     : DCD ON
,07-05 13:12:30.934   916  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:12:30.944   916  1223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:12:30.944   916  1223 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:12:30.944   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:12:30.944   916   916 I MotionRecognitionService: Plugged
,07-05 13:12:30.944   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:12:30.944  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:12:30.954  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:12:30.954  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:12:30.954   916  1223 D BatteryService: stay LED for fully charged
,07-05 13:12:30.954  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:12:30.954  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:12:30.954  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:12:30.964  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:12:30.964  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:12:31.004   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:12:32.684   303   303 E SMD     : DCD ON
,07-05 13:12:35.684   303   303 E SMD     : DCD ON
,07-05 13:12:38.684   303   303 E SMD     : DCD ON
,07-05 13:12:40.994   916   932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:12:41.044   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:12:41.684   303   303 E SMD     : DCD ON
,07-05 13:12:44.674   303   303 E SMD     : DCD ON
,07-05 13:12:47.674   303   303 E SMD     : DCD ON
,07-05 13:12:50.684   303   303 E SMD     : DCD ON
,07-05 13:12:51.054   916  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:12:51.064   916  2110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:12:51.064   916  2110 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:12:51.064   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:12:51.064   916   916 I MotionRecognitionService: Plugged
,07-05 13:12:51.064   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:12:51.074  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:12:51.074  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:12:51.074  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:12:51.074   916  2110 D BatteryService: stay LED for fully charged
,07-05 13:12:51.074  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:12:51.084  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:12:51.084  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
07-05 13:12:51.084  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:12:51.084  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:12:51.124   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:12:53.684   303   303 E SMD     : DCD ON
,07-05 13:12:56.674   303   303 E SMD     : DCD ON
,07-05 13:12:58.794   916  1321 E Watchdog: !@Sync 49
,07-05 13:12:59.684   303   303 E SMD     : DCD ON
,07-05 13:13:01.114   916  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:13:01.114   916  1451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:13:01.124   916  1451 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:13:01.124   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:13:01.124  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:13:01.124  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 13:13:01.124   916   916 I MotionRecognitionService: Plugged
07-05 13:13:01.124   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:13:01.134  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:13:01.134  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:13:01.134   916  1451 D BatteryService: stay LED for fully charged
,07-05 13:13:01.134  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:13:01.134  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:13:01.134  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:13:01.144  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:13:01.214   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:13:02.684   303   303 E SMD     : DCD ON
,07-05 13:13:05.684   303   303 E SMD     : DCD ON
,07-05 13:13:08.694   303   303 E SMD     : DCD ON
,07-05 13:13:11.174   916  4028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:13:11.184   916  4028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:13:11.184   916  4028 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 13:13:11.184   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:13:11.184  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:13:11.194   916   916 I MotionRecognitionService: Plugged
,07-05 13:13:11.194   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:13:11.194  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:13:11.194   916  4028 D BatteryService: stay LED for fully charged
,07-05 13:13:11.194  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:13:11.194  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:13:11.204  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:13:11.204  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 13:13:11.204  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:13:11.204  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:13:11.254   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:13:11.684   303   303 E SMD     : DCD ON
,07-05 13:13:14.684   303   303 E SMD     : DCD ON
,07-05 13:13:17.684   303   303 E SMD     : DCD ON
,07-05 13:13:20.694   303   303 E SMD     : DCD ON
,07-05 13:13:21.244   916  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:13:21.244   916  1451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:13:21.254   916  1451 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:13:21.254   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:13:21.254   916   916 I MotionRecognitionService: Plugged
,07-05 13:13:21.264   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:13:21.264  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:13:21.264  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:13:21.264   916  1451 D BatteryService: stay LED for fully charged
,07-05 13:13:21.274  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:13:21.284  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:13:21.284  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:13:21.304  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:13:21.304  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:13:21.304  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:13:21.334   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:13:23.684   303   303 E SMD     : DCD ON
,07-05 13:13:25.864   916  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 13:13:25.864   916  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 13:13:25.874   916  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 13:13:26.684   303   303 E SMD     : DCD ON
,07-05 13:13:28.724   916  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 13:13:28.724   916  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 13:13:28.734   916  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 13:13:28.744   916  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 13:13:28.794   916  1321 E Watchdog: !@Sync 50
,07-05 13:13:29.694   303   303 E SMD     : DCD ON
,07-05 13:13:31.304   916  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:13:31.304   916  2110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:13:31.304   916  2110 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:13:31.314   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:13:31.314  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:13:31.314  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:13:31.324   916   916 I MotionRecognitionService: Plugged
07-05 13:13:31.324   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:13:31.324   916  2110 D BatteryService: stay LED for fully charged
,07-05 13:13:31.324  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:13:31.334  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:13:31.334  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:13:31.344  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:13:31.344  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 13:13:31.344  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:13:31.374   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:13:32.684   303   303 E SMD     : DCD ON
,07-05 13:13:35.694   303   303 E SMD     : DCD ON
,07-05 13:13:38.694   303   303 E SMD     : DCD ON
,07-05 13:13:41.364   916  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:13:41.364   916  1451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 13:13:41.364   916  1451 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 13:13:41.374   916   916 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 13:13:41.384   916   916 I MotionRecognitionService: Plugged
,07-05 13:13:41.384  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 13:13:41.394  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 13:13:41.394   916   916 I MotionRecognitionService: setPowerConnected  = true
,07-05 13:13:41.394  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 13:13:41.394   916  1451 D BatteryService: stay LED for fully charged
,07-05 13:13:41.404  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:13:41.414  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 13:13:41.414  3197  3408 D HeadsetStateMachine: Disconnected process message: 10
,07-05 13:13:41.424  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:13:41.424  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 13:13:41.444   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:13:41.694   303   303 E SMD     : DCD ON
,07-05 13:13:44.704   303   303 E SMD     : DCD ON
,07-05 13:13:47.704   303   303 E SMD     : DCD ON
,07-05 13:13:50.704   303   303 E SMD     : DCD ON
,07-05 13:13:51.424   916  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:13:51.524   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:13:52.944   916  1061 I PowerManagerService: [PWL] Off : 1500s ago
,07-05 13:13:53.694   303   303 E SMD     : DCD ON
,07-05 13:13:56.704   303   303 E SMD     : DCD ON
,07-05 13:13:58.784   916  1321 E Watchdog: !@Sync 51
,07-05 13:13:59.704   303   303 E SMD     : DCD ON
,07-05 13:14:01.484   916  1419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 13:14:01.604   916  3260 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 13:14:02.694   303   303 E SMD     : DCD ON
,07-05 13:14:05.694   303   303 E SMD     : DCD ON
,TIME-OUT KILL (timeout was 1400000ms),07-05 13:14:08.714   303   303 E SMD     : DCD ON
07-05 13:14:08.934  7711  7711 D AndroidRuntime: 
07-05 13:14:08.934  7711  7711 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 13:14:08.934  7711  7711 D AndroidRuntime: CheckJNI is OFF
07-05 13:14:08.934  7711  7711 D AndroidRuntime: readGMSProperty: start
07-05 13:14:08.944  7711  7711 D AndroidRuntime: readGMSProperty: already setted!!
07-05 13:14:08.944  7711  7711 D AndroidRuntime: readGMSProperty: end
07-05 13:14:08.944  7711  7711 D AndroidRuntime: addProductProperty: start
07-05 13:14:09.114  7711  7711 E AffinityControl: AffinityControl: registerfunction enter
07-05 13:14:09.144  7711  7711 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-05 13:14:09.144   916  1713 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-05 13:14:09.144   916  1713 D PackageManager: START PACKAGE DELETE: observer{523847184}
07-05 13:14:09.144   916  1713 D PackageManager: pkg{<packageName>}
07-05 13:14:09.144   916  1713 D PackageManager: user{0}
07-05 13:14:09.144   916  1713 D PackageManager: caller{2000}
07-05 13:14:09.144   916  1713 D PackageManager: flags{2}
07-05 13:14:09.144   916  1713 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-05 13:14:09.144   916  1713 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-05 13:14:09.154   916  1713 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 13:14:09.154   916  1713 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 13:14:09.154   916  1065 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-05 13:14:09.154   916  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-05 13:14:09.154   916  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-05 13:14:09.154   916  1065 D ApplicationPolicy: getApplicationUninstallationEnabled
07-05 13:14:09.154   916  1065 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-05 13:14:09.154   916  1065 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
07-05 13:14:09.154   916  1008 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
07-05 13:14:09.154   916  1008 I ActivityManager: Killing 7427:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
07-05 13:14:09.154   916  1008 I ActivityManager:   Force finishing activity ActivityRecord{155e3d6f u0 com.test.thalitest/.MainActivity t23}
07-05 13:14:09.164   916  1008 D FocusedStackFrame: Set to : 0
07-05 13:14:09.164   266   982 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
07-05 13:14:09.164   266   981 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
07-05 13:14:09.174   916  3260 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 13:14:09.314   916  1065 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
07-05 13:14:09.344  1605  1605 I art     : Explicit concurrent mark sweep GC freed 458(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 19MB/32MB, paused 371us total 27.183ms
07-05 13:14:09.354  5201  5201 I art     : Explicit concurrent mark sweep GC freed 853(47KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 300us total 38.709ms
07-05 13:14:09.374  5338  5338 I art     : Explicit concurrent mark sweep GC freed 35132(1919KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 15MB/26MB, paused 366us total 28.390ms
07-05 13:14:09.384  6429  6429 I art     : Explicit concurrent mark sweep GC freed 20348(2MB) AllocSpace objects, 2(40KB) LOS objects, 31% free, 17MB/25MB, paused 698us total 44.753ms
07-05 13:14:09.384  5760  5760 I art     : Explicit concurrent mark sweep GC freed 11657(638KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 326us total 56.313ms
07-05 13:14:09.384   916  3196 E libprocessgroup: failed to kill 1 processes for processgroup 7427
07-05 13:14:09.404   916  1059 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
07-05 13:14:09.404  1983  2345 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-05 13:14:09.404  1689  1689 E SamsungIME: mOCRHelper is null
07-05 13:14:09.404  1448  1448 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
07-05 13:14:09.414  1448  1448 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 13:14:09.414  1421  1421 D RegisteredServicesCache: empty dynamic service
07-05 13:14:09.414  1448  1448 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-05 13:14:09.414   916  1119 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-05 13:14:09.414  1448  1448 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
07-05 13:14:09.414  1448  1448 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 13:14:09.414  1448  1448 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 13:14:09.414  1448  1448 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-05 13:14:09.414  1448  1448 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
07-05 13:14:09.424  1448  1448 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 13:14:09.424  1448  1448 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-05 13:14:09.444  2565  2565 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-05 13:14:09.444   916  1145 V NetworkStats: removeUidsLocked() for UIDs [10079]
07-05 13:14:09.444   916  1145 V NetworkStats: performPollLocked(flags=0x3)
07-05 13:14:09.444   916  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 13:14:09.454   916  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-05 13:14:09.454   916  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 13:14:09.454   916  1145 V NetworkStats: performPollLocked() took 4ms
07-05 13:14:09.454   916  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 13:14:09.474   916  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 13:14:09.474   916  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 13:14:09.494  2565  2565 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1467717249500
07-05 13:14:09.494  2565  2565 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
07-05 13:14:09.504   916   916 I art     : Explicit concurrent mark sweep GC freed 33964(2MB) AllocSpace objects, 47(752KB) LOS objects, 30% free, 36MB/52MB, paused 2.139ms total 135.182ms
07-05 13:14:09.504   916   916 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
07-05 13:14:09.504   916  1065 I art     : WaitForGcToComplete blocked for 56.710ms for cause Explicit
07-05 13:14:09.504  2565  2565 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
07-05 13:14:09.514   916   916 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
07-05 13:14:09.524   916   916 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
07-05 13:14:09.524   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
07-05 13:14:09.534   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
07-05 13:14:09.534   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
07-05 13:14:09.534   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
07-05 13:14:09.544   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
07-05 13:14:09.544   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
07-05 13:14:09.554   916  3588 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-05 13:14:09.554   916  3588 D SecContentProvider2: mCursor = null
07-05 13:14:09.564   916   916 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
07-05 13:14:09.564   916   916 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
07-05 13:14:09.564   916   916 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
07-05 13:14:09.584   916   916 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
07-05 13:14:09.584   916   916 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
07-05 13:14:09.584   916   916 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
07-05 13:14:09.584   916   916 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
07-05 13:14:09.594   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
07-05 13:14:09.604   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
07-05 13:14:09.604   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
07-05 13:14:09.604   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
07-05 13:14:09.614   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
07-05 13:14:09.614   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
07-05 13:14:09.614   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
07-05 13:14:09.614  2565  2565 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
07-05 13:14:09.614   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
07-05 13:14:09.624   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
07-05 13:14:09.624  2565  2565 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
07-05 13:14:09.624   916  1364 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
07-05 13:14:09.624   916  1364 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 13:14:09.624   916  1364 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 13:14:09.624   916  1364 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 13:14:09.624   916  1364 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 13:14:09.634   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
07-05 13:14:09.634   916   916 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
07-05 13:14:09.634   916   916 D RCPManagerService: PackageReceiver onReceive()
07-05 13:14:09.634   916   916 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
07-05 13:14:09.634   916   916 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-05 13:14:09.644   916   916 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 13:14:09.644   916   916 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-05 13:14:09.644   916   916 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-05 13:14:09.644   916   916 V EnterpriseBillingPolicy: uID is 10079
07-05 13:14:09.644   916   916 V EnterpriseBillingPolicy: Removed Packageuid is0
07-05 13:14:09.644   916   916 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-05 13:14:09.644   916   916 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
07-05 13:14:09.644   916   916 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-05 13:14:09.644   916   916 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-05 13:14:09.644   916   916 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-05 13:14:09.644   916   916 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-05 13:14:09.674  7739  7739 E Zygote  : MountEmulatedStorage()
07-05 13:14:09.674  7739  7739 E Zygote  : v2
07-05 13:14:09.674  7739  7739 I libpersona: KNOX_SDCARD checking this for 10116
07-05 13:14:09.674  7739  7739 I libpersona: KNOX_SDCARD not a persona
07-05 13:14:09.674   916  1364 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7739 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
07-05 13:14:09.684   916  3260 D SSRM:aY : MSG_TYPE_APP_REMOVED::
07-05 13:14:09.684   916  1178 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
07-05 13:14:09.684   916   916 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
07-05 13:14:09.704  7739  7739 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 13:14:09.704  7739  7739 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 13:14:09.704  7739  7739 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 13:14:09.714   916  1065 I art     : Explicit concurrent mark sweep GC freed 12481(670KB) AllocSpace objects, 2(32KB) LOS objects, 30% free, 36MB/52MB, paused 1.451ms total 209.542ms
07-05 13:14:09.734  7739  7739 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 13:14:09.734  7739  7739 D ActivityThread: Added TimaKeyStore provider
07-05 13:14:09.764  7739  7739 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
07-05 13:14:09.764  1448  1448 D SurfaceWidgetView: destroyHardwareResources():764520145
07-05 13:14:09.764   916  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
07-05 13:14:09.764  1448  1448 D Launcher: onRestart, Launcher: 395427166
07-05 13:14:09.764  1448  1448 D Launcher: onStart, Launcher: 395427166
07-05 13:14:09.764  1448  1448 D Launcher.HomeView: onStart
07-05 13:14:09.764  1448  1448 V ActivityThread: updateVisibility : ActivityRecord{3c4af118 token=android.os.BinderProxy@909659b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-05 13:14:09.764  1759  1769 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
07-05 13:14:09.764  1759  1998 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
07-05 13:14:09.774  1759  1998 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
07-05 13:14:09.774   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
07-05 13:14:09.774  7739  7739 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
07-05 13:14:09.784  7739  7739 D elm:14491: ELMEngine.ELMEngine( context ).
07-05 13:14:09.784  7739  7739 D elm:14491: MDMBridge.setEnterpriseBridge()
07-05 13:14:09.784   916  1364 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-05 13:14:09.784   916  1364 D ActivityManager: caller:android.app.ApplicationThreadProxy@326fa2fb, r.packageName :com.sec.esdk.elm
07-05 13:14:09.784   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
07-05 13:14:09.784   266   266 I SurfaceFlinger: id=14 createSurf (1080x1920),1 flag=4, Mauncher
07-05 13:14:09.784  7739  7739 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
07-05 13:14:09.784   916  1065 D PackageManager: delete codoeFile: 
07-05 13:14:09.794   916  1065 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
07-05 13:14:09.794   916  1065 I AASA_removePackage: UID=10079 Target=com.test.thalitest
07-05 13:14:09.794  7739  7739 D elm:14491: ElmAgentService : onCreate()
07-05 13:14:09.794   916  1065 D PackageManager: result of delete: 1{523847184}
07-05 13:14:09.794  7739  7755 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-05 13:14:09.794  7739  7755 D elm:14491: MainReceiver.listeningToPackageRemoved()
07-05 13:14:09.794  7739  7755 D elm:14491: MDMBridge.getInstance()
07-05 13:14:09.794  7739  7755 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
07-05 13:14:09.794  3818  3818 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
07-05 13:14:09.794  3818  3818 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 13:14:09.794  3818  3818 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
07-05 13:14:09.794  3818  3818 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-05 13:14:09.794  3818  3818 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-05 13:14:09.794  3818  3818 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-05 13:14:09.794  3818  3818 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-05 13:14:09.794  3818  3818 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:14:09.794  3818  3818 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 13:14:09.794  3818  3818 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-05 13:14:09.794  3818  3818 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 13:14:09.794  3818  3818 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 13:14:09.794  3818  3818 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-05 13:14:09.794  3818  3818 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-05 13:14:09.804  7739  7755 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
07-05 13:14:09.804   916  1003 D EnterpriseDeviceManagerService: Package has changed for user 0
07-05 13:14:09.804   916  1003 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-05 13:14:09.804   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
07-05 13:14:09.804  7711  7711 D AndroidRuntime: Shutting down VM
07-05 13:14:09.804  7739  7739 D elm:14491: ElmAgentService : onDestroy().
07-05 13:14:09.804  4077  4077 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-05 13:14:09.804  4077  4077 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
07-05 13:14:09.814   916  3588 I ActivityManager: Killing 6711:flipboard.app/u0a125 (adj 15): emptyCount ##41
07-05 13:14:09.814   916  1419 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 13:14:09.814   916  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
07-05 13:14:09.814   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.814   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
07-05 13:14:09.824   916  1451 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-05 13:14:09.824   916  1451 D ActivityManager: caller:android.app.ApplicationThreadProxy@31cbefad, r.packageName :com.google.android.gms
07-05 13:14:09.824   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
07-05 13:14:09.834  2202  7760 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-05 13:14:09.834  2202  7760 D AccountUtils: Clearing selected account for com.test.thalitest
07-05 13:14:09.834  2202  2202 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
07-05 13:14:09.834  2202  2202 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
07-05 13:14:09.834  2202  2202 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-05 13:14:09.834  2202  2202 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-05 13:14:09.834   916  3344 D ActivityManager: caller:android.app.ApplicationThreadProxy@27b0a930, r.packageName :com.google.android.gms
07-05 13:14:09.834  2202  2202 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
07-05 13:14:09.834  2202  2202 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
07-05 13:14:09.834  2202  2202 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-05 13:14:09.834  2202  2202 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-05 13:14:09.834   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
07-05 13:14:09.844   916  1419 D ActivityManager: caller:android.app.ApplicationThreadProxy@342f285c, r.packageName :com.google.android.gms
07-05 13:14:09.854   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.854   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
07-05 13:14:09.854   916  3344 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 13:14:09.854   916  3344 D ActivityManager: caller:android.app.ApplicationThreadProxy@2cb46e48, r.packageName :com.google.android.gms
07-05 13:14:09.854  2202  7760 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
07-05 13:14:09.854   916  1239 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
07-05 13:14:09.854   916  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
07-05 13:14:09.854  7114  7114 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
07-05 13:14:09.854  7114  7114 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
07-05 13:14:09.854  7114  7114 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
07-05 13:14:09.864   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.864   916  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
07-05 13:14:09.864   916  1059 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2539f0b8 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t20} time:1559786
07-05 13:14:09.864   916  1059 D MultiWindowConverter: MultiWindow Gesture is not supported with launcher
07-05 13:14:09.864   916  1223 D ActivityManager: caller:android.app.ApplicationThreadProxy@adce263, r.packageName :com.google.android.gms
07-05 13:14:09.874  7132  7132 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-05 13:14:09.874  7132  7132 I PCWCLIENTTRACE_PushUtil: sales region : global
07-05 13:14:09.874  7132  7132 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-05 13:14:09.874  7132  7132 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
07-05 13:14:09.874   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.874   916  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
07-05 13:14:09.884   916  2110 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 13:14:09.884   916  2110 D ActivityManager: caller:android.app.ApplicationThreadProxy@15c7ebde, r.packageName :com.google.android.gms
07-05 13:14:09.884  2202  7765 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
07-05 13:14:09.884  2202  7765 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
07-05 13:14:09.884   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.884   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.884   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
07-05 13:14:09.894   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.894   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
07-05 13:14:09.894   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
07-05 13:14:09.894   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
07-05 13:14:09.904  2202  7765 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
07-05 13:14:09.904  2202  7765 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
07-05 13:14:09.904   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
07-05 13:14:09.904   916   932 D ActivityManager: startService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.sec.android.app.shealth
07-05 13:14:09.904   916   932 D ActivityManager: caller:android.app.ApplicationThreadProxy@22ff98b6, r.packageName :com.sec.android.app.shealth
07-05 13:14:09.904   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.904   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
07-05 13:14:09.914  2202  7765 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
07-05 13:14:09.914  2202  7765 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
07-05 13:14:09.914   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
07-05 13:14:09.924  2202  7765 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
07-05 13:14:09.924   916  1239 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 13:14:09.924   916  1239 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e648a42, r.packageName :com.google.android.gms
07-05 13:14:09.924   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
07-05 13:14:09.934  2202  7765 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
07-05 13:14:09.934  2202  7765 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
07-05 13:14:09.934  2202  7765 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
07-05 13:14:09.934   916  1451 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 13:14:09.934  4077  4077 I ConfigService: onCreate
07-05 13:14:09.934   916  1451 D ActivityManager: caller:android.app.ApplicationThreadProxy@25217c45, r.packageName :com.google.android.gms
07-05 13:14:09.934  4077  4077 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-05 13:14:09.934   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
07-05 13:14:09.944   916  1239 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
07-05 13:14:09.944   916  1239 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 13:14:09.944   916  1239 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 13:14:09.944   916  1239 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 13:14:09.944   916  1239 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 13:14:09.944   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.944   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.944   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
07-05 13:14:09.944   916  1003 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-05 13:14:09.944   916  1003 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 13:14:09.944   916  1003 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 13:14:09.944  4077  4077 I ConfigService: onBind returning update interface
07-05 13:14:09.954   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.954   916  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
07-05 13:14:09.954   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.954   916  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
07-05 13:14:09.954   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.954   916  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
07-05 13:14:09.964   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.964   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-05 13:14:09.964   916  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
07-05 13:14:09.964   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.964   916  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
07-05 13:14:09.964   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.964   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-05 13:14:09.964   916  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
07-05 13:14:09.974   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.974   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-05 13:14:09.974   916  1003 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
07-05 13:14:09.974   916  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 13:14:09.984  7770  7770 E Zygote  : MountEmulatedStorage()
07-05 13:14:09.984  7770  7770 E Zygote  : v2
07-05 13:14:09.984  7770  7770 I libpersona: KNOX_SDCARD checking this for 10043
07-05 13:14:09.984  7770  7770 I libpersona: KNOX_SDCARD not a persona
07-05 13:14:09.994  7770  7770 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 13:14:09.994  7770  7770 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 13:14:09.994  7770  7770 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-05 13:14:09.994   916  1239 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7770 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 13:14:09.994   916  4028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 13:14:09.994   916  4028 D ActivityManager: caller:android.app.ApplicationThreadProxy@36217df9, r.packageName :com.google.android.gms
07-05 13:14:09.994  4077  4077 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-05 13:14:09.994  4077  4077 I ConfigService: onBind returning service broker
07-05 13:14:10.004   916  1003 D UsbSettingsManager: clearDefaults: com.test.thalitest

```
