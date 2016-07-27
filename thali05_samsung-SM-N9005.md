#### Test 78968685da35147_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
07-27 08:53:41.616   297   297 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
07-27 08:53:41.616   297   297 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
07-27 08:53:41.616   297   297 I rmt_storage: wakelock acquired: 1, error no: 42
07-27 08:53:41.616   297   678 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,07-27 08:53:41.716   297   678 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
07-27 08:53:41.716   297   678 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
07-27 08:53:41.727   297   678 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 0
07-27 08:53:41.727   297   678 I rmt_storage: 
07-27 08:53:41.737   297   297 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
07-27 08:53:42.026  6269  6269 D AndroidRuntime: 
07-27 08:53:42.026  6269  6269 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 08:53:42.036  6269  6269 D AndroidRuntime: CheckJNI is OFF
07-27 08:53:42.036  6269  6269 D AndroidRuntime: readGMSProperty: start
07-27 08:53:42.036  6269  6269 D AndroidRuntime: readGMSProperty: already setted!!
07-27 08:53:42.036  6269  6269 D AndroidRuntime: readGMSProperty: end
07-27 08:53:42.036  6269  6269 D AndroidRuntime: addProductProperty: start
07-27 08:53:42.246  6269  6269 E AffinityControl: AffinityControl: registerfunction enter
07-27 08:53:42.266  6269  6269 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 08:53:42.276   754  1657 E PersonaManagerService: inState():  stateMachine is null !!
07-27 08:53:42.276   754  1657 I PersonaManagerService: PersonaId don't exist
07-27 08:53:42.276   754  1657 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-27 08:53:42.276   754  1657 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
07-27 08:53:42.286   754  1657 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 08:53:42.286   754  1657 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-27 08:53:42.296   754  1657 W ActivityManager: mDVFSHelper.acquire()
07-27 08:53:42.296   754  1657 D FocusedStackFrame: Set to : 0
07-27 08:53:42.296   754  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:42.296   754  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:42.296   754  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:42.296   754  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:42.326   308   308 E SMD     : DCD ON
07-27 08:53:42.346  6285  6285 E Zygote  : MountEmulatedStorage()
07-27 08:53:42.346  6285  6285 E Zygote  : v2
07-27 08:53:42.346  6285  6285 I libpersona: KNOX_SDCARD checking this for 10079
07-27 08:53:42.346  6285  6285 I libpersona: KNOX_SDCARD not a persona
07-27 08:53:42.346   754  1657 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6285 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-27 08:53:42.356  6285  6285 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:53:42.356  6285  6285 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 08:53:42.356  6285  6285 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-27 08:53:42.366  6269  6269 D AndroidRuntime: Shutting down VM
07-27 08:53:42.406  6285  6285 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:42.416  6285  6285 D ActivityThread: Added TimaKeyStore provider
07-27 08:53:42.416   754   754 V ActivityManager: Display changed displayId=0
07-27 08:53:42.436  1456  1456 V ActivityThread: updateVisibility : ActivityRecord{14ce2659 token=android.os.BinderProxy@b121bf9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-27 08:53:42.436  1789  1917 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
07-27 08:53:42.446  1456  1456 D SurfaceWidgetView: destroyHardwareResources():398518713
07-27 08:53:42.456  6285  6285 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-27 08:53:42.466   754  2987 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:53:42.536  6285  6285 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-27 08:53:42.536  6285  6285 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
07-27 08:53:42.546   266   337 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
07-27 08:53:42.546   266   321 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
07-27 08:53:42.556  6285  6285 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 450-452)
07-27 08:53:42.556  6285  6285 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:53:42.556  1456  1456 D Launcher: onTrimMemory. Level: 20
,07-27 08:53:42.586  6285  6285 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23756f8b}
07-27 08:53:42.586  6285  6285 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:53:42.586  6285  6285 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 08:53:42.626  6285  6285 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-27 08:53:42.626  6285  6285 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:53:42.626  6285  6285 E SysUtils: ApplicationContext is null in ApplicationStatus
07-27 08:53:42.646  6285  6310 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
07-27 08:53:42.656  6285  6285 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-27 08:53:42.656  6285  6285 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-27 08:53:42.656  6285  6285 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
07-27 08:53:42.666  6285  6285 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-27 08:53:42.666  6285  6285 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-27 08:53:42.666  6285  6285 I Adreno-EGL: Build Date: 11/19/14 Wed
07-27 08:53:42.666  6285  6285 I Adreno-EGL: Local Branch: mybranch5813579
07-27 08:53:42.666  6285  6285 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-27 08:53:42.666  6285  6285 I Adreno-EGL: Local Patches: NONE
07-27 08:53:42.666  6285  6285 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
07-27 08:53:42.796  6285  6319 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
07-27 08:53:42.836  6285  6285 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:53:42.846  6285  6285 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-27 08:53:42.866  6285  6285 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-27 08:53:42.866  6285  6285 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:53:42.866  6285  6285 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:53:42.936  6285  6285 D Activity: performCreate Call secproduct feature valuefalse
07-27 08:53:42.936  6285  6285 D Activity: performCreate Call debug elastic valuetrue
07-27 08:53:42.946   754  1008 W ActivityManager: Activity pause timeout for ActivityRecord{171a89d5 u0 com.test.thalitest/.MainActivity t36}
07-27 08:53:42.956  6285  6336 D OpenGLRenderer: Render dirty regions requested: true
07-27 08:53:42.966   754  1657 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-27 08:53:42.966   754  1657 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-27 08:53:42.966   754  1657 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-27 08:53:42.966   754   754 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-27 08:53:42.966   754   754 D PersonaManagerService: getPersonasForUser(): returning null!
07-27 08:53:42.986  6285  6285 V ActivityThread: updateVisibility : ActivityRecord{21302a2d token=android.os.BinderProxy@2d8d8a57 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-27 08:53:42.996   266   266 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
07-27 08:53:43.016  6285  6336 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 08:53:43.026  6285  6336 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3cede20 ,&mEglDisplay = 1 , &mEglConfig = 8 
07-27 08:53:43.036  6285  6336 D OpenGLRenderer: Enabling debug mode 0
07-27 08:53:43.096  6285  6285 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d8d8a57 time:100989
07-27 08:53:43.096   754  1057 W ActivityManager: mDVFSHelper.release()
07-27 08:53:43.096   754  1057 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{171a89d5 u0 com.test.thalitest/.MainActivity t36} time:100996
07-27 08:53:43.146  6285  6285 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6285
07-27 08:53:43.366  6285  6285 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 08:53:43.536  6285  6339 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1359649152
,07-27 08:53:43.556  6285  6339 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 08:53:43.556  6285  6339 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 08:53:43.556  6285  6339 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 08:53:43.556  6285  6339 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 08:53:43.556  6285  6339 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-27 08:53:43.556  6285  6339 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171cf89d added. We now have 1 listener(s)
,07-27 08:53:43.556  6285  6339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:2A:28:2D
,07-27 08:53:43.566  6285  6339 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,07-27 08:53:43.566  6285  6339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-27 08:53:43.566  6285  6339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 08:53:43.576  6285  6339 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 08:53:43.576  6285  6339 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 08:53:43.576  6285  6339 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 08:53:43.576  6285  6339 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:2A:28:2D
07-27 08:53:43.576  6285  6339 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 08:53:43.576  6285  6339 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 08:53:43.576  6285  6339 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 08:53:43.576  6285  6339 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 08:53:43.576  6285  6339 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 08:53:43.576  6285  6339 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 08:53:43.576  6285  6339 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-27 08:53:43.576  6285  6339 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29bc3ae0 added. We now have 1 listener(s)
,07-27 08:53:43.576  6285  6339 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 08:53:43.586  6285  6339 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-27 08:53:43.586  6285  6339 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-27 08:53:43.596  6285  6339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 08:53:43.596  6285  6339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-27 08:53:43.596  6285  6339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-27 08:53:43.596  6285  6339 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-27 08:53:43.596  6285  6339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 08:53:43.606  6285  6339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:2A:28:2D
,07-27 08:53:43.606  6285  6339 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-27 08:53:43.606  6285  6339 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:53:43.606  6285  6339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:43.606  6285  6339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:53:43.606  6285  6339 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:53:43.606  6285  6339 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:53:43.606  6285  6339 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:53:43.606  6285  6339 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:53:43.606  6285  6339 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 08:53:43.616  6285  6339 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 08:53:43.616  6285  6339 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 08:53:43.616  6285  6339 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-27 08:53:43.646  6285  6285 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 08:53:43.936   754  2987 D SSRM:n  : SIOP:: AP = 340, PST = 383, CUR = 450
,07-27 08:53:44.846  6285  6348 W jxcore-log: Initializing JXcore engine
,07-27 08:53:44.846  6285  6348 W jxcore-log: JXcore engine is ready
,07-27 08:53:44.926  1930  1930 E auditd  : In denial and Property audit_ondenial is set to 1 
,07-27 08:53:44.926  1930  1930 E audit   : type=1400 msg=audit(1469602424.926:201): avc:  denied  { ioctl } for  pid=6348 comm="Thread-1043" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,07-27 08:53:44.926  1930  1930 E audit   :  SEPF_SM-N9005_5.0-1_0032
07-27 08:53:44.926  1930  1930 E audit   : 
07-27 08:53:44.926   754  1052 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
07-27 08:53:44.926  1930  1930 E audit   : type=1300 msg=audit(1469602424.926:201): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9a9008d8 items=0 ppid=349 ppcomm=main pid=6348 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1043" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-27 08:53:44.926  1930  1930 E audit   : type=1320 msg=audit(1469602424.926:201): 
07-27 08:53:44.926   754  1052 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
07-27 08:53:44.936   754  1008 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
07-27 08:53:44.936   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:44.936   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:44.936   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:44.936   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:44.936   754  1052 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,07-27 08:53:44.956  6285  6348 W jxcore-log: Starting JXcore engine
,07-27 08:53:45.046   754  1008 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6355 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-27 08:53:45.046  6355  6355 E Zygote  : MountEmulatedStorage()
07-27 08:53:45.046  6355  6355 E Zygote  : v2
07-27 08:53:45.046  6355  6355 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:53:45.046  6355  6355 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:45.066  6285  6348 W jxcore-log: Platform android
07-27 08:53:45.066  6285  6348 W jxcore-log: 
,07-27 08:53:45.076  6285  6348 W jxcore-log: Process ARCH arm
07-27 08:53:45.076  6285  6348 W jxcore-log: 
,07-27 08:53:45.086  6355  6355 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-27 08:53:45.086  6355  6355 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:53:45.086  6355  6355 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:53:45.116   754   785 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:53:45.116   754   785 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 08:53:45.116   754   785 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 08:53:45.116   754   785 D BatteryService: stay LED for fully charged
07-27 08:53:45.116   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:53:45.116   754   754 I MotionRecognitionService: Plugged
07-27 08:53:45.116   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:53:45.116  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:53:45.116  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:53:45.136  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:53:45.136  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:53:45.136  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:53:45.156  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:53:45.176  6355  6355 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:45.176  6355  6355 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:45.196  6355  6355 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,07-27 08:53:45.216  6355  6355 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-27 08:53:45.216  6355  6355 D SecurityLogAgent:  SeDenialReceiver : File path = null
,07-27 08:53:45.226   754  1657 I ActivityManager: Killing 5481:com.android.providers.calendar/u0a51 (adj 15): emptyCount ##41
,07-27 08:53:45.326   308   308 E SMD     : DCD ON
,07-27 08:53:45.366  6285  6348 I jxcore-log: JXcore Cordova bridge is ready!
07-27 08:53:45.366  6285  6348 I jxcore-log: 
,07-27 08:53:45.366  6285  6348 W jxcore-log: JXcore engine is started
,07-27 08:53:45.386  6285  6339 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 08:53:45.386  6285  6285 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 08:53:48.336   308   308 E SMD     : DCD ON
,07-27 08:53:50.676   754  1347 E Watchdog: !@Sync 3
,07-27 08:53:51.336   308   308 E SMD     : DCD ON
,07-27 08:53:52.356   754  1063 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-27 08:53:52.586   360   360 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-27 08:53:52.586   360   360 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-27 08:53:52.846  5548  5548 D FactoryTest: Not factory mode
,07-27 08:53:52.846  5548  5548 D FactoryTest: Not factory mode. isFactoryMode() returend false
,07-27 08:53:52.856  5548  5548 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,07-27 08:53:52.856  5548  5548 D MTPRx   : still no open session command from host, so toast
,07-27 08:53:52.856  5548  5548 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1583 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 android.os.Handler.dispatchMessage:102 
,07-27 08:53:52.856  5548  5548 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.app.ContextImpl.startActivity:1584 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 
,07-27 08:53:52.856  5548  5548 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:110753
,07-27 08:53:52.856   754  1593 E PersonaManagerService: inState():  stateMachine is null !!
,07-27 08:53:52.856   754  1593 I PersonaManagerService: PersonaId don't exist
07-27 08:53:52.856   754  1593 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,07-27 08:53:52.856   754  1593 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,07-27 08:53:52.856   754  1593 I ActivityManager: START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,07-27 08:53:52.866   754  1593 W ActivityManager: mDVFSHelper.acquire()
,07-27 08:53:52.876   754  2987 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:52.876  5548  5548 E MTPRx   : started activity for popup
,07-27 08:53:52.896  5548  5548 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,07-27 08:53:52.906  5548  5548 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,07-27 08:53:52.906  5548  5548 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
07-27 08:53:52.906  5548  5548 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-27 08:53:52.906  5548  5548 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 08:53:52.906  5548  5548 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 08:53:52.906  5548  5548 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-27 08:53:52.926  5548  5548 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,07-27 08:53:52.946  5548  5548 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,07-27 08:53:52.956  5548  5548 D Activity: performCreate Call secproduct feature valuefalse
07-27 08:53:52.956  5548  5548 D Activity: performCreate Call debug elastic valuetrue
,07-27 08:53:52.966  6285  6285 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-27 08:53:52.966  6285  6285 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,07-27 08:53:52.966  6285  6285 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-27 08:53:52.966  6285  6285 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-27 08:53:52.966   754  1580 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-27 08:53:52.966   754  1580 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-27 08:53:52.966   754  1580 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-27 08:53:52.966   754   754 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-27 08:53:52.966   754   754 D PersonaManagerService: getPersonasForUser(): returning null!
,07-27 08:53:52.986  6285  6285 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-27 08:53:52.986  6285  6285 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-27 08:53:52.986  6285  6285 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d8d8a57 time:110886
,07-27 08:53:52.996  6285  6285 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@16bfb50a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@13d6e410, 16908290=android.view.AbsSavedState$1@13d6e410}, android:focusedViewId=100}]}]
,07-27 08:53:52.996  6285  6285 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-27 08:53:52.996  6285  6285 V ActivityThread: updateVisibility : ActivityRecord{21302a2d token=android.os.BinderProxy@2d8d8a57 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-27 08:53:52.996  6285  6285 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-27 08:53:52.996  6285  6285 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-27 08:53:53.296   754  2987 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:53.976   754  2987 D SSRM:n  : SIOP:: AP = 360, PST = 380, CUR = 450
,07-27 08:53:54.336   308   308 E SMD     : DCD ON
,07-27 08:53:55.196   754  1639 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:53:55.196   754  1639 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 08:53:55.196   754  1639 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 08:53:55.196   754  1639 D BatteryService: stay LED for fully charged
07-27 08:53:55.196   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:53:55.196  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:53:55.196  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
07-27 08:53:55.196   754   754 I MotionRecognitionService: Plugged
07-27 08:53:55.196   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:53:55.206  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:53:55.206  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:53:55.206  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:53:55.206  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:53:55.716  6285  6348 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 08:53:55.716  6285  6348 I jxcore-log: 
,07-27 08:53:55.726  6285  6348 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 08:53:55.726  6285  6348 I jxcore-log: 
,07-27 08:53:55.726  6285  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-27 08:53:55.726  6285  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:53:55.726  6285  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:55.726  6285  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:53:55.726  6285  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:53:55.726  6285  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:53:55.726  6285  6348 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:53:55.726  6285  6348 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:53:55.726  6285  6348 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:53:55.726  6285  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:53:55.726  6285  6348 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 08:53:55.726  6285  6348 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 08:53:55.726  6285  6348 I jxcore-log: 
,07-27 08:53:55.726  6285  6348 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 08:53:55.726  6285  6348 I jxcore-log: 
,07-27 08:53:55.866   754  1008 W ActivityManager: mDVFSHelper.release()
,07-27 08:53:56.096  6285  6348 I jxcore-log: Unit Test app is loaded
07-27 08:53:56.096  6285  6348 I jxcore-log: 
,07-27 08:53:56.106  6285  6348 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 08:53:56.106  6285  6348 I jxcore-log: 
,07-27 08:53:56.106  6285  6285 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-27 08:53:56.116  6285  6348 I WifiManager: packageName : com.test.thalitest
,07-27 08:53:56.116   754  1318 D SecContentProvider: uri = 18 selection = isWifiEnabled
,07-27 08:53:56.116   754  1318 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-27 08:53:56.116   754  1318 D SecContentProvider2: mCursor = null
,07-27 08:53:56.116   754  1318 D WifiService: setWifiEnabled: true pid=6285, uid=10079
,07-27 08:53:56.116   754  1318 W ActivityManager: Permission Denial: getCurrentUser() from pid=6285, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 08:53:56.116   754  1318 W WifiService: Failed getting userId using ActivityManagerNative
07-27 08:53:56.116   754  1318 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6285, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 08:53:56.116   754  1318 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-27 08:53:56.116   754  1318 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-27 08:53:56.116   754  1318 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-27 08:53:56.116   754  1318 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-27 08:53:56.116   754  1318 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-27 08:53:56.116   754  1318 D SettingsProvider: name = wifi_on
,07-27 08:53:56.126   754  1446 I WifiService: disconnect: pid=6285, uid=10079
07-27 08:53:56.126   754  1146 E WifiHW  : ##################### set firmware type 0 #####################
,07-27 08:53:56.126   301  1051 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
07-27 08:53:56.126  6285  6348 D BluetoothAdapter: enable()
07-27 08:53:56.126   301  1051 I WifiHW  : module is semco
07-27 08:53:56.126   301  1051 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-27 08:53:56.126   301  1051 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-27 08:53:56.126   301  1051 E WifiHW  : TEMP_FAILURE_RETRY complete
07-27 08:53:56.126   301  1051 D SoftapController: Softap fwReload - Ok
,07-27 08:53:56.126   754  1291 W ActivityManager: Permission Denial: getCurrentUser() from pid=6285, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-27 08:53:56.126   754  1291 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-27 08:53:56.126   754  1291 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6285, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 08:53:56.126   754  1291 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-27 08:53:56.126   754  1291 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-27 08:53:56.126   754  1291 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-27 08:53:56.126   754  1291 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-27 08:53:56.126   754  1291 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
07-27 08:53:56.126   754  1291 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 08:53:56.126   754  1291 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 08:53:56.126   754  1291 D SettingsProvider: name = bluetooth_on
,07-27 08:53:56.126   301  1051 D CommandListener: Setting iface cfg
07-27 08:53:56.126   301  1051 D CommandListener: Trying to bring down wlan0
,07-27 08:53:56.126   754  1056 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-27 08:53:56.126   754  1056 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 08:53:56.126   301  1051 D CommandListener: Clearing all IP addresses on wlan0
,07-27 08:53:56.136  6285  6348 I jxcore-log: My device name is: samsung-SM-N9005
07-27 08:53:56.136  6285  6348 I jxcore-log: 
,07-27 08:53:56.136   754  1056 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-27 08:53:56.136  2926  2979 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
07-27 08:53:56.136  2926  2979 D BluetoothAdapterProperties: Setting state to 11
07-27 08:53:56.136  2926  2979 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-27 08:53:56.136  2926  2979 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 08:53:56.136  2926  2979 D BluetoothAdapterService: updateAdapterState state is 11
,07-27 08:53:56.136  2926  2979 D BluetoothAdapterService: Autoconnection is available 
07-27 08:53:56.136  2926  2979 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
07-27 08:53:56.136  2926  2979 D BtConfig.SecureMode: isSecureModeOn:false
07-27 08:53:56.136  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-27 08:53:56.136  2926  2979 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
07-27 08:53:56.136  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-27 08:53:56.136  2926  2979 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-27 08:53:56.136  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-27 08:53:56.136  2926  2979 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,07-27 08:53:56.136  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 08:53:56.146  2926  2979 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
07-27 08:53:56.146  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-27 08:53:56.146  2926  2979 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-27 08:53:56.146  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-27 08:53:56.146  2926  2979 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-27 08:53:56.146  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-27 08:53:56.146  2926  2979 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-27 08:53:56.146  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 08:53:56.146  2926  2979 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,07-27 08:53:56.146  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:53:56.146   754  1146 E WifiHW  : supplicant_name : p2p_supplicant
07-27 08:53:56.146  2926  2979 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:53:56.146  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-27 08:53:56.146  2926  2979 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-27 08:53:56.146  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-27 08:53:56.146  2926  2979 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
07-27 08:53:56.146  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-27 08:53:56.146  2926  2979 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
07-27 08:53:56.146  2926  2979 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
,07-27 08:53:56.146  2926  2979 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
07-27 08:53:56.146  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-27 08:53:56.146  2926  2979 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-27 08:53:56.146   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:53:56.156   754  1008 D ActivityManager: startProcessLocked calleePkgName: tv.peel.samsung.app, hostingType: broadcast
,07-27 08:53:56.156  4000  4000 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:53:56.156   754  1150 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-27 08:53:56.156  6285  6285 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 08:53:56.166   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:56.166   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:56.166   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:56.166   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:56.166  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-27 08:53:56.166  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 08:53:56.166  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-27 08:53:56.166  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 08:53:56.166  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,07-27 08:53:56.166  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 08:53:56.166  1197  1197 D HotspotTile: onReceive : 2, 0
07-27 08:53:56.176  1197  1618 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-27 08:53:56.176   754  1146 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-27 08:53:56.196  6402  6402 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-27 08:53:56.196  6402  6402 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-27 08:53:56.206  6402  6402 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 08:53:56.206  6402  6402 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 08:53:56.206   365   365 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6402
07-27 08:53:56.206   365   365 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
07-27 08:53:56.206  6402  6402 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 08:53:56.206  6402  6402 I wpa_supplicant: ssSupport state is = 1
,07-27 08:53:56.206  6402  6402 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-27 08:53:56.206  6402  6402 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-27 08:53:56.206   365   365 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6402
07-27 08:53:56.206   365   365 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,07-27 08:53:56.216  1197  1197 D QSpanel : label top:23
,07-27 08:53:56.226   754  1008 I ActivityManager: Start proc tv.peel.samsung.app for broadcast tv.peel.samsung.app/com.peel.receiver.ConnectivityActionReceiver: pid=6403 uid=10152 gids={50152, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-27 08:53:56.226   754  1639 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 08:53:56.226   754  1639 D ActivityManager: caller:android.app.ApplicationThreadProxy@29eee76d, r.packageName :com.android.bluetooth
07-27 08:53:56.226  6403  6403 E Zygote  : MountEmulatedStorage()
07-27 08:53:56.226  6403  6403 E Zygote  : v2
07-27 08:53:56.226  6403  6403 I libpersona: KNOX_SDCARD checking this for 10152
07-27 08:53:56.226  6403  6403 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:56.226  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-27 08:53:56.226  2926  2979 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
07-27 08:53:56.226  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-27 08:53:56.226  2926  2979 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-27 08:53:56.226   754   754 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 08:53:56.226   754   754 I InputMethodManagerService: [BT Setting State] State =11
,07-27 08:53:56.226  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-27 08:53:56.226  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-27 08:53:56.226  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-27 08:53:56.226  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-27 08:53:56.226  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-27 08:53:56.226  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-27 08:53:56.226  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-27 08:53:56.226  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-27 08:53:56.226  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-27 08:53:56.246   754  1558 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 08:53:56.246  6403  6403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:53:56.246  6403  6403 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:53:56.246   754  1558 D ActivityManager: caller:android.app.ApplicationThreadProxy@b0a9433, r.packageName :com.android.bluetooth
,07-27 08:53:56.246  6403  6403 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-27 08:53:56.246  1751  1751 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 08:53:56.256  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-27 08:53:56.266  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 08:53:56.266  2926  2979 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,07-27 08:53:56.266  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 08:53:56.266  2926  2979 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,07-27 08:53:56.266  2926  2926 D HeadsetService: Received start request. Starting profile...
,07-27 08:53:56.266  2926  2926 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-27 08:53:56.266  2926  2926 D HeadsetStateMachine: make
,07-27 08:53:56.276   754  1446 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 08:53:56.276   754  1446 D ActivityManager: caller:android.app.ApplicationThreadProxy@269f8d69, r.packageName :com.android.bluetooth
,07-27 08:53:56.276  2926  2979 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,07-27 08:53:56.276  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-27 08:53:56.276   754  1470 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-27 08:53:56.276  2926  2979 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-27 08:53:56.276   754  1528 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 08:53:56.276   754  1528 D ActivityManager: caller:android.app.ApplicationThreadProxy@34d0408f, r.packageName :com.android.bluetooth
07-27 08:53:56.276   754   783 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-27 08:53:56.276  2926  2979 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
07-27 08:53:56.276  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-27 08:53:56.276  2926  2979 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,07-27 08:53:56.276   754  1528 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 08:53:56.276   754  1528 D ActivityManager: caller:android.app.ApplicationThreadProxy@3c9a9725, r.packageName :com.android.bluetooth
07-27 08:53:56.276  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-27 08:53:56.286  2926  2979 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
07-27 08:53:56.286  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 08:53:56.286  2926  2979 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-27 08:53:56.286   754  1703 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 08:53:56.286   754  1703 D ActivityManager: caller:android.app.ApplicationThreadProxy@1d9a56ab, r.packageName :com.android.bluetooth
,07-27 08:53:56.286  2926  2926 E HeadsetStateMachine: # of Max HF connection is 2
,07-27 08:53:56.286  2926  2979 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
07-27 08:53:56.286  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 08:53:56.286  2926  2979 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,07-27 08:53:56.286   754  1291 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 08:53:56.286   754  1291 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e8280a1, r.packageName :com.android.bluetooth
,07-27 08:53:56.286  2926  2979 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:53:56.286  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:53:56.286  2926  2979 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:53:56.286  2926  2979 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-27 08:53:56.286  1197  1618 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-27 08:53:56.286  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-27 08:53:56.286  2926  2979 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-27 08:53:56.286  2926  2979 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
07-27 08:53:56.286  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-27 08:53:56.286  2926  2979 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-27 08:53:56.286  2926  2979 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
07-27 08:53:56.286  2926  2979 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-27 08:53:56.286  2926  2979 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-27 08:53:56.286  2926  2979 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-27 08:53:56.286  6403  6403 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:53:56.286  6403  6403 D ActivityThread: Added TimaKeyStore provider
07-27 08:53:56.286   754  1470 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
07-27 08:53:56.296  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-27 08:53:56.296  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-27 08:53:56.296  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-27 08:53:56.296  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-27 08:53:56.296  1197  1197 D QSpanel : label top:23
07-27 08:53:56.296  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-27 08:53:56.296  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-27 08:53:56.296  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-27 08:53:56.296  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-27 08:53:56.296  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-27 08:53:56.296  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
07-27 08:53:56.306   754  1221 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
07-27 08:53:56.306  2926  2926 I bluedroid: get_profile_interface handsfree
07-27 08:53:56.306  6403  6403 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
07-27 08:53:56.316  2926  2926 I DualScoManager: Instantiating Dual Sco Manager
07-27 08:53:56.316  2926  2926 I DualScoManager: Set HeadsetServiceHelper
07-27 08:53:56.316  2926  2926 D BluetoothAtMessage: createCMTIContentObservers
07-27 08:53:56.316   754  1446 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
07-27 08:53:56.316   754  1446 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:53:56.316   754  1446 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:53:56.316   754  1446 D SettingsProvider: selectionArgs: false
07-27 08:53:56.316   754  1446 D SettingsProvider: selectionArgs: 1002
07-27 08:53:56.316   754  1446 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 08:53:56.316   754  1446 D SettingsProvider: ret = -1
,07-27 08:53:56.316   754  1446 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
07-27 08:53:56.316  2926  6430 D HeadsetStateMachine: Enter Disconnected: -2
07-27 08:53:56.326  2926  2926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ca4415a
07-27 08:53:56.326  2926  6430 E HeadsetStateMachine: set to mRemoteBrsf = 0
07-27 08:53:56.326   754   754 D BluetoothA2dp: Proxy object connected
07-27 08:53:56.326  2926  6430 D HeadsetStateMachine: map size, before remove : 0
07-27 08:53:56.326  2926  6430 D HeadsetStateMachine: map size, after remove: 0
07-27 08:53:56.326  2926  6430 D HeadsetStateMachine: mNextConnectingDevice : null
07-27 08:53:56.326  2926  2926 D A2dpService: Received start request. Starting profile...
07-27 08:53:56.326  3133  3133 D BluetoothA2dp: Proxy object connected
07-27 08:53:56.326  2926  2926 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 08:53:56.326  2926  2926 V Avrcp   : make
07-27 08:53:56.326  2926  2926 V Avrcp   : Avrcp
07-27 08:53:56.326  2926  2926 I bluedroid: get_profile_interface avrcp
07-27 08:53:56.326  2926  2926 V Avrcp   : start
07-27 08:53:56.336  2926  2926 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-27 08:53:56.336  2926  2926 V Avrcp   : ++registerMediaPlayers++
07-27 08:53:56.336  2926  2926 I Avrcp   : No of Audio players :: 2
07-27 08:53:56.336  2926  2926 I Avrcp   : App Package name is com.google.android.music
07-27 08:53:56.336  2926  2926 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
07-27 08:53:56.346  2926  2926 I Avrcp   : App pkg name is Google Play Music
07-27 08:53:56.346  2926  2926 I Avrcp   : Name::Google Play Music
07-27 08:53:56.346  2926  2926 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-27 08:53:56.346  2926  2926 I Avrcp   : App Package name is com.sec.android.app.music
07-27 08:53:56.346  2926  2926 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
07-27 08:53:56.346  2926  2926 I Avrcp   : App pkg name is Music
07-27 08:53:56.346  2926  2926 I Avrcp   : Name::Music
07-27 08:53:56.346  2926  2926 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-27 08:53:56.346  2926  2926 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
07-27 08:53:56.356  2926  2926 I Avrcp   : No of Video players :: 1
07-27 08:53:56.356  2926  2926 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
07-27 08:53:56.356  2926  2926 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
07-27 08:53:56.356  2926  2926 I Avrcp   : Video App pkg name is Video Player
07-27 08:53:56.356  2926  2926 I Avrcp   : Name::Video Player
07-27 08:53:56.356  2926  2926 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-27 08:53:56.356  2926  2926 I Avrcp   : Add tempPlayer
07-27 08:53:56.356  2926  2926 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-27 08:53:56.356  2926  2926 I Avrcp   : Total no of players: 4
07-27 08:53:56.356  2926  2926 V Avrcp   : swapping the samsung player with 1st player
07-27 08:53:56.356  2926  2926 I Avrcp   :  Updating now playing list upon AVRCP Start
07-27 08:53:56.356  2926  6432 V Avrcp   : handleMessage, msg=207
07-27 08:53:56.356  2926  2926 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 08:53:56.356  2926  2926 D A2dpStateMachine: make
07-27 08:53:56.356  2926  6432 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,07-27 08:53:56.356  2926  2926 I bluedroid: get_profile_interface a2dp
07-27 08:53:56.356  2926  6434 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-27 08:53:56.356  2926  2926 E bt-btif : warning : media task started media_task_refcnt 1 
07-27 08:53:56.366  2926  2926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ca4415a
07-27 08:53:56.366  2926  6433 D A2dpStateMachine: Enter Disconnected: -2
07-27 08:53:56.366  2926  2926 I BluetoothHidServiceJni: classInitNative: succeeds
07-27 08:53:56.366  2926  2926 D HidService: Received start request. Starting profile...
07-27 08:53:56.366  2926  2926 I bluedroid: get_profile_interface hidhost
07-27 08:53:56.366  2926  2926 D HidService: setHidService(): set to: null
07-27 08:53:56.366  2926  6432 D BluetoothMediaBrowser: no now playing list
07-27 08:53:56.366  2926  2926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ca4415a
07-27 08:53:56.366  2926  6432 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
07-27 08:53:56.366  2926  6432 D Avrcp   :  checkNowPlayingList start
07-27 08:53:56.366  2926  2926 I BluetoothHealthServiceJni: classInitNative: succeeds
07-27 08:53:56.366  2926  2926 D HealthService: Received start request. Starting profile...
07-27 08:53:56.366  2926  2926 I bluedroid: get_profile_interface health
07-27 08:53:56.366  2926  2926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ca4415a
07-27 08:53:56.376  2926  2926 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-27 08:53:56.376   754   754 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 08:53:56.376  2926  2926 D PanService: Received start request. Starting profile...
07-27 08:53:56.376  2926  2926 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 08:53:56.376  2926  2926 I bluedroid: get_profile_interface pan
07-27 08:53:56.376  2926  2926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ca4415a
07-27 08:53:56.376  2926  2926 D BluetoothMapService: Received start request. Starting profile...
07-27 08:53:56.386   754  1703 D ActivityManager: getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
07-27 08:53:56.386   754  1703 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:56.386   754  1703 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:56.386   754  1703 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:56.386   754  1703 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:53:56.406  6403  6403 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,07-27 08:53:56.406  6403  6403 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,07-27 08:53:56.426  6438  6438 E Zygote  : MountEmulatedStorage()
,07-27 08:53:56.426  6438  6438 E Zygote  : v2
07-27 08:53:56.426  6438  6438 I libpersona: KNOX_SDCARD checking this for 10186
07-27 08:53:56.426  6438  6438 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:56.426   754  1703 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6438 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,07-27 08:53:56.486  6438  6438 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:53:56.486  6438  6438 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:53:56.486  6438  6438 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:53:56.496  6403  6403 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 4392-4398)
,07-27 08:53:56.496  6403  6403 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 08:53:56.506   365   365 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,07-27 08:53:56.516  6438  6438 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:56.516  6438  6438 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:56.526  6438  6438 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-27 08:53:56.536  6438  6438 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-27 08:53:56.536  6438  6438 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 08:53:56.536  6438  6438 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
07-27 08:53:56.536  6438  6438 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 08:53:56.536  6438  6438 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-27 08:53:56.536  6403  6403 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23756f8b}
,07-27 08:53:56.536  6403  6403 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 08:53:56.536  6403  6403 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 08:53:56.566  6403  6403 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-27 08:53:56.566  6403  6403 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 08:53:56.566  6403  6403 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-27 08:53:56.576  6403  6454 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,07-27 08:53:56.586  6403  6403 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-27 08:53:56.586  6403  6403 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50556 len=3379
,07-27 08:53:56.586  6403  6403 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:7638088 len:1165478
,07-27 08:53:56.596  6403  6403 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-27 08:53:56.596  6403  6403 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-27 08:53:56.596  6403  6403 I Adreno-EGL: Build Date: 11/19/14 Wed
07-27 08:53:56.596  6403  6403 I Adreno-EGL: Local Branch: mybranch5813579
07-27 08:53:56.596  6403  6403 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-27 08:53:56.596  6403  6403 I Adreno-EGL: Local Patches: NONE
07-27 08:53:56.596  6403  6403 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-27 08:53:56.636   754  1528 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:53:56.676  2926  2926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ca4415a
,07-27 08:53:56.686   754  1451 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:53:56.686  2926  2926 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,07-27 08:53:56.686  2926  2926 D SapService: Received start request. Starting profile...
07-27 08:53:56.686   754  1580 D RCPManagerService: exchangeData() failure , invalid userId
07-27 08:53:56.686  2926  2926 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-27 08:53:56.686  2926  2926 I bluedroid: get_profile_interface sap
07-27 08:53:56.686  2926  2926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ca4415a
,07-27 08:53:56.686  2926  2926 D HeadsetStateMachine: Try to query the phonestate on bind
,07-27 08:53:56.686  1408  1429 I Telecom : BluetoothPhoneService: queryPhoneState
,07-27 08:53:56.686  1408  1408 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-27 08:53:56.686   754  1593 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,07-27 08:53:56.696   754  1593 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:56.696   754  1593 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:56.696   754  1593 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:56.696   754  1593 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:53:56.696  1408  1408 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,07-27 08:53:56.696  1408  1408 W BluetoothHeadset: Proxy not attached to service
,07-27 08:53:56.706  2926  2926 D HeadsetStateMachine: Proxy object connected
,07-27 08:53:56.706  2926  2926 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
07-27 08:53:56.706  2926  2926 D HeadsetPhoneState: sendDeviceDataStateChanged
,07-27 08:53:56.706  2926  2926 D HeadsetPhoneState: Signal level : previous=0 curr=1
07-27 08:53:56.706  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 08:53:56.706  2926  2926 E BluetoothAdapterService(480526682): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
07-27 08:53:56.706  2926  2926 D BluetoothA2dp: Proxy object connected
07-27 08:53:56.706  2926  2926 D BluetoothAdapterService: Bluetooth A2dp source service connected
,07-27 08:53:56.706  2926  2926 E BluetoothAdapterService(480526682): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
07-27 08:53:56.706  2926  6430 D HeadsetStateMachine: Disconnected process message: 11
07-27 08:53:56.706  2926  6430 D HeadsetStateMachine: Disconnected process message: 18
07-27 08:53:56.706  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:53:56.706  2926  6430 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 08:53:56.706  2926  6430 D HeadsetStateMachine: Disconnected process message: 11
,07-27 08:53:56.726   754   783 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:53:56.726  6478  6478 E Zygote  : MountEmulatedStorage()
07-27 08:53:56.736  6478  6478 I libpersona: KNOX_SDCARD checking this for 10092
07-27 08:53:56.736  6478  6478 E Zygote  : v2
07-27 08:53:56.736  6478  6478 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:56.736   754  1593 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6478 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,07-27 08:53:56.746  6403  6466 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-27 08:53:56.766  6402  6402 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-27 08:53:56.786  6478  6478 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:53:56.786  6478  6478 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 08:53:56.786  6478  6478 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-27 08:53:56.786  2926  2926 E BluetoothAdapterService(480526682): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-27 08:53:56.786  2926  2926 E BluetoothAdapterService(480526682): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-27 08:53:56.786  2926  2926 E BluetoothAdapterService(480526682): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-27 08:53:56.796   754  1221 I ActivityManager: Killing 5500:com.sec.providers.settingsearch/u0a191 (adj 15): emptyCount ##41
,07-27 08:53:56.796  6402  6402 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 08:53:56.796  6402  6402 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 08:53:56.796   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6402
07-27 08:53:56.796   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-27 08:53:56.796  6402  6402 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 08:53:56.796  6402  6402 I wpa_supplicant: ssSupport state is = 1
07-27 08:53:56.796  6402  6402 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 08:53:56.796  6402  6402 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 08:53:56.796  6402  6402 E wpa_supplicant: SIM READ ERROR
07-27 08:53:56.796  6402  6402 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 08:53:56.796  6402  6402 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 08:53:56.796  6402  6402 E wpa_supplicant: SIM READ ERROR
07-27 08:53:56.796  6402  6402 I wpa_supplicant: Blacklist: Clear (all) 
07-27 08:53:56.796  6402  6402 I wpa_supplicant: wpa_default_ap_write_once
07-27 08:53:56.796  6402  6402 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-27 08:53:56.796  6402  6402 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 08:53:56.796  6402  6402 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-27 08:53:56.796  6402  6402 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 08:53:56.796  6402  6402 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 08:53:56.796  6402  6402 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 08:53:56.796  2926  2926 E BluetoothAdapterService(480526682): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
07-27 08:53:56.796  2926  2926 E BluetoothAdapterService(480526682): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,07-27 08:53:56.796  2926  2979 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-27 08:53:56.796  2926  2979 I bluedroid: enable
07-27 08:53:56.806  2926  2982 E bt-btif : Calling BTA_HhEnable
07-27 08:53:56.806  2926  2982 E bt-btif : BTM_SEC_REG[3]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
07-27 08:53:56.806  2926  2982 E bt-btif :                : sec): asser, service name [] (up to 21 chars saved)
07-27 08:53:56.806  2926  2982 E bt-btif : BTM_SEC_REG[4]: id 38, is_orig 1, psm 0x0019, proto_id 7
07-27 08:53:56.806  2926  2982 D BluetoothAdapterProperties: Address is:B0:C5:59:2A:28:2D
07-27 08:53:56.806  2926  2982 E BluetoothServiceJni: populateRssiValuesNative
07-27 08:53:56.806  2926  2982 I bluedroid: getModelRssiValues
07-27 08:53:56.806  2926  2982 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-27 08:53:56.806  2926  2982 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
07-27 08:53:56.806  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.806  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:56.806  2926  2982 D BluetoothAdapterProperties: Name is: Galaxy Note3
07-27 08:53:56.806   754   754 D SettingsProvider: name = bluetooth_name
07-27 08:53:56.806  2926  2982 D BluetoothAdapterProperties: Scan Mode:20
07-27 08:53:56.806  2926  2982 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 08:53:56.806  2926  2982 D BluetoothAdapterProperties: LE Address is:F0:8B:B2:54:50:5A
07-27 08:53:56.806  2926  2982 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
07-27 08:53:56.806  2926  2982 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
07-27 08:53:56.806  2926  2982 E bt-btif : btif_sock_init: !radio_req && !rfc_init
07-27 08:53:56.806  2926  2982 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
07-27 08:53:56.806  2926  2985 D bt_upio : proc btwrite assertion
07-27 08:53:56.806  2926  2982 D IOP_DB_BT: db_open: db_open : handle 3026272272l, read 14063 bytes onto local cache
07-27 08:53:56.806  2926  2982 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
07-27 08:53:56.816  2926  2982 D IOP_DB_BT: db_query: result 1
07-27 08:53:56.816  2926  2982 I         : iop_db_open: iop_db_open status 0
07-27 08:53:56.816  2926  2982 D bte_conf: Device ID record 1 : primary
07-27 08:53:56.816  2926  2982 D bte_conf:   vendorId            = 0075
07-27 08:53:56.816  2926  2982 D bte_conf:   vendorIdSource      = 0001
07-27 08:53:56.816  2926  2982 D bte_conf:   product             = 0100
07-27 08:53:56.816  2926  2982 D bte_conf:   version             = 0200
07-27 08:53:56.816  2926  2982 D bte_conf:   clientExecutableURL = 
07-27 08:53:56.816  2926  2982 D bte_conf:   serviceDescription  = 
07-27 08:53:56.816  2926  2982 D bte_conf:   documentationURL    = 
07-27 08:53:56.816  2926  2982 D bte_conf: bte_load_did_conf no section named DID2.
07-27 08:53:56.816  6285  6285 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 08:53:56.816  2926  2979 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-27 08:53:56.816  2926  2979 D BluetoothAdapterProperties: ScanMode =  20
07-27 08:53:56.816  2926  2979 D BluetoothAdapterProperties: State =  11
07-27 08:53:56.816  2926  2982 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-27 08:53:56.816  2926  2982 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-27 08:53:56.816   754  1639 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
07-27 08:53:56.816  2926  2979 D BluetoothAdapterProperties: Setting state to 12
07-27 08:53:56.816  2926  2979 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-27 08:53:56.816  2926  2982 D BluetoothAdapterProperties: Scan Mode:21
07-27 08:53:56.816  2926  2982 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 08:53:56.816   754  1528 D SettingsProvider: name = bluetooth_a2dp_sink_mode
07-27 08:53:56.816   754  1528 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:53:56.816   754  1528 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:53:56.816   754  1528 D SettingsProvider: selectionArgs: false
07-27 08:53:56.816   754  1528 D SettingsProvider: selectionArgs: 1002
07-27 08:53:56.816   754  1528 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 08:53:56.816   754  1528 D SettingsProvider: ret = -1
07-27 08:53:56.816  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.816  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:56.816  6285  6285 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-27 08:53:56.816  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.816  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:56.826  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.826  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:56.826   754  1528 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
07-27 08:53:56.826  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.826  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:56.826  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.826  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:56.826  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.826  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:56.836  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.836  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:56.836  2926  2979 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 08:53:56.836  2926  2979 D BluetoothAdapterService: updateAdapterState state is 12
07-27 08:53:56.836   754   783 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 08:53:56.836   754   783 D ActivityManager: caller:android.app.ApplicationThreadProxy@2eb27b7c, r.packageName :com.android.bluetooth
07-27 08:53:56.836  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.836  2926  2985 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:56.836  6478  6478 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:56.836  6478  6478 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:56.836  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.836  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:56.846  2926  2979 D BluetoothAdapterService: Autoconnection is available 
07-27 08:53:56.846  2926  2979 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-27 08:53:56.846  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.846  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:56.846  6285  6285 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:53:56.846  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:56.846  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 08:53:56.846  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:53:56.846  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:53:56.846  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:53:56.846  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:53:56.846  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:53:56.846  2926  2979 D BluetoothAdapterService: starting service from this receiver
07-27 08:53:56.846   754  1291 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 08:53:56.846  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.846  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:56.846   754  1291 D ActivityManager: caller:android.app.ApplicationThreadProxy@35d1545a, r.packageName :com.android.bluetooth
07-27 08:53:56.846  6285  6285 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 08:53:56.846  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.846  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:56.846  2926  2985 D bt_vendor: op for 7
,07-27 08:53:56.846  2926  2985 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:56.846  2926  2979 I BluetoothAdapterState: Entering On State from state = 11
,07-27 08:53:56.846  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.846  2926  2985 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:56.846  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.846  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:56.846   754  1056 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 08:53:56.856  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.856  2926  2985 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:56.856   754  1291 I ActivityManager: Killing 5520:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 15): emptyCount ##41
07-27 08:53:56.856  2926  2926 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-27 08:53:56.856  2926  2985 D bt_vendor: op for 7
,07-27 08:53:56.856  2926  2985 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:56.856  2926  2985 D bt_vendor: op for 7
,07-27 08:53:56.856  2926  2985 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:56.856  2926  2985 D bt_vendor: op for 7
,07-27 08:53:56.856  2926  2985 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:56.856  2926  2985 D bt_vendor: op for 7
,07-27 08:53:56.856  2926  2985 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:56.866  2926  2985 D bt_vendor: op for 7
,07-27 08:53:56.866  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:56.866  3133  3144 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 08:53:56.866  2926  2985 D bt_vendor: op for 7
,07-27 08:53:56.866  2926  2985 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:56.866  2926  2985 D bt_vendor: op for 7
,07-27 08:53:56.866  2926  2985 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:56.866  2926  2985 D bt_vendor: op for 7
,07-27 08:53:56.866  2926  2985 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:56.866  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.866  2926  2985 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:56.866  2926  6428 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 08:53:56.876   754  1056 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-27 08:53:56.876   754   754 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 08:53:56.876   754   754 I InputMethodManagerService: [BT Setting State] State =12
,07-27 08:53:56.876   754   754 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-27 08:53:56.876  1197  1197 D BluetoothTile:  onBluetoothStateChange:
,07-27 08:53:56.886  1408  1408 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@9582286, true
,07-27 08:53:56.886  1408  1408 D BluetoothHeadset: registerMessageListener
07-27 08:53:56.886  6478  6478 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,07-27 08:53:56.886  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-27 08:53:56.886  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 08:53:56.886  2926  2937 D HeadsetService: registerMessageListener
,07-27 08:53:56.886  2926  2926 I BluetoothPbapService: Handler(): got msg=1
,07-27 08:53:56.886  2926  2937 D HeadsetService: registerMessageListener
07-27 08:53:56.886  2926  6430 D HeadsetStateMachine: Disconnected process message: 70
,07-27 08:53:56.886   754   783 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
07-27 08:53:56.886  1408  1408 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-27 08:53:56.886  1408  1408 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
07-27 08:53:56.886  2926  6430 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3fef0037
,07-27 08:53:56.886   754  1639 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-27 08:53:56.896  2926  6430 D HeadsetStateMachine: Disconnected process message: 9
,07-27 08:53:56.896  2926  6430 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,07-27 08:53:56.896  2926  6496 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-27 08:53:56.896   319  2313 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
07-27 08:53:56.896   319  2313 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-27 08:53:56.896   319  2313 V voice   : voice_set_parameters: exit with code(-2)
07-27 08:53:56.896   319  2313 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-27 08:53:56.896   319  2313 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-27 08:53:56.896   319  2313 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-27 08:53:56.896   319  2313 V audio_hw_primary: adev_set_parameters: exit
,07-27 08:53:56.896  2926  6430 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,07-27 08:53:56.896  2926  6497 D BluetoothMapMasInstance: set MAP SDP message type : 1
,07-27 08:53:56.906  1751  1751 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 08:53:56.906   754  1580 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,07-27 08:53:56.906  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-27 08:53:56.906  2926  6496 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:53:56.906   754  1056 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
07-27 08:53:56.906  2926  6497 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:53:56.906  1197  1618 D BluetoothTile:  handleUpdatestate:false name:null
,07-27 08:53:56.906  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.906  1197  1618 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-27 08:53:56.906  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:56.906  2926  6496 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
07-27 08:53:56.906  2926  6496 D BluetoothSocket: bindListen(), new LocalSocket 
07-27 08:53:56.906  2926  6496 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-27 08:53:56.906  2926  6496 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c5e09a4
,07-27 08:53:56.906  2926  6496 D BluetoothSocket: channel: 19
07-27 08:53:56.906  2926  6496 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-27 08:53:56.906  2926  6497 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
07-27 08:53:56.906  2926  2985 D bt_vendor: op for 7
07-27 08:53:56.906  2926  2985 D bt_upio : BT_WAKE is asserted already
,07-27 08:53:56.906  2926  6497 D BluetoothSocket: bindListen(), new LocalSocket 
07-27 08:53:56.906  2926  6497 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-27 08:53:56.906  2926  6497 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@23d2430d
07-27 08:53:56.906  2926  6497 D BluetoothSocket: channel: 5
,07-27 08:53:56.916  6478  6478 D BadgeProvider: onCreate
,07-27 08:53:56.916  6478  6478 D BadgeProvider: DatabaseHelper
,07-27 08:53:56.926  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-27 08:53:56.926  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-27 08:53:56.926  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-27 08:53:56.926  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-27 08:53:56.926  1197  1197 D QSpanel : label top:23
07-27 08:53:56.926  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-27 08:53:56.926  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-27 08:53:56.926  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-27 08:53:56.926  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-27 08:53:56.926  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-27 08:53:56.926  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-27 08:53:56.926  6403  6403 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 08:53:56.936  6478  6489 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,07-27 08:53:56.936  6403  6403 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-27 08:53:56.946  1456  1456 D Launcher.Model: reloadBadges entered.
07-27 08:53:56.946  6478  6489 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
07-27 08:53:56.946  6478  6489 D BadgeProvider: sendNotify, [notify] : null
,07-27 08:53:56.946  6478  6489 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
07-27 08:53:56.946  6478  6489 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-27 08:53:56.946  6478  6489 D BadgeProvider: update, [UpdateCount] : 1
,07-27 08:53:57.066  4973  4973 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 08:53:57.086   754  1528 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:57.086  6355  6355 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 08:53:57.086  6355  6355 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 08:53:57.086  6355  6355 D SecurityLogAgent: StateMachine : Current State = 1
,07-27 08:53:57.086  6355  6355 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 08:53:57.096   754  1318 I ActivityManager: Killing 4616:com.google.android.gm/u0a128 (adj 15): emptyCount ##41
,07-27 08:53:57.106  1562  1562 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 08:53:57.116  4000  4000 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 08:53:57.116   754  1470 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,07-27 08:53:57.116   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:57.116   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:57.116   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:57.116   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:53:57.156   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:53:57.166   754  1470 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6511 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,07-27 08:53:57.166  6511  6511 E Zygote  : MountEmulatedStorage()
07-27 08:53:57.166  6511  6511 E Zygote  : v2
07-27 08:53:57.166  6511  6511 I libpersona: KNOX_SDCARD checking this for 10140
07-27 08:53:57.166  6511  6511 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:57.166   754   783 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-27 08:53:57.206  6511  6511 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:53:57.206  6511  6511 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:53:57.206  6511  6511 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-27 08:53:57.226  6511  6511 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:57.226  6511  6511 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:57.236  6511  6511 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
,07-27 08:53:57.336   308   308 E SMD     : DCD ON
,07-27 08:53:57.476   754  1149 E Tethering: No numeric data
,07-27 08:53:57.476   754  1149 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-27 08:53:57.476   754  1143 D NtpTrustedTime: forceRefresh() from cache miss
,07-27 08:53:57.476  1197  1197 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-27 08:53:57.476  1197  1197 D HotspotTile: updateTetherState():false, false
,07-27 08:53:57.476   754  1143 D NtpTrustedTime: forceRefresh Fail.
,07-27 08:53:57.476   754  1143 V NetworkStats: performPollLocked(flags=0x1)
,07-27 08:53:57.476   754  1143 D NetworkStatsFactory: UpdateStatsForKnox
07-27 08:53:57.476   754  1143 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:57.486   754  1143 V NetworkStats: performPollLocked() took 3ms
,07-27 08:53:57.486   754  1144 D NtpTrustedTime: forceRefresh() from cache miss
,07-27 08:53:57.486   754  1144 D NtpTrustedTime: forceRefresh Fail.
07-27 08:53:57.486  6511  6511 D StrictMode: StrictMode policy violation; ~duration=211 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 08:53:57.486  6511  6511 D StrictMode: StrictMode policy violation; ~duration=201 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27, 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 08:53:57.486  6511  6511 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.io.File.exists(File.java:363)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 08:53:57.486  6511  6511 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 08:53:57.486  6511  6511 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 08:53:57.486  6511  6511 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.r.e.b(PG:170)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 08:53:57.486  6511  6511 D StrictMode: StrictMode policy violation; ~duration=148 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.r.k.b(PG:14147)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.r.k.c(PG:583)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.r.e.b(PG:170)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 08:53:57.486  6511  6511 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.io.File.exists(File.java:363)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 08:53:57.486  6511  6511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 08:53:57.486   754  1528 I ActivityManager: Killing 5256:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 15): emptyCount ##41
07-27 08:53:57.506  4000  4000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-27 08:53:57.506   754  1593 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-27 08:53:57.506   754  1593 D ActivityManager: caller:android.app.ApplicationThreadProxy@2a14be47, r.packageName :com.android.settings
07-27 08:53:57.506  1562  1562 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 08:53:57.516  6511  6528 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-27 08:53:57.526  6402  6402 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
07-27 08:53:57.536  4000  4000 D LocalBluetoothProfileManager: Adding local A2DP profile
07-27 08:53:57.536   754  1593 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
07-27 08:53:57.536  4000  4000 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-27 08:53:57.536  4000  4000 E BluetoothHeadset: BTStateChangeCB is registed
07-27 08:53:57.536   754  1446 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-27 08:53:57.546  4000  4000 E BluetoothHeadset: BluetoothHeadset service is binded
07-27 08:53:57.546  4000  4000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
07-27 08:53:57.546   754   783 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
07-27 08:53:57.546  4000  4000 D Bluetoothsap: bindService called to Bluetooth SAP Service
07-27 08:53:57.556  6402  6402 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
07-27 08:53:57.556  6402  6402 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 08:53:57.556  6402  6402 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 08:53:57.556   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6402
07-27 08:53:57.556   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-27 08:53:57.556  6402  6402 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 08:53:57.556  6402  6402 I wpa_supplicant: ssSupport state is = 1
,07-27 08:53:57.556  6402  6402 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 08:53:57.556  6402  6402 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 08:53:57.566   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6402
07-27 08:53:57.566   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-27 08:53:57.566  6402  6402 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 08:53:57.566  6402  6402 I wpa_supplicant: ssSupport state is = 1
07-27 08:53:57.566  6402  6402 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,07-27 08:53:57.566  6402  6402 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 08:53:57.566  6402  6402 E wpa_supplicant: SIM READ ERROR
07-27 08:53:57.566  6402  6402 I wpa_supplicant: wpa_default_ap_write_once
07-27 08:53:57.566  6402  6402 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-27 08:53:57.566  6402  6402 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 08:53:57.586   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:53:57.606  6402  6402 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
07-27 08:53:57.606  6402  6402 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-27 08:53:57.636   754  1703 I art     : Explicit concurrent mark sweep GC freed 27584(1772KB) AllocSpace objects, 13(208KB) LOS objects, 30% free, 35MB/51MB, paused 1.327ms total 88.448ms
,07-27 08:53:57.646   754  1558 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,07-27 08:53:57.646   754  1639 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-27 08:53:57.646  4000  4000 D LocalBluetoothProfileManager: PANU : true
07-27 08:53:57.646  4000  4000 D LocalBluetoothProfileManager: Adding local MAP profile
,07-27 08:53:57.656  4000  4000 D BluetoothMap: Create BluetoothMap proxy object
07-27 08:53:57.656  6402  6402 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
07-27 08:53:57.656  6402  6402 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
07-27 08:53:57.656  6402  6402 I wpa_supplicant: Skip scan - bUseNetwork false
07-27 08:53:57.656   754  1291 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-27 08:53:57.656   754  1146 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-27 08:53:57.656   754  1593 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-27 08:53:57.656   754  1146 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-27 08:53:57.656  6402  6402 I wpa_supplicant: HOTSPOT20_ENABLE called
07-27 08:53:57.656  6402  6402 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 08:53:57.656  6402  6402 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 08:53:57.656  6402  6402 E wpa_supplicant: SIM READ ERROR
07-27 08:53:57.656  4000  4000 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
07-27 08:53:57.656  6402  6402 I wpa_supplicant: Blacklist: Clear (all) 
07-27 08:53:57.656  4000  4000 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-27 08:53:57.666  4000  4000 D DockEventReceiver: finishStartingService: stopping service
,07-27 08:53:57.666  4000  4000 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 08:53:57.666  4000  4000 D BluetoothA2dp: Proxy object connected
07-27 08:53:57.666  4000  4000 D A2dpProfile: Bluetooth service connected
,07-27 08:53:57.666  2926  2926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ca4415a
07-27 08:53:57.666  2926  2926 D BtConfig.SecureMode: isSecureModeOn:false
,07-27 08:53:57.666   754   785 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 08:53:57.666   754   785 D ActivityManager: caller:android.app.ApplicationThreadProxy@308ba4be, r.packageName :com.android.bluetooth
07-27 08:53:57.676  4000  4000 D HeadsetProfile: Bluetooth service connected
,07-27 08:53:57.676  6402  6402 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-27 08:53:57.676  4000  4000 D Bluetoothsap: BluetoothSAP Proxy object connected
,07-27 08:53:57.676  4000  4000 D SapProfile: Bluetooth service connected
07-27 08:53:57.676  4000  4000 D Bluetoothsap: getConnectedDevices()
,07-27 08:53:57.676  6402  6402 I wpa_supplicant: Skip scan - bUseNetwork false
,07-27 08:53:57.676  4000  4000 D BluetoothInputDevice: Proxy object connected
07-27 08:53:57.676   754  1146 D WifiNative-HAL: callSECApiInt - ID [210]
,07-27 08:53:57.676   754  1146 D WifiConfigStore: Loading config and enabling all networks 
,07-27 08:53:57.686   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:53:57.686   754  1150 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-27 08:53:57.686  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-27 08:53:57.686  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 08:53:57.686  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 08:53:57.686  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 08:53:57.686  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 08:53:57.686  4000  4000 D HidProfile: Bluetooth service connected
,07-27 08:53:57.686  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 08:53:57.686  1197  1197 D StatusBar.NetworkController: applyOpen
07-27 08:53:57.686  6285  6285 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:53:57.686  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:57.686  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 08:53:57.686  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:53:57.686  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:53:57.686  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:53:57.686  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:53:57.686  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 08:53:57.686  6285  6285 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 08:53:57.686  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 08:53:57.686  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 08:53:57.686  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 08:53:57.696  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 08:53:57.696  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:53:57.696  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
07-27 08:53:57.696  1197  1618 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-27 08:53:57.696  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:53:57.696  1197  1197 D HotspotTile: onReceive : 3, 0
,07-27 08:53:57.696  4000  4000 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 08:53:57.696  4000  4000 D PanProfile: Bluetooth service connected
,07-27 08:53:57.696   754  1146 E WifiConfigStore: Not a HS20
,07-27 08:53:57.696  4000  4000 D BluetoothMap: Proxy object connected
,07-27 08:53:57.696  4973  4973 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 08:53:57.706  4000  4000 D MapProfile: Bluetooth service connected
07-27 08:53:57.706  4000  4000 D BluetoothPbap: Proxy object connected
,07-27 08:53:57.706  4000  4000 D PbapServerProfile: Bluetooth service connected
,07-27 08:53:57.706   754  1657 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-27 08:53:57.706   754  1528 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:57.706  6355  6355 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-27 08:53:57.706  6355  6355 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 08:53:57.706  6355  6355 D SecurityLogAgent: StateMachine : Current State = 1
07-27 08:53:57.706  6355  6355 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 08:53:57.716   754  1146 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-27 08:53:57.716   754  1146 D WifiNative-HAL: callSECApiInt - ID [65]
,07-27 08:53:57.716  1197  1197 D QSpanel : label top:23
,07-27 08:53:57.716  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-27 08:53:57.716  2926  6544 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:53:57.716  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-27 08:53:57.716  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-27 08:53:57.716  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
,07-27 08:53:57.716  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-27 08:53:57.726  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-27 08:53:57.726  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
,07-27 08:53:57.726  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-27 08:53:57.726  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-27 08:53:57.726  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-27 08:53:57.726  4000  4000 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:53:57.726   754  1146 D WifiNative-HAL: callSECApiBoolean - ID [13]
,07-27 08:53:57.726  2926  6544 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
07-27 08:53:57.726  2926  6544 D BluetoothSocket: bindListen(), new LocalSocket 
07-27 08:53:57.726  2926  6544 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-27 08:53:57.726  2926  6544 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2497bf2f
07-27 08:53:57.726  2926  2985 D bt_vendor: op for 7
07-27 08:53:57.726  2926  2985 D bt_upio : BT_WAKE is asserted already
07-27 08:53:57.726  2926  6544 D BluetoothSocket: channel: 12
07-27 08:53:57.726  2926  6544 I BtOppRfcommListener: Accept thread started.
07-27 08:53:57.726  6402  6402 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-27 08:53:57.726  6402  6402 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-27 08:53:57.726  6402  6402 I wpa_supplicant: reset timer : RESET_TIMER 0
07-27 08:53:57.726  6402  6402 I wpa_supplicant: P2P: Current p2p state = IDLE
07-27 08:53:57.726  6402  6402 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-27 08:53:57.726  6402  6402 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-27 08:53:57.726  6402  6402 I wpa_supplicant: First Scan Start
,07-27 08:53:57.726  6402  6402 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-27 08:53:57.726  4724  4724 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 08:53:57.726   754  1146 D WifiNative-HAL: Setting external_sim to 1
,07-27 08:53:57.736   754  1146 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 08:53:57.736   754  1146 I WifiNative-HAL: startHal
07-27 08:53:57.736   754  1146 E wifi    : getStaticLongField sWifiHalHandle 0x938a686c
07-27 08:53:57.736   754  1146 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x301816
07-27 08:53:57.736   754  1146 I WifiNative-HAL: Could not start hal
,07-27 08:53:57.736   754  1146 E native  : do suspend true
,07-27 08:53:57.736   754  1145 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-27 08:53:57.736   754   754 D WifiScanningService: SCAN_AVAILABLE : 3
07-27 08:53:57.736   754   754 D RttService: SCAN_AVAILABLE : 3
07-27 08:53:57.736   754  1146 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
07-27 08:53:57.736   754  1165 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:53:57.736   754  1165 I WifiNative-HAL: startHal
07-27 08:53:57.736   754  1165 E wifi    : getStaticLongField sWifiHalHandle 0x9b02999c
07-27 08:53:57.736   754  1165 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x40181e
07-27 08:53:57.736   754  1165 I WifiNative-HAL: Could not start hal
07-27 08:53:57.736   754  1165 E WifiScanningService: could not start HAL
07-27 08:53:57.736   301  1051 D CommandListener: Setting iface cfg
07-27 08:53:57.736   301  1051 D CommandListener: Trying to bring up p2p0
07-27 08:53:57.736   754  1166 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:53:57.736   754  1145 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-27 08:53:57.746   754  1145 D WifiP2pService: P2pEnablingState
07-27 08:53:57.746   754  1145 D WifiP2pService: P2pEnablingState{ what=147457 }
,07-27 08:53:57.746   754  1145 D WifiP2pService: P2p socket connection successful
07-27 08:53:57.746   754  1145 D WifiP2pService: P2pEnabledState
,07-27 08:53:57.746   754   754 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-27 08:53:57.746   754  1145 D WifiP2pService: sending p2p connection changed broadcast: IDLE
07-27 08:53:57.746   754  1008 D ActivityManager: startProcessLocked calleePkgName: com.samsung.shareshot, hostingType: broadcast
,07-27 08:53:57.746   754  1057 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-27 08:53:57.746   754  1057 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-27 08:53:57.746   754  1057 D WifiDisplayController: disconnect
07-27 08:53:57.746   754  1057 D WifiDisplayController: updateConnection
07-27 08:53:57.746   754  1057 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,07-27 08:53:57.746   754  1057 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 08:53:57.746   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:57.746   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:57.746   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:57.746   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:53:57.746   754  1146 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-27 08:53:57.746   754  1146 D WifiNative-HAL: callSECStringApiVoid - ID [215]
,07-27 08:53:57.746   754  1146 E WifiNative-HAL: invaild command id : 215
,07-27 08:53:57.776  6402  6402 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-27 08:53:57.786  6546  6546 E Zygote  : MountEmulatedStorage()
,07-27 08:53:57.786  6546  6546 E Zygote  : v2
07-27 08:53:57.786  6546  6546 I libpersona: KNOX_SDCARD checking this for 10192
07-27 08:53:57.786  6546  6546 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:57.796   754  1008 I ActivityManager: Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=6546 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:53:57.806   754  1145 D WifiP2pService: create mNetworkAgent
,07-27 08:53:57.806   754  1057 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:57.806  6402  6402 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-27 08:53:57.816   349   349 I art     : Explicit concurrent mark sweep GC freed 8739(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 420us total 16.165ms
,07-27 08:53:57.816   754  1145 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,07-27 08:53:57.816   754  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 08:53:57.816   754  1146 D SecContentProvider2: mCursor = null
07-27 08:53:57.816   754  1148 D ConnectivityService: Got NetworkAgent Messenger
,07-27 08:53:57.816   754  1148 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,07-27 08:53:57.816   754  1148 E ConnectivityService: updateNetworkInfo()
07-27 08:53:57.816   754  1148 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-27 08:53:57.816   754  1148 D ConnectivityService: NetworkAgent connected
,07-27 08:53:57.816   754  1148 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,07-27 08:53:57.816   754  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 08:53:57.816   754  1146 D SecContentProvider2: mCursor = null
,07-27 08:53:57.826   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 274us total 9.531ms
,07-27 08:53:57.826   754  1145 D WifiNative-HAL: p2pGetDeviceAddress
,07-27 08:53:57.826   754  1145 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:d7:fd:2b
07-27 08:53:57.826   754  1145 D WifiP2pService: DeviceAddress: ea:fd:2b
07-27 08:53:57.826   754  1057 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy Note3
07-27 08:53:57.826   754  1057 D WifiDisplayController:  deviceAddress: ea:50:8b:d7:fd:2b
07-27 08:53:57.826   754  1057 D WifiDisplayController:  primary type: 10-0050F204-5
07-27 08:53:57.826   754  1057 D WifiDisplayController:  secondary type: null
07-27 08:53:57.826   754  1057 D WifiDisplayController:  wps: 0
07-27 08:53:57.826   754  1057 D WifiDisplayController:  grpcapab: 0
07-27 08:53:57.826   754  1057 D WifiDisplayController:  devcapab: 0
07-27 08:53:57.826   754  1057 D WifiDisplayController:  status: 3
07-27 08:53:57.826   754  1057 D WifiDisplayController:  wfdInfo: null
07-27 08:53:57.826   754  1057 D WifiDisplayController:  groupownerAddress: null
07-27 08:53:57.826   754  1057 D WifiDisplayController:  GOdeviceName: null
07-27 08:53:57.826   754  1057 D WifiDisplayController:  interfaceAddress: 
07-27 08:53:57.826   754  1057 D WifiDisplayController:  SConnectInfo : null
07-27 08:53:57.826  6546  6546 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:53:57.826  6546  6546 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 08:53:57.826  6546  6546 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-27 08:53:57.826  1197  1197 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-27 08:53:57.826   754  1481 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-27 08:53:57.826  1197  1197 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-27 08:53:57.836   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 270us total 9.643ms
,07-27 08:53:57.836   754  1145 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-27 08:53:57.846   754  1145 D WifiP2pService: InactiveState
07-27 08:53:57.846   754  1145 D WifiP2pService: InactiveState{ what=143376 }
,07-27 08:53:57.846   754  1145 D WifiP2pService: P2pEnabledState{ what=143376 }
07-27 08:53:57.846  6402  6402 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-27 08:53:57.846   754  1148 E ConnectivityService: updateNetworkInfo()
,07-27 08:53:57.846   754  1145 D WifiP2pService: InactiveState{ what=143376 }
07-27 08:53:57.846   754  1145 D WifiP2pService: P2pEnabledState{ what=143376 }
07-27 08:53:57.846   754  1148 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
,07-27 08:53:57.856  6546  6546 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:57.856  6546  6546 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:57.866  6546  6546 D ResourcesManager: creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,07-27 08:53:57.886  6546  6546 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-27 08:53:57.886   754  1558 I ActivityManager: Killing 5273:com.android.calendar/u0a172 (adj 15): emptyCount ##41
,07-27 08:53:57.896  4000  4000 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 08:53:57.896  4000  4000 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 08:53:57.896   754  1481 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:57.896  4000  4000 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 08:53:57.896   754  1451 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:53:57.896  4000  4000 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
07-27 08:53:57.896  4000  4000 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 08:53:57.896  4000  4000 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-27 08:53:57.906  4000  4089 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 08:53:57.906   754  1470 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,07-27 08:53:57.906   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:57.906   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:57.906   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:57.906   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:53:57.946  6562  6562 E Zygote  : MountEmulatedStorage()
,07-27 08:53:57.946  6562  6562 E Zygote  : v2
07-27 08:53:57.946  6562  6562 I libpersona: KNOX_SDCARD checking this for 10088
07-27 08:53:57.946  6562  6562 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:57.956   754  1470 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6562 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:53:57.986  6562  6562 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:53:57.986  6562  6562 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:53:57.986  6562  6562 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:53:58.006  6562  6562 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:58.006  6562  6562 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:58.016  6562  6562 D ResourcesManager: creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,07-27 08:53:58.026  6562  6562 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-27 08:53:58.036  6546  6546 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 08:53:58.036  6546  6546 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-27 08:53:58.036  6546  6546 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-27 08:53:58.036  6546  6546 D WifiDirectBR: stopServiceTest : false
,07-27 08:53:58.036   754  1593 I ActivityManager: Killing 5337:com.sec.android.app.music:service/u0a49 (adj 15): emptyCount ##41
,07-27 08:53:58.466  6402  6402 I wpa_supplicant: nl80211: Received scan results (19 BSSes)
,07-27 08:53:58.476  6402  6402 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-27 08:53:58.476  6402  6402 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
,07-27 08:53:58.476  6402  6402 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,07-27 08:53:58.476  6402  6402 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,07-27 08:53:58.476   754  1146 I WifiNative-HAL: startHal
07-27 08:53:58.476   754  1146 E wifi    : getStaticLongField sWifiHalHandle 0x938a688c
07-27 08:53:58.476   754  1146 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x501cae
,07-27 08:53:58.476   754  1146 I WifiNative-HAL: Could not start hal
,07-27 08:53:58.486   754  1059 I PowerManagerService: [PWL] Off : 75s ago
07-27 08:53:58.486   754  1059 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
07-27 08:53:58.486   754  1059 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
07-27 08:53:58.486   754  1059 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=1592)
,07-27 08:53:58.506   754  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 08:53:58.506   754  1146 D SecContentProvider2: mCursor = null
,07-27 08:53:58.566  6402  6402 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
07-27 08:53:58.566  6402  6402 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,07-27 08:53:58.566  6402  6402 I wpa_supplicant: Associated with F4.99.3E
07-27 08:53:58.566  6402  6402 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-27 08:53:58.566  6402  6402 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,07-27 08:53:58.576   754  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 08:53:58.576   754  1146 D SecContentProvider2: mCursor = null
,07-27 08:53:58.576   754  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 08:53:58.576   754  1146 D SecContentProvider2: mCursor = null
,07-27 08:53:58.586  6402  6402 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,07-27 08:53:58.586   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:53:58.586  6402  6402 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
07-27 08:53:58.586  6402  6402 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-27 08:53:58.586  6402  6402 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 08:53:58.586  6402  6402 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
07-27 08:53:58.586  6402  6402 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
07-27 08:53:58.586  6402  6402 I wpa_supplicant: Blacklist: Clear (temp) 
07-27 08:53:58.586  6402  6402 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,07-27 08:53:58.596   754  1146 D WifiNative-HAL: callSECApiVoid - ID [50]
,07-27 08:53:58.596   754  1008 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
,07-27 08:53:58.596   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:58.596   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:58.596   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:53:58.596   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:53:58.596  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-27 08:53:58.596  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 08:53:58.606  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 08:53:58.606   754  1146 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,07-27 08:53:58.616   754  1148 D ConnectivityService: Got NetworkAgent Messenger
07-27 08:53:58.616   754  1148 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
07-27 08:53:58.616   754  1148 E ConnectivityService: updateNetworkInfo()
,07-27 08:53:58.616   754  1148 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:58.616   754  1148 D ConnectivityService: NetworkAgent connected
,07-27 08:53:58.616   754  1146 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 08:53:58.626   754  1146 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 08:53:58.626   301  1051 D CommandListener: Setting iface cfg
,07-27 08:53:58.656  6580  6580 E Zygote  : MountEmulatedStorage()
,07-27 08:53:58.656  6580  6580 E Zygote  : v2
07-27 08:53:58.656  6580  6580 I libpersona: KNOX_SDCARD checking this for 10038
07-27 08:53:58.656  6580  6580 I libpersona: KNOX_SDCARD not a persona
,07-27 08:53:58.656   754  1008 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=6580 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,07-27 08:53:58.656   754  1146 E WifiStateMachine: Start Dhcp Watchdog 1
,07-27 08:53:58.656   754  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 08:53:58.656   754  1146 D SecContentProvider2: mCursor = null
,07-27 08:53:58.666   754  1148 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-27 08:53:58.686  6580  6580 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:53:58.686  6580  6580 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 08:53:58.686  6580  6580 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-27 08:53:58.686  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-27 08:53:58.686  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 08:53:58.686  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 08:53:58.706  6580  6580 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:53:58.706  6580  6580 D ActivityThread: Added TimaKeyStore provider
,07-27 08:53:58.726  6580  6580 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,07-27 08:53:58.726  6580  6580 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-27 08:53:58.746   754  1146 E native  : do suspend false
,07-27 08:53:58.756   754  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 08:53:58.756   754  1146 D SecContentProvider2: mCursor = null
,07-27 08:53:58.756   754  1145 D WifiP2pService: InactiveState{ what=143375 }
,07-27 08:53:58.756   754  1145 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 08:53:58.806  2926  3115 D bt_upio : ..proc_btwrite_timeout..
,07-27 08:53:58.856  6580  6580 I VlingoApplication: VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,07-27 08:53:58.976  6598  6598 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 08:53:58.976  6598  6598 I dhcpcd  : version 5.5.6 starting
,07-27 08:53:58.976  6598  6598 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 08:53:58.996  6580  6580 E BluetoothHeadset: BTStateChangeCB is registed
,07-27 08:53:59.006   754  1470 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 08:53:59.006  6580  6580 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 08:53:59.006   754  1446 I ActivityManager: Killing 5374:com.sec.android.app.myfiles/u0a56 (adj 15): emptyCount ##41
,07-27 08:53:59.006  4000  4000 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 08:53:59.006  4000  4000 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 08:53:59.006   754  1221 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:53:59.006  4000  4000 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 08:53:59.006   754  1593 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:59.016  4000  4000 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,07-27 08:53:59.016  4000  4000 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 08:53:59.016  4000  4000 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 08:53:59.016  4000  4089 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 08:53:59.026   754   785 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:59.036  4973  4973 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 08:53:59.046  6580  6580 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,07-27 08:53:59.046  6598  6598 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-27 08:53:59.046  6598  6598 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-27 08:53:59.046  6598  6598 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,07-27 08:53:59.046  6598  6598 I dhcpcd  : bssid match
07-27 08:53:59.046  6598  6598 I dhcpcd  : wlan0: rebinding lease of 192.168.1.119
,07-27 08:53:59.146  6598  6598 I dhcpcd  : wlan0: acknowledged 192.168.1.119 from 192.168.1.1
,07-27 08:53:59.186  6598  6598 I dhcpcd  : wlan0: leased 192.168.1.119 for 172800 seconds
,07-27 08:53:59.186   754  1148 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-27 08:53:59.226  2926  2985 D bt_vendor: op for 7
,07-27 08:53:59.566   754  1146 E native  : do suspend true
,07-27 08:53:59.586   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:53:59.586   754  1145 D WifiP2pService: InactiveState{ what=143375 }
07-27 08:53:59.586   754  1145 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 08:53:59.596   754  1148 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false,
,07-27 08:53:59.596   754  1146 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,07-27 08:53:59.596   754  1146 E WifiStateMachine: VerifyingLinkState enter
,07-27 08:53:59.596  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
07-27 08:53:59.596  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 08:53:59.596  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-27 08:53:59.596   754  1146 D WifiNative-HAL: callSECApiInt - ID [210]
,07-27 08:53:59.606   754  1148 E ConnectivityService: updateNetworkInfo(),
,07-27 08:53:59.606   754  1148 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 08:53:59.606   754  1148 D ConnectivityService: Adding iface wlan0 to network 502
,07-27 08:53:59.606   754  1160 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
07-27 08:53:59.606   754  1160 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 08:53:59.606   754  1160 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-27 08:53:59.606   754  1160 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
07-27 08:53:59.606   754  1160 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 08:53:59.616  4000  4000 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 08:53:59.616  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-27 08:53:59.616   754  1146 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
07-27 08:53:59.616  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 08:53:59.616  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 08:53:59.626  4000  4000 I NearbySettings: MountReceiver.onReceive - Keep current state
07-27 08:53:59.626   754   754 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-27 08:53:59.626   754   754 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-27 08:53:59.626   754   754 I WifiTrafficPoller: mBoosterFLAG : 0
07-27 08:53:59.626   754   754 I WifiTrafficPoller: current booster mode : FullMode
07-27 08:53:59.626   754   754 D WifiNative-HAL: callSECApiVoid - ID [212]
,07-27 08:53:59.626   754  1146 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-27 08:53:59.636  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-27 08:53:59.636  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 08:53:59.636  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 08:53:59.636  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 08:53:59.636  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-27 08:53:59.636  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 08:53:59.636  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 08:53:59.646  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 08:53:59.646  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 08:53:59.646  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 08:53:59.646  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 08:53:59.646  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 08:53:59.646  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 08:53:59.646   754  1580 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:59.656  4973  4973 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 08:53:59.656   754  1148 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 502
,07-27 08:53:59.656   754  1148 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,07-27 08:53:59.656   754  1148 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,07-27 08:53:59.656   754  1148 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-27 08:53:59.656   754  1148 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-27 08:53:59.656   754  1148 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.119
,07-27 08:53:59.656   301  1051 V         : QcRouteController
,07-27 08:53:59.666  4000  4000 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 08:53:59.666  4000  4000 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 08:53:59.666   754  1703 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:53:59.666  4000  4000 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 08:53:59.666   754  1657 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:59.666  4000  4000 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
07-27 08:53:59.666  4000  4000 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 08:53:59.666  4000  4000 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 08:53:59.666  4000  4089 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 08:53:59.676   754  1558 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:59.676   301  1051 V         : QcRouteController
,07-27 08:53:59.686  4973  4973 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 08:53:59.686   301  1051 V         : QcRouteController
,07-27 08:53:59.696   301  1051 V         : QcRouteController
,07-27 08:53:59.706  4000  4000 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 08:53:59.706  4000  4000 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-27 08:53:59.706   754  1221 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,07-27 08:53:59.716   301  1051 V         : QcRouteController
,07-27 08:53:59.726   754   785 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:59.736   301  1051 V         : QcRouteController
,07-27 08:53:59.736  4973  4973 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 08:53:59.746   266   266 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=4, Uoast
,07-27 08:53:59.746   301  1051 V         : QcRouteController
,07-27 08:53:59.746   301  1051 V         : QcRouteController
,07-27 08:53:59.756   754  1451 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=754
,07-27 08:53:59.766   301  1051 V         : QcRouteController
,07-27 08:53:59.786   754  1148 D ConnectivityService: Setting Dns servers for network 502 to [/192.168.1.1]
,07-27 08:53:59.786   754  1148 D ConnectivityService: LTETest block dns file not exists
,07-27 08:53:59.796   754  1148 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
,07-27 08:53:59.796   754  1148 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-27 08:53:59.796   754  1148 D ConnectivityService: calling update connectivity
,07-27 08:53:59.796   754  1056 D EntConnectivity: Not allowed due to - mEnabled false
,07-27 08:53:59.796   754  1148 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-27 08:53:59.796   754  1148 E ConnectivityService: updateNetworkInfo()
07-27 08:53:59.796   754  1148 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-27 08:53:59.796   754  1148 E ConnectivityService: updateNetworkInfo()
07-27 08:53:59.796   754  1148 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:59.796   754  1148 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
07-27 08:53:59.796   754  1148 D ConnectivityService: calling update connectivity
07-27 08:53:59.796   754  1148 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,07-27 08:53:59.796   754  1148 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:59.796   754  6578 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:53:59.796   754  1148 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:53:59.796   754  1148 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:59.796   754  6578 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
07-27 08:53:59.796   754  6578 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 08:53:59.796   754  6578 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,07-27 08:53:59.796   754  1148 D ConnectivityService: currentScore = 0, newScore = 60
07-27 08:53:59.796   754  1148 D ConnectivityService:    accepting network in place of null
,07-27 08:53:59.796   754  1148 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:59.806  1430  1430 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:53:59.806   754  1148 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,07-27 08:53:59.806   754  6578 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:53:59.806   754  6578 I System.out: (HTTPLog)-Static: isShipBuild true
07-27 08:53:59.806   754  6578 I System.out: (HTTPLog)-Thread-178-291491585: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
07-27 08:53:59.806   754  1148 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-27 08:53:59.806   754  6578 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:53:59.806   754  1148 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,07-27 08:53:59.806   754  1148 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-27 08:53:59.806   754  1148 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:53:59.806   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 08:53:59.806   754  1148 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
07-27 08:53:59.806   754  1149 D Tethering: MasterInitialState.processMessage what=3
07-27 08:53:59.806   754  1144 D NtpTrustedTime: forceRefresh() from cache miss
07-27 08:53:59.806   754  1143 V NetworkStats: updateIfacesLocked()
07-27 08:53:59.806   754  1143 V NetworkStats: performPollLocked(flags=0x1)
,07-27 08:53:59.806   754  1143 D NetworkStatsFactory: UpdateStatsForKnox
07-27 08:53:59.806   754  1143 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:59.806   754  1150 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-27 08:53:59.806   754  1150 D SmartBondingService: getSBEnabled() enabled =false
,07-27 08:53:59.806   754  1150 D SmartBondingService: getSBEnabled() enabled =false
07-27 08:53:59.806   754  1150 D SmartBondingService: getSBEnabled() enabled =false
07-27 08:53:59.806   754  1221 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:59.806  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-27 08:53:59.806  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-27 08:53:59.806  1197  1197 D StatusBar.NetworkController: updateDataNetType()
,07-27 08:53:59.806   754  1150 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-27 08:53:59.816   754  1148 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
07-27 08:53:59.816   754  1148 D ConnectivityService: calling update connectivity
07-27 08:53:59.816   754  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:59.816   754  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:53:59.816   754  1148 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 08:53:59.816   754  1056 D EntConnectivity: Not allowed due to - mEnabled false
07-27 08:53:59.816   754  1143 V NetworkStats: performPollLocked() took 8ms
07-27 08:53:59.816   754  1703 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:59.816  1197  1604 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-27 08:53:59.816  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-27 08:53:59.816  1197  1197 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-27 08:53:59.816   754   785 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 08:53:59.816   754   785 D SecContentProvider2: mCursor = null
,07-27 08:53:59.816   754  1446 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
,07-27 08:53:59.816   754  1446 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
,07-27 08:53:59.816  1197  1197 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-27 08:53:59.816  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 4 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
07-27 08:53:59.816  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
07-27 08:53:59.816  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
07-27 08:53:59.816  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 08:53:59.816  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 08:53:59.826  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 08:53:59.826  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 08:53:59.826  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 08:53:59.826  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 08:53:59.826  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 08:53:59.826  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 08:53:59.826  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 08:53:59.826  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 08:53:59.826  1197  1197 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,07-27 08:53:59.826  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
07-27 08:53:59.826  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
07-27 08:53:59.826  1197  1197 I PhoneStatusBar: Icon Only
07-27 08:53:59.826  1197  1197 I StatusBar: Icon Only
,07-27 08:53:59.826  1197  1197 D PanelView: There is/are notification(s) 
,07-27 08:53:59.826  1197  1197 D PanelView: There is/are notification(s) 
,07-27 08:53:59.886   754  1144 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1469602440053 mCachedNtpElapsedRealtime : 117770 mCachedNtpCertainty : 14
,07-27 08:53:59.886   754  1144 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 08:53:59.886   754  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:53:59.886   754  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:53:59.886   754  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:53:59.886   754  1144 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 08:53:59.886   754  1144 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-27 08:53:59.886   754  1144 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 08:53:59.896   754  6578 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,07-27 08:53:59.906   754  6578 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 06:54:00 GMT], X-Android-Received-Millis=[1469602439920], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469602439916]}
,07-27 08:53:59.906   754  6578 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-27 08:53:59.906   754  6578 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,07-27 08:53:59.906   754  1148 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 502]
07-27 08:53:59.906   754  1148 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-27 08:53:59.906   754  1148 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:53:59.906   754  1148 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:53:59.906   754  1148 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-27 08:53:59.906   754  1148 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
07-27 08:53:59.906   754  1148 D ConnectivityService: calling update connectivity
07-27 08:53:59.906   754  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:53:59.906   754  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 08:53:59.906   754  1148 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:53:59.906   754  1148 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-27 08:53:59.906  1197  1604 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-27 08:53:59.906   754  1221 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:53:59.916  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,07-27 08:53:59.916  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-27 08:53:59.916  1197  1197 D StatusBar.NetworkController: updateDataNetType()
,07-27 08:53:59.916  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-27 08:53:59.916  1197  1197 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-27 08:53:59.916   754  1558 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 08:53:59.916   754  1558 D SecContentProvider2: mCursor = null
,07-27 08:53:59.916   754   785 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
07-27 08:53:59.916   754   785 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
,07-27 08:53:59.916  1197  1197 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-27 08:53:59.916  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 4 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
07-27 08:53:59.916  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
07-27 08:53:59.916  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
,07-27 08:53:59.916  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 08:53:59.916  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 08:53:59.916  1197  1197 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,07-27 08:53:59.926  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
,07-27 08:53:59.926  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
07-27 08:53:59.926  1197  1197 I PhoneStatusBar: Icon Only
07-27 08:53:59.926  1197  1197 I StatusBar: Icon Only
,07-27 08:53:59.926  1197  1197 D PanelView: There is/are notification(s) 
,07-27 08:53:59.926  1197  1197 D PanelView: There is/are notification(s) 
,07-27 08:53:59.986   754  1111 V AlarmManager: waitForAlarm result :8
,07-27 08:54:00.306   754  1148 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:54:00.316   754   991 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:54:00.316   754   991 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:00.316   754   754 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.316   754   754 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.316   754   991 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.326   754  1558 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.326   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-27 08:54:00.326   754   785 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:00.326   754  1657 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.326   754  1470 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.326   754  1446 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:00.326   754  1580 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.326   754  1639 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.326   754  1593 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.326   754   754 D SmartBondingService: SmartBondingReceiver: wifi is connected
,07-27 08:54:00.326   754   754 D SmartBondingService: SmartBondingReceiver: wifi ap is changed, init speed ratio
,07-27 08:54:00.326   754   754 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.336   754  1150 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-27 08:54:00.336   754  1150 D SmartBondingService: getSBEnabled() enabled =false
07-27 08:54:00.336   754  1150 D SmartBondingService: getSBEnabled() enabled =false
,07-27 08:54:00.336   754  1150 D SmartBondingService: getSBEnabled() enabled =false
07-27 08:54:00.336   754   754 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.336   754  1446 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:00.336   308   308 E SMD     : DCD ON
07-27 08:54:00.336   754   754 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.336   754   754 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:00.336   754   754 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:00.336   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.336   754  1402 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 08:54:00.336   754  1291 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.336   754  1593 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.336  5213  5213 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-27 08:54:00.336  6285  6285 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:54:00.336  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:54:00.336  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 08:54:00.336  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:54:00.336  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:54:00.336  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 08:54:00.336  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 08:54:00.336  6285  6285 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 08:54:00.336   754  1150 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-27 08:54:00.336  6285  6285 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 08:54:00.346   754  1657 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.346  5802  5802 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-27 08:54:00.346  5802  5802 I PCWCLIENTTRACE_PushUtil: sales region : global
07-27 08:54:00.346  5802  5802 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-27 08:54:00.346  5802  5802 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:54:00.346   754  1402 D AlarmManagerService: Setting time of day to sec=1469602440
,07-27 08:54:00.346   754  1402 D AlarmManagerService: Trying to open a file
,07-27 08:54:00.346   754  1402 D AlarmManagerService: File Open Success
07-27 08:54:00.346   754  1402 D AlarmManagerService: File Close Success
07-27 08:54:00.346   754  1402 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
,07-27 08:54:00.506   754  1402 W AlarmManagerService: Unable to set rtc to 1469602440: Invalid argument
07-27 08:54:00.506   754  1111 V AlarmManager: waitForAlarm result :65536
,07-27 08:54:00.506  5213  5213 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-27 08:54:00.506   754   991 E GpsLocationProvider: No APN found to select.
,07-27 08:54:00.516   754   754 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,07-27 08:54:00.516  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
07-27 08:54:00.516  1197  1197 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:54:00.516   754   754 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
,07-27 08:54:00.516  1197  1197 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
,07-27 08:54:00.516  1197  1197 D StatusBar-DoNotDistrub: Received intent with android.intent.action.TIME_SET action
07-27 08:54:00.516  1197  1197 D StatusBar-DoNotDistrub: Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,07-27 08:54:00.516   754   754 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 08:54:00.516   754  1008 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
07-27 08:54:00.516   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:00.516   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:00.516   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:00.516   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:00.526  1789  1789 D accuweather: [Accuweather J]>>> SWW:64 [0:0] =============== BR act = androidintentactionTIME_SET
,07-27 08:54:00.526   754   754 I DrmEventService:  no response from SecureClock 
,07-27 08:54:00.526  1789  1789 D accuweather: [Accuweather J]>>> SWW:645 [0:0] renderUpdateAllCondition : [0] = 1
,07-27 08:54:00.526  1789  1789 D accuweather: [Accuweather J]>>> WR:452 [0:0] =============== updateAllCondition = 1
,07-27 08:54:00.556  6662  6662 E Zygote  : MountEmulatedStorage()
,07-27 08:54:00.556  6662  6662 E Zygote  : v2
07-27 08:54:00.556  6662  6662 I libpersona: KNOX_SDCARD checking this for 10014
07-27 08:54:00.556  6662  6662 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:00.566   754  1008 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6662 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:00.566  1197  1197 D StatusBar-DoNotDistrub: sendBroadcast android.intent.action.DORMANT_MODE_OFF
07-27 08:54:00.566   754  1558 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-27 08:54:00.566   754  1558 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e583232, r.packageName :com.google.android.gms
,07-27 08:54:00.576   754  1580 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,07-27 08:54:00.576   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:00.576   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:00.576   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:00.576   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:00.586   319   693 V AudioPolicyManager: getOutputsForDevice device 0002 -> 0002
07-27 08:54:00.586  6662  6662 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-27 08:54:00.586  6662  6662 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 08:54:00.586  1197  1197 D StatusBar-DoNotDistrub: The STREAM NOTIFICATION volume is 11
07-27 08:54:00.586   754  1291 I AudioService: getStreamVolume 5 index 110
07-27 08:54:00.586   754  1221 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=com.android.systemui
07-27 08:54:00.586  6662  6662 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-27 08:54:00.596  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 08:54:00.606  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 08:54:00.616  6672  6672 E Zygote  : MountEmulatedStorage()
07-27 08:54:00.616  6672  6672 E Zygote  : v2
07-27 08:54:00.616  6672  6672 I libpersona: KNOX_SDCARD checking this for 10004
07-27 08:54:00.616  6672  6672 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:00.626   754  1580 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6672 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:00.636  6672  6672 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:00.636  6672  6672 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:54:00.636  6662  6662 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:00.636  6662  6662 D ActivityThread: Added TimaKeyStore provider
07-27 08:54:00.636  6672  6672 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:00.646  6662  6662 D ResourcesManager: creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,07-27 08:54:00.646   754  1451 D ActivityManager: bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
,07-27 08:54:00.646  1562  1562 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:54:00.666  6672  6672 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:00.666  6672  6672 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:00.676  6672  6672 D ResourcesManager: creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,07-27 08:54:00.706  6662  6662 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-27 08:54:00.716  6662  6662 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,07-27 08:54:00.726   754  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 08:54:00.726   754  1481 D ActivityManager: caller:android.app.ApplicationThreadProxy@31edc056, r.packageName :com.google.android.gms
,07-27 08:54:00.736   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:00.746   754  1291 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.746   754  1639 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 08:54:00.756   754  1639 D ActivityManager: caller:android.app.ApplicationThreadProxy@367fb5c4, r.packageName :com.google.android.gms
,07-27 08:54:00.756  4139  4139 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-27 08:54:00.756  4139  4139 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1469602440766
,07-27 08:54:00.756   754  1291 I ActivityManager: Killing 5670:com.android.defcontainer/u0a7 (adj 15): emptyCount ##41
,07-27 08:54:00.756  4139  4139 I KLMS-2.4.511: : MainReciver(): TIME_CHANGED
,07-27 08:54:00.756  4139  4139 I KLMS-2.4.511: : StateImplV2(): dateTimeChanged().START : Wed Jul 27 08:54:00 GMT+02:00 2016
,07-27 08:54:00.766   754  1470 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,07-27 08:54:00.766  4139  4139 I KLMS-2.4.511: : StateImplV2(): dateTimeChanged().END
07-27 08:54:00.766   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:00.766   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:00.766   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:00.766   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:00.806  6698  6698 E Zygote  : MountEmulatedStorage()
07-27 08:54:00.806  6698  6698 E Zygote  : v2
07-27 08:54:00.806  6698  6698 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:54:00.806  6698  6698 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:00.816   754  1470 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6698 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-27 08:54:00.856  6698  6698 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:00.856  6698  6698 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 08:54:00.856  6698  6698 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:00.856   754  1593 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:00.856  5821  5821 W System.err: android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
07-27 08:54:00.856  5821  5821 W System.err: 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
07-27 08:54:00.856  5821  5821 W System.err: 	at android.provider.Settings$System.getLong(Settings.java:1669)
07-27 08:54:00.856  5821  5821 W System.err: 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
07-27 08:54:00.856  5821  5821 W System.err: 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
07-27 08:54:00.856  5821  5821 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-27 08:54:00.856  5821  5821 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-27 08:54:00.856  5821  5821 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-27 08:54:00.856  5821  5821 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:00.856  5821  5821 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:54:00.856  5821  5821 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 08:54:00.856  5821  5821 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:00.856  5821  5821 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:54:00.856  5821  5821 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 08:54:00.856  5821  5821 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,07-27 08:54:00.866   754  1558 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,07-27 08:54:00.866   754  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:00.866   754  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:00.866   754  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:00.866   754  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:00.896  6698  6698 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:00.896  6698  6698 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:00.906  6713  6713 E Zygote  : MountEmulatedStorage()
,07-27 08:54:00.906  6713  6713 E Zygote  : v2
07-27 08:54:00.906  6713  6713 I libpersona: KNOX_SDCARD checking this for 10042
07-27 08:54:00.906  6713  6713 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:00.906   754  1558 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/com.sec.android.fota.osp.time.ServerTimeReceiver: pid=6713 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,07-27 08:54:00.926  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-27 08:54:00.926  6285  6348 I jxcore-log: 
,07-27 08:54:00.936  6713  6713 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-27 08:54:00.936  6713  6713 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:54:00.936  6713  6713 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:00.956  6713  6713 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:00.956  6713  6713 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:00.956  6698  6698 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,07-27 08:54:00.966  6713  6713 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,07-27 08:54:00.996  6713  6713 I SO_AGENT: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,07-27 08:54:00.996  5911  5911 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,07-27 08:54:00.996  6698  6698 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,07-27 08:54:01.016  6698  6698 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,07-27 08:54:01.016   754  1528 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
07-27 08:54:01.016   754  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:01.016   754  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:01.016   754  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:01.026   754  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:01.056  6729  6729 E Zygote  : MountEmulatedStorage()
07-27 08:54:01.056  6729  6729 E Zygote  : v2
07-27 08:54:01.056  6729  6729 I libpersona: KNOX_SDCARD checking this for 10076
07-27 08:54:01.056  6729  6729 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:01.066   754  1528 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6729 uid=10076 gids={50076, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:01.126  6729  6729 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:01.126  6729  6729 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 08:54:01.126  6729  6729 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:01.126   754  1528 I ActivityManager: Killing 4797:com.google.android.gms.wearable/u0a15 (adj 15): emptyCount ##41
,07-27 08:54:01.136  6729  6729 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:01.146  6729  6729 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:01.156  6729  6729 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,07-27 08:54:01.156  6698  6698 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,07-27 08:54:01.166  6698  6698 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,07-27 08:54:01.166  6698  6698 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:54:01.166  6698  6698 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-27 08:54:01.206   754  1446 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,07-27 08:54:01.206   754  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:01.206   754  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:01.206   754  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:01.206   754  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:01.206  6729  6745 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,07-27 08:54:01.286  6747  6747 E Zygote  : MountEmulatedStorage()
07-27 08:54:01.286  6747  6747 E Zygote  : v2
07-27 08:54:01.286  6747  6747 I libpersona: KNOX_SDCARD checking this for 10106
07-27 08:54:01.286  6747  6747 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:01.286   754  1446 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6747 uid=10106 gids={50106, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,07-27 08:54:01.336  6747  6747 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:01.336  6747  6747 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:54:01.336  6747  6747 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:01.336   754  1446 I ActivityManager: Killing 5713:com.google.android.partnersetup/u0a19 (adj 15): emptyCount ##41
,07-27 08:54:01.366  6747  6747 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:01.366  6747  6747 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:01.366  6662  6662 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-27 08:54:01.376  6662  6662 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-27 08:54:01.386  6747  6747 D ResourcesManager: creating new AssetManager and set to /system/app/ClockPackage_Osup/ClockPackage_Osup.apk
,07-27 08:54:01.386  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-27 08:54:01.386  6285  6348 I jxcore-log: 
,07-27 08:54:01.386  6747  6747 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,07-27 08:54:01.386  6747  6747 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 08:54:01.386  6747  6747 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-27 08:54:01.396  6662  6662 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-27 08:54:01.406   754  1593 I ActivityManager: Killing 5741:com.samsung.groupcast/u0a20 (adj 15): emptyCount ##41
,07-27 08:54:01.406   754  1446 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.426  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-27 08:54:01.426  6285  6348 I jxcore-log: 
,07-27 08:54:01.436  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-27 08:54:01.436  6285  6348 I jxcore-log: 
,07-27 08:54:01.436   754  1318 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-27 08:54:01.436   754  1318 D ActivityManager: caller:android.app.ApplicationThreadProxy@f9d8be2, r.packageName :com.google.android.gms
,07-27 08:54:01.436   754   785 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.436   754  1580 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.436   754  1558 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.446  1759  1759 I iu.Environment: update battery state; isPlugged? true*
,07-27 08:54:01.446   754  1318 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.446  1759  1759 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,07-27 08:54:01.456   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.456   754  1593 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.456   754  1318 D SettingsProvider: name = next_alarm_formatted
07-27 08:54:01.456  1759  1759 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
07-27 08:54:01.456   754  1318 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:54:01.456   754  1318 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:54:01.456   754  1318 D SettingsProvider: selectionArgs: false
07-27 08:54:01.456   754  1318 D SettingsProvider: selectionArgs: 10106
07-27 08:54:01.456   754  1580 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.456   754  1318 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 08:54:01.456   754  1558 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:01.456  1759  1759 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
07-27 08:54:01.456   754  1318 D SettingsProvider: ret = -1
,07-27 08:54:01.466  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-27 08:54:01.466  6285  6348 I jxcore-log: 
,07-27 08:54:01.466   754  1580 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 08:54:01.466   754  1580 D ActivityManager: caller:android.app.ApplicationThreadProxy@397f9b73, r.packageName :com.google.android.gms
,07-27 08:54:01.466  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-27 08:54:01.466  6285  6348 I jxcore-log: 
,07-27 08:54:01.476  1759  1759 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy}
07-27 08:54:01.476  1759  1759 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy} to Chimera receiver impl com.google.android.gms.kids.account.SystemEventReceiver
07-27 08:54:01.476  1759  1759 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-27 08:54:01.476  1759  1759 I Kids    : [GCoreUtils] Current gmscore version, 7571438 is smaller than the required version 8400000
,07-27 08:54:01.486  4139  4139 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-27 08:54:01.486  4139  4139 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1469602441494
,07-27 08:54:01.486   754  1470 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.486  4139  4139 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-27 08:54:01.486   754   785 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.486   754  1580 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.496  4139  4139 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,07-27 08:54:01.496  4139  4139 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().START
,07-27 08:54:01.496  4139  4139 I KLMS-2.4.511: : NetworkChangeOperations(): uploadRequestLog().START 
,07-27 08:54:01.506  4139  4139 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,07-27 08:54:01.506   754  1639 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.pinboard, hostingType: broadcast
,07-27 08:54:01.506   754  1639 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:01.506   754  1639 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:01.506   754  1639 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:01.506   754  1639 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:01.546  6768  6768 E Zygote  : MountEmulatedStorage()
,07-27 08:54:01.546  6768  6768 E Zygote  : v2
07-27 08:54:01.546  6768  6768 I libpersona: KNOX_SDCARD checking this for 10036
07-27 08:54:01.546  6768  6768 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:01.546   754  1639 I ActivityManager: Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=6768 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-27 08:54:01.576  1562  6765 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-27 08:54:01.586  6768  6768 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:01.586  6768  6768 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:54:01.586  6768  6768 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-27 08:54:01.586   754  1657 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.596   754  1528 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.606  6768  6768 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:01.606  6768  6768 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:01.626   754  1558 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-27 08:54:01.626   754  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:01.626   754  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:01.626   754  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:01.626   754  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:01.626  6768  6768 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-27 08:54:01.636  6768  6768 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-27 08:54:01.636  6768  6768 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-27 08:54:01.666  6768  6768 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
07-27 08:54:01.666  6785  6785 E Zygote  : MountEmulatedStorage()
07-27 08:54:01.666  6785  6785 E Zygote  : v2
07-27 08:54:01.666  6785  6785 I libpersona: KNOX_SDCARD checking this for 10116
07-27 08:54:01.666  6785  6785 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:01.666   754  1558 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6785 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,07-27 08:54:01.716  6785  6785 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:01.716  6785  6785 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:54:01.716  6785  6785 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:01.716   754  1558 I ActivityManager: Killing 4907:com.sec.android.service.health/u0a21 (adj 15): emptyCount ##41
,07-27 08:54:01.726   754  1558 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.726   754   785 I ActivityManager: Killing 5760:sstream.app/u0a25 (adj 15): emptyCount ##41
,07-27 08:54:01.736   754  1580 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,07-27 08:54:01.736   754  1580 D ActivityManager: caller:android.app.ApplicationThreadProxy@317c06a9, r.packageName :com.samsung.android.app.galaxyfinder
,07-27 08:54:01.736   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:01.746  1562  6780 D GCM     : Connected
,07-27 08:54:01.746   754  1657 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.756   754  1446 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.766   754  1221 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.766  6785  6785 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:01.766   754  1481 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.766  6785  6785 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:01.766  6713  6713 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,07-27 08:54:01.776  6785  6785 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,07-27 08:54:01.776   754  1291 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.786  1562  6780 D GCM     : Message class com.google.f.a.a.p
,07-27 08:54:01.786   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.786   754  1470 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.796  6785  6785 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,07-27 08:54:01.796  6785  6785 D elm:14491: ELMEngine.ELMEngine( context ).
,07-27 08:54:01.796  6785  6785 D elm:14491: MDMBridge.setEnterpriseBridge()
,07-27 08:54:01.806   754  1593 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,07-27 08:54:01.806   754  1593 D ActivityManager: caller:android.app.ApplicationThreadProxy@391df95c, r.packageName :com.sec.esdk.elm
,07-27 08:54:01.806  6785  6785 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,07-27 08:54:01.816   754   783 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,07-27 08:54:01.816   754   783 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:01.816  6785  6785 D elm:14491: ElmAgentService : onCreate()
,07-27 08:54:01.816   754   783 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:01.816   754   783 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:01.816   754   783 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:01.816   754  1703 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.816  3396  6805 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-27 08:54:01.816  6785  6804 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
07-27 08:54:01.816  3396  6805 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,07-27 08:54:01.816  3396  6805 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,07-27 08:54:01.816  3396  6805 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(259/xdmNotInitSetResume)] DM Not Init
,07-27 08:54:01.826  3396  6805 I DBG_POLICYDM: [com.policydm.XDMService(300/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,07-27 08:54:01.826  3396  3517 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(33/xuiAdpGetUiMode)] nDmUiMode : 0
,07-27 08:54:01.826  6785  6804 D elm:14491: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,07-27 08:54:01.826  3396  3517 I DBG_POLICYDM: [com.policydm.agent.XDMTask(200/xdmAgentTaskHandler)] XEVENT_DM_INIT
,07-27 08:54:01.826  6785  6785 D elm:14491: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,07-27 08:54:01.826  6785  6785 D elm:14491: ModuleBase.ModifySetAlarm()
07-27 08:54:01.826  6785  6785 D elm:14491: MDMBridge.getInstance()
07-27 08:54:01.826  6785  6785 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,07-27 08:54:01.826   754  1291 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.826  3396  3517 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-27 08:54:01.836  3396  3517 I DBG_POLICYDM: [com.policydm.XDMService(661/xdmGetNotibarState)] get NotibarState : 9
,07-27 08:54:01.836  3396  3517 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 9
,07-27 08:54:01.836  3396  3517 I DBG_POLICYDM: [com.policydm.XDMService(653/xdmSetNotibarState)] set NotibarState : 9
,07-27 08:54:01.856  3396  3517 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(234/xdbGetCryptionkey)] try read dbString
,07-27 08:54:01.866  3396  3517 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(442/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,07-27 08:54:01.866  3396  3517 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(574/xdbGetFUMOInitiatedType)] Initiated Type: 0
,07-27 08:54:01.876  3396  3518 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(216/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,07-27 08:54:01.876   754  1451 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:01.876  3396  3518 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-27 08:54:01.876  3396  3517 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(78/xpollingCheckVersionInfo)] 
,07-27 08:54:01.876  3396  3517 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(277/xpollingCheckTimer)] 
,07-27 08:54:01.886  3396  3518 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,07-27 08:54:01.886  3396  3518 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(306/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,07-27 08:54:01.886  3396  3518 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(307/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,07-27 08:54:01.886  3396  3518 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(308/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,07-27 08:54:01.886  3396  3518 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(348/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,07-27 08:54:01.886  3396  3518 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(175/xnotiPushAdpClearSessionStatus)] 
,07-27 08:54:01.886  3396  3518 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,07-27 08:54:01.886  3396  3518 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(453/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,07-27 08:54:01.886  3396  3517 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(291/xpollingCheckTimer)] savedpollingtime : 2016/07/30/03:04:35
,07-27 08:54:01.896  3396  3517 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(292/xpollingCheckTimer)] currentTime : 2016/07/27/08:54:01
07-27 08:54:01.896  3396  3517 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(296/xpollingCheckTimer)] Restart Timer..
,07-27 08:54:01.896  6810  6810 E Zygote  : MountEmulatedStorage()
07-27 08:54:01.896  6810  6810 E Zygote  : v2
07-27 08:54:01.896  6810  6810 I libpersona: KNOX_SDCARD checking this for 10172
07-27 08:54:01.896  6810  6810 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:01.896  3396  3517 I DBG_POLICYDM: [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 0
,07-27 08:54:01.906   754   783 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6810 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,07-27 08:54:01.916  3396  3518 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(552/xdbSetFUMOInitiatedType)] Initiated Type: 0
,07-27 08:54:01.916   349   349 I art     : Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 306us total 12.957ms
,07-27 08:54:01.926  3396  3518 I DBG_POLICYDM: [com.policydm.db.XDB(1781/xdbSetBackUpServerUrl)] 
,07-27 08:54:01.926   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 269us total 9.691ms
,07-27 08:54:01.936   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 267us total 9.625ms
,07-27 08:54:01.946  6810  6810 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:01.946  6810  6810 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 08:54:01.946  6810  6810 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:01.946  6785  6785 D elm:14491: ElmAgentService : onDestroy().
,07-27 08:54:01.966  6810  6810 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:01.966  6810  6810 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:01.966  3396  3517 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(318/xPollingReportReStartAlarm)] 
,07-27 08:54:01.976  5160  5160 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,07-27 08:54:01.996  6810  6810 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,07-27 08:54:01.996  6810  6810 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-27 08:54:01.996  6810  6810 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 08:54:01.996  6810  6810 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-27 08:54:02.006  5911  5911 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-27 08:54:02.006  5911  5911 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,07-27 08:54:02.006  5911  5911 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-27 08:54:02.006  5911  5911 I SA      : [SLFUCHKMGR] constructor called
,07-27 08:54:02.016   754  1148 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
,07-27 08:54:02.016   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
07-27 08:54:02.016   754   754 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:02.016   754  1150 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-27 08:54:02.016   754  1150 D SmartBondingService: getSBEnabled() enabled =false
07-27 08:54:02.016   754  1150 D SmartBondingService: getSBEnabled() enabled =false
07-27 08:54:02.016   754  1150 D SmartBondingService: getSBEnabled() enabled =false
07-27 08:54:02.016   754  1148 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,fe80::ea50:8bff:fed7:fd2b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-27 08:54:02.016   754  1148 D ConnectivityService: identical MTU - not setting
07-27 08:54:02.016   754  1148 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-27 08:54:02.016   754  1148 D ConnectivityService: updateSourceRoutes : add src route for:fe80::ea50:8bff:fed7:fd2b
,07-27 08:54:02.016   301  1051 V         : QcRouteController
,07-27 08:54:02.036   301  1051 V         : QcRouteController
,07-27 08:54:02.036   754  1148 W NetworkManagementService: route cmd failed: 
07-27 08:54:02.036   754  1148 W NetworkManagementService: com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '54 route replace src v6 wlan0 fe80::ea50:8bff:fed7:fd2b 2 ::' failed with '400 54 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
07-27 08:54:02.036   754  1148 W NetworkManagementService: '
07-27 08:54:02.036   754  1148 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
07-27 08:54:02.036   754  1148 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
07-27 08:54:02.036   754  1148 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
07-27 08:54:02.036   754  1148 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
07-27 08:54:02.036   754  1148 W NetworkManagementService: 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2844)
07-27 08:54:02.036   754  1148 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5632)
07-27 08:54:02.036   754  1148 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5444)
07-27 08:54:02.036   754  1148 W NetworkManagementService: 	at com.android.server.ConnectivityService.access$2400(ConnectivityService.java:230)
07-27 08:54:02.036   754  1148 W NetworkManagementService: 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2387)
07-27 08:54:02.036   754  1148 W NetworkManagementService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:02.036   754  1148 W NetworkManagementService: 	at android.os.Looper.loop(Looper.java:145)
07-27 08:54:02.036   754  1148 W NetworkManagementService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:54:02.036   754  1148 V Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true
07-27 08:54:02.036   754  1148 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-27 08:54:02.036   754  1148 D ConnectivityService: calling update connectivity
,07-27 08:54:02.046   754  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:02.046   754  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 08:54:02.046   754  1148 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 08:54:02.046   754  1148 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-27 08:54:02.046  5911  5911 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-27 08:54:02.046  5911  5911 I SA      : [OR] == isSIMCardReady false ==
,07-27 08:54:02.046  1197  1604 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-27 08:54:02.046   754  1703 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:02.046  5911  5911 I SA      : [SCU] == networkStateCheck == true
,07-27 08:54:02.046   754  1148 D ConnectivityService: calling update connectivity
,07-27 08:54:02.046  5911  5911 I SA      : [DM] getCountryCodeFromCSC : PL
07-27 08:54:02.046  5911  5911 I SA      : isChinaCountryCode : false
07-27 08:54:02.046  5911  5911 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-27 08:54:02.046  5911  5911 I SA      : [OR] == networkStateCheck true ==
07-27 08:54:02.046   754  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:02.046   754  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 08:54:02.046   754  1148 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 08:54:02.046  1197  1604 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-27 08:54:02.056   754  1446 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,07-27 08:54:02.056  5911  5911 I SA      : [OR] GetMyCountryZoneTask
07-27 08:54:02.056   754  1446 D ActivityManager: caller:android.app.ApplicationThreadProxy@d60b53a, r.packageName :com.android.calendar
07-27 08:54:02.056  5911  5911 I SA      : [OR] onReceive END
,07-27 08:54:02.066  5911  6831 I SA      : [SRS] prepareGetMyCountryZone
,07-27 08:54:02.066   754  1451 I ActivityManager: Killing 5837:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): emptyCount ##41
,07-27 08:54:02.066  5911  6831 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-27 08:54:02.066  5911  6831 I SA      : [SSP] query invoked
,07-27 08:54:02.076  3396  3517 I DBG_POLICYDM: [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 1
,07-27 08:54:02.086   754  1318 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:02.086  3396  3517 I DBG_POLICYDM: [com.policydm.agent.XDMTask(225/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,07-27 08:54:02.136  3396  3518 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,07-27 08:54:02.156  3396  3518 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,07-27 08:54:02.166   754   785 I art     : Explicit concurrent mark sweep GC freed 57060(3MB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 35MB/51MB, paused 1.375ms total 91.523ms
,07-27 08:54:02.166   754  1657 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
07-27 08:54:02.166   754  1657 D ActivityManager: caller:android.app.ApplicationThreadProxy@203f4f48, r.packageName :com.android.providers.downloads
,07-27 08:54:02.166   754  1639 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,07-27 08:54:02.176   754  1639 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.176   754  1639 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.176   754  1639 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.176   754  1639 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:02.176  5911  6831 I SA      : [TPMU] GetMccFromDB : null
07-27 08:54:02.176  5911  6831 I SA      : [SCU] getMccFromPreferece mcc = 260
,07-27 08:54:02.176  5911  6831 I SA      : [TPM] isNoProxy(default) : true
,07-27 08:54:02.186  5911  6831 E File    : fail readDirectory() errno=2
,07-27 08:54:02.206  6836  6836 E Zygote  : MountEmulatedStorage()
07-27 08:54:02.206  6836  6836 E Zygote  : v2
07-27 08:54:02.206  6836  6836 I libpersona: KNOX_SDCARD checking this for 10051
07-27 08:54:02.206  6836  6836 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:02.216   754  1639 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6836 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:02.216   754  1451 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
07-27 08:54:02.226   754  1451 D ActivityManager: caller:android.app.ApplicationThreadProxy@1f14eb06, r.packageName :com.android.calendar
,07-27 08:54:02.226   754  1528 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,07-27 08:54:02.226   754  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.226   754  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.226   754  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.226   754  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:02.236  6836  6836 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:02.236  6836  6836 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 08:54:02.236  6836  6836 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-27 08:54:02.256  6836  6836 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:02.256  6836  6836 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:02.266  6850  6850 E Zygote  : MountEmulatedStorage()
07-27 08:54:02.266  6850  6850 E Zygote  : v2
07-27 08:54:02.266  6850  6850 I libpersona: KNOX_SDCARD checking this for 10074
07-27 08:54:02.266  6850  6850 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:02.276   754  1528 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=6850 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,07-27 08:54:02.296  6850  6850 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:02.296  6850  6850 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:54:02.296  6850  6850 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:02.296  6355  6355 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 08:54:02.296  6355  6355 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 08:54:02.296  6355  6355 D SecurityLogAgent: StateMachine : Current State = 1
,07-27 08:54:02.296   754  1221 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:02.306   754  1593 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:02.306   754  1291 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,07-27 08:54:02.306   754  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.306   754  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.306   754  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.306   754  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:02.306  6836  6836 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,07-27 08:54:02.306  6836  6836 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-27 08:54:02.316  6850  6850 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:02.316  6850  6850 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:02.346  6867  6867 E Zygote  : MountEmulatedStorage()
07-27 08:54:02.346   754  1291 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6867 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-27 08:54:02.346  6867  6867 E Zygote  : v2
07-27 08:54:02.346  6867  6867 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:54:02.346  6867  6867 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:02.376  6836  6836 I CalendarProvider2: CalendarProvider2.onCreate() called
,07-27 08:54:02.386  6867  6867 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:02.386  6867  6867 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 08:54:02.386  6867  6867 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:02.396  6850  6850 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,07-27 08:54:02.406  6867  6867 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:02.406  6867  6867 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:02.416  6867  6867 D ResourcesManager: creating new AssetManager and set to /system/app/TimeService/TimeService.apk
,07-27 08:54:02.426  6867  6867 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1469602442438
,07-27 08:54:02.426  6867  6867 D         : TimeServiceNative: User Time to be set is 1469602442438
07-27 08:54:02.426  6867  6867 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
07-27 08:54:02.426  6867  6867 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
07-27 08:54:02.436  6867  6867 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1469602442438
,07-27 08:54:02.436   362   769 D QC-time-services: Daemon: Connection accepted:time_genoff
,07-27 08:54:02.436  6867  6867 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
07-27 08:54:02.436   362  6883 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1469602442438
07-27 08:54:02.436   362  6883 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1469602442438, operation = 0
07-27 08:54:02.436   362  6883 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/2/70 8:28:48
07-27 08:54:02.436   362  6883 D QC-time-services: Daemon:Value read from RTC seconds = 28974528000
07-27 08:54:02.436   362  6883 D QC-time-services: Daemon:new time 1469602442438 
07-27 08:54:02.436   362  6883 D QC-time-services: Daemon: delta 1440627914438 genoff 1440627914438 
07-27 08:54:02.436   362  6883 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440627914438 to memory
07-27 08:54:02.436   362  6883 D QC-time-services: Daemon:Opening File: /data/time/ats_2
07-27 08:54:02.436   362  6883 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-27 08:54:02.436   362  6883 D QC-time-services: Updating the TOD offset
07-27 08:54:02.436   362  6883 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440627914438 to memory
07-27 08:54:02.436   362  6883 D QC-time-services: Daemon:Opening File: /data/time/ats_1
07-27 08:54:02.436   362  6883 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-27 08:54:02.436   362  6883 E QC-time-services: Daemon:Update to modem bit set
07-27 08:54:02.436   362  6883 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
07-27 08:54:02.436   362  6883 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1124663114438
,07-27 08:54:02.436  6867  6867 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,07-27 08:54:02.446   754  1470 I ActivityManager: Killing 5860:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
,07-27 08:54:02.446   362   769 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
07-27 08:54:02.446   362   767 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,07-27 08:54:02.446  4379  4379 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:63 [0:0] onReceive: androidintentactionTIME_SET
,07-27 08:54:02.446  4379  4379 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:64 [0:0] appServiceStatus: 0
07-27 08:54:02.446  4379  4379 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:65 [0:0] [AR]: 0
07-27 08:54:02.446  4379  4379 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:66 [0:0] [AR]: Next time = 0
,07-27 08:54:02.456  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : androidintentactionTIME_SET, run:true
,07-27 08:54:02.456  4379  4379 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
07-27 08:54:02.456  4379  4379 D comsamsunglog: [MSC_Accu_Daemon]>>> daemonapp [Version : 150820735400 ] [ 1 ] 
07-27 08:54:02.456  4379  4379 D comsamsunglog: [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 08:54:02.456  4379  4379 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
,07-27 08:54:02.456  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-27 08:54:02.456  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,07-27 08:54:02.456  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-27 08:54:02.456  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-27 08:54:02.456  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-27 08:54:02.466  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 08:54:02.466  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,07-27 08:54:02.466  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-27 08:54:02.466  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
07-27 08:54:02.466  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-27 08:54:02.466  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,07-27 08:54:02.496  6850  6850 I sCloudBackupApp: sCloudBackupApp Version Info : 3.13.7.KK_APP
,07-27 08:54:02.496  6850  6850 I SCloudBackupReceiver: Other Intent
07-27 08:54:02.496   754  1291 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,07-27 08:54:02.496   754  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.496   754  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.496   754  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.496   754  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:02.536  6886  6886 E Zygote  : MountEmulatedStorage()
,07-27 08:54:02.536  6886  6886 E Zygote  : v2
07-27 08:54:02.536  6886  6886 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:54:02.536  6886  6886 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:02.546   754  1291 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=6886 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-27 08:54:02.546   754  1291 I ActivityManager: Killing 5352:com.sec.android.gallery3d/u0a53 (adj 15): emptyCount ##41
,07-27 08:54:02.576  6886  6886 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:02.576  6886  6886 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:54:02.576  6886  6886 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:02.596   754  1703 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,07-27 08:54:02.596   754  1703 D ActivityManager: caller:android.app.ApplicationThreadProxy@5b854de, r.packageName :com.android.providers.calendar
,07-27 08:54:02.596  6886  6886 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:02.596  6886  6886 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:02.616  6886  6886 D ResourcesManager: creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,07-27 08:54:02.616  6886  6886 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-27 08:54:02.626  6886  6886 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,07-27 08:54:02.636  6886  6886 I KnoxUsageLogPro: premStatus:2
,07-27 08:54:02.636  6886  6886 I KnoxUsageLogPro: isEulaShown : false
07-27 08:54:02.636  6886  6886 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-27 08:54:02.646   754  1481 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,07-27 08:54:02.646   754  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.646   754  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.646   754  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.646   754  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:02.726  6905  6905 E Zygote  : MountEmulatedStorage()
,07-27 08:54:02.726  6905  6905 E Zygote  : v2
07-27 08:54:02.726  6905  6905 I libpersona: KNOX_SDCARD checking this for 10104
07-27 08:54:02.726  6905  6905 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:02.736   754  1481 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6905 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:02.736   754  1481 I ActivityManager: Killing 5933:com.sec.android.app.soundalive/u0a64 (adj 15): emptyCount ##41
,07-27 08:54:02.736   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-27 08:54:02.786  6905  6905 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:02.786  6905  6905 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:54:02.786  6905  6905 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,07-27 08:54:02.786   754  1221 I ActivityManager: Killing 5238:com.samsung.android.app.assistantmenu/1000 (adj 15): emptyCount ##41
,07-27 08:54:02.826  6905  6905 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:02.826  6905  6905 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:02.836  6905  6905 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-27 08:54:02.966  2926  2980 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-27 08:54:02.976  5911  6831 I SA      : [RC New] Execute method=[GET] start
,07-27 08:54:02.996   754  1481 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,07-27 08:54:02.996   754  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:02.996   754  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.996   754  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:02.996   754  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:03.016  5911  6831 I SA      : [RC New] Security=[true]
,07-27 08:54:03.016  5911  6831 I System.out: Thread-965(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-27 08:54:03.016  5911  6831 I System.out: Thread-965(ApacheHTTPLog):isShipBuild true
,07-27 08:54:03.016  5911  6831 I System.out: Thread-965(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,07-27 08:54:03.046  6922  6922 E Zygote  : MountEmulatedStorage()
,07-27 08:54:03.046  6922  6922 E Zygote  : v2
07-27 08:54:03.046  6922  6922 I libpersona: KNOX_SDCARD checking this for 10146
07-27 08:54:03.046  6922  6922 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:03.046   754  1481 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6922 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:03.056   754  1481 I ActivityManager: Killing 5989:com.google.android.apps.docs/u0a112 (adj 15): emptyCount ##41
,07-27 08:54:03.096  6922  6922 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:03.096  6922  6922 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:54:03.096  6922  6922 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-27 08:54:03.096   754  1146 E WifiStateMachine: CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,07-27 08:54:03.116  6922  6922 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:03.116  6922  6922 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:03.126  6922  6922 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-27 08:54:03.316   265   551 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-27 08:54:03.316   265   551 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 08:54:03.316  6922  6940 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-27 08:54:03.326   265   551 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-27 08:54:03.326   265   551 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 08:54:03.326  6922  6940 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-27 08:54:03.356   265   551 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-27 08:54:03.356   265   551 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 08:54:03.356  6922  6942 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-27 08:54:03.376   265   551 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-27 08:54:03.376   265   551 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 08:54:03.376  6922  6942 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-27 08:54:03.386   266   321 I SurfaceFlinger: id=12 Removed Uoast (8/9)
,07-27 08:54:03.386   266  1584 I SurfaceFlinger: id=12 Removed Uoast (-2/9)
,07-27 08:54:03.386   754  1446 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=754 (0x0)
,07-27 08:54:03.386   754  1446 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=754, ws=WorkSource{10067}) (elapsedTime=3484)
,07-27 08:54:03.406   754  1558 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:03.486  6598  6598 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-27 08:54:03.486   308   308 E SMD     : DCD ON
,07-27 08:54:03.506  6922  6922 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,07-27 08:54:03.506  6922  6922 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,07-27 08:54:03.526  6922  6922 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1269-1272)
,07-27 08:54:03.526  6922  6922 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 08:54:03.526  6922  6922 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3867097d}
,07-27 08:54:03.526  6922  6922 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 08:54:03.536  6922  6922 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 08:54:03.556  6922  6922 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-27 08:54:03.556  6922  6922 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 08:54:03.556  6922  6922 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-27 08:54:03.576  6922  6922 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-27 08:54:03.576  6922  6922 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,07-27 08:54:03.576  6922  6922 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,07-27 08:54:03.576  6922  6922 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-27 08:54:03.576  6922  6922 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-27 08:54:03.576  6922  6922 I Adreno-EGL: Build Date: 11/19/14 Wed
07-27 08:54:03.576  6922  6922 I Adreno-EGL: Local Branch: mybranch5813579
07-27 08:54:03.576  6922  6922 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-27 08:54:03.576  6922  6922 I Adreno-EGL: Local Patches: NONE
07-27 08:54:03.576  6922  6922 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-27 08:54:03.606  6836  6836 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,07-27 08:54:03.606   754  1639 I ActivityManager: Killing 6023:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##41
,07-27 08:54:03.616  5911  6831 I SA      : [RC New] [v2liruge] api execute + 607
07-27 08:54:03.626  5911  6831 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,07-27 08:54:03.626  5911  6831 I System.out: AsyncTask #1 calls detatch()
,07-27 08:54:03.636  5911  6831 I SA      : [TPMU] getNetworkMcc : 260
,07-27 08:54:03.666  6922  6922 I NSApplication: Starting up...
,07-27 08:54:03.666  6922  6970 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-27 08:54:03.666  5911  6831 I SA      : [SCU] saveMccToPreferece Start
,07-27 08:54:03.666  5911  6831 I SA      : [SCU] RegionMCC : 260
,07-27 08:54:03.666  5911  6831 I SA      : [SSP] query invoked
,07-27 08:54:03.676  5911  6831 I SA      : [TPMU] GetMccFromDB : null
07-27 08:54:03.676  5911  6831 I SA      : [SCU] getMccFromPreferece mcc = 260
,07-27 08:54:03.676  5911  6831 I SA      : [SCU] saveMccToPreferece End
,07-27 08:54:03.676  5911  6831 I SA      : [RC New] executeRequest [v2liruge] end. 699
07-27 08:54:03.676  5911  6831 I SA      : [RC New] Execute end
,07-27 08:54:03.676  5911  5911 I SA      : [OR] GetMyCountryZoneTask mcc = 260
,07-27 08:54:03.676  5911  5911 I SA      : [OR] GetMyCountryZoneTask Success
,07-27 08:54:03.676   754  1318 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:03.676   754  1291 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:03.686   754  1703 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:03.725  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-27 08:54:03.725  6285  6348 I jxcore-log: 
,07-27 08:54:03.736   754  1657 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:03.736   754  1593 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:03.736   754  1470 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:03.736   754  1558 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:03.736   754  1580 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
07-27 08:54:03.736   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:03.736   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:03.736   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:03.736   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:03.736  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-27 08:54:03.736  6285  6348 I jxcore-log: 
,07-27 08:54:03.746  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-27 08:54:03.746  6285  6348 I jxcore-log: 
,07-27 08:54:03.776  6977  6977 E Zygote  : MountEmulatedStorage()
07-27 08:54:03.776  6977  6977 E Zygote  : v2
07-27 08:54:03.776  6977  6977 I libpersona: KNOX_SDCARD checking this for 10158
07-27 08:54:03.776  6977  6977 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:03.786   754  1580 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6977 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,07-27 08:54:03.786   754  1580 I ActivityManager: Killing 6039:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): emptyCount ##41
,07-27 08:54:03.826  6977  6977 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:03.826  6977  6977 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:54:03.826  6977  6977 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 08:54:03.846  6977  6977 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:03.846  6977  6977 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:03.866  6977  6977 D ResourcesManager: creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,07-27 08:54:03.866  6977  6977 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 08:54:03.866  6977  6977 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-27 08:54:03.866  6977  6977 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-27 08:54:03.886  6977  6977 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:54:03.886  6977  6977 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,07-27 08:54:03.886  6977  6977 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-27 08:54:03.896   754  1639 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:03.896   754  1703 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:03.896   754   783 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:54:03.906   754  1221 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:03.906  6355  6355 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 08:54:03.906  6355  6355 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 08:54:03.906  6355  6355 D SecurityLogAgent: StateMachine : Current State = 1
07-27 08:54:03.906   754  1657 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:03.906  6355  6355 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 08:54:03.906   754  1528 I ActivityManager: Killing 6054:com.samsung.helphub/1000 (adj 15): emptyCount ##41
,07-27 08:54:03.916   754  1528 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,07-27 08:54:03.916   754  1470 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:03.916   754  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:03.916   754  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:03.916   754  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:03.916   754  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:03.916   754  1558 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:03.916  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-27 08:54:03.916  6285  6348 I jxcore-log: 
,07-27 08:54:03.956  6992  6992 E Zygote  : MountEmulatedStorage()
,07-27 08:54:03.956  6992  6992 E Zygote  : v2
07-27 08:54:03.956  6992  6992 I libpersona: KNOX_SDCARD checking this for 10200
07-27 08:54:03.956  6992  6992 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:03.956   754  1528 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6992 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:03.966   754  1580 D ActivityManager: startService callerProcessName:com.sec.android.app.SmartClipService, calleePkgName: com.sec.android.app.SmartClipService
07-27 08:54:03.966   754  1580 D ActivityManager: caller:android.app.ApplicationThreadProxy@1e186af9, r.packageName :com.sec.android.app.SmartClipService
,07-27 08:54:04.006  6992  6992 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:04.006  6992  6992 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:54:04.006  6992  6992 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-27 08:54:04.026  6992  6992 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:04.026  6992  6992 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:04.036  6992  6992 D ResourcesManager: creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,07-27 08:54:04.056   754  1657 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:04.066  6152  6152 D WaitQueueForNetworkActivate: notifyNetworkActivated
,07-27 08:54:04.176   754  2987 D SSRM:n  : SIOP:: AP = 400, PST = 378, CUR = 450
,07-27 08:54:04.206   754  1451 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,07-27 08:54:04.206   754  1451 D ActivityManager: caller:android.app.ApplicationThreadProxy@36939a3e, r.packageName :com.sec.android.app.samsungapps
,07-27 08:54:04.216  6152  6152 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,07-27 08:54:04.216  6152  6152 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,07-27 08:54:04.216  6152  6152 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,07-27 08:54:04.216  6152  6152 D InitializeManagerStateMachine: exit::IDLE
07-27 08:54:04.216  6152  6152 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,07-27 08:54:04.216   754  1657 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:04.216   754  1446 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:04.216  6152  6152 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
07-27 08:54:04.216  6152  6152 D InitializeManagerStateMachine: exit::NETWORK_CHECK
07-27 08:54:04.216  6152  6152 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
07-27 08:54:04.216  6152  6152 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
07-27 08:54:04.216  6152  6152 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
07-27 08:54:04.216  6152  6152 D InitializeManagerStateMachine: entry::SUCCESS
,07-27 08:54:04.216  6152  6152 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,07-27 08:54:04.226  6152  6152 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,07-27 08:54:04.226  6152  6152 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,07-27 08:54:04.226  6152  6152 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
07-27 08:54:04.226   754  1318 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:04.236  6152  6152 D InitializeManagerStateMachine: exit::SUCCESS
07-27 08:54:04.236  6152  6152 D InitializeManagerStateMachine: entry::IDLE
,07-27 08:54:04.246   754  1291 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,07-27 08:54:04.246   754  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:04.246   754  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:04.246   754  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:54:04.246   754  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:54:04.286  7010  7010 E Zygote  : MountEmulatedStorage()
07-27 08:54:04.286  7010  7010 E Zygote  : v2
07-27 08:54:04.286  7010  7010 I libpersona: KNOX_SDCARD checking this for 10171
07-27 08:54:04.286  7010  7010 I libpersona: KNOX_SDCARD not a persona
,07-27 08:54:04.296   754  1291 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7010 uid=10171 gids={50171, 9997} abi=armeabi-v7a
,07-27 08:54:04.296   754  1291 I ActivityManager: Killing 6132:com.sec.kidsplat.installer/u0a189 (adj 15): emptyCount ##41
,07-27 08:54:04.346  7010  7010 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:54:04.346  7010  7010 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 08:54:04.346  7010  7010 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-27 08:54:04.366  7010  7010 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:54:04.366  7010  7010 D ActivityThread: Added TimaKeyStore provider
,07-27 08:54:04.376  7010  7010 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,07-27 08:54:04.386  7010  7010 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-27 08:54:04.386  7010  7010 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-27 08:54:04.396   754  1221 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,07-27 08:54:04.396   754  1221 D ActivityManager: caller:android.app.ApplicationThreadProxy@186ba5ec, r.packageName :com.android.calendar
,07-27 08:54:04.406   754  1481 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,07-27 08:54:04.406   754  1481 D ActivityManager: caller:android.app.ApplicationThreadProxy@312b1c4a, r.packageName :com.android.calendar
,07-27 08:54:04.416   754  1221 I ActivityManager: Killing 6177:flipboard.app/u0a125 (adj 15): emptyCount ##41
,07-27 08:54:04.736  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-27 08:54:04.736  6285  6348 I jxcore-log: 
,07-27 08:54:04.796  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-27 08:54:04.796  6285  6348 I jxcore-log: 
,07-27 08:54:04.796  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-27 08:54:04.796  6285  6348 I jxcore-log: 
,07-27 08:54:04.976   754  1481 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,07-27 08:54:04.976   754  1481 D ActivityManager: caller:android.app.ApplicationThreadProxy@286334d8, r.packageName :com.sec.spp.push
,07-27 08:54:04.996  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-27 08:54:04.996  6285  6348 I jxcore-log: 
,07-27 08:54:05.006   754  1703 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:05.016  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-27 08:54:05.016  6285  6348 I jxcore-log: 
,07-27 08:54:05.026  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-27 08:54:05.026  6285  6348 I jxcore-log: 
,07-27 08:54:05.026  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-27 08:54:05.026  6285  6348 I jxcore-log: 
,07-27 08:54:05.046  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-27 08:54:05.046  6285  6348 I jxcore-log: 
,07-27 08:54:05.066  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-27 08:54:05.066  6285  6348 I jxcore-log: 
,07-27 08:54:05.136  3396  3517 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,07-27 08:54:05.136  3396  3517 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,07-27 08:54:05.136  3396  3517 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,07-27 08:54:05.136  3396  3517 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,07-27 08:54:05.146  3396  3517 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,07-27 08:54:05.146  3396  3517 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,07-27 08:54:05.146  3396  3517 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,07-27 08:54:05.146  3396  3517 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,07-27 08:54:05.156  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-27 08:54:05.156  6285  6348 I jxcore-log: 
,07-27 08:54:05.156  3396  3517 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,07-27 08:54:05.156  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-27 08:54:05.156  6285  6348 I jxcore-log: 
,07-27 08:54:05.166   754  1593 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:05.166  3396  3517 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-27 08:54:05.186  6285  6348 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-27 08:54:05.186  6285  6348 I jxcore-log: 
,07-27 08:54:05.196  6285  6348 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-27 08:54:05.196  6285  6348 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-27 08:54:05.196  6285  6348 I jxcore-log: 
,07-27 08:54:05.246  6285  6348 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 08:54:05.246  6285  6348 I jxcore-log: 
,07-27 08:54:05.246  6285  6348 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 08:54:05.246  6285  6348 I jxcore-log: 
,07-27 08:54:05.246  6285  6348 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 08:54:05.246  6285  6348 I jxcore-log: 
,07-27 08:54:05.496  5802  5802 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,07-27 08:54:05.516   754  1481 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:05.516  5802  7029 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,07-27 08:54:05.556   754  1639 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:54:05.556   754  1639 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:54:05.556   754  1639 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 08:54:05.556   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:54:05.556   754  1639 D BatteryService: stay LED for fully charged
,07-27 08:54:05.556   754   754 I MotionRecognitionService: Plugged
07-27 08:54:05.556  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:54:05.556   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:54:05.556  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
07-27 08:54:05.556  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:54:05.556  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 08:54:05.556  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:54:05.556  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
07-27 08:54:05.556  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:54:05.556  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:54:05.566  5802  7029 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,07-27 08:54:05.566  5802  7029 E art     : No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
07-27 08:54:05.566  5802  7029 W PCWCLIENTTRACE_SecurePreferencesJNI: GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
07-27 08:54:05.566  5802  7029 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,07-27 08:54:05.566  5802  7029 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-27 08:54:05.566  5802  7029 I PCWCLIENTTRACE_PushUtil: sales region : global
07-27 08:54:05.566  5802  7029 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-27 08:54:05.566  5802  7029 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,07-27 08:54:05.876   754  1291 I ActivityManager: Killing 4338:com.android.vending/u0a33 (adj 15): emptyCount ##41
,07-27 08:54:06.485   308   308 E SMD     : DCD ON
,07-27 08:54:07.485  6598  6598 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
,07-27 08:54:07.735   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:08.355   754  1451 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,07-27 08:54:08.365  6922  6941 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-27 08:54:08.735   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:09.485   308   308 E SMD     : DCD ON
,07-27 08:54:09.745   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:10.745   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:11.495  6598  6598 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-27 08:54:11.495  6598  6598 I dhcpcd  : wlan0: no IPv6 Routers available
,07-27 08:54:11.745   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:12.485   308   308 E SMD     : DCD ON
,07-27 08:54:12.745   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-27 08:54:14.215   754  1318 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,07-27 08:54:14.215   754  1318 D ActivityManager: caller:android.app.ApplicationThreadProxy@942c684, r.packageName :com.sec.android.app.samsungapps
,07-27 08:54:14.245   754  2987 D SSRM:n  : SIOP:: AP = 350, PST = 371, CUR = 450
,07-27 08:54:14.255  6152  6152 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,07-27 08:54:14.255  6152  6152 D PreloadUpdateManagerStateMachine: exit::IDLE
,07-27 08:54:14.255  6152  6152 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,07-27 08:54:14.255  6152  6152 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:86400000
,07-27 08:54:14.265  6152  6152 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,07-27 08:54:14.265  6152  6152 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,07-27 08:54:14.265  6152  6152 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,07-27 08:54:14.265  6152  6152 D PreloadUpdateManagerStateMachine: entry::IDLE
,07-27 08:54:15.485   308   308 E SMD     : DCD ON
,07-27 08:54:15.615   754   785 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:54:15.625   754   785 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:54:15.625   754   785 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 08:54:15.625   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:54:15.635   754   754 I MotionRecognitionService: Plugged
,07-27 08:54:15.635   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:54:15.635  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:54:15.645  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:54:15.645   754   785 D BatteryService: stay LED for fully charged
,07-27 08:54:15.655  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:54:15.655  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:54:15.665  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:54:15.665  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:54:15.675  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:54:15.675  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:54:17.315   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:54:18.485   308   308 E SMD     : DCD ON
,07-27 08:54:20.835   754  1347 E Watchdog: !@Sync 4
,07-27 08:54:21.485   308   308 E SMD     : DCD ON
,07-27 08:54:22.745   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:23.745   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:24.295   754  2987 D SSRM:n  : SIOP:: AP = 330, PST = 361, CUR = 450
,07-27 08:54:24.345   754  2014 V SAMP_SPCM_test: CSC File load.. 
,07-27 08:54:24.375   754  2014 D ResourcesManager: creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,07-27 08:54:24.385   754  2014 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-27 08:54:24.395   754  2014 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,07-27 08:54:24.405   754  2014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,07-27 08:54:24.435   754  2014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,07-27 08:54:24.455   754  2014 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,07-27 08:54:24.485   308   308 E SMD     : DCD ON
,07-27 08:54:24.745   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:25.665   754  1446 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:54:25.665   754  1446 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:54:25.665   754  1446 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 08:54:25.675   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:54:25.675   754   754 I MotionRecognitionService: Plugged
,07-27 08:54:25.675   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:54:25.675  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:54:25.685  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:54:25.685  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:54:25.685   754  1446 D BatteryService: stay LED for fully charged
,07-27 08:54:25.685  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:54:25.695  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:54:25.695  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:54:25.695  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:54:25.695  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:54:25.745   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:26.745   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:27.485   308   308 E SMD     : DCD ON
,07-27 08:54:27.745   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-27 08:54:28.635   754  1059 I PowerManagerService: [PWL] Off : 105s ago
,07-27 08:54:30.495   308   308 E SMD     : DCD ON
,07-27 08:54:33.495   308   308 E SMD     : DCD ON
,07-27 08:54:34.345   754  2987 D SSRM:n  : SIOP:: AP = 330, PST = 353, CUR = 450
,07-27 08:54:35.725   754  1528 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:54:36.495   308   308 E SMD     : DCD ON
,07-27 08:54:37.325   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:54:39.495   308   308 E SMD     : DCD ON
,07-27 08:54:42.495   308   308 E SMD     : DCD ON
,07-27 08:54:42.755   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:43.755   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:44.395   754  2987 D SSRM:n  : SIOP:: AP = 320, PST = 350, CUR = 450
,07-27 08:54:44.755   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:45.495   308   308 E SMD     : DCD ON
,07-27 08:54:45.755   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:45.785   754   783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:54:45.795   754   783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:54:45.795   754   783 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 08:54:45.795   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:54:45.795  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:54:45.805  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:54:45.805   754   754 I MotionRecognitionService: Plugged
,07-27 08:54:45.805   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:54:45.805  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:54:45.805  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:54:45.805   754   783 D BatteryService: stay LED for fully charged
,07-27 08:54:45.815  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:54:45.815  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:54:45.815  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:54:45.815  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:54:46.755   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:54:47.755   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-27 08:54:48.495   308   308 E SMD     : DCD ON
,07-27 08:54:50.835   754  1347 E Watchdog: !@Sync 5
,07-27 08:54:51.495   308   308 E SMD     : DCD ON
,07-27 08:54:54.435   754  2987 D SSRM:n  : SIOP:: AP = 320, PST = 347, CUR = 450
,07-27 08:54:54.495   308   308 E SMD     : DCD ON
,07-27 08:54:55.845   754  1528 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:54:57.325   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:54:57.495   308   308 E SMD     : DCD ON
,07-27 08:54:59.995   754  1111 V AlarmManager: waitForAlarm result :8
,07-27 08:55:00.495   308   308 E SMD     : DCD ON
,07-27 08:55:03.495   308   308 E SMD     : DCD ON
,07-27 08:55:03.645   754  1059 I PowerManagerService: [PWL] Off : 140s ago
,07-27 08:55:04.485   754  2987 D SSRM:n  : SIOP:: AP = 320, PST = 341, CUR = 450
,07-27 08:55:05.905   754  1580 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:55:06.505   308   308 E SMD     : DCD ON
,07-27 08:55:07.755   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:55:08.755   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:55:09.505   308   308 E SMD     : DCD ON
,07-27 08:55:09.755   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:55:10.765   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:55:11.765   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:55:12.505   308   308 E SMD     : DCD ON
,07-27 08:55:12.765   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-27 08:55:14.535   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 338, CUR = 450
,07-27 08:55:15.505   308   308 E SMD     : DCD ON
,07-27 08:55:17.325   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:55:18.505   308   308 E SMD     : DCD ON
,07-27 08:55:20.835   754  1347 E Watchdog: !@Sync 6
,07-27 08:55:21.505   308   308 E SMD     : DCD ON
,07-27 08:55:21.525   754  1111 V AlarmManager: waitForAlarm result :4
,07-27 08:55:21.545   754   754 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,07-27 08:55:21.545   754   754 V AlarmManagerEXT: <AppSync3 Whitelist>
,07-27 08:55:21.555   754   754 V AlarmManagerEXT: (AppSync) ### 0 added ###
,07-27 08:55:21.555  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 08:55:21.555  1197  1197 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:55:21.565  1197  1197 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-27 08:55:21.565  1197  1197 I KeyguardEffectViewController: *** don't update sliding image ***
,07-27 08:55:21.575   754  1639 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:55:21.575   754  1639 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:55:21.575   754  1639 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 08:55:21.575   754  1639 D BatteryService: stay LED for fully charged
,07-27 08:55:21.605   754  1318 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:55:21.615   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:55:21.625  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:55:21.635  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:55:21.635  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
07-27 08:55:21.635  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:55:21.635  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:55:21.635  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:55:21.635  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:55:21.635  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
07-27 08:55:21.635   754   754 I MotionRecognitionService: Plugged
07-27 08:55:21.635   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:55:21.675   754  1291 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-27 08:55:21.675   754  1291 D ActivityManager: caller:android.app.ApplicationThreadProxy@10b00dc6, r.packageName :com.google.android.gms
,07-27 08:55:21.715  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 08:55:21.735  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 08:55:21.785  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 08:55:21.785  1197  1197 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:55:21.785  1197  1197 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-27 08:55:21.785  1197  1197 I KeyguardEffectViewController: *** don't update sliding image ***
,07-27 08:55:21.835  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 08:55:21.845  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 08:55:24.505   308   308 E SMD     : DCD ON
,07-27 08:55:24.575   754  2987 D SSRM:n  : SIOP:: AP = 320, PST = 336, CUR = 450
,07-27 08:55:27.505   308   308 E SMD     : DCD ON,
,07-27 08:55:30.505   308   308 E SMD     : DCD ON
,07-27 08:55:31.635   754  1657 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:55:31.645   754  1657 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:55:31.645   754  1657 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 08:55:31.645   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:55:31.655  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:55:31.655  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:55:31.665  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:55:31.665  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:55:31.665   754   754 I MotionRecognitionService: Plugged
07-27 08:55:31.665   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:55:31.665  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:55:31.665  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:55:31.665  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:55:31.665  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:55:31.665   754  1657 D BatteryService: stay LED for fully charged
,07-27 08:55:33.135   297   297 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6b01090
,07-27 08:55:33.135   297   297 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: R/W request received
07-27 08:55:33.135   297   297 I rmt_storage: wakelock acquired: 1, error no: 42
,07-27 08:55:33.135   297   679 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229454592)
,07-27 08:55:33.235   297   679 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Bytes written = 1572864
07-27 08:55:33.235   297   679 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Send response: res=0 err=0
07-27 08:55:33.235   297   679 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229454592) wakelock released: 1, error no: 0
07-27 08:55:33.235   297   679 I rmt_storage: 
,07-27 08:55:33.245   297   297 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6b01090
,07-27 08:55:33.505   308   308 E SMD     : DCD ON
,07-27 08:55:34.625   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 331, CUR = 450
,07-27 08:55:36.505   308   308 E SMD     : DCD ON
,07-27 08:55:37.335   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:55:37.765   360   360 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-27 08:55:37.765   360   360 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-27 08:55:39.505   308   308 E SMD     : DCD ON
,07-27 08:55:41.695   754  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:55:41.695   754  1481 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:55:41.695   754  1481 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 08:55:41.705   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:55:41.705  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:55:41.715  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:55:41.715   754   754 I MotionRecognitionService: Plugged
,07-27 08:55:41.715   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:55:41.715   754  1481 D BatteryService: stay LED for fully charged
,07-27 08:55:41.725  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:55:41.735  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:55:41.735  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:55:41.745  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:55:41.745  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:55:41.755  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:55:42.505   308   308 E SMD     : DCD ON
,07-27 08:55:43.645   754  1059 I PowerManagerService: [PWL] Off : 180s ago
,07-27 08:55:44.675   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 322, CUR = 450
,07-27 08:55:45.515   308   308 E SMD     : DCD ON
,07-27 08:55:47.765   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:55:48.515   308   308 E SMD     : DCD ON
,07-27 08:55:48.765   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:55:49.765   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:55:50.765   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:55:50.835   754  1347 E Watchdog: !@Sync 7
,07-27 08:55:51.515   308   308 E SMD     : DCD ON
,07-27 08:55:51.755   754  1580 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:55:51.755   754  1580 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:55:51.755   754  1580 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 08:55:51.755   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:55:51.765  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:55:51.765  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:55:51.765   754   754 I MotionRecognitionService: Plugged
,07-27 08:55:51.775   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:55:51.775  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:55:51.775   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:55:51.775   754  1580 D BatteryService: stay LED for fully charged
,07-27 08:55:51.785  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:55:51.785  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:55:51.795  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:55:51.795  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:55:51.795  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:55:52.775   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-27 08:55:54.515   308   308 E SMD     : DCD ON
,07-27 08:55:54.725   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 318, CUR = 450
,07-27 08:55:57.335   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:55:57.515   308   308 E SMD     : DCD ON
,07-27 08:55:57.775   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:55:58.775   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:55:59.775   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:55:59.995   754  1111 V AlarmManager: waitForAlarm result :8
,07-27 08:56:00.515   308   308 E SMD     : DCD ON
,07-27 08:56:00.775   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:56:01.775   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:56:01.815   754  1221 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:56:01.815   754  1221 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:56:01.825   754  1221 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 08:56:01.825   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:56:01.835  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:56:01.835  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:56:01.835  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:56:01.835   754   754 I MotionRecognitionService: Plugged
,07-27 08:56:01.845   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:56:01.845  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:01.845  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:56:01.845   754  1221 D BatteryService: stay LED for fully charged
,07-27 08:56:01.845  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:56:01.845  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:56:01.855  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:02.775   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-27 08:56:03.515   308   308 E SMD     : DCD ON
,07-27 08:56:04.765   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 450
,07-27 08:56:06.515   308   308 E SMD     : DCD ON
,07-27 08:56:09.515   308   308 E SMD     : DCD ON
,07-27 08:56:11.875   754  1593 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:56:11.875   754  1593 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:56:11.875   754  1593 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 08:56:11.885   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:56:11.885  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:56:11.895  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:56:11.895   754   754 I MotionRecognitionService: Plugged
,07-27 08:56:11.895   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:56:11.905   754  1593 D BatteryService: stay LED for fully charged
,07-27 08:56:11.905  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:56:11.915  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:11.915  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:56:11.915  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:56:11.925  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:11.925  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:12.525   308   308 E SMD     : DCD ON
,07-27 08:56:12.775   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:56:13.785   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:56:14.785   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:56:14.825   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 450
,07-27 08:56:15.525   308   308 E SMD     : DCD ON
,07-27 08:56:15.785   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:56:16.785   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:56:17.345   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:56:17.785   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-27 08:56:18.525   308   308 E SMD     : DCD ON
,07-27 08:56:20.845   754  1347 E Watchdog: !@Sync 8
,07-27 08:56:21.525   308   308 E SMD     : DCD ON
,07-27 08:56:21.935   754  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:56:21.935   754  1470 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:56:21.935   754  1470 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 08:56:21.945   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:56:21.945  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:56:21.955  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:56:21.955   754   754 I MotionRecognitionService: Plugged
07-27 08:56:21.955   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:56:21.955   754  1470 D BatteryService: stay LED for fully charged
,07-27 08:56:21.955  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:56:21.965  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:56:21.965  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:56:21.975  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:21.975  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:56:21.975  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:24.525   308   308 E SMD     : DCD ON
,07-27 08:56:24.875   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 450
,07-27 08:56:27.525   308   308 E SMD     : DCD ON
,07-27 08:56:28.645   754  1059 I PowerManagerService: [PWL] Off : 225s ago
,07-27 08:56:30.525   308   308 E SMD     : DCD ON
,07-27 08:56:31.995   754  1318 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:56:32.785   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:56:33.525   308   308 E SMD     : DCD ON
,07-27 08:56:33.785   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:56:34.785   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:56:34.915   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 450
,07-27 08:56:35.785   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:56:36.525   308   308 E SMD     : DCD ON
,07-27 08:56:36.795   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:56:37.345   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:56:37.795   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-27 08:56:39.525   308   308 E SMD     : DCD ON
,07-27 08:56:42.055   754  1446 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:56:42.065   754  1446 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:56:42.065   754  1446 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 08:56:42.065   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:56:42.075   754   754 I MotionRecognitionService: Plugged
,07-27 08:56:42.075  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:56:42.075  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:56:42.085  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:56:42.085   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:56:42.085  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:42.085  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:56:42.085  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:56:42.085  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:42.085   754  1446 D BatteryService: stay LED for fully charged
,07-27 08:56:42.105  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:42.525   308   308 E SMD     : DCD ON
,07-27 08:56:44.965   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,07-27 08:56:45.525   308   308 E SMD     : DCD ON
,07-27 08:56:48.535   308   308 E SMD     : DCD ON
,07-27 08:56:50.845   754  1347 E Watchdog: !@Sync 9
,07-27 08:56:51.535   308   308 E SMD     : DCD ON
,07-27 08:56:52.125   754  1291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:56:52.125   754  1291 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:56:52.125   754  1291 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 08:56:52.135   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:56:52.135   754   754 I MotionRecognitionService: Plugged
,07-27 08:56:52.135   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:56:52.135  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:56:52.145  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:56:52.145   754  1291 D BatteryService: stay LED for fully charged
,07-27 08:56:52.145  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:56:52.155  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:56:52.155  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:56:52.155  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:52.175  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:52.175  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:56:54.535   308   308 E SMD     : DCD ON
,07-27 08:56:55.025   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,07-27 08:56:57.355   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:56:57.535   308   308 E SMD     : DCD ON
,07-27 08:56:57.795   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:56:58.795   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:56:59.795   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:57:00.535   308   308 E SMD     : DCD ON
,07-27 08:57:00.795   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:57:01.795   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:57:02.185   754   785 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:57:02.185   754   785 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:57:02.185   754   785 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 08:57:02.195   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:57:02.195   754   754 I MotionRecognitionService: Plugged
,07-27 08:57:02.195   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:57:02.205  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:57:02.205  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:57:02.205  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:57:02.205  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:57:02.205  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:02.205   754   785 D BatteryService: stay LED for fully charged
,07-27 08:57:02.215  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:02.215  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:57:02.215  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:02.795   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-27 08:57:03.535   308   308 E SMD     : DCD ON
,07-27 08:57:05.065   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-27 08:57:06.535   308   308 E SMD     : DCD ON
,07-27 08:57:09.535   308   308 E SMD     : DCD ON
,07-27 08:57:12.245   754  1291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:57:12.535   308   308 E SMD     : DCD ON
,07-27 08:57:15.115   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450
,07-27 08:57:15.535   308   308 E SMD     : DCD ON
,07-27 08:57:17.355   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:57:18.065   754  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 08:57:18.065   754  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 08:57:18.075   754  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 08:57:18.095   754  1100 I TLC_TIMA_PKM_initialize: initializing...
,07-27 08:57:18.095   754  1100 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
07-27 08:57:18.095   754  1100 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
07-27 08:57:18.095   754  1100 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
07-27 08:57:18.095   754  1100 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
07-27 08:57:18.095   754  1100 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-27 08:57:18.095   754  1100 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
07-27 08:57:18.095   754  1100 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
07-27 08:57:18.095   754  1100 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
07-27 08:57:18.095   754  1100 D QSEECOMAPI: : App is not loaded in QSEE
,07-27 08:57:18.115   754  1100 D QSEECOMAPI: : Loaded image: APP id = 2
,07-27 08:57:18.125   754  1100 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-27 08:57:18.135   754  1100 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-27 08:57:18.535   308   308 E SMD     : DCD ON
,07-27 08:57:18.645   754  1059 I PowerManagerService: [PWL] Off : 275s ago
,07-27 08:57:18.655   754  1059 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,07-27 08:57:18.655   754  1059 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,07-27 08:57:18.655   754  1059 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=754, ws=null) (elapsedTime=582),
,07-27 08:57:20.845   754  1347 E Watchdog: !@Sync 10
,07-27 08:57:20.975   754  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 08:57:20.975   754  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 08:57:20.985   754  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 08:57:20.995   754  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 08:57:21.535   308   308 E SMD     : DCD ON
,07-27 08:57:22.305   754  1446 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:57:24.545   308   308 E SMD     : DCD ON
,07-27 08:57:25.165   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 309, CUR = 450
,07-27 08:57:27.545   308   308 E SMD     : DCD ON
,07-27 08:57:27.795   360   360 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-27 08:57:27.795   360   360 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-27 08:57:30.545   308   308 E SMD     : DCD ON
,07-27 08:57:33.545   308   308 E SMD     : DCD ON
,07-27 08:57:35.215   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450
,07-27 08:57:36.525   754  1111 V AlarmManager: waitForAlarm result :4
,07-27 08:57:36.545   308   308 E SMD     : DCD ON
,07-27 08:57:36.555   754  1008 D ActivityManager: startProcessLocked calleePkgName: com.blurb.checkout, hostingType: broadcast
,07-27 08:57:36.555   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:57:36.555   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:57:36.555   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 08:57:36.555   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 08:57:36.585   754  1318 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:57:36.585   754  1318 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 08:57:36.585   754  1318 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 08:57:36.585   754  1318 D BatteryService: stay LED for fully charged
,07-27 08:57:36.625   754  1008 I ActivityManager: Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7087 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 08:57:36.625   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:57:36.635  7087  7087 E Zygote  : MountEmulatedStorage()
,07-27 08:57:36.635  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-27 08:57:36.635  1197  1197 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:57:36.645  1197  1197 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-27 08:57:36.645  7087  7087 E Zygote  : v2
,07-27 08:57:36.645  7087  7087 I libpersona: KNOX_SDCARD checking this for 10096
07-27 08:57:36.645  7087  7087 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:36.645  1197  1197 I KeyguardEffectViewController: *** don't update sliding image ***
,07-27 08:57:36.655   754   754 I MotionRecognitionService: Plugged
,07-27 08:57:36.655   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:57:36.675  7087  7087 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 08:57:36.675  7087  7087 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 08:57:36.675  7087  7087 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-27 08:57:36.675  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:57:36.675  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:57:36.685  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:57:36.685  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:57:36.685  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:36.685  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:36.685  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:57:36.685  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:57:36.715  7087  7087 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:57:36.715  7087  7087 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:36.725  7087  7087 D ResourcesManager: creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,07-27 08:57:36.735  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 08:57:36.745  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 08:57:36.755   754  1481 D ActivityManager: startService callerProcessName:com.blurb.checkout, calleePkgName: com.blurb.checkout
,07-27 08:57:36.755   754  1481 D ActivityManager: caller:android.app.ApplicationThreadProxy@2f8f4052, r.packageName :com.blurb.checkout
,07-27 08:57:36.795   754  1528 I ActivityManager: Killing 6478:com.sec.android.provider.badge/u0a92 (adj 15): emptyCount ##41
,07-27 08:57:37.355   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:57:39.545   308   308 E SMD     : DCD ON
,07-27 08:57:42.545   308   308 E SMD     : DCD ON
,07-27 08:57:42.795   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:57:43.805   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:57:44.805   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:57:45.255   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450
,07-27 08:57:45.545   308   308 E SMD     : DCD ON
,07-27 08:57:45.805   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:57:46.645   754  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:57:46.655   754  1451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:57:46.655   754  1451 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 08:57:46.655   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:57:46.655   754   754 I MotionRecognitionService: Plugged
,07-27 08:57:46.655   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:57:46.665  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:57:46.665  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:57:46.665   754  1451 D BatteryService: stay LED for fully charged
,07-27 08:57:46.665  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:57:46.675  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:57:46.675  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:46.675  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:46.675  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:57:46.675  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:57:46.805   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:57:47.805   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-27 08:57:48.545   308   308 E SMD     : DCD ON
,07-27 08:57:50.855   754  1347 E Watchdog: !@Sync 11
,07-27 08:57:51.545   308   308 E SMD     : DCD ON
,07-27 08:57:52.805   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:57:53.805   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:57:54.555   308   308 E SMD     : DCD ON
,07-27 08:57:54.805   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:57:55.345   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450
,07-27 08:57:55.805   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:57:56.705   754  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:57:56.715   754  1481 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
07-27 08:57:56.715   754  1481 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 08:57:56.715   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:57:56.715   754   754 I MotionRecognitionService: Plugged
,07-27 08:57:56.715   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:57:56.725  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:57:56.725  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:57:56.725  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:57:56.725  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:57:56.725   754  1481 D BatteryService: stay LED for fully charged
,07-27 08:57:56.725  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:57:56.735  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:56.735  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-27 08:57:56.735  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:56.805   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:57:57.365   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:57:57.555   308   308 E SMD     : DCD ON
,07-27 08:57:57.815   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-27 08:57:59.995   754  1111 V AlarmManager: waitForAlarm result :8
,07-27 08:58:00.555   308   308 E SMD     : DCD ON
,07-27 08:58:03.555   308   308 E SMD     : DCD ON
,07-27 08:58:05.395   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450
,07-27 08:58:06.555   308   308 E SMD     : DCD ON
,07-27 08:58:06.765   754  1318 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:58:06.775   754  1318 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:58:06.775   754  1318 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 08:58:06.775   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:58:06.775   754   754 I MotionRecognitionService: Plugged
,07-27 08:58:06.775   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:58:06.785  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:58:06.785  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:58:06.785   754  1318 D BatteryService: stay LED for fully charged
,07-27 08:58:06.785  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:06.785  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:58:06.785  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:58:06.795  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:06.795  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:06.795  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:58:07.815   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:58:08.815   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:58:09.555   308   308 E SMD     : DCD ON
,07-27 08:58:09.815   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:58:10.815   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:58:11.815   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:58:12.555   308   308 E SMD     : DCD ON
,07-27 08:58:12.815   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-27 08:58:13.655   754  1059 I PowerManagerService: [PWL] Off : 330s ago
,07-27 08:58:15.445   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450
,07-27 08:58:15.555   308   308 E SMD     : DCD ON
,07-27 08:58:16.825   754  1703 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:58:16.835   754  1703 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:58:16.835   754  1703 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 08:58:16.835   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:58:16.835   754   754 I MotionRecognitionService: Plugged
,07-27 08:58:16.835   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:58:16.835  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:58:16.845  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:58:16.845  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:58:16.845  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:58:16.845   754  1703 D BatteryService: stay LED for fully charged
,07-27 08:58:16.845  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:16.855  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:16.855  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:16.855  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:58:17.365   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:58:18.555   308   308 E SMD     : DCD ON
,07-27 08:58:20.855   754  1347 E Watchdog: !@Sync 12
,07-27 08:58:21.555   308   308 E SMD     : DCD ON
,07-27 08:58:24.555   308   308 E SMD     : DCD ON
,07-27 08:58:25.485   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,07-27 08:58:26.885   754  1528 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:58:26.885   754  1528 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:58:26.895   754  1528 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 08:58:26.895   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:58:26.895   754   754 I MotionRecognitionService: Plugged
,07-27 08:58:26.895  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:58:26.895   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:58:26.895  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:58:26.905  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:58:26.905  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:58:26.905  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:58:26.905   754  1528 D BatteryService: stay LED for fully charged
,07-27 08:58:26.915  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:26.915  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:58:26.915  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:27.555   308   308 E SMD     : DCD ON
,07-27 08:58:27.815   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:58:28.815   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:58:29.825   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:58:30.555   308   308 E SMD     : DCD ON
,07-27 08:58:30.825   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:58:31.825   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:58:32.825   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-27 08:58:33.565   308   308 E SMD     : DCD ON
,07-27 08:58:35.535   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-27 08:58:36.565   308   308 E SMD     : DCD ON
,07-27 08:58:36.945   754  1657 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:58:36.945   754  1657 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:58:36.955   754  1657 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 08:58:36.955   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:58:36.955   754   754 I MotionRecognitionService: Plugged
,07-27 08:58:36.955  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:58:36.955  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:58:36.965  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:58:36.965   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:58:36.965  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:36.965   754  1657 D BatteryService: stay LED for fully charged
,07-27 08:58:36.965  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:58:36.965  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:58:36.975  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:36.975  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:37.375   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:58:39.565   308   308 E SMD     : DCD ON
,07-27 08:58:42.565   308   308 E SMD     : DCD ON
,07-27 08:58:45.565   308   308 E SMD     : DCD ON
,07-27 08:58:45.615   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-27 08:58:47.005   754  1558 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:58:48.565   308   308 E SMD     : DCD ON
,07-27 08:58:50.855   754  1347 E Watchdog: !@Sync 13
,07-27 08:58:51.565   308   308 E SMD     : DCD ON
,07-27 08:58:52.825   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:58:53.825   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:58:54.565   308   308 E SMD     : DCD ON
,07-27 08:58:54.825   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:58:55.655   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-27 08:58:55.825   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:58:56.825   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:58:57.065   754  1703 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:58:57.375   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:58:57.565   308   308 E SMD     : DCD ON
,07-27 08:58:57.825   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-27 08:59:00.565   308   308 E SMD     : DCD ON
,07-27 08:59:03.565   308   308 E SMD     : DCD ON
,07-27 08:59:05.705   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 08:59:06.565   308   308 E SMD     : DCD ON
,07-27 08:59:07.125   754  1291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:59:09.565   308   308 E SMD     : DCD ON
,07-27 08:59:12.575   308   308 E SMD     : DCD ON
,07-27 08:59:13.665   754  1059 I PowerManagerService: [PWL] Off : 390s ago
,07-27 08:59:15.575   308   308 E SMD     : DCD ON
,07-27 08:59:15.755   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 08:59:17.185   754  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:59:17.195   754  1470 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:59:17.195   754  1470 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 08:59:17.195   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:59:17.195   754   754 I MotionRecognitionService: Plugged
,07-27 08:59:17.195  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:59:17.195  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:59:17.205   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:59:17.205  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:59:17.205   754  1470 D BatteryService: stay LED for fully charged
,07-27 08:59:17.205  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:17.205  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:17.215  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 08:59:17.215  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:59:17.215  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:17.375   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:59:18.575   308   308 E SMD     : DCD ON
,07-27 08:59:20.865   754  1347 E Watchdog: !@Sync 14
,07-27 08:59:21.575   308   308 E SMD     : DCD ON
,07-27 08:59:22.825   360   360 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-27 08:59:22.825   360   360 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-27 08:59:24.575   308   308 E SMD     : DCD ON
,07-27 08:59:25.795   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 08:59:27.245   754  1593 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:59:27.255   754  1593 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:59:27.255   754  1593 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 08:59:27.255   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:59:27.255   754   754 I MotionRecognitionService: Plugged
,07-27 08:59:27.255  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:59:27.265  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:59:27.265   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:59:27.265   754  1593 D BatteryService: stay LED for fully charged
,07-27 08:59:27.265  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:59:27.265  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:27.265  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:59:27.275  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:59:27.275  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:27.275  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:27.575   308   308 E SMD     : DCD ON
,07-27 08:59:30.575   308   308 E SMD     : DCD ON
,07-27 08:59:33.575   308   308 E SMD     : DCD ON
,07-27 08:59:35.845   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 08:59:36.575   308   308 E SMD     : DCD ON
,07-27 08:59:37.305   754   783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:59:37.315   754   783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:59:37.315   754   783 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 08:59:37.315   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:59:37.315   754   754 I MotionRecognitionService: Plugged
,07-27 08:59:37.315   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:59:37.315  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:59:37.325  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:59:37.325   754   783 D BatteryService: stay LED for fully charged
,07-27 08:59:37.325  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:59:37.325  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:37.325  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:37.325  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:59:37.335  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:59:37.335  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:37.375   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:59:39.575   308   308 E SMD     : DCD ON
,07-27 08:59:42.575   308   308 E SMD     : DCD ON
,07-27 08:59:42.835   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:59:43.835   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:59:44.835   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:59:45.575   308   308 E SMD     : DCD ON
,07-27 08:59:45.835   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:59:45.895   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 08:59:46.835   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:59:47.365   754  1318 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:59:47.365   754  1318 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:59:47.375   754  1318 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 08:59:47.375   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:59:47.375   754   754 I MotionRecognitionService: Plugged
,07-27 08:59:47.375   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:59:47.375  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:59:47.385  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:59:47.385  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:59:47.385  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:59:47.385  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:59:47.385   754  1318 D BatteryService: stay LED for fully charged
07-27 08:59:47.385  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:47.395  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:47.395  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:47.835   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-27 08:59:48.585   308   308 E SMD     : DCD ON
,07-27 08:59:50.865   754  1347 E Watchdog: !@Sync 15
,07-27 08:59:51.585   308   308 E SMD     : DCD ON
,07-27 08:59:52.835   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:59:53.835   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:59:54.585   308   308 E SMD     : DCD ON
,07-27 08:59:54.835   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:59:55.845   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:59:55.945   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 08:59:56.845   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 08:59:57.375   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:59:57.425   754  1703 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:59:57.435   754  1703 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 08:59:57.435   754  1703 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 08:59:57.435   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:59:57.435   754   754 I MotionRecognitionService: Plugged
,07-27 08:59:57.435   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 08:59:57.435  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:59:57.445  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 08:59:57.445   754  1703 D BatteryService: stay LED for fully charged
,07-27 08:59:57.445  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:59:57.445  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:57.445  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 08:59:57.445  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 08:59:57.455  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:57.455  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:57.585   308   308 E SMD     : DCD ON
,07-27 08:59:57.845   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-27 09:00:00.585   308   308 E SMD     : DCD ON
,07-27 09:00:03.585   308   308 E SMD     : DCD ON
,07-27 09:00:05.985   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:00:06.585   308   308 E SMD     : DCD ON
,07-27 09:00:07.485   754  1528 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:00:07.495   754  1528 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:00:07.495   754  1528 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 09:00:07.495   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:00:07.495   754   754 I MotionRecognitionService: Plugged
,07-27 09:00:07.495   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:00:07.495  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:00:07.505  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:00:07.505  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:00:07.505  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:00:07.505  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:00:07.505  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:00:07.505   754  1528 D BatteryService: stay LED for fully charged
,07-27 09:00:07.515  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:07.515  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:07.845   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:00:08.845   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:00:09.135   355   355 I bootchecker: bootchecker wake up!!
,07-27 09:00:09.585   308   308 E SMD     : DCD ON
,07-27 09:00:09.845   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:00:10.845   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:00:11.845   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:00:12.585   308   308 E SMD     : DCD ON
,07-27 09:00:12.845   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-27 09:00:15.585   308   308 E SMD     : DCD ON
,07-27 09:00:16.035   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:00:17.385   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:00:17.545   754  1657 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:00:17.555   754  1657 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:00:17.555   754  1657 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 09:00:17.555   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:00:17.555   754   754 I MotionRecognitionService: Plugged
,07-27 09:00:17.555   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:00:17.565  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:00:17.565  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:00:17.565  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:00:17.565   754  1657 D BatteryService: stay LED for fully charged
,07-27 09:00:17.565  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:00:17.565  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:00:17.575  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:00:17.575  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:17.575  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:18.585   308   308 E SMD     : DCD ON
,07-27 09:00:18.665   754  1059 I PowerManagerService: [PWL] Off : 455s ago
,07-27 09:00:20.865   754  1347 E Watchdog: !@Sync 16
,07-27 09:00:21.585   308   308 E SMD     : DCD ON
,07-27 09:00:24.585   308   308 E SMD     : DCD ON
,07-27 09:00:26.085   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:00:27.595   308   308 E SMD     : DCD ON
,07-27 09:00:27.605   754  1639 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:00:27.615   754  1639 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:00:27.615   754  1639 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 09:00:27.615   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:00:27.615   754   754 I MotionRecognitionService: Plugged
,07-27 09:00:27.615   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:00:27.615  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:00:27.625  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:00:27.625  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:00:27.625  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:00:27.625  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:00:27.625  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:27.635   754  1639 D BatteryService: stay LED for fully charged
,07-27 09:00:27.635  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:27.635  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:27.845   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:00:28.855   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:00:29.855   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:00:30.595   308   308 E SMD     : DCD ON
,07-27 09:00:30.855   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:00:31.855   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:00:32.855   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-27 09:00:33.595   308   308 E SMD     : DCD ON
,07-27 09:00:36.135   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:00:36.595   308   308 E SMD     : DCD ON
,07-27 09:00:37.385   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:00:37.665   754  1580 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:00:39.595   308   308 E SMD     : DCD ON
,07-27 09:00:42.595   308   308 E SMD     : DCD ON
,07-27 09:00:45.595   308   308 E SMD     : DCD ON
,07-27 09:00:46.205   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:00:47.725   754  1528 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:00:48.595   308   308 E SMD     : DCD ON
,07-27 09:00:50.875   754  1347 E Watchdog: !@Sync 17
,07-27 09:00:51.595   308   308 E SMD     : DCD ON
,07-27 09:00:52.855   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:00:53.855   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:00:54.595   308   308 E SMD     : DCD ON
,07-27 09:00:54.855   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:00:55.855   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:00:56.285   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:00:56.865   360   360 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:00:57.385   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:00:57.595   308   308 E SMD     : DCD ON
,07-27 09:00:57.785   754  1446 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:00:57.865   360   360 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-27 09:01:00.595   308   308 E SMD     : DCD ON
,07-27 09:01:03.605   308   308 E SMD     : DCD ON
,07-27 09:01:06.335   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:01:06.605   308   308 E SMD     : DCD ON
,07-27 09:01:07.845   754  1291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:01:07.845   754  1291 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:01:07.855   754  1291 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:01:07.855   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:01:07.855   754   754 I MotionRecognitionService: Plugged
,07-27 09:01:07.855  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:01:07.855  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:01:07.855   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:01:07.865  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:01:07.865  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:01:07.865  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:01:07.865   754  1291 D BatteryService: stay LED for fully charged
07-27 09:01:07.865  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:07.875  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:07.885  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:09.605   308   308 E SMD     : DCD ON
,07-27 09:01:12.605   308   308 E SMD     : DCD ON
,07-27 09:01:15.605   308   308 E SMD     : DCD ON
,07-27 09:01:16.375   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:01:17.395   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:01:17.905   754   783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:01:17.915   754   783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:01:17.915   754   783 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 09:01:17.915   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:01:17.915   754   754 I MotionRecognitionService: Plugged
,07-27 09:01:17.915   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:01:17.925  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:01:17.925  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:01:17.925  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
07-27 09:01:17.925   754   783 D BatteryService: stay LED for fully charged
,07-27 09:01:17.925  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:17.925  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:01:17.935  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:01:17.935  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:17.935  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:18.605   308   308 E SMD     : DCD ON
,07-27 09:01:20.875   754  1347 E Watchdog: !@Sync 18
,07-27 09:01:21.605   308   308 E SMD     : DCD ON
,07-27 09:01:22.865   360   360 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-27 09:01:22.865   360   360 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-27 09:01:24.605   308   308 E SMD     : DCD ON
,07-27 09:01:26.455   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:01:27.605   308   308 E SMD     : DCD ON
,07-27 09:01:27.965   754  1318 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:01:27.965   754  1318 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:01:27.975   754  1318 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 09:01:27.975   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:01:27.975   754   754 I MotionRecognitionService: Plugged
,07-27 09:01:27.975   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:01:27.975  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:01:27.985  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:01:27.985  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:01:27.985   754  1318 D BatteryService: stay LED for fully charged
07-27 09:01:27.985  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:27.985  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:01:27.985  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:01:27.995  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:01:27.995  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:28.665   754  1059 I PowerManagerService: [PWL] Off : 525s ago
,07-27 09:01:30.605   308   308 E SMD     : DCD ON
,07-27 09:01:33.605   308   308 E SMD     : DCD ON
,07-27 09:01:36.505   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:01:36.605   308   308 E SMD     : DCD ON
,07-27 09:01:37.395   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:01:38.025   754  1703 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:01:38.025   754  1703 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:01:38.035   754  1703 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 09:01:38.035   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:01:38.035   754   754 I MotionRecognitionService: Plugged
,07-27 09:01:38.035   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:01:38.035  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:01:38.045  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:01:38.045  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:01:38.045  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:01:38.045  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:01:38.045   754  1703 D BatteryService: stay LED for fully charged
,07-27 09:01:38.045  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:38.055  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:38.055  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:39.615   308   308 E SMD     : DCD ON
,07-27 09:01:42.615   308   308 E SMD     : DCD ON
,07-27 09:01:45.615   308   308 E SMD     : DCD ON
,07-27 09:01:46.545   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:01:47.875   360   360 I Atfwd_Daemon: Stop the daemon....
,07-27 09:01:48.085   754  1528 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:01:48.085   754  1528 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:01:48.085   754  1528 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:01:48.095   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:01:48.095   754   754 I MotionRecognitionService: Plugged
,07-27 09:01:48.095   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:01:48.095  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:01:48.105  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:01:48.105  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:01:48.105  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:01:48.105  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:01:48.105  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:48.105   754  1528 D BatteryService: stay LED for fully charged
07-27 09:01:48.105  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:48.115  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:48.615   308   308 E SMD     : DCD ON
,07-27 09:01:50.875   754  1347 E Watchdog: !@Sync 19
,07-27 09:01:51.615   308   308 E SMD     : DCD ON
,07-27 09:01:54.615   308   308 E SMD     : DCD ON
,07-27 09:01:56.615   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:01:57.405   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:01:57.615   308   308 E SMD     : DCD ON
,07-27 09:01:58.145   754  1657 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:02:00.615   308   308 E SMD     : DCD ON
,07-27 09:02:03.615   308   308 E SMD     : DCD ON
,07-27 09:02:06.615   308   308 E SMD     : DCD ON
,07-27 09:02:06.665   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:02:08.205   754  1318 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:02:09.615   308   308 E SMD     : DCD ON
,07-27 09:02:12.615   308   308 E SMD     : DCD ON
,07-27 09:02:15.615   308   308 E SMD     : DCD ON
,07-27 09:02:16.715   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:02:17.405   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:02:18.065   754  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 09:02:18.065   754  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:02:18.065   754  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:02:18.275   754   783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:02:18.275   754   783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 09:02:18.275   754   783 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:02:18.275   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:02:18.285  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:02:18.285  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
07-27 09:02:18.285   754   754 I MotionRecognitionService: Plugged
,07-27 09:02:18.285   754   754 I MotionRecognitionService: setPowerConnected  = true
07-27 09:02:18.285   754   783 D BatteryService: stay LED for fully charged
,07-27 09:02:18.285  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:02:18.305  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:18.305  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:02:18.305  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:02:18.305  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:18.305  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:18.625   308   308 E SMD     : DCD ON
,07-27 09:02:20.875   754  1347 E Watchdog: !@Sync 20
,07-27 09:02:21.015   754  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 09:02:21.015   754  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:02:21.025   754  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:02:21.035   754  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:02:21.625   308   308 E SMD     : DCD ON
,07-27 09:02:24.625   308   308 E SMD     : DCD ON
,07-27 09:02:26.755   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:02:27.625   308   308 E SMD     : DCD ON
,07-27 09:02:28.335   754  1558 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:02:28.335   754  1558 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 09:02:28.335   754  1558 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 09:02:28.335   754  1558 D BatteryService: stay LED for fully charged
,07-27 09:02:28.335   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:02:28.335  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:02:28.335  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:02:28.345  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:02:28.345  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:02:28.345  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:02:28.355  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:28.355  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:28.355   754   754 I MotionRecognitionService: Plugged
07-27 09:02:28.355  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:02:28.355   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:02:30.625   308   308 E SMD     : DCD ON
,07-27 09:02:33.625   308   308 E SMD     : DCD ON
,07-27 09:02:36.625   308   308 E SMD     : DCD ON
,07-27 09:02:36.805   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:02:37.405   754  3020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:02:38.405   754  1703 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:02:38.405   754  1703 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:02:38.405   754  1703 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:02:38.405   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:02:38.415  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:02:38.415  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:02:38.415   754   754 I MotionRecognitionService: Plugged
,07-27 09:02:38.415   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:02:38.415   754  1703 D BatteryService: stay LED for fully charged
,07-27 09:02:38.415  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:02:38.425  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:02:38.425  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:02:38.425  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:38.425  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:02:38.425  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:39.625   308   308 E SMD     : DCD ON
,07-27 09:02:42.625   308   308 E SMD     : DCD ON
,07-27 09:02:43.675   754  1059 I PowerManagerService: [PWL] Off : 600s ago
,07-27 09:02:45.625   308   308 E SMD     : DCD ON
,07-27 09:02:46.855   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:02:48.465   754  1528 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:02:48.465   754  1528 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:02:48.465   754  1528 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:02:48.465   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:02:48.475  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:02:48.475  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:02:48.475  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:02:48.475   754   754 I MotionRecognitionService: Plugged
,07-27 09:02:48.485  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:02:48.485  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:02:48.485   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:02:48.485   754  1528 D BatteryService: stay LED for fully charged
,07-27 09:02:48.485  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:48.485  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:48.485  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:48.625   308   308 E SMD     : DCD ON
,07-27 09:02:50.885   754  1347 E Watchdog: !@Sync 21
,07-27 09:02:51.625   308   308 E SMD     : DCD ON
,07-27 09:02:54.625   308   308 E SMD     : DCD ON
,07-27 09:02:56.895   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:02:57.635   308   308 E SMD     : DCD ON
,07-27 09:02:58.515   754  1580 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:03:00.635   308   308 E SMD     : DCD ON
,07-27 09:03:03.635   308   308 E SMD     : DCD ON
,07-27 09:03:06.635   308   308 E SMD     : DCD ON
,07-27 09:03:06.945   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:03:08.575   754  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:03:09.635   308   308 E SMD     : DCD ON
,07-27 09:03:12.635   308   308 E SMD     : DCD ON
,07-27 09:03:15.635   308   308 E SMD     : DCD ON
,07-27 09:03:16.995   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:03:18.635   308   308 E SMD     : DCD ON
,07-27 09:03:18.645   754  1446 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:03:18.645   754  1446 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:03:18.645   754  1446 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:03:18.655   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:03:18.655   754   754 I MotionRecognitionService: Plugged
,07-27 09:03:18.655   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:03:18.655  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:03:18.665  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:03:18.665  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:03:18.665  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:03:18.665  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:03:18.665  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:18.665   754  1446 D BatteryService: stay LED for fully charged
07-27 09:03:18.665  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:18.675  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:20.885   754  1347 E Watchdog: !@Sync 22
,07-27 09:03:21.635   308   308 E SMD     : DCD ON
,07-27 09:03:24.635   308   308 E SMD     : DCD ON
,07-27 09:03:27.045   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:03:27.635   308   308 E SMD     : DCD ON
,07-27 09:03:28.695   754  1318 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:03:28.705   754  1318 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:03:28.705   754  1318 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:03:28.705   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:03:28.715   754   754 I MotionRecognitionService: Plugged
,07-27 09:03:28.715  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:03:28.715  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:03:28.715   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:03:28.725   754  1318 D BatteryService: stay LED for fully charged
,07-27 09:03:28.725  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:03:28.735  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:28.745  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:03:28.745  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:03:28.755  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:28.755  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:30.645   308   308 E SMD     : DCD ON
,07-27 09:03:33.645   308   308 E SMD     : DCD ON
,07-27 09:03:36.645   308   308 E SMD     : DCD ON
,07-27 09:03:37.095   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:03:38.765   754  1703 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:03:38.765   754  1703 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:03:38.765   754  1703 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:03:38.775   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:03:38.775   754   754 I MotionRecognitionService: Plugged
,07-27 09:03:38.775   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:03:38.775  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:03:38.785  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:03:38.785  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:03:38.785  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:03:38.785  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:03:38.785   754  1703 D BatteryService: stay LED for fully charged
,07-27 09:03:38.795  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:38.795  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:38.795  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:39.645   308   308 E SMD     : DCD ON
,07-27 09:03:42.645   308   308 E SMD     : DCD ON
,07-27 09:03:45.645   308   308 E SMD     : DCD ON
,07-27 09:03:47.135   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:03:48.645   308   308 E SMD     : DCD ON
,07-27 09:03:48.835   754  1639 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:03:48.835   754  1639 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 09:03:48.835   754  1639 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:03:48.835   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:03:48.835  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:03:48.835  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
07-27 09:03:48.835   754   754 I MotionRecognitionService: Plugged
,07-27 09:03:48.835   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:03:48.845   754  1639 D BatteryService: stay LED for fully charged
,07-27 09:03:48.845  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:03:48.855  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:48.855  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:48.855  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:03:48.855  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:03:48.855  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:50.885   754  1347 E Watchdog: !@Sync 23
,07-27 09:03:51.645   308   308 E SMD     : DCD ON
,07-27 09:03:54.645   308   308 E SMD     : DCD ON
,07-27 09:03:57.185   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:03:57.645   308   308 E SMD     : DCD ON
,07-27 09:03:58.895   754  1580 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:03:58.895   754  1580 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 09:03:58.895   754  1580 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 09:03:58.895   754  1580 D BatteryService: stay LED for fully charged
,07-27 09:03:58.895   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:03:58.895  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:03:58.895  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:03:58.895   754   754 I MotionRecognitionService: Plugged
07-27 09:03:58.895   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:03:58.905  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:03:58.905  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:03:58.915  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:03:58.915  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:58.915  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:58.915  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:00.645   308   308 E SMD     : DCD ON
,07-27 09:04:03.645   308   308 E SMD     : DCD ON
,07-27 09:04:03.675   754  1059 I PowerManagerService: [PWL] Off : 680s ago
,07-27 09:04:06.645   308   308 E SMD     : DCD ON
,07-27 09:04:07.235   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:04:08.395   754  1117 D InputReader: Input event: value=1
,07-27 09:04:08.395   754  1117 D InputReader: !@notifyKey(116), action=0
07-27 09:04:08.395   754  1117 D InputManager-JNI: !@interceptKeyBeforeQueueing(116), action=0
,07-27 09:04:08.395   754  1117 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 754  pkgName : WAKEUP_BOOSTER@32
,07-27 09:04:08.405   754  1117 E SamsungWindowManager: mCoreNumLockHelper.acquire
,07-27 09:04:08.405   754  1117 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 754) eventTime = 726143 event = 1
,07-27 09:04:08.405   754  1117 I PowerManagerService: !@[ps] Screen__On  - 1 :  wakeUpWithReason: 1 (uid: 1000 pid: 754)
07-27 09:04:08.405   754  1117 I PowerManagerService: Waking up from sleep (uid 1000)...
07-27 09:04:08.405   754  1117 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,07-27 09:04:08.405   754  1170 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@22b624df)
07-27 09:04:08.405   754  1117 D PowerManagerService: [s] UserActivityState : 0 -> 1
07-27 09:04:08.405   754  1117 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
07-27 09:04:08.405   754  1117 D InputManager-JNI: !@handleInterceptActions(116), action=0, wmActions=0
,07-27 09:04:08.415  1197  2593 D KeyguardViewMediator: onScreenTurnedOn, seq = 2
07-27 09:04:08.415   754  1059 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-27 09:04:08.415   754  1059 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-27 09:04:08.415   754  1059 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-27 09:04:08.415  1197  2593 D KeyguardViewMediator: notifyScreenOnLocked
,07-27 09:04:08.415  1197  1197 D KeyguardViewMediator: handleNotifyScreenOn
07-27 09:04:08.415   754  1055 D SContextService: 	.registerCallback : 1, client=
07-27 09:04:08.415   754  1055 W CAE     : setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,07-27 09:04:08.415  1197  1197 D StatusBarKeyguardViewManager: onScreenTurnedOn()
07-27 09:04:08.415  1197  1197 D KeyguardViewBase: screen on, instance 9284c14
,07-27 09:04:08.415   754  1170 D InputManager-JNI: setDeviceInteractive: 1
,07-27 09:04:08.415  1197  1197 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
07-27 09:04:08.415  1197  1197 D KeyguardSecurityView: showSecurityScreen(None)
,07-27 09:04:08.415  1197  1197 D KeyguardUnlockView: outRect: Rect(0, 99 - 1080, 1920)
07-27 09:04:08.415  1197  1197 D KeyguardUnlockView: isValidRect: true
07-27 09:04:08.415  1197  1197 I WaterColor Keyguard: showUnlockAffordance
07-27 09:04:08.415  1197  1540 D TEST    : run!!!
07-27 09:04:08.415  1197  1540 I WaterColorEffect_View: showAffordanceEffect
,07-27 09:04:08.415  1197  1197 D VisualEffectCircleUnlockEffect: KeyguardEffectViewNone : screenTurnedOn
07-27 09:04:08.415  1197  1197 I WaterColor Keyguard: screenTurnedOn
07-27 09:04:08.415  1197  1197 D SecKeyguardCircleView: onScreenTurnedOn
,07-27 09:04:08.415  1197  1540 I WaterColor_Renderer: clearEffect()
,07-27 09:04:08.425   754  1175 D PowerManagerService: !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
07-27 09:04:08.425   754  1175 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
07-27 09:04:08.425   754  1175 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
07-27 09:04:08.425   754  1055 I CAE     : setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
07-27 09:04:08.425   754  1055 I CAE     : setCAProperty(ContextAwareService.java:469) - result : true
,07-27 09:04:08.425   754  1175 I QCOM PowerHAL: Got set_interactive hint
07-27 09:04:08.425   266   266 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a62000
07-27 09:04:08.425   266   266 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-27 09:04:08.425   754  1291 E Sensors : Acc old sensor_state 8192, new sensor_state : 8193 en : 1
,07-27 09:04:08.425   754  1057 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,07-27 09:04:08.435   754  1055 W CAE     : setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
,07-27 09:04:08.435   754  1055 D SContextService: sendAttribute() : service = Auto Rotation
,07-27 09:04:08.435   754  1055 W CAE     : registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
,07-27 09:04:08.435   754  1055 V CAE     : start(ContextProvider.java:126)
07-27 09:04:08.435   754  1055 V CAE     : clear(AutoRotationRunner.java:182)
07-27 09:04:08.435   754  1055 V CAE     : enable(AutoRotationRunner.java:158)
07-27 09:04:08.435  1197  1540 I WaterColor_Renderer: dirty mode
,07-27 09:04:08.435   754  1055 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
07-27 09:04:08.435  1197  1197 D SensorManager: registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
,07-27 09:04:08.445  1197  1197 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
07-27 09:04:08.445  1197  1197 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1845 should be AT_MOST
,07-27 09:04:08.445   754  1055 D SensorHubManager: SendSensorHubData: send data = -79, 7, 0, 0
,07-27 09:04:08.445   754  1528 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-27 09:04:08.445   754   754 V ActivityManager: Display changed displayId=0
,07-27 09:04:08.445   329   329 D Sensorhubs: sendContextData: -79, 7, 0, 0
,07-27 09:04:08.445   754  7151 D InputManager-JNI: sysfs_write +: /sys/class/input/event2/device/enabled: 1
07-27 09:04:08.445  1197  1197 D StatusBarKeyguardViewManager: callback.onShown()
,07-27 09:04:08.445   754  7150 D InputManager-JNI: sysfs_write +: /sys/class/input/event3/device/enabled: 1
07-27 09:04:08.445   754  7149 D InputManager-JNI: sysfs_write +: /sys/class/input/event4/device/enabled: 1
,07-27 09:04:08.445   754  7150 D InputManager-JNI: sysfs_write -: /sys/class/input/event3/device/enabled: 1
,07-27 09:04:08.445   754   754 D LightsService: [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 754) 
07-27 09:04:08.445   754   754 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
07-27 09:04:08.445   754  1089 D lights  : led_pattern : 0 +
07-27 09:04:08.445   754  1089 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
07-27 09:04:08.445   754   754 D BatteryService: turn off LED
07-27 09:04:08.445   754  1089 D lights  : led_pattern : 0 -
07-27 09:04:08.445   754  1089 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-27 09:04:08.455   754  1055 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-27 09:04:08.455   754  1055 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,07-27 09:04:08.475  1197  1197 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
,07-27 09:04:08.475  1197  1197 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1845 should be AT_MOST
,07-27 09:04:08.475   754   754 I CAE     : handleMessage(CaPowerManager.java:188) - AP_WAKEUP
07-27 09:04:08.475   754   754 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,07-27 09:04:08.475   754   754 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
07-27 09:04:08.475   754   754 D SensorHubManager: SendSensorHubData: send data = -76, 13, -47, 0
07-27 09:04:08.475   329   563 D Sensorhubs: sendContextData: -76, 13, -47, 0
,07-27 09:04:08.485   754   754 D InputMethodManagerService: [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,07-27 09:04:08.485   754   754 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
,07-27 09:04:08.485   754  1124 E MotionRecognitionService:  handler : SCREEN_ON end
,07-27 09:04:08.485   754   754 D NotificationService: ACTION_SCREEN_ON
07-27 09:04:08.485   754   754 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 754) 
07-27 09:04:08.485   754   754 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
07-27 09:04:08.485   754  1089 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
07-27 09:04:08.485   754  1089 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-27 09:04:08.485   754  1146 I WifiNative-HAL: startHal
07-27 09:04:08.485   754  1146 E wifi    : getStaticLongField sWifiHalHandle 0x938a680c
07-27 09:04:08.485   754  1146 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x401f3e
07-27 09:04:08.485   754  1146 I WifiNative-HAL: Could not start hal
,07-27 09:04:08.485   319   693 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-27 09:04:08.485   319   693 V voice   : voice_set_parameters: enter: screen_state=on
07-27 09:04:08.485   319   693 V voice   : voice_set_parameters: exit with code(-2)
07-27 09:04:08.485   319   693 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-27 09:04:08.485   319   693 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-27 09:04:08.485   319   693 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-27 09:04:08.485   319   693 V audio_hw_primary: adev_set_parameters: exit
,07-27 09:04:08.495   754   754 I SecExternalDisplayIntents_Java: Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,07-27 09:04:08.495  1197  1197 D QSpanel : label top:23
07-27 09:04:08.495  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-27 09:04:08.495  1197  1197 D QSpanel : label top:23
07-27 09:04:08.495  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-27 09:04:08.495  1197  1197 D QSpanel : label top:23
07-27 09:04:08.495  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
,07-27 09:04:08.495  1197  1197 D QSpanel : label top:0
07-27 09:04:08.495  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-27 09:04:08.495  1197  1197 D QSpanel : label top:23
07-27 09:04:08.495  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-27 09:04:08.495  1197  1197 D QSpanel : label top:0
07-27 09:04:08.495  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
,07-27 09:04:08.495  1197  1197 D QSpanel : label top:0
07-27 09:04:08.495  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-27 09:04:08.495  1197  1197 D QSpanel : label top:0
07-27 09:04:08.495  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-27 09:04:08.495  1197  1197 D QSpanel : label top:0
07-27 09:04:08.495  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
,07-27 09:04:08.495  1197  1197 D QSpanel : label top:0
07-27 09:04:08.495  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-27 09:04:08.505   754  1055 D CAE     : doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
07-27 09:04:08.505   754  1146 E native  : do suspend false
,07-27 09:04:08.505   754  1055 I CAE     : displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,07-27 09:04:08.505   754  1055 D CAE     : showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
07-27 09:04:08.505   754  1055 I CAE     : showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@2292d9d9, Service : AUTO_ROTATION(1)
07-27 09:04:08.505   754  1055 W CAE     : registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
,07-27 09:04:08.515  6402  6402 I wpa_supplicant: reset timer : RESET_TIMER 1
07-27 09:04:08.515  6402  6402 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-27 09:04:08.515  6402  6402 I wpa_supplicant: P2P: Current p2p state = IDLE
07-27 09:04:08.515   754  1055 D SContextService: addSContextService() : service = Auto Rotation
07-27 09:04:08.515   754  1055 D SContextService: ===== SContext Service List =====
07-27 09:04:08.515   754  1055 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@dbd0f9e, Service : Auto Rotation
,07-27 09:04:08.515  6402  6402 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-27 09:04:08.515   754  1055 D SContextManager:   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@2a43d52c, service=Auto Rotation
,07-27 09:04:08.555   754  7149 D InputManager-JNI: sysfs_write -: /sys/class/input/event4/device/enabled: 1
,07-27 09:04:08.555   754  1059 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-27 09:04:08.555   754  1059 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-27 09:04:08.665   754  1117 D InputReader: Input event: value=0
07-27 09:04:08.665   754  1117 D InputReader: !@notifyKey(116), action=1
07-27 09:04:08.665   754  1117 D InputManager-JNI: !@interceptKeyBeforeQueueing(116), action=1
,07-27 09:04:08.665   754  1117 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 754  tag : WAKEUP_BOOSTER@32
,07-27 09:04:08.665   754  1117 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 754  pkgName : WAKEUP_BOOSTER@32
07-27 09:04:08.665   754  1117 E SamsungWindowManager: mCoreNumLockHelper.acquire
,07-27 09:04:08.665   754  1117 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 754) eventTime = 726411 event = 1
07-27 09:04:08.665   754  1117 D InputManager-JNI: !@handleInterceptActions(116), action=1, wmActions=0
,07-27 09:04:08.665   266   520 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,07-27 09:04:08.665   266   266 E qdexternal: writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
07-27 09:04:08.665   266   266 D qdhwcomposer: hwc_blank: Done unblanking display: 0
07-27 09:04:08.665   754  1175 D SurfaceControl: Excessive delay in setPowerMode(): 246ms
07-27 09:04:08.665   754  1175 D PowerManagerService: Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 248ms
,07-27 09:04:08.665   754  1057 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
07-27 09:04:08.665   754  1057 D IpRemoteDisplayController: Bridge Server is not available
,07-27 09:04:08.665  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-27 09:04:08.665  1197  1197 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte level=1
07-27 09:04:08.665  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
07-27 09:04:08.665  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
07-27 09:04:08.675  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
,07-27 09:04:08.675  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 09:04:08.675  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-27 09:04:08.675  1197  1197 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte level=1
07-27 09:04:08.675  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
07-27 09:04:08.675  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
07-27 09:04:08.675  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
,07-27 09:04:08.675  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:08.675  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:08.675   754  1055 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,07-27 09:04:08.675   754  1059 I DisplayPowerController: Unblocked screen on after 268 ms
07-27 09:04:08.675   754  1059 D DisplayPowerState: !@ ColorFade exit
,07-27 09:04:08.675  1197  1197 D KeyguardViewMediator: handleKeyguardDoneDrawing
,07-27 09:04:08.685  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 09:04:08.685  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:08.685  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 09:04:08.685  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:08.685  1197  1197 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:04:08.685  1197  1197 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-27 09:04:08.685  1197  1197 I KeyguardEffectViewController: *** don't update sliding image ***
07-27 09:04:08.685   754   991 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
07-27 09:04:08.695   266   337 I SurfaceFlinger: id=10 Removed DolorFade (8/8)
07-27 09:04:08.695   266  1584 I SurfaceFlinger: id=10 Removed DolorFade (-2/8)
07-27 09:04:08.695   754  1059 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-27 09:04:08.695   754  1059 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-27 09:04:08.695   754  1059 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-27 09:04:08.695   754  1174 D lights  : lcd : 255 +
07-27 09:04:08.695   754   754 D PersonaManagerService: ACTION_SCREEN_ON onReceive
07-27 09:04:08.695   754  1066 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
07-27 09:04:08.715  1421  1421 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_LOCKED by isKeyguardLocked()
07-27 09:04:08.715  1421  1421 D NativeNfcManager: power state=3
,07-27 09:04:08.725   754  1174 D lights  : lcd : 255 -
07-27 09:04:08.725   754  1059 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-27 09:04:08.725   754  1059 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-27 09:04:08.725   754  1059 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-27 09:04:08.725   754  1059 D PowerManagerService: SecHardwareInterface.setBatteryADC : true
07-27 09:04:08.725   754  1059 D PowerManagerService: [input device light] setInputDeviceLightOn is called : 1
07-27 09:04:08.725   754  1171 D PowerManagerService: [input device light] handleInputDeviceLightOn
07-27 09:04:08.725   754  1171 D lights  : button : 1 +
07-27 09:04:08.725  1421  7169 D NfcService: call the applyRouting
07-27 09:04:08.725   329   561 D Sensorhubs: readContextData: 1, 1, 7, 0
07-27 09:04:08.735   754  1113 D SensorHubManager: onGetSensorHubDataLocked: library(4) = 1, 1, 7, 0
07-27 09:04:08.735   754   754 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:87) - onGetSensorHubData Event [event buffer len :4], AP_WAKEUP
07-27 09:04:08.735  1789  1789 D accuweather: [Accuweather J]>>> SWW:67 [0:0] =============== BR act = androidintentactionSCREEN_ON
07-27 09:04:08.735  1789  1789 D accuweather: [Accuweather J]>>> SWW:70 [0:0] =============== androidintentactionSCREEN_ON instance : [0]1
07-27 09:04:08.735   754   754 I CAE     : parse(SensorHubParserProvider.java:166) - buffer size = 4
07-27 09:04:08.735   754   754 I CAE     : parse(SensorHubParserProvider.java:177) - 1, 1, 7, 0,
07-27 09:04:08.745   754   754 D CAE     : display(ContextProvider.java:365) - ================= AUTO_ROTATION =================
07-27 09:04:08.745   754   754 I CAE     : display(ContextProvider.java:381) - Angle=[0]
07-27 09:04:08.745   754   754 D SContextService: updateSContext() : event = Auto Rotation
07-27 09:04:08.745   754   754 V WindowOrientationListener: mSContextAutoRotationListener.onSContextChanged, Rotation: 0
07-27 09:04:08.755   754  1639 D ActivityManager: caller:android.app.ApplicationThreadProxy@2675fa7f, r.packageName :com.google.android.gms
,07-27 09:04:08.765   754  1171 D lights  : button : 1 -
07-27 09:04:08.765  1421  7169 D NfcService: index : 0
07-27 09:04:08.765  1421  7169 D NfcService: index : 1
07-27 09:04:08.765  1421  7169 D NfcService: index : 2
07-27 09:04:08.775  1751  1751 I SamsungIME: getNextShiftState() cursorCapsMode : 0
07-27 09:04:08.785   754  7151 D InputManager-JNI: sysfs_write -: /sys/class/input/event2/device/enabled: 1
07-27 09:04:08.795   754  2987 D SSRM:a  : DeviceInfo:: 000100100000
07-27 09:04:08.795   754  2987 D SSRM:a  : SettingsAirViewInfo:: 010100000
07-27 09:04:08.795   754  2987 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 09:04:08.795  4379  4379 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:43 [0:0] onReceive() action : androidintentactionSCREEN_ON
07-27 09:04:08.805  4379  4379 E com.samsung.app: [MSC]>>>News_Daemon(E) DR:71 [0:0] [NameNotFoundException] process restart With Widget !!!!!
,07-27 09:04:08.805  4379  4379 W com.samsung.app: [MSC]>>>News_Daemon(E) U:95 [0:0]  ::::::::: Available Internal MemorySize ::::::::: = 25614172k
,07-27 09:04:08.805  4379  4379 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:104 [0:0] checkPackageNameList is Empty
07-27 09:04:08.805  4379  4379 I com.samsung.app: [MSC]>>>News_Daemon(E) DR:110 [0:0] serviceStatus = 0 checkPackageNameList = 0
,07-27 09:04:08.805  4379  4379 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:145 [0:0] [CARS][AUTOREFRESHKEY] --> 0
07-27 09:04:08.805  4379  4379 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:146 [0:0] [CARS][NRT] = 0
,07-27 09:04:08.805  4379  4379 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:147 [0:0] [CARS][DT] = 1469603048817
,07-27 09:04:08.815  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 09:04:08.825   754  1170 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-27 09:04:08.825  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 09:04:08.835   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:04:08.845  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,07-27 09:04:08.845  4379  4379 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
,07-27 09:04:08.845  4379  4379 D comsamsunglog: [MSC_Accu_Daemon]>>> daemonapp [Version : 150820735400 ] [ 1 ] 
07-27 09:04:08.845  4379  4379 D comsamsunglog: [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 09:04:08.845  4379  4379 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
,07-27 09:04:08.845  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-27 09:04:08.855  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,07-27 09:04:08.855  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-27 09:04:08.855  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-27 09:04:08.855  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-27 09:04:08.865  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 09:04:08.865  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,07-27 09:04:08.865  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:616 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
07-27 09:04:08.865  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-27 09:04:08.865  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:618 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,07-27 09:04:08.865  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:619 [0:0] [ASO][NUT] = 07/27/2016 01:00 PM
,07-27 09:04:08.865  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:620 [0:0] [ASO][CT] = 07/27/2016 09:04 AM
07-27 09:04:08.865  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-27 09:04:08.875  4379  4379 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,07-27 09:04:08.895   754  1111 V AlarmManager: waitForAlarm result :8
,07-27 09:04:08.905   754  7173 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-27 09:04:08.905   754   754 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-27 09:04:08.905   754  7173 D NetworkStatsFactory: UpdateStatsForKnox
,07-27 09:04:08.915  1197  1197 I WaterColorEffect_View: showAffordanceEffect Renderer.handleTouchEvent(0, 540, 1009
07-27 09:04:08.915  1197  1197 I WaterColor_Renderer: Renderer handleTouchEvent action = 0
,07-27 09:04:08.925   754  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:04:08.925   754  7173 D NetworkStatsFactory: UpdateStatsForKnox
,07-27 09:04:08.935   754  1470 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4250, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:04:08.945   754  1470 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:04:08.945   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:04:08.945  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:04:08.945  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:04:08.945   754   754 I MotionRecognitionService: Plugged
07-27 09:04:08.945   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:04:08.955  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:04:08.955  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:04:08.955  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:04:08.955  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:08.955  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:04:08.965  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:04:08.985   754  7173 I BatteryStatsDumper: Screen bin #0: time=515 power=0.0032616666666666666
07-27 09:04:08.985   754  7173 I BatteryStatsDumper: Screen bin #1: time=0 power=0.0
07-27 09:04:08.985   754  7173 I BatteryStatsDumper: Screen bin #2: time=0 power=0.0
07-27 09:04:08.985   754  7173 I BatteryStatsDumper: Screen bin #3: time=0 power=0.0
07-27 09:04:08.985   754  7173 I BatteryStatsDumper: Screen bin #4: time=42561 power=2.4259769999999996
07-27 09:04:08.985   754  7173 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-27 09:04:09.375   754  7173 I BatteryStatsDumper: Writing to database completed
,07-27 09:04:09.605   754  1089 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
07-27 09:04:09.605   754  1089 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-27 09:04:09.655   308   308 E SMD     : DCD ON
,07-27 09:04:09.665   754   754 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 754  tag : WAKEUP_BOOSTER@32
,07-27 09:04:09.925  1197  1540 I WaterColor_Renderer: fps 59.820538
,07-27 09:04:10.085  1197  1540 I WaterColor_Renderer: dirty mode
,07-27 09:04:10.085  1197  1540 I WaterColor_Renderer: fps 60.402683
,07-27 09:04:10.225   754  1171 D PowerManagerService: [input device light] handleInputDeviceLightOff
,07-27 09:04:10.225   754  1171 D lights  : button : 0 +
,07-27 09:04:10.265   754  1171 D lights  : button : 0 -
,07-27 09:04:11.035   754  1117 D InputReader: Input event: value=1
,07-27 09:04:11.035   754  1117 D InputReader: Input event: value=1
,07-27 09:04:11.035   754  1117 I InputReader: Touch event's action is 0x0 (deviceType=0) [pCnt=1, s=0.0 ] when=728782341000
07-27 09:04:11.035   754  1116 I InputDispatcher: Delivering touch to (1197): action: 0x0, toolType: 1,
,07-27 09:04:11.045  1197  1197 D ViewRootImpl: ViewPostImeInputStage ACTION_DOWN
,07-27 09:04:11.045  1197  1197 D PanelView: mDispatchInitX=510.0, mDispatchInitY=1476.0
,07-27 09:04:11.045  1197  1197 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,07-27 09:04:11.045   754  1116 E InputTransport: channel 'TouchIntercepter (client)' publisher ~ Received unexpected message of type 2 from consumer
,07-27 09:04:11.045   754  1116 E InputDispatcher: channel 'TouchIntercepter (client)' ~ Failed to receive finished signal.  status=-2147483648
07-27 09:04:11.045   754  1116 E InputDispatcher: channel ~ Channel is unrecoverably broken and will be disposed!
07-27 09:04:11.045  1197  1197 I WaterColor Keyguard: handleTouchEvent action : 0
,07-27 09:04:11.045  1197  1197 D WaterColor Keyguard: ACTION_DOWN, mSoundPool == null
,07-27 09:04:11.045  1197  1197 D WaterColor Keyguard: sound : new SoundPool
,07-27 09:04:11.055  1197  1197 D WaterColor Keyguard: SOUND PLAY SOUND_ID_TAB
,07-27 09:04:11.065  1197  1197 D WaterColor Keyguard: SOUND PLAY mSoundPool = android.media.SoundPool@1fcf52b2, isSystemSoundChecked = true
07-27 09:04:11.065  1197  1197 D WaterColor Keyguard: SOUND PLAY soundId = 0
07-27 09:04:11.065  1197  1197 W SoundPool: Sample was not loaded. Waiting for 30ms.
,07-27 09:04:11.065  1197  7184 V MediaPlayer: decode(81, 11838884, 24881)
,07-27 09:04:11.065   319   319 V MediaPlayerService: decode(27, 11838884, 24881)
,07-27 09:04:11.065   319   319 V MediaPlayerService: player type = 3
,07-27 09:04:11.065   319   319 V AwesomePlayer: setDefault
,07-27 09:04:11.075   319   319 V AwesomePlayer: constructor
,07-27 09:04:11.075   319   319 V AwesomePlayer: setDefault
07-27 09:04:11.075   319   319 V AwesomePlayer: reset_l()
07-27 09:04:11.075   319   319 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:04:11.075   319   319 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:04:11.075   319   319 V AwesomePlayer: mAudioTrackVector clear
07-27 09:04:11.075   319   319 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:04:11.075   319   319 V AwesomePlayer: mSecCapture clear
07-27 09:04:11.075   319   319 V AwesomePlayer: mSecMediaClock clear
,07-27 09:04:11.075   319   319 V StagefrightPlayer: StagefrightPlayer
07-27 09:04:11.075   319   319 V AwesomePlayer: setListener
07-27 09:04:11.075   319   319 V StagefrightPlayer: initCheck
07-27 09:04:11.075   319   319 V AwesomePlayer: setAudioSink
07-27 09:04:11.075   319   319 V StagefrightPlayer: setDataSource(27, 11838884, 24881)
07-27 09:04:11.075   319   319 V AwesomePlayer: reset_l()
07-27 09:04:11.075   319   319 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:04:11.075   319   319 V AudioCache: notify(0xb31fa3d0, 8, 0, 0)
07-27 09:04:11.075   319   319 V AudioCache: ignored
,07-27 09:04:11.075   319   319 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:04:11.075   319   319 V AwesomePlayer: mAudioTrackVector clear
07-27 09:04:11.075   319   319 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:04:11.075   319   319 V AwesomePlayer: mSecCapture clear
07-27 09:04:11.075   319   319 V AwesomePlayer: mSecMediaClock clear
,07-27 09:04:11.075   319   319 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
,07-27 09:04:11.075   319   319 V AwesomePlayer: mBitrate = -1 bits/sec
07-27 09:04:11.075   319   319 I OggExtractor: OggSource::OggSource() mExtractor ref count = 4
07-27 09:04:11.075   319   319 V AwesomePlayer: current audio track index (0) is added to vector
07-27 09:04:11.075   319   319 V AwesomePlayer: setDataSource_l: Audio(1), Video(0)
07-27 09:04:11.075   319   319 I AwesomePlayer: checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
07-27 09:04:11.075   319   319 V MediaPlayerService: prepare
07-27 09:04:11.075   319   319 V AwesomePlayer: prepareAsync
,07-27 09:04:11.075   319   319 V MediaPlayerService: wait for prepare
07-27 09:04:11.075   319  7185 V AwesomePlayer: onPrepareAsyncEvent
07-27 09:04:11.075   319  7185 I SecMediaClock: SecMediaClock constructor
07-27 09:04:11.075   319  7185 I SecMediaClock: reset
07-27 09:04:11.075   319  7185 I SecVideoCapture: SecVideoCapture constructor
,07-27 09:04:11.075   319  7185 I SecVideoCapture: reset
,07-27 09:04:11.085   319  7185 V AwesomePlayer: initAudioDecoder
07-27 09:04:11.085   319  7185 V AwesomePlayer: checkOffloadExceptions is true
07-27 09:04:11.085   319  7185 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1160997 us, has_video=0
07-27 09:04:11.085   319  7185 V AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 09:04:11.085   319  7185 I OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,07-27 09:04:11.085   319  7185 I OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,07-27 09:04:11.085   319  7185 I OMXCodec: >>>UHQA initOutputFormat 16
07-27 09:04:11.085   319  7185 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-27 09:04:11.085   319  7185 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1160997 us, has_video=0
07-27 09:04:11.085   319  7185 V AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 09:04:11.085   319  7185 I OMXCodec: [OMX.google.vorbis.decoder] OMXCodec::start mState=1
07-27 09:04:11.085   319  7185 I OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,07-27 09:04:11.085   319  7185 I OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 09:04:11.085   319  7187 I OMXCodec: [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,07-27 09:04:11.085   319  7185 V AwesomePlayer: finishAsyncPrepare_l
07-27 09:04:11.085   319  7185 V AwesomePlayer: notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
07-27 09:04:11.085   319  7185 V AudioCache: notify(0xb31fa3d0, 200, 973, 0)
07-27 09:04:11.085   319  7185 V AudioCache: ignored
07-27 09:04:11.085   319  7185 V AwesomePlayer: notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
07-27 09:04:11.085   319  7185 V AudioCache: notify(0xb31fa3d0, 5, 0, 0)
07-27 09:04:11.085   319  7185 V AudioCache: ignored
07-27 09:04:11.085   319  7185 V AwesomePlayer: notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
07-27 09:04:11.085   319  7185 V AudioCache: notify(0xb31fa3d0, 1, 0, 0)
,07-27 09:04:11.085   319  7185 V AudioCache: prepared
07-27 09:04:11.085   319   319 V AudioCache: wait - success
07-27 09:04:11.085   319   319 V MediaPlayerService: start
07-27 09:04:11.085   319   319 V StagefrightPlayer: start
,07-27 09:04:11.085   319   319 V AwesomePlayer: play
07-27 09:04:11.085   319   319 V AwesomePlayer: AwesomePlayer::play_l():: This is not a DRM content
07-27 09:04:11.085   319   319 V AwesomePlayer: startAudioPlayer_l, sendErrorNotification (0)
07-27 09:04:11.085   319   319 D AudioPlayer: start of Playback, useOffload 0
,07-27 09:04:11.095  1197  1197 W SoundPool: Sample was not loaded. Waiting for 30ms.
,07-27 09:04:11.095   319  7187 I OMXCodec: [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,07-27 09:04:11.095   319  7187 I OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-27 09:04:11.095   319  7187 I OMXCodec: >>>UHQA initOutputFormat 16
07-27 09:04:11.095   319  7187 I OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,07-27 09:04:11.095   319   319 I AudioPlayer: Audio channels(2)
07-27 09:04:11.095   319   319 I AudioPlayer: Audioplayer kKeyAudioPCMFormat:0, 1, 0
07-27 09:04:11.095   319   319 I AudioPlayer: Audioplayer kKeyAudioPCMFormat read fail(2, 1)
07-27 09:04:11.095   319   319 V AudioCache: open(44100, 2, 0x0, 1, 0)
,07-27 09:04:11.095   319   319 V AwesomePlayer: notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
07-27 09:04:11.095   319   319 V AudioCache: notify(0xb31fa3d0, 6, 0, 0)
07-27 09:04:11.095   319   319 V AudioCache: ignored
07-27 09:04:11.095   319   319 V AwesomePlayer: addBatteryData
,07-27 09:04:11.095   319   319 V MediaPlayerService: wait for playback complete
,07-27 09:04:11.095   319  7188 I AudioPlayer: First fillBuffer call!!
,07-27 09:04:11.105   319  7188 I AudioPlayer: >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
07-27 09:04:11.105   319  7188 E AudioPlayer: >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,07-27 09:04:11.125   319  7187 I OMXCodec: [OMX.google.vorbis.decoder] End Of Stream
,07-27 09:04:11.125  1197  1197 W SoundPool: Sample was not loaded. Waiting for 30ms.
,07-27 09:04:11.125   319  7188 V AwesomePlayer: postAudioEOS delayUs (0)
,07-27 09:04:11.125   319  7185 V AwesomePlayer: onCheckAudioStatus
07-27 09:04:11.125   319  7185 V AwesomePlayer: onCheckAudioStatus() set AUDIO_AT_EOS flag
07-27 09:04:11.125   319  7185 V AwesomePlayer: onStreamDone
07-27 09:04:11.125   319  7185 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-27 09:04:11.125   319  7185 V AwesomePlayer: notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,07-27 09:04:11.125   319  7185 V AudioCache: notify(0xb31fa3d0, 2, 0, 0)
,07-27 09:04:11.125   319  7185 V AudioCache: playback complete - thread will wake up later
07-27 09:04:11.125   319  7185 V AwesomePlayer: notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
07-27 09:04:11.125   319  7185 V AudioCache: notify(0xb31fa3d0, 7, 0, 0)
07-27 09:04:11.125   319  7185 V AudioCache: ignored
07-27 09:04:11.125   319  7185 V AwesomePlayer: cancelPlayerEvents (keepNotifications=1)
,07-27 09:04:11.125   319  7185 V AwesomePlayer: addBatteryData
07-27 09:04:11.125   319   319 V AudioCache: wait - success
07-27 09:04:11.125   319   319 V StagefrightPlayer: reset
07-27 09:04:11.125   319   319 V AwesomePlayer: reset_l()
,07-27 09:04:11.125   319   319 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:04:11.125   319   319 V AudioCache: notify(0xb31fa3d0, 8, 0, 0)
07-27 09:04:11.125   319   319 V AudioCache: ignored
07-27 09:04:11.125   319   319 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:04:11.125   319   319 V AwesomePlayer: mAudioTrackVector clear
07-27 09:04:11.125   319   319 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-27 09:04:11.125   319   319 I OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-27 09:04:11.125   319   319 I OMXCodec: [OMX.google.vorbis.decoder] stop() sendCommand(0x72, OMX_CommandStateSet, OMX_StateIdle)
,07-27 09:04:11.125   319  7187 I OMXCodec: [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,07-27 09:04:11.135   319   319 I OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
07-27 09:04:11.135   319   319 I OggExtractor: OggSource::stop() mExtractor ref count = 1
,07-27 09:04:11.135   319   319 I OggExtractor: OggSource::~OggSource() mExtractor !mStarted ref count = 1
07-27 09:04:11.135   319   319 I OggExtractor: ~OggSource --
07-27 09:04:11.135   319   319 I OggExtractor: ~OggExtractor ++
07-27 09:04:11.135   319   319 I OggExtractor: ~MyVorbisExtractor ++ 
07-27 09:04:11.135   319   319 I OggExtractor: ~MyVorbisExtractor --
07-27 09:04:11.135   319   319 I OggExtractor: ~OggExtractor --
,07-27 09:04:11.135   319   319 I AudioPlayer: reset out
,07-27 09:04:11.135   319   319 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:04:11.135   319   319 I SecVideoCapture: SecVideoCapture destructor
07-27 09:04:11.135   319   319 I SecVideoCapture: reset
07-27 09:04:11.135   319   319 V AwesomePlayer: mSecCapture clear
07-27 09:04:11.135   319   319 I SecMediaClock: SecMediaClock destructor
07-27 09:04:11.135   319   319 V AwesomePlayer: mSecMediaClock clear
,07-27 09:04:11.135   319   319 V StagefrightPlayer: ~StagefrightPlayer
,07-27 09:04:11.135   319   319 V StagefrightPlayer: reset
07-27 09:04:11.135   319   319 V AwesomePlayer: reset_l()
07-27 09:04:11.135   319   319 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:04:11.135   319   319 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:04:11.135   319   319 V AwesomePlayer: mAudioTrackVector clear
07-27 09:04:11.135   319   319 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:04:11.135   319   319 V AwesomePlayer: mSecCapture clear
07-27 09:04:11.135   319   319 V AwesomePlayer: mSecMediaClock clear
,07-27 09:04:11.135   319   319 V AwesomePlayer: destructor
07-27 09:04:11.135   319   319 V AwesomePlayer: reset_l()
07-27 09:04:11.135   319   319 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:04:11.135   319   319 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:04:11.135   319   319 V AwesomePlayer: mAudioTrackVector clear
,07-27 09:04:11.145   319   319 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:04:11.145   319   319 V AwesomePlayer: mSecCapture clear
07-27 09:04:11.145   319   319 V AwesomePlayer: mSecMediaClock clear
,07-27 09:04:11.145  1197  7184 V MediaPlayer: decode(82, 11863824, 11684)
07-27 09:04:11.145   319  2616 V MediaPlayerService: decode(28, 11863824, 11684)
,07-27 09:04:11.145   319  2616 V MediaPlayerService: player type = 3
,07-27 09:04:11.145   319  2616 V AwesomePlayer: setDefault
07-27 09:04:11.145   319  2616 V AwesomePlayer: constructor
,07-27 09:04:11.145   319  2616 V AwesomePlayer: setDefault
07-27 09:04:11.145   319  2616 V AwesomePlayer: reset_l()
07-27 09:04:11.145   319  2616 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:04:11.145   319  2616 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:04:11.145   319  2616 V AwesomePlayer: mAudioTrackVector clear
07-27 09:04:11.145   319  2616 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:04:11.145   319  2616 V AwesomePlayer: mSecCapture clear
07-27 09:04:11.145   319  2616 V AwesomePlayer: mSecMediaClock clear
07-27 09:04:11.145   319  2616 V StagefrightPlayer: StagefrightPlayer
,07-27 09:04:11.145   319  2616 V AwesomePlayer: setListener
07-27 09:04:11.145   319  2616 V StagefrightPlayer: initCheck
07-27 09:04:11.145   319  2616 V AwesomePlayer: setAudioSink
07-27 09:04:11.145   319  2616 V StagefrightPlayer: setDataSource(28, 11863824, 11684)
07-27 09:04:11.145   319  2616 V AwesomePlayer: reset_l()
07-27 09:04:11.145   319  2616 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:04:11.145   319  2616 V AudioCache: notify(0xb02220b0, 8, 0, 0)
07-27 09:04:11.145   319  2616 V AudioCache: ignored
07-27 09:04:11.145   319  2616 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:04:11.145   319  2616 V AwesomePlayer: mAudioTrackVector clear
,07-27 09:04:11.145   319  2616 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:04:11.145   319  2616 V AwesomePlayer: mSecCapture clear
07-27 09:04:11.145   319  2616 V AwesomePlayer: mSecMediaClock clear
,07-27 09:04:11.155   319  2616 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-27 09:04:11.155   319  2616 V AwesomePlayer: mBitrate = -1 bits/sec
,07-27 09:04:11.155   319  2616 I OggExtractor: OggSource::OggSource() mExtractor ref count = 4
07-27 09:04:11.155   319  2616 V AwesomePlayer: current audio track index (0) is added to vector
07-27 09:04:11.155   319  2616 V AwesomePlayer: setDataSource_l: Audio(1), Video(0)
07-27 09:04:11.155   319  2616 I AwesomePlayer: checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
07-27 09:04:11.155   319  2616 V MediaPlayerService: prepare
07-27 09:04:11.155   319  2616 V AwesomePlayer: prepareAsync
07-27 09:04:11.155   319  2616 V MediaPlayerService: wait for prepare
07-27 09:04:11.155   319  7194 V AwesomePlayer: onPrepareAsyncEvent
07-27 09:04:11.155   319  7194 I SecMediaClock: SecMediaClock constructor
,07-27 09:04:11.155   319  7194 I SecMediaClock: reset
07-27 09:04:11.155   319  7194 I SecVideoCapture: SecVideoCapture constructor
07-27 09:04:11.155   319  7194 I SecVideoCapture: reset
07-27 09:04:11.155   319  2313 V AudioPolicyManager: getOutput() device 2, stream 1, samplingRate 0, format 0, channelMask 0, flags 3
07-27 09:04:11.155   319  2313 V AudioPolicyManager: getOutputsForDevice device 0002 -> 0002
07-27 09:04:11.155   319  2313 V AudioPolicyManager: getOutput() returns output 2
07-27 09:04:11.155   319  7194 V AwesomePlayer: initAudioDecoder
07-27 09:04:11.155   319  7194 V AwesomePlayer: checkOffloadExceptions is true
07-27 09:04:11.155   319  7194 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=499410 us, has_video=0
07-27 09:04:11.155   319  7194 V AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
,07-27 09:04:11.155   319  7194 I OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,07-27 09:04:11.155   319  2313 V AudioPolicyManager: getOutput() device 2, stream 1, samplingRate 0, format 0, channelMask 0, flags 3
07-27 09:04:11.155   319  2313 V AudioPolicyManager: getOutputsForDevice device 0002 -> 0002
07-27 09:04:11.155   319  2313 V AudioPolicyManager: getOutput() returns output 2
07-27 09:04:11.155   319   693 V AudioPolicyManager: getOutputForAttr() usage=13, content=4, tag= flags=00000000
07-27 09:04:11.155   319   693 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 44100, format 1, channelMask 3, flags 4
07-27 09:04:11.155   319   693 V AudioPolicyManager: getOutputsForDevice device 0002 -> 0002
07-27 09:04:11.155   319   693 V AudioPolicyManager: getOutput() returns output 2
07-27 09:04:11.155  1197  1197 W AudioTrack: AUDIO_OUTPUT_FLAG_FAST denied by client
,07-27 09:04:11.155   319   693 V AudioPolicyManager: startOutput() output 2, stream 1, session 13
,07-27 09:04:11.155   319   693 V AudioPolicyManager: changeRefCount() stream 1, count 1
07-27 09:04:11.155   319   693 V AudioPolicyManager: getNewOutputDevice() selected device 2
07-27 09:04:11.155   319   693 V AudioPolicyManager: setOutputDevice() output 2 device 0002 delayMs 0
07-27 09:04:11.155   319   693 V AudioPolicyManager: setOutputDevice() prevDevice 0002
07-27 09:04:11.155   319   693 V AudioPolicyManager: setOutputDevice() setting same device 0002 or null device for output 2
,07-27 09:04:11.155  1197  1540 I WaterColor_Renderer: Renderer handleTouchEvent action = 0
07-27 09:04:11.165  1197  1197 D WaterColor Keyguard: sound : onLoadComplete
,07-27 09:04:11.165   319  7194 I OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,07-27 09:04:11.165   319   687 D SoundAliveResampler: [SoundAliveResampler] Init+++
,07-27 09:04:11.165   319   687 V audio_hw_primary: start_output_stream: enter: usecase(0: deep-buffer-playback) devices(0x2)
07-27 09:04:11.165   319   687 V audio_hw_primary: select_devices: ENTER
07-27 09:04:11.165   319   687 V audio_hw_primary: select_devices: usecase(normal)
07-27 09:04:11.165   319   687 V audio_hw_primary: select_devices: usecase(PCM_PLAYBACK)
07-27 09:04:11.165   319   687 V msm8974_platform: platform_get_output_snd_device: enter: output devices(0x2)
07-27 09:04:11.165   319   687 V msm8974_platform: get_OUTPUT_snd_device: for Normal Playback
07-27 09:04:11.165   319   687 V msm8974_platform: platform_get_output_snd_device: exit: snd_device(speaker)
07-27 09:04:11.165   319   687 D audio_hw_primary: select_devices: out_snd_device(2: speaker)
07-27 09:04:11.165   319   687 D audio_hw_primary: select_devices: in_snd_device(0: dummy)
07-27 09:04:11.165   319   687 D ACDB-LOADER: ACDB -> send_audio_cal, acdb_id = 15, path =  0
07-27 09:04:11.165   319   687 D ACDB-LOADER: ACDB -> send_adm_topology
07-27 09:04:11.165   319   687 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
07-27 09:04:11.165   319   687 D ACDB-LOADER: ACDB -> send_asm_topology
07-27 09:04:11.165   319   687 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
07-27 09:04:11.165   319   687 D ACDB-LOADER: ACDB -> send_audtable
07-27 09:04:11.165   319   687 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
07-27 09:04:11.165   319   687 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_CAL
07-27 09:04:11.165   319   687 D ACDB-LOADER: ACDB -> send_audvoltable
07-27 09:04:11.165   319   687 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
07-27 09:04:11.165   319   687 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
07-27 09:04:11.165   319   687 D ACDB-LOADER: ACDB -> send_afe_cal
07-27 09:04:11.165   319   687 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AFE_COMMON_TABLE
07-27 09:04:11.165   319   687 D ACDB-LOADER: ACDB -> AUDIO_SET_AFE_CAL
07-27 09:04:11.165   319   687 V audio_hw_primary: enable_snd_device: snd_device(2: speaker, speaker)
07-27 09:04:11.165   319   687 D audio_route: ++++ audio_route_update_mixer ==============
07-27 09:04:11.165   319   687 D audio_route: Setting mixer control: SPK DRV Volume
07-27 09:04:11.165   319   687 D audio_route: Setting mixer control: value: 8
,07-27 09:04:11.165   319   687 D audio_route: Setting mixer control: RX7 Digital Volume
07-27 09:04:11.165   319   687 D audio_route: Setting mixer control: value: 81
07-27 09:04:11.165  1197  1197 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
07-27 09:04:11.175   319   687 D audio_route: Setting mixer control: COMP0 Switch
07-27 09:04:11.175   319   687 D audio_route: Setting mixer control: value: 1
07-27 09:04:11.175   754  1221 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10067 pid: 1197) eventTime = 728920
07-27 09:04:11.175   319   687 D audio_route: Setting mixer control: RX7 MIX1 INP1, value: 5
07-27 09:04:11.175   319   687 D audio_route: Setting mixer control: DAC1 Switch
07-27 09:04:11.175   319   687 D audio_route: Setting mixer control: value: 1
07-27 09:04:11.175   319   687 D audio_route: Setting mixer control: SPK Status
07-27 09:04:11.175   319   687 D audio_route: Setting mixer control: value: 1
07-27 09:04:11.175   319   687 D audio_route: ------ audio_route_update_mixer ==============
07-27 09:04:11.175   319   687 V audio_hw_primary: enable_audio_route: enter: usecase(0)
07-27 09:04:11.175   319   687 V audio_hw_primary: enable_audio_route: apply mixer path: deep-buffer-playback
07-27 09:04:11.175   319   687 D audio_route: ++++ audio_route_update_mixer ==============
07-27 09:04:11.175   319   687 D audio_route: Setting mixer control: SLIMBUS_0_RX Audio Mixer MultiMedia1
07-27 09:04:11.175   319   687 D audio_route: Setting mixer control: value: 1
07-27 09:04:11.175   319   687 D audio_route: ------ audio_route_update_mixer ==============
07-27 09:04:11.175   319   687 V audio_hw_primary: enable_audio_route: exit
07-27 09:04:11.175   319   687 V audio_hw_primary: start_output_stream: Opening PCM device card_id(0) device_id(0)
07-27 09:04:11.175   319   687 V audio_hw_primary: start_output_stream: exit
07-27 09:04:11.175   319  7194 I OMXCodec: >>>UHQA initOutputFormat 16
07-27 09:04:11.175   319  7194 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-27 09:04:11.175   319  7194 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=499410 us, has_video=0
07-27 09:04:11.175   319  7194 V AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 09:04:11.175   319  7194 I OMXCodec: [OMX.google.vorbis.decoder] OMXCodec::start mState=1
07-27 09:04:11.175   319  7194 I OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-27 09:04:11.175   319  7194 I OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 09:04:11.185   319  7197 I OMXCodec: [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
07-27 09:04:11.185   319  7194 V AwesomePlayer: finishAsyncPrepare_l
07-27 09:04:11.185  1197  1197 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
07-27 09:04:11.185   319  7194 V AwesomePlayer: notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
07-27 09:04:11.195   754  1446 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10067 pid: 1197) eventTime = 728939
07-27 09:04:11.195   319  7194 V AudioCache: notify(0xb02220b0, 200, 973, 0)
07-27 09:04:11.195   319  7194 V AudioCache: ignored
07-27 09:04:11.195   319  7194 V AwesomePlayer: notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
07-27 09:04:11.195   319  7194 V AudioCache: notify(0xb02220b0, 5, 0, 0)
07-27 09:04:11.195   319  7194 V AudioCache: ignored
07-27 09:04:11.195   319  7194 V AwesomePlayer: notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
07-27 09:04:11.195   319  7194 V AudioCache: notify(0xb02220b0, 1, 0, 0)
07-27 09:04:11.195   319  7194 V AudioCache: prepared
07-27 09:04:11.195   319  2616 V AudioCache: wait - success
07-27 09:04:11.195   319  2616 V MediaPlayerService: start
07-27 09:04:11.195   319  2616 V StagefrightPlayer: start
07-27 09:04:11.195   319  2616 V AwesomePlayer: play
07-27 09:04:11.195   319  2616 V AwesomePlayer: AwesomePlayer::play_l():: This is not a DRM content
07-27 09:04:11.195   319  2616 V AwesomePlayer: startAudioPlayer_l, sendErrorNotification (0)
07-27 09:04:11.195   319  2616 D AudioPlayer: start of Playback, useOffload 0
07-27 09:04:11.195   319  7197 I OMXCodec: [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
07-27 09:04:11.195   319  7197 I OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-27 09:04:11.195   319  7197 I OMXCodec: >>>UHQA initOutputFormat 16
07-27 09:04:11.195   319  7197 I OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 09:04:11.195   319  2616 I AudioPlayer: Audio channels(1)
07-27 09:04:11.195   319  2616 I AudioPlayer: Audioplayer kKeyAudioPCMFormat:0, 1, 0
07-27 09:04:11.195   319  2616 I AudioPlayer: Audioplayer kKeyAudioPCMFormat read fail(1, 1)
07-27 09:04:11.195   319  2616 V AudioCache: open(44100, 1, 0x0, 1, 0)
,07-27 09:04:11.205   319  2616 V AwesomePlayer: notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
07-27 09:04:11.205   319  2616 V AudioCache: notify(0xb02220b0, 6, 0, 0)
07-27 09:04:11.205   319  2616 V AudioCache: ignored
07-27 09:04:11.205   319  2616 V AwesomePlayer: addBatteryData
07-27 09:04:11.205   319  7198 I AudioPlayer: First fillBuffer call!!
07-27 09:04:11.205   319  2616 V MediaPlayerService: wait for playback complete
07-27 09:04:11.205   319  7198 I AudioPlayer: >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
07-27 09:04:11.205   319  7198 E AudioPlayer: >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
07-27 09:04:11.205  1197  1197 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
07-27 09:04:11.205   754   785 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10067 pid: 1197) eventTime = 728953
07-27 09:04:11.225  1197  1197 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
07-27 09:04:11.225   754  1703 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10067 pid: 1197) eventTime = 728970
07-27 09:04:11.225   319  7197 I OMXCodec: [OMX.google.vorbis.decoder] End Of Stream
07-27 09:04:11.225   319  7198 V AwesomePlayer: postAudioEOS delayUs (0)
07-27 09:04:11.225   319  7194 V AwesomePlayer: onCheckAudioStatus
07-27 09:04:11.225   319  7194 V AwesomePlayer: onCheckAudioStatus() set AUDIO_AT_EOS flag
07-27 09:04:11.225   319  7194 V AwesomePlayer: onStreamDone
07-27 09:04:11.225   319  7194 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-27 09:04:11.225   319  7194 V AwesomePlayer: notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
07-27 09:04:11.225   319  7194 V AudioCache: notify(0xb02220b0, 2, 0, 0)
07-27 09:04:11.225   319  7194 V AudioCache: playback complete - thread will wake up later
07-27 09:04:11.225   319  7194 V AwesomePlayer: notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
07-27 09:04:11.225   319  7194 V AudioCache: notify(0xb02220b0, 7, 0, 0)
07-27 09:04:11.225   319  7194 V AudioCache: ignored
07-27 09:04:11.225   319  7194 V AwesomePlayer: cancelPlayerEvents (keepNotifications=1)
07-27 09:04:11.225   319  7194 V AwesomePlayer: addBatteryData
07-27 09:04:11.225   319  2616 V AudioCache: wait - success
07-27 09:04:11.225   319  2616 V StagefrightPlayer: reset
07-27 09:04:11.225   319  2616 V AwesomePlayer: reset_l()
07-27 09:04:11.225   319  2616 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:04:11.225   319  2616 V AudioCache: notify(0xb02220b0, 8, 0, 0)
07-27 09:04:11.225   319  2616 V AudioCache: ignored
07-27 09:04:11.225   319  2616 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:04:11.225   319  2616 V AwesomePlayer: mAudioTrackVector clear
07-27 09:04:11.225   319  2616 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-27 09:04:11.225   319  2616 I OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-27 09:04:11.225   319  2616 I OMXCodec: [OMX.google.vorbis.decoder] stop() sendCommand(0x73, OMX_CommandStateSet, OMX_StateIdle)
07-27 09:04:11.225   319  7197 I OMXCodec: [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
07-27 09:04:11.235   319  2616 I OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
07-27 09:04:11.235   319  2616 I OggExtractor: OggSource::stop() mExtractor ref count = 1
07-27 09:04:11.235   319  2616 I OggExtractor: OggSource::~OggSource() mExtractor !mStarted ref count = 1
07-27 09:04:11.235   319  2616 I OggExtractor: ~OggSource --
07-27 09:04:11.235   319  2616 I OggExtractor: ~OggExtractor ++
07-27 09:04:11.235   319  2616 I OggExtractor: ~MyVorbisExtractor ++ 
07-27 09:04:11.235   319  2616 I OggExtractor: ~MyVorbisExtractor --
07-27 09:04:11.235   319  2616 I OggExtractor: ~OggExtractor --
07-27 09:04:11.235   319  2616 I AudioPlayer: reset out
07-27 09:04:11.235   319  2616 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:04:11.235   319  2616 I SecVideoCapture: SecVideoCapture destructor
07-27 09:04:11.235   319  2616 I SecVideoCapture: reset
07-27 09:04:11.235   319  2616 V AwesomePlayer: mSecCapture clear
07-27 09:04:11.235   319  2616 I SecMediaClock: SecMediaClock destructor
07-27 09:04:11.235   319  2616 V AwesomePlayer: mSecMediaClock clear
07-27 09:04:11.235  1197  1197 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
07-27 09:04:11.235   754  1580 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10067 pid: 1197) eventTime = 728986
,07-27 09:04:11.245   319  2616 V StagefrightPlayer: ~StagefrightPlayer
,07-27 09:04:11.245   319  2616 V StagefrightPlayer: reset
07-27 09:04:11.245   319  2616 V AwesomePlayer: reset_l()
07-27 09:04:11.245   319  2616 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:04:11.245   319  2616 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:04:11.245   319  2616 V AwesomePlayer: mAudioTrackVector clear
07-27 09:04:11.245   319  2616 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:04:11.245   319  2616 V AwesomePlayer: mSecCapture clear
07-27 09:04:11.245   319  2616 V AwesomePlayer: mSecMediaClock clear
07-27 09:04:11.245   319  2616 V AwesomePlayer: destructor
,07-27 09:04:11.245   319  2616 V AwesomePlayer: reset_l()
07-27 09:04:11.245   319  2616 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:04:11.245   319  2616 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:04:11.245   319  2616 V AwesomePlayer: mAudioTrackVector clear
,07-27 09:04:11.245   319  2616 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:04:11.245   319  2616 V AwesomePlayer: mSecCapture clear
07-27 09:04:11.245   319  2616 V AwesomePlayer: mSecMediaClock clear
,07-27 09:04:11.255  1197  1197 D KeyguardUnlockEventHandler: mIsUnlockStarted - false
,07-27 09:04:11.255   754  1318 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10067 pid: 1197) eventTime = 729004
,07-27 09:04:11.255  1197  1197 I WaterColor Keyguard: handleUnlock
07-27 09:04:11.255  1197  1540 D TEST    : run!!!
07-27 09:04:11.255  1197  1540 I unlock  : lockBGEffect unlock
07-27 09:04:11.255  1197  1197 D WaterColor Keyguard: SOUND PLAY mSoundPool = android.media.SoundPool@1fcf52b2, isSystemSoundChecked = true
07-27 09:04:11.255  1197  1540 I WaterColor_Renderer: showUnlock()
,07-27 09:04:11.255  1197  1197 D WaterColor Keyguard: SOUND PLAY soundId = 1
07-27 09:04:11.255   319  1090 V AudioPolicyManager: getOutput() device 2, stream 1, samplingRate 0, format 0, channelMask 0, flags 3
07-27 09:04:11.255   319  1090 V AudioPolicyManager: getOutputsForDevice device 0002 -> 0002
07-27 09:04:11.255   319  1090 V AudioPolicyManager: getOutput() returns output 2
07-27 09:04:11.255   319  2313 V AudioPolicyManager: getOutput() device 2, stream 1, samplingRate 0, format 0, channelMask 0, flags 3
07-27 09:04:11.255   319  2313 V AudioPolicyManager: getOutputsForDevice device 0002 -> 0002
07-27 09:04:11.255   319  2313 V AudioPolicyManager: getOutput() returns output 2
07-27 09:04:11.255   319   693 V AudioPolicyManager: getOutputForAttr() usage=13, content=4, tag= flags=00000000
07-27 09:04:11.255   319   693 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 44100, format 1, channelMask 1, flags 4
07-27 09:04:11.255   319   693 V AudioPolicyManager: getOutputsForDevice device 0002 -> 0002
07-27 09:04:11.255   319   693 V AudioPolicyManager: getOutput() returns output 2
07-27 09:04:11.255  1197  1197 W AudioTrack: AUDIO_OUTPUT_FLAG_FAST denied by client
,07-27 09:04:11.255   319   319 V AudioPolicyManager: startOutput() output 2, stream 1, session 14
07-27 09:04:11.255   319   319 V AudioPolicyManager: changeRefCount() stream 1, count 2
,07-27 09:04:11.255  1197  1197 D WaterColor Keyguard: sound : onLoadComplete
,07-27 09:04:11.265  1197  1197 D KeyguardUnlockEventHandler: mIsUnlockStarted - true
,07-27 09:04:11.275   319   687 D SoundAliveResampler: [SoundAliveResampler] Init+++
,07-27 09:04:11.285   754  1117 D InputReader: Input event: value=0
07-27 09:04:11.285   754  1117 I InputReader: Touch event's action is 0x1 (deviceType=0) [pCnt=1, s=] when=729032494000
07-27 09:04:11.285   754  1116 I InputDispatcher: Delivering touch to (1197): action: 0x1, toolType: 1
,07-27 09:04:11.285  1197  1197 D KeyguardUnlockEventHandler: mIsUnlockStarted - true
07-27 09:04:11.285  1197  1197 D KeyguardUnlockEventHandler: mIsUnlockStarted - true
,07-27 09:04:11.515   754  1558 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10067 pid: 1197) eventTime = 729269
,07-27 09:04:11.525  1197  1197 D KeyguardUnlockEventHandler: launch() - mIsKeyguardDismissing=false
07-27 09:04:11.525  1197  1197 D KeyguardSecurityView: showNextSecurityScreenOrFinish(false)
,07-27 09:04:11.525  1197  1197 D KeyguardViewMediator: keyguardDone(true)
,07-27 09:04:11.525  1197  1197 D KeyguardViewMediator: handleKeyguardDone
07-27 09:04:11.525  1197  1197 D KeyguardViewMediator: handleHide
,07-27 09:04:11.525  1197  1197 D KeyguardViewMediator: isAutoUnlockEnabled in KeyguardViewMediator = true
,07-27 09:04:11.535   754  1148 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 502] to 60
07-27 09:04:11.535   754  1148 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-27 09:04:11.535   754  1148 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 09:04:11.535   754  1148 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 09:04:11.535   754  1148 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-27 09:04:11.535   754  1148 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
07-27 09:04:11.535   754  1148 D ConnectivityService: calling update connectivity
07-27 09:04:11.535   754  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:04:11.535   754  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 09:04:11.535   754  1148 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 09:04:11.535   754  1148 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:04:11.535  1197  1604 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-27 09:04:11.535   319  2616 V AudioPolicyManager: getOutput() device 2, stream 1, samplingRate 0, format 0, channelMask 0, flags 3
07-27 09:04:11.535   319  2616 V AudioPolicyManager: getOutputsForDevice device 0002 -> 0002
07-27 09:04:11.535   319  2616 V AudioPolicyManager: getOutput() returns output 2
,07-27 09:04:11.535   319  1090 V AudioPolicyManager: getOutput() device 2, stream 1, samplingRate 0, format 0, channelMask 0, flags 3
07-27 09:04:11.535   319  1090 V AudioPolicyManager: getOutputsForDevice device 0002 -> 0002
07-27 09:04:11.535   319  1090 V AudioPolicyManager: getOutput() returns output 2
07-27 09:04:11.545   319  2313 V AudioPolicyManager: getOutputForAttr() usage=13, content=4, tag=zlJD flags=00000000
07-27 09:04:11.545   319  2313 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 44100, format 1, channelMask 3, flags 4
07-27 09:04:11.545   319  2313 V AudioPolicyManager: getOutputsForDevice device 0002 -> 0002
07-27 09:04:11.545   319  2313 V AudioPolicyManager: getOutput() returns output 2
07-27 09:04:11.545  1197  1197 W AudioTrack: AUDIO_OUTPUT_FLAG_FAST denied by client
,07-27 09:04:11.545   319   693 V AudioPolicyManager: startOutput() output 2, stream 1, session 15
07-27 09:04:11.545   319   693 V AudioPolicyManager: changeRefCount() stream 1, count 3
,07-27 09:04:11.545   754  1703 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 09:04:11.545   754  1703 D SecContentProvider2: mCursor = null
,07-27 09:04:11.545  1197  1197 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME recent clock search >
07-27 09:04:11.545   754  1481 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 09:04:11.545   754  1481 D SecContentProvider2: mCursor = null
,07-27 09:04:11.545   754  1580 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 09:04:11.545   754  1580 D SecContentProvider2: mCursor = null
,07-27 09:04:11.545   754  1318 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 09:04:11.545   754  1318 D SecContentProvider2: mCursor = null
,07-27 09:04:11.545  1197  1197 D StatusBar-DoNotDistrub: isDisableAlert isDormantModeOn:false isNotificationDisabled:true
,07-27 09:04:11.555  1197  1197 D KeyguardEffectViewUtil: wallpaperType :1
07-27 09:04:11.555  1197  1197 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
07-27 09:04:11.555  1197  1197 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-27 09:04:11.555   754  2987 D SSRM:a  : DeviceInfo:: 000100100000
07-27 09:04:11.555   754  2987 D SSRM:a  : SettingsAirViewInfo:: 010100000
,07-27 09:04:11.555   319   687 D SoundAliveResampler: [SoundAliveResampler] Init+++
,07-27 09:04:11.565  1197  1197 D PhoneStatusBar: makeExpandedInvisible: mExpandedVisible=true mExpandedVisible=true
,07-27 09:04:11.565  1197  1197 D StatusBar-QSPanel: setSingleLine:true
07-27 09:04:11.565  1197  1197 D StatusBar-QSPanel: updateButtonInfo mButtonWidth : 206 mColumns:5 orien: 1 displayWidth:1032
07-27 09:04:11.565  1197  1197 D StatusBar-QSPanel: setSingleLine height:0
,07-27 09:04:11.565  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-27 09:04:11.565  1197  1197 D STATUSBAR-PhoneStatusBar: showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
,07-27 09:04:11.565  1197  1197 D PhoneStatusBar: updateQSpanelHeight: 279 height:279
07-27 09:04:11.565  1197  1197 I StatusBar: Icon Only
07-27 09:04:11.565   754  1291 D ActivityManager: startService callerProcessName:tv.peel.samsung.app, calleePkgName: tv.peel.samsung.app
07-27 09:04:11.565   754  1291 D ActivityManager: caller:android.app.ApplicationThreadProxy@7d7476, r.packageName :tv.peel.samsung.app
,07-27 09:04:11.565  1197  1197 D PanelView: There is/are notification(s) 
,07-27 09:04:11.565  1197  1197 D KeyguardEffectViewUtil: wallpaperType :1
07-27 09:04:11.565  1197  1197 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
07-27 09:04:11.565  1197  1197 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-27 09:04:11.565  1197  1197 D PanelView: flingSettings mQsMin:0 mQsMax:393 mQsEx:393.0mQsPeek:279
,07-27 09:04:11.565  1197  1197 I PhoneStatusBar: Icon Only
,07-27 09:04:11.565  1197  1197 I StatusBar: Icon Only
,07-27 09:04:11.575  1197  1197 D PanelView: There is/are notification(s) 
,07-27 09:04:11.575  1197  1197 I StatusBar: Icon Only
,07-27 09:04:11.575  1197  1197 D PanelView: There is/are notification(s) 
,07-27 09:04:11.575  1197  1197 D KeyguardEffectViewUtil: wallpaperType :1
07-27 09:04:11.575  1197  1197 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
07-27 09:04:11.575  1197  1197 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-27 09:04:11.575  1197  1197 D KeyguardEffectViewUtil: wallpaperType :1
,07-27 09:04:11.575  1197  1197 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
07-27 09:04:11.575  1197  1197 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-27 09:04:11.575   754  1470 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 09:04:11.575   754  1470 D SecContentProvider2: mCursor = null
,07-27 09:04:11.575  1197  1197 D PhoneStatusBar: disable: < expand icons* alerts system_info* back HOME recent clock search >
07-27 09:04:11.585   754  1528 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 09:04:11.585   754  1528 D SecContentProvider2: mCursor = null
,07-27 09:04:11.585   754  1221 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 09:04:11.585   754  1221 D SecContentProvider2: mCursor = null
,07-27 09:04:11.585  1197  1197 D StatusBar-DoNotDistrub: isDisableAlert isDormantModeOn:false isNotificationDisabled:true
07-27 09:04:11.585  1197  1197 D PhoneStatusBar: updateKeyguardState :0
07-27 09:04:11.585  1197  1197 I KeyguardEffectViewController: setKeyguardShowing = false
,07-27 09:04:11.585  1197  1197 D KeyguardEffectViewController: cleanUp()
07-27 09:04:11.585  1197  1197 D VisualEffectCircleUnlockEffect: KeyguardEffectViewNone : cleanUp
07-27 09:04:11.585  1197  1197 I WaterColor Keyguard: cleanUp
07-27 09:04:11.585  1197  1197 V KeyguardUpdateMonitor: *** unregister callback for com.android.keyguard.sec.KeyguardEffectViewController$2@3eaa8064
,07-27 09:04:11.585  1197  1197 D KeyguardEffectViewController: isFestivalActivated()false
07-27 09:04:11.585  1197  1197 I KeyguardEffectViewController: setFestivalKeyguardShowing = false ,:false
07-27 09:04:11.585  1197  1197 D KeyguardEffectViewController: isFestivalActivated()false
07-27 09:04:11.585  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
07-27 09:04:11.585  1197  1197 I PhoneStatusBar: Icon Only
07-27 09:04:11.585  1197  1197 I StatusBar: Icon Only
,07-27 09:04:11.585  1197  1197 D PanelView: There is/are notification(s) 
,07-27 09:04:11.585  1197  1197 D PanelView: There is/are notification(s) 
,07-27 09:04:11.585  1197  1197 D PhoneStatusBar: updateKeyguardPreviousState :0
,07-27 09:04:11.595  1197  1197 D KeyguardProperties: isIgnoreNationalRoaming() = false
,07-27 09:04:11.595  1197  1197 D PhoneStatusBar: HomeCitySettingsDialog available = false, show = false
07-27 09:04:11.595  1197  1197 D KeyguardEffectViewUtil: wallpaperType :1
,07-27 09:04:11.595  1197  1197 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
07-27 09:04:11.595  1197  1197 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-27 09:04:11.595  1197  1197 D StatusBar-Window: fnf=true sanc=false, kni=false, sbf=false
07-27 09:04:11.595  1197  1197 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-27 09:04:11.595  1197  1197 V KeyguardUpdateMonitor: *** unregister callback for com.android.keyguard.sec.SecKeyguardCircleView$1@27d5d177
07-27 09:04:11.595   754  1639 E Sensors : Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,07-27 09:04:11.605  1197  1197 D SensorManager: unregisterListener ::   
,07-27 09:04:11.605  1197  1197 D KeyguardUnlockEventHandler: cleanUp()
,07-27 09:04:11.605  1197  1197 I SecAttributionInfoView: onDetachedFromWindow
07-27 09:04:11.605  1197  1197 V KeyguardUpdateMonitor: *** unregister callback for com.android.keyguard.KeyguardSimpleHostView$1@2f60f54c
07-27 09:04:11.605  1197  1197 V KeyguardDisplayManager: hide
,07-27 09:04:11.605  1197  1197 D KeyguardUpdateMonitor: sendKeyguardVisibilityChanged(false)
,07-27 09:04:11.615   754   754 V ActivityManager: Display changed displayId=0
,07-27 09:04:11.625  1197  1197 D KeyguardViewMediator: adjustStatusBarLocked: mShowing=false mOccluded=false isSecure=false --> flags=0x0
07-27 09:04:11.625  6285  6285 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-27 09:04:11.625  6285  6285 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-27 09:04:11.625   754  1528 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,07-27 09:04:11.625  6285  6285 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-27 09:04:11.625  6285  6285 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-27 09:04:11.625  1197  1197 D PhoneStatusBar: makeExpandedInvisible: mExpandedVisible=false mExpandedVisible=false
,07-27 09:04:11.625   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
,07-27 09:04:11.625   754   754 D PalmMotion: 2013 - SURFACE_MOTION_ENGINE: 1 SURFACE_PALM_TOUCH: 1
,07-27 09:04:11.635   754  1657 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 09:04:11.635   754   754 D PalmMotion: SURFACE_PALM_SWIPE: 1
07-27 09:04:11.635   754   754 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
07-27 09:04:11.635   754   754 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 754) 
07-27 09:04:11.635   754   754 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,07-27 09:04:11.635  1421  1421 D NativeNfcManager: power state=4
07-27 09:04:11.635   754  1089 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
07-27 09:04:11.635   754  1089 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
07-27 09:04:11.635   754  1146 D WifiStateMachine: WiFi already connected. do nothing
,07-27 09:04:11.635   754   754 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 09:04:11.635   754   754 W PackageManager: Failure retrieving resources for com.google.android.gms: Resource ID #0x0
,07-27 09:04:11.635   754   783 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,07-27 09:04:11.635   754  1055 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-27 09:04:11.635   754   783 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: 0
07-27 09:04:11.635   754   783 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-27 09:04:11.635   754   783 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-27 09:04:11.635   754   783 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: 0
,07-27 09:04:11.645   754  1318 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-27 09:04:11.645   754  1318 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-27 09:04:11.645   754  1318 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-27 09:04:11.645  6285  6285 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d8d8a57 time:729393
,07-27 09:04:11.645   754   783 D PowerManagerService: [api] setUserActivityTimeoutOverrideFromWindowManagerInternal: timeoutMillis: -1
07-27 09:04:11.645   754   783 D PowerManagerService: [s] getScreenOffTimeoutLocked: 10000 -> 30000
,07-27 09:04:11.645   754   783 D PowerManagerService: [api] setScreenDimDurationOverrideFromWindowManagerInternal: timeoutMillis: -1
,07-27 09:04:11.645   754   754 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: null
,07-27 09:04:11.645  1751  1751 D SamsungIME: showDlgMsgBox : false true true
07-27 09:04:11.645   754  1057 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-27 09:04:11.645   754  1057 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 09:04:11.645   754  1057 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-27 09:04:11.645   754  1057 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-27 09:04:11.655  1491  1491 D Coffee - GoogleTrustAgent: onCreate
,07-27 09:04:11.655   754  2987 D SSRM:a  : DeviceInfo:: 000000100000
07-27 09:04:11.655   754  2987 D SSRM:a  : SettingsAirViewInfo:: 010100000
,07-27 09:04:11.655  1197  1197 D StatusBar-Window: fnf=true sanc=false, kni=false, sbf=false
07-27 09:04:11.655  1197  1197 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-27 09:04:11.655   754   754 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-27 09:04:11.655   754   754 D PersonaManagerService: getPersonasForUser(): returning null!
,07-27 09:04:11.655   754  1703 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-27 09:04:11.665  1421  7212 D NfcService: call the applyRouting
,07-27 09:04:11.665  1197  1197 D KeyguardUpdateMonitor: handleKeyguardVisibilityChanged(0)
,07-27 09:04:11.675   754  7215 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:04:11.675   754  1446 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 09:04:11.675   754  1446 D SecContentProvider2: mCursor = null
,07-27 09:04:11.675  1197  1197 D PhoneStatusBar: disable: < expand icons alerts system_info back home* recent clock search >
07-27 09:04:11.675   754  1593 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 09:04:11.675   754  1593 D SecContentProvider2: mCursor = null
,07-27 09:04:11.675   754  1221 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 09:04:11.675   754  1221 D SecContentProvider2: mCursor = null
07-27 09:04:11.675   754  1558 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 09:04:11.675   754  1558 D SecContentProvider2: mCursor = null
07-27 09:04:11.675  1197  1197 D StatusBar-DoNotDistrub: isDisableAlert isDormantModeOn:false isNotificationDisabled:true
,07-27 09:04:11.695  1751  1751 I SamsungIME: getCurrentCandidateView
,07-27 09:04:11.705  1491  1491 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,07-27 09:04:11.745  4680  4680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.sm.common.appmanager.AppLockingNotiReceiver.onReceive:93 android.app.ActivityThread.handleReceiver:2989 
,07-27 09:04:11.745   754  1291 D ActivityManager: startService callerProcessName:com.samsung.android.sm, calleePkgName: com.samsung.android.sm
,07-27 09:04:11.745   754  1291 D ActivityManager: caller:android.app.ApplicationThreadProxy@211d4fb2, r.packageName :com.samsung.android.sm
,07-27 09:04:11.755   319   667 V AudioPolicyManager: stopOutput() output 2, stream 1, session 15
07-27 09:04:11.755   319   667 V AudioPolicyManager: changeRefCount() stream 1, count 2
,07-27 09:04:11.765  1197  1197 D WaterColor Keyguard: onWindowFocusChanged - false
,07-27 09:04:11.875   319   667 V AudioPolicyManager: stopOutput() output 2, stream 1, session 14
07-27 09:04:11.875   319   667 V AudioPolicyManager: changeRefCount() stream 1, count 1
,07-27 09:04:11.885  1491  1491 I TrustAgentApi - GoogleTrustAgentServiceImpl: GoogleTrustAgent registerCallbacks.
,07-27 09:04:11.915  1421  7212 D NfcService: index : 0
07-27 09:04:11.915  1421  7212 D NfcService: index : 1
07-27 09:04:11.915  1421  7212 D NfcService: index : 2
,07-27 09:04:11.935  1751  1751 D SamsungIME: Dismiss ExpandCandiate
,07-27 09:04:11.955  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 09:04:11.955  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:11.955  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 09:04:11.955  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:11.955  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:11.955  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:11.965  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 09:04:11.965  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:11.965  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:11.965  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:11.985   754  1446 I art     : Explicit concurrent mark sweep GC freed 116276(8MB) AllocSpace objects, 193(3MB) LOS objects, 30% free, 36MB/52MB, paused 2.394ms total 160.210ms
,07-27 09:04:11.985  1197  1540 I WaterColor_Renderer: clearEffect()
,07-27 09:04:11.985   754  1221 D ActivityManager: caller:android.app.ApplicationThreadProxy@3502a45f, r.packageName :com.google.android.gms
,07-27 09:04:11.985  1491  1491 D Coffee - TrustStateMonitor: TrustAgent enabled state changed from false to true.
,07-27 09:04:12.015  1197  1540 I WaterColor_Renderer: dirty mode
07-27 09:04:12.015  1197  1540 I WaterColor_Renderer: fps 39.906105
,07-27 09:04:12.025  1491  1491 I Coffee - TrustletManager: Starting trustlet Bluetooth
,07-27 09:04:12.035  1491  1491 I Coffee - BluetoothConnectionTracker: Failed to find BluetoothDevice.isEncrypted private API.
07-27 09:04:12.035  1491  1491 I Coffee - BluetoothConnectionTracker: Are you running a recent enough version of L-MR1 master?
,07-27 09:04:12.045  1491  1491 I Coffee - BluetoothConnectionTracker: Failed to find BluetoothDevice.isEncrypted private API.
07-27 09:04:12.045  1491  1491 I Coffee - BluetoothConnectionTracker: Are you running a recent enough version of L-MR1 master?
,07-27 09:04:12.065  1751  1751 I SamsungIME: getDebugLevel  : 0x4f4c
,07-27 09:04:12.065  1491  1491 E Coffee - BluetoothTrustlet: Illegal Bluetooth address.null
,07-27 09:04:12.065  1491  1491 E Coffee - BluetoothTrustlet: Illegal Bluetooth address.null
,07-27 09:04:12.075  1491  1491 I Coffee - TrustletManager: Starting trustlet NFC
,07-27 09:04:12.075  1491  1491 W Coffee - Trustlet: Trustlet NFC attempted to change its canProvideTrust state to the current state (ignored).
,07-27 09:04:12.085  1491  1491 I Coffee - TrustletManager: Starting trustlet Place
,07-27 09:04:12.085  1491  1491 I Coffee - PlaceTrustlet: No account is set for trusted places.
,07-27 09:04:12.095  1491  1491 I Coffee - PlaceTrustlet: removeWorkFromTrustedPlaces
,07-27 09:04:12.095  1491  1491 I Coffee - PlaceTrustlet: No account is set for trusted places.
,07-27 09:04:12.105  1491  1491 I Coffee - TrustletManager: Starting trustlet Voice Unlock
,07-27 09:04:12.105  1491  1491 W Coffee - Trustlet: Trustlet Voice Unlock attempted to change its canProvideTrust state to the current state (ignored).
,07-27 09:04:12.105  1751  1751 I SamsungIME: getDebugLevel  : 0x4f4c
,07-27 09:04:12.105  1491  1491 D Coffee - TrustletManager: validateTrust, mDeviceIdle: false, mRequireUserAuthentication: false
,07-27 09:04:12.115  1751  1751 I SamsungIME: KeybaordView init() : load resources
,07-27 09:04:12.125  1491  1491 I GAv4-SVC: Google Analytics 7.5.71 is starting up.
,07-27 09:04:12.145  1751  1751 I SamsungIME: getCurrentKeyboard
,07-27 09:04:12.145  1751  1751 I SamsungIME: getTextKeyboard
,07-27 09:04:12.155  1751  1751 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-27 09:04:12.235  1491  1833 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-27 09:04:12.255   754  1481 D ActivityManager: caller:null, r.packageName :com.google.android.gms
,07-27 09:04:12.255  1491  1491 D PlaceInferenceEngine: PlaceInferenceEngine start
,07-27 09:04:12.265  1491  1491 I Places  : j.<init>:262: Creating ReverseGeocodingPlaceInferenceModule
,07-27 09:04:12.265  1491  1491 I PlaceInferenceEngine: Adding module: ReverseGeocoding
07-27 09:04:12.265  1491  1491 I PlaceInferenceEngine: Active modules: 1
,07-27 09:04:12.265  1491  1491 I Places  : j.<init>:262: Creating WifiDecisionTreePlaceInferenceModule
,07-27 09:04:12.285  1491  1491 I PlaceInferenceEngine: Adding module: WifiDecisionTree
,07-27 09:04:12.285  1491  1491 I PlaceInferenceEngine: Active modules: 2
,07-27 09:04:12.285  1491  1491 I Places  : j.<init>:262: Creating SpotterPlaceInferenceModule
,07-27 09:04:12.295  1491  1491 I PlaceInferenceEngine: Adding module: Spotter
,07-27 09:04:12.295  1491  1491 I PlaceInferenceEngine: Active modules: 3
,07-27 09:04:12.295   754  1318 D ActivityManager: caller:null, r.packageName :com.google.android.gms
,07-27 09:04:12.305  1491  1491 D Places  : j.<init>:279: Creating GeofencingNearbyAlertModule
,07-27 09:04:12.315  1491  1491 D Coffee - NearbyAlertTracker: GoogleApiClient connected
,07-27 09:04:12.345   319   667 V AudioPolicyManager: stopOutput() output 2, stream 1, session 13
,07-27 09:04:12.345   319   667 V AudioPolicyManager: changeRefCount() stream 1, count 0
07-27 09:04:12.345   319   667 V AudioPolicyManager: getNewOutputDevice() selected device 0
07-27 09:04:12.345   319   667 V AudioPolicyManager: setOutputDevice() output 2 device 0000 delayMs 160
07-27 09:04:12.345   319   667 V AudioPolicyManager: setOutputDevice() prevDevice 0002
07-27 09:04:12.345   319   667 V AudioPolicyManager: setOutputDevice() setting same device 0000 or null device for output 2
,07-27 09:04:12.465  6402  6402 I wpa_supplicant: nl80211: Received scan results (23 BSSes)
,07-27 09:04:12.465   754  1145 D WifiP2pService: InactiveState{ what=147461 }
,07-27 09:04:12.465   754  1145 D WifiP2pService: P2pEnabledState{ what=147461 }
07-27 09:04:12.465   754  1145 D WifiP2pService: DefaultState{ what=147461 }
,07-27 09:04:12.515  1751  7234 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-27 09:04:12.655   308   308 E SMD     : DCD ON
,07-27 09:04:13.585  1197  1197 D WaterColor Keyguard: BrilliantRing sound : release SoundPool
,07-27 09:04:13.585   319   667 V AudioPolicyManager: releaseOutput() 2
,07-27 09:04:13.585   319   667 V AudioPolicyManager: releaseOutput() 2
,07-27 09:04:13.975  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:13.975  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-27 09:04:13.975  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:13.975  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:13.975  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:13.975  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:13.985  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:13.985  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:13.985  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:13.985  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:14.655  1197  1197 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte level=2
,07-27 09:04:14.655  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte
,07-27 09:04:14.665  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=2
,07-27 09:04:14.665  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_2 mContentDescriptionPhoneSignal = Two bars of phone signal
,07-27 09:04:14.665  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:14.675  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:14.675  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:14.675  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:14.675  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:14.675  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:14.685  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:14.685  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:14.685  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:14.685  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:14.995  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:14.995  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:15.005  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:15.005  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:15.015  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:15.015  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:15.015  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:15.015  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:15.025  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:15.025  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:15.235   319   687 V audio_hw_primary: out_standby: enter: usecase(0: deep-buffer-playback)
,07-27 09:04:15.435   319   687 V audio_hw_primary: stop_output_stream: enter: usecase(0: deep-buffer-playback)
,07-27 09:04:15.435   319   687 V audio_hw_primary: disable_audio_route: enter: usecase(0)
07-27 09:04:15.435   319   687 V audio_hw_primary: disable_audio_route: reset mixer path: deep-buffer-playback
07-27 09:04:15.435   319   687 D audio_route: ++++ audio_route_update_mixer ==============
,07-27 09:04:15.435   319   687 D audio_route: Setting mixer control: SLIMBUS_0_RX Audio Mixer MultiMedia1
07-27 09:04:15.435   319   687 D audio_route: Setting mixer control: value: 0
,07-27 09:04:15.435   319   687 D audio_route: ------ audio_route_update_mixer ==============
,07-27 09:04:15.435   319   687 V audio_hw_primary: disable_audio_route: exit
07-27 09:04:15.435   319   687 V audio_hw_primary: disable_snd_device: snd_device(2: speaker)
07-27 09:04:15.435   319   687 D audio_route: ++++ audio_route_update_mixer ==============
,07-27 09:04:15.435   319   687 D audio_route: Setting mixer control: SPK DRV Volume
07-27 09:04:15.435   319   687 D audio_route: Setting mixer control: value: 0
07-27 09:04:15.435   319   687 D audio_route: Setting mixer control: RX7 Digital Volume
,07-27 09:04:15.435   319   687 D audio_route: Setting mixer control: value: 0
,07-27 09:04:15.435   319   687 D audio_route: Setting mixer control: COMP0 Switch
07-27 09:04:15.435   319   687 D audio_route: Setting mixer control: value: 0
07-27 09:04:15.435   319   687 D audio_route: Setting mixer control: RX7 MIX1 INP1, value: 0
,07-27 09:04:15.445   319   687 D audio_route: Setting mixer control: DAC1 Switch
,07-27 09:04:15.445   319   687 D audio_route: Setting mixer control: value: 0
,07-27 09:04:15.445   319   687 D audio_route: Setting mixer control: SPK Status
,07-27 09:04:15.445   319   687 D audio_route: Setting mixer control: value: 0
07-27 09:04:15.445   319   687 D audio_route: ------ audio_route_update_mixer ==============
,07-27 09:04:15.445   319   687 V audio_hw_primary: stop_output_stream: exit: status(0)
07-27 09:04:15.445   319   687 V audio_hw_primary: out_standby: exit
,07-27 09:04:15.655   308   308 E SMD     : DCD ON
,07-27 09:04:18.655   308   308 E SMD     : DCD ON
,07-27 09:04:18.875   754  2987 D SSRM:n  : SIOP:: AP = 320, PST = 302, CUR = 450
,07-27 09:04:18.995   754  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:04:18.995   754  1470 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:04:18.995   754  1470 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:04:18.995   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:04:18.995   754   754 I MotionRecognitionService: Plugged
,07-27 09:04:18.995   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:04:18.995  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:04:19.005  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:04:19.005  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:04:19.005  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:19.005  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:19.005  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:19.015  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:04:19.015  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:04:19.025  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:19.025  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:19.035  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:19.035  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:19.035  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:19.035  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:19.035  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:19.035  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:19.035  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:19.035  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:20.895   754  1347 E Watchdog: !@Sync 24
,07-27 09:04:21.045  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:21.045  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:21.045  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:21.055  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:21.065  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:21.065  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:21.075  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:21.075  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:21.075  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:21.075  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:21.655   308   308 E SMD     : DCD ON
,07-27 09:04:22.065  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:22.065  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:22.075  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:22.085  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:22.095  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:22.095  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:22.095  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:22.095  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:22.095  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:22.095  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:23.095   329   561 D Sensorhubs: readContextData: 1, 1, 7, -1
,07-27 09:04:23.095   754  1113 D SensorHubManager: onGetSensorHubDataLocked: library(4) = 1, 1, 7, -1
,07-27 09:04:23.105   754   754 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:87) - onGetSensorHubData Event [event buffer len :4], AP_WAKEUP
,07-27 09:04:23.105   754   754 I CAE     : parse(SensorHubParserProvider.java:166) - buffer size = 4
,07-27 09:04:23.105   754   754 I CAE     : parse(SensorHubParserProvider.java:177) - 1, 1, 7, -1,
,07-27 09:04:23.115   754   754 D CAE     : display(ContextProvider.java:365) - ================= AUTO_ROTATION =================
,07-27 09:04:23.115   754   754 I CAE     : display(ContextProvider.java:381) - Angle=[-1]
,07-27 09:04:23.125   754   754 D SContextService: updateSContext() : event = Auto Rotation
,07-27 09:04:23.125   754   754 V WindowOrientationListener: mSContextAutoRotationListener.onSContextChanged, Rotation: -1
,07-27 09:04:24.105  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:24.105  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:24.105  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:24.115  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:24.125  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:24.125  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:24.135  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:24.135  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:24.135  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:24.135  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:24.655   308   308 E SMD     : DCD ON
,07-27 09:04:25.125  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:25.135  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:25.135  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:25.145  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:25.155  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:25.155  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:25.155  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:25.155  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:25.155  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:25.155  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:25.205   754  1117 D InputReader: Input event: value=1
,07-27 09:04:25.205   754  1117 D InputReader: !@notifyKey(172), action=0
07-27 09:04:25.205   754  1117 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=0
,07-27 09:04:25.205   754  1117 D InputManager-JNI: !@handleInterceptActions(172), action=0, wmActions=1
,07-27 09:04:25.215   754  1116 D VoIPInterfaceManager: isVoIPRinging()...
,07-27 09:04:25.215   754  1116 D VoIPInterfaceManager: isVoIPRunningAndDeregi()...
07-27 09:04:25.215   754  1116 D VoIPInterfaceManager: Not exist call session
,07-27 09:04:25.215   754  1116 D PersonaManager: isKioskContainerExistOnDevice
,07-27 09:04:25.425   754  1117 D InputReader: Input event: value=0
,07-27 09:04:25.425   754  1117 D InputReader: !@notifyKey(172), action=1
07-27 09:04:25.425   754  1117 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=1
07-27 09:04:25.425   754  1117 D InputManager-JNI: !@handleInterceptActions(172), action=1, wmActions=1
,07-27 09:04:25.425   754  1116 D VoIPInterfaceManager: isVoIPRinging()...
,07-27 09:04:25.425   754  1116 D VoIPInterfaceManager: isVoIPRunningAndDeregi()...
07-27 09:04:25.425   754  1116 D VoIPInterfaceManager: Not exist call session
07-27 09:04:25.425   754  1116 D PersonaManager: isKioskContainerExistOnDevice
,07-27 09:04:25.735   754  1055 I WindowManager: startDockOrHome
,07-27 09:04:25.735   754   754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.accessibility.AccessibilityManagerService$DirectAccessBrocastReceiver.onReceive:382 android.app.LoadedApk$ReceiverDispatcher$Args.run:923 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,07-27 09:04:25.735  1197  1197 D HotspotTile: onReceive : android.intent.action.CLOSE_SYSTEM_DIALOGS
,07-27 09:04:25.735  1197  1197 D AirplaneModeTile: onReceive : android.intent.action.CLOSE_SYSTEM_DIALOGS
07-27 09:04:25.745  1197  1197 D PhoneStatusBar: animateCollapse(): mExpandedVisible=false flags=0
,07-27 09:04:25.745  1197  1197 D StatusBar-Window: fnf=true sanc=false, kni=false, sbf=false
,07-27 09:04:25.745   754  1055 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 754) eventTime = 743492
07-27 09:04:25.745  1197  1197 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-27 09:04:25.745   754  1106 V Scroll/Pause Worker: onReceive: android.intent.action.CLOSE_SYSTEM_DIALOGS
,07-27 09:04:25.745   754  1055 E PersonaManagerService: inState():  stateMachine is null !!
07-27 09:04:25.745   754  1055 I PersonaManagerService: PersonaId don't exist
07-27 09:04:25.745   754  1055 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,07-27 09:04:25.755  1197  1197 D STATUSBAR-LocationQuickSettingButton: onReceive : android.intent.action.CLOSE_SYSTEM_DIALOGS
,07-27 09:04:25.755   754  1055 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10200000 cmp=com.sec.android.app.launcher/com.android.launcher2.Launcher} from uid 1000 on display 0
,07-27 09:04:25.755   754  1055 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 754  pkgName : ACTIVITY_RESUME_BOOSTER@7
,07-27 09:04:25.765   754  1055 W ActivityManager: mDVFSHelper.acquire()
,07-27 09:04:25.765   754  1055 D FocusedStackFrame: Set to : 0
,07-27 09:04:25.785  6285  6285 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-27 09:04:25.785  6285  6285 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-27 09:04:25.795   754  1057 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-27 09:04:25.795   754  1057 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 09:04:25.795   754  1057 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-27 09:04:25.795   754  1057 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-27 09:04:25.795  1197  1197 D Recents_AlternateRecentsComponent: isRecentsTopMost is getting called
,07-27 09:04:25.805   754  1593 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-27 09:04:25.805   754  1593 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,07-27 09:04:25.805   754  1593 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-27 09:04:25.805   754  1593 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-27 09:04:25.805   754  1593 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,07-27 09:04:25.805  1456  1456 D SurfaceWidgetView: destroyHardwareResources():398518713
,07-27 09:04:25.815   754  2987 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 09:04:25.815  1456  1456 D Launcher: onRestart, Launcher: 768940326
,07-27 09:04:25.815  1456  1456 D Launcher: onStart, Launcher: 768940326
07-27 09:04:25.815  1456  1456 D Launcher.HomeView: onStart
07-27 09:04:25.815  1456  1456 D Launcher: onResume, Launcher: 768940326
,07-27 09:04:25.815   754  1657 D SettingsProvider: name = kids_home_mode
07-27 09:04:25.815   754  1657 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 09:04:25.815   754  1657 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 09:04:25.815   754  1657 D SettingsProvider: selectionArgs: false
07-27 09:04:25.815   754  1657 D SettingsProvider: selectionArgs: 10010
,07-27 09:04:25.815   754  1657 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 09:04:25.815   754  1657 D SettingsProvider: ret = -1
07-27 09:04:25.815  1456  1456 D Launcher.HomeView: onResume
,07-27 09:04:25.815  1789  1800 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget resume on instance = 1
07-27 09:04:25.815  1789  1789 D accuweather: [Accuweather J]>>> SWW:179 [0:0] [SWW] onResume : rI = 1
07-27 09:04:25.815  1789  1789 D accuweather: [Accuweather J]>>> SWW:184 [0:0] [SWW] onResume : Orientation = 1/1
07-27 09:04:25.815  1789  1789 D accuweather: [Accuweather J]>>> WR:456 [0:0] =============== updateTime = 1
07-27 09:04:25.815  1789  1789 D accuweather: [Accuweather J]>>> SWW:198 [0:0] [SWW] onResume : size = 1
,07-27 09:04:25.815   754  1470 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
,07-27 09:04:25.825  1456  1456 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
07-27 09:04:25.825  1456  1456 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
07-27 09:04:25.825   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 09:04:25.825   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 09:04:25.825   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 09:04:25.825   754  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 09:04:25.865  7266  7266 E Zygote  : MountEmulatedStorage()
07-27 09:04:25.865  7266  7266 E Zygote  : v2
07-27 09:04:25.865  7266  7266 I libpersona: KNOX_SDCARD checking this for 10084
07-27 09:04:25.865  7266  7266 I libpersona: KNOX_SDCARD not a persona
,07-27 09:04:25.875   754  1470 I ActivityManager: Start proc com.sec.android.widgetapp.ap.hero.accuweather for content provider com.sec.android.widgetapp.ap.hero.accuweather/.provider.accuweather.AccuContentProvider: pid=7266 uid=10084 gids={50084, 9997, 3003} abi=armeabi-v7a
07-27 09:04:25.875  7266  7266 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-27 09:04:25.875  7266  7266 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 09:04:25.875  7266  7266 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-27 09:04:25.875  1456  1456 D MenuAppsGridFragment: onResume
,07-27 09:04:25.875  1456  1456 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-27 09:04:25.875  1456  1456 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-27 09:04:25.875   754  1580 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,07-27 09:04:25.885   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 09:04:25.885   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 09:04:25.885   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 09:04:25.885   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 09:04:25.885   349   349 I art     : Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 306us total 15.744ms
,07-27 09:04:25.895  1789  1804 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
,07-27 09:04:25.895  1789  1962 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
07-27 09:04:25.895  1789  1962 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,07-27 09:04:25.905   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 368us total 11.851ms
,07-27 09:04:25.905  7266  7266 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:04:25.905  7266  7266 D ActivityThread: Added TimaKeyStore provider
,07-27 09:04:25.915   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 269us total 10.522ms
,07-27 09:04:25.955  7282  7282 E Zygote  : MountEmulatedStorage()
07-27 09:04:25.955  7282  7282 E Zygote  : v2
07-27 09:04:25.955  7282  7282 I libpersona: KNOX_SDCARD checking this for 10053
07-27 09:04:25.955  7282  7282 I libpersona: KNOX_SDCARD not a persona
,07-27 09:04:25.955   754  1580 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=7282 uid=10053 gids={50053, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,07-27 09:04:25.965  7282  7282 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 09:04:25.965  7282  7282 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 09:04:25.965  7282  7282 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 09:04:25.965   754   785 D ActivityManager: handle home activity for 0
,07-27 09:04:25.965   754   785 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-27 09:04:25.965   754   785 D KnoxTimeoutHandler: post home show event for user 0
07-27 09:04:25.965   754   754 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-27 09:04:25.965   754   785 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-27 09:04:25.965   754   754 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-27 09:04:25.965   754   785 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-27 09:04:25.965   754   785 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-27 09:04:25.965   754   754 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-27 09:04:25.965   754   754 D PersonaManagerService: getPersonasForUser(): returning null!
,07-27 09:04:25.975  7266  7266 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,07-27 09:04:25.975   266   266 I SurfaceFlinger: id=13 createSurf (1080x1920),1 flag=4, Mauncher
,07-27 09:04:25.975  7266  7266 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 09:04:25.975  7266  7266 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 09:04:25.975  7266  7266 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-27 09:04:25.985   754  1055 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-27 09:04:25.995   754  1057 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-27 09:04:25.995   754  1057 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 09:04:25.995   754  1057 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-27 09:04:25.995   754  1057 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-27 09:04:25.995  7282  7282 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:04:25.995  7282  7282 D ActivityThread: Added TimaKeyStore provider
,07-27 09:04:26.025  1456  1456 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
,07-27 09:04:26.025  1456  1456 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,07-27 09:04:26.025   754  1528 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-27 09:04:26.025   754  1558 D SettingsProvider: name = aw_daemon_service_key_agree_popup_check
07-27 09:04:26.025   754  1558 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 09:04:26.035   754  1558 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-27 09:04:26.035   754  1558 D SettingsProvider: selectionArgs: false
07-27 09:04:26.035   754  1558 D SettingsProvider: selectionArgs: 10084
07-27 09:04:26.035   754  1055 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-27 09:04:26.035   754  1558 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 09:04:26.035   754  1558 D SettingsProvider: ret = -1
,07-27 09:04:26.035  7282  7282 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-27 09:04:26.045   754  7298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:04:26.045  7282  7282 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-27 09:04:26.045  7282  7282 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 09:04:26.045  7282  7282 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
07-27 09:04:26.045  7282  7282 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 09:04:26.045  7282  7282 W ResourcesManager: Asset path '/system/framework/svi.jar' does not exist or contains no resources.
07-27 09:04:26.045  7282  7282 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-27 09:04:26.045  7282  7282 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-27 09:04:26.045   754  1481 I AudioService: getStreamVolume 3 index 0
,07-27 09:04:26.055   754   783 I AudioService: getStreamVolume 3 index 0
,07-27 09:04:26.055   754  1451 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 09:04:26.055   754  1580 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 09:04:26.055  1789  1789 D accuweather: [Accuweather J]>>> DBH:1954 [0:0] gADWI : count = 0
,07-27 09:04:26.055   754  1291 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 09:04:26.065  1456  1456 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b121bf9 time:743813
,07-27 09:04:26.065   754  1639 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,07-27 09:04:26.065   754  1639 D ActivityManager: caller:android.app.ApplicationThreadProxy@c02fe72, r.packageName :com.google.android.googlequicksearchbox
,07-27 09:04:26.075  6285  6285 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-27 09:04:26.075  1789  1789 D accuweather: [Accuweather J]>>> WCD:423 [0:0]  onFirstUpdate :: fU = false
,07-27 09:04:26.075  1789  1789 D accuweather: [Accuweather J]>>> SWW:313 [0:0] hideMsg : mResumeInstnceList[0] = 1
07-27 09:04:26.075  1789  1789 D accuweather: [Accuweather J]>>> WR:800 [0:0] hideMsg : -1, isShow = false
,07-27 09:04:26.075  1789  1789 D accuweather: [Accuweather J]>>> WR:806 [0:0] hideMsg : 0
07-27 09:04:26.075  1789  1789 D accuweather: [Accuweather J]>>> WCD:513 [0:0]  onResume : fU = false, cnt =0
07-27 09:04:26.075  1789  1789 D accuweather: [Accuweather J]>>> WCD:523 [0:0]  onResume :: mFAR = false, cC = false, isa = false
,07-27 09:04:26.075  1789  1789 D accuweather: [Accuweather J]>>> SWW:605 [0:0]  registerTTReceiver ! 
,07-27 09:04:26.075  1789  1789 D accuweather: [Accuweather J]>>> WR:497 [0:0] onResume : 1, widgetMode : 1, orientation : 1
,07-27 09:04:26.085  1507  7303 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_hotword_models]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,07-27 09:04:26.085  1789  1789 D comsamsunglog: [Accuweather J]>>> ==============================================================================================
07-27 09:04:26.085  1789  1789 D comsamsunglog: [Accuweather J]>>> widgetappapheroaccuweather [Version : 150820760143] [ 1 ] 
07-27 09:04:26.085  1789  1789 D comsamsunglog: [Accuweather J]>>> Header set to : ===> "accuweather" <===
07-27 09:04:26.085  1789  1789 D comsamsunglog: [Accuweather J]>>> ==============================================================================================
,07-27 09:04:26.085  1789  1962 D accuweather: [Accuweather J]>>> SM:1141 [0:0] updateCurrentCityTime : [1]0/1
,07-27 09:04:26.085  1789  1962 D accuweather: [Accuweather J]>>> SM:1161 [0:0] updateCurrentCityTime , ConditionLayerWidth = 852, mConditionLayerHeight = 532
,07-27 09:04:26.085  1789  1962 D accuweather: [Accuweather J]>>> SM:2066 [0:0] drw 1nd Tm dt = Wed, Jul 27
,07-27 09:04:26.085  1789  1962 D accuweather: [Accuweather J]>>> SM:2100 [0:0] makeTimeText[1] time :Wed, Jul 27 08:52 , new :Wed, Jul 27 09:04 
,07-27 09:04:26.085  1789  1962 D accuweather: [Accuweather J]>>> SM:2221 [0:0] uCCV : msg = -1, oT = true
07-27 09:04:26.085  1789  1962 D accuweather: [Accuweather J]>>> SM:2184 [0:0] uCCV : time = 09:04
,07-27 09:04:26.085  1507  7306 I HotwordRecognitionRnr: Starting hotword detection.
,07-27 09:04:26.095  1507  7307 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.w@d166af
,07-27 09:04:26.095  1789  1789 D accuweather: [Accuweather J]>>> SM:3461 [0:0] onR : isAni = false
,07-27 09:04:26.095   319  2313 V AudioPolicyManager: getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
07-27 09:04:26.095   319  2313 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
07-27 09:04:26.095   319  2313 V audio_hw_primary: adev_open_input_stream: enter
07-27 09:04:26.095   319  2313 E audio_hw_primary: adev_open_input_stream : jack_config 0
,07-27 09:04:26.095   319  2313 E audio_hw_primary: can not make /data/snd/hal_input.pcm 
07-27 09:04:26.095   319  2313 E audio_hw_primary: can not make /data/snd/hal_input_before_ns.pcm 
07-27 09:04:26.095   319  2313 E audio_hw_primary: can not make /data/snd/hal_input_after_ns.pcm 
07-27 09:04:26.095   319  2313 E audio_hw_primary: adev_open_input_stream input is null, set new input stream
07-27 09:04:26.095   319  2313 V audio_hw_primary: adev_open_input_stream: exit
07-27 09:04:26.095   319  7310 I AudioFlinger: AudioFlinger's thread 0xb0856000 ready to run
07-27 09:04:26.095   319  7310 V audio_hw_primary: in_standby: enter
07-27 09:04:26.095   319  7310 V audio_hw_primary: in_standby: exit:  status(0)
,07-27 09:04:26.095   319  7310 V audio_hw_primary: in_standby: enter
07-27 09:04:26.095   319  7310 V audio_hw_primary: in_standby: exit:  status(0)
,07-27 09:04:26.095  1789  1789 D accuweather: [Accuweather J]>>> SWW:544 [0:0] =================== , resume :1
,07-27 09:04:26.105   754   785 I EDMNativeHelperService: isMicrophoneEnabled
,07-27 09:04:26.105   319  2313 V AudioPolicyManager: startInput() input 17
,07-27 09:04:26.105   319  2313 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
07-27 09:04:26.105   319  2313 V AudioPolicyManager: getNewInputDevice() selected device 80000004
07-27 09:04:26.105   319  2313 V AudioPolicyManager: DeviceVector::refreshTypes() mDeviceTypes 80000004
07-27 09:04:26.105   319  2313 V AudioPolicyManager: DeviceVector::getDevicesFromType() for type 80000004 found 0xb315b3c0
,07-27 09:04:26.105   319  7310 V audio_hw_primary: in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
07-27 09:04:26.105   319  7310 V audio_hw_primary: in_set_parameters: exit: status(11)
07-27 09:04:26.105   319  2313 V AudioPolicyManager: setInputDevice() createAudioPatch returned 11 patchHandle 0
07-27 09:04:26.105   319  2313 V AudioPolicyManager: AudioPolicyManager::startInput() input source = 1999
,07-27 09:04:26.105  1507  7307 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.w@d166af
,07-27 09:04:26.115   319  7310 V msm8974_platform: platform_update_usecase_from_source: input source :6
07-27 09:04:26.115   319  7310 V audio_hw_primary: start_input_stream: enter: usecase(7)
07-27 09:04:26.115   319  7310 V voice   : voice_check_and_set_incall_rec_usecase: voice call not active
07-27 09:04:26.115   319  7310 V audio_hw_primary: start_input_stream: usecase(7)
07-27 09:04:26.115   319  7310 D PreProcess: new SamsungRecord
07-27 09:04:26.115   319  7310 D PreProcess: new NS
07-27 09:04:26.115   319  7310 I samsungRecord: [samsungrecord] SamsungRecInit 
,07-27 09:04:26.115   319  7310 I samsungRecord: [samsungrecordMIC]Use HardCoding Values
07-27 09:04:26.115   319  7310 E samsungRecord: miccalib file can't created. (/data/snd/miccalib.txt)
07-27 09:04:26.115   319  7310 I samsungRecord: 1
07-27 09:04:26.115   319  7310 D SamsungRecord_NS: [SamsungRecord_NS] Init SR 16000
07-27 09:04:26.115   319  7310 D SamsungRecord_NS: [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
07-27 09:04:26.115   319  7310 V audio_hw_primary: select_devices: ENTER
07-27 09:04:26.115   319  7310 V audio_hw_primary: select_devices: usecase(normal)
07-27 09:04:26.115   319  7310 V audio_hw_primary: select_devices: usecase(PCM_CAPTURE)
07-27 09:04:26.115   319  7310 V msm8974_platform: platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
07-27 09:04:26.115   319  7310 V msm8974_platform: get_INPUT_snd_device: check by Input_source(6)
07-27 09:04:26.115   319  7310 V msm8974_platform: platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
07-27 09:04:26.115   319  7310 V msm8974_platform: get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
07-27 09:04:26.115   319  7310 V msm8974_platform: platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
07-27 09:04:26.115   319  7310 D audio_hw_primary: select_devices: out_snd_device(0: dummy)
07-27 09:04:26.115   319  7310 D audio_hw_primary: select_devices: in_snd_device(128: vr-main-mic)
07-27 09:04:26.115   319  7310 D ACDB-LOADER: ACDB -> send_audio_cal, acdb_id = 53, path =  1
07-27 09:04:26.115   319  7310 D ACDB-LOADER: ACDB -> send_adm_topology
07-27 09:04:26.115   319  7310 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
07-27 09:04:26.115   319  7310 D ACDB-LOADER: ACDB -> send_asm_topology
07-27 09:04:26.115   319  7310 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
07-27 09:04:26.115   319  7310 D ACDB-LOADER: ACDB -> send_audtable
07-27 09:04:26.115   319  7310 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
07-27 09:04:26.115   319  7310 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_CAL
07-27 09:04:26.115   319  7310 D ACDB-LOADER: ACDB -> send_audvoltable
07-27 09:04:26.115   319  7310 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
07-27 09:04:26.115   319  7310 D         : Failed to fetch the lookup information of the device 00000035 
07-27 09:04:26.115   319  7310 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
07-27 09:04:26.115   319  7310 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
07-27 09:04:26.115   319  7310 D ACDB-LOADER: ACDB -> AUDIO_SET_AFE_CAL
07-27 09:04:26.115   319  7310 V audio_hw_primary: enable_snd_device: snd_device(128: vr-main-mic, vr-main-mic)
07-27 09:04:26.115   319  7310 D audio_route: ++++ audio_route_update_mixer ==============
07-27 09:04:26.115   319  7310 D audio_route: Setting mixer control: ADC1 Volume
07-27 09:04:26.115   319  7310 D audio_route: Setting mixer control: value: 19
,07-27 09:04:26.125   319  7310 D audio_route: Setting mixer control: DEC6 Volume
07-27 09:04:26.125   319  7310 D audio_route: Setting mixer control: value: 84
,07-27 09:04:26.125   319  7310 D audio_route: Setting mixer control: SLIM TX7 MUX, value: 13
,07-27 09:04:26.125   319  7310 D audio_route: Setting mixer control: AIF1_CAP Mixer SLIM TX7
07-27 09:04:26.125   319  7310 D audio_route: Setting mixer control: value: 1
,07-27 09:04:26.125   319  7310 D audio_route: Setting mixer control: DEC6 MUX, value: 2
,07-27 09:04:26.125   319  7310 D audio_route: ------ audio_route_update_mixer ==============
07-27 09:04:26.125   319  7310 V audio_hw_primary: enable_audio_route: enter: usecase(7)
07-27 09:04:26.125   319  7310 V audio_hw_primary: enable_audio_route: apply mixer path: audio-record
07-27 09:04:26.125   319  7310 D audio_route: ++++ audio_route_update_mixer ==============
07-27 09:04:26.125   319  7310 D audio_route: Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
07-27 09:04:26.125   319  7310 D audio_route: Setting mixer control: value: 1
,07-27 09:04:26.125   319  7310 D audio_route: ------ audio_route_update_mixer ==============
07-27 09:04:26.125   319  7310 V audio_hw_primary: enable_audio_route: exit
07-27 09:04:26.125   319  7310 V audio_hw_primary: start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,07-27 09:04:26.125   319  7310 V audio_hw_primary: start_input_stream: exit
,07-27 09:04:26.135  1789  1962 D accuweather: [Accuweather J]>>> SM:1141 [0:0] updateCurrentCityTime : [1]0/1
07-27 09:04:26.135  1789  1962 D accuweather: [Accuweather J]>>> SM:1161 [0:0] updateCurrentCityTime , ConditionLayerWidth = 852, mConditionLayerHeight = 532
,07-27 09:04:26.135  1789  1962 D accuweather: [Accuweather J]>>> SM:2066 [0:0] drw 1nd Tm dt = Wed, Jul 27
,07-27 09:04:26.195  1507  1507 I HotwordWorker: onReady
,07-27 09:04:26.195   754  1528 I AudioService: getStreamVolume 3 index 0
,07-27 09:04:26.235  7282  7282 D NearbySource: Nearby Source Create!
,07-27 09:04:26.235  7282  7282 D NearbyContext: Nearby Context Create!
,07-27 09:04:26.255   265   551 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
07-27 09:04:26.255   265   551 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 09:04:26.255  7282  7282 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,07-27 09:04:26.255   754  1008 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 754  tag : ACTIVITY_RESUME_BOOSTER@7
07-27 09:04:26.255   754  1008 W ActivityManager: mDVFSHelper.release()
,07-27 09:04:26.265   754  1008 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 754  pkgName : ACTIVITY_RESUME_BOOSTER@11
,07-27 09:04:26.285   754  1057 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{18c4523b u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t35} time:744037
,07-27 09:04:26.285   754  1528 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 09:04:26.285   754  1703 D RCPManagerService: exchangeData() failure , invalid userId
07-27 09:04:26.295  6285  6285 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@16bfb50a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@13d6e410, 16908290=android.view.AbsSavedState$1@13d6e410}, android:focusedViewId=100}]}]
07-27 09:04:26.295  6285  6285 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-27 09:04:26.295  6285  6285 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-27 09:04:26.295  6285  6285 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-27 09:04:26.295  6285  6285 V ActivityThread: updateVisibility : ActivityRecord{21302a2d token=android.os.BinderProxy@2d8d8a57 {com.test.thalitest/com.test.thalitest.MainActivity}} show : false
,07-27 09:04:26.295   754  1221 D RCPManagerService: exchangeData() failure , invalid userId
07-27 09:04:26.295   754  1446 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 09:04:26.305  7282  7282 D GalleryCacheReady: Receive : home resume
,07-27 09:04:26.305  3714  3714 D Mms/UIEventReceiver: ui event
,07-27 09:04:26.315   754  1558 I ActivityManager: Killing 6511:com.google.android.apps.maps/u0a140 (adj 15): emptyCount ##41
,07-27 09:04:26.315   754   783 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1456, uid=10010) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,07-27 09:04:26.315   754  1008 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,07-27 09:04:26.325   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 09:04:26.325   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 09:04:26.325   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 09:04:26.325   754  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 09:04:26.365  7314  7314 E Zygote  : MountEmulatedStorage()
07-27 09:04:26.365  7314  7314 E Zygote  : v2
07-27 09:04:26.365  7314  7314 I libpersona: KNOX_SDCARD checking this for 10109
07-27 09:04:26.365  7314  7314 I libpersona: KNOX_SDCARD not a persona
,07-27 09:04:26.375  7314  7314 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 09:04:26.375  7314  7314 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 09:04:26.375  7314  7314 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-27 09:04:26.375   754  1008 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7314 uid=10109 gids={50109, 9997} abi=armeabi-v7a
,07-27 09:04:26.395  7314  7314 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:04:26.395  7314  7314 D ActivityThread: Added TimaKeyStore provider
,07-27 09:04:26.405  7314  7314 D ResourcesManager: creating new AssetManager and set to /system/app/DigitalClock/DigitalClock.apk
,07-27 09:04:26.405  7314  7314 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-27 09:04:26.415   754  1580 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
,07-27 09:04:26.415   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 09:04:26.415   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 09:04:26.415   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 09:04:26.415   754  1580 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 09:04:26.455  7329  7329 E Zygote  : MountEmulatedStorage()
07-27 09:04:26.455  7329  7329 E Zygote  : v2
07-27 09:04:26.455  7329  7329 I libpersona: KNOX_SDCARD checking this for 10115
07-27 09:04:26.455  7329  7329 I libpersona: KNOX_SDCARD not a persona
,07-27 09:04:26.465   754  1580 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=7329 uid=10115 gids={50115, 9997, 3003} abi=armeabi-v7a
,07-27 09:04:26.465   754  1580 I ActivityManager: Killing 6562:com.samsung.android.app.FileShareServer/u0a88 (adj 15): emptyCount ##41
,07-27 09:04:26.475  7329  7329 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 09:04:26.475  7329  7329 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 09:04:26.475  7329  7329 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-27 09:04:26.485   266  1584 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,07-27 09:04:26.485   266   321 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,07-27 09:04:26.495  7329  7329 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:04:26.495  7329  7329 D ActivityThread: Added TimaKeyStore provider
,07-27 09:04:26.525  7329  7329 D ResourcesManager: creating new AssetManager and set to /system/app/DualClockDigital/DualClockDigital.apk
,07-27 09:04:26.525  7329  7329 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-27 09:04:26.525  7329  7329 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,07-27 09:04:26.555  4973  4973 D PushAndAttach: mAssignedMemoMap.size() :0
,07-27 09:04:26.555   754  1657 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
07-27 09:04:26.555   754  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 09:04:26.555   754  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 09:04:26.555   754  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 09:04:26.555   754  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 09:04:26.565   754   754 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 754  tag : ACTIVITY_RESUME_BOOSTER@11
,07-27 09:04:26.605  7345  7345 E Zygote  : MountEmulatedStorage()
07-27 09:04:26.605  7345  7345 E Zygote  : v2
07-27 09:04:26.605  7345  7345 I libpersona: KNOX_SDCARD checking this for 10182
07-27 09:04:26.605  7345  7345 I libpersona: KNOX_SDCARD not a persona
,07-27 09:04:26.625  7345  7345 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 09:04:26.625  7345  7345 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 09:04:26.625  7345  7345 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 09:04:26.625   754  1657 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7345 uid=10182 gids={50182, 9997, 1028, 1015} abi=armeabi-v7a
,07-27 09:04:26.625   754  1657 I ActivityManager: Killing 6546:com.samsung.shareshot/u0a192 (adj 15): emptyCount ##41
,07-27 09:04:26.625   754  1008 I ActivityManager: Waited long enough for: ServiceRecord{382aba77 u0 tv.peel.samsung.app/tv.peel.samsung.widget.NotiRemoteService}
,07-27 09:04:26.645  7345  7345 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:04:26.645  7345  7345 D ActivityThread: Added TimaKeyStore provider
,07-27 09:04:26.655  7345  7345 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungWidget_ActiveApplication/SamsungWidget_ActiveApplication.apk
,07-27 09:04:26.675  7345  7345 V TaskCloserActivity: TaskCloserActivity enter()
,07-27 09:04:26.685  7345  7345 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-27 09:04:26.685   754  1446 I ActivityManager: Killing 5802:com.sec.pcw.device/1000 (adj 15): emptyCount ##41
,07-27 09:04:27.165  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:27.165  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:27.165  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:27.175  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:27.185  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:27.185  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:27.185  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:27.185  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:27.185  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:27.185  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:27.655   308   308 E SMD     : DCD ON
,07-27 09:04:28.195  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:28.195  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:28.205  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:28.205  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:28.215  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:28.225  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:28.225  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:28.225  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:28.225  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:28.235  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:28.925   754  2987 D SSRM:n  : SIOP:: AP = 320, PST = 304, CUR = 450
,07-27 09:04:30.015  1197  1197 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte level=1
,07-27 09:04:30.015  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
,07-27 09:04:30.025  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
,07-27 09:04:30.025  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
,07-27 09:04:30.025  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:30.035  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:30.035  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:30.045  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:30.045  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:30.045  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:30.055  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:30.055  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:30.055  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:30.055  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:30.225  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:30.225  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:30.235  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:30.245  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:30.245  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:30.245  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:30.245  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:30.245  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:30.245  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:30.255  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:30.655   308   308 E SMD     : DCD ON
,07-27 09:04:31.065   754  1111 V AlarmManager: waitForAlarm result :4
,07-27 09:04:31.065   754  1111 D ActivityManager: caller:null, r.packageName :com.google.android.googlequicksearchbox
,07-27 09:04:31.095  1507  7380 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,07-27 09:04:31.115   754  1639 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:04:31.115   754  1639 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 09:04:31.115   754  1639 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 09:04:31.115   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:04:31.125   754   754 I MotionRecognitionService: Plugged
,07-27 09:04:31.125   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:04:31.125  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:04:31.125  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:04:31.125  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:04:31.125  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:31.125  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:31.135  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:04:31.135  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
07-27 09:04:31.135  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:31.245  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:31.245  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-27 09:04:31.245  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:31.255  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:31.255  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:31.255  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:31.255  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:31.255  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:31.255  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:31.255  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:31.335  7282  7385 D ContactProvider: getAllContactInfoList Start
,07-27 09:04:31.385  7282  7385 D ContactProvider: getAllContactInfoList End
,07-27 09:04:31.385  7282  7385 I syncContacts: thread: 1167, sync time = 56
,07-27 09:04:33.265  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:33.265  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:33.265  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:33.275  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:33.285  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:33.285  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:33.285  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:33.285  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:33.285  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 09:04:33.285  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:33.655   308   308 E SMD     : DCD ON
,07-27 09:04:34.305  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:34.305  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-27 09:04:34.305  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:34.305  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:34.305  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:34.305  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:34.315  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:34.315  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:34.315  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:34.315  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:36.325  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:36.325  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:36.335  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:36.345  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:36.345  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:36.345  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:36.345  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:36.345  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:36.345  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:36.355  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:36.655   308   308 E SMD     : DCD ON
,07-27 09:04:38.965   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 305, CUR = 450
,07-27 09:04:39.665   308   308 E SMD     : DCD ON
,07-27 09:04:40.375  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:40.375  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:40.385  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:40.385  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:40.395  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:40.405  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:40.405  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:40.405  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:40.405  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:40.405  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:41.185   754  1528 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:04:41.195   754  1528 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:04:41.195   754  1528 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:04:41.195   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:04:41.205  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:04:41.205  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:04:41.205   754   754 I MotionRecognitionService: Plugged
,07-27 09:04:41.205   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:04:41.215  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:04:41.225  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:41.225  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:41.225  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:41.225  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:04:41.235  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:04:42.365   754   984 I TemperatureHumiditySensor: Accuracy has been changed to 3
,07-27 09:04:42.405  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:42.405  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:42.415  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:42.415  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:42.425  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:42.425  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:42.425  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:42.425  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:42.425  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:42.425  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:42.665   308   308 E SMD     : DCD ON
,07-27 09:04:43.435  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:43.435  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:43.445  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:43.445  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:43.455  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:43.455  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:43.465  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:43.465  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:43.465  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:43.465  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:45.465  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:45.465  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:45.475  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:45.485  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:45.485  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:45.485  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:45.485  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:45.485  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:45.485  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 09:04:45.485  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:45.665   308   308 E SMD     : DCD ON
,07-27 09:04:46.495  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:46.495  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:46.505  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:46.505  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:46.515  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:46.515  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:46.525  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:46.525  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:46.525  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:46.525  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:48.525  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:48.525  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:48.535  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:48.545  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:48.545  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:48.545  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:48.545  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:48.545  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:48.545  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 09:04:48.555  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:48.665   308   308 E SMD     : DCD ON
,07-27 09:04:49.025   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 306, CUR = 450
,07-27 09:04:49.555  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:49.555  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:49.565  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:49.565  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:49.575  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:49.585  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:49.585  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:49.585  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:49.585  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:49.595  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:49.745   754  1059 D PowerManagerService: [s] UserActivityState : 1 -> 2
,07-27 09:04:49.755   754  1059 D DisplayPowerController: getFinalBrightness : 20 -> 20
,07-27 09:04:49.755   754  1059 D DisplayPowerController: animation target = 20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-27 09:04:49.755   754  1059 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,07-27 09:04:49.765   754  1174 D lights  : lcd : 237 +
,07-27 09:04:49.805   754  1174 D lights  : lcd : 237 -
,07-27 09:04:49.805   754  1174 D lights  : lcd : 170 +
,07-27 09:04:49.825   754  1174 D lights  : lcd : 170 -
,07-27 09:04:49.825   754  1174 D lights  : lcd : 137 +
,07-27 09:04:49.845   754  1174 D lights  : lcd : 137 -
,07-27 09:04:49.845   754  1174 D lights  : lcd : 104 +
,07-27 09:04:49.865   754  1174 D lights  : lcd : 104 -
,07-27 09:04:49.865   754  1174 D lights  : lcd : 71 +
,07-27 09:04:49.885   754  1174 D lights  : lcd : 71 -
,07-27 09:04:49.885   754  1059 D DisplayPowerController: getFinalBrightness : 20 -> 20
,07-27 09:04:49.885   754  1174 D lights  : lcd : 20 +
07-27 09:04:49.885   754  1059 D DisplayPowerController: animation target = 20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-27 09:04:49.895   754  1174 D lights  : lcd : 20 -
,07-27 09:04:49.905   754  1059 D DisplayPowerController: getFinalBrightness : 20 -> 20
07-27 09:04:49.905   754  1059 D DisplayPowerController: animation target = 20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-27 09:04:50.895   754  1347 E Watchdog: !@Sync 25
,07-27 09:04:51.245   754  1657 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:04:51.245   754  1657 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:04:51.245   754  1657 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:04:51.255   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:04:51.255  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:04:51.265  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:04:51.265   754   754 I MotionRecognitionService: Plugged
07-27 09:04:51.265   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:04:51.265  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:04:51.265  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:51.275  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:51.275  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:51.275  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:04:51.275  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:04:51.585  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:51.595  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:51.595  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:51.605  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:51.605  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:51.605  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:51.605  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:51.605  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:51.615  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:51.615  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:51.665   308   308 E SMD     : DCD ON
,07-27 09:04:52.615  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:52.615  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:52.625  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:52.625  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:52.635  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:52.645  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:52.645  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:52.645  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:52.645  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:52.645  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:54.645  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:54.655  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:54.655  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:54.665   308   308 E SMD     : DCD ON
,07-27 09:04:54.665  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:54.665  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:54.665  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:54.665  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:54.665  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:54.675  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:54.675  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:55.675  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 09:04:55.675  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:55.685  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:55.685  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:55.685  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:55.695  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:55.695  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:55.695  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:55.695  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 09:04:55.695  1197  1197 D StatusBar.NetworkController: applyOpen
,07-27 09:04:55.745   754  1059 D PowerManagerService: [s] UserActivityState : 2 -> 4
,07-27 09:04:55.745   754  1059 I PowerManagerService: !@[ps] Screen__Off - 1 : timeout (0x4) (2)
07-27 09:04:55.745   754  1059 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-27 09:04:55.745   754  1059 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,07-27 09:04:55.745   754  1170 D InputManager-JNI: setDeviceInteractive: 0
07-27 09:04:55.745   754  1059 D PowerManagerService: SecHardwareInterface.setBatteryADC : false
,07-27 09:04:55.745   754  1059 D PowerManagerService: handleSandman : startDream()
07-27 09:04:55.745   754  1059 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
07-27 09:04:55.745   754  1059 I PowerManagerService: Sleeping (uid 1000)...
,07-27 09:04:55.745   754  1059 D PowerManagerService: [s] UserActivityState : 4 -> 0
07-27 09:04:55.745   754  1059 D PowerManagerService: [input device light] setInputDeviceLightOn is called : 0
07-27 09:04:55.745   754  1171 D PowerManagerService: [input device light] handleInputDeviceLightOff
,07-27 09:04:55.745   266   266 I SurfaceFlinger: id=14 createSurf (1080x1920),2 flag=404, DolorFade
,07-27 09:04:55.755   754  7388 D InputManager-JNI: sysfs_write +: /sys/class/input/event2/device/enabled: 0
,07-27 09:04:55.755   754  7386 D InputManager-JNI: sysfs_write +: /sys/class/input/event4/device/enabled: 0
07-27 09:04:55.755   754  7387 D InputManager-JNI: sysfs_write +: /sys/class/input/event3/device/enabled: 0
07-27 09:04:55.755   754  7387 D InputManager-JNI: sysfs_write -: /sys/class/input/event3/device/enabled: 0
,07-27 09:04:55.755   754  1117 D InputReader: Input event: value=0
07-27 09:04:55.755   754  7388 D InputManager-JNI: sysfs_write -: /sys/class/input/event2/device/enabled: 0
,07-27 09:04:55.755   754  7386 D InputManager-JNI: sysfs_write -: /sys/class/input/event4/device/enabled: 0
,07-27 09:04:55.755   754  1170 D SContextService: 	.unregisterCallback : 1, client=
07-27 09:04:55.755   754  1170 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@dbd0f9e, Service = Auto Rotation, used = 1
07-27 09:04:55.755   754  1170 W CAE     : unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,07-27 09:04:55.755   754  1170 V CAE     : stop(ContextProvider.java:149)
07-27 09:04:55.755   754  1170 V CAE     : clear(AutoRotationRunner.java:182)
,07-27 09:04:55.755   754  1170 V CAE     : disable(AutoRotationRunner.java:171)
07-27 09:04:55.755   754  1170 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,07-27 09:04:55.755   754  1170 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
07-27 09:04:55.755   329   329 D Sensorhubs: sendContextData: -78, 7, 0, 0
,07-27 09:04:55.795   754  1170 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-27 09:04:55.795   754  1170 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,07-27 09:04:55.815   754  1059 D DisplayPowerController: ColorFade: onAnimationStart
,07-27 09:04:55.815   754  1059 D DisplayPowerController: getFinalBrightness : 255 -> 0
07-27 09:04:55.815   754  1059 D DisplayPowerController: animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-27 09:04:55.835   754  1174 D lights  : lcd : 2 +
,07-27 09:04:55.845   754  1170 D CAE     : doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,07-27 09:04:55.845   754  1170 I CAE     : displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,07-27 09:04:55.845   754  1170 D CAE     : showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
07-27 09:04:55.845   754  1059 D DisplayPowerController: getFinalBrightness : 255 -> 0
07-27 09:04:55.845   754  1059 D DisplayPowerController: animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-27 09:04:55.845   754  1170 W CAE     : unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
07-27 09:04:55.855   754  1170 D SContextService: removeSContextService() : service = Auto Rotation
,07-27 09:04:55.855   754  1170 D SContextService: ===== SContext Service List =====
,07-27 09:04:55.855   754  1170 D SContextManager:   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@2a43d52c, service=Auto Rotation
,07-27 09:04:55.855  1197  1807 D KeyguardViewMediator: onScreenTurnedOff(3)
,07-27 09:04:55.855  1197  1807 I KeyguardEffectViewController: *** KeyguardEffectView getInstanceIfExists ***
07-27 09:04:55.855  1197  1807 D KeyguardEffectViewController: changeWallpaperByScreenOff()
,07-27 09:04:55.855  1197  1807 D KeyguardViewMediator: notifyScreenOffLocked
,07-27 09:04:55.865   754  1174 D lights  : lcd : 2 -
,07-27 09:04:55.865   754  1174 D lights  : lcd : 0 +
,07-27 09:04:55.865  1456  1456 D Launcher.HomeView: onPause
,07-27 09:04:55.865  1456  1456 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
,07-27 09:04:55.875  1197  1807 D KeyguardViewMediator: timeout : 5000
,07-27 09:04:55.915   754  1174 D lights  : lcd : 0 -
,07-27 09:04:55.955   754  1055 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-27 09:04:55.955  1197  1807 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 2
,07-27 09:04:55.955  1197  1197 D KeyguardViewMediator: handleNotifyScreenOff
,07-27 09:04:55.965  7345  7345 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,07-27 09:04:55.965   754   754 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 754) 
07-27 09:04:55.965   754   754 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,07-27 09:04:55.965   754   754 E LightSensor: Light old sensor_state 8192, new sensor_state : 8704 en : 1
,07-27 09:04:55.975   754   754 D SensorManager: registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,07-27 09:04:55.975   754   754 D BatteryService: turn on LED for fully charged
,07-27 09:04:55.975  1456  1456 V ActivityThread: updateVisibility : ActivityRecord{14ce2659 token=android.os.BinderProxy@b121bf9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-27 09:04:55.975  1456  1456 D Launcher.HomeView: onStop
,07-27 09:04:55.985  1789  1804 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget pause on instance = 1
,07-27 09:04:55.985  1789  1789 D accuweather: [Accuweather J]>>> SWW:212 [0:0] [SWW] onPause : rI = 1
07-27 09:04:55.985  1789  1789 D accuweather: [Accuweather J]>>> SWW:222 [0:0] [SWW] onPause : size = 0
,07-27 09:04:55.985  1789  1789 D accuweather: [Accuweather J]>>> SWW:634 [0:0]  unRegisterTTReceiver !! 
,07-27 09:04:55.985   754  1481 I AudioService: getStreamVolume 3 index 0
,07-27 09:04:55.985  1507  1866 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.w@d166af
,07-27 09:04:55.985  1789  1789 D accuweather: [Accuweather J]>>> WCD:1431 [0:0] cARH()
,07-27 09:04:55.985   754   754 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
07-27 09:04:55.985   754   754 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
07-27 09:04:55.995   754   754 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
07-27 09:04:55.995   754   754 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
07-27 09:04:55.995   329   563 D Sensorhubs: sendContextData: -76, 13, -46, 0
,07-27 09:04:55.995  1789  1789 D accuweather: [Accuweather J]>>> WCD:549 [0:0]  onPause 
07-27 09:04:55.995   319   319 V AudioPolicyManager: stopInput() input 17
07-27 09:04:55.995  1789  1789 D accuweather: [Accuweather J]>>> WR:475 [0:0] onPause : 1
,07-27 09:04:55.995  1789  1789 D accuweather: [Accuweather J]>>> SWW:540 [0:0] =================== , pause :1
,07-27 09:04:55.995   319   693 V AudioPolicyManager: releaseInput() 17
,07-27 09:04:55.995   319   693 V AudioPolicyManager: closeInput(17)
07-27 09:04:55.995  1507  7306 I HotwordRecognitionRnr: Hotword detection finished
07-27 09:04:55.995  1507  1881 I HotwordRecognitionRnr: Stopping hotword detection.
,07-27 09:04:55.995   319  7310 V audio_hw_primary: in_standby: enter
,07-27 09:04:56.005   754   754 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 7, 4, 56,
,07-27 09:04:56.005   754   754 D SensorHubManager: SendSensorHubData: send data = -63, 14, 7, 4, 56
07-27 09:04:56.005   329   329 D Sensorhubs: sendContextData: -63, 14, 7, 4, 56
,07-27 09:04:56.005   754  1481 I AudioService: getStreamVolume 3 index 0
,07-27 09:04:56.005   754  1593 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 09:04:56.015   754   754 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,07-27 09:04:56.025   754  1124 E MotionRecognitionService:  handler : SCREEN_OFF end 
,07-27 09:04:56.025   754   754 D NotificationService: ACTION_SCREEN_OFF
,07-27 09:04:56.025   754   754 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 754) 
07-27 09:04:56.025   754   754 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,07-27 09:04:56.025   754  1146 E native  : do suspend true
,07-27 09:04:56.035   319   319 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-27 09:04:56.035   319  7310 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
07-27 09:04:56.035   319  7310 V audio_hw_primary: disable_audio_route: enter: usecase(7)
07-27 09:04:56.035   319  7310 V audio_hw_primary: disable_audio_route: reset mixer path: audio-record
07-27 09:04:56.035   319  7310 D audio_route: ++++ audio_route_update_mixer ==============
07-27 09:04:56.035   319  7310 D audio_route: Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
07-27 09:04:56.035   319  7310 D audio_route: Setting mixer control: value: 0
,07-27 09:04:56.045   319  7310 D audio_route: ------ audio_route_update_mixer ==============
,07-27 09:04:56.045   319  7310 V audio_hw_primary: disable_audio_route: exit
07-27 09:04:56.045   319  7310 V audio_hw_primary: disable_snd_device: snd_device(128: vr-main-mic)
07-27 09:04:56.045   319  7310 D audio_route: ++++ audio_route_update_mixer ==============
07-27 09:04:56.045   319  7310 D audio_route: Setting mixer control: ADC1 Volume
07-27 09:04:56.045   319  7310 D audio_route: Setting mixer control: value: 0
07-27 09:04:56.045   319  7310 D audio_route: Setting mixer control: DEC6 Volume
07-27 09:04:56.045   319  7310 D audio_route: Setting mixer control: value: 0
,07-27 09:04:56.045   319  7310 D audio_route: Setting mixer control: SLIM TX7 MUX, value: 0
,07-27 09:04:56.045   319  7310 D audio_route: Setting mixer control: AIF1_CAP Mixer SLIM TX7
07-27 09:04:56.045   319  7310 D audio_route: Setting mixer control: value: 0
,07-27 09:04:56.045   754  1059 D DisplayPowerState: !@ ColorFade entry
07-27 09:04:56.045   319  7310 D audio_route: Setting mixer control: DEC6 MUX, value: 0
,07-27 09:04:56.045   754  1059 D DisplayPowerController: ColorFade: onAnimationEnd
,07-27 09:04:56.045   319  7310 D audio_route: ------ audio_route_update_mixer ==============
07-27 09:04:56.045   319  7310 V audio_hw_primary: stop_input_stream: exit: status(0)
07-27 09:04:56.045   319   319 V voice   : voice_set_parameters: enter: screen_state=off
07-27 09:04:56.045   319   319 V voice   : voice_set_parameters: exit with code(-2)
07-27 09:04:56.045   319   319 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-27 09:04:56.045   319   319 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-27 09:04:56.045   319   319 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-27 09:04:56.045   319   319 V audio_hw_primary: adev_set_parameters: exit
07-27 09:04:56.055   319  7310 V audio_hw_primary: in_standby: exit:  status(0)
,07-27 09:04:56.055   319   693 V audio_hw_primary: adev_close_input_stream
07-27 09:04:56.055   319   693 V audio_hw_primary: in_standby: enter
07-27 09:04:56.055   319   693 V audio_hw_primary: in_standby: exit:  status(0)
07-27 09:04:56.055   319   693 E audio_hw_primary: adev_close_input_stream, set jack_in to null
,07-27 09:04:56.055   319   693 V AudioPolicyManager: releaseInput() exit
,07-27 09:04:56.055   754  1059 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-27 09:04:56.055   754  1059 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-27 09:04:56.055   754  1059 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-27 09:04:56.055   754  1059 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-27 09:04:56.055   754  1059 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-27 09:04:56.055   754  1059 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-27 09:04:56.055   754  1059 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-27 09:04:56.055   754  1059 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,07-27 09:04:56.055   754  1057 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,07-27 09:04:56.055   266   266 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a62000
07-27 09:04:56.055   266   266 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-27 09:04:56.065   754   754 V ActivityManager: Display changed displayId=0
,07-27 09:04:56.065   754   754 I SecExternalDisplayIntents_Java: Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,07-27 09:04:56.075   754   754 I BackgroundCompactionService: Schedule Type1 BGCompaction
,07-27 09:04:56.085  1197  1197 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte level=1
07-27 09:04:56.085  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
07-27 09:04:56.085  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
,07-27 09:04:56.085  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
07-27 09:04:56.085  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 09:04:56.085  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 09:04:56.105   754  1057 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
07-27 09:04:56.105   754  1057 D IpRemoteDisplayController: Bridge Server is not available
,07-27 09:04:56.105  1197  1197 D VolumePanel.1183e112: forceTimeout delay=0 callers=com.android.systemui.volume.VolumePanel.postDismiss:2103 com.android.systemui.volume.VolumePanel$8.onReceive:1167 android.app.LoadedApk$ReceiverDispatcher$Args.run:923 
,07-27 09:04:56.105  1197  1197 D VolumePanel: mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
07-27 09:04:56.105  1197  1197 D VolumePanel: mCoverBroadcastReceiver: Screen OFF start
07-27 09:04:56.105  1197  1197 D VolumePanel: mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,07-27 09:04:56.105  1197  1197 D VolumePanel: mCoverBroadcastReceiver: Screen OFF end
07-27 09:04:56.105  1197  1197 D VolumePanel: mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,07-27 09:04:56.315   266   520 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
07-27 09:04:56.315   266   266 D qdhwcomposer: hwc_blank: Done blanking display: 0
07-27 09:04:56.315   754  1175 D SurfaceControl: Excessive delay in setPowerMode(): 257ms
07-27 09:04:56.315   754  1175 D PowerManagerService: !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
07-27 09:04:56.315   754  1175 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
07-27 09:04:56.315   754  1175 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
07-27 09:04:56.315   754  1175 I QCOM PowerHAL: Got set_interactive hint
,07-27 09:04:56.315   754  1175 D PowerManagerService: Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 265ms
07-27 09:04:56.315   754  1059 I PowerManagerService: [PWL] Off : 0s ago
07-27 09:04:56.315   754  1059 I PowerManagerService: [PWL]   PowerManagerService.Broadcasts: ref count=1
,07-27 09:04:56.335   754  1089 D LightsService: [SvcLED]  onSensorChanged::light value = 44
,07-27 09:04:56.335   754  1089 E LightSensor: Light old sensor_state 8704, new sensor_state : 8192 en : 0
,07-27 09:04:56.345   754  1089 D SensorManager: unregisterListener ::   
,07-27 09:04:56.345   754  1089 D lights  : led_pattern : 5 +
,07-27 09:04:56.345   754  1089 D lights  : led_pattern : 5 -
07-27 09:04:56.345   754  1089 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-27 09:04:57.405   754   991 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,07-27 09:04:57.405   754   754 D PersonaManagerService: ACTION_SCREEN_OFF onReceive
07-27 09:04:57.405   754  1066 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
,07-27 09:04:57.415  1421  1421 D NativeNfcManager: power state=2
,07-27 09:04:57.415  1197  1197 D STATUSBAR-PhoneStatusBar:      ACTION_SCREEN_OFF is finished!!!! 
,07-27 09:04:57.425  1421  1656 D NfcService: call the applyRouting
,07-27 09:04:57.445  1789  1789 D accuweather: [Accuweather J]>>> SWW:81 [0:0] =============== BR act = androidintentactionSCREEN_OFF
,07-27 09:04:57.455   754  1703 D ActivityManager: caller:android.app.ApplicationThreadProxy@19a062b3, r.packageName :com.google.android.gms
,07-27 09:04:57.465  1421  1656 D NfcService: index : 0
07-27 09:04:57.465  1421  1656 D NfcService: index : 1
07-27 09:04:57.465  1421  1656 D NfcService: index : 2
,07-27 09:04:57.475   754  2987 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 09:04:57.485   754  1528 W ActivityManager: getTasks: caller 10102 does not hold GET_TASKS; limiting output
,07-27 09:04:57.485   754  1593 W ActivityManager: getTasks: caller 10102 does not hold GET_TASKS; limiting output
,07-27 09:04:57.495  1491  1491 D ScreenOnOffReceiver: Received intent: Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }.
,07-27 09:04:57.495   754  1170 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-27 09:04:57.505   754  2987 D SSRM:n  : SIOP:: AP = 320, PST = 308, CUR = 450
,07-27 09:04:57.575   754  7425 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-27 09:04:57.575   754  7425 D NetworkStatsFactory: UpdateStatsForKnox
,07-27 09:04:57.605   754  7425 D NetworkStatsFactory: UpdateStatsForKnox
,07-27 09:04:57.645   754  7425 I BatteryStatsDumper: Screen bin #0: time=515 power=0.0032616666666666666
,07-27 09:04:57.645   754  7425 I BatteryStatsDumper: Screen bin #1: time=0 power=0.0
07-27 09:04:57.645   754  7425 I BatteryStatsDumper: Screen bin #2: time=0 power=0.0
07-27 09:04:57.645   754  7425 I BatteryStatsDumper: Screen bin #3: time=0 power=0.0
07-27 09:04:57.645   754  7425 I BatteryStatsDumper: Screen bin #4: time=42561 power=2.4259769999999996
07-27 09:04:57.645   754  7425 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-27 09:04:57.665   308   308 E SMD     : DCD ON
,07-27 09:04:57.795   754  7425 I BatteryStatsDumper: Writing to database completed
,07-27 09:04:59.995   754  1111 V AlarmManager: waitForAlarm result :8
,07-27 09:05:00.665   308   308 E SMD     : DCD ON
,07-27 09:05:00.875   754  1111 V AlarmManager: waitForAlarm result :4
,07-27 09:05:00.885  1197  1197 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,07-27 09:05:00.895  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
,07-27 09:05:00.915  1197  1197 D KeyguardViewMediator: isAutoUnlockEnabled in KeyguardViewMediator = true
,07-27 09:05:00.915  1197  1197 D KeyguardViewMediator: doKeyguard: showing the lock screen
,07-27 09:05:00.925  1197  1197 D KeyguardViewMediator: showLocked
,07-27 09:05:00.935  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 09:05:00.945  1197  1197 D KeyguardViewMediator: handleShow
,07-27 09:05:00.945  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
,07-27 09:05:00.945  1197  1197 D KeyguardViewMediator: Kiosk container not exists on device.
,07-27 09:05:00.945  1197  1197 D KeyguardEffectViewUtil: wallpaperType :1
,07-27 09:05:00.955  1197  1197 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
,07-27 09:05:00.955  1197  1197 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-27 09:05:00.965  1197  1197 D KeyguardEffectViewUtil: wallpaperType :1
,07-27 09:05:00.965  1197  1197 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=false
07-27 09:05:00.965  1197  1197 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-27 09:05:00.965  1197  1197 D PhoneStatusBar: updateKeyguardState :1
,07-27 09:05:00.975  1197  1197 D StatusBar: LSSN:1
,07-27 09:05:00.975  1197  1197 D StatusBar: fullBouncer=false
,07-27 09:05:00.975  1197  1197 D StatusBar: SLN:S
,07-27 09:05:00.985  1197  1197 E LSO     : LSO Service is not yet ready!!!
07-27 09:05:00.985  1197  1197 D StatusBar-QSPanel: setSingleLine:true
,07-27 09:05:00.985  1197  1197 D StatusBar-QSPanel: updateButtonInfo mButtonWidth : 206 mColumns:5 orien: 1 displayWidth:1032
,07-27 09:05:00.985  1197  1197 D StatusBar-QSPanel: setSingleLine height:0
,07-27 09:05:00.985  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:05:00.985  1197  1197 D STATUSBAR-PhoneStatusBar: showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
,07-27 09:05:00.995  1197  1197 I PhoneStatusBar: Icon Only
,07-27 09:05:00.995  1197  1197 I StatusBar: Icon Only
,07-27 09:05:00.995  1197  1197 D PanelView: There is/are notification(s) 
,07-27 09:05:00.995  1197  1197 D PhoneStatusBar: updateQSpanelHeight: 279 height:591
,07-27 09:05:01.005  1197  1197 D PanelView: setQsHeight mQsMin:0 mQsMax:705 mQsEx:0.0mQsPeek:591
,07-27 09:05:01.005  1197  1197 I KeyguardEffectViewController: setKeyguardShowing = true
,07-27 09:05:01.005  1197  1197 D KeyguardEffectViewController: show()
07-27 09:05:01.005  1197  1197 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.sec.KeyguardEffectViewController$2@3eaa8064
,07-27 09:05:01.005  1197  1197 V KeyguardUpdateMonitor: *** unregister callback for null
,07-27 09:05:01.005  1197  1197 D VisualEffectCircleUnlockEffect: KeyguardEffectViewNone : show
,07-27 09:05:01.005  1197  1197 I WaterColor Keyguard: show
07-27 09:05:01.005  1197  1197 D WaterColor Keyguard: sound : new SoundPool
,07-27 09:05:01.015  1197  1540 I WaterColor_Renderer: clearEffect()
,07-27 09:05:01.015  1197  1197 D KeyguardEffectViewController: isFestivalActivated()false
,07-27 09:05:01.015  1197  1197 I KeyguardEffectViewController: setFestivalKeyguardShowing = true ,:false
,07-27 09:05:01.015  1197  1197 D KeyguardEffectViewController: isFestivalActivated()false,
,07-27 09:05:01.025  1197  1540 I WaterColor_Renderer: dirty mode
,07-27 09:05:01.025  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
,07-27 09:05:01.025  1197  1197 I PhoneStatusBar: Icon Only
,07-27 09:05:01.035  1197  1197 I StatusBar: Icon Only
,07-27 09:05:01.035  1197  1197 D PanelView: There is/are notification(s) 
,07-27 09:05:01.035  1197  1197 D PanelView: There is/are notification(s) 
,07-27 09:05:01.045  1197  1197 D PhoneStatusBar: updateKeyguardPreviousState :1
,07-27 09:05:01.045  1197  1197 D PhoneStatusBar: makeExpandedVisible:false
,07-27 09:05:01.045  1197  7430 V MediaPlayer: decode(64, 11838884, 24881)
,07-27 09:05:01.045  1197  1197 D KeyguardEffectViewUtil: wallpaperType :1
07-27 09:05:01.045  1197  1197 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
,07-27 09:05:01.045  1197  1197 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-27 09:05:01.045   754  1703 D SecContentProvider2: uri = 14 selection = getSealedState
,07-27 09:05:01.045   319  1090 V MediaPlayerService: decode(27, 11838884, 24881)
,07-27 09:05:01.045   754  1703 D SecContentProvider2: mCursor = null
,07-27 09:05:01.055   319  1090 V MediaPlayerService: player type = 3
,07-27 09:05:01.055   319  1090 V AwesomePlayer: setDefault
,07-27 09:05:01.055   319  1090 V AwesomePlayer: constructor
,07-27 09:05:01.055   319  1090 V AwesomePlayer: setDefault
,07-27 09:05:01.055   319  1090 V AwesomePlayer: reset_l()
07-27 09:05:01.055   319  1090 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:05:01.055   319  1090 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
,07-27 09:05:01.055   319  1090 V AwesomePlayer: mAudioTrackVector clear
07-27 09:05:01.055   319  1090 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:05:01.055   319  1090 V AwesomePlayer: mSecCapture clear
,07-27 09:05:01.055   319  1090 V AwesomePlayer: mSecMediaClock clear
07-27 09:05:01.055   319  1090 V StagefrightPlayer: StagefrightPlayer
07-27 09:05:01.055  1197  1197 D PhoneStatusBar: disable: < expand ICONS* alerts SYSTEM_INFO* back home recent clock search >
,07-27 09:05:01.055   319  1090 V AwesomePlayer: setListener
07-27 09:05:01.055   319  1090 V StagefrightPlayer: initCheck
07-27 09:05:01.055   319  1090 V AwesomePlayer: setAudioSink
,07-27 09:05:01.065   319  1090 V StagefrightPlayer: setDataSource(27, 11838884, 24881)
,07-27 09:05:01.065   319  1090 V AwesomePlayer: reset_l()
07-27 09:05:01.065   319  1090 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:05:01.065   319  1090 V AudioCache: notify(0xb0222830, 8, 0, 0)
07-27 09:05:01.065   319  1090 V AudioCache: ignored
,07-27 09:05:01.065   319  1090 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:05:01.065   319  1090 V AwesomePlayer: mAudioTrackVector clear
07-27 09:05:01.065   319  1090 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
,07-27 09:05:01.065   319  1090 V AwesomePlayer: mSecCapture clear
07-27 09:05:01.065   319  1090 V AwesomePlayer: mSecMediaClock clear
,07-27 09:05:01.065   754  1221 D SecContentProvider2: uri = 14 selection = getSealedState
,07-27 09:05:01.065   754  1221 D SecContentProvider2: mCursor = null
,07-27 09:05:01.065   319  1090 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
,07-27 09:05:01.065   754  1451 D SecContentProvider2: uri = 14 selection = getSealedState
,07-27 09:05:01.065   754  1451 D SecContentProvider2: mCursor = null
,07-27 09:05:01.075  1197  1197 D StatusBar-DoNotDistrub: isDisableAlert isDormantModeOn:false isNotificationDisabled:true
,07-27 09:05:01.075  1197  1197 D KeyguardProperties: isIgnoreNationalRoaming() = false
,07-27 09:05:01.075  1197  1197 D PhoneStatusBar: HomeCitySettingsDialog available = false, show = true
,07-27 09:05:01.075   319  1090 V AwesomePlayer: mBitrate = -1 bits/sec
,07-27 09:05:01.075   319  1090 I OggExtractor: OggSource::OggSource() mExtractor ref count = 4
07-27 09:05:01.075   319  1090 V AwesomePlayer: current audio track index (0) is added to vector
07-27 09:05:01.075   319  1090 V AwesomePlayer: setDataSource_l: Audio(1), Video(0)
07-27 09:05:01.075   319  1090 I AwesomePlayer: checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,07-27 09:05:01.075   319  1090 V MediaPlayerService: prepare
,07-27 09:05:01.075   319  1090 V AwesomePlayer: prepareAsync
,07-27 09:05:01.075   319  1090 V MediaPlayerService: wait for prepare
,07-27 09:05:01.085  1197  1197 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardSimpleHostView$1@118a860a
07-27 09:05:01.085  1197  1197 V KeyguardUpdateMonitor: *** unregister callback for null
,07-27 09:05:01.085  1197  1197 D KeyguardSecurityView: AUTO_WIPE = false , IT Policy = false
,07-27 09:05:01.085  1197  1197 I KeyguardSecurityView: addAttributionInfoViewIfNecessary
,07-27 09:05:01.085   319  7431 V AwesomePlayer: onPrepareAsyncEvent
07-27 09:05:01.085   319  7431 I SecMediaClock: SecMediaClock constructor
07-27 09:05:01.085   319  7431 I SecMediaClock: reset
,07-27 09:05:01.085   319  7431 I SecVideoCapture: SecVideoCapture constructor
07-27 09:05:01.085   319  7431 I SecVideoCapture: reset
07-27 09:05:01.085   319  7431 V AwesomePlayer: initAudioDecoder
07-27 09:05:01.085   319  7431 V AwesomePlayer: checkOffloadExceptions is true
,07-27 09:05:01.085   319  7431 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1160997 us, has_video=0
07-27 09:05:01.085   319  7431 V AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
,07-27 09:05:01.085   319  7431 I OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,07-27 09:05:01.095  1197  1197 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
,07-27 09:05:01.095  1197  1197 D KeyguardSecurityView: showSecurityScreen(None)
,07-27 09:05:01.095  1197  1197 V KeyguardSecurityView: inflating id = 2130968634
,07-27 09:05:01.095   319  7431 I OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,07-27 09:05:01.095  1197  1197 D SecKeyguardBottomAreaView: mUseBackUp= falsemUseCenteredMessageArea= false
,07-27 09:05:01.095   319  7431 I OMXCodec: >>>UHQA initOutputFormat 16
07-27 09:05:01.095   319  7431 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-27 09:05:01.095   319  7431 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1160997 us, has_video=0
,07-27 09:05:01.095   319  7431 V AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 09:05:01.095   319  7431 I OMXCodec: [OMX.google.vorbis.decoder] OMXCodec::start mState=1
07-27 09:05:01.095   319  7431 I OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,07-27 09:05:01.105   319  7431 I OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,07-27 09:05:01.105   319  7433 I OMXCodec: [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,07-27 09:05:01.105   319  7431 V AwesomePlayer: finishAsyncPrepare_l
07-27 09:05:01.105   319  7431 V AwesomePlayer: notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
07-27 09:05:01.105   319  7431 V AudioCache: notify(0xb0222830, 200, 973, 0)
,07-27 09:05:01.105   319  7431 V AudioCache: ignored
07-27 09:05:01.105   319  7431 V AwesomePlayer: notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
07-27 09:05:01.105   319  7431 V AudioCache: notify(0xb0222830, 5, 0, 0)
07-27 09:05:01.105   319  7431 V AudioCache: ignored
,07-27 09:05:01.105   319  7431 V AwesomePlayer: notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
07-27 09:05:01.105   319  7431 V AudioCache: notify(0xb0222830, 1, 0, 0)
07-27 09:05:01.105   319  7431 V AudioCache: prepared
07-27 09:05:01.105   319  1090 V AudioCache: wait - success
,07-27 09:05:01.105   319  1090 V MediaPlayerService: start
07-27 09:05:01.105   319  1090 V StagefrightPlayer: start
,07-27 09:05:01.105   319  1090 V AwesomePlayer: play
,07-27 09:05:01.105   319  1090 V AwesomePlayer: AwesomePlayer::play_l():: This is not a DRM content
07-27 09:05:01.105   319  1090 V AwesomePlayer: startAudioPlayer_l, sendErrorNotification (0)
07-27 09:05:01.105   319  1090 D AudioPlayer: start of Playback, useOffload 0
,07-27 09:05:01.115  1197  1197 D SecKeyguardBottomAreaView: shortcut value[0-off / 1-camera] = 1,
07-27 09:05:01.115  1197  1197 D SecKeyguardBottomAreaView: mKidsModeEnabled= false
,07-27 09:05:01.115   319  7433 I OMXCodec: [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,07-27 09:05:01.115   319  7433 I OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-27 09:05:01.115   319  7433 I OMXCodec: >>>UHQA initOutputFormat 16
07-27 09:05:01.115   319  7433 I OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,07-27 09:05:01.115   319  1090 I AudioPlayer: Audio channels(2)
,07-27 09:05:01.115   319  1090 I AudioPlayer: Audioplayer kKeyAudioPCMFormat:0, 1, 0
07-27 09:05:01.115   319  1090 I AudioPlayer: Audioplayer kKeyAudioPCMFormat read fail(2, 1)
07-27 09:05:01.115   319  1090 V AudioCache: open(44100, 2, 0x0, 1, 0)
,07-27 09:05:01.125   319  1090 V AwesomePlayer: notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,07-27 09:05:01.125   319  7446 I AudioPlayer: First fillBuffer call!!
,07-27 09:05:01.125   319  7446 I AudioPlayer: >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
07-27 09:05:01.125   319  7446 E AudioPlayer: >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,07-27 09:05:01.135   319  1090 V AudioCache: notify(0xb0222830, 6, 0, 0)
07-27 09:05:01.135   319  1090 V AudioCache: ignored
07-27 09:05:01.135   319  1090 V AwesomePlayer: addBatteryData
,07-27 09:05:01.135   319  1090 V MediaPlayerService: wait for playback complete
,07-27 09:05:01.135  1197  1197 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardMessageArea$2@2952f8d6
07-27 09:05:01.135  1197  1197 V KeyguardUpdateMonitor: *** unregister callback for null
,07-27 09:05:01.175  1197  1197 D KeyguardUnlockView: mIsHelpTextEnabled= true
,07-27 09:05:01.175  1197  1197 D KeyguardUnlockView: hideBouncer mBouncerHelpText != null
,07-27 09:05:01.185  1197  1197 D KeyguardEffectViewUtil: wallpaperType :1
07-27 09:05:01.185  1197  1197 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
07-27 09:05:01.185  1197  1197 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-27 09:05:01.185  1197  1197 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.sec.SecKeyguardCircleView$1@2e0fdc4b
07-27 09:05:01.185  1197  1197 V KeyguardUpdateMonitor: *** unregister callback for null
,07-27 09:05:01.185  1197  1197 I SecAttributionInfoView: onAttachedToWindow
,07-27 09:05:01.185   319  7433 I OMXCodec: [OMX.google.vorbis.decoder] End Of Stream
,07-27 09:05:01.185   319  7446 V AwesomePlayer: postAudioEOS delayUs (0)
07-27 09:05:01.185  1197  1197 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
07-27 09:05:01.185  1197  1197 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,07-27 09:05:01.185   319  7431 V AwesomePlayer: onCheckAudioStatus
07-27 09:05:01.185   319  7431 V AwesomePlayer: onCheckAudioStatus() set AUDIO_AT_EOS flag
07-27 09:05:01.185   319  7431 V AwesomePlayer: onStreamDone
07-27 09:05:01.185   319  7431 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-27 09:05:01.185   319  7431 V AwesomePlayer: notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
07-27 09:05:01.185   319  7431 V AudioCache: notify(0xb0222830, 2, 0, 0)
07-27 09:05:01.185   319  7431 V AudioCache: playback complete - thread will wake up later
07-27 09:05:01.185   319  7431 V AwesomePlayer: notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
07-27 09:05:01.185   319  7431 V AudioCache: notify(0xb0222830, 7, 0, 0)
07-27 09:05:01.185   319  7431 V AudioCache: ignored
07-27 09:05:01.185   319  7431 V AwesomePlayer: cancelPlayerEvents (keepNotifications=1)
,07-27 09:05:01.195   319  7431 V AwesomePlayer: addBatteryData
07-27 09:05:01.195   319  1090 V AudioCache: wait - success
07-27 09:05:01.195   319  1090 V StagefrightPlayer: reset
,07-27 09:05:01.195  1197  1197 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
07-27 09:05:01.195   319  1090 V AwesomePlayer: reset_l()
07-27 09:05:01.195   319  1090 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:05:01.195   319  1090 V AudioCache: notify(0xb0222830, 8, 0, 0)
07-27 09:05:01.195   319  1090 V AudioCache: ignored
07-27 09:05:01.195   319  1090 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:05:01.195   319  1090 V AwesomePlayer: mAudioTrackVector clear
07-27 09:05:01.195   319  1090 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-27 09:05:01.195   319  1090 I OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-27 09:05:01.195   319  1090 I OMXCodec: [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
07-27 09:05:01.195  1197  1197 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,07-27 09:05:01.195   319  7433 I OMXCodec: [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,07-27 09:05:01.195  1197  1197 D KeyguardUpdateMonitor: sendKeyguardVisibilityChanged(true)
,07-27 09:05:01.195  1197  1197 D KeyguardViewMediator: adjustStatusBarLocked: mShowing=true mOccluded=false isSecure=false --> flags=0x3200000
07-27 09:05:01.195   319  1090 I OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
07-27 09:05:01.195   319  1090 I OggExtractor: OggSource::stop() mExtractor ref count = 1
07-27 09:05:01.195   319  1090 I OggExtractor: OggSource::~OggSource() mExtractor !mStarted ref count = 1
07-27 09:05:01.195   319  1090 I OggExtractor: ~OggSource --
07-27 09:05:01.195   319  1090 I OggExtractor: ~OggExtractor ++
07-27 09:05:01.195   319  1090 I OggExtractor: ~MyVorbisExtractor ++ 
07-27 09:05:01.195   319  1090 I OggExtractor: ~MyVorbisExtractor --
07-27 09:05:01.195   319  1090 I OggExtractor: ~OggExtractor --
,07-27 09:05:01.195   754  1528 D StatusBarManagerService: manageDisableList userId=0 what=0x3200000 pkg=com.android.systemui
,07-27 09:05:01.195   319  1090 I AudioPlayer: reset out
07-27 09:05:01.195   319  1090 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:05:01.195   319  1090 I SecVideoCapture: SecVideoCapture destructor
07-27 09:05:01.195   319  1090 I SecVideoCapture: reset
07-27 09:05:01.195   319  1090 V AwesomePlayer: mSecCapture clear
07-27 09:05:01.195   319  1090 I SecMediaClock: SecMediaClock destructor
07-27 09:05:01.195   319  1090 V AwesomePlayer: mSecMediaClock clear
,07-27 09:05:01.195   319  1090 V StagefrightPlayer: ~StagefrightPlayer
07-27 09:05:01.195   319  1090 V StagefrightPlayer: reset
07-27 09:05:01.195   319  1090 V AwesomePlayer: reset_l()
07-27 09:05:01.195   319  1090 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:05:01.195   319  1090 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:05:01.195   319  1090 V AwesomePlayer: mAudioTrackVector clear
07-27 09:05:01.195   319  1090 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
,07-27 09:05:01.205   319  1090 V AwesomePlayer: mSecCapture clear
07-27 09:05:01.205   319  1090 V AwesomePlayer: mSecMediaClock clear
07-27 09:05:01.205   319  1090 V AwesomePlayer: destructor
,07-27 09:05:01.205   754  1657 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 10067 pid: 1197) eventTime = 778951
07-27 09:05:01.205   319  1090 V AwesomePlayer: reset_l()
07-27 09:05:01.205   319  1090 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:05:01.205   319  1090 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:05:01.205   319  1090 V AwesomePlayer: mAudioTrackVector clear
07-27 09:05:01.205   319  1090 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:05:01.205   319  1090 V AwesomePlayer: mSecCapture clear
07-27 09:05:01.205   319  1090 V AwesomePlayer: mSecMediaClock clear
,07-27 09:05:01.205  1197  7430 V MediaPlayer: decode(67, 11863824, 11684)
07-27 09:05:01.205   319  2616 V MediaPlayerService: decode(27, 11863824, 11684)
07-27 09:05:01.205  1197  1197 V KeyguardDisplayManager: show
07-27 09:05:01.205  1197  1197 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:05:01.205  1197  1197 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-27 09:05:01.205  1197  1197 I KeyguardEffectViewController: *** don't update sliding image ***
,07-27 09:05:01.205  1197  1197 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
07-27 09:05:01.205  1197  1197 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 0 should be AT_MOST
,07-27 09:05:01.205   319  2616 V MediaPlayerService: player type = 3
,07-27 09:05:01.205   319  2616 V AwesomePlayer: setDefault
07-27 09:05:01.205   319  2616 V AwesomePlayer: constructor
,07-27 09:05:01.205   319  2616 V AwesomePlayer: setDefault
07-27 09:05:01.205   319  2616 V AwesomePlayer: reset_l()
,07-27 09:05:01.205   319  2616 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:05:01.205   319  2616 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:05:01.205   319  2616 V AwesomePlayer: mAudioTrackVector clear
07-27 09:05:01.205   319  2616 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:05:01.205   319  2616 V AwesomePlayer: mSecCapture clear
,07-27 09:05:01.205   319  2616 V AwesomePlayer: mSecMediaClock clear
07-27 09:05:01.205   319  2616 V StagefrightPlayer: StagefrightPlayer
07-27 09:05:01.205   319  2616 V AwesomePlayer: setListener
07-27 09:05:01.205   319  2616 V StagefrightPlayer: initCheck
07-27 09:05:01.205   319  2616 V AwesomePlayer: setAudioSink
,07-27 09:05:01.205   319  2616 V StagefrightPlayer: setDataSource(27, 11863824, 11684)
07-27 09:05:01.205   319  2616 V AwesomePlayer: reset_l()
07-27 09:05:01.205   319  2616 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:05:01.205   319  2616 V AudioCache: notify(0xb1a288d0, 8, 0, 0)
07-27 09:05:01.205   319  2616 V AudioCache: ignored
,07-27 09:05:01.205   319  2616 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:05:01.215   319  2616 V AwesomePlayer: mAudioTrackVector clear
07-27 09:05:01.215   319  2616 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:05:01.215   319  2616 V AwesomePlayer: mSecCapture clear
07-27 09:05:01.215   319  2616 V AwesomePlayer: mSecMediaClock clear
,07-27 09:05:01.215   319  2616 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
,07-27 09:05:01.215   319  2616 V AwesomePlayer: mBitrate = -1 bits/sec
07-27 09:05:01.215   319  2616 I OggExtractor: OggSource::OggSource() mExtractor ref count = 4
07-27 09:05:01.215   319  2616 V AwesomePlayer: current audio track index (0) is added to vector
07-27 09:05:01.215   319  2616 V AwesomePlayer: setDataSource_l: Audio(1), Video(0)
,07-27 09:05:01.215   319  2616 I AwesomePlayer: checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
07-27 09:05:01.215   319  2616 V MediaPlayerService: prepare
07-27 09:05:01.215   319  2616 V AwesomePlayer: prepareAsync
07-27 09:05:01.215   319  2616 V MediaPlayerService: wait for prepare
,07-27 09:05:01.215   319  7449 V AwesomePlayer: onPrepareAsyncEvent
07-27 09:05:01.215   319  7449 I SecMediaClock: SecMediaClock constructor
07-27 09:05:01.215   319  7449 I SecMediaClock: reset
07-27 09:05:01.215   319  7449 I SecVideoCapture: SecVideoCapture constructor
07-27 09:05:01.215   319  7449 I SecVideoCapture: reset
07-27 09:05:01.215   319  7449 V AwesomePlayer: initAudioDecoder
07-27 09:05:01.215   319  7449 V AwesomePlayer: checkOffloadExceptions is true
07-27 09:05:01.215   319  7449 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=499410 us, has_video=0
07-27 09:05:01.215   319  7449 V AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
,07-27 09:05:01.215   319  7449 I OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,07-27 09:05:01.215   754  1055 D StatusBarManagerService: manageDisableList userId=0 what=0x200000 pkg=WindowManager.LayoutParams
,07-27 09:05:01.225   319  7449 I OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,07-27 09:05:01.225   319  7449 I OMXCodec: >>>UHQA initOutputFormat 16
07-27 09:05:01.225   319  7449 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-27 09:05:01.225   319  7449 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=499410 us, has_video=0
07-27 09:05:01.225   319  7449 V AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
,07-27 09:05:01.225   319  7449 I OMXCodec: [OMX.google.vorbis.decoder] OMXCodec::start mState=1
07-27 09:05:01.225   319  7449 I OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-27 09:05:01.225   319  7449 I OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,07-27 09:05:01.225   319  7451 I OMXCodec: [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
07-27 09:05:01.225   319  7449 V AwesomePlayer: finishAsyncPrepare_l
07-27 09:05:01.225   319  7449 V AwesomePlayer: notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
07-27 09:05:01.225   319  7449 V AudioCache: notify(0xb1a288d0, 200, 973, 0)
07-27 09:05:01.225   319  7449 V AudioCache: ignored
07-27 09:05:01.225   319  7449 V AwesomePlayer: notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
07-27 09:05:01.225   319  7449 V AudioCache: notify(0xb1a288d0, 5, 0, 0)
07-27 09:05:01.225   319  7449 V AudioCache: ignored
07-27 09:05:01.225   319  7449 V AwesomePlayer: notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
07-27 09:05:01.225   319  7449 V AudioCache: notify(0xb1a288d0, 1, 0, 0)
07-27 09:05:01.225   319  7449 V AudioCache: prepared
07-27 09:05:01.225   319  2616 V AudioCache: wait - success
07-27 09:05:01.225   319  2616 V MediaPlayerService: start
07-27 09:05:01.225   319  2616 V StagefrightPlayer: start
07-27 09:05:01.225   319  2616 V AwesomePlayer: play
07-27 09:05:01.225   319  2616 V AwesomePlayer: AwesomePlayer::play_l():: This is not a DRM content
07-27 09:05:01.225   319  2616 V AwesomePlayer: startAudioPlayer_l, sendErrorNotification (0)
07-27 09:05:01.225   319  2616 D AudioPlayer: start of Playback, useOffload 0
,07-27 09:05:01.235   754  1451 D PowerManagerService: [api] setUserActivityTimeoutOverrideFromWindowManagerInternal: timeoutMillis: 10000
07-27 09:05:01.235   754  1451 D PowerManagerService: [api] setScreenDimDurationOverrideFromWindowManagerInternal: timeoutMillis: 0
,07-27 09:05:01.235   754  1057 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-27 09:05:01.235   754  1057 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 09:05:01.235   754  1057 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-27 09:05:01.235   754  1057 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-27 09:05:01.245   319  7451 I OMXCodec: [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
07-27 09:05:01.245   319  7451 I OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-27 09:05:01.245   319  7451 I OMXCodec: >>>UHQA initOutputFormat 16
,07-27 09:05:01.245   319  7451 I OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,07-27 09:05:01.245   319  2616 I AudioPlayer: Audio channels(1)
07-27 09:05:01.245  1197  1197 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
07-27 09:05:01.245   319  2616 I AudioPlayer: Audioplayer kKeyAudioPCMFormat:0, 1, 0
07-27 09:05:01.245  1197  1197 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1770 should be AT_MOST
07-27 09:05:01.245   319  2616 I AudioPlayer: Audioplayer kKeyAudioPCMFormat read fail(1, 1)
07-27 09:05:01.245   319  2616 V AudioCache: open(44100, 1, 0x0, 1, 0)
,07-27 09:05:01.245   319  2616 V AwesomePlayer: notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
07-27 09:05:01.245   319  2616 V AudioCache: notify(0xb1a288d0, 6, 0, 0)
07-27 09:05:01.245   319  2616 V AudioCache: ignored
07-27 09:05:01.245   319  2616 V AwesomePlayer: addBatteryData
,07-27 09:05:01.245   319  7453 I AudioPlayer: First fillBuffer call!!
07-27 09:05:01.245   319  2616 V MediaPlayerService: wait for playback complete
,07-27 09:05:01.245   319  7453 I AudioPlayer: >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
07-27 09:05:01.245   319  7453 E AudioPlayer: >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,07-27 09:05:01.265  1197  1197 D QSpanel : label top:23
07-27 09:05:01.265  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-27 09:05:01.265  1197  1197 D QSpanel : label top:23
07-27 09:05:01.265  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-27 09:05:01.265  1197  1197 D QSpanel : label top:23
07-27 09:05:01.265  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-27 09:05:01.265  1197  1197 D QSpanel : label top:0
07-27 09:05:01.265  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-27 09:05:01.265  1197  1197 D QSpanel : label top:23
07-27 09:05:01.265  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-27 09:05:01.265  1197  1197 D QSpanel : label top:0
07-27 09:05:01.265  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-27 09:05:01.265  1197  1197 D QSpanel : label top:0
07-27 09:05:01.265  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-27 09:05:01.265  1197  1197 D QSpanel : label top:0
07-27 09:05:01.265  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-27 09:05:01.265  1197  1197 D QSpanel : label top:0
07-27 09:05:01.265  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-27 09:05:01.265  1197  1197 D QSpanel : label top:0
07-27 09:05:01.265  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-27 09:05:01.265  1197  1197 D PhoneStatusBar: makeExpandedVisible:true
,07-27 09:05:01.265   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=com.android.systemui.statusbar.EXPANDED
,07-27 09:05:01.265   754  2987 D SSRM:a  : DeviceInfo:: 001000100000
07-27 09:05:01.275  1197  1197 D ScrimController: updateScrimKeyguard() mDozing=false, mBouncerShowing=false
07-27 09:05:01.275   754  2987 D SSRM:a  : SettingsAirViewInfo:: 010100000
,07-27 09:05:01.275  1197  1197 D KeyguardUpdateMonitor: handleKeyguardVisibilityChanged(1)
,07-27 09:05:01.275   319  7451 I OMXCodec: [OMX.google.vorbis.decoder] End Of Stream
,07-27 09:05:01.275   319  7453 V AwesomePlayer: postAudioEOS delayUs (0)
,07-27 09:05:01.275   754  1528 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 09:05:01.275   754  1528 D SecContentProvider2: mCursor = null
07-27 09:05:01.275   319  7449 V AwesomePlayer: onCheckAudioStatus
07-27 09:05:01.275   319  7449 V AwesomePlayer: onCheckAudioStatus() set AUDIO_AT_EOS flag
07-27 09:05:01.275   319  7449 V AwesomePlayer: onStreamDone
,07-27 09:05:01.275   319  7449 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-27 09:05:01.275   319  7449 V AwesomePlayer: notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
07-27 09:05:01.275   319  7449 V AudioCache: notify(0xb1a288d0, 2, 0, 0)
07-27 09:05:01.275  1197  1197 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME* RECENT* clock SEARCH* >
07-27 09:05:01.275   754  1657 D ActivityManager: startService callerProcessName:tv.peel.samsung.app, calleePkgName: tv.peel.samsung.app
,07-27 09:05:01.275   319  7449 V AudioCache: playback complete - thread will wake up later
07-27 09:05:01.275   319  7449 V AwesomePlayer: notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
07-27 09:05:01.275   754  1703 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 09:05:01.275   754  1657 D ActivityManager: caller:android.app.ApplicationThreadProxy@2162d88, r.packageName :tv.peel.samsung.app
07-27 09:05:01.275   754  1703 D SecContentProvider2: mCursor = null
07-27 09:05:01.275   319  7449 V AudioCache: notify(0xb1a288d0, 7, 0, 0)
,07-27 09:05:01.275   319  7449 V AudioCache: ignored
07-27 09:05:01.275   319  7449 V AwesomePlayer: cancelPlayerEvents (keepNotifications=1)
07-27 09:05:01.275   319  7449 V AwesomePlayer: addBatteryData
07-27 09:05:01.275   754   783 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 09:05:01.275   754   783 D SecContentProvider2: mCursor = null
,07-27 09:05:01.275   319  2616 V AudioCache: wait - success
07-27 09:05:01.275   319  2616 V StagefrightPlayer: reset
07-27 09:05:01.275   319  2616 V AwesomePlayer: reset_l()
07-27 09:05:01.275   319  2616 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:05:01.275   319  2616 V AudioCache: notify(0xb1a288d0, 8, 0, 0)
07-27 09:05:01.275   319  2616 V AudioCache: ignored
07-27 09:05:01.275   319  2616 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:05:01.275   319  2616 V AwesomePlayer: mAudioTrackVector clear
07-27 09:05:01.275   319  2616 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-27 09:05:01.275   319  2616 I OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-27 09:05:01.275   319  2616 I OMXCodec: [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
07-27 09:05:01.275   319  7451 I OMXCodec: [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
07-27 09:05:01.275   754  1446 D SecContentProvider2: uri = 14 selection = getSealedState
07-27 09:05:01.275   754  1446 D SecContentProvider2: mCursor = null
,07-27 09:05:01.285  1197  1197 D StatusBar-DoNotDistrub: isDisableAlert isDormantModeOn:false isNotificationDisabled:true
07-27 09:05:01.285  1197  1197 D WaterColor Keyguard: sound : onLoadComplete
,07-27 09:05:01.285  6403  6403 W ContextImpl: Implicit intents with startService are not safe: Intent { act=tv.peel.samsung.widget.service.IPeelService } android.content.ContextWrapper.bindService:559 tv.peel.samsung.widget.a.<init>:76 tv.peel.samsung.widget.NotiRemoteService.a:562 
07-27 09:05:01.285   319  2616 I OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,07-27 09:05:01.285   319  2616 I OggExtractor: OggSource::stop() mExtractor ref count = 1
07-27 09:05:01.285   319  2616 I OggExtractor: OggSource::~OggSource() mExtractor !mStarted ref count = 1
07-27 09:05:01.285   319  2616 I OggExtractor: ~OggSource --
07-27 09:05:01.285   319  2616 I OggExtractor: ~OggExtractor ++
,07-27 09:05:01.285   319  2616 I OggExtractor: ~MyVorbisExtractor ++ 
07-27 09:05:01.285   319  2616 I OggExtractor: ~MyVorbisExtractor --
07-27 09:05:01.285   319  2616 I OggExtractor: ~OggExtractor --
,07-27 09:05:01.285   319  2616 I AudioPlayer: reset out
,07-27 09:05:01.285   319  2616 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:05:01.285   319  2616 I SecVideoCapture: SecVideoCapture destructor
07-27 09:05:01.285   319  2616 I SecVideoCapture: reset
07-27 09:05:01.285   319  2616 V AwesomePlayer: mSecCapture clear
,07-27 09:05:01.285   319  2616 I SecMediaClock: SecMediaClock destructor
07-27 09:05:01.295   319  2616 V AwesomePlayer: mSecMediaClock clear
,07-27 09:05:01.295   319  2616 V StagefrightPlayer: ~StagefrightPlayer
07-27 09:05:01.295   319  2616 V StagefrightPlayer: reset
,07-27 09:05:01.295   319  2616 V AwesomePlayer: reset_l()
07-27 09:05:01.295   319  2616 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:05:01.295   319  2616 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
07-27 09:05:01.295   754  1657 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:05:01.295   319  2616 V AwesomePlayer: mAudioTrackVector clear
,07-27 09:05:01.295   319  2616 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:05:01.295   319  2616 V AwesomePlayer: mSecCapture clear
07-27 09:05:01.295   319  2616 V AwesomePlayer: mSecMediaClock clear
07-27 09:05:01.295   319  2616 V AwesomePlayer: destructor
,07-27 09:05:01.295   754  1657 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 09:05:01.295   754  1657 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 09:05:01.295   754  1657 D BatteryService: stay LED for fully charged
07-27 09:05:01.295   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:05:01.295   319  2616 V AwesomePlayer: reset_l()
07-27 09:05:01.295   319  2616 V AwesomePlayer: notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
07-27 09:05:01.295   319  2616 V AwesomePlayer: cancelPlayerEvents (keepNotifications=0)
,07-27 09:05:01.295   319  2616 V AwesomePlayer: mAudioTrackVector clear
07-27 09:05:01.295   319  2616 V AwesomePlayer: reset_l() mAudioPlayer successfully deleted
07-27 09:05:01.295   754   754 I MotionRecognitionService: Plugged
07-27 09:05:01.295   319  2616 V AwesomePlayer: mSecCapture clear
07-27 09:05:01.295   319  2616 V AwesomePlayer: mSecMediaClock clear
07-27 09:05:01.295  1197  1197 D WaterColor Keyguard: onWindowFocusChanged - true
07-27 09:05:01.295  1197  1197 D KeyguardUnlockView: Window is focused
,07-27 09:05:01.295   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:05:01.305  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:05:01.305  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
07-27 09:05:01.305   754   783 D ActivityManager: startService callerProcessName:tv.peel.samsung.app, calleePkgName: tv.peel.samsung.app
07-27 09:05:01.305   754   783 D ActivityManager: caller:android.app.ApplicationThreadProxy@449b05d, r.packageName :tv.peel.samsung.app
,07-27 09:05:01.305  1197  1197 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
07-27 09:05:01.305  1197  1197 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1770 should be AT_MOST
,07-27 09:05:01.305   754  1446 D ActivityManager: startService callerProcessName:tv.peel.samsung.app, calleePkgName: tv.peel.samsung.app
07-27 09:05:01.305   754  1446 D ActivityManager: caller:android.app.ApplicationThreadProxy@c0a9dd2, r.packageName :tv.peel.samsung.app
,07-27 09:05:01.315   754  1470 I ActivityManager: Killing 5213:com.google.android.music:main/u0a144 (adj 15): emptyCount ##41
,07-27 09:05:01.315   754  1059 I PowerManagerService: [PWL] Off : 5s ago
07-27 09:05:01.315   754  1059 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
07-27 09:05:01.315   754  1059 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,07-27 09:05:01.325  1197  1197 D QSpanel : label top:23
07-27 09:05:01.325  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-27 09:05:01.325  1197  1197 D QSpanel : label top:23
07-27 09:05:01.325  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-27 09:05:01.325  1197  1197 D QSpanel : label top:23
07-27 09:05:01.325  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-27 09:05:01.325  1197  1197 D QSpanel : label top:0
07-27 09:05:01.325  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-27 09:05:01.325  1197  1197 D QSpanel : label top:23
07-27 09:05:01.325  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-27 09:05:01.325  1197  1197 D QSpanel : label top:0
07-27 09:05:01.325  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-27 09:05:01.325  1197  1197 D QSpanel : label top:0
07-27 09:05:01.325  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-27 09:05:01.325  1197  1197 D QSpanel : label top:0
07-27 09:05:01.325  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-27 09:05:01.325  1197  1197 D QSpanel : label top:0
07-27 09:05:01.325  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-27 09:05:01.325  1197  1197 D QSpanel : label top:0
07-27 09:05:01.325  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-27 09:05:01.365  1197  1197 D Recents_AlternateRecentsComponent: isRecentsTopMost is getting called
,07-27 09:05:01.365  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:05:01.365  1197  1197 D WaterColor Keyguard: sound : onLoadComplete
,07-27 09:05:01.365  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:05:01.365  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:05:01.365  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:01.375  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:01.375  1197  1197 D KeyguardViewMediator: handleKeyguardDoneDrawing
,07-27 09:05:01.375  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:05:01.445  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 09:05:01.455  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 09:05:03.665   308   308 E SMD     : DCD ON
,07-27 09:05:06.005   754  1111 V AlarmManager: waitForAlarm result :8
,07-27 09:05:06.075   754  1111 V AlarmManager: waitForAlarm result :8
,07-27 09:05:06.205  1197  1197 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
,07-27 09:05:06.205  1197  1197 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1770 should be AT_MOST
,07-27 09:05:06.665   308   308 E SMD     : DCD ON
,07-27 09:05:07.545   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 309, CUR = 450
,07-27 09:05:09.075   754  1111 V AlarmManager: waitForAlarm result :8
,07-27 09:05:09.665   308   308 E SMD     : DCD ON
,07-27 09:05:11.325   754  1059 I PowerManagerService: [PWL] Off : 15s ago
,07-27 09:05:11.345   754  1639 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:05:11.355   754  1639 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:05:11.355   754  1639 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:05:11.355   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:05:11.365  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:05:11.365  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:05:11.375   754   754 I MotionRecognitionService: Plugged
,07-27 09:05:11.375   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:05:11.375   754  1639 D BatteryService: stay LED for fully charged
,07-27 09:05:11.385  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:05:11.395  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:05:11.395  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:05:11.395  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:11.395  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:11.395  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:12.665   308   308 E SMD     : DCD ON
,07-27 09:05:15.665   308   308 E SMD     : DCD ON
,07-27 09:05:17.595   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-27 09:05:18.665   308   308 E SMD     : DCD ON
,07-27 09:05:20.895   754  1347 E Watchdog: !@Sync 26
,07-27 09:05:21.675   308   308 E SMD     : DCD ON
,07-27 09:05:24.675   308   308 E SMD     : DCD ON
,07-27 09:05:26.325   754  1059 I PowerManagerService: [PWL] Off : 30s ago
,07-27 09:05:27.475   754  1111 V AlarmManager: waitForAlarm result :4
,07-27 09:05:27.505   754  1528 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 09:05:27.525   754  1111 D ActivityManager: caller:null, r.packageName :com.google.android.googlequicksearchbox
,07-27 09:05:27.535   754   783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:05:27.535   754   783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 09:05:27.545   754   783 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:05:27.545   754   783 D BatteryService: stay LED for fully charged
07-27 09:05:27.545   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:05:27.545  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:05:27.555  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:05:27.555  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:05:27.555  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:05:27.555  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:27.555  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:27.555  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:27.555  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:05:27.565   754   754 I MotionRecognitionService: Plugged
,07-27 09:05:27.565   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:05:27.575   754   754 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
,07-27 09:05:27.595   754   754 I BackgroundCompactionService: onStart. jobID=801
,07-27 09:05:27.605   754   754 I BackgroundCompactionService: onStart done. jobID=801
,07-27 09:05:27.615   754  1470 D ActivityManager: caller:android.app.ApplicationThreadProxy@362259f6, r.packageName :com.google.android.gms
,07-27 09:05:27.625   754  1221 D ActivityManager: caller:android.app.ApplicationThreadProxy@bbcf864, r.packageName :com.google.android.gms
,07-27 09:05:27.625   754  1446 D ActivityManager: caller:android.app.ApplicationThreadProxy@147c6acd, r.packageName :com.google.android.gms
,07-27 09:05:27.625   754   785 D ActivityManager: caller:android.app.ApplicationThreadProxy@9121f82, r.packageName :com.google.android.gms
,07-27 09:05:27.625   754  1451 D ActivityManager: caller:android.app.ApplicationThreadProxy@2dd3693, r.packageName :com.google.android.gms
,07-27 09:05:27.635   754  1318 D ActivityManager: caller:android.app.ApplicationThreadProxy@278336d0, r.packageName :com.google.android.gms
,07-27 09:05:27.635   754  1481 D ActivityManager: caller:android.app.ApplicationThreadProxy@271e6c9, r.packageName :com.google.android.gms
,07-27 09:05:27.635   754  1639 D ActivityManager: caller:android.app.ApplicationThreadProxy@746b1ce, r.packageName :com.google.android.gms
,07-27 09:05:27.635   754  1558 D ActivityManager: caller:android.app.ApplicationThreadProxy@369aa8ef, r.packageName :com.google.android.gms
,07-27 09:05:27.645   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,07-27 09:05:27.645   754  7468 I BackgroundCompactionService: Execute BGCompaction (type1). (1 times)
,07-27 09:05:27.655   754  7468 I BackgroundCompactionService: compact_memory command done
,07-27 09:05:27.675   308   308 E SMD     : DCD ON
,07-27 09:05:30.675   308   308 E SMD     : DCD ON
,07-27 09:05:33.675   308   308 E SMD     : DCD ON
,07-27 09:05:36.675   308   308 E SMD     : DCD ON
,07-27 09:05:37.585   754  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:05:37.685   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 450
,07-27 09:05:39.675   308   308 E SMD     : DCD ON
,07-27 09:05:42.675   308   308 E SMD     : DCD ON
,07-27 09:05:45.675   308   308 E SMD     : DCD ON
,07-27 09:05:46.325   754  1059 I PowerManagerService: [PWL] Off : 50s ago
,07-27 09:05:47.655   754  1639 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:05:47.655   754  1639 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:05:47.655   754  1639 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:05:47.655   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:05:47.665  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:05:47.675  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:05:47.675   754   754 I MotionRecognitionService: Plugged
,07-27 09:05:47.675   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:05:47.675   754  1639 D BatteryService: stay LED for fully charged
,07-27 09:05:47.705  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:05:47.705  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:47.705  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:05:47.705  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:05:47.705  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:47.715  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:47.725   754  2987 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 450
,07-27 09:05:48.675   308   308 E SMD     : DCD ON
,07-27 09:05:50.905   754  1347 E Watchdog: !@Sync 27
,07-27 09:05:51.675   308   308 E SMD     : DCD ON
,07-27 09:05:54.675   308   308 E SMD     : DCD ON
,07-27 09:05:57.685   308   308 E SMD     : DCD ON
,07-27 09:05:57.715   754  1221 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:05:57.715   754  1221 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:05:57.715   754  1221 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:05:57.725   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:05:57.735  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:05:57.735  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:05:57.735   754   754 I MotionRecognitionService: Plugged
,07-27 09:05:57.745   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:05:57.745   754  1221 D BatteryService: stay LED for fully charged
,07-27 09:05:57.755  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:05:57.765  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:05:57.765  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:05:57.775  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:57.775  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:57.775  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:57.785   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 311, CUR = 450
,07-27 09:05:59.995   754  1111 V AlarmManager: waitForAlarm result :8
,07-27 09:06:00.685   308   308 E SMD     : DCD ON
,07-27 09:06:03.685   308   308 E SMD     : DCD ON
,07-27 09:06:06.685   308   308 E SMD     : DCD ON
,07-27 09:06:07.775   754  1291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:06:07.825   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450
,07-27 09:06:09.685   308   308 E SMD     : DCD ON
,07-27 09:06:11.335   754  1059 I PowerManagerService: [PWL] Off : 75s ago
,07-27 09:06:12.685   308   308 E SMD     : DCD ON
,07-27 09:06:15.685   308   308 E SMD     : DCD ON
,07-27 09:06:17.835   754  1446 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:06:17.835   754  1446 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:06:17.835   754  1446 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:06:17.845   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:06:17.855  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:06:17.855  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:06:17.855   754   754 I MotionRecognitionService: Plugged
,07-27 09:06:17.865   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:06:17.865   754  1446 D BatteryService: stay LED for fully charged
,07-27 09:06:17.885  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:06:17.895  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:17.905   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450
,07-27 09:06:17.905  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:17.905  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:06:17.905  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:06:17.915  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:18.685   308   308 E SMD     : DCD ON
,07-27 09:06:20.905   754  1347 E Watchdog: !@Sync 28
,07-27 09:06:21.685   308   308 E SMD     : DCD ON
,07-27 09:06:24.685   308   308 E SMD     : DCD ON
,07-27 09:06:27.685   308   308 E SMD     : DCD ON
,07-27 09:06:27.895   754  1558 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:06:27.945   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450
,07-27 09:06:30.685   308   308 E SMD     : DCD ON
,07-27 09:06:33.695   308   308 E SMD     : DCD ON
,07-27 09:06:36.695   308   308 E SMD     : DCD ON
,07-27 09:06:37.955   754   783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:06:37.965   754   783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:06:37.965   754   783 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:06:37.965   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:06:37.975  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:06:37.985  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:06:37.985   754   754 I MotionRecognitionService: Plugged
,07-27 09:06:37.985   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:06:37.995   754   783 D BatteryService: stay LED for fully charged
,07-27 09:06:38.005   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450
,07-27 09:06:38.005  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:06:38.015  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:06:38.015  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:06:38.025  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:38.025  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:06:38.025  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:39.695   308   308 E SMD     : DCD ON
,07-27 09:06:41.335   754  1059 I PowerManagerService: [PWL] Off : 105s ago
,07-27 09:06:42.695   308   308 E SMD     : DCD ON
,07-27 09:06:45.695   308   308 E SMD     : DCD ON
,07-27 09:06:48.045   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450
,07-27 09:06:48.695   308   308 E SMD     : DCD ON
,07-27 09:06:50.905   754  1347 E Watchdog: !@Sync 29
,07-27 09:06:51.695   308   308 E SMD     : DCD ON
,07-27 09:06:54.695   308   308 E SMD     : DCD ON
,07-27 09:06:56.095   754  1111 V AlarmManager: waitForAlarm result :4
,07-27 09:06:56.115  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 09:06:56.115  1197  1197 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:06:56.125  1197  1197 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-27 09:06:56.125  1197  1197 I KeyguardEffectViewController: *** don't update sliding image ***
,07-27 09:06:56.155   754  1703 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:06:56.155   754  1703 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 09:06:56.155   754  1703 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 09:06:56.155   754  1703 D BatteryService: stay LED for fully charged
,07-27 09:06:56.165   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:06:56.175  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:06:56.175  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:06:56.175   754   754 I MotionRecognitionService: Plugged
,07-27 09:06:56.175   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:06:56.185  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:06:56.185  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:06:56.185  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:56.185  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:06:56.185  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:56.195  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:06:56.245  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 09:06:56.245  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 09:06:57.695   308   308 E SMD     : DCD ON
,07-27 09:06:58.095   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,07-27 09:06:59.995   754  1111 V AlarmManager: waitForAlarm result :8
,07-27 09:07:00.695   308   308 E SMD     : DCD ON
,07-27 09:07:03.695   308   308 E SMD     : DCD ON
,07-27 09:07:06.215   754  1446 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:07:06.225   754  1446 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:07:06.225   754  1446 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:07:06.225   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:07:06.235  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:07:06.235  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:07:06.245   754  1446 D BatteryService: stay LED for fully charged
,07-27 09:07:06.245   754   754 I MotionRecognitionService: Plugged,
07-27 09:07:06.255   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:07:06.255  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:07:06.265  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:07:06.265  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:07:06.275  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:06.275  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:07:06.275  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:06.695   308   308 E SMD     : DCD ON
,07-27 09:07:08.135   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-27 09:07:09.705   308   308 E SMD     : DCD ON
,07-27 09:07:12.705   308   308 E SMD     : DCD ON
,07-27 09:07:15.705   308   308 E SMD     : DCD ON
,07-27 09:07:16.285   754  1639 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:07:16.285   754  1639 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:07:16.285   754  1639 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:07:16.285   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:07:16.295  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:07:16.305  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:07:16.305   754   754 I MotionRecognitionService: Plugged
,07-27 09:07:16.305   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:07:16.315   754  1639 D BatteryService: stay LED for fully charged
,07-27 09:07:16.335  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:07:16.335   754  1059 I PowerManagerService: [PWL] Off : 140s ago
,07-27 09:07:16.345  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:16.355  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:07:16.355  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:07:16.355  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:16.355  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:18.065   754  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 09:07:18.065   754  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:07:18.065   754  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:07:18.205   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-27 09:07:18.705   308   308 E SMD     : DCD ON
,07-27 09:07:20.715   754  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 09:07:20.715   754  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:07:20.725   754  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:07:20.735   754  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:07:20.915   754  1347 E Watchdog: !@Sync 30
,07-27 09:07:21.705   308   308 E SMD     : DCD ON
,07-27 09:07:24.705   308   308 E SMD     : DCD ON
,07-27 09:07:26.365   754  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:07:26.365   754  1470 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:07:26.365   754  1470 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:07:26.375   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:07:26.385  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:07:26.385  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:07:26.385   754   754 I MotionRecognitionService: Plugged
,07-27 09:07:26.385   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:07:26.395   754  1470 D BatteryService: stay LED for fully charged
,07-27 09:07:26.405  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:07:26.415  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:07:26.415  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:07:26.425  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:26.425  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:07:26.425  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:27.705   308   308 E SMD     : DCD ON
,07-27 09:07:28.245   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:07:30.705   308   308 E SMD     : DCD ON
,07-27 09:07:33.705   308   308 E SMD     : DCD ON
,07-27 09:07:36.425   754  1291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:07:36.705   308   308 E SMD     : DCD ON
,07-27 09:07:38.295   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:07:39.705   308   308 E SMD     : DCD ON
,07-27 09:07:42.705   308   308 E SMD     : DCD ON
,07-27 09:07:45.715   308   308 E SMD     : DCD ON
,07-27 09:07:46.485   754  1221 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:07:46.485   754  1221 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:07:46.485   754  1221 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:07:46.495   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:07:46.505  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:07:46.505  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:07:46.515   754   754 I MotionRecognitionService: Plugged
,07-27 09:07:46.515   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:07:46.515   754  1221 D BatteryService: stay LED for fully charged
,07-27 09:07:46.535  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:07:46.555  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:46.555  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:07:46.555  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:07:46.565  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:46.565  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:48.345   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:07:48.715   308   308 E SMD     : DCD ON
,07-27 09:07:50.915   754  1347 E Watchdog: !@Sync 31
,07-27 09:07:51.715   308   308 E SMD     : DCD ON
,07-27 09:07:54.715   308   308 E SMD     : DCD ON
,07-27 09:07:56.345   754  1059 I PowerManagerService: [PWL] Off : 180s ago
,07-27 09:07:56.545   754  1558 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:07:56.545   754  1558 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:07:56.545   754  1558 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:07:56.555   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:07:56.565  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:07:56.565  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:07:56.565   754   754 I MotionRecognitionService: Plugged
,07-27 09:07:56.575   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:07:56.575   754  1558 D BatteryService: stay LED for fully charged
,07-27 09:07:56.595  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:07:56.605  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:56.605  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:07:56.605  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:07:56.615  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:56.625  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:57.715   308   308 E SMD     : DCD ON
,07-27 09:07:58.385   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:08:00.715   308   308 E SMD     : DCD ON
,07-27 09:08:03.715   308   308 E SMD     : DCD ON
,07-27 09:08:06.605   754  1528 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:08:06.605   754  1528 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:08:06.615   754  1528 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:08:06.615   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:08:06.625  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:08:06.625  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:08:06.625   754   754 I MotionRecognitionService: Plugged
,07-27 09:08:06.635   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:08:06.635   754  1528 D BatteryService: stay LED for fully charged
,07-27 09:08:06.655  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:08:06.655  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:08:06.655  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:08:06.665  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:08:06.675  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:08:06.675  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:08:06.715   308   308 E SMD     : DCD ON
,07-27 09:08:08.435   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:08:09.715   308   308 E SMD     : DCD ON
,07-27 09:08:12.715   308   308 E SMD     : DCD ON
,07-27 09:08:15.715   308   308 E SMD     : DCD ON
,07-27 09:08:16.665   754  1593 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:08:18.475   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:08:18.715   308   308 E SMD     : DCD ON
,07-27 09:08:20.915   754  1347 E Watchdog: !@Sync 32
,07-27 09:08:21.715   308   308 E SMD     : DCD ON
,07-27 09:08:24.725   308   308 E SMD     : DCD ON
,07-27 09:08:26.725   754  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:08:26.725   754  1470 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:08:26.735   754  1470 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:08:26.735   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:08:26.745  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:08:26.745  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:08:26.755   754  1470 D BatteryService: stay LED for fully charged
,07-27 09:08:26.765   754   754 I MotionRecognitionService: Plugged
,07-27 09:08:26.765  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:08:26.775   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:08:26.785  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:08:26.785  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:08:26.795  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:08:26.795  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:08:26.805  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:08:27.725   308   308 E SMD     : DCD ON
,07-27 09:08:28.525   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:08:30.725   308   308 E SMD     : DCD ON
,07-27 09:08:33.725   308   308 E SMD     : DCD ON
,07-27 09:08:36.725   308   308 E SMD     : DCD ON
,07-27 09:08:36.785   754  1291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:08:36.785   754  1291 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:08:36.795   754  1291 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:08:36.795   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:08:36.805  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:08:36.805  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:08:36.815   754   754 I MotionRecognitionService: Plugged
,07-27 09:08:36.815   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:08:36.825   754  1291 D BatteryService: stay LED for fully charged
,07-27 09:08:36.835  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:08:36.845  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:08:36.855  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:08:36.855  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:08:36.865  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:08:36.865  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:08:38.565   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:08:39.725   308   308 E SMD     : DCD ON
,07-27 09:08:41.345   754  1059 I PowerManagerService: [PWL] Off : 225s ago
,07-27 09:08:42.725   308   308 E SMD     : DCD ON
,07-27 09:08:45.725   308   308 E SMD     : DCD ON
,07-27 09:08:46.845   754  1580 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:08:48.615   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:08:48.725   308   308 E SMD     : DCD ON
,07-27 09:08:50.915   754  1347 E Watchdog: !@Sync 33
,07-27 09:08:51.725   308   308 E SMD     : DCD ON
,07-27 09:08:54.725   308   308 E SMD     : DCD ON
,07-27 09:08:56.915   754  1291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:08:57.725   308   308 E SMD     : DCD ON
,07-27 09:08:58.665   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:09:00.735   308   308 E SMD     : DCD ON
,07-27 09:09:03.735   308   308 E SMD     : DCD ON
,07-27 09:09:06.735   308   308 E SMD     : DCD ON
,07-27 09:09:06.975   754  1221 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:09:06.975   754  1221 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:09:06.975   754  1221 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 09:09:06.985   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:09:06.995  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:09:06.995  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:09:07.005   754  1221 D BatteryService: stay LED for fully charged
,07-27 09:09:07.015   754   754 I MotionRecognitionService: Plugged
,07-27 09:09:07.025  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:09:07.025   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:09:07.035  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:09:07.035  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:09:07.045  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:09:07.045  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:09:07.045  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:09:08.705   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:09:09.735   308   308 E SMD     : DCD ON
,07-27 09:09:12.735   308   308 E SMD     : DCD ON
,07-27 09:09:15.735   308   308 E SMD     : DCD ON
,07-27 09:09:18.735   308   308 E SMD     : DCD ON
,07-27 09:09:18.755   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-27 09:09:20.845   754  1111 V AlarmManager: waitForAlarm result :4
,07-27 09:09:20.905   754  1446 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:09:20.905   754  1446 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-27 09:09:20.905   754  1446 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 09:09:20.905   754  1446 D BatteryService: stay LED for fully charged
,07-27 09:09:20.915  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 09:09:20.915  1197  1197 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:09:20.915  1197  1197 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-27 09:09:20.915  1197  1197 I KeyguardEffectViewController: *** don't update sliding image ***
,07-27 09:09:20.925   754  1347 E Watchdog: !@Sync 34
,07-27 09:09:20.925   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:09:20.935  2926  2926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:09:20.935  2926  6430 D HeadsetStateMachine: Disconnected process message: 10
,07-27 09:09:20.935   754   754 I MotionRecognitionService: Plugged
,07-27 09:09:20.945   754   754 I MotionRecognitionService: setPowerConnected  = true
,07-27 09:09:20.955  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:09:20.955  1562  6780 D GCM     : Message class com.google.f.a.a.i
,07-27 09:09:20.955   754  1528 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 09:09:20.955   754   785 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 09:09:20.965  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 09:09:20.975  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:09:20.975  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:09:20.975  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:09:20.995  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:09:21.005   754  1221 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 09:09:21.045  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 09:09:21.045  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 09:09:21.065   754  1318 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-27 09:09:21.065   754  1318 D ActivityManager: caller:android.app.ApplicationThreadProxy@22f32ca6, r.packageName :com.google.android.gms
,07-27 09:09:21.225   754  1580 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 09:09:21.735   308   308 E SMD     : DCD ON
,07-27 09:09:24.735   308   308 E SMD     : DCD ON
,07-27 09:09:27.735   308   308 E SMD     : DCD ON
,07-27 09:09:28.795   754  2987 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450

```
