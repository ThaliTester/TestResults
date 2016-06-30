#### Test 72145431fdae11f_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
06-30 10:35:10.540  6380  6380 D UMC:AdminManager: loadAdmins
06-30 10:35:10.540  6380  6380 D UMC:AdminManager: startPolicyHandlers
06-30 10:35:10.550  6380  6380 I UMC:TestPolicyHandler: Setup is called in testpolicyhandler
06-30 10:35:10.550  6380  6380 D UMC:AdminManager: init - end
06-30 10:35:10.550  6380  6380 V UMC:AlarmHandler: Enter loadList
06-30 10:35:10.570  6380  6380 D GSLBManager: migrateStoredUrlFromOldPref
06-30 10:35:10.580  6380  6380 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
06-30 10:35:10.580  6380  6380 D UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
06-30 10:35:10.580  6380  6380 E UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
06-30 10:35:10.580  6380  6380 D UMC:UMCAdmin: deactivateUMCAdmin : -1
06-30 10:35:10.580  6380  6380 D UMC:UMCAdmin: isContainer : 0
06-30 10:35:10.580   752  1482 W LicenseLogService: log() failed
06-30 10:35:10.580   752  1550 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
06-30 10:35:10.580  6380  6380 E UMC:UMCAdmin: No active admin owned by uid 10201
06-30 10:35:10.580  6380  6380 D UMC:UMCAdmin: isContainer : 0
06-30 10:35:10.590  6380  6380 D UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
06-30 10:35:10.590  6380  6380 V UMC:AlarmHandler: onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
06-30 10:35:10.590  6380  6380 D QuickStartReceiver: Msg Id : 2
06-30 10:35:10.590  6380  6380 D QuickStartReceiver: model : SM-N9005
06-30 10:35:10.590  6380  6380 D QuickStartReceiver: id : 100
--------- beginning of system
06-30 10:35:10.590   752  1474 I ActivityManager: Killing 5568:com.sec.providers.settingsearch/u0a191 (adj 15): emptyCount ##41
,06-30 10:35:10.990  6427  6427 D AndroidRuntime: 
06-30 10:35:10.990  6427  6427 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 10:35:11.000  6427  6427 D AndroidRuntime: CheckJNI is OFF
06-30 10:35:11.000  6427  6427 D AndroidRuntime: readGMSProperty: start
06-30 10:35:11.000  6427  6427 D AndroidRuntime: readGMSProperty: already setted!!
06-30 10:35:11.000  6427  6427 D AndroidRuntime: readGMSProperty: end
06-30 10:35:11.000  6427  6427 D AndroidRuntime: addProductProperty: start
06-30 10:35:11.130  6427  6427 E AffinityControl: AffinityControl: registerfunction enter
06-30 10:35:11.150  6427  6427 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 10:35:11.160   752  1975 E PersonaManagerService: inState():  stateMachine is null !!
06-30 10:35:11.160   752  1975 I PersonaManagerService: PersonaId don't exist
06-30 10:35:11.160   752  1975 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
06-30 10:35:11.160   752  1975 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-30 10:35:11.160   752  1975 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 10:35:11.160   752  1975 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
06-30 10:35:11.180   752  1975 W ActivityManager: mDVFSHelper.acquire()
06-30 10:35:11.180   752  1975 D FocusedStackFrame: Set to : 0
06-30 10:35:11.180   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:11.180   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:11.180   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:11.180   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:11.220  6441  6441 E Zygote  : MountEmulatedStorage()
06-30 10:35:11.220  6441  6441 E Zygote  : v2
06-30 10:35:11.220  6441  6441 I libpersona: KNOX_SDCARD checking this for 10079
06-30 10:35:11.220  6441  6441 I libpersona: KNOX_SDCARD not a persona
06-30 10:35:11.220   752  1975 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6441 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-30 10:35:11.240  6441  6441 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:11.240  6441  6441 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 10:35:11.240  6441  6441 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
06-30 10:35:11.240  6427  6427 D AndroidRuntime: Shutting down VM
06-30 10:35:11.270  6441  6441 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:35:11.270  6441  6441 D ActivityThread: Added TimaKeyStore provider
06-30 10:35:11.280   752   752 V ActivityManager: Display changed displayId=0
06-30 10:35:11.300   752  3003 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:11.310  1445  1445 D SurfaceWidgetView: destroyHardwareResources():316904490
06-30 10:35:11.310  6441  6441 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
06-30 10:35:11.350   266   928 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
06-30 10:35:11.350   266   451 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
06-30 10:35:11.360  1445  1445 V ActivityThread: updateVisibility : ActivityRecord{30107fb5 token=android.os.BinderProxy@258e1f55 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-30 10:35:11.360  1445  1445 D Launcher: onTrimMemory. Level: 20
06-30 10:35:11.360  1816  1837 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
06-30 10:35:11.390  6441  6441 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
06-30 10:35:11.390  6441  6441 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
06-30 10:35:11.400   752  3003 D SSRM:n  : SIOP:: AP = 340, PST = 389, CUR = 450
06-30 10:35:11.410  6441  6441 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2441-2443)
06-30 10:35:11.410  6441  6441 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:11.430  6441  6441 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {195a45d}
06-30 10:35:11.430  6441  6441 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:11.430  6441  6441 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 10:35:11.450  6441  6441 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 10:35:11.460  6441  6441 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 10:35:11.460  6441  6441 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 10:35:11.470  6441  6460 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
06-30 10:35:11.470  6441  6441 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
06-30 10:35:11.470  6441  6441 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
06-30 10:35:11.470  6441  6441 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
06-30 10:35:11.480  6441  6441 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
06-30 10:35:11.480  6441  6441 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
06-30 10:35:11.480  6441  6441 I Adreno-EGL: Build Date: 11/19/14 Wed
06-30 10:35:11.480  6441  6441 I Adreno-EGL: Local Branch: mybranch5813579
06-30 10:35:11.480  6441  6441 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
06-30 10:35:11.480  6441  6441 I Adreno-EGL: Local Patches: NONE
06-30 10:35:11.480  6441  6441 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
06-30 10:35:11.580  6441  6469 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
06-30 10:35:11.610  6441  6441 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 10:35:11.620  6441  6441 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 10:35:11.630  6441  6441 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
06-30 10:35:11.640  6441  6441 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 10:35:11.640  6441  6441 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 10:35:11.680  6441  6441 D Activity: performCreate Call secproduct feature valuefalse
06-30 10:35:11.680  6441  6441 D Activity: performCreate Call debug elastic valuetrue
06-30 10:35:11.690  6441  6482 D OpenGLRenderer: Render dirty regions requested: true
06-30 10:35:11.690   752  1469 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
06-30 10:35:11.690   752  1469 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-30 10:35:11.690   752  1469 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
06-30 10:35:11.690   752   752 D KnoxTimeoutHandler: handleActiveUserChange for user 0
06-30 10:35:11.690   752   752 D PersonaManagerService: getPersonasForUser(): returning null!
06-30 10:35:11.710   266   266 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
06-30 10:35:11.720  6441  6482 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 10:35:11.730  6441  6482 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3ca7fb0 ,&mEglDisplay = 1 , &mEglConfig = 8 
06-30 10:35:11.730  6441  6482 D OpenGLRenderer: Enabling debug mode 0
06-30 10:35:11.740  6441  6441 V ActivityThread: updateVisibility : ActivityRecord{1b23fcef token=android.os.BinderProxy@18be1ac9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
06-30 10:35:11.770  6441  6441 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@18be1ac9 time:102808
06-30 10:35:11.790   752  1044 W ActivityManager: mDVFSHelper.release()
06-30 10:35:11.790   752  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{58cefeb u0 com.test.thalitest/.MainActivity t21} time:102828
06-30 10:35:11.800   752  1044 D MultiWindowConverter: This application or window do not support multiwindow
06-30 10:35:11.850  6441  6441 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6441
06-30 10:35:11.980  6441  6441 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 10:35:12.120  6441  6486 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358969216
06-30 10:35:12.130  6441  6486 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 10:35:12.130  6441  6486 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 10:35:12.130  6441  6486 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 10:35:12.130  6441  6486 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 10:35:12.130  6441  6486 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 10:35:12.130  6441  6486 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cf3ffdf added. We now have 1 listener(s)
06-30 10:35:12.140  6441  6486 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:2A:28:2D
06-30 10:35:12.140  6441  6486 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
06-30 10:35:12.140  6441  6486 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 10:35:12.150  6441  6486 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 10:35:12.160  6441  6486 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 10:35:12.160  6441  6486 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 10:35:12.160  6441  6486 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 10:35:12.160  6441  6486 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:2A:28:2D
06-30 10:35:12.160  6441  6486 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 10:35:12.160  6441  6486 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 10:35:12.160  6441  6486 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 10:35:12.160  6441  6486 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 10:35:12.160  6441  6486 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 10:35:12.160  6441  6486 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 10:35:12.160  6441  6486 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 10:35:12.160  6441  6486 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f52d48a added. We now have 1 listener(s)
06-30 10:35:12.160  6441  6486 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 10:35:12.160  6441  6486 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:12.160  6441  6486 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 10:35:12.160  6441  6486 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 10:35:12.160  6441  6486 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 10:35:12.160  6441  6486 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 10:35:12.170  6441  6486 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 10:35:12.170  6441  6486 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 10:35:12.170  6441  6486 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:2A:28:2D
06-30 10:35:12.170  6441  6486 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:12.170  6441  6486 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:35:12.170  6441  6486 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:12.170  6441  6486 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:35:12.170  6441  6486 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:35:12.170  6441  6486 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:35:12.170  6441  6486 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:12.170  6441  6486 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:12.170  6441  6486 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:35:12.170  6441  6486 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 10:35:12.170  6441  6486 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 10:35:12.170  6441  6486 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 10:35:12.200  6441  6441 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 10:35:12.310   299   299 E SMD     : DCD ON
,06-30 10:35:13.010  6441  6456 I art     : Background sticky concurrent mark sweep GC freed 69022(4MB) AllocSpace objects, 16(1524KB) LOS objects, 17% free, 21MB/25MB, paused 3.608ms total 128.416ms
,06-30 10:35:13.200  6441  6491 W jxcore-log: Initializing JXcore engine
06-30 10:35:13.200  6441  6491 W jxcore-log: JXcore engine is ready
,06-30 10:35:13.250  1956  1956 E auditd  : In denial and Property audit_ondenial is set to 1 
06-30 10:35:13.250  1956  1956 E audit   : type=1400 msg=audit(1467275713.250:201): avc:  denied  { ioctl } for  pid=6491 comm="Thread-1088" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
06-30 10:35:13.250  1956  1956 E audit   :  SEPF_SM-N9005_5.0-1_0032
06-30 10:35:13.250  1956  1956 E audit   : 
06-30 10:35:13.250   752  1032 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
06-30 10:35:13.250   752  1032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
06-30 10:35:13.250   752   999 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,06-30 10:35:13.250   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:13.250   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:13.250   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:13.250   752  1032 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent,
,06-30 10:35:13.250   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0,
06-30 10:35:13.260  1956  1956 E audit   : type=1300 msg=audit(1467275713.250:201): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=997e08d8 items=0 ppid=328 ppcomm=main pid=6491 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1088" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null),
,06-30 10:35:13.260  1956  1956 E audit   : type=1320 msg=audit(1467275713.250:201): ,
,06-30 10:35:13.270  6441  6491 W jxcore-log: Starting JXcore engine
,06-30 10:35:13.350   752   999 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6493 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 10:35:13.360  6493  6493 E Zygote  : MountEmulatedStorage()
,06-30 10:35:13.360  6493  6493 E Zygote  : v2
06-30 10:35:13.360  6493  6493 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:35:13.360  6493  6493 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:13.390  6493  6493 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:13.390  6441  6491 W jxcore-log: Platform android
06-30 10:35:13.390  6441  6491 W jxcore-log: 
06-30 10:35:13.390  6493  6493 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 10:35:13.390  6441  6491 W jxcore-log: Process ARCH arm
06-30 10:35:13.390  6441  6491 W jxcore-log: 
06-30 10:35:13.390  6493  6493 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:13.430  6493  6493 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:13.430  6493  6493 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:13.440  6493  6493 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,06-30 10:35:13.460  6493  6493 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,06-30 10:35:13.460  6493  6493 D SecurityLogAgent:  SeDenialReceiver : File path = null
,06-30 10:35:13.460   752  1742 I ActivityManager: Killing 5701:com.samsung.android.app.FileShareServer/u0a88 (adj 15): emptyCount ##41
,06-30 10:35:13.640  6441  6491 I jxcore-log: JXcore Cordova bridge is ready!
06-30 10:35:13.640  6441  6491 I jxcore-log: 
,06-30 10:35:13.640  6441  6491 W jxcore-log: JXcore engine is started
,06-30 10:35:13.640  6441  6486 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 10:35:13.650  6441  6441 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-30 10:35:15.310   299   299 E SMD     : DCD ON
,06-30 10:35:17.890   752  1338 E Watchdog: !@Sync 3
,06-30 10:35:18.310   299   299 E SMD     : DCD ON
,06-30 10:35:19.450   337   337 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 10:35:19.450   337   337 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 10:35:19.980   752  1691 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:35:19.980   752  1691 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 10:35:19.980   752  1691 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:35:19.980   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:35:19.990   752  1691 D BatteryService: stay LED for fully charged
06-30 10:35:19.990   752   752 I MotionRecognitionService: Plugged
06-30 10:35:19.990   752   752 I MotionRecognitionService: setPowerConnected  = true
06-30 10:35:19.990  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:35:19.990  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 10:35:19.990  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:35:20.000  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:35:20.000  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:35:20.000  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:35:20.590   752  1065 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,06-30 10:35:20.590   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,06-30 10:35:20.600   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,06-30 10:35:20.600   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,06-30 10:35:20.620   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,06-30 10:35:20.630   752  1122 I InputReader: Reconfiguring input devices.  changes=0x00000010
,06-30 10:35:20.640  3516  3516 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.sec.enterprise.knox.cloudmdm.smdms, uid = -1
,06-30 10:35:20.640  1418  1418 D RegisteredServicesCache: empty dynamic service
,06-30 10:35:20.650   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,06-30 10:35:20.660   752  1975 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 10:35:20.660   752  1975 D ActivityManager: caller:android.app.ApplicationThreadProxy@2018d1a1, r.packageName :com.google.android.gms
,06-30 10:35:20.670  1445  1445 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,06-30 10:35:20.670  1445  1445 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 10:35:20.670  1445  1445 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,06-30 10:35:20.670  1758  6529 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,06-30 10:35:20.680   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,06-30 10:35:20.690   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:20.700   752  1463 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:20.700   752  1463 D ActivityManager: caller:android.app.ApplicationThreadProxy@1fcfe6dd, r.packageName :com.google.android.gms
,06-30 10:35:20.700   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:20.700   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:20.700   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:20.700   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:20.700   752  1643 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:20.700  1445  1445 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
06-30 10:35:20.700   752  1643 D ActivityManager: caller:android.app.ApplicationThreadProxy@20578c4c, r.packageName :com.google.android.gms
,06-30 10:35:20.700   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:20.700   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:20.710  1445  1445 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:35:20.710  1445  1445 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 10:35:20.710  1445  1445 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,06-30 10:35:20.710  1445  1445 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,06-30 10:35:20.710  1445  1445 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 10:35:20.710  1445  1445 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,06-30 10:35:20.720   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,06-30 10:35:20.720  1758  6540 I PeopleContactsSync: CP2 sync disabled
,06-30 10:35:20.730   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,06-30 10:35:20.730   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:20.730   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,06-30 10:35:20.740   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,06-30 10:35:20.740   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,06-30 10:35:20.740   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,06-30 10:35:20.750   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:20.750   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:20.750   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:20.750   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,06-30 10:35:20.750   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,06-30 10:35:20.760   752   752 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,06-30 10:35:20.760   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:20.760   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:20.760   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:35:20.760   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 10:35:20.760   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:35:20.760   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:35:20.760   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 10:35:20.760   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:35:20.760   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 10:35:20.760   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:20.820   752  1441 I art     : Explicit concurrent mark sweep GC freed 159157(9MB) AllocSpace objects, 17(2MB) LOS objects, 30% free, 35MB/51MB, paused 1.450ms total 114.746ms
,06-30 10:35:20.820   752  1441 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
06-30 10:35:20.820   752  1441 D SecContentProvider2: mCursor = null
,06-30 10:35:20.830   752   776 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:20.830   752   776 D ActivityManager: caller:android.app.ApplicationThreadProxy@e4e45b0, r.packageName :com.google.android.gms
,06-30 10:35:20.870   752  1251 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,06-30 10:35:20.870   752  1251 D ActivityManager: caller:android.app.ApplicationThreadProxy@6af7c29, r.packageName :com.google.android.googlequicksearchbox
,06-30 10:35:20.880   752  1441 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,06-30 10:35:20.880  1619  6542 I UpdateIcingCorporaServi: Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
06-30 10:35:20.880   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:20.880   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:20.880   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:20.880   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:20.920  6543  6543 E Zygote  : MountEmulatedStorage()
06-30 10:35:20.920  6543  6543 E Zygote  : v2
06-30 10:35:20.920  6543  6543 I libpersona: KNOX_SDCARD checking this for 10088
06-30 10:35:20.920  6543  6543 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:20.930   752  1441 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6543 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:20.940  1619  6542 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 59 ms] updated apps [took 59 ms] 
,06-30 10:35:20.970  6543  6543 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,06-30 10:35:20.970  6543  6543 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:20.970  6543  6543 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:20.990  6543  6543 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:20.990  6543  6543 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:21.000  6543  6543 D ResourcesManager: creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,06-30 10:35:21.020   752  1144 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,06-30 10:35:21.020   752  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@678ad4f, r.packageName :com.samsung.android.app.galaxyfinder
06-30 10:35:21.020  6543  6543 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,06-30 10:35:21.040  5779  5779 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,06-30 10:35:21.050   752  1550 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,06-30 10:35:21.050   752  1550 D ActivityManager: caller:android.app.ApplicationThreadProxy@204a0cdc, r.packageName :com.google.android.apps.plus
,06-30 10:35:21.060   752  1691 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,06-30 10:35:21.060   752  1691 D ActivityManager: caller:android.app.ApplicationThreadProxy@392fb4ba, r.packageName :com.google.android.apps.plus
,06-30 10:35:21.070   752  1144 I ActivityManager: Killing 5426:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 15): emptyCount ##41
,06-30 10:35:21.160  5611  5611 D FactoryTest: Not factory mode
,06-30 10:35:21.160  5611  5611 D FactoryTest: Not factory mode. isFactoryMode() returend false
,06-30 10:35:21.160  5611  5611 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
06-30 10:35:21.160  5611  5611 D MTPRx   : still no open session command from host, so toast
,06-30 10:35:21.160  5611  5611 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1583 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 android.os.Handler.dispatchMessage:102 
,06-30 10:35:21.160  5611  5611 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.app.ContextImpl.startActivity:1584 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 
06-30 10:35:21.160  5611  5611 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:112196
,06-30 10:35:21.160   752  1975 E PersonaManagerService: inState():  stateMachine is null !!
06-30 10:35:21.160   752  1975 I PersonaManagerService: PersonaId don't exist
06-30 10:35:21.160   752  1975 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,06-30 10:35:21.160   752  1975 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,06-30 10:35:21.160   752  1975 I ActivityManager: START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,06-30 10:35:21.170   752  1975 W ActivityManager: mDVFSHelper.acquire()
,06-30 10:35:21.180   752  3003 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:21.180   752  1065 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
06-30 10:35:21.180  5611  5611 E MTPRx   : started activity for popup
,06-30 10:35:21.210  5611  5611 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,06-30 10:35:21.220  5611  5611 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,06-30 10:35:21.220  5611  5611 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
06-30 10:35:21.220  5611  5611 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,06-30 10:35:21.220  5611  5611 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:35:21.220  5611  5611 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 10:35:21.220  5611  5611 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,06-30 10:35:21.230  5611  5611 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,06-30 10:35:21.250  5611  5611 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,06-30 10:35:21.270  5611  5611 D Activity: performCreate Call secproduct feature valuefalse
,06-30 10:35:21.270  5611  5611 D Activity: performCreate Call debug elastic valuetrue
,06-30 10:35:21.280  6441  6441 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,06-30 10:35:21.280  6441  6441 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,06-30 10:35:21.280  6441  6441 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
06-30 10:35:21.280  6441  6441 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,06-30 10:35:21.280   752  1441 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,06-30 10:35:21.280   752  1441 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-30 10:35:21.280   752  1441 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
06-30 10:35:21.280   752   752 D KnoxTimeoutHandler: handleActiveUserChange for user 0
06-30 10:35:21.280   752   752 D PersonaManagerService: getPersonasForUser(): returning null!
,06-30 10:35:21.300  6441  6441 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
06-30 10:35:21.300  6441  6441 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,06-30 10:35:21.300  6441  6441 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1d093c64 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@7caa0ec, 16908290=android.view.AbsSavedState$1@7caa0ec}, android:focusedViewId=100}]}]
06-30 10:35:21.300  6441  6441 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
06-30 10:35:21.300  6441  6441 V ActivityThread: updateVisibility : ActivityRecord{1b23fcef token=android.os.BinderProxy@18be1ac9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
06-30 10:35:21.300  6441  6441 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
06-30 10:35:21.300  6441  6441 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,06-30 10:35:21.300  6441  6441 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@18be1ac9 time:112332
,06-30 10:35:21.310   299   299 E SMD     : DCD ON
,06-30 10:35:21.440   752  3003 D SSRM:n  : SIOP:: AP = 370, PST = 386, CUR = 450
,06-30 10:35:21.610   752  3003 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:23.820  6441  6491 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
06-30 10:35:23.820  6441  6491 I jxcore-log: 
,06-30 10:35:23.820  6441  6491 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
06-30 10:35:23.820  6441  6491 I jxcore-log: ,
,06-30 10:35:23.820  6441  6491 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 10:35:23.820  6441  6491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,06-30 10:35:23.820  6441  6491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:23.820  6441  6491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
,06-30 10:35:23.820  6441  6491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false,
06-30 10:35:23.820  6441  6491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,06-30 10:35:23.820  6441  6491 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:23.820  6441  6491 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,06-30 10:35:23.820  6441  6491 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 10:35:23.820  6441  6491 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 10:35:23.820  6441  6491 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,06-30 10:35:23.820  6441  6491 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-30 10:35:23.820  6441  6491 I jxcore-log: ,
,06-30 10:35:23.820  6441  6491 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
06-30 10:35:23.820  6441  6491 I jxcore-log: 
,06-30 10:35:24.150  6441  6491 I jxcore-log: Unit Test app is loaded
06-30 10:35:24.150  6441  6491 I jxcore-log: 
,06-30 10:35:24.160  6441  6491 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 10:35:24.160  6441  6491 I jxcore-log: 
,06-30 10:35:24.160  6441  6441 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,06-30 10:35:24.170  6441  6491 I WifiManager: packageName : com.test.thalitest
,06-30 10:35:24.170   752  1474 D SecContentProvider: uri = 18 selection = isWifiEnabled
06-30 10:35:24.170   752  1474 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
06-30 10:35:24.170   752  1474 D SecContentProvider2: mCursor = null
,06-30 10:35:24.170   752  1474 D WifiService: setWifiEnabled: true pid=6441, uid=10079
06-30 10:35:24.170   752   999 W ActivityManager: mDVFSHelper.release()
,06-30 10:35:24.170   752  1474 W ActivityManager: Permission Denial: getCurrentUser() from pid=6441, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
06-30 10:35:24.170   752  1474 W WifiService: Failed getting userId using ActivityManagerNative
06-30 10:35:24.170   752  1474 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6441, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
06-30 10:35:24.170   752  1474 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
06-30 10:35:24.170   752  1474 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
06-30 10:35:24.170   752  1474 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
06-30 10:35:24.170   752  1474 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
06-30 10:35:24.170   752  1474 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
06-30 10:35:24.170   752  1474 D SettingsProvider: name = wifi_on
,06-30 10:35:24.170   752  1441 I WifiService: disconnect: pid=6441, uid=10079
,06-30 10:35:24.170   752  1149 E WifiHW  : ##################### set firmware type 0 #####################
,06-30 10:35:24.170  6441  6491 D BluetoothAdapter: enable()
,06-30 10:35:24.170   293  1064 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
06-30 10:35:24.180   752  1590 W ActivityManager: Permission Denial: getCurrentUser() from pid=6441, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
06-30 10:35:24.180   752  1590 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
06-30 10:35:24.180   752  1590 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6441, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
06-30 10:35:24.180   752  1590 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
06-30 10:35:24.180   752  1590 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
06-30 10:35:24.180   752  1590 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
06-30 10:35:24.180   752  1590 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
06-30 10:35:24.180   752  1590 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
06-30 10:35:24.180   752  1590 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
06-30 10:35:24.180   752  1590 D SettingsProvider: name = bluetooth_on
06-30 10:35:24.180   752  1590 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,06-30 10:35:24.180   752  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
06-30 10:35:24.180   752  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,06-30 10:35:24.180  6441  6491 I jxcore-log: My device name is: samsung-SM-N9005
06-30 10:35:24.180  6441  6491 I jxcore-log: 
,06-30 10:35:24.180   752  1042 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,06-30 10:35:24.190   293  1064 I WifiHW  : module is semco
06-30 10:35:24.190   293  1064 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
06-30 10:35:24.190   293  1064 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
06-30 10:35:24.190   293  1064 E WifiHW  : TEMP_FAILURE_RETRY complete
06-30 10:35:24.190   293  1064 D SoftapController: Softap fwReload - Ok
,06-30 10:35:24.190  2940  2995 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,06-30 10:35:24.190  2940  2995 D BluetoothAdapterProperties: Setting state to 11
06-30 10:35:24.190  2940  2995 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
06-30 10:35:24.190  2940  2995 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,06-30 10:35:24.190  2940  2995 D BluetoothAdapterService: updateAdapterState state is 11
06-30 10:35:24.190  2940  2995 D BluetoothAdapterService: Autoconnection is available 
06-30 10:35:24.190  2940  2995 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
06-30 10:35:24.190   293  1064 D CommandListener: Setting iface cfg
06-30 10:35:24.190   293  1064 D CommandListener: Trying to bring down wlan0
,06-30 10:35:24.190  2940  2995 D BtConfig.SecureMode: isSecureModeOn:false
06-30 10:35:24.190  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
06-30 10:35:24.190   293  1064 D CommandListener: Clearing all IP addresses on wlan0
,06-30 10:35:24.190  2940  2995 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
06-30 10:35:24.190  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,06-30 10:35:24.190  2940  2995 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
06-30 10:35:24.190  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,06-30 10:35:24.190  2940  2995 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
06-30 10:35:24.190  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 10:35:24.190  2940  2995 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,06-30 10:35:24.190  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 10:35:24.190  2940  2995 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
06-30 10:35:24.190  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,06-30 10:35:24.190  2940  2995 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
06-30 10:35:24.190  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,06-30 10:35:24.190  2940  2995 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
06-30 10:35:24.190  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,06-30 10:35:24.190  2940  2995 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
06-30 10:35:24.190   752  1149 E WifiHW  : supplicant_name : p2p_supplicant
06-30 10:35:24.190  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,06-30 10:35:24.200   752   752 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:24.200  2940  2995 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
06-30 10:35:24.200  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
06-30 10:35:24.200   752   752 I InputMethodManagerService: [BT Setting State] State =11
,06-30 10:35:24.200  2940  2995 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
06-30 10:35:24.200  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
06-30 10:35:24.200  2940  2995 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
06-30 10:35:24.200  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
06-30 10:35:24.200  2940  2995 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
06-30 10:35:24.200  2940  2995 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
06-30 10:35:24.200  2940  2995 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
06-30 10:35:24.200  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-30 10:35:24.200  2940  2995 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,06-30 10:35:24.200  1719  1719 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,06-30 10:35:24.200   752  1742 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 10:35:24.200   752  1742 D ActivityManager: caller:android.app.ApplicationThreadProxy@35c91b74, r.packageName :com.android.bluetooth
,06-30 10:35:24.210  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
06-30 10:35:24.210  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,06-30 10:35:24.210   752  1149 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,06-30 10:35:24.210  2940  2995 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
06-30 10:35:24.210  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
06-30 10:35:24.210  2940  2995 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,06-30 10:35:24.210   752   752 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,06-30 10:35:24.210   752  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,06-30 10:35:24.210   752  1251 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 10:35:24.210   752  1251 D ActivityManager: caller:android.app.ApplicationThreadProxy@25442112, r.packageName :com.android.bluetooth
06-30 10:35:24.210   752  1377 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,06-30 10:35:24.210   752  1691 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,06-30 10:35:24.210  1197  1608 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,06-30 10:35:24.220  2940  2940 D HeadsetService: Received start request. Starting profile...
,06-30 10:35:24.220  2940  2940 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,06-30 10:35:24.220  2940  2940 D HeadsetStateMachine: make
,06-30 10:35:24.230  2940  2940 E HeadsetStateMachine: # of Max HF connection is 2
,06-30 10:35:24.230  4023  4023 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
06-30 10:35:24.230  2940  2995 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
06-30 10:35:24.230  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 10:35:24.230  2940  2995 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,06-30 10:35:24.230  6441  6441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 10:35:24.240   752  1643 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 10:35:24.240  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 10:35:24.240  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=3 combinedSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId=0x7f020134/com.android.systemui:drawable/ic_qs_signal_3 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 10:35:24.240  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
06-30 10:35:24.240   752  1643 D ActivityManager: caller:android.app.ApplicationThreadProxy@2a167ae0, r.packageName :com.android.bluetooth
06-30 10:35:24.240  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-30 10:35:24.240  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
06-30 10:35:24.240  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,06-30 10:35:24.240  1197  1608 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
06-30 10:35:24.240  1197  1197 D HotspotTile: onReceive : 2, 0
06-30 10:35:24.240  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
06-30 10:35:24.240  6580  6580 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
06-30 10:35:24.240  6580  6580 I wpa_supplicant: Successfully initialized wpa_supplicant
06-30 10:35:24.240   752  1377 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
06-30 10:35:24.240  2940  2995 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
06-30 10:35:24.240  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 10:35:24.240  2940  2995 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
06-30 10:35:24.240   752   777 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 10:35:24.240   752   777 D ActivityManager: caller:android.app.ApplicationThreadProxy@2a18650c, r.packageName :com.android.bluetooth
06-30 10:35:24.240  6580  6580 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
06-30 10:35:24.240  6580  6580 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,06-30 10:35:24.240   346   346 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6580
06-30 10:35:24.240   346   346 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
06-30 10:35:24.240  6580  6580 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
06-30 10:35:24.240  6580  6580 I wpa_supplicant: ssSupport state is = 1
06-30 10:35:24.240  2940  2995 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
06-30 10:35:24.240  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-30 10:35:24.240  2940  2995 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,06-30 10:35:24.240  6580  6580 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,06-30 10:35:24.240  6580  6580 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,06-30 10:35:24.240   346   346 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6580
06-30 10:35:24.240   346   346 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
06-30 10:35:24.240   752   776 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
06-30 10:35:24.240  1583  1583 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-30 10:35:24.250   752  1463 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 10:35:24.250   752  1463 D ActivityManager: caller:android.app.ApplicationThreadProxy@26cc5f8, r.packageName :com.android.bluetooth
06-30 10:35:24.250  2940  2940 I bluedroid: get_profile_interface handsfree
06-30 10:35:24.250  2940  2995 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
06-30 10:35:24.250  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 10:35:24.250  2940  2995 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,06-30 10:35:24.250   752  1590 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 10:35:24.250   752  1590 D ActivityManager: caller:android.app.ApplicationThreadProxy@38807936, r.packageName :com.android.bluetooth
06-30 10:35:24.250  2940  2995 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
06-30 10:35:24.250  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 10:35:24.250  2940  2995 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
06-30 10:35:24.260   752  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 10:35:24.260   752  1469 D ActivityManager: caller:android.app.ApplicationThreadProxy@29a449a4, r.packageName :com.android.bluetooth
06-30 10:35:24.260  2940  2995 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
06-30 10:35:24.260  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
06-30 10:35:24.260  2940  2995 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
06-30 10:35:24.260  2940  2995 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
06-30 10:35:24.260  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
06-30 10:35:24.260  4023  4023 D BluetoothNotiBroadcastReceiver: onReceive
06-30 10:35:24.260  2940  2995 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
06-30 10:35:24.260  2940  2995 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
06-30 10:35:24.260  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
06-30 10:35:24.260  2940  2995 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
06-30 10:35:24.260  2940  2995 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
06-30 10:35:24.260  2940  2995 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
06-30 10:35:24.260  2940  2995 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
06-30 10:35:24.260  2940  2995 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
06-30 10:35:24.270  2940  2940 I DualScoManager: Instantiating Dual Sco Manager
06-30 10:35:24.270  2940  2940 I DualScoManager: Set HeadsetServiceHelper
06-30 10:35:24.270  1197  1197 D QSpanel : label top:23
06-30 10:35:24.270  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 10:35:24.270  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 10:35:24.270  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 10:35:24.270  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 10:35:24.270  1197  1197 D QSpanel : label top:23
06-30 10:35:24.270  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 10:35:24.270  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 10:35:24.270  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 10:35:24.270  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 10:35:24.270  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 10:35:24.270  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
06-30 10:35:24.270  2940  2940 D BluetoothAtMessage: createCMTIContentObservers
06-30 10:35:24.270   752  1377 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
06-30 10:35:24.270   752  1377 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:24.270   752  1377 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:24.270   752  1377 D SettingsProvider: selectionArgs: false
06-30 10:35:24.270   752  1377 D SettingsProvider: selectionArgs: 1002
06-30 10:35:24.270   752  1377 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:24.270   752  1377 D SettingsProvider: ret = -1
06-30 10:35:24.270   752  1377 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
06-30 10:35:24.280  2940  6584 D HeadsetStateMachine: Enter Disconnected: -2
06-30 10:35:24.280  2940  2940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3797de34
06-30 10:35:24.280  2940  6584 E HeadsetStateMachine: set to mRemoteBrsf = 0
06-30 10:35:24.280  2940  6584 D HeadsetStateMachine: map size, before remove : 0
06-30 10:35:24.280  2940  6584 D HeadsetStateMachine: map size, after remove: 0
06-30 10:35:24.280  2940  6584 D HeadsetStateMachine: mNextConnectingDevice : null
06-30 10:35:24.280   752   752 D BluetoothA2dp: Proxy object connected
06-30 10:35:24.280  2940  2940 D A2dpService: Received start request. Starting profile...
06-30 10:35:24.280  3112  3112 D BluetoothA2dp: Proxy object connected
06-30 10:35:24.280  2940  2940 I BluetoothAvrcpServiceJni: classInitNative: succeeds
06-30 10:35:24.280  2940  2940 V Avrcp   : make
06-30 10:35:24.280  2940  2940 V Avrcp   : Avrcp
06-30 10:35:24.280  2940  2940 I bluedroid: get_profile_interface avrcp
06-30 10:35:24.280  2940  2940 V Avrcp   : start
,06-30 10:35:24.290  2940  2940 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,06-30 10:35:24.290  2940  2940 V Avrcp   : ++registerMediaPlayers++
,06-30 10:35:24.290  2940  2940 I Avrcp   : No of Audio players :: 2
06-30 10:35:24.290  2940  2940 I Avrcp   : App Package name is com.google.android.music
06-30 10:35:24.290  2940  2940 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
06-30 10:35:24.300  2940  2940 I Avrcp   : App pkg name is Google Play Music
,06-30 10:35:24.300  2940  2940 I Avrcp   : Name::Google Play Music
06-30 10:35:24.300  2940  2940 V Avrcp   : MediaPlayerInfo: mPlayerId=1
06-30 10:35:24.300  2940  2940 I Avrcp   : App Package name is com.sec.android.app.music
,06-30 10:35:24.300  2940  2940 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,06-30 10:35:24.300  2940  2940 I Avrcp   : App pkg name is Music
,06-30 10:35:24.300  2940  2940 I Avrcp   : Name::Music
06-30 10:35:24.300  2940  2940 V Avrcp   : MediaPlayerInfo: mPlayerId=2
06-30 10:35:24.300  2940  2940 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,06-30 10:35:24.300  2940  2940 I Avrcp   : No of Video players :: 1
,06-30 10:35:24.300  2940  2940 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,06-30 10:35:24.300  2940  2940 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,06-30 10:35:24.310  2940  2940 I Avrcp   : Video App pkg name is Video Player
,06-30 10:35:24.310  2940  2940 I Avrcp   : Name::Video Player
06-30 10:35:24.310  2940  2940 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,06-30 10:35:24.310  2940  2940 I Avrcp   : Add tempPlayer
06-30 10:35:24.310  2940  2940 V Avrcp   : MediaPlayerInfo: mPlayerId=4
06-30 10:35:24.310  2940  2940 I Avrcp   : Total no of players: 4
,06-30 10:35:24.310  2940  2940 V Avrcp   : swapping the samsung player with 1st player
06-30 10:35:24.310  2940  2940 I Avrcp   :  Updating now playing list upon AVRCP Start
,06-30 10:35:24.310  2940  6587 V Avrcp   : handleMessage, msg=207
,06-30 10:35:24.310  2940  6587 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,06-30 10:35:24.310   299   299 E SMD     : DCD ON
,06-30 10:35:24.310  2940  2940 I BluetoothA2dpServiceJni: classInitNative: succeeds
,06-30 10:35:24.310  2940  2940 D A2dpStateMachine: make
,06-30 10:35:24.330  2940  2940 I bluedroid: get_profile_interface a2dp
,06-30 10:35:24.330  2940  6589 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
06-30 10:35:24.330  2940  6587 D BluetoothMediaBrowser: no now playing list
06-30 10:35:24.330  2940  2940 E bt-btif : warning : media task started media_task_refcnt 1 
,06-30 10:35:24.330  2940  6587 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,06-30 10:35:24.330  2940  6587 D Avrcp   :  checkNowPlayingList start
,06-30 10:35:24.330  2940  2940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3797de34
06-30 10:35:24.330  2940  6588 D A2dpStateMachine: Enter Disconnected: -2
,06-30 10:35:24.330  2940  2940 I BluetoothHidServiceJni: classInitNative: succeeds
,06-30 10:35:24.330  2940  2940 D HidService: Received start request. Starting profile...
06-30 10:35:24.330  2940  2940 I bluedroid: get_profile_interface hidhost
,06-30 10:35:24.330  2940  2940 D HidService: setHidService(): set to: null
06-30 10:35:24.330  2940  2940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3797de34
,06-30 10:35:24.330  2940  2940 I BluetoothHealthServiceJni: classInitNative: succeeds
,06-30 10:35:24.330  2940  2940 D HealthService: Received start request. Starting profile...
,06-30 10:35:24.340  2940  2940 I bluedroid: get_profile_interface health
,06-30 10:35:24.340  2940  2940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3797de34
06-30 10:35:24.340  2940  2940 D HeadsetStateMachine: Try to query the phonestate on bind
,06-30 10:35:24.340  1405  1415 I Telecom : BluetoothPhoneService: queryPhoneState
,06-30 10:35:24.340  1405  1405 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,06-30 10:35:24.350  1405  1405 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,06-30 10:35:24.350  1405  1405 W BluetoothHeadset: Proxy not attached to service
,06-30 10:35:24.350  2940  2940 D HeadsetStateMachine: Proxy object connected
,06-30 10:35:24.350  2940  2940 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,06-30 10:35:24.350   752   752 D BluetoothPan: BluetoothPAN Proxy object connected
,06-30 10:35:24.350  2940  2940 D PanService: Received start request. Starting profile...
06-30 10:35:24.360  2940  2940 D BluetoothPanServiceJni: initializeNative(L110): pan
06-30 10:35:24.360  2940  2940 I bluedroid: get_profile_interface pan
,06-30 10:35:24.360  2940  2940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3797de34
,06-30 10:35:24.360  2940  2940 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,06-30 10:35:24.360  2940  6584 D HeadsetStateMachine: Disconnected process message: 11
,06-30 10:35:24.360  2940  2940 D BluetoothMapService: Received start request. Starting profile...
,06-30 10:35:24.360   752  1377 D ActivityManager: getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
,06-30 10:35:24.370   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:24.370   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:24.370   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:24.370   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:24.410  6593  6593 E Zygote  : MountEmulatedStorage()
06-30 10:35:24.410  6593  6593 E Zygote  : v2
06-30 10:35:24.410  6593  6593 I libpersona: KNOX_SDCARD checking this for 10186
06-30 10:35:24.410  6593  6593 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:24.410   752  1377 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6593 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,06-30 10:35:24.450   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:35:24.460  6593  6593 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,06-30 10:35:24.460  6593  6593 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:24.460  6593  6593 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:24.460   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:35:24.480  6593  6593 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:24.480  6593  6593 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:24.490  6593  6593 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,06-30 10:35:24.490  6593  6593 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,06-30 10:35:24.490  6593  6593 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:35:24.490  6593  6593 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
06-30 10:35:24.490  6593  6593 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 10:35:24.490  6593  6593 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-30 10:35:24.530   346   346 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,06-30 10:35:24.580   752  1590 D RCPManagerService: exchangeData() failure , invalid userId
,06-30 10:35:24.610  2940  2940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3797de34
,06-30 10:35:24.610  2940  2940 D HeadsetPhoneState: sendDeviceDataStateChanged
06-30 10:35:24.610  2940  6584 D HeadsetStateMachine: Disconnected process message: 18
06-30 10:35:24.610  2940  2940 D HeadsetPhoneState: Signal level : previous=0 curr=3
,06-30 10:35:24.620  2940  2940 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,06-30 10:35:24.620  2940  2940 D SapService: Received start request. Starting profile...
06-30 10:35:24.620  2940  2940 D BluetoothSAPServiceJni: initializeNative(L209): sap
06-30 10:35:24.620  2940  2940 I bluedroid: get_profile_interface sap
06-30 10:35:24.620  2940  2940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3797de34
,06-30 10:35:24.620   752  1377 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
06-30 10:35:24.620  2940  2940 E BluetoothAdapterService(932699700): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
06-30 10:35:24.620  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 10:35:24.620   752   777 D RCPManagerService: exchangeData() failure , invalid userId
06-30 10:35:24.620  2940  2940 D BluetoothA2dp: Proxy object connected
06-30 10:35:24.620  2940  2940 D BluetoothAdapterService: Bluetooth A2dp source service connected
06-30 10:35:24.620  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
06-30 10:35:24.620  2940  6584 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-30 10:35:24.620  2940  6584 D HeadsetStateMachine: Disconnected process message: 11
06-30 10:35:24.620   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:24.620   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:24.620   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:24.620   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:24.660  6614  6614 E Zygote  : MountEmulatedStorage()
06-30 10:35:24.660  6614  6614 E Zygote  : v2
06-30 10:35:24.660  6614  6614 I libpersona: KNOX_SDCARD checking this for 10092
06-30 10:35:24.660  6614  6614 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:24.670   752  1377 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6614 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,06-30 10:35:24.690  6614  6614 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:24.690  6614  6614 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:24.690  6614  6614 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,06-30 10:35:24.690  2940  2940 E BluetoothAdapterService(932699700): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
06-30 10:35:24.690  2940  2940 E BluetoothAdapterService(932699700): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,06-30 10:35:24.690  2940  2940 E BluetoothAdapterService(932699700): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
06-30 10:35:24.690  2940  2940 E BluetoothAdapterService(932699700): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,06-30 10:35:24.690   752  1691 I ActivityManager: Killing 5442:com.android.calendar/u0a172 (adj 15): emptyCount ##41
,06-30 10:35:24.690   752   777 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,06-30 10:35:24.690  2940  2940 E BluetoothAdapterService(932699700): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
06-30 10:35:24.690  2940  2940 E BluetoothAdapterService(932699700): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
06-30 10:35:24.690   752  1441 D RCPManagerService: exchangeData() failure , invalid userId
,06-30 10:35:24.690  2940  2995 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
06-30 10:35:24.690  2940  2995 I bluedroid: enable
06-30 10:35:24.690   752   777 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:24.690   752   777 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:24.690   752   777 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:24.690   752   777 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:24.720  6614  6614 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:24.720  6614  6614 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:24.730   752  1251 D RCPManagerService: exchangeData() failure , invalid userId
,06-30 10:35:24.740  6629  6629 E Zygote  : MountEmulatedStorage()
06-30 10:35:24.740  6629  6629 E Zygote  : v2
06-30 10:35:24.740  6629  6629 I libpersona: KNOX_SDCARD checking this for 10140
06-30 10:35:24.740  6629  6629 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:24.740   752   777 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6629 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,06-30 10:35:24.740  2940  2998 E bt-btif : Calling BTA_HhEnable
06-30 10:35:24.740  2940  2998 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
06-30 10:35:24.740  2940  2998 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
06-30 10:35:24.740  2940  2998 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
06-30 10:35:24.740  2940  2998 D BluetoothAdapterProperties: Address is:B0:C5:59:2A:28:2D
06-30 10:35:24.740  2940  2998 E BluetoothServiceJni: populateRssiValuesNative
06-30 10:35:24.740  2940  2998 I bluedroid: getModelRssiValues
06-30 10:35:24.740  2940  2998 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
06-30 10:35:24.740  2940  2998 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,06-30 10:35:24.790  6580  6580 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,06-30 10:35:24.810  6629  6629 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:24.810  6629  6629 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:24.810  6629  6629 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 10:35:24.810  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.810  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.810  6580  6580 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,06-30 10:35:24.810  6580  6580 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
06-30 10:35:24.810   346   346 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6580
06-30 10:35:24.810   346   346 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
06-30 10:35:24.810  6580  6580 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
06-30 10:35:24.810  6580  6580 I wpa_supplicant: ssSupport state is = 1
,06-30 10:35:24.810  6580  6580 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 10:35:24.810  6580  6580 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 10:35:24.810  6580  6580 E wpa_supplicant: SIM READ ERROR
06-30 10:35:24.810  2940  3001 D bt_upio : proc btwrite assertion
06-30 10:35:24.810  6580  6580 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 10:35:24.810  6580  6580 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 10:35:24.810  6580  6580 E wpa_supplicant: SIM READ ERROR
06-30 10:35:24.810  6580  6580 I wpa_supplicant: Blacklist: Clear (all) 
,06-30 10:35:24.810   752  1643 I ActivityManager: Killing 5369:com.sec.android.app.music:service/u0a49 (adj 15): emptyCount ##41
06-30 10:35:24.810  6580  6580 I wpa_supplicant: wpa_default_ap_write_once
06-30 10:35:24.810  6580  6580 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
06-30 10:35:24.810  6580  6580 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,06-30 10:35:24.810  6580  6580 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
06-30 10:35:24.810  6580  6580 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 10:35:24.810  6580  6580 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,06-30 10:35:24.820  6580  6580 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-30 10:35:24.820  2940  2998 D BluetoothAdapterProperties: Name is: Galaxy Note3
,06-30 10:35:24.820  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.820  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.820   752   752 D SettingsProvider: name = bluetooth_name
,06-30 10:35:24.820  2940  2998 D BluetoothAdapterProperties: Scan Mode:20
06-30 10:35:24.820  2940  2998 D BluetoothAdapterProperties: Discoverable Timeout:120
06-30 10:35:24.820  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.820  2940  3001 D bt_upio : BT_WAKE is asserted already
06-30 10:35:24.820  2940  2998 D BluetoothAdapterProperties: LE Address is:F0:8B:B2:54:50:5A
06-30 10:35:24.820  2940  2998 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
06-30 10:35:24.820  2940  2998 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
06-30 10:35:24.820  2940  2998 E bt-btif : btif_sock_init: !radio_req && !rfc_init
06-30 10:35:24.820  2940  2998 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,06-30 10:35:24.820  2940  2998 D IOP_DB_BT: db_open: db_open : handle 3026255888l, read 14063 bytes onto local cache
06-30 10:35:24.820  2940  2998 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,06-30 10:35:24.820  2940  2998 D IOP_DB_BT: db_query: result 1
06-30 10:35:24.820  2940  2998 I         : iop_db_open: iop_db_open status 0
06-30 10:35:24.820  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.820  2940  3001 D bt_upio : BT_WAKE is asserted already
06-30 10:35:24.820  2940  2998 D bte_conf: Device ID record 1 : primary
06-30 10:35:24.820  2940  2998 D bte_conf:   vendorId            = 0075
06-30 10:35:24.820  2940  2998 D bte_conf:   vendorIdSource      = 0001
06-30 10:35:24.820  2940  2998 D bte_conf:   product             = 0100
06-30 10:35:24.820  2940  2998 D bte_conf:   version             = 0200
06-30 10:35:24.820  2940  2998 D bte_conf:   clientExecutableURL = 
06-30 10:35:24.820  2940  2998 D bte_conf:   serviceDescription  = 
06-30 10:35:24.820  2940  2998 D bte_conf:   documentationURL    = 
06-30 10:35:24.820  2940  2998 D bte_conf: bte_load_did_conf no section named DID2.
06-30 10:35:24.820  2940  2998 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
06-30 10:35:24.820  2940  2998 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
06-30 10:35:24.820  2940  2995 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
06-30 10:35:24.820  2940  2995 D BluetoothAdapterProperties: ScanMode =  20
06-30 10:35:24.820  2940  2995 D BluetoothAdapterProperties: State =  11
,06-30 10:35:24.820   752  1590 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
06-30 10:35:24.820  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.820  6441  6441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 10:35:24.820  2940  3001 D bt_upio : BT_WAKE is asserted already
06-30 10:35:24.820  2940  2995 D BluetoothAdapterProperties: Setting state to 12
06-30 10:35:24.820  2940  2995 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,06-30 10:35:24.830  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.830  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.830  2940  2998 D BluetoothAdapterProperties: Scan Mode:21
06-30 10:35:24.830  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.830  2940  3001 D bt_upio : BT_WAKE is asserted already
06-30 10:35:24.830  2940  2998 D BluetoothAdapterProperties: Discoverable Timeout:120
,06-30 10:35:24.830   752  1742 D SettingsProvider: name = bluetooth_a2dp_sink_mode
06-30 10:35:24.830   752  1742 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:24.830   752  1742 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:24.830   752  1742 D SettingsProvider: selectionArgs: false
06-30 10:35:24.830   752  1742 D SettingsProvider: selectionArgs: 1002
06-30 10:35:24.830   752  1742 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:24.830   752  1742 D SettingsProvider: ret = -1
,06-30 10:35:24.830  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.830  2940  3001 D bt_upio : BT_WAKE is asserted already
06-30 10:35:24.830   752  1742 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,06-30 10:35:24.830  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.830  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.830  2940  2995 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-30 10:35:24.830  2940  2995 D BluetoothAdapterService: updateAdapterState state is 12
06-30 10:35:24.830  6441  6441 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,06-30 10:35:24.830   752  1550 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 10:35:24.830  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.830  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.830   752  1550 D ActivityManager: caller:android.app.ApplicationThreadProxy@1f7f63d4, r.packageName :com.android.bluetooth
,06-30 10:35:24.830  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.830  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.840  2940  2995 D BluetoothAdapterService: Autoconnection is available 
06-30 10:35:24.840  2940  2995 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
06-30 10:35:24.840  2940  2995 D BluetoothAdapterService: starting service from this receiver
,06-30 10:35:24.840   752  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 10:35:24.840   752  1469 D ActivityManager: caller:android.app.ApplicationThreadProxy@35519072, r.packageName :com.android.bluetooth
,06-30 10:35:24.840  6629  6629 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:35:24.840  6629  6629 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:24.840   752  1042 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-30 10:35:24.840  3112  3126 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-30 10:35:24.840  2940  2995 I BluetoothAdapterState: Entering On State from state = 11
06-30 10:35:24.840  2940  2949 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-30 10:35:24.840  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.840  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.840  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.840  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.850  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.850  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.850  6441  6441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 10:35:24.850  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:24.850  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 10:35:24.850  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:35:24.850  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 10:35:24.850  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:24.850  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:24.850  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 10:35:24.850  6441  6441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,06-30 10:35:24.850  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.850  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.850  2940  2940 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
06-30 10:35:24.850  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.850  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.850  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.850  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.850  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.850  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.850  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.850  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.850   752  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,06-30 10:35:24.860  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.860  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.860   752   752 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,06-30 10:35:24.860   752   752 I InputMethodManagerService: [BT Setting State] State =12
06-30 10:35:24.860   752   752 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,06-30 10:35:24.860  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.860  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.860  1405  1405 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@76f7800, true
,06-30 10:35:24.860  1719  1719 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
06-30 10:35:24.860  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.860  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.860  2940  2940 I BluetoothPbapService: Handler(): got msg=1
,06-30 10:35:24.860  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.860  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.860   752  1482 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,06-30 10:35:24.860  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.860  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.870  1405  1405 D BluetoothHeadset: registerMessageListener
,06-30 10:35:24.870  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.870  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.870  6614  6614 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,06-30 10:35:24.870  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.870  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.870  2940  6585 D HeadsetService: registerMessageListener
06-30 10:35:24.870  1197  1197 D BluetoothTile:  onBluetoothStateChange:
,06-30 10:35:24.870   752  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,06-30 10:35:24.870  2940  6585 D HeadsetService: registerMessageListener
06-30 10:35:24.870  2940  6584 D HeadsetStateMachine: Disconnected process message: 70
,06-30 10:35:24.870  2940  6646 V BluetoothPbapService: PBAP Service initSocket try: 0
06-30 10:35:24.870  2940  6584 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@292cb1a9
06-30 10:35:24.870  1405  1405 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,06-30 10:35:24.870  1405  1405 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,06-30 10:35:24.880  2940  6646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-30 10:35:24.880  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
06-30 10:35:24.880  2940  6584 D HeadsetStateMachine: Disconnected process message: 9
,06-30 10:35:24.880  2940  6646 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
06-30 10:35:24.880  2940  6646 D BluetoothSocket: bindListen(), new LocalSocket 
06-30 10:35:24.880  2940  6646 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
06-30 10:35:24.880  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.880  2940  3001 D bt_upio : BT_WAKE is asserted already
06-30 10:35:24.880  2940  6646 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37df532e
06-30 10:35:24.880  2940  6646 D BluetoothSocket: channel: 19
06-30 10:35:24.880  2940  6646 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,06-30 10:35:24.880  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:24.880  2940  6584 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
06-30 10:35:24.880  2940  6647 D BluetoothMapMasInstance: set MAP SDP message type : 1
,06-30 10:35:24.880   307   307 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
06-30 10:35:24.880   307   307 V voice   : voice_set_parameters: enter: A2dpSuspended=false
06-30 10:35:24.880   307   307 V voice   : voice_set_parameters: exit with code(-2)
06-30 10:35:24.880   307   307 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
06-30 10:35:24.880   307   307 V msm8974_platform: platform_set_parameters: exit with code(-2)
06-30 10:35:24.880   307   307 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
06-30 10:35:24.880   307   307 V audio_hw_primary: adev_set_parameters: exit
,06-30 10:35:24.880  2940  6584 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
06-30 10:35:24.880  2940  6647 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-30 10:35:24.880  2940  6647 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
06-30 10:35:24.880  2940  6647 D BluetoothSocket: bindListen(), new LocalSocket 
06-30 10:35:24.880  2940  6647 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
06-30 10:35:24.880  2940  6647 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19029ecf
06-30 10:35:24.880  2940  6647 D BluetoothSocket: channel: 5
06-30 10:35:24.880  2940  3001 D bt_vendor: op for 7
06-30 10:35:24.880  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:24.880   752  1144 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
06-30 10:35:24.890   752  1691 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,06-30 10:35:24.890  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,06-30 10:35:24.890  1197  1608 D BluetoothTile:  handleUpdatestate:false name:null
06-30 10:35:24.890  1197  1608 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,06-30 10:35:24.890  6629  6629 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
,06-30 10:35:24.890  6614  6614 D BadgeProvider: onCreate
,06-30 10:35:24.900  6614  6614 D BadgeProvider: DatabaseHelper
,06-30 10:35:24.910  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 10:35:24.910  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 10:35:24.910  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 10:35:24.910  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 10:35:24.910  1197  1197 D QSpanel : label top:23
06-30 10:35:24.910  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 10:35:24.910  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 10:35:24.910  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 10:35:24.910  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 10:35:24.910  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 10:35:24.910  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 10:35:24.920  6614  6624 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,06-30 10:35:24.930  1445  1445 D Launcher.Model: reloadBadges entered.
,06-30 10:35:24.930  6614  6624 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
06-30 10:35:24.930  6614  6624 D BadgeProvider: sendNotify, [notify] : null
06-30 10:35:24.930  6614  6624 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,06-30 10:35:24.930  6614  6624 D BadgeProvider: update, [BadgeCount] : badgecount=0
06-30 10:35:24.930  6614  6624 D BadgeProvider: update, [UpdateCount] : 1
,06-30 10:35:25.090   752   776 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,06-30 10:35:25.160  6629  6629 D StrictMode: StrictMode policy violation; ~duration=220 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 10:35:25.160  6629  6629 D StrictMode: StrictMode policy violation; ~duration=209 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 10:35:25.160  6629  6629 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.io.File.doAccess(File.java:283)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.io.File.exists(File.java:363)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 10:35:25.160  6629  6629 D StrictMode: StrictMode policy violation; ~duration=161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 10:35:25.160  6629  6629 D StrictMode: StrictMode policy violation; ~duration=159 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 10:35:25.160  6629  6629 D StrictMode: StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.r.k.c(PG:1187)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.r.k.a(PG:2107)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.r.v.a(PG:1206)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.r.y.a(PG:2233)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.r.e.b(PG:170)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.r.e.b(PG:13188)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 10:35:25.160  6629  6629 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.r.k.c(PG:1187)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.r.k.b(PG:14147)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.r.k.c(PG:583)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.r.v.a(PG:1206)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.r.y.a(PG:2233)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.r.e.b(PG:170)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.r.e.b(PG:13188)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 10:35:25.160  6629  6629 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.io.File.doAccess(File.java:283)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.io.File.exists(File.java:363)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 10:35:25.160  6629  6629 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 10:35:25.170   752   777 D ActivityManager: startProcessLocked calleePkgName: tv.peel.samsung.app, hostingType: broadcast
06-30 10:35:25.170   752   777 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:25.170   752   777 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:25.170   752   777 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:25.170   752   777 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:25.220  6629  6651 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
06-30 10:35:25.220  6659  6659 E Zygote  : MountEmulatedStorage()
06-30 10:35:25.220  6659  6659 E Zygote  : v2
06-30 10:35:25.220  6659  6659 I libpersona: KNOX_SDCARD checking this for 10152
06-30 10:35:25.220  6659  6659 I libpersona: KNOX_SDCARD not a persona
06-30 10:35:25.230   752   777 I ActivityManager: Start proc tv.peel.samsung.app for broadcast tv.peel.samsung.app/com.peel.receiver.ConnectivityActionReceiver: pid=6659 uid=10152 gids={50152, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
06-30 10:35:25.240   752   777 I ActivityManager: Killing 5406:com.sec.android.app.myfiles/u0a56 (adj 15): emptyCount ##41
,06-30 10:35:25.300  6659  6659 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:25.300  6659  6659 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:25.300  6659  6659 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 10:35:25.350  6659  6659 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:25.350  6659  6659 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:25.360  1493  3557 I art     : Explicit concurrent mark sweep GC freed 16345(974KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 19MB/31MB, paused 2.041ms total 33.683ms
,06-30 10:35:25.360  6659  6659 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,06-30 10:35:25.420  6659  6659 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,06-30 10:35:25.420  6659  6659 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,06-30 10:35:25.440  6659  6659 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6469-6471)
,06-30 10:35:25.440  6659  6659 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 10:35:25.450   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:35:25.460  6659  6659 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {195a45d}
,06-30 10:35:25.460  6659  6659 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 10:35:25.460  6659  6659 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 10:35:25.480   752  1152 E Tethering: No numeric data
,06-30 10:35:25.480   752  1152 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,06-30 10:35:25.480   752  1146 D NtpTrustedTime: forceRefresh() from cache miss
06-30 10:35:25.480  1197  1197 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,06-30 10:35:25.480  1197  1197 D HotspotTile: updateTetherState():false, false
,06-30 10:35:25.490   752  1146 D NtpTrustedTime: forceRefresh Fail.
,06-30 10:35:25.490   752  1146 V NetworkStats: performPollLocked(flags=0x1)
,06-30 10:35:25.490   752  1146 D NetworkStatsFactory: UpdateStatsForKnox
06-30 10:35:25.490   752  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:25.490   752  1146 V NetworkStats: performPollLocked() took 3ms
,06-30 10:35:25.490   752  1147 D NtpTrustedTime: forceRefresh() from cache miss
,06-30 10:35:25.490   752  1147 D NtpTrustedTime: forceRefresh Fail.
,06-30 10:35:25.490  6659  6659 I BrowserStartupController: Initializing chromium process, singleProcess=true
,06-30 10:35:25.490  6659  6659 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:35:25.490  6659  6659 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-30 10:35:25.510  6659  6677 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,06-30 10:35:25.510  6659  6659 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,06-30 10:35:25.510  6659  6659 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50556 len=3379
06-30 10:35:25.510  6659  6659 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:7638088 len:1165478
,06-30 10:35:25.520  6659  6659 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
06-30 10:35:25.520  6659  6659 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
06-30 10:35:25.520  6659  6659 I Adreno-EGL: Build Date: 11/19/14 Wed
06-30 10:35:25.520  6659  6659 I Adreno-EGL: Local Branch: mybranch5813579
06-30 10:35:25.520  6659  6659 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
06-30 10:35:25.520  6659  6659 I Adreno-EGL: Local Patches: NONE
06-30 10:35:25.520  6659  6659 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,06-30 10:35:25.570  6580  6580 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,06-30 10:35:25.610  6659  6686 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,06-30 10:35:25.630  6580  6580 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,06-30 10:35:25.630  6580  6580 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
06-30 10:35:25.630  6580  6580 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,06-30 10:35:25.630   346   346 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6580
06-30 10:35:25.630   346   346 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,06-30 10:35:25.630  6580  6580 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
06-30 10:35:25.630  6580  6580 I wpa_supplicant: ssSupport state is = 1
,06-30 10:35:25.630  6580  6580 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
06-30 10:35:25.630  6580  6580 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,06-30 10:35:25.630   346   346 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6580
06-30 10:35:25.630   346   346 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
06-30 10:35:25.630  6580  6580 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
06-30 10:35:25.630  6580  6580 I wpa_supplicant: ssSupport state is = 1
06-30 10:35:25.630  6580  6580 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 10:35:25.630  6580  6580 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 10:35:25.630  6580  6580 E wpa_supplicant: SIM READ ERROR
06-30 10:35:25.630  6580  6580 I wpa_supplicant: wpa_default_ap_write_once
06-30 10:35:25.640  6580  6580 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
06-30 10:35:25.640  6580  6580 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-30 10:35:25.650  6659  6659 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:35:25.660  6659  6659 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 10:35:25.690  6580  6580 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
06-30 10:35:25.690  6580  6580 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,06-30 10:35:25.730  6580  6580 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
06-30 10:35:25.730  6580  6580 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
06-30 10:35:25.730  6580  6580 I wpa_supplicant: Skip scan - bUseNetwork false
,06-30 10:35:25.730   752  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,06-30 10:35:25.730   752  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,06-30 10:35:25.730  6580  6580 I wpa_supplicant: HOTSPOT20_ENABLE called
06-30 10:35:25.730  6580  6580 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 10:35:25.730  6580  6580 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 10:35:25.730  6580  6580 E wpa_supplicant: SIM READ ERROR
06-30 10:35:25.730  6580  6580 I wpa_supplicant: Blacklist: Clear (all) 
,06-30 10:35:25.750  6580  6580 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,06-30 10:35:25.760  4934  4934 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,06-30 10:35:25.770   752  1691 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:25.770  6493  6493 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,06-30 10:35:25.770  6493  6493 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,06-30 10:35:25.780  6493  6493 D SecurityLogAgent: StateMachine : Current State = 1
,06-30 10:35:25.780  6493  6493 D SecurityLogAgent: StateMachine : Changed Current State = 1
,06-30 10:35:25.780  6580  6580 I wpa_supplicant: Skip scan - bUseNetwork false
06-30 10:35:25.780   752  1474 I ActivityManager: Killing 5293:com.google.android.music:main/u0a144 (adj 15): emptyCount ##41
,06-30 10:35:25.790   752  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,06-30 10:35:25.790  4023  4023 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,06-30 10:35:25.790   752  1149 D WifiConfigStore: Loading config and enabling all networks 
,06-30 10:35:25.790   752   752 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,06-30 10:35:25.800  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 10:35:25.800  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=3 combinedSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId=0x7f020134/com.android.systemui:drawable/ic_qs_signal_3 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 10:35:25.800  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
06-30 10:35:25.800  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 10:35:25.800  1197  1197 D StatusBar.NetworkController: applyOpen
,06-30 10:35:25.800  6441  6441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 10:35:25.800  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:25.800  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 10:35:25.800  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 10:35:25.800  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 10:35:25.800  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:25.800  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:25.800  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:35:25.800  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 10:35:25.800  1197  1197 D StatusBar.NetworkController: applyOpen
,06-30 10:35:25.800  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 10:35:25.800  1197  1197 D StatusBar.NetworkController: applyOpen
,06-30 10:35:25.800  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 10:35:25.800  1197  1197 D StatusBar.NetworkController: applyOpen
,06-30 10:35:25.800  6441  6441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-30 10:35:25.800  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-30 10:35:25.800  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
06-30 10:35:25.800   752  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
06-30 10:35:25.800  1197  1608 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
06-30 10:35:25.800  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-30 10:35:25.800  1197  1197 D HotspotTile: onReceive : 3, 0
,06-30 10:35:25.800   752  1149 E WifiConfigStore: Not a HS20
,06-30 10:35:25.810   752  1149 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,06-30 10:35:25.810   752  1149 D WifiNative-HAL: callSECApiInt - ID [65]
,06-30 10:35:25.820   752  1049 I PowerManagerService: [PWL] Off : 75s ago
06-30 10:35:25.820   752  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
06-30 10:35:25.820   752  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
06-30 10:35:25.820   752  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=935)
,06-30 10:35:25.820   752  1149 D WifiNative-HAL: callSECApiBoolean - ID [13]
,06-30 10:35:25.820  6580  6580 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
06-30 10:35:25.820  6580  6580 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,06-30 10:35:25.830  1197  1197 D QSpanel : label top:23
,06-30 10:35:25.830  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 10:35:25.830  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 10:35:25.830  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 10:35:25.830  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
,06-30 10:35:25.830  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 10:35:25.830  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 10:35:25.830  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 10:35:25.830  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
,06-30 10:35:25.830  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 10:35:25.830  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
06-30 10:35:25.830  6580  6580 I wpa_supplicant: reset timer : RESET_TIMER 0
06-30 10:35:25.830  6580  6580 I wpa_supplicant: P2P: Current p2p state = IDLE
06-30 10:35:25.830  6580  6580 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
06-30 10:35:25.830  6580  6580 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
06-30 10:35:25.830  6580  6580 I wpa_supplicant: First Scan Start
,06-30 10:35:25.830  4640  4640 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 10:35:25.830  6580  6580 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,06-30 10:35:25.830   752  1149 D WifiNative-HAL: Setting external_sim to 1
,06-30 10:35:25.830   752  1149 D WifiStateMachine: Setting OUI to DA-A1-19
06-30 10:35:25.830   752  1149 I WifiNative-HAL: startHal
06-30 10:35:25.830   752  1149 E wifi    : getStaticLongField sWifiHalHandle 0x939bd86c
06-30 10:35:25.830   752  1149 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x501aae
06-30 10:35:25.830   752  1149 I WifiNative-HAL: Could not start hal
,06-30 10:35:25.840   752  1149 E native  : do suspend true
,06-30 10:35:25.840   752  1148 D WifiP2pService: P2pDisabledState{ what=131203 }
,06-30 10:35:25.840   293  1064 D CommandListener: Setting iface cfg
06-30 10:35:25.840   293  1064 D CommandListener: Trying to bring up p2p0
,06-30 10:35:25.840   752  1148 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
06-30 10:35:25.840   752  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,06-30 10:35:25.850   752  1148 D WifiP2pService: P2pEnablingState
,06-30 10:35:25.850   752  1148 D WifiP2pService: P2pEnablingState{ what=147457 }
,06-30 10:35:25.850   752  1149 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,06-30 10:35:25.850   752  1149 D WifiNative-HAL: callSECStringApiVoid - ID [215]
06-30 10:35:25.850   752  1149 E WifiNative-HAL: invaild command id : 215
06-30 10:35:25.850   752  1148 D WifiP2pService: P2p socket connection successful
06-30 10:35:25.850   752  1148 D WifiP2pService: P2pEnabledState
,06-30 10:35:25.850   752  1148 D WifiP2pService: sending p2p connection changed broadcast: IDLE
,06-30 10:35:25.850   752  1148 D WifiP2pService: create mNetworkAgent
,06-30 10:35:25.870  4023  4023 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,06-30 10:35:25.870   752  1148 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,06-30 10:35:25.870   752  1151 D ConnectivityService: Got NetworkAgent Messenger
06-30 10:35:25.870   752  1151 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,06-30 10:35:25.870   752  1151 E ConnectivityService: updateNetworkInfo()
06-30 10:35:25.870   752  1151 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,06-30 10:35:25.870   752  1151 D ConnectivityService: NetworkAgent connected
,06-30 10:35:25.870   752  1151 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,06-30 10:35:25.870   752  1742 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,06-30 10:35:25.870   752  1742 D ActivityManager: caller:android.app.ApplicationThreadProxy@268450e7, r.packageName :com.android.settings
,06-30 10:35:25.870   752   752 D WifiScanningService: SCAN_AVAILABLE : 3
,06-30 10:35:25.870   752  1167 D WifiScanningService: DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:25.870   752  1167 I WifiNative-HAL: startHal
,06-30 10:35:25.880   752   752 D RttService: SCAN_AVAILABLE : 3
06-30 10:35:25.880   752  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
06-30 10:35:25.880   752  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
06-30 10:35:25.880   752   752 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,06-30 10:35:25.880   752  1044 D WifiDisplayController: disconnect
06-30 10:35:25.880   752  1044 D WifiDisplayController: updateConnection
06-30 10:35:25.880   752  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
06-30 10:35:25.880   752  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:25.880  1583  1583 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-30 10:35:25.880   752  1168 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,06-30 10:35:25.880   752  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-30 10:35:25.890  6580  6580 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
06-30 10:35:25.890  1197  1197 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,06-30 10:35:25.890   752  1469 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
06-30 10:35:25.890   752  1167 E wifi    : getStaticLongField sWifiHalHandle 0x9c2ff99c
06-30 10:35:25.890   752  1167 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x20223e
06-30 10:35:25.890   752  1167 I WifiNative-HAL: Could not start hal
06-30 10:35:25.890   752  1167 E WifiScanningService: could not start HAL
,06-30 10:35:25.890  1197  1197 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,06-30 10:35:25.910  4023  4023 D LocalBluetoothProfileManager: Adding local A2DP profile
,06-30 10:35:25.910  6580  6580 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,06-30 10:35:25.910   752  1144 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,06-30 10:35:25.920  4023  4023 D LocalBluetoothProfileManager: Adding local HEADSET profile
,06-30 10:35:25.920   752  1148 D WifiNative-HAL: p2pGetDeviceAddress
,06-30 10:35:25.920   752  1148 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:d7:fd:2b
,06-30 10:35:25.920  4023  4023 E BluetoothHeadset: BTStateChangeCB is registed
06-30 10:35:25.920   752  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy Note3
06-30 10:35:25.920   752  1044 D WifiDisplayController:  deviceAddress: ea:50:8b:d7:fd:2b
06-30 10:35:25.920   752  1044 D WifiDisplayController:  primary type: 10-0050F204-5
06-30 10:35:25.920   752  1044 D WifiDisplayController:  secondary type: null
06-30 10:35:25.920   752  1044 D WifiDisplayController:  wps: 0
06-30 10:35:25.920   752  1044 D WifiDisplayController:  grpcapab: 0
06-30 10:35:25.920   752  1044 D WifiDisplayController:  devcapab: 0
06-30 10:35:25.920   752  1044 D WifiDisplayController:  status: 3
06-30 10:35:25.920   752  1044 D WifiDisplayController:  wfdInfo: null
06-30 10:35:25.920   752  1044 D WifiDisplayController:  groupownerAddress: null
06-30 10:35:25.920   752  1044 D WifiDisplayController:  GOdeviceName: null
06-30 10:35:25.920   752  1044 D WifiDisplayController:  interfaceAddress: 
06-30 10:35:25.920   752  1044 D WifiDisplayController:  SConnectInfo : null
,06-30 10:35:25.920   752  1148 D WifiP2pService: DeviceAddress: ea:fd:2b
,06-30 10:35:25.920   752  1742 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,06-30 10:35:25.920  4023  4023 E BluetoothHeadset: BluetoothHeadset service is binded
,06-30 10:35:25.920   752  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 10:35:25.920   752  1149 D SecContentProvider2: mCursor = null
,06-30 10:35:25.930   752  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 10:35:25.930   752  1149 D SecContentProvider2: mCursor = null
,06-30 10:35:25.930  4023  4023 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,06-30 10:35:25.930   752   776 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,06-30 10:35:25.930  4023  4023 D Bluetoothsap: bindService called to Bluetooth SAP Service
,06-30 10:35:25.930   752  1148 D WifiP2pService: sending p2p persistent groups changed broadcast
,06-30 10:35:25.930   752  1482 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
06-30 10:35:25.930   752  1148 D WifiP2pService: InactiveState
,06-30 10:35:25.940   752  1148 D WifiP2pService: InactiveState{ what=143376 }
06-30 10:35:25.940   752  1151 E ConnectivityService: updateNetworkInfo()
06-30 10:35:25.940   752  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
06-30 10:35:25.940   752  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
,06-30 10:35:25.940  6580  6580 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,06-30 10:35:25.940   752  1148 D WifiP2pService: InactiveState{ what=143376 }
,06-30 10:35:25.940   752  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
,06-30 10:35:25.940   752  1144 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,06-30 10:35:25.940  4023  4023 D LocalBluetoothProfileManager: PANU : true
06-30 10:35:25.940  4023  4023 D LocalBluetoothProfileManager: Adding local MAP profile
,06-30 10:35:25.940  4023  4023 D BluetoothMap: Create BluetoothMap proxy object
,06-30 10:35:25.940   752   777 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,06-30 10:35:25.950   752  1469 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,06-30 10:35:25.950  4023  4023 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
06-30 10:35:25.950  4023  4023 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,06-30 10:35:25.950  4023  4023 D DockEventReceiver: finishStartingService: stopping service
,06-30 10:35:25.950  4023  4023 D BluetoothNotiBroadcastReceiver: onReceive
,06-30 10:35:25.960  4023  4023 D BluetoothA2dp: Proxy object connected
,06-30 10:35:25.960  4023  4023 D A2dpProfile: Bluetooth service connected
,06-30 10:35:25.960  2940  2940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3797de34
06-30 10:35:25.960  2940  2940 D BtConfig.SecureMode: isSecureModeOn:false
,06-30 10:35:25.960  4023  4023 D HeadsetProfile: Bluetooth service connected
,06-30 10:35:25.960   752  1742 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 10:35:25.960   752  1742 D ActivityManager: caller:android.app.ApplicationThreadProxy@19ac4ec7, r.packageName :com.android.bluetooth
,06-30 10:35:25.960  4023  4023 D Bluetoothsap: BluetoothSAP Proxy object connected
,06-30 10:35:25.960  4023  4023 D SapProfile: Bluetooth service connected
06-30 10:35:25.960  4023  4023 D Bluetoothsap: getConnectedDevices()
,06-30 10:35:25.970  4023  4023 D BluetoothInputDevice: Proxy object connected
,06-30 10:35:25.970  4023  4023 D HidProfile: Bluetooth service connected
,06-30 10:35:25.980  4934  4934 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,06-30 10:35:25.980  4023  4023 D BluetoothPan: BluetoothPAN Proxy object connected
06-30 10:35:25.980  4023  4023 D PanProfile: Bluetooth service connected
,06-30 10:35:25.980   752  1469 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:25.980  6493  6493 D SecurityLogAgent: KnoxConfiguration : Current State = 1
06-30 10:35:25.980  6493  6493 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-30 10:35:25.980  6493  6493 D SecurityLogAgent: StateMachine : Current State = 1
06-30 10:35:25.980  6493  6493 D SecurityLogAgent: StateMachine : Changed Current State = 1
,06-30 10:35:25.980  4023  4023 D BluetoothMap: Proxy object connected
,06-30 10:35:25.980  4023  4023 D MapProfile: Bluetooth service connected
06-30 10:35:25.980  4023  4023 D BluetoothPbap: Proxy object connected
,06-30 10:35:25.980  4023  4023 D PbapServerProfile: Bluetooth service connected
,06-30 10:35:25.990   752  1742 D ActivityManager: startProcessLocked calleePkgName: com.samsung.shareshot, hostingType: broadcast
,06-30 10:35:25.990   752  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:25.990   752  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:25.990   752  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:25.990   752  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:26.030  6713  6713 E Zygote  : MountEmulatedStorage()
06-30 10:35:26.030  6713  6713 E Zygote  : v2
06-30 10:35:26.030  6713  6713 I libpersona: KNOX_SDCARD checking this for 10192
06-30 10:35:26.030  6713  6713 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:26.040   752  1742 I ActivityManager: Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=6713 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:26.090  6713  6713 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,06-30 10:35:26.090  6713  6713 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:26.090  6713  6713 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:26.090   752  1441 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,06-30 10:35:26.100  2940  6723 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-30 10:35:26.100  2940  6723 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
06-30 10:35:26.100  2940  6723 D BluetoothSocket: bindListen(), new LocalSocket 
06-30 10:35:26.100  2940  6723 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
06-30 10:35:26.100  2940  6723 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1087ece1
,06-30 10:35:26.100  2940  3001 D bt_vendor: op for 7
06-30 10:35:26.100  2940  3001 D bt_upio : BT_WAKE is asserted already
,06-30 10:35:26.100  2940  6723 D BluetoothSocket: channel: 12
06-30 10:35:26.100  2940  6723 I BtOppRfcommListener: Accept thread started.
,06-30 10:35:26.120  6713  6713 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:26.120  6713  6713 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:26.130  6713  6713 D ResourcesManager: creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,06-30 10:35:26.150  6713  6713 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,06-30 10:35:26.160   752  1463 I ActivityManager: Killing 5856:flipboard.app/u0a125 (adj 15): emptyCount ##41
,06-30 10:35:26.160  4023  4023 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,06-30 10:35:26.160  4023  4023 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
06-30 10:35:26.160   752  1590 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:26.160  4023  4023 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
06-30 10:35:26.160   752  1975 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:26.160  4023  4023 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
06-30 10:35:26.160  4023  4023 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
06-30 10:35:26.160  4023  4023 I NearbySettings: MountReceiver.onReceive - Set preference state off
06-30 10:35:26.160  4023  4143 V NearbySettings: MountReceiver.mPrefHandler - 7002
,06-30 10:35:26.170  6543  6543 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,06-30 10:35:26.170  6713  6713 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,06-30 10:35:26.170  6713  6713 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
06-30 10:35:26.170  6713  6713 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,06-30 10:35:26.180  6713  6713 D WifiDirectBR: stopServiceTest : false
,06-30 10:35:26.450   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:35:26.580  6580  6580 I wpa_supplicant: nl80211: Received scan results (18 BSSes)
,06-30 10:35:26.580  6580  6580 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,06-30 10:35:26.590   752  1149 I WifiNative-HAL: startHal
06-30 10:35:26.590   752  1149 E wifi    : getStaticLongField sWifiHalHandle 0x939bd88c
06-30 10:35:26.590   752  1149 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x20228e
06-30 10:35:26.590   752  1149 I WifiNative-HAL: Could not start hal
06-30 10:35:26.590  6580  6580 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
06-30 10:35:26.590  6580  6580 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
06-30 10:35:26.590  6580  6580 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,06-30 10:35:26.610   752  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 10:35:26.610   752  1149 D SecContentProvider2: mCursor = null
,06-30 10:35:26.670  6580  6580 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,06-30 10:35:26.670  6580  6580 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,06-30 10:35:26.680  6580  6580 I wpa_supplicant: Associated with F4.99.3E
,06-30 10:35:26.680  6580  6580 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,06-30 10:35:26.680  6580  6580 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,06-30 10:35:26.690   752  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,06-30 10:35:26.690   752  1149 D SecContentProvider2: mCursor = null
,06-30 10:35:26.690   752  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,06-30 10:35:26.690   752  1149 D SecContentProvider2: mCursor = null
,06-30 10:35:26.690  6580  6580 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,06-30 10:35:26.700  6580  6580 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
06-30 10:35:26.700  6580  6580 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,06-30 10:35:26.700  6580  6580 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-30 10:35:26.700  6580  6580 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
06-30 10:35:26.700  6580  6580 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
06-30 10:35:26.700  6580  6580 I wpa_supplicant: Blacklist: Clear (temp) 
06-30 10:35:26.700  6580  6580 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,06-30 10:35:26.700   752  1149 D WifiNative-HAL: callSECApiVoid - ID [50]
,06-30 10:35:26.700   752   999 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
,06-30 10:35:26.700   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:26.700   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:26.700   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:26.700   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:26.710  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 10:35:26.710  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=3 combinedSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId=0x7f020134/com.android.systemui:drawable/ic_qs_signal_3 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 10:35:26.710  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,06-30 10:35:26.710   752  1149 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
06-30 10:35:26.710   752  1151 D ConnectivityService: Got NetworkAgent Messenger
06-30 10:35:26.710   752  1151 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
06-30 10:35:26.710   752  1151 E ConnectivityService: updateNetworkInfo()
06-30 10:35:26.710   752  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 10:35:26.710   752  1151 D ConnectivityService: NetworkAgent connected
,06-30 10:35:26.710   752  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,06-30 10:35:26.720   752  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,06-30 10:35:26.730   293  1064 D CommandListener: Setting iface cfg
,06-30 10:35:26.750  6734  6734 E Zygote  : MountEmulatedStorage()
06-30 10:35:26.750  6734  6734 E Zygote  : v2
06-30 10:35:26.750  6734  6734 I libpersona: KNOX_SDCARD checking this for 10038
06-30 10:35:26.750  6734  6734 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:26.760   752   999 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=6734 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,06-30 10:35:26.760   752  1149 E WifiStateMachine: Start Dhcp Watchdog 1
,06-30 10:35:26.770   752  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 10:35:26.770   752  1149 D SecContentProvider2: mCursor = null
,06-30 10:35:26.780   328   328 I art     : Explicit concurrent mark sweep GC freed 8741(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 301us total 16.018ms
,06-30 10:35:26.780   752  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,06-30 10:35:26.790   328   328 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 269us total 12.765ms
,06-30 10:35:26.800   328   328 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 269us total 10.608ms
,06-30 10:35:26.810  6734  6734 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:26.810  6734  6734 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:26.810  6734  6734 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 10:35:26.810  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 10:35:26.810  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=3 combinedSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId=0x7f020134/com.android.systemui:drawable/ic_qs_signal_3 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 10:35:26.810  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,06-30 10:35:26.810  2940  3120 D bt_upio : ..proc_btwrite_timeout..
,06-30 10:35:26.840  6734  6734 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:26.840  6734  6734 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:26.850  6734  6734 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,06-30 10:35:26.850  6734  6734 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,06-30 10:35:26.860   752  1149 E native  : do suspend false
,06-30 10:35:26.870   752  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 10:35:26.870   752  1149 D SecContentProvider2: mCursor = null
,06-30 10:35:26.870   752  1148 D WifiP2pService: InactiveState{ what=143375 }
,06-30 10:35:26.870   752  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-30 10:35:26.980  6734  6734 I VlingoApplication: VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,06-30 10:35:27.100  6751  6751 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,06-30 10:35:27.100  6751  6751 I dhcpcd  : version 5.5.6 starting
,06-30 10:35:27.100  6751  6751 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,06-30 10:35:27.120  6734  6734 E BluetoothHeadset: BTStateChangeCB is registed
,06-30 10:35:27.120   752  1377 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,06-30 10:35:27.120  6734  6734 E BluetoothHeadset: BluetoothHeadset service is binded
,06-30 10:35:27.130   752  1463 I ActivityManager: Killing 5962:com.android.defcontainer/u0a7 (adj 15): emptyCount ##41
,06-30 10:35:27.130  4023  4023 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,06-30 10:35:27.160  6734  6734 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
06-30 10:35:27.160  4023  4023 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,06-30 10:35:27.160  4023  4023 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
06-30 10:35:27.160   752  1742 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:27.160   752  1975 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:27.160  4023  4023 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
06-30 10:35:27.160  4023  4023 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
06-30 10:35:27.160  4023  4023 I NearbySettings: MountReceiver.onReceive - Set preference state off
,06-30 10:35:27.160  4023  4143 V NearbySettings: MountReceiver.mPrefHandler - 7002
,06-30 10:35:27.170   752   777 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:27.170  4934  4934 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,06-30 10:35:27.180  6751  6751 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
06-30 10:35:27.180  6751  6751 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
06-30 10:35:27.180  6751  6751 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,06-30 10:35:27.180  6751  6751 I dhcpcd  : bssid match
,06-30 10:35:27.180  6751  6751 I dhcpcd  : wlan0: rebinding lease of 192.168.1.119
,06-30 10:35:27.250  6751  6751 I dhcpcd  : wlan0: acknowledged 192.168.1.119 from 192.168.1.1
,06-30 10:35:27.290  6751  6751 I dhcpcd  : wlan0: leased 192.168.1.119 for 172800 seconds
,06-30 10:35:27.290   752  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,06-30 10:35:27.310   299   299 E SMD     : DCD ON
,06-30 10:35:27.460   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:35:27.610  2940  3001 D bt_vendor: op for 7
,06-30 10:35:27.680   752  1149 E native  : do suspend true
,06-30 10:35:27.700   752  1148 D WifiP2pService: InactiveState{ what=143375 }
,06-30 10:35:27.700   752  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-30 10:35:27.710   752  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,06-30 10:35:27.710   752  1149 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,06-30 10:35:27.710  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
06-30 10:35:27.710  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=3 combinedSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId=0x7f020134/com.android.systemui:drawable/ic_qs_signal_3 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 10:35:27.710  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
06-30 10:35:27.710   752  1149 E WifiStateMachine: VerifyingLinkState enter
,06-30 10:35:27.710   752  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,06-30 10:35:27.720   752  1151 E ConnectivityService: updateNetworkInfo()
,06-30 10:35:27.720   752  1151 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,06-30 10:35:27.720   752  1151 D ConnectivityService: Adding iface wlan0 to network 502
,06-30 10:35:27.720   752  1162 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
06-30 10:35:27.720   752  1162 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 10:35:27.720   752  1162 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,06-30 10:35:27.720   752  1162 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 10:35:27.720   752  1162 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,06-30 10:35:27.730   752  1149 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,06-30 10:35:27.740  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 10:35:27.740  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=3 combinedSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId=0x7f020134/com.android.systemui:drawable/ic_qs_signal_3 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 10:35:27.740  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,06-30 10:35:27.740  4023  4023 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,06-30 10:35:27.740  4023  4023 I NearbySettings: MountReceiver.onReceive - Keep current state
,06-30 10:35:27.750   752   752 I WifiTrafficPoller: evaluateTrafficStatsPolling
,06-30 10:35:27.750  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 10:35:27.750  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=3 combinedSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId=0x7f020134/com.android.systemui:drawable/ic_qs_signal_3 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 10:35:27.750  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,06-30 10:35:27.760   752  1149 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,06-30 10:35:27.760  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=3 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId=0x7f020134/com.android.systemui:drawable/ic_qs_signal_3 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 10:35:27.760  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,06-30 10:35:27.760   752   752 I WifiTrafficPoller: evaluateTrafficStatsPolling
06-30 10:35:27.760   752   752 I WifiTrafficPoller: mBoosterFLAG : 0
06-30 10:35:27.760  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 10:35:27.760   752   752 I WifiTrafficPoller: current booster mode : FullMode
06-30 10:35:27.760   752   752 D WifiNative-HAL: callSECApiVoid - ID [212]
,06-30 10:35:27.760  1197  1197 D StatusBar.NetworkController: applyOpen
,06-30 10:35:27.760  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,06-30 10:35:27.760  1197  1197 D StatusBar.NetworkController: applyOpen
,06-30 10:35:27.760  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 10:35:27.760  1197  1197 D StatusBar.NetworkController: applyOpen
,06-30 10:35:27.760  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 10:35:27.760  1197  1197 D StatusBar.NetworkController: applyOpen
,06-30 10:35:27.770   752  1975 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:27.770   752  1151 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 502
,06-30 10:35:27.770   752  1151 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,06-30 10:35:27.770   752  1151 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,06-30 10:35:27.770   752  1151 E ConnectivityService: Unexpected mtu value: 0, wlan0
,06-30 10:35:27.770   752  1151 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
06-30 10:35:27.770   752  1151 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.119
,06-30 10:35:27.770   293  1064 V         : QcRouteController
,06-30 10:35:27.770  4934  4934 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,06-30 10:35:27.790  4023  4023 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,06-30 10:35:27.790  4023  4023 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
06-30 10:35:27.790   752  1590 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:27.790  4023  4023 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
06-30 10:35:27.790   752  1691 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:27.790  4023  4023 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,06-30 10:35:27.790  4023  4023 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
06-30 10:35:27.790  4023  4023 I NearbySettings: MountReceiver.onReceive - Set preference state off
06-30 10:35:27.790  4023  4143 V NearbySettings: MountReceiver.mPrefHandler - 7002
,06-30 10:35:27.790   293  1064 V         : QcRouteController
,06-30 10:35:27.800   752  1643 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:27.800  4934  4934 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,06-30 10:35:27.810   293  1064 V         : QcRouteController
,06-30 10:35:27.810   293  1064 V         : QcRouteController
,06-30 10:35:27.810  4023  4023 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,06-30 10:35:27.810  4023  4023 I NearbySettings: MountReceiver.onReceive - Keep current state
,06-30 10:35:27.820   752   777 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,06-30 10:35:27.830   752  1441 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:27.830  4934  4934 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,06-30 10:35:27.830   293  1064 V         : QcRouteController
,06-30 10:35:27.840   266   266 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=4, Uoast
,06-30 10:35:27.850   293  1064 V         : QcRouteController
,06-30 10:35:27.850   752  1144 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=752
,06-30 10:35:27.870   293  1064 V         : QcRouteController
,06-30 10:35:27.870   293  1064 V         : QcRouteController
,06-30 10:35:27.890   293  1064 V         : QcRouteController
,06-30 10:35:27.910   752  1151 D ConnectivityService: Setting Dns servers for network 502 to [/192.168.1.1]
,06-30 10:35:27.910   752  1151 D ConnectivityService: LTETest block dns file not exists
,06-30 10:35:27.910   752  1151 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
06-30 10:35:27.910   752  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,06-30 10:35:27.920   752  1151 D ConnectivityService: calling update connectivity
,06-30 10:35:27.920   752  1042 D EntConnectivity: Not allowed due to - mEnabled false
06-30 10:35:27.920   752  1151 E ConnectivityService: updateNetworkInfo()
06-30 10:35:27.920   752  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
06-30 10:35:27.920   752  1151 E ConnectivityService: updateNetworkInfo()
06-30 10:35:27.920   752  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
06-30 10:35:27.920   752  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 10:35:27.920   752  1151 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
06-30 10:35:27.920   752  1151 D ConnectivityService: calling update connectivity
,06-30 10:35:27.920   752  1151 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
06-30 10:35:27.920   752  6732 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:27.920   752  6732 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
06-30 10:35:27.920   752  1151 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 10:35:27.920   752  6732 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,06-30 10:35:27.920   752  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:27.920   752  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:27.920   752  6732 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,06-30 10:35:27.920   752  1151 D ConnectivityService: currentScore = 0, newScore = 60
,06-30 10:35:27.920   752  1151 D ConnectivityService:    accepting network in place of null
06-30 10:35:27.920   752  1151 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 10:35:27.920   752  1151 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,06-30 10:35:27.920  1432  1432 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 10:35:27.930   752  6732 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:35:27.930   752  6732 I System.out: (HTTPLog)-Static: isShipBuild true
06-30 10:35:27.930   752  6732 I System.out: (HTTPLog)-Thread-178-44624344: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
06-30 10:35:27.930   752  6732 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:35:27.930   752  1151 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,06-30 10:35:27.930   752  1151 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
06-30 10:35:27.930   752  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,06-30 10:35:27.930   752  1146 V NetworkStats: updateIfacesLocked()
06-30 10:35:27.930   752  1146 V NetworkStats: performPollLocked(flags=0x1)
06-30 10:35:27.930   752  1146 D NetworkStatsFactory: UpdateStatsForKnox
06-30 10:35:27.930   752  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:27.930   752  1147 D NtpTrustedTime: forceRefresh() from cache miss
06-30 10:35:27.930   752  1151 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
06-30 10:35:27.930   752  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:27.930   752  1151 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,06-30 10:35:27.930   752   752 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
06-30 10:35:27.930   752  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
06-30 10:35:27.930   752  1153 D SmartBondingService: getSBEnabled() enabled =false
06-30 10:35:27.930   752  1153 D SmartBondingService: getSBEnabled() enabled =false
06-30 10:35:27.930   752  1153 D SmartBondingService: getSBEnabled() enabled =false
06-30 10:35:27.930  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,06-30 10:35:27.930  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
06-30 10:35:27.930   752  1146 V NetworkStats: performPollLocked() took 3ms
06-30 10:35:27.930  1197  1197 D StatusBar.NetworkController: updateDataNetType()
,06-30 10:35:27.930   752  1152 D Tethering: MasterInitialState.processMessage what=3
06-30 10:35:27.930   752  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,06-30 10:35:27.930   752  1147 D NtpTrustedTime: forceRefresh Fail.
06-30 10:35:27.930   752   776 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:27.940  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
06-30 10:35:27.940  1197  1197 E StatusBar.NetworkController: updateLTEICONDataNetType:0
06-30 10:35:27.940   752  1042 D EntConnectivity: Not allowed due to - mEnabled false
,06-30 10:35:27.940   752  1147 D NtpTrustedTime: forceRefresh() from cache miss
06-30 10:35:27.940   752  1147 D NtpTrustedTime: forceRefresh Fail.
,06-30 10:35:27.940   752  1147 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,06-30 10:35:27.940   752  1691 D SecContentProvider2: uri = 14 selection = getSealedState
06-30 10:35:27.940   752  1691 D SecContentProvider2: mCursor = null
,06-30 10:35:27.940   752  1441 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
06-30 10:35:27.940   752  1441 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
06-30 10:35:27.940   752  1151 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
06-30 10:35:27.940   752  1151 D ConnectivityService: calling update connectivity
06-30 10:35:27.940   752  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:27.940   752  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,06-30 10:35:27.940  1197  1197 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
06-30 10:35:27.940  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 8 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x3 gsm|lte
06-30 10:35:27.940   752  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:27.940  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=3
06-30 10:35:27.940  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_3 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_3 mContentDescriptionPhoneSignal = Three bars of phone signal
06-30 10:35:27.940  1197  1603 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-30 10:35:27.940  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=3 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId=0x7f020134/com.android.systemui:drawable/ic_qs_signal_3 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 10:35:27.940  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,06-30 10:35:27.940  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 10:35:27.940  1197  1197 D StatusBar.NetworkController: applyOpen
,06-30 10:35:27.940  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,06-30 10:35:27.940  1197  1197 D StatusBar.NetworkController: applyOpen
,06-30 10:35:27.940  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 10:35:27.940  1197  1197 D StatusBar.NetworkController: applyOpen
,06-30 10:35:27.940  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 10:35:27.940  1197  1197 D StatusBar.NetworkController: applyOpen
,06-30 10:35:27.940  1197  1197 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,06-30 10:35:27.950  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
06-30 10:35:27.950  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
06-30 10:35:27.950  1197  1197 I PhoneStatusBar: Icon Only
06-30 10:35:27.950  1197  1197 I StatusBar: Icon Only
,06-30 10:35:27.950  1197  1197 D PanelView: There is/are notification(s) 
,06-30 10:35:27.950  1197  1197 D PanelView: There is/are notification(s) 
,06-30 10:35:28.030   752  6732 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 10:35:28.090   752  6732 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 30 Jun 2016 08:35:28 GMT], X-Android-Received-Millis=[1467275728102], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467275728072]}
,06-30 10:35:28.090   752  6732 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
06-30 10:35:28.090   752  6732 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
06-30 10:35:28.090   752  1151 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 502]
06-30 10:35:28.090   752  1151 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
06-30 10:35:28.090   752  1151 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 10:35:28.090   752  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,06-30 10:35:28.090   752  1151 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
06-30 10:35:28.090   752  1151 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
06-30 10:35:28.090   752  1151 D ConnectivityService: calling update connectivity
06-30 10:35:28.090   752  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:28.090   752  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:28.090   752  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,06-30 10:35:28.090   752  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
06-30 10:35:28.090  1197  1603 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,06-30 10:35:28.090   752  1590 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:28.090  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): 0
06-30 10:35:28.090  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
06-30 10:35:28.090  1197  1197 D StatusBar.NetworkController: updateDataNetType()
,06-30 10:35:28.090  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
06-30 10:35:28.090  1197  1197 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,06-30 10:35:28.100   752  1463 D SecContentProvider2: uri = 14 selection = getSealedState
06-30 10:35:28.100   752  1463 D SecContentProvider2: mCursor = null
,06-30 10:35:28.100   752  1643 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
06-30 10:35:28.100   752  1643 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
,06-30 10:35:28.100  1197  1197 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
06-30 10:35:28.100  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 8 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x3 gsm|lte
06-30 10:35:28.100  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=3
,06-30 10:35:28.100  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_3 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_3 mContentDescriptionPhoneSignal = Three bars of phone signal
,06-30 10:35:28.100  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=3 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mQSPhoneSignalIconId=0x7f020134/com.android.systemui:drawable/ic_qs_signal_3 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02049e/com.android.systemui:drawable/stat_sys_signal_3 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 10:35:28.100  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,06-30 10:35:28.100  1197  1197 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,06-30 10:35:28.100  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
06-30 10:35:28.100  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
,06-30 10:35:28.100  1197  1197 I PhoneStatusBar: Icon Only
06-30 10:35:28.100  1197  1197 I StatusBar: Icon Only
,06-30 10:35:28.100  1197  1197 D PanelView: There is/are notification(s) 
,06-30 10:35:28.100  1197  1197 D PanelView: There is/are notification(s) 
,06-30 10:35:28.430   752  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,06-30 10:35:28.440   752   752 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:28.440   752   752 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:28.440   752   752 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
06-30 10:35:28.440   752   752 D SmartBondingService: SmartBondingReceiver: wifi is connected
06-30 10:35:28.440   752   777 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:28.440   752   752 D SmartBondingService: SmartBondingReceiver: wifi ap is changed, init speed ratio
,06-30 10:35:28.440   752   752 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:28.450   752   994 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
06-30 10:35:28.450   752   994 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:28.450   752   994 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:28.450   752  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
06-30 10:35:28.450   752  1153 D SmartBondingService: getSBEnabled() enabled =false
06-30 10:35:28.450   752  1153 D SmartBondingService: getSBEnabled() enabled =false
06-30 10:35:28.450   752  1153 D SmartBondingService: getSBEnabled() enabled =false
,06-30 10:35:28.450   752  1441 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:28.450   752  1643 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:28.450   752  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,06-30 10:35:28.450   752  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:28.450   752  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:28.450   752   752 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:28.450   752   752 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:28.450   752   752 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:28.450   752   752 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:28.450   752  1398 D NtpTrustedTime: forceRefresh() from cache miss
,06-30 10:35:28.450   752   776 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:28.450   752   776 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:28.450   752  1398 D NtpTrustedTime: forceRefresh Fail.
,06-30 10:35:28.460   752  1742 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:28.460   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:35:28.460  6067  6067 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
06-30 10:35:28.460   752  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:28.460  6067  6067 I PCWCLIENTTRACE_PushUtil: sales region : global
06-30 10:35:28.460  6067  6067 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,06-30 10:35:28.460   752  1975 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:28.460  6441  6441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 10:35:28.460  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:28.460  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 10:35:28.460  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 10:35:28.460  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 10:35:28.460  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 10:35:28.460  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 10:35:28.460  6441  6441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 10:35:28.460  6067  6067 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,06-30 10:35:28.460  6441  6441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,06-30 10:35:28.460   752  1469 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:28.470   752  1377 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,06-30 10:35:28.470   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:28.470   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:28.470   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:28.470   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:28.510  6816  6816 E Zygote  : MountEmulatedStorage()
,06-30 10:35:28.510  6816  6816 E Zygote  : v2
06-30 10:35:28.510  6816  6816 I libpersona: KNOX_SDCARD checking this for 10144
06-30 10:35:28.510  6816  6816 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:28.520   752  1377 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6816 uid=10144 gids={50144, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:28.520   752  1474 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 10:35:28.520   752  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@a870f6d, r.packageName :com.google.android.gms
,06-30 10:35:28.550  6816  6816 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:28.550  6816  6816 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 10:35:28.550  6816  6816 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 10:35:28.550   752   994 E GpsLocationProvider: No APN found to select.
,06-30 10:35:28.550  1583  1583 I ConfigService: onCreate
,06-30 10:35:28.550  1583  1583 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,06-30 10:35:28.560  1758  1758 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-30 10:35:28.560  1758  6826 I ConfigFetchService: running network task: configservice_periodic
,06-30 10:35:28.560  1583  1583 I ConfigService: onBind returning update interface
,06-30 10:35:28.560  1583  1583 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-30 10:35:28.560  1583  1583 I ConfigService: onBind returning service broker
,06-30 10:35:28.570  1758  1758 I ConfigFetchService: service connected
,06-30 10:35:28.570  1758  6826 E WakeLock: callingPackage is not supposed to be empty for wakelock Config Service fetch!
,06-30 10:35:28.570  1758  1758 D ConfigFetchService: ConfigApi connection successful.
,06-30 10:35:28.570  6816  6816 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:28.580  6816  6816 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:28.590  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
06-30 10:35:28.590  6441  6491 I jxcore-log: 
,06-30 10:35:28.670   752  1441 I art     : Explicit concurrent mark sweep GC freed 72421(4MB) AllocSpace objects, 8(128KB) LOS objects, 30% free, 35MB/51MB, paused 1.318ms total 87.435ms
,06-30 10:35:28.680  1758  6826 I ConfigFetchService: launchTask
,06-30 10:35:28.680  1758  6833 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,06-30 10:35:28.680  1758  6833 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1U9ukw1rP8jbEliL2LkiOtBFYu3wqMwEsDAFoWtzqu9yRk30iAo67TwJ-z6wluVVwOak1C9Cjn1hPKvgMmoz_5TkXMuhbGcTRnMWru7zCZ9g17e1daG2Z_UFdE_VrpItXo0JAAv0DJRRlRVENIBhmRtT2pxkdM8KOXsv-cP2p6vKAllaOlW6D-my99mrDpu3-oUH_XseutcyAEhHYaxw0ivjTY485hjOMMlU-5YU7tJ4JW3dqI
,06-30 10:35:28.690  6816  6816 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,06-30 10:35:28.730   752  1691 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,06-30 10:35:28.730  1758  6833 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-30 10:35:28.730  1758  6833 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:35:28.780  1758  6833 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 10:35:28.790  6816  6816 I MusicStore: Database version: 108
,06-30 10:35:28.800   752   776 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 10:35:28.860  6816  6816 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,06-30 10:35:28.860  6816  6816 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-30 10:35:28.860  6816  6816 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 10:35:28.880  6816  6816 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,06-30 10:35:28.940  6816  6816 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,06-30 10:35:28.940  6816  6816 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@28b6f660: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,06-30 10:35:28.940  6816  6816 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-30 10:35:28.940  6816  6816 D AndroidMusic: GMSCore installation verified
,06-30 10:35:28.950   752  1474 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 10:35:28.950  6816  6816 I ConfigStore: Config Database version: 1
,06-30 10:35:28.980   265   545 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
06-30 10:35:28.980   265   545 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:35:28.980  6816  6816 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,06-30 10:35:28.980   265   545 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
06-30 10:35:28.980   265   545 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:35:28.990  6816  6816 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,06-30 10:35:28.990   265   545 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
06-30 10:35:28.990   265   545 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:35:28.990  6816  6816 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,06-30 10:35:28.990   752  1691 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,06-30 10:35:28.990   752  1691 D ActivityManager: caller:android.app.ApplicationThreadProxy@11a9537f, r.packageName :com.google.android.music
,06-30 10:35:29.000   752  1482 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 10:35:29.010  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
06-30 10:35:29.010  6441  6491 I jxcore-log: 
,06-30 10:35:29.020   752  1742 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-30 10:35:29.020   752  1377 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-30 10:35:29.020   752  1550 I AudioService: getStreamVolume 3 index 70
,06-30 10:35:29.030  6816  6816 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,06-30 10:35:29.030  6816  6816 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,06-30 10:35:29.030  1758  6833 I ConfigFetchTask: updating config table for com.google.android.gms
,06-30 10:35:29.040  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
06-30 10:35:29.040  6441  6491 I jxcore-log: 
,06-30 10:35:29.040   752  1441 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:29.040  6816  6816 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-30 10:35:29.040  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
06-30 10:35:29.040  6441  6491 I jxcore-log: 
,06-30 10:35:29.060  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
06-30 10:35:29.060  6441  6491 I jxcore-log: 
,06-30 10:35:29.060   752  1590 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 10:35:29.060   752  1742 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 10:35:29.060  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-30 10:35:29.060  6441  6491 I jxcore-log: 
,06-30 10:35:29.070   752  1975 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 10:35:29.070  1758  1758 I ConfigFetchService: fetch service done; releasing wakelock
,06-30 10:35:29.070  1758  1758 I ConfigFetchService: stopping self
,06-30 10:35:29.070   752  1643 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-30 10:35:29.080   752  1590 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,06-30 10:35:29.080   752  1550 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:29.080   752  1590 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:29.080   752  1590 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:29.080   752  1590 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:29.080   752  1590 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:29.080  6816  6816 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-30 10:35:29.090   752  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:29.100   752  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
,06-30 10:35:29.100   752  1151 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,fe80::ea50:8bff:fed7:fd2b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 10:35:29.100   752  1151 D ConnectivityService: identical MTU - not setting
06-30 10:35:29.100   752  1151 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
,06-30 10:35:29.100   752  1151 D ConnectivityService: updateSourceRoutes : add src route for:fe80::ea50:8bff:fed7:fd2b
06-30 10:35:29.100   293  1064 V         : QcRouteController
,06-30 10:35:29.120   293  1064 V         : QcRouteController
06-30 10:35:29.120   752  1590 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6850 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:29.120   752  1151 W NetworkManagementService: route cmd failed: 
06-30 10:35:29.120   752  1151 W NetworkManagementService: com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '54 route replace src v6 wlan0 fe80::ea50:8bff:fed7:fd2b 2 ::' failed with '400 54 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
06-30 10:35:29.120   752  1151 W NetworkManagementService: '
06-30 10:35:29.120   752  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
06-30 10:35:29.120   752  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
06-30 10:35:29.120   752  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
06-30 10:35:29.120   752  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
06-30 10:35:29.120   752  1151 W NetworkManagementService: 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2844)
06-30 10:35:29.120   752  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5632)
06-30 10:35:29.120   752  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5444)
06-30 10:35:29.120   752  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.access$2400(ConnectivityService.java:230)
06-30 10:35:29.120   752  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2387)
06-30 10:35:29.120   752  1151 W NetworkManagementService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:29.120   752  1151 W NetworkManagementService: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:35:29.120   752  1151 W NetworkManagementService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:29.120   752  1151 V Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true
06-30 10:35:29.120   752  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
06-30 10:35:29.120   752  1151 D ConnectivityService: calling update connectivity
06-30 10:35:29.120   752   752 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
06-30 10:35:29.120   752   752 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:29.120   752  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
06-30 10:35:29.120   752  1153 D SmartBondingService: getSBEnabled() enabled =false
06-30 10:35:29.120   752  1153 D SmartBondingService: getSBEnabled() enabled =false
06-30 10:35:29.120   752  1153 D SmartBondingService: getSBEnabled() enabled =false
,06-30 10:35:29.120   752  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:29.120   752  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,06-30 10:35:29.120   752  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,06-30 10:35:29.120   752  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
06-30 10:35:29.130  1197  1603 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
06-30 10:35:29.120   752  1151 D ConnectivityService: calling update connectivity
06-30 10:35:29.130  6850  6850 E Zygote  : MountEmulatedStorage()
06-30 10:35:29.120   752  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:35:29.130  6850  6850 E Zygote  : v2
06-30 10:35:29.120   752  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:29.120   752  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:35:29.130  6850  6850 I libpersona: KNOX_SDCARD checking this for 10004
06-30 10:35:29.130  1197  1603 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
06-30 10:35:29.130  6850  6850 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:29.170  6850  6850 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:29.170  6850  6850 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:29.170  6850  6850 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:29.180   752  1251 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,06-30 10:35:29.180  6816  6816 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,06-30 10:35:29.190   752   776 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 10:35:29.190  6850  6850 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:29.190  6850  6850 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:29.200  6850  6850 D ResourcesManager: creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,06-30 10:35:29.220   752  1742 I ActivityManager: Killing 4838:com.google.android.gms.wearable/u0a15 (adj 15): emptyCount ##41
,06-30 10:35:29.250   752  1482 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:29.260   752  1474 I ActivityManager: Killing 6005:com.google.android.partnersetup/u0a19 (adj 15): emptyCount ##41
,06-30 10:35:29.260   752  1482 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,06-30 10:35:29.260   752  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:29.260   752  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:29.260   752  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:29.260   752  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:29.300  6869  6869 E Zygote  : MountEmulatedStorage()
06-30 10:35:29.300  6869  6869 E Zygote  : v2
06-30 10:35:29.300  6869  6869 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:35:29.300  6869  6869 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:29.310   752  1482 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6869 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 10:35:29.330  6869  6869 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:29.330  6869  6869 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:29.330  6869  6869 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:29.350  6869  6869 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:29.350  6869  6869 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:29.360  6869  6869 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,06-30 10:35:29.390  6869  6869 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,06-30 10:35:29.400  6869  6869 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,06-30 10:35:29.460   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-30 10:35:29.510  6869  6869 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,06-30 10:35:29.520  6869  6869 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,06-30 10:35:29.520  6869  6869 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,06-30 10:35:29.520  6869  6869 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,06-30 10:35:29.580   752  1441 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,06-30 10:35:29.580   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:29.580   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:29.580   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:29.580   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:29.620  6885  6885 E Zygote  : MountEmulatedStorage()
,06-30 10:35:29.620  6885  6885 E Zygote  : v2
06-30 10:35:29.620  6885  6885 I libpersona: KNOX_SDCARD checking this for 10014
06-30 10:35:29.620  6885  6885 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:29.630   752  1441 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=6885 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:29.660  6885  6885 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:29.660  6885  6885 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 10:35:29.660  6885  6885 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,06-30 10:35:29.680  6885  6885 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:29.680  6885  6885 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:29.690  6885  6885 D ResourcesManager: creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,06-30 10:35:29.740   752  1463 I ActivityManager: Killing 6030:com.samsung.groupcast/u0a20 (adj 15): emptyCount ##41
,06-30 10:35:29.740  6885  6885 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,06-30 10:35:29.750  6885  6885 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,06-30 10:35:29.770  6885  6885 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,06-30 10:35:29.780   752  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:29.780   752  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@3d451fe, r.packageName :com.google.android.gms
,06-30 10:35:29.790   752  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:29.790  1758  6900 I CheckinService: Checking schedule, now: 1467275729805 next: 1467039952342
,06-30 10:35:29.790  1758  6900 I CheckinService: active receiver: enabled
,06-30 10:35:29.800  1758  6900 I CheckinService: Preparing to send checkin request
06-30 10:35:29.800   752   776 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:29.800  1758  6900 I EventLogService: Accumulating logs since 1467274960867
,06-30 10:35:29.810   752  1377 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 10:35:29.810   752  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@290f907b, r.packageName :com.google.android.gms
,06-30 10:35:29.810   752  1590 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:29.810   752  1975 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:29.810   752   776 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:29.810   752  1251 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:29.820  1758  1758 I iu.Environment: update battery state; isPlugged? true*
,06-30 10:35:29.820  1758  1758 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,06-30 10:35:29.820   752  1482 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:29.820   752  1742 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:29.820  1758  1758 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
06-30 10:35:29.830   752  1590 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:29.830   752  1975 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:29.830  1758  1758 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,06-30 10:35:29.840   752  1463 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:29.840   752  1463 D ActivityManager: caller:android.app.ApplicationThreadProxy@33c82e98, r.packageName :com.google.android.gms
,06-30 10:35:29.840  1758  1758 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy}
,06-30 10:35:29.850  1758  1758 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy} to Chimera receiver impl com.google.android.gms.kids.account.SystemEventReceiver
06-30 10:35:29.850  1758  1758 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,06-30 10:35:29.850  1758  1758 I Kids    : [GCoreUtils] Current gmscore version, 7571438 is smaller than the required version 8400000
,06-30 10:35:29.850  3974  3974 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,06-30 10:35:29.850   752  1691 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:29.850  3974  3974 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1467275729864
,06-30 10:35:29.850  3974  3974 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,06-30 10:35:29.860   752  1441 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:29.860   752  1742 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:29.860  3974  3974 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,06-30 10:35:29.860  3974  3974 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().START
,06-30 10:35:29.860  3974  3974 I KLMS-2.4.511: : NetworkChangeOperations(): uploadRequestLog().START 
,06-30 10:35:29.870  3974  3974 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,06-30 10:35:29.870   752  1975 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.pinboard, hostingType: broadcast
,06-30 10:35:29.870   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:29.870   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:29.870   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:29.870   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:29.910  6907  6907 E Zygote  : MountEmulatedStorage()
06-30 10:35:29.910  6907  6907 I libpersona: KNOX_SDCARD checking this for 10036
06-30 10:35:29.910  6907  6907 E Zygote  : v2
06-30 10:35:29.910  6907  6907 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:29.910   752  1975 I ActivityManager: Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=6907 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,06-30 10:35:29.940  6907  6907 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:29.940  6907  6907 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:29.940  6907  6907 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:29.940   752  1643 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,06-30 10:35:29.940  1758  6900 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-30 10:35:29.950  1758  6900 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,06-30 10:35:29.960  6907  6907 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:29.960  6907  6907 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:29.970  6907  6907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,06-30 10:35:29.970  6907  6907 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 10:35:29.970  6907  6907 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-30 10:35:30.010  6907  6907 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
,06-30 10:35:30.010  1583  4036 I art     : Explicit concurrent mark sweep GC freed 11944(665KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 18MB/31MB, paused 625us total 23.787ms
,06-30 10:35:30.030   752  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:35:30.030   752  1643 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4301, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 10:35:30.030   752  1643 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:35:30.030   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:35:30.030   752  1643 D BatteryService: stay LED for fully charged
,06-30 10:35:30.030   752  1643 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:30.030   752   752 I MotionRecognitionService: Plugged
06-30 10:35:30.030  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:35:30.030   752   752 I MotionRecognitionService: setPowerConnected  = true
06-30 10:35:30.030  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:35:30.030  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:35:30.030  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:35:30.030  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 10:35:30.030  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:35:30.030   752  1463 I ActivityManager: Killing 6052:com.sec.android.service.health/u0a21 (adj 15): emptyCount ##41
,06-30 10:35:30.040   752  1643 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,06-30 10:35:30.040   752  1643 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:30.040   752  1643 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:30.040   752  1643 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:30.040   752  1643 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:30.060  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:35:30.060  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:35:30.080  6925  6925 E Zygote  : MountEmulatedStorage()
,06-30 10:35:30.080  6925  6925 E Zygote  : v2
06-30 10:35:30.080  6925  6925 I libpersona: KNOX_SDCARD checking this for 10042
06-30 10:35:30.080  6925  6925 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:30.090   752  1643 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6925 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,06-30 10:35:30.110  6925  6925 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:30.110  6925  6925 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:30.110  6925  6925 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:30.110   752  1377 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
06-30 10:35:30.110   752  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@3d5d9c44, r.packageName :com.samsung.android.app.galaxyfinder
,06-30 10:35:30.150  6925  6925 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:30.150  6925  6925 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:30.160  6925  6925 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,06-30 10:35:30.170   752  1742 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:30.190  6925  6925 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,06-30 10:35:30.210   752  1474 I ActivityManager: Killing 5240:com.sec.spp.push/u0a43 (adj 15): emptyCount ##41
,06-30 10:35:30.210   752   776 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:30.210   752   776 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:30.210   752   776 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:30.210   752   776 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:30.250  6945  6945 E Zygote  : MountEmulatedStorage()
06-30 10:35:30.250  6945  6945 E Zygote  : v2
06-30 10:35:30.250  6945  6945 I libpersona: KNOX_SDCARD checking this for 10015
06-30 10:35:30.250  6945  6945 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:30.260   752   776 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6945 uid=10015 gids={50015, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,06-30 10:35:30.310  6945  6945 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:30.310  6945  6945 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:30.310   752  1463 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:30.310   752  1469 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,06-30 10:35:30.310   752  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:30.310   752  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:30.310   752  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:30.310   752  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:30.310  6945  6945 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 10:35:30.310  3398  6951 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
06-30 10:35:30.310  3398  6951 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,06-30 10:35:30.310   299   299 E SMD     : DCD ON
,06-30 10:35:30.310  3398  6951 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,06-30 10:35:30.310  3398  6951 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(259/xdmNotInitSetResume)] DM Not Init
,06-30 10:35:30.320  3398  6951 I DBG_POLICYDM: [com.policydm.XDMService(300/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,06-30 10:35:30.320  3398  3522 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(33/xuiAdpGetUiMode)] nDmUiMode : 0
,06-30 10:35:30.320  3398  3522 I DBG_POLICYDM: [com.policydm.agent.XDMTask(200/xdmAgentTaskHandler)] XEVENT_DM_INIT
,06-30 10:35:30.320   752  1975 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:30.330  3398  3522 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,06-30 10:35:30.330  6945  6945 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:30.340  6945  6945 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:30.340  3398  3522 I DBG_POLICYDM: [com.policydm.XDMService(661/xdmGetNotibarState)] get NotibarState : 9
,06-30 10:35:30.340  3398  3522 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 9
,06-30 10:35:30.350  3398  3522 I DBG_POLICYDM: [com.policydm.XDMService(653/xdmSetNotibarState)] set NotibarState : 9
,06-30 10:35:30.350  6961  6961 E Zygote  : MountEmulatedStorage()
06-30 10:35:30.350  6961  6961 E Zygote  : v2
06-30 10:35:30.350  6961  6961 I libpersona: KNOX_SDCARD checking this for 10043
06-30 10:35:30.350  6961  6961 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:30.360   752  1469 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6961 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:30.410  6961  6961 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:30.410  6961  6961 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:30.410  6961  6961 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,06-30 10:35:30.420  6945  6945 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,06-30 10:35:30.420  6945  6945 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 10:35:30.420  6945  6945 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 10:35:30.430  3398  3522 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(234/xdbGetCryptionkey)] try read dbString
,06-30 10:35:30.430  6961  6961 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:30.430  6961  6961 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:30.440  3398  3522 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(442/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,06-30 10:35:30.450  6961  6961 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,06-30 10:35:30.450  3398  3522 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(574/xdbGetFUMOInitiatedType)] Initiated Type: 0
,06-30 10:35:30.460  3398  3524 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(216/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,06-30 10:35:30.460  3398  3522 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(78/xpollingCheckVersionInfo)] 
,06-30 10:35:30.460   752  1550 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:30.460  3398  3524 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,06-30 10:35:30.460  6945  6945 I MultiDex: VM with version 2.1.0 has multidex support
,06-30 10:35:30.460  3398  3522 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(277/xpollingCheckTimer)] 
06-30 10:35:30.460  6945  6945 I MultiDex: install
06-30 10:35:30.460  6945  6945 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 10:35:30.470  3398  3524 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,06-30 10:35:30.470  3398  3524 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(306/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,06-30 10:35:30.470  3398  3524 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(307/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,06-30 10:35:30.470  3398  3524 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(308/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,06-30 10:35:30.470  3398  3524 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(348/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,06-30 10:35:30.470  3398  3524 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(175/xnotiPushAdpClearSessionStatus)] 
,06-30 10:35:30.480  6945  6945 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,06-30 10:35:30.480  3398  3522 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(291/xpollingCheckTimer)] savedpollingtime : 2016/06/30/18:53:51
,06-30 10:35:30.480  3398  3524 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,06-30 10:35:30.480  3398  3524 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(453/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,06-30 10:35:30.490  3398  3522 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(292/xpollingCheckTimer)] currentTime : 2016/06/30/10:35:30
,06-30 10:35:30.490  3398  3522 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(296/xpollingCheckTimer)] Restart Timer..
,06-30 10:35:30.490  3398  3522 I DBG_POLICYDM: [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 0
,06-30 10:35:30.490  6961  6961 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,06-30 10:35:30.490  6961  6961 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,06-30 10:35:30.500  3398  3524 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(552/xdbSetFUMOInitiatedType)] Initiated Type: 0
,06-30 10:35:30.500  6961  6961 D SPPClientService: PushLog.txt file is not deleted.
06-30 10:35:30.500  6961  6961 D SPPClientService: PushLog.txt file is not deleted.
06-30 10:35:30.500  6961  6961 D SPPClientService: ============PushLog. stop!
,06-30 10:35:30.510  3398  3522 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(318/xPollingReportReStartAlarm)] 
,06-30 10:35:30.510  6961  6961 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,06-30 10:35:30.520  6138  6138 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,06-30 10:35:30.520  6138  6138 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,06-30 10:35:30.520  6138  6138 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,06-30 10:35:30.520  6138  6138 I SA      : [SLFUCHKMGR] constructor called
,06-30 10:35:30.530  6138  6138 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
06-30 10:35:30.530  6138  6138 I SA      : [OR] == isSIMCardReady false ==
,06-30 10:35:30.530   752  1482 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:30.530  6138  6138 I SA      : [SCU] == networkStateCheck == true
,06-30 10:35:30.530  6138  6138 I SA      : [DM] getCountryCodeFromCSC : PL
06-30 10:35:30.530  6138  6138 I SA      : isChinaCountryCode : false
06-30 10:35:30.530  6138  6138 I SA      : [SCU] is ChinestModel Data Restricted   : false
,06-30 10:35:30.530  6138  6138 I SA      : [OR] == networkStateCheck true ==
06-30 10:35:30.530  3398  3524 I DBG_POLICYDM: [com.policydm.db.XDB(1781/xdbSetBackUpServerUrl)] 
,06-30 10:35:30.540  6138  6138 I SA      : [OR] GetMyCountryZoneTask
,06-30 10:35:30.540  6138  6138 I SA      : [OR] onReceive END
,06-30 10:35:30.540   752  1251 I ActivityManager: Killing 6106:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
,06-30 10:35:30.540  6138  6981 I SA      : [SRS] prepareGetMyCountryZone
,06-30 10:35:30.550   752  1975 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:30.550   752  1742 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,06-30 10:35:30.550   752  1742 D ActivityManager: caller:android.app.ApplicationThreadProxy@33aff329, r.packageName :com.android.providers.downloads
,06-30 10:35:30.550   752  1441 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,06-30 10:35:30.550   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:30.550   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:30.550   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:30.550   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:30.570  1583  6904 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,06-30 10:35:30.590   752  1550 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:30.590   752  1441 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=6983 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,06-30 10:35:30.590  6983  6983 E Zygote  : MountEmulatedStorage()
06-30 10:35:30.590  6983  6983 E Zygote  : v2
06-30 10:35:30.590  6983  6983 I libpersona: KNOX_SDCARD checking this for 10074
06-30 10:35:30.590  6983  6983 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:30.590   752  1441 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:30.630  3398  3522 I DBG_POLICYDM: [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 1
,06-30 10:35:30.640  6983  6983 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:30.640  6983  6983 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:30.640  6983  6983 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:30.650  3398  3522 I DBG_POLICYDM: [com.policydm.agent.XDMTask(225/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,06-30 10:35:30.680  6983  6983 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:30.680  6983  6983 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:30.680  6138  6981 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,06-30 10:35:30.680  6138  6981 I SA      : [SSP] query invoked
,06-30 10:35:30.700  1583  6990 D GCM     : Connected
,06-30 10:35:30.700   307  1547 D WVCdm   : Instantiating CDM.
06-30 10:35:30.700  6983  6983 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
06-30 10:35:30.700   752  1441 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:30.700   307   678 I WVCdm   : CdmEngine::OpenSession
06-30 10:35:30.700   307   678 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,06-30 10:35:30.710   752  1691 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:30.710   752  1463 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,06-30 10:35:30.710  6945  6959 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-30 10:35:30.710   307   678 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,06-30 10:35:30.720   752  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:30.720   752  1474 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:30.730   307   678 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
06-30 10:35:30.730   307   678 D DrmWidevineDash: Service_Initialize: starts!
06-30 10:35:30.730   307   678 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,06-30 10:35:30.730   307   678 D QSEECOMAPI: : App is not loaded in QSEE
06-30 10:35:30.730  6138  6981 I SA      : [TPMU] GetMccFromDB : null
06-30 10:35:30.730  6138  6981 I SA      : [SCU] getMccFromPreferece mcc = 260
,06-30 10:35:30.730   307   678 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
06-30 10:35:30.730   307   678 E QSEECOMAPI: : Error::Loading image failed with ret = -1
06-30 10:35:30.730   307   678 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
06-30 10:35:30.730   307   678 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 10:35:30.730   752  1441 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:30.730   307   678 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
06-30 10:35:30.730   307   678 E QSEECOMAPI: : Error::Loading image failed with ret = -1
06-30 10:35:30.730   307   678 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
06-30 10:35:30.730   307   678 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 10:35:30.740  1583  6990 D GCM     : Message class com.google.f.a.a.p
,06-30 10:35:30.740   752  1377 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:30.740   752  1550 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:30.750  6138  6981 I SA      : [TPM] isNoProxy(default) : true
,06-30 10:35:30.750   307   678 D QSEECOMAPI: : Loaded image: APP id = 4
,06-30 10:35:30.750  6945  6959 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:35:30.750  6945  6959 I System.out: (HTTPLog)-Static: isShipBuild true
06-30 10:35:30.750  6945  6959 I System.out: (HTTPLog)-Thread-1140-242456063: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
06-30 10:35:30.750  6945  6959 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:35:30.750   307   678 D DrmWidevineDash: Service_Initialize: ends! returns 0
06-30 10:35:30.750   307   678 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1c93000
06-30 10:35:30.750   307   678 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1c93000
,06-30 10:35:30.760  6138  6981 E File    : fail readDirectory() errno=2
,06-30 10:35:30.770   307   678 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
06-30 10:35:30.770   307   678 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,06-30 10:35:30.770   307   678 D DrmWidevineDash: hlos api version =  9
06-30 10:35:30.770   307   678 D DrmWidevineDash: tz api version =  8
06-30 10:35:30.770   307   678 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-30 10:35:30.770   307   678 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,06-30 10:35:30.780   307   678 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
06-30 10:35:30.780   307   678 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
06-30 10:35:30.780   307   678 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb1df9940
,06-30 10:35:30.780   307   678 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
06-30 10:35:30.780   307   678 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
06-30 10:35:30.780   307   678 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb1832930, dataLength=8
,06-30 10:35:30.780   307   678 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,06-30 10:35:30.780   307   678 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb1bca000, wrapped_rsa_key_length=1280
,06-30 10:35:30.780   307   678 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
06-30 10:35:30.780   307   678 I WVCdm   : CdmEngine::QueryKeyControlInfo
,06-30 10:35:30.780   307   989 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-30 10:35:30.780   307   989 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-30 10:35:30.780   307   989 I WVCdm   : CdmEngine::GenerateKeyRequest
06-30 10:35:30.780   307   989 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb0b34740, idLength=0xadeff710
,06-30 10:35:30.790  3398  3524 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,06-30 10:35:30.790   307   989 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
06-30 10:35:30.790   307   989 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,06-30 10:35:30.790   307   989 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
06-30 10:35:30.790   307   989 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
06-30 10:35:30.790   307   989 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
06-30 10:35:30.790   307   989 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
06-30 10:35:30.790   307   989 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
06-30 10:35:30.790   307   989 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,06-30 10:35:30.790   307   989 D DrmWidevineDash: hlos api version =  9
06-30 10:35:30.790   307   989 D DrmWidevineDash: tz api version =  8
06-30 10:35:30.790   307   989 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-30 10:35:30.790   307   989 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,06-30 10:35:30.790   307   989 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
06-30 10:35:30.790   307   989 D WVCdm   : PrepareKeyRequest: nonce=228363317
06-30 10:35:30.790   307   989 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb19ed600
06-30 10:35:30.790   307   989 D DrmWidevineDash: message_length=1586, signature=0xb1960480, signature_length=2918184692
,06-30 10:35:30.800  6945  6959 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 10:35:30.810  3398  3524 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,06-30 10:35:30.820  6983  6983 I sCloudBackupApp: sCloudBackupApp Version Info : 3.13.7.KK_APP
,06-30 10:35:30.820  6983  6983 I SCloudBackupReceiver: Other Intent
,06-30 10:35:30.830  5720  5720 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,06-30 10:35:30.830  2940  2996 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,06-30 10:35:30.840  5720  5720 I KnoxUsageLogPro: premStatus:2
,06-30 10:35:30.840  5720  5720 I KnoxUsageLogPro: isEulaShown : false
06-30 10:35:30.840  5720  5720 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,06-30 10:35:30.850   752  1144 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,06-30 10:35:30.850   752  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:30.850   752  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:30.850   752  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:30.850   752  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:30.860   307   989 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,06-30 10:35:30.870   307  4988 I WVCdm   : CdmEngine::CloseSession
06-30 10:35:30.870   307  4988 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,06-30 10:35:30.870   307  4988 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
06-30 10:35:30.870   307  4988 I WVCdm   : L3 Terminate.
06-30 10:35:30.870   307  4988 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,06-30 10:35:30.870   307  4988 D DrmWidevineDash: Service_Uninitialize: starts!
06-30 10:35:30.870   307  4988 D QSEECOMAPI: : QSEECom_dealloc_memory 
06-30 10:35:30.870   307  4988 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 4
,06-30 10:35:30.870   307  4988 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,06-30 10:35:30.870   307  4988 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,06-30 10:35:30.890   752  1144 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7007 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:30.890  7007  7007 E Zygote  : MountEmulatedStorage()
,06-30 10:35:30.890  7007  7007 E Zygote  : v2
06-30 10:35:30.890   752  1144 I ActivityManager: Killing 5164:com.android.mms/u0a55 (adj 15): emptyCount ##41
06-30 10:35:30.890  7007  7007 I libpersona: KNOX_SDCARD checking this for 10104
06-30 10:35:30.890  7007  7007 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:30.950  7007  7007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:30.950  7007  7007 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:30.950   752  1482 D CountryDetector: No listener is left
06-30 10:35:30.950  7007  7007 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,06-30 10:35:30.970  7007  7007 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:30.970  7007  7007 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:30.990  7007  7007 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,06-30 10:35:31.120   752  1149 E WifiStateMachine: CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,06-30 10:35:31.180   752  1144 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,06-30 10:35:31.180   752  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:31.180   752  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:31.180   752  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:31.180   752  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:31.220  7024  7024 E Zygote  : MountEmulatedStorage()
06-30 10:35:31.220  7024  7024 E Zygote  : v2
06-30 10:35:31.220  7024  7024 I libpersona: KNOX_SDCARD checking this for 10146
06-30 10:35:31.220  7024  7024 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:31.240   752  1144 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7024 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:31.240   752  1144 I ActivityManager: Killing 6166:com.sec.android.app.soundalive/u0a64 (adj 15): emptyCount ##41
,06-30 10:35:31.240   328   328 I art     : Explicit concurrent mark sweep GC freed 8745(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 441us total 13.152ms
,06-30 10:35:31.250   328   328 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 263us total 9.582ms
,06-30 10:35:31.260  7024  7024 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:31.260  7024  7024 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:31.260  7024  7024 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 10:35:31.260   328   328 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 266us total 9.910ms
,06-30 10:35:31.290  7024  7024 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:31.290  7024  7024 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:31.310  7024  7024 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,06-30 10:35:31.330  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
06-30 10:35:31.330  6441  6491 I jxcore-log: 
,06-30 10:35:31.330   266   453 I SurfaceFlinger: id=12 Removed Uoast (8/9)
,06-30 10:35:31.330   266  1841 I SurfaceFlinger: id=12 Removed Uoast (-2/9)
,06-30 10:35:31.340   752  1441 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=752 (0x0)
,06-30 10:35:31.340   752  1441 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=752, ws=WorkSource{10067}) (elapsedTime=3484)
,06-30 10:35:31.340  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
06-30 10:35:31.340  6441  6491 I jxcore-log: 
,06-30 10:35:31.350  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
06-30 10:35:31.350  6441  6491 I jxcore-log: 
,06-30 10:35:31.430  6751  6751 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-30 10:35:31.480  7041  7041 I dex2oat : ----------------------------------------------------
,06-30 10:35:31.480  7041  7041 I dex2oat : <SS>: S T A R T I N G . . .
06-30 10:35:31.480  7041  7041 I dex2oat : <SS>: Zip is absent. Canceled.
06-30 10:35:31.480  7041  7041 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,06-30 10:35:31.480   752  3003 D SSRM:n  : SIOP:: AP = 410, PST = 384, CUR = 450
,06-30 10:35:31.520  7041  7041 I dex2oat : dex2oat took 43.691ms (threads: 4)
,06-30 10:35:31.540  6945  6959 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
06-30 10:35:31.540  6945  6959 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
06-30 10:35:31.540  6945  6959 I Adreno-EGL: Build Date: 11/19/14 Wed
06-30 10:35:31.540  6945  6959 I Adreno-EGL: Local Branch: mybranch5813579
06-30 10:35:31.540  6945  6959 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
06-30 10:35:31.540  6945  6959 I Adreno-EGL: Local Patches: NONE
06-30 10:35:31.540  6945  6959 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,06-30 10:35:31.540  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
06-30 10:35:31.540  6441  6491 I jxcore-log: 
,06-30 10:35:31.550   265   545 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
06-30 10:35:31.550   265   545 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:35:31.550  7024  7048 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,06-30 10:35:31.610   265   545 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
06-30 10:35:31.610   265   545 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:35:31.610  7024  7048 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,06-30 10:35:31.620  6945  6959 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
06-30 10:35:31.620  6945  6959 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
06-30 10:35:31.620  6945  6959 I Adreno-EGL: Build Date: 11/19/14 Wed
06-30 10:35:31.620  6945  6959 I Adreno-EGL: Local Branch: mybranch5813579
06-30 10:35:31.620  6945  6959 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
06-30 10:35:31.620  6945  6959 I Adreno-EGL: Local Patches: NONE
06-30 10:35:31.620  6945  6959 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,06-30 10:35:31.620  6138  6981 I SA      : [RC New] Execute method=[GET] start
,06-30 10:35:31.630   752  1377 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:31.640   265   545 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
06-30 10:35:31.640   265   545 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:35:31.640  7024  7053 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,06-30 10:35:31.640  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-30 10:35:31.640  6441  6491 I jxcore-log: 
,06-30 10:35:31.640   265   545 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
06-30 10:35:31.640   265   545 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:35:31.640  7024  7053 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,06-30 10:35:31.680  6138  6981 I SA      : [RC New] Security=[true]
,06-30 10:35:31.680  6138  6981 I System.out: Thread-1026(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,06-30 10:35:31.690  6138  6981 I System.out: Thread-1026(ApacheHTTPLog):isShipBuild true
,06-30 10:35:31.690  6138  6981 I System.out: Thread-1026(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,06-30 10:35:31.700  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-30 10:35:31.700  6441  6491 I jxcore-log: 
,06-30 10:35:31.710  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-30 10:35:31.710  6441  6491 I jxcore-log: 
,06-30 10:35:31.770  7024  7024 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,06-30 10:35:31.770  7024  7024 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,06-30 10:35:31.780  7024  7024 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2814-2816)
,06-30 10:35:31.780  7024  7024 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 10:35:31.790  7024  7024 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1a2ed9bf}
,06-30 10:35:31.790  7024  7024 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 10:35:31.790  7024  7024 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 10:35:31.810  7024  7024 I BrowserStartupController: Initializing chromium process, singleProcess=true
,06-30 10:35:31.810   752  1251 I art     : Explicit concurrent mark sweep GC freed 25079(1670KB) AllocSpace objects, 4(64KB) LOS objects, 30% free, 35MB/51MB, paused 1.376ms total 90.492ms
,06-30 10:35:31.820  7024  7024 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:35:31.820  7024  7024 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-30 10:35:31.840  7024  7024 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,06-30 10:35:31.840  7024  7024 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
06-30 10:35:31.840  7024  7024 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,06-30 10:35:31.850  7024  7024 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
06-30 10:35:31.850  7024  7024 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
06-30 10:35:31.850  7024  7024 I Adreno-EGL: Build Date: 11/19/14 Wed
06-30 10:35:31.850  7024  7024 I Adreno-EGL: Local Branch: mybranch5813579
06-30 10:35:31.850  7024  7024 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
06-30 10:35:31.850  7024  7024 I Adreno-EGL: Local Patches: NONE
06-30 10:35:31.850  7024  7024 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,06-30 10:35:31.930   752  1482 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:31.940  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
06-30 10:35:31.940  6441  6491 I jxcore-log: 
,06-30 10:35:31.940  6945  6959 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
06-30 10:35:31.940  6945  6959 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
06-30 10:35:31.940  6945  6959 I Adreno-EGL: Build Date: 11/19/14 Wed
06-30 10:35:31.940  6945  6959 I Adreno-EGL: Local Branch: mybranch5813579
06-30 10:35:31.940  6945  6959 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
06-30 10:35:31.940  6945  6959 I Adreno-EGL: Local Patches: NONE
06-30 10:35:31.940  6945  6959 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,06-30 10:35:31.960  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-30 10:35:31.960  6441  6491 I jxcore-log: 
,06-30 10:35:31.960  7024  7080 W AudioManagerAndroid: Requires BLUETOOTH permission
,06-30 10:35:31.960  7024  7024 I NSApplication: Starting up...
,06-30 10:35:31.960  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-30 10:35:31.960  6441  6491 I jxcore-log: 
,06-30 10:35:31.970  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-30 10:35:31.970  6441  6491 I jxcore-log: 
,06-30 10:35:31.970   752  1643 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:31.980   752  1482 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:31.980   752  1691 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:31.990   306   306 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 3377
06-30 10:35:31.990   306   306 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 3377
,06-30 10:35:31.990   306  3108 D WVMDrmPlugIn: WVMDrmPlugin::onGetSupportInfo : 0
,06-30 10:35:31.990  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-30 10:35:31.990  6441  6491 I jxcore-log: 
,06-30 10:35:32.010  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-30 10:35:32.010  6441  6491 I jxcore-log: 
,06-30 10:35:32.010   307  4988 D WVCdm   : Instantiating CDM.
,06-30 10:35:32.010   307  1547 I WVCdm   : CdmEngine::OpenSession
,06-30 10:35:32.010   307  1547 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,06-30 10:35:32.020   307  1547 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,06-30 10:35:32.030   307  1547 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
06-30 10:35:32.030   307  1547 D DrmWidevineDash: Service_Initialize: starts!
06-30 10:35:32.030   307  1547 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,06-30 10:35:32.030   307  1547 D QSEECOMAPI: : App is not loaded in QSEE
06-30 10:35:32.030   307  1547 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
06-30 10:35:32.030   307  1547 E QSEECOMAPI: : Error::Loading image failed with ret = -1
06-30 10:35:32.030   307  1547 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
06-30 10:35:32.030   307  1547 D QSEECOMAPI: : App is not loaded in QSEE
06-30 10:35:32.030   307  1547 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
06-30 10:35:32.030   307  1547 E QSEECOMAPI: : Error::Loading image failed with ret = -1
06-30 10:35:32.030   307  1547 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
06-30 10:35:32.030   307  1547 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 10:35:32.040   307  1547 D QSEECOMAPI: : Loaded image: APP id = 4
,06-30 10:35:32.040   307  1547 D DrmWidevineDash: Service_Initialize: ends! returns 0
06-30 10:35:32.040   307  1547 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1c93000
06-30 10:35:32.040   307  1547 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1c93000
,06-30 10:35:32.040   307  1547 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
06-30 10:35:32.040   307  1547 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,06-30 10:35:32.040   307  1547 D DrmWidevineDash: hlos api version =  9
06-30 10:35:32.040   307  1547 D DrmWidevineDash: tz api version =  8
06-30 10:35:32.040   307  1547 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-30 10:35:32.040   307  1547 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,06-30 10:35:32.050   307  1547 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
06-30 10:35:32.050   307  1547 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
06-30 10:35:32.050   307  1547 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xade01940
,06-30 10:35:32.050   307  1547 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
06-30 10:35:32.050   307  1547 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
06-30 10:35:32.050   307  1547 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb1902fc0, dataLength=8
,06-30 10:35:32.050   307  1547 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
06-30 10:35:32.050   307  1547 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb05cc000, wrapped_rsa_key_length=1280
,06-30 10:35:32.050   307  1547 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
06-30 10:35:32.050   307  1547 I WVCdm   : CdmEngine::QueryKeyControlInfo
,06-30 10:35:32.060   752   776 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:32.060   307  4988 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-30 10:35:32.060   307  4988 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-30 10:35:32.060   307  4988 I WVCdm   : CdmEngine::GenerateKeyRequest
06-30 10:35:32.060   307  4988 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb0b34780, idLength=0xadc01710
,06-30 10:35:32.060   752  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:32.060   752  1550 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:32.060   752  1474 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:32.060   752  1975 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,06-30 10:35:32.060   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:32.060   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:32.060   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:32.060   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:32.060   307  4988 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
06-30 10:35:32.060   307  4988 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,06-30 10:35:32.060   307  4988 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
06-30 10:35:32.060   307  4988 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
06-30 10:35:32.060   307  4988 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
06-30 10:35:32.060   307  4988 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
,06-30 10:35:32.060   307  4988 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
06-30 10:35:32.060   307  4988 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,06-30 10:35:32.070   307  4988 D DrmWidevineDash: hlos api version =  9
06-30 10:35:32.070   307  4988 D DrmWidevineDash: tz api version =  8
06-30 10:35:32.070   307  4988 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-30 10:35:32.070   307  4988 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,06-30 10:35:32.070   307  4988 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
06-30 10:35:32.070   307  4988 D WVCdm   : PrepareKeyRequest: nonce=2412219838
06-30 10:35:32.070   307  4988 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb0d22600
06-30 10:35:32.070   307  4988 D DrmWidevineDash: message_length=1618, signature=0xb0241a00, signature_length=2915047156
,06-30 10:35:32.100  7089  7089 E Zygote  : MountEmulatedStorage()
,06-30 10:35:32.100  7089  7089 E Zygote  : v2
06-30 10:35:32.100  7089  7089 I libpersona: KNOX_SDCARD checking this for 10158
06-30 10:35:32.100  7089  7089 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:32.110  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
06-30 10:35:32.110  6441  6491 I jxcore-log: 
,06-30 10:35:32.110   752  1975 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7089 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,06-30 10:35:32.110   752  1975 I ActivityManager: Killing 4712:com.samsung.android.sm/1000 (adj 15): emptyCount ##41
,06-30 10:35:32.110  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
06-30 10:35:32.110  6441  6491 I jxcore-log: 
,06-30 10:35:32.140   307  4988 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,06-30 10:35:32.140  6441  6491 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
06-30 10:35:32.140  6441  6491 I jxcore-log: 
,06-30 10:35:32.140   307   989 I WVCdm   : CdmEngine::CloseSession
06-30 10:35:32.140   307   989 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
06-30 10:35:32.140  7089  7089 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:32.140  7089  7089 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:32.140   307   989 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
06-30 10:35:32.140   307   989 I WVCdm   : L3 Terminate.
06-30 10:35:32.140   307   989 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,06-30 10:35:32.140   307   989 D DrmWidevineDash: Service_Uninitialize: starts!
06-30 10:35:32.140   307   989 D QSEECOMAPI: : QSEECom_dealloc_memory 
06-30 10:35:32.140   307   989 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 4
06-30 10:35:32.140  7089  7089 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:32.140   307   989 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,06-30 10:35:32.140   307   989 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,06-30 10:35:32.150  6441  6491 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,06-30 10:35:32.150  6441  6491 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
06-30 10:35:32.150  6441  6491 I jxcore-log: 
,06-30 10:35:32.170  7089  7089 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:32.170  7089  7089 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:32.190  1758  6900 I CheckinRequestBuilder: Classify the device as Phone.
,06-30 10:35:32.200  1758  6900 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,06-30 10:35:32.200  7089  7089 D ResourcesManager: creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,06-30 10:35:32.200  7089  7089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 10:35:32.200  7089  7089 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
06-30 10:35:32.200  7089  7089 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,06-30 10:35:32.210  6441  6491 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
06-30 10:35:32.210  6441  6491 I jxcore-log: 
,06-30 10:35:32.210  6441  6491 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
06-30 10:35:32.210  6441  6491 I jxcore-log: 
,06-30 10:35:32.210  6441  6491 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-30 10:35:32.210  6441  6491 I jxcore-log: 
,06-30 10:35:32.210  7089  7089 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,06-30 10:35:32.220  7089  7089 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,06-30 10:35:32.220  7089  7089 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,06-30 10:35:32.230   752  1463 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:32.230   752  1469 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:32.230   752  1482 D RCPManagerService: exchangeData() failure , invalid userId
,06-30 10:35:32.240   752  1590 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:32.240  6493  6493 D SecurityLogAgent: KnoxConfiguration : Current State = 1
06-30 10:35:32.240  6493  6493 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-30 10:35:32.240  6493  6493 D SecurityLogAgent: StateMachine : Current State = 1
06-30 10:35:32.240   752   777 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:32.240  6493  6493 D SecurityLogAgent: StateMachine : Changed Current State = 1
,06-30 10:35:32.240   752  1691 I ActivityManager: Killing 5225:com.samsung.android.app.assistantmenu/1000 (adj 15): emptyCount ##41
,06-30 10:35:32.250   752  1691 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,06-30 10:35:32.250   752  1482 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:32.250   752   777 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:35:32.250   752  1691 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:32.250   752  1691 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:32.250   752  1691 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:32.250   752  1691 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:32.290  7108  7108 E Zygote  : MountEmulatedStorage()
06-30 10:35:32.290  7108  7108 E Zygote  : v2
06-30 10:35:32.290  7108  7108 I libpersona: KNOX_SDCARD checking this for 10200
06-30 10:35:32.290  7108  7108 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:32.300  7108  7108 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:32.300  7108  7108 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:32.300  7108  7108 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,06-30 10:35:32.300   752  1691 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7108 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:32.310   752  1742 D ActivityManager: startService callerProcessName:com.sec.android.app.SmartClipService, calleePkgName: com.sec.android.app.SmartClipService
06-30 10:35:32.310   752  1742 D ActivityManager: caller:android.app.ApplicationThreadProxy@28acc3c, r.packageName :com.sec.android.app.SmartClipService
,06-30 10:35:32.320  7108  7108 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:32.320  7108  7108 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:32.340  7108  7108 D ResourcesManager: creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,06-30 10:35:32.340  1758  6900 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:35:32.340  1758  6900 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 10:35:32.360   752  1482 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:32.360  6304  6304 D WaitQueueForNetworkActivate: notifyNetworkActivated
,06-30 10:35:32.390  6138  6981 I SA      : [RC New] [v2liruge] api execute + 708
06-30 10:35:32.390  6138  6981 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,06-30 10:35:32.390  6138  6981 I System.out: AsyncTask #1 calls detatch()
,06-30 10:35:32.390  6138  6981 I SA      : [TPMU] getNetworkMcc : 260
,06-30 10:35:32.410  6138  6981 I SA      : [SCU] saveMccToPreferece Start
06-30 10:35:32.410  6138  6981 I SA      : [SCU] RegionMCC : 260
06-30 10:35:32.410  6138  6981 I SA      : [SSP] query invoked
,06-30 10:35:32.410  6138  6981 I SA      : [TPMU] GetMccFromDB : null
06-30 10:35:32.410  6138  6981 I SA      : [SCU] getMccFromPreferece mcc = 260
,06-30 10:35:32.410  6138  6981 I SA      : [SCU] saveMccToPreferece End
06-30 10:35:32.410  6138  6981 I SA      : [RC New] executeRequest [v2liruge] end. 780
,06-30 10:35:32.410  6138  6981 I SA      : [RC New] Execute end
06-30 10:35:32.410  6138  6138 I SA      : [OR] GetMyCountryZoneTask mcc = 260
,06-30 10:35:32.410  6138  6138 I SA      : [OR] GetMyCountryZoneTask Success
,06-30 10:35:32.420  1758  6900 I CheckinTask: Sending checkin request (10377 bytes)
,06-30 10:35:32.500   752   776 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,06-30 10:35:32.500   752   776 D ActivityManager: caller:android.app.ApplicationThreadProxy@11bb6dc5, r.packageName :com.sec.android.app.samsungapps
,06-30 10:35:32.510  1758  1758 I ConfigFetchService: PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,06-30 10:35:32.510   752  1441 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:35:32.510   752  1441 D ActivityManager: caller:android.app.ApplicationThreadProxy@1a6e9e4b, r.packageName :com.google.android.gms
,06-30 10:35:32.510  6304  6304 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,06-30 10:35:32.510  6304  6304 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
06-30 10:35:32.510   752  1590 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,06-30 10:35:32.510   752  1590 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:32.510   752  1590 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:32.510   752  1590 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:32.510   752  1590 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:32.510  6304  6304 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,06-30 10:35:32.510  6304  6304 D InitializeManagerStateMachine: exit::IDLE
06-30 10:35:32.510  6304  6304 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,06-30 10:35:32.520   752  1691 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:32.520   752  1441 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:32.520  6304  6304 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
06-30 10:35:32.520  6304  6304 D InitializeManagerStateMachine: exit::NETWORK_CHECK
06-30 10:35:32.520  6304  6304 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
06-30 10:35:32.520  6304  6304 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
06-30 10:35:32.520  6304  6304 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
06-30 10:35:32.520  6304  6304 D InitializeManagerStateMachine: entry::SUCCESS
06-30 10:35:32.520  6304  6304 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,06-30 10:35:32.550  1758  6900 I CheckinResponseProcessor: From server: 10 gservices updates and 7 deletes
,06-30 10:35:32.550  7127  7127 E Zygote  : MountEmulatedStorage()
06-30 10:35:32.550  7127  7127 E Zygote  : v2
06-30 10:35:32.550  7127  7127 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:35:32.550  7127  7127 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:32.560   752  1590 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7127 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 10:35:32.560  6304  6304 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,06-30 10:35:32.570  7127  7127 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:32.570  7127  7127 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:32.570  1758  1758 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
06-30 10:35:32.570  1758  1758 I ConfigFetchService: GmsCore config value changed; rescheduling
,06-30 10:35:32.570  7127  7127 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:32.570  1758  1758 I ConfigFetchService: service connected
,06-30 10:35:32.570  1758  1758 D ConfigFetchService: ConfigApi connection successful.
,06-30 10:35:32.570  6304  6304 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
06-30 10:35:32.570  6304  6304 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,06-30 10:35:32.570   752   776 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:32.570  6304  6304 D InitializeManagerStateMachine: exit::SUCCESS
06-30 10:35:32.570  6304  6304 D InitializeManagerStateMachine: entry::IDLE
,06-30 10:35:32.580   752  1975 I ActivityManager: Killing 6187:com.google.android.apps.docs/u0a112 (adj 15): emptyCount ##41
,06-30 10:35:32.590  1758  7133 I ConfigFetchService: self-hosted config:fetch_interval = 43200
,06-30 10:35:32.590  1758  7133 I ConfigFetchService: stopping self
,06-30 10:35:32.600  7127  7127 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:32.600  7127  7127 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:32.610  7127  7127 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SmartManager_OSUP/SmartManager_OSUP.apk
,06-30 10:35:32.620  7127  7127 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 10:35:32.650   752  1474 I ActivityManager: Killing 6227:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##41
,06-30 10:35:32.660   752  1377 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 10:35:32.660   752  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@2806d427, r.packageName :com.google.android.gms
,06-30 10:35:32.660  1583  4835 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,06-30 10:35:32.670  1583  1583 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,06-30 10:35:32.670  1758  1758 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,06-30 10:35:32.670   752   777 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:32.670   752   777 D ActivityManager: caller:android.app.ApplicationThreadProxy@1cb666d4, r.packageName :com.google.android.gms
,06-30 10:35:32.690   752  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:32.690   752  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:32.690   752  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:32.690   752  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:32.740   752   776 D SettingsProvider: name = notification_sound_set
06-30 10:35:32.740   752   776 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.740   752   776 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.740   752   776 D SettingsProvider: selectionArgs: false
06-30 10:35:32.740   752   776 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.750   752   776 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.750   752   776 D SettingsProvider: ret = -1
,06-30 10:35:32.750   752  1550 D SettingsProvider: name = ringtone_set
,06-30 10:35:32.750   752  1550 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.750   752  1550 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.750   752  1550 D SettingsProvider: selectionArgs: false
06-30 10:35:32.750   752  1550 D SettingsProvider: selectionArgs: 10015
,06-30 10:35:32.750   752  1550 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.750   752  1550 D SettingsProvider: ret = -1
,06-30 10:35:32.760   752  1469 D SettingsProvider: name = alarm_alert_set
06-30 10:35:32.760   752  1469 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.760   752  1469 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.760   752  1469 D SettingsProvider: selectionArgs: false
06-30 10:35:32.760   752  1469 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.760   752  1469 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.760   752  1469 D SettingsProvider: ret = -1
,06-30 10:35:32.760   752  1691 D SettingsProvider: name = lockscreen.options
,06-30 10:35:32.760   752  1691 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.760   752  1691 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.760   752  1691 D SettingsProvider: selectionArgs: false
06-30 10:35:32.760   752  1691 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.760   752  1691 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,06-30 10:35:32.760   752  1691 D SettingsProvider: ret = -1
,06-30 10:35:32.760   752  1441 D SettingsProvider: name = serial_blacklist
06-30 10:35:32.760   752  1441 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.760   752  1441 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.760   752  1441 D SettingsProvider: selectionArgs: false
06-30 10:35:32.760   752  1441 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.760   752  1441 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.760   752  1441 D SettingsProvider: ret = -1
,06-30 10:35:32.760   752  1144 D SettingsProvider: name = facelock_liveliness_recognition_threshold
06-30 10:35:32.760   752  1144 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.760   752  1144 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.760   752  1144 D SettingsProvider: selectionArgs: false
06-30 10:35:32.760   752  1144 D SettingsProvider: selectionArgs: 10015
,06-30 10:35:32.760   752  1144 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.760   752  1144 D SettingsProvider: ret = -1
,06-30 10:35:32.760   752  1482 D SettingsProvider: name = config_update_certificate
06-30 10:35:32.760   752  1482 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.760   752  1482 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.760   752  1482 D SettingsProvider: selectionArgs: false
06-30 10:35:32.760   752  1482 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.760   752  1482 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.760   752  1482 D SettingsProvider: ret = -1
,06-30 10:35:32.760   752  1975 D SettingsProvider: name = pubkey_blacklist
06-30 10:35:32.760   752  1975 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.760   752  1975 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.760   752  1975 D SettingsProvider: selectionArgs: false
06-30 10:35:32.760   752  1975 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.760   752  1975 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.760   752  1975 D SettingsProvider: ret = -1
,06-30 10:35:32.770   752   777 D SettingsProvider: name = dropbox:data_app_crash
,06-30 10:35:32.770   752   777 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.770   752   777 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.770   752   777 D SettingsProvider: selectionArgs: false
06-30 10:35:32.770   752   777 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.770   752   777 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,06-30 10:35:32.770   752   777 D SettingsProvider: ret = -1
,06-30 10:35:32.770   752  1251 D SettingsProvider: name = facelock_max_center_movement
06-30 10:35:32.770   752  1251 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.770   752  1251 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.770   752  1251 D SettingsProvider: selectionArgs: false
06-30 10:35:32.770   752  1251 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.770   752  1251 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.770   752  1251 D SettingsProvider: ret = -1
,06-30 10:35:32.770   752  1474 D SettingsProvider: name = send_action_app_error
06-30 10:35:32.770   752  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.770   752  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.770   752  1474 D SettingsProvider: selectionArgs: false
06-30 10:35:32.770   752  1474 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.770   752  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.770   752  1474 D SettingsProvider: ret = -1
,06-30 10:35:32.770   752  1550 D SettingsProvider: name = facelock_detection_threshold
,06-30 10:35:32.770   752  1550 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.770   752  1550 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,06-30 10:35:32.770   752  1550 D SettingsProvider: selectionArgs: false
06-30 10:35:32.770   752  1550 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.770   752  1550 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,06-30 10:35:32.770   752  1742 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7145 uid=10015 gids={50015, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,06-30 10:35:32.770   752  1550 D SettingsProvider: ret = -1
06-30 10:35:32.770   752  7144 I CertBlacklister: Certificate blacklist changed, updating...
06-30 10:35:32.770  7145  7145 E Zygote  : MountEmulatedStorage()
06-30 10:35:32.770   752  1643 D ActivityManager: caller:android.app.ApplicationThreadProxy@1d028bc3, r.packageName :com.google.android.gms
06-30 10:35:32.770  7145  7145 E Zygote  : v2
06-30 10:35:32.770  7145  7145 I libpersona: KNOX_SDCARD checking this for 10015
06-30 10:35:32.770  7145  7145 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:32.780   752  7144 I CertBlacklister: Certificate blacklist updated
,06-30 10:35:32.800   752  1441 D SettingsProvider: name = dropbox:data_app_anr
06-30 10:35:32.800   752  1441 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.800   752  1441 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.800   752  1441 D SettingsProvider: selectionArgs: false
06-30 10:35:32.800   752  1441 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.800  7145  7145 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:32.800   752  1441 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.800   752  1441 D SettingsProvider: ret = -1
06-30 10:35:32.800  7145  7145 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:32.800   752  1482 D SettingsProvider: name = web_autofill_query_url
06-30 10:35:32.800   752  1482 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.800   752  1482 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.800   752  1482 D SettingsProvider: selectionArgs: false
06-30 10:35:32.800   752  1482 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.800   752  1482 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.800   752  1482 D SettingsProvider: ret = -1
,06-30 10:35:32.800  7145  7145 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 10:35:32.800   752   777 D SettingsProvider: name = ssl_session_cache
06-30 10:35:32.800   752   777 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.800   752   777 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.800   752   777 D SettingsProvider: selectionArgs: false
06-30 10:35:32.800   752   777 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.800   752   777 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.800   752   777 D SettingsProvider: ret = -1
,06-30 10:35:32.800   752  1474 D SettingsProvider: name = print_service_search_uri
06-30 10:35:32.800   752  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.800   752  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.800   752  1474 D SettingsProvider: selectionArgs: false
06-30 10:35:32.800   752  1474 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.800   752  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.800   752  1474 D SettingsProvider: ret = -1
,06-30 10:35:32.800   752  1550 D SettingsProvider: name = masterLocationPackagePrefixBlacklist
,06-30 10:35:32.800   752  1550 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.800   752  1550 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.800   752  1550 D SettingsProvider: selectionArgs: false
06-30 10:35:32.800   752  1550 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.800   752  1550 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,06-30 10:35:32.800   752  1550 D SettingsProvider: ret = -1
,06-30 10:35:32.800   752  1742 D SettingsProvider: name = masterLocationPackagePrefixWhitelist
06-30 10:35:32.800   752  1742 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.800   752  1742 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.800   752  1742 D SettingsProvider: selectionArgs: false
06-30 10:35:32.800   752  1742 D SettingsProvider: selectionArgs: 10015
,06-30 10:35:32.800   752  1742 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.800   752  1742 D SettingsProvider: ret = -1
,06-30 10:35:32.800   752   777 D SettingsProvider: name = dropbox:data_app_wtf
06-30 10:35:32.800   752   777 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.800   752   777 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.800   752   777 D SettingsProvider: selectionArgs: false
06-30 10:35:32.800   752   777 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.800   752   777 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.800   752   777 D SettingsProvider: ret = -1
,06-30 10:35:32.810   752  1550 D SettingsProvider: name = sms_short_codes_metadata_url
06-30 10:35:32.810   752  1550 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.810   752  1550 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,06-30 10:35:32.810   752  1550 D SettingsProvider: selectionArgs: false
06-30 10:35:32.810   752  1550 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.810   752  1550 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.810   752  1550 D SettingsProvider: ret = -1
,06-30 10:35:32.810   752  1482 D SettingsProvider: name = cert_pin_metadata_url
,06-30 10:35:32.810   752  1482 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.810   752  1482 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.810   752  1482 D SettingsProvider: selectionArgs: false
06-30 10:35:32.810   752  1482 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.810   752  1482 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,06-30 10:35:32.810   752  1482 D SettingsProvider: ret = -1
,06-30 10:35:32.810   752  1742 D SettingsProvider: name = send_action_app_error
06-30 10:35:32.810   752  1742 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.810   752  1742 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.810   752  1742 D SettingsProvider: selectionArgs: false
06-30 10:35:32.810   752  1742 D SettingsProvider: selectionArgs: 10015
,06-30 10:35:32.810   752  1742 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.810   752  1742 D SettingsProvider: ret = -1
,06-30 10:35:32.810   752   777 D SettingsProvider: name = cert_pin_content_url
06-30 10:35:32.810   752   777 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:35:32.810   752   777 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.810   752   777 D SettingsProvider: selectionArgs: false
06-30 10:35:32.810   752   777 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.810   752   777 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:35:32.810   752   777 D SettingsProvider: ret = -1
,06-30 10:35:32.810   752  1474 D SettingsProvider: name = sms_short_codes_content_url
06-30 10:35:32.810   752  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,06-30 10:35:32.810   752  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:35:32.810   752  1643 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:35:32.810   752  1474 D SettingsProvider: selectionArgs: false
06-30 10:35:32.810   752  1643 D ActivityManager: caller:android.app.ApplicationThreadProxy@3960b779, r.packageName :com.google.android.gms
06-30 10:35:32.810   752  1474 D SettingsProvider: selectionArgs: 10015
06-30 10:35:32.810   752  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,06-30 10:35:32.810   752  1474 D SettingsProvider: ret = -1
06-30 10:35:32.810  1758  7151 D LocationInitializer: Restart initialization of location
,06-30 10:35:32.820  1583  1746 I GservicesProvider: main difference update completed
,06-30 10:35:32.830  1758  6900 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,06-30 10:35:32.830  7145  7145 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:32.830  7145  7145 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:32.840  7145  7145 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,06-30 10:35:32.850  7145  7145 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 10:35:32.850  7145  7145 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 10:35:32.880  7145  7145 I MultiDex: VM with version 2.1.0 has multidex support
,06-30 10:35:32.880  7145  7145 I MultiDex: install
06-30 10:35:32.880  7145  7145 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 10:35:32.900   752  1643 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 10:35:32.900   752  1643 D ActivityManager: caller:android.app.ApplicationThreadProxy@1778211f, r.packageName :com.google.android.gms
,06-30 10:35:32.900   752  1691 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:32.900   752  1691 D ActivityManager: caller:android.app.ApplicationThreadProxy@1687b03b, r.packageName :com.google.android.gms
,06-30 10:35:32.910  7145  7145 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,06-30 10:35:32.910   752  1482 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:32.910   752  1482 D ActivityManager: caller:android.app.ApplicationThreadProxy@21371517, r.packageName :com.google.android.gms
,06-30 10:35:32.930   752  1742 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:32.930   752  1643 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:32.930   752  1643 D ActivityManager: caller:android.app.ApplicationThreadProxy@1cb192ed, r.packageName :com.google.android.gms
,06-30 10:35:32.940  7145  7145 D WearableService: callingUid 10015, callindPid: 7145
,06-30 10:35:32.960  1758  6900 I CheckinRequestBuilder: Classify the device as Phone.
,06-30 10:35:32.960  1758  6900 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,06-30 10:35:32.960  1758  1758 I SystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,06-30 10:35:32.960   752   777 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:32.960   752   777 D ActivityManager: caller:android.app.ApplicationThreadProxy@22adf522, r.packageName :com.google.android.gms
,06-30 10:35:32.960  1758  1758 D SystemUpdateService: onCreate
,06-30 10:35:32.970  1758  1758 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,06-30 10:35:32.980   752  1550 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:32.980  1758  7168 I SystemUpdateService: cancelUpdate (empty URL)
06-30 10:35:32.980  1758  7168 I SystemUpdateService: active receiver: disabled
,06-30 10:35:32.990  1493  2803 E MDM     : [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,06-30 10:35:32.990  1758  1758 D SystemUpdateService: onDestroy
,06-30 10:35:33.000  1758  6900 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,06-30 10:35:33.010  1758  6900 I CheckinService: Checking schedule, now: 1467275733025 next: 1467829090015
06-30 10:35:33.010  1758  6900 I CheckinService: active receiver: disabled
,06-30 10:35:33.030   752  1643 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 10:35:33.030   752  1643 D ActivityManager: caller:android.app.ApplicationThreadProxy@1e71900f, r.packageName :com.google.android.gms
,06-30 10:35:33.040  1758  7170 I CheckinService: Checking schedule, now: 1467275733048 next: 1467829090015
06-30 10:35:33.040  1758  7170 I CheckinService: active receiver: disabled
,06-30 10:35:33.050  1758  1758 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
,06-30 10:35:33.050  1583  5020 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,06-30 10:35:33.050  1758  1758 I OcrUtils: Updating ocr activity enabled=false
,06-30 10:35:33.060   752  1742 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:33.060   752  1742 D ActivityManager: caller:android.app.ApplicationThreadProxy@ad9189c, r.packageName :com.google.android.gms
,06-30 10:35:33.060  1493  1493 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,06-30 10:35:33.060   752   777 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:35:33.060   752   777 D ActivityManager: caller:android.app.ApplicationThreadProxy@2a6d067a, r.packageName :com.google.android.gms
,06-30 10:35:33.080  1493  1493 I GCoreUlr: DispatchingService.onCreate()
,06-30 10:35:33.120  1493  7173 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,06-30 10:35:33.180  1493  7173 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: (no Google accounts)
,06-30 10:35:33.180  1493  7173 I GCoreUlr: Unbound from all location providers
,06-30 10:35:33.190  1493  1493 I GCoreUlr: DispatchingService.onDestroy()
,06-30 10:35:33.190  1493  1493 I GCoreUlr: Unbound from all location providers
,06-30 10:35:33.250   752  1463 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:33.250   752  1463 D ActivityManager: caller:android.app.ApplicationThreadProxy@10b51046, r.packageName :com.google.android.gms
,06-30 10:35:33.260   752  1144 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:33.260   752  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@3235df34, r.packageName :com.google.android.gms
,06-30 10:35:33.260   752  1441 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:33.260   752  1441 D ActivityManager: caller:android.app.ApplicationThreadProxy@212a115d, r.packageName :com.google.android.gms
,06-30 10:35:33.290   752   777 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 10:35:33.290   752   777 D ActivityManager: caller:android.app.ApplicationThreadProxy@336927a3, r.packageName :com.google.android.gms
,06-30 10:35:33.290   752  1474 D ActivityManager: startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
,06-30 10:35:33.290   752  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:33.290   752  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:33.290   752  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:33.290   752  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:33.310   299   299 E SMD     : DCD ON
,06-30 10:35:33.330  7177  7177 E Zygote  : MountEmulatedStorage()
06-30 10:35:33.330  7177  7177 E Zygote  : v2
06-30 10:35:33.330  7177  7177 I libpersona: KNOX_SDCARD checking this for 10019
06-30 10:35:33.330  7177  7177 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:33.340  7177  7177 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,06-30 10:35:33.340  7177  7177 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:33.340  7177  7177 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 10:35:33.340   752  1474 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=7177 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,06-30 10:35:33.360  7177  7177 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:33.360  7177  7177 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:33.370  7177  7177 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
,06-30 10:35:33.380   752  1144 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,06-30 10:35:33.380   752  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@6fb6659, r.packageName :com.google.android.partnersetup
,06-30 10:35:33.390   752  1691 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,06-30 10:35:33.390   752  1691 D ActivityManager: caller:android.app.ApplicationThreadProxy@22dc9aff, r.packageName :com.google.android.partnersetup
,06-30 10:35:33.390   752  1469 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,06-30 10:35:33.390   752  1469 D ActivityManager: caller:android.app.ApplicationThreadProxy@28f30f15, r.packageName :com.google.android.partnersetup
,06-30 10:35:33.390   752  1251 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,06-30 10:35:33.390   752  1251 D ActivityManager: caller:android.app.ApplicationThreadProxy@be9e81b, r.packageName :com.google.android.partnersetup
,06-30 10:35:33.390   752   776 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,06-30 10:35:33.390   752   776 D ActivityManager: caller:android.app.ApplicationThreadProxy@3828791, r.packageName :com.google.android.partnersetup
,06-30 10:35:33.410   752  1742 D ActivityManager: startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,06-30 10:35:33.410   752  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:33.410   752  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:33.410   752  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:33.410   752  1742 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:33.450  7201  7201 E Zygote  : MountEmulatedStorage()
06-30 10:35:33.450  7201  7201 E Zygote  : v2
06-30 10:35:33.450  7201  7201 I libpersona: KNOX_SDCARD checking this for 10107
06-30 10:35:33.450  7201  7201 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:33.460   752  1742 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=7201 uid=10107 gids={50107, 9997, 3003} abi=armeabi-v7a
,06-30 10:35:33.460   752  1474 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,06-30 10:35:33.460   752  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@35b4eaf7, r.packageName :com.google.android.googlequicksearchbox
,06-30 10:35:33.470  7201  7201 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,06-30 10:35:33.470  7201  7201 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 10:35:33.470  6067  6067 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
06-30 10:35:33.470  7201  7201 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 10:35:33.470   752  1550 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:33.470  6067  7207 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,06-30 10:35:33.490  7201  7201 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:33.490  7201  7201 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:33.490  1619  7209 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_gservices_config]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,06-30 10:35:33.490  1619  7218 I GservicesUpdateTask: Updating Gservices keys
,06-30 10:35:33.490  1583  2406 I art     : Explicit concurrent mark sweep GC freed 16551(803KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 18MB/31MB, paused 565us total 24.059ms
,06-30 10:35:33.510  7201  7201 D ResourcesManager: creating new AssetManager and set to /system/app/ConfigUpdater/ConfigUpdater.apk
,06-30 10:35:33.520   752   777 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,06-30 10:35:33.520   752   777 D ActivityManager: caller:android.app.ApplicationThreadProxy@eb70bcd, r.packageName :com.sec.spp.push
,06-30 10:35:33.520  6067  7207 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,06-30 10:35:33.520  6067  7207 E art     : No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
06-30 10:35:33.520  6067  7207 W PCWCLIENTTRACE_SecurePreferencesJNI: GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
06-30 10:35:33.520  6067  7207 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,06-30 10:35:33.520  6067  7207 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
06-30 10:35:33.520  6067  7207 I PCWCLIENTTRACE_PushUtil: sales region : global
06-30 10:35:33.520  6067  7207 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,06-30 10:35:33.520  6067  7207 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,06-30 10:35:33.530   752  1377 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:33.580   752  1691 I ActivityManager: Killing 6255:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): emptyCount ##41
,06-30 10:35:33.590  1619  7218 I GStaticConfiguration: #getNewConfigurationUrl [pref=2016_04_08_14_33_37, gservice=2016_06_27_18_09_34]
,06-30 10:35:33.590  7201  7201 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-30 10:35:33.600   752  1377 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:33.610  7201  7201 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-30 10:35:33.620  7201  7201 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-30 10:35:33.630  7201  7201 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-30 10:35:33.690  3398  3522 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,06-30 10:35:33.690   752  1474 I ActivityManager: Killing 6271:com.samsung.helphub/1000 (adj 15): emptyCount ##41
,06-30 10:35:33.690   752  1482 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 10:35:33.700   752  1482 D ActivityManager: caller:android.app.ApplicationThreadProxy@bc33f93, r.packageName :com.google.android.gms
,06-30 10:35:33.700  1583  2702 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,06-30 10:35:33.700   752  1251 I art     : Explicit concurrent mark sweep GC freed 25348(1593KB) AllocSpace objects, 2(32KB) LOS objects, 30% free, 35MB/51MB, paused 1.749ms total 95.427ms
,06-30 10:35:33.700  3398  3522 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,06-30 10:35:33.710  1583  1583 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,06-30 10:35:33.710  3398  3522 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,06-30 10:35:33.710  3398  3522 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,06-30 10:35:33.710  3398  3522 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,06-30 10:35:33.710  1758  1758 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,06-30 10:35:33.720  3398  3522 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,06-30 10:35:33.720  3398  3522 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,06-30 10:35:33.720   752  1742 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:35:33.720   752  1742 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e330bd0, r.packageName :com.google.android.gms
,06-30 10:35:33.720  3398  3522 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,06-30 10:35:33.730  3398  3522 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,06-30 10:35:33.750   752  1643 D ActivityManager: caller:android.app.ApplicationThreadProxy@3c3597c9, r.packageName :com.google.android.gms
,06-30 10:35:33.750   752  1691 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:33.750   752  1691 D ActivityManager: caller:android.app.ApplicationThreadProxy@225841ef, r.packageName :com.google.android.gms
,06-30 10:35:33.750  1758  7238 D LocationInitializer: Restart initialization of location
,06-30 10:35:33.760   752  1975 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:33.760  3398  3522 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,06-30 10:35:33.770   752  1975 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:33.770  1493  4837 E MDM     : [131] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,06-30 10:35:33.780   752  1463 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 10:35:33.780   752  1463 D ActivityManager: caller:android.app.ApplicationThreadProxy@318514fc, r.packageName :com.google.android.gms
,06-30 10:35:33.790  1619  7218 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:35:33.790  1758  1758 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy}
06-30 10:35:33.790  1758  1758 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy} to Chimera receiver impl com.google.android.gms.kids.account.SystemEventReceiver
06-30 10:35:33.790  1758  1758 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,06-30 10:35:33.800  1758  1758 I Kids    : [GCoreUtils] Current gmscore version, 7571438 is smaller than the required version 8400000
,06-30 10:35:33.800  1583  2802 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,06-30 10:35:33.810   752  1590 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:33.810   752  1474 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:33.810   752   776 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:33.820   752  1643 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:33.820   752   776 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 10:35:33.820   752   776 D ActivityManager: caller:android.app.ApplicationThreadProxy@8407fe7, r.packageName :com.google.android.gms
,06-30 10:35:33.830   752  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:34.030   752  1474 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,06-30 10:35:34.030   752  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@26490900, r.packageName :com.google.android.music
,06-30 10:35:34.040   752  1691 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 10:35:34.050   752  1463 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 10:35:34.050   752  1975 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 10:35:34.050   752  1643 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,06-30 10:35:34.050   752  1643 D ActivityManager: caller:android.app.ApplicationThreadProxy@2b3e4856, r.packageName :com.google.android.music
,06-30 10:35:34.060  6816  7251 I MusicLeanback: Conditions not met for autocaching.
06-30 10:35:34.060  6816  7251 I MusicLeanback: Stop autocaching.
,06-30 10:35:34.080   752  1550 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 10:35:34.120  6816  6816 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,06-30 10:35:34.120  6816  7258 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,06-30 10:35:34.460   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:35:35.440  6751  6751 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-30 10:35:35.460   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:35:36.310   299   299 E SMD     : DCD ON
,06-30 10:35:36.470   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:35:36.550   752  1691 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,06-30 10:35:36.560  7024  7049 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,06-30 10:35:37.220   752   777 I ActivityManager: Killing 6288:com.sec.kidsplat.installer/u0a189 (adj 15): emptyCount ##41
,06-30 10:35:37.470   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:35:37.620  1583  1583 I ConfigService: onDestroy
,06-30 10:35:38.470   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:35:38.690   752  1590 D ActivityManager: bindService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,06-30 10:35:38.720  5794  7236 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,06-30 10:35:38.780   752  1377 I ActivityManager: Killing 6380:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): emptyCount ##41
,06-30 10:35:38.840   752   777 I ActivityManager: Killing 5639:sstream.app/u0a25 (adj 15): emptyCount ##41
,06-30 10:35:39.320   299   299 E SMD     : DCD ON
,06-30 10:35:39.450  6751  6751 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
06-30 10:35:39.450  6751  6751 I dhcpcd  : wlan0: no IPv6 Routers available
,06-30 10:35:39.470   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 10:35:40.070   752  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:35:40.080   752  1643 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:35:40.080   752  1643 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:35:40.080   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:35:40.080   752   752 I MotionRecognitionService: Plugged
,06-30 10:35:40.090  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:35:40.090   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:35:40.090   752  1643 D BatteryService: stay LED for fully charged
,06-30 10:35:40.090  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:35:40.100  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:35:40.100  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:35:40.100  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:35:40.100  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:35:40.100  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:35:40.110  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:35:41.520   752  3003 D SSRM:n  : SIOP:: AP = 360, PST = 377, CUR = 450
,06-30 10:35:42.280   306  3108 D WVMDrmPlugIn: WVMDrmPlugin::onTerminate : 3377
,06-30 10:35:42.320   299   299 E SMD     : DCD ON
,06-30 10:35:42.510   752  1469 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,06-30 10:35:42.510   752  1469 D ActivityManager: caller:android.app.ApplicationThreadProxy@13928c65, r.packageName :com.sec.android.app.samsungapps
,06-30 10:35:42.540  6304  6304 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,06-30 10:35:42.540  6304  6304 D PreloadUpdateManagerStateMachine: exit::IDLE
,06-30 10:35:42.540  6304  6304 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,06-30 10:35:42.550  6304  6304 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:86400000
,06-30 10:35:42.550  6304  6304 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,06-30 10:35:42.550  6304  6304 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,06-30 10:35:42.560  6304  6304 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,06-30 10:35:42.560  6304  6304 D PreloadUpdateManagerStateMachine: entry::IDLE
,06-30 10:35:43.060   752  1065 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,06-30 10:35:43.080   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,06-30 10:35:43.090   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,06-30 10:35:43.100   752  1044 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,06-30 10:35:43.100   752  1122 I InputReader: Reconfiguring input devices.  changes=0x00000010
,06-30 10:35:43.140  1418  1418 D RegisteredServicesCache: empty dynamic service
,06-30 10:35:43.140   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,06-30 10:35:43.150   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,06-30 10:35:43.160   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,06-30 10:35:43.160   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,06-30 10:35:43.170   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,06-30 10:35:43.170   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,06-30 10:35:43.170   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,06-30 10:35:43.190   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,06-30 10:35:43.190   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,06-30 10:35:43.210  1445  1526 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,06-30 10:35:43.210  3516  3516 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
,06-30 10:35:43.220   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,06-30 10:35:43.240   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,06-30 10:35:43.240   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,06-30 10:35:43.240   752   776 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,06-30 10:35:43.240   752   776 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e510c97, r.packageName :com.google.android.talk
,06-30 10:35:43.250   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,06-30 10:35:43.250   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,06-30 10:35:43.250   752  1474 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 10:35:43.250  4640  4640 I Babel   : Creating RTCS
06-30 10:35:43.250   752  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@1c8fdb33, r.packageName :com.google.android.gms
,06-30 10:35:43.250   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,06-30 10:35:43.260   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,06-30 10:35:43.260   752   776 D ActivityManager: startProcessLocked calleePkgName: sstream.app, hostingType: broadcast
,06-30 10:35:43.270  1758  7297 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,06-30 10:35:43.270   752   776 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:43.270   752   776 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:43.270   752   776 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:43.270   752   776 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:43.270   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,06-30 10:35:43.270   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,06-30 10:35:43.280   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,06-30 10:35:43.280   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,06-30 10:35:43.280   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,06-30 10:35:43.290   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,06-30 10:35:43.290   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.290   752  1251 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,06-30 10:35:43.290   752  1251 D SecContentProvider2: mCursor = null
06-30 10:35:43.290   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.290   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,06-30 10:35:43.290   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,06-30 10:35:43.300   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.300   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,06-30 10:35:43.300   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,06-30 10:35:43.310   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,06-30 10:35:43.310  7299  7299 E Zygote  : MountEmulatedStorage()
06-30 10:35:43.310  7299  7299 E Zygote  : v2
06-30 10:35:43.310  7299  7299 I libpersona: KNOX_SDCARD checking this for 10025
06-30 10:35:43.310  7299  7299 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:43.320   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,06-30 10:35:43.320   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.320   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,06-30 10:35:43.320   752   752 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
06-30 10:35:43.320   752   752 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,06-30 10:35:43.330   752   776 I ActivityManager: Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=7299 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,06-30 10:35:43.330   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.330   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.330   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.330   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,06-30 10:35:43.340   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.340   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,06-30 10:35:43.340   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,06-30 10:35:43.350  7299  7299 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:35:43.350  7299  7299 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:43.350  4640  4640 I Babel   : Destroying RTCS
,06-30 10:35:43.350  7299  7299 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:35:43.350   752   752 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,06-30 10:35:43.350   752   752 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
,06-30 10:35:43.370   752   752 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,06-30 10:35:43.370   752   752 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@33632b0a
,06-30 10:35:43.370   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.370   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.380   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,06-30 10:35:43.380   752  1377 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:43.380   752   777 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:43.380   752   994 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,06-30 10:35:43.380   752   994 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 10:35:43.390  7299  7299 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:43.390  7299  7299 D ActivityThread: Added TimaKeyStore provider
06-30 10:35:43.390   752   994 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 10:35:43.400   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.400   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,06-30 10:35:43.400  7299  7299 D ResourcesManager: creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
,06-30 10:35:43.400   752  1065 D PackageManager: [MSG] WRITE_SETTINGS
,06-30 10:35:43.400  7299  7299 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 10:35:43.420  1758  7297 I art     : Explicit concurrent mark sweep GC freed 46054(3MB) AllocSpace objects, 27(1032KB) LOS objects, 24% free, 21MB/28MB, paused 722us total 66.418ms
,06-30 10:35:43.420  1758  7297 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,06-30 10:35:43.430   752  1463 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:43.480   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,06-30 10:35:43.480   752  1463 D ActivityManager: caller:android.app.ApplicationThreadProxy@2fb0a857, r.packageName :com.google.android.gms
,06-30 10:35:43.490   752  1550 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:35:43.490   752  1550 D ActivityManager: caller:android.app.ApplicationThreadProxy@1da3782d, r.packageName :com.google.android.gms
,06-30 10:35:43.490   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.490   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,06-30 10:35:43.490   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.500   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:35:43.500   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 10:35:43.500   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,06-30 10:35:43.500   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.500   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,06-30 10:35:43.500   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:35:43.500  1758  3879 I Icing   : updateResources: need to parse f{com.google.android.gms}
,06-30 10:35:43.500   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
06-30 10:35:43.500   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,06-30 10:35:43.510   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.510   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 10:35:43.510   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 10:35:43.510  7299  7299 W linker  : libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,06-30 10:35:43.510  1493  1493 V GmsNetworkLocationProvi: DISABLE
,06-30 10:35:43.520  7299  7299 D MVFD_interface: <<<  caMVFace_FaceInit
,06-30 10:35:43.520  1493  1493 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,06-30 10:35:43.570   752   994 D LocationProviderProxy: applying state to connected service
,06-30 10:35:43.570   752   994 D LocationProviderProxy: applying state to connected service
,06-30 10:35:43.580   265   545 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
06-30 10:35:43.580   265   545 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:35:43.580  7299  7299 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
,06-30 10:35:43.590   265   545 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
06-30 10:35:43.590   265   545 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:35:43.590  7299  7299 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
,06-30 10:35:43.670  7299  7299 D HockeyApp: Current handler class = sstream.app.util.Log$1
,06-30 10:35:43.790  7299  7330 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,06-30 10:35:43.800  7299  7330 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 10:35:43.820  7299  7330 D ApplicationCompatibleReceiver: com.sec.chaton Already existed in setting table , SKIP!!!
,06-30 10:35:43.820  7299  7330 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,06-30 10:35:43.820  7299  7330 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,06-30 10:35:43.820  7299  7330 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 10:35:43.820  7299  7330 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
06-30 10:35:43.820  7299  7330 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 10:35:43.820  7299  7330 W ResourcesManager: Asset path '/system/framework/videowall.jar' does not exist or contains no resources.
,06-30 10:35:43.820  7299  7330 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,06-30 10:35:43.830  7299  7330 D ApplicationCompatibleReceiver: com.sec.android.app.videoplayer Already existed in setting table , SKIP!!!
,06-30 10:35:43.830  7299  7330 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,06-30 10:35:43.830  7299  7330 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
06-30 10:35:43.830  7299  7330 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 10:35:43.830  7299  7330 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,06-30 10:35:43.840  7299  7330 D ApplicationCompatibleReceiver: com.sec.pcw Already existed in setting table , SKIP!!!
,06-30 10:35:43.840  7299  7330 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,06-30 10:35:43.840  7299  7330 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 10:35:43.840  7299  7330 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-30 10:35:43.840  7299  7330 D ApplicationCompatibleReceiver: com.samsung.android.app.pinboard Already existed in setting table , SKIP!!!
,06-30 10:35:43.840  7299  7330 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,06-30 10:35:43.840  7299  7330 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 10:35:43.850  7299  7330 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:35:43.850  7299  7330 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 10:35:43.850  7299  7330 E SQLiteLog: (1299) abort at 20 in [INSERT INTO config(selected,category,native_package_names,image_unselected,image_selected,login,application_name,visible,native_app_required,config_id,stream_id,source_icon) VALUES (?,?,?,?,?,?
,06-30 10:35:43.850  7299  7330 E SQLiteDatabase: Error inserting selected=1 category=com.android.calendar native_package_names=null image_unselected=2130903040 image_selected=2130903040 login=0 application_name=2131625003 visible=1 native_app_required=0 config_id=com.android.calendar stream_id=null source_icon=0
06-30 10:35:43.850  7299  7330 E SQLiteDatabase: android.database.sqlite.SQLiteConstraintException: NOT NULL constraint failed: config.stream_id (code 1299)
06-30 10:35:43.850  7299  7330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
06-30 10:35:43.850  7299  7330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
06-30 10:35:43.850  7299  7330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
06-30 10:35:43.850  7299  7330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
06-30 10:35:43.850  7299  7330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1595)
06-30 10:35:43.850  7299  7330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1465)
06-30 10:35:43.850  7299  7330 E SQLiteDatabase: 	at sstream.app.provider.StoryProvider.insertOne(StoryProvider.java:352)
06-30 10:35:43.850  7299  7330 E SQLiteDatabase: 	at sstream.app.provider.StoryProvider.insert(StoryProvider.java:263)
06-30 10:35:43.850  7299  7330 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
06-30 10:35:43.850  7299  7330 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1217)
06-30 10:35:43.850  7299  7330 E SQLiteDatabase: 	at sstream.app.provider.DatabaseUtil.storeConfigSetting(DatabaseUtil.java:784)
06-30 10:35:43.850  7299  7330 E SQLiteDatabase: 	at sstream.app.receiver.ApplicationCompatibleReceiver.addCompatibleAppsToDB(ApplicationCompatibleReceiver.java:420)
06-30 10:35:43.850  7299  7330 E SQLiteDatabase: 	at sstream.app.receiver.ApplicationCompatibleReceiver.getCompatibleApps(ApplicationCompatibleReceiver.java:155)
06-30 10:35:43.850  7299  7330 E SQLiteDatabase: 	at sstream.app.StreamManager$1.run(StreamManager.java:177)
,06-30 10:35:43.850  7299  7330 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,06-30 10:35:43.850  7299  7330 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 10:35:43.850  7299  7330 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:35:43.850  7299  7330 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
06-30 10:35:43.850  7299  7330 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 10:35:43.850  7299  7330 W ResourcesManager: Asset path '/system/framework/svi.jar' does not exist or contains no resources.
06-30 10:35:43.850  7299  7330 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
06-30 10:35:43.850  7299  7330 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-30 10:35:43.860  7299  7330 D ApplicationCompatibleReceiver: com.sec.android.gallery3d Already existed in setting table , SKIP!!!
,06-30 10:35:43.860  7299  7330 D ResourcesManager: creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,06-30 10:35:43.860  7299  7330 D ApplicationCompatibleReceiver: com.sec.android.app.samsungapps Already existed in setting table , SKIP!!!
,06-30 10:35:43.870  7299  7330 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,06-30 10:35:43.870  7299  7330 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,06-30 10:35:43.870  7299  7330 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,06-30 10:35:43.870  7299  7330 D ApplicationCompatibleReceiver: com.samsung.android.snote Already existed in setting table , SKIP!!!
,06-30 10:35:43.960   752  1377 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,06-30 10:35:43.960   752  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@4bcebf8, r.packageName :com.google.android.googlequicksearchbox
,06-30 10:35:43.970  1619  7337 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,06-30 10:35:43.970  6543  6543 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,06-30 10:35:43.990  7299  7322 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:35:43.990  7299  7323 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:35:43.990  7299  7323 I System.out: (HTTPLog)-Static: isShipBuild true
06-30 10:35:43.990  7299  7323 I System.out: (HTTPLog)-Thread-1203-734268600: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
06-30 10:35:43.990  7299  7323 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:35:43.990  7299  7322 I System.out: (HTTPLog)-Static: isShipBuild true
,06-30 10:35:43.990  7299  7322 I System.out: (HTTPLog)-Thread-1202-964006683: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
06-30 10:35:43.990  7299  7322 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:35:43.990  7299  7324 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:35:44.000  5779  5779 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,06-30 10:35:44.010   752  1590 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,06-30 10:35:44.010   752  1590 D ActivityManager: caller:android.app.ApplicationThreadProxy@2e3c0f36, r.packageName :com.google.android.apps.plus
,06-30 10:35:44.020   752  1377 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,06-30 10:35:44.020   752  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@37d0cfa4, r.packageName :com.google.android.apps.plus
,06-30 10:35:44.020   752  1463 D ActivityManager: startProcessLocked calleePkgName: flipboard.app, hostingType: broadcast
,06-30 10:35:44.020   752  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:44.020   752  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:44.020   752  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:35:44.020   752  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:35:44.030  1619  7337 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,06-30 10:35:44.040  1619  7337 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 74 ms] updated apps [took 74 ms] 
,06-30 10:35:44.040  7299  7323 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 10:35:44.040  7299  7323 I qtaguid : Tagging socket 50 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 7299, getuid(): 10025
,06-30 10:35:44.040  7299  7322 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 10:35:44.040  7299  7322 I qtaguid : Tagging socket 54 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 7299, getuid(): 10025
,06-30 10:35:44.050  7299  7324 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 10:35:44.050  7299  7324 I qtaguid : Tagging socket 51 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 7299, getuid(): 10025
,06-30 10:35:44.070  7350  7350 E Zygote  : MountEmulatedStorage()
,06-30 10:35:44.070  7350  7350 E Zygote  : v2
,06-30 10:35:44.070  7350  7350 I libpersona: KNOX_SDCARD checking this for 10125
06-30 10:35:44.070  7350  7350 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:44.080   752  1463 I ActivityManager: Start proc flipboard.app for broadcast flipboard.app/flipboard.sstream.SstreamBroadcastReceiver: pid=7350 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:44.080   752  1474 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
06-30 10:35:44.080   752  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@331e8c2, r.packageName :com.samsung.android.app.galaxyfinder
,06-30 10:35:44.090  7350  7350 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,06-30 10:35:44.090  7350  7350 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:35:44.090  7350  7350 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,06-30 10:35:44.130  7350  7350 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:35:44.130  7350  7350 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:44.150  7350  7350 D ResourcesManager: creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,06-30 10:35:44.180  7350  7350 I MultiDex: VM with version 2.1.0 has multidex support
,06-30 10:35:44.180  7350  7350 I MultiDex: install
06-30 10:35:44.180  7350  7350 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 10:35:44.240   752  1377 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:44.250   265   545 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
06-30 10:35:44.250  7350  7350 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
06-30 10:35:44.250   265   545 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:35:44.270   265   545 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
06-30 10:35:44.270  7350  7371 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
06-30 10:35:44.270   265   545 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:35:44.340  7350  7350 I System.out: Reading bundled version for config.json
,06-30 10:35:44.460  7350  7350 I System.out: Reading bundled version for services.json
,06-30 10:35:44.460   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:35:44.480  7350  7350 I System.out: Reading bundled version for dynamicStrings.json
,06-30 10:35:44.510  7350  7350 I System.out: Parsed section Cover Stories, private: false
,06-30 10:35:44.540   752  1463 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:35:44.540   752   776 I ActivityManager: Killing 6614:com.sec.android.provider.badge/u0a92 (adj 15): emptyCount ##41
,06-30 10:35:44.590  7299  7322 I qtaguid : Untagging socket 54
06-30 10:35:44.590  7299  7324 I qtaguid : Untagging socket 51
,06-30 10:35:44.600  7299  7323 I qtaguid : Untagging socket 50
,06-30 10:35:45.320   299   299 E SMD     : DCD ON
,06-30 10:35:47.890   752  1338 E Watchdog: !@Sync 4
,06-30 10:35:48.320   299   299 E SMD     : DCD ON
,06-30 10:35:48.590   752  1482 I ActivityManager: Killing 6629:com.google.android.apps.maps/u0a140 (adj 15): emptyCount ##41
,06-30 10:35:49.480   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:35:50.120   752  1975 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:35:50.120   752  1975 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:35:50.120   752  1975 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:35:50.130   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:35:50.130   752   752 I MotionRecognitionService: Plugged
,06-30 10:35:50.130   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:35:50.140  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:35:50.140  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:35:50.140   752  1975 D BatteryService: stay LED for fully charged
,06-30 10:35:50.140  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:35:50.150  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:35:50.150  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:35:50.150  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:35:50.160  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:35:50.160  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:35:50.480   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:35:51.320   299   299 E SMD     : DCD ON
,06-30 10:35:51.470   752  2023 V SAMP_SPCM_test: CSC File load.. 
,06-30 10:35:51.480   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:35:51.510   752  2023 D ResourcesManager: creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,06-30 10:35:51.570   752  3003 D SSRM:n  : SIOP:: AP = 350, PST = 369, CUR = 450
,06-30 10:35:51.590   752  2023 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,06-30 10:35:51.610   752  2023 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,06-30 10:35:52.480   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:35:53.480   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:35:54.320   299   299 E SMD     : DCD ON
,06-30 10:35:54.480   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 10:35:55.820   752  1049 I PowerManagerService: [PWL] Off : 105s ago
,06-30 10:35:57.320   299   299 E SMD     : DCD ON
,06-30 10:35:59.990   752  1113 V AlarmManager: waitForAlarm result :8
,06-30 10:36:00.180   752  1975 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:36:00.190   752  1975 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:36:00.190   752  1975 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:36:00.190   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:36:00.190   752   752 I MotionRecognitionService: Plugged
,06-30 10:36:00.190   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:36:00.200  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:36:00.200  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:36:00.200  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:36:00.200  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:36:00.200   752  1975 D BatteryService: stay LED for fully charged
,06-30 10:36:00.210  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:00.210  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:00.210  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:36:00.210  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:36:00.320   299   299 E SMD     : DCD ON
,06-30 10:36:01.620   752  3003 D SSRM:n  : SIOP:: AP = 340, PST = 362, CUR = 450
,06-30 10:36:03.320   299   299 E SMD     : DCD ON
,06-30 10:36:04.460   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:36:06.320   299   299 E SMD     : DCD ON
,06-30 10:36:09.330   299   299 E SMD     : DCD ON
,06-30 10:36:09.490   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:36:10.230   752  1474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:36:10.230   752  1474 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:36:10.230   752  1474 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:36:10.240   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:36:10.240  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:36:10.240  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:36:10.250   752   752 I MotionRecognitionService: Plugged
,06-30 10:36:10.250   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:36:10.250   752  1474 D BatteryService: stay LED for fully charged
,06-30 10:36:10.250  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:36:10.250  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:36:10.260  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:36:10.260  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:10.260  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:10.260  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:10.490   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:36:11.490   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:36:11.660   752  3003 D SSRM:n  : SIOP:: AP = 330, PST = 358, CUR = 450
,06-30 10:36:12.330   299   299 E SMD     : DCD ON
,06-30 10:36:12.490   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:36:13.490   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:36:14.490   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 10:36:15.330   299   299 E SMD     : DCD ON
,06-30 10:36:17.900   752  1338 E Watchdog: !@Sync 5
,06-30 10:36:18.330   299   299 E SMD     : DCD ON
,06-30 10:36:21.330   299   299 E SMD     : DCD ON
,06-30 10:36:21.710   752  3003 D SSRM:n  : SIOP:: AP = 330, PST = 355, CUR = 450
,06-30 10:36:24.330   299   299 E SMD     : DCD ON
,06-30 10:36:24.470   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:36:27.330   299   299 E SMD     : DCD ON
,06-30 10:36:28.470   752  1113 V AlarmManager: waitForAlarm result :4
,06-30 10:36:28.490   752  1398 D NtpTrustedTime: forceRefresh() from cache miss
,06-30 10:36:28.490  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 10:36:28.490  1197  1197 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:36:28.510   752  1643 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:36:28.530  1197  1197 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
06-30 10:36:28.530  1197  1197 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 10:36:28.540   752  1691 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:36:28.540   752  1691 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 10:36:28.540   752  1691 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:36:28.540   752  1691 D BatteryService: stay LED for fully charged
06-30 10:36:28.540   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:36:28.550  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:36:28.550  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:36:28.550  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:36:28.550  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:28.550  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:28.550   752   752 I MotionRecognitionService: Plugged
06-30 10:36:28.550   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:36:28.560  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:36:28.560  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:36:28.570  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:28.580   752  1975 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 10:36:28.580   752  1975 D ActivityManager: caller:android.app.ApplicationThreadProxy@20581f6c, r.packageName :com.google.android.gms
,06-30 10:36:28.580   752  1398 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1467275789174 mCachedNtpElapsedRealtime : 179607 mCachedNtpCertainty : 9
,06-30 10:36:28.580   752  1398 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 10:36:28.580   752  1398 D AlarmManagerService: Setting time of day to sec=1467275789
,06-30 10:36:28.580   752  1398 D AlarmManagerService: Trying to open a file
,06-30 10:36:28.590   752  1398 D AlarmManagerService: File Open Success
06-30 10:36:28.590   752  1398 D AlarmManagerService: File Close Success
06-30 10:36:28.590   752  1398 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
,06-30 10:36:29.174   752  1398 W AlarmManagerService: Unable to set rtc to 1467275789: Invalid argument
06-30 10:36:29.174   752  1113 V AlarmManager: waitForAlarm result :65536
,06-30 10:36:29.204  1816  1816 D accuweather: [Accuweather J]>>> SWW:64 [0:0] =============== BR act = androidintentactionTIME_SET
,06-30 10:36:29.204  1816  1816 D accuweather: [Accuweather J]>>> SWW:645 [0:0] renderUpdateAllCondition : [0] = 1
06-30 10:36:29.204  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
06-30 10:36:29.204  1197  1197 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:36:29.204  1816  1816 D accuweather: [Accuweather J]>>> WR:452 [0:0] =============== updateAllCondition = 1
,06-30 10:36:29.204   752   752 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
06-30 10:36:29.204  1197  1197 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
06-30 10:36:29.204   752   752 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
,06-30 10:36:29.204  1197  1197 D StatusBar-DoNotDistrub: Received intent with android.intent.action.TIME_SET action
06-30 10:36:29.204   752   752 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:29.204  1197  1197 D StatusBar-DoNotDistrub: Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,06-30 10:36:29.214   752   752 I DrmEventService:  no response from SecureClock 
,06-30 10:36:29.214  1197  1197 D StatusBar-DoNotDistrub: sendBroadcast android.intent.action.DORMANT_MODE_OFF
,06-30 10:36:29.214   307   307 V AudioPolicyManager: getOutputsForDevice device 0002 -> 0002
,06-30 10:36:29.214   752   777 I AudioService: getStreamVolume 5 index 110
06-30 10:36:29.214  1197  1197 D StatusBar-DoNotDistrub: The STREAM NOTIFICATION volume is 11
,06-30 10:36:29.214   752  1742 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,06-30 10:36:29.224  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 10:36:29.224  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 10:36:29.234  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 10:36:29.234  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 10:36:29.274  6885  6885 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,06-30 10:36:29.284  6885  6885 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,06-30 10:36:29.294   752  1590 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:36:29.294   752  1590 D ActivityManager: caller:android.app.ApplicationThreadProxy@153ff1ca, r.packageName :com.google.android.gms
,06-30 10:36:29.314   752  1590 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:36:29.314   752  1590 D ActivityManager: caller:android.app.ApplicationThreadProxy@185dc658, r.packageName :com.google.android.gms
,06-30 10:36:29.324  3974  3974 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,06-30 10:36:29.334  3974  3974 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1467275789334
,06-30 10:36:29.334  3974  3974 I KLMS-2.4.511: : MainReciver(): TIME_CHANGED
,06-30 10:36:29.334  3974  3974 I KLMS-2.4.511: : StateImplV2(): dateTimeChanged().START : Thu Jun 30 10:36:29 GMT+02:00 2016
,06-30 10:36:29.334  3974  3974 I KLMS-2.4.511: : StateImplV2(): dateTimeChanged().END
,06-30 10:36:29.344  6090  6090 W System.err: android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
,06-30 10:36:29.344  6090  6090 W System.err: 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
06-30 10:36:29.344  6090  6090 W System.err: 	at android.provider.Settings$System.getLong(Settings.java:1669)
06-30 10:36:29.344  6090  6090 W System.err: 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
06-30 10:36:29.344  6090  6090 W System.err: 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
06-30 10:36:29.344  6090  6090 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
06-30 10:36:29.344  6090  6090 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
06-30 10:36:29.344  6090  6090 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
06-30 10:36:29.344  6090  6090 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:36:29.344  6090  6090 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:36:29.344  6090  6090 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 10:36:29.344  6090  6090 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:36:29.344  6090  6090 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:36:29.344  6090  6090 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 10:36:29.344  6090  6090 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,06-30 10:36:29.364  6925  6925 I SO_AGENT: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,06-30 10:36:29.364  6138  6138 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,06-30 10:36:29.394   752  1975 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,06-30 10:36:29.394   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:29.394   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:29.394   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:29.394   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:36:29.434  7436  7436 E Zygote  : MountEmulatedStorage()
06-30 10:36:29.434  7436  7436 E Zygote  : v2
06-30 10:36:29.434  7436  7436 I libpersona: KNOX_SDCARD checking this for 10055
06-30 10:36:29.434  7436  7436 I libpersona: KNOX_SDCARD not a persona
,06-30 10:36:29.444   752  1975 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=7436 uid=10055 gids={50055, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,06-30 10:36:29.454  7436  7436 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,06-30 10:36:29.454  7436  7436 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:36:29.454  7436  7436 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,06-30 10:36:29.494  7436  7436 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:36:29.494  7436  7436 D ActivityThread: Added TimaKeyStore provider
,06-30 10:36:29.514  7436  7436 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,06-30 10:36:29.524  7436  7436 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,06-30 10:36:29.524  7436  7436 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:36:29.524  7436  7436 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,06-30 10:36:29.524  7436  7436 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 10:36:29.524  7436  7436 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
06-30 10:36:29.524  7436  7436 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,06-30 10:36:29.574  7436  7436 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,06-30 10:36:29.574  7436  7436 D Mms/TelephonyPermission: start operation mode monitor
,06-30 10:36:29.574  7436  7436 D Mms/TelephonyPermission: User ID is null set current User Id
,06-30 10:36:29.584  7436  7436 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,06-30 10:36:29.584  7436  7436 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-30 10:36:29.594  7436  7436 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
,06-30 10:36:29.594  7436  7436 D Mms/TelephonyPermission: isDefault true
06-30 10:36:29.594  7436  7436 D Mms/MmsApp: onCreate() com.android.mms
,06-30 10:36:29.644  7436  7436 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 71.257448
,06-30 10:36:29.654  7436  7436 D Mms/MmsConfig: before partial update
,06-30 10:36:29.664  7436  7436 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
06-30 10:36:29.664  7436  7436 D EasySignUpManager: serviceId : 1, features : -1
06-30 10:36:29.664  7436  7436 D EasySignUpManager: isAuth is false
06-30 10:36:29.664  7436  7436 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
06-30 10:36:29.664  7436  7436 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,06-30 10:36:29.674  1432  4034 D TP/MmsSmsProvider: query,matched:2117, calling pid = 7436
,06-30 10:36:29.674  1432  4034 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.370 ms
,06-30 10:36:29.674  7436  7436 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup
,06-30 10:36:29.674  7436  7436 D EasySignUpManager: getServiceStatus : serviceId (1) is OFF
,06-30 10:36:29.684  7436  7436 D Mms/MmsConfig: Load Resize quality : 80
,06-30 10:36:29.694  7436  7436 D Mms/MmsConfig:  enable multiwindow = true
,06-30 10:36:29.704  7436  7436 E Mms/MessageUtils: setCountryDetector : update country detector info 
,06-30 10:36:29.704  7436  7436 E Mms/MessageUtils: updateCountryIso : update country iso info 
,06-30 10:36:29.714  7436  7436 D Mms/PackageInfo: com.sec.imsservice is not installed
06-30 10:36:29.714  7436  7436 D Mms/MmsConfig: [end]    init() consume time = 67.574844
06-30 10:36:29.714  7436  7436 D Mms/MmsApp: [start]    initCountryIso consume time = 0.105156
,06-30 10:36:29.714   752  1691 D CountryDetector: The first listener is added
,06-30 10:36:29.714  7436  7436 D Mms/MmsApp: [end]    initCountryIso consume time = 3.375156
,06-30 10:36:29.714  7436  7436 D Mms/Contact: [start]    init() consume time = 2.013958
,06-30 10:36:29.724  1432  1458 D TP/MmsSmsProvider: query,matched:13, calling pid = 7436
,06-30 10:36:29.724  1432  1458 D TP/MmsSmsProvider: match 13:Elapsed time : 0.650 ms
,06-30 10:36:29.734  7436  7436 D Mms/Contact: [end]    init consume time = 20.901719
,06-30 10:36:29.744  7436  7436 D Mms/Conversation: [start]    init() consume time = 9.141042
,06-30 10:36:29.744  1432  3066 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,06-30 10:36:29.754  7436  7459 D Mms/DraftCache: [start]    rebuildCache consume time = 2.100468
,06-30 10:36:29.754  1432  3066 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,06-30 10:36:29.754  1432  1697 D TP/MmsSmsProvider: query,matched:12, calling pid = 7436
,06-30 10:36:29.754  1432  1697 D TP/MmsSmsProvider: match 12:Elapsed time : 0.951 ms
,06-30 10:36:29.754  7436  7459 D Mms/DraftCache: [end]    rebuildCache consume time = 8.320626
,06-30 10:36:29.764  1432  3066 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
06-30 10:36:29.764  1432  3066 D TP/MmsSmsProvider: need read changed broadcast:false
,06-30 10:36:29.764  7436  7436 D Mms/Conversation: [end]    init consume time = 6.037969
,06-30 10:36:29.774  7436  7436 D Mms/TelephonyUtils: getSubId from simSlot 0, return Value = -1
,06-30 10:36:29.774  7436  7436 D Mms/DownloadManager: roaming -> false (slotId = 0)
,06-30 10:36:29.774  7436  7436 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
06-30 10:36:29.774  7436  7436 D Mms/DownloadManager: auto download without roaming -> true
06-30 10:36:29.774  7436  7436 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,06-30 10:36:29.774  7436  7436 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
06-30 10:36:29.774  7436  7436 D Mms/TelephonyUtils: getSubId from simSlot 1, return Value = 9223372036854775807
06-30 10:36:29.774  7436  7436 D Mms/DownloadManager: roaming -> false (slotId = 1)
06-30 10:36:29.774  7436  7436 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
06-30 10:36:29.774  7436  7436 D Mms/DownloadManager: auto download without roaming -> true
06-30 10:36:29.774  7436  7436 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
,06-30 10:36:29.774  7436  7436 D Mms/DownloadManager: auto download during roaming secondary -> false
06-30 10:36:29.774  7436  7436 D Mms/DownloadManager: mAutoDownload ------> true
,06-30 10:36:29.794  7436  7436 D Mms/MessagingNotification: [start]    init() consume time = 27.689687
,06-30 10:36:29.794  7436  7436 D Mms/MessagingNotification: [end]    init consume time = 1.540729
,06-30 10:36:29.794  7436  7460 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 3.906875
,06-30 10:36:29.804  1432  1697 D TP/MmsSmsProvider: query,matched:0, calling pid = 7436
06-30 10:36:29.804  1432  1697 V TP/MmsSmsProvider: getSimpleConversations entered.
,06-30 10:36:29.804  1432  1697 D TP/MmsSmsProvider: match 0:Elapsed time : 1.153 ms
,06-30 10:36:29.804  1432  4034 D TP/MmsSmsProvider: query,matched:400, calling pid = 7436
,06-30 10:36:29.804  7436  7462 D Mms/Synchronizer: [start]    doSync consume time = 7.358073
06-30 10:36:29.804  7436  7460 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 0.695573
,06-30 10:36:29.804  7436  7436 D Mms/MmsApp: [end]    onCreate() consume time = 1.044948
,06-30 10:36:29.804   752  1474 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
06-30 10:36:29.804  7436  7436 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=708]
,06-30 10:36:29.804  7436  7436 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,06-30 10:36:29.804   752  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:29.804   752  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:29.804   752  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:29.804   752  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:29.804  7436  7436 D Mms/TelephonyUtils: getSubId from simSlot 0, return Value = -1
06-30 10:36:29.804  7436  7436 D Mms/DownloadManager: roaming -> false (slotId = 0)
06-30 10:36:29.804  7436  7436 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
,06-30 10:36:29.804  7436  7436 D Mms/DownloadManager: auto download without roaming -> true
06-30 10:36:29.804  7436  7436 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
06-30 10:36:29.804  7436  7436 D Mms/DownloadManager: mAutoDownload ------> true
,06-30 10:36:29.814  1432  1464 D TP/MmsSmsProvider: update uri: content://mms-sms/db_synchronization
06-30 10:36:29.814  1432  1464 V TP/MmsSmsProvider: syncDBData start
,06-30 10:36:29.814  1432  1464 V TP/MmsSmsProvider: syncDBData sms end
,06-30 10:36:29.814  1432  1464 V TP/MmsSmsProvider: syncDBData mms end
06-30 10:36:29.814  1432  1464 V TP/MmsSmsProvider: syncDBData end
,06-30 10:36:29.844  7463  7463 E Zygote  : MountEmulatedStorage()
06-30 10:36:29.844  7463  7463 E Zygote  : v2
06-30 10:36:29.844  7463  7463 I libpersona: KNOX_SDCARD checking this for 10076
06-30 10:36:29.844  7463  7463 I libpersona: KNOX_SDCARD not a persona
,06-30 10:36:29.854   752  1474 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=7463 uid=10076 gids={50076, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:36:29.864  7463  7463 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:36:29.864  7463  7463 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:36:29.864   752  1474 I ActivityManager: Killing 6713:com.samsung.shareshot/u0a192 (adj 15): emptyCount ##41
06-30 10:36:29.864  7463  7463 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:36:29.864  7436  7462 D Mms/Synchronizer: [end]    doSync consume time = 57.666823
,06-30 10:36:29.864   752  1975 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,06-30 10:36:29.864   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:36:29.864   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:29.864   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:29.864   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:36:29.904  7463  7463 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:36:29.904  7463  7463 D ActivityThread: Added TimaKeyStore provider
,06-30 10:36:29.904  7479  7479 E Zygote  : MountEmulatedStorage()
06-30 10:36:29.904  7479  7479 E Zygote  : v2
06-30 10:36:29.904  7479  7479 I libpersona: KNOX_SDCARD checking this for 10092
06-30 10:36:29.904  7479  7479 I libpersona: KNOX_SDCARD not a persona
,06-30 10:36:29.914  7479  7479 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:36:29.914  7479  7479 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:36:29.914  7479  7479 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,06-30 10:36:29.924   752  1975 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7479 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,06-30 10:36:29.934   328   328 I art     : Explicit concurrent mark sweep GC freed 8743(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 321us total 14.353ms
,06-30 10:36:29.944  7463  7463 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,06-30 10:36:29.944  7479  7479 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:36:29.944  7479  7479 D ActivityThread: Added TimaKeyStore provider
,06-30 10:36:29.944   328   328 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 265us total 10.744ms
,06-30 10:36:29.954   752  1643 I ActivityManager: Killing 4934:com.samsung.android.snote/u0a168 (adj 15): emptyCount ##41
,06-30 10:36:29.954   328   328 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 274us total 10.609ms
,06-30 10:36:30.054   752  1441 I art     : Explicit concurrent mark sweep GC freed 61026(4MB) AllocSpace objects, 20(320KB) LOS objects, 30% free, 36MB/52MB, paused 1.299ms total 89.387ms
,06-30 10:36:30.064  7479  7479 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,06-30 10:36:30.074  7479  7479 D BadgeProvider: onCreate
,06-30 10:36:30.084  7479  7479 D BadgeProvider: DatabaseHelper
,06-30 10:36:30.094   752  1441 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,06-30 10:36:30.094   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.094   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.094   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.094   752  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:36:30.094  7463  7501 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,06-30 10:36:30.134  7504  7504 E Zygote  : MountEmulatedStorage()
06-30 10:36:30.134  7504  7504 E Zygote  : v2
06-30 10:36:30.134  7504  7504 I libpersona: KNOX_SDCARD checking this for 10106
,06-30 10:36:30.134  7504  7504 I libpersona: KNOX_SDCARD not a persona
,06-30 10:36:30.144   752  1441 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=7504 uid=10106 gids={50106, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,06-30 10:36:30.154  7504  7504 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:36:30.154  7504  7504 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:36:30.154   752  1441 I ActivityManager: Killing 6067:com.sec.pcw.device/1000 (adj 15): emptyCount ##41
06-30 10:36:30.154  7504  7504 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:36:30.154  7436  7461 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,06-30 10:36:30.154  1432  4034 D TP/SmsProvider: query,matched:26, calling pid = 7436
,06-30 10:36:30.154  1432  4034 D TP/SmsProvider: match 26:Elapsed time : 0.523 ms
,06-30 10:36:30.164  1432  1962 D TP/MmsSmsProvider: query,matched:6, calling pid = 7436
,06-30 10:36:30.164  1432  1962 D TP/MmsSmsProvider: match 6:Elapsed time : 0.568 ms
,06-30 10:36:30.174  7504  7504 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:36:30.174  7504  7504 D ActivityThread: Added TimaKeyStore provider
,06-30 10:36:30.184  7436  7461 I Mms/ReservationManager: ReservationManager()
,06-30 10:36:30.184  7436  7461 I Mms/ReservationManager: resetAfterConnected()
,06-30 10:36:30.194  7504  7504 D ResourcesManager: creating new AssetManager and set to /system/app/ClockPackage_Osup/ClockPackage_Osup.apk
,06-30 10:36:30.194  7504  7504 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,06-30 10:36:30.194  7504  7504 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:36:30.194  7504  7504 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 10:36:30.194  1432  3066 D TP/MmsSmsProvider: query,matched:7, calling pid = 7436
,06-30 10:36:30.204  1432  3066 D TP/MmsSmsProvider: match 7:Elapsed time : 1.698 ms
,06-30 10:36:30.204  7436  7461 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,06-30 10:36:30.214   752  1474 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,06-30 10:36:30.214   752  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.214   752  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.214   752  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.214   752  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:36:30.264  7520  7520 E Zygote  : MountEmulatedStorage()
06-30 10:36:30.264  7520  7520 E Zygote  : v2
06-30 10:36:30.264  7520  7520 I libpersona: KNOX_SDCARD checking this for 10029
06-30 10:36:30.264  7520  7520 I libpersona: KNOX_SDCARD not a persona
,06-30 10:36:30.284  7520  7520 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:36:30.284  7520  7520 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:36:30.284  7520  7520 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:36:30.284   752  1474 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7520 uid=10029 gids={50029, 9997} abi=armeabi-v7a
,06-30 10:36:30.304   752  1550 D SettingsProvider: name = next_alarm_formatted
06-30 10:36:30.304   752  1550 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 10:36:30.304   752  1550 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 10:36:30.304   752  1550 D SettingsProvider: selectionArgs: false
06-30 10:36:30.304   752  1550 D SettingsProvider: selectionArgs: 10106
06-30 10:36:30.304   752  1550 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 10:36:30.304   752  1550 D SettingsProvider: ret = -1
,06-30 10:36:30.314  7520  7520 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:36:30.314  7520  7520 D ActivityThread: Added TimaKeyStore provider
,06-30 10:36:30.314   752  1482 I ActivityManager: Killing 6850:com.sec.android.cloudagent/u0a4 (adj 15): emptyCount ##41
,06-30 10:36:30.324  7520  7520 D ResourcesManager: creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
,06-30 10:36:30.324  7520  7520 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,06-30 10:36:30.374  7436  7461 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,06-30 10:36:30.434   752  1251 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,06-30 10:36:30.444   752  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.444   752  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.444   752  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.444   752  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:36:30.494  7535  7535 E Zygote  : MountEmulatedStorage()
06-30 10:36:30.494  7535  7535 E Zygote  : v2
,06-30 10:36:30.494  7535  7535 I libpersona: KNOX_SDCARD checking this for 10116
06-30 10:36:30.494  7535  7535 I libpersona: KNOX_SDCARD not a persona
,06-30 10:36:30.494   752  1251 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7535 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,06-30 10:36:30.524  7535  7535 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:36:30.524  7535  7535 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 10:36:30.524   752  1251 I ActivityManager: Killing 6869:com.sec.android.diagmonagent/1000 (adj 15): emptyCount ##41
,06-30 10:36:30.524  7535  7535 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:36:30.554  7535  7535 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:36:30.554  7535  7535 D ActivityThread: Added TimaKeyStore provider
,06-30 10:36:30.564  7535  7535 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,06-30 10:36:30.584  7535  7535 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,06-30 10:36:30.584  7535  7535 D elm:14491: ELMEngine.ELMEngine( context ).
,06-30 10:36:30.584  7535  7535 D elm:14491: MDMBridge.setEnterpriseBridge()
,06-30 10:36:30.584   752  1144 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,06-30 10:36:30.584   752  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@2858dd2b, r.packageName :com.sec.esdk.elm
,06-30 10:36:30.584  7535  7535 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,06-30 10:36:30.594   752   777 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,06-30 10:36:30.594   752   777 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.594   752   777 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.594   752   777 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.594   752   777 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:36:30.594  7535  7535 D elm:14491: ElmAgentService : onCreate()
,06-30 10:36:30.594  7535  7550 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,06-30 10:36:30.594  7535  7550 D elm:14491: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,06-30 10:36:30.604  7535  7535 D elm:14491: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,06-30 10:36:30.604  7535  7535 D elm:14491: ModuleBase.ModifySetAlarm()
06-30 10:36:30.604  7535  7535 D elm:14491: MDMBridge.getInstance()
,06-30 10:36:30.604  7535  7535 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,06-30 10:36:30.614  7436  7552 D Mms/PerformanceUtils: link cahcing start
,06-30 10:36:30.634  7553  7553 E Zygote  : MountEmulatedStorage()
06-30 10:36:30.634  7553  7553 I libpersona: KNOX_SDCARD checking this for 10172
06-30 10:36:30.634  7553  7553 E Zygote  : v2
06-30 10:36:30.634  7553  7553 I libpersona: KNOX_SDCARD not a persona
,06-30 10:36:30.644   752   777 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7553 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,06-30 10:36:30.644  7436  7552 D Mms/PerformanceUtils: link cahcing done
,06-30 10:36:30.654  7553  7553 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:36:30.654  7553  7553 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:36:30.654  7535  7535 D elm:14491: ElmAgentService : onDestroy().
06-30 10:36:30.654  7553  7553 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:36:30.654   752  1975 I ActivityManager: Killing 6907:com.samsung.android.app.pinboard:tagService/u0a36 (adj 15): emptyCount ##41
,06-30 10:36:30.694  7553  7553 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:36:30.694  7553  7553 D ActivityThread: Added TimaKeyStore provider
,06-30 10:36:30.704  7553  7553 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,06-30 10:36:30.704  7553  7553 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,06-30 10:36:30.704  7553  7553 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:36:30.704  7553  7553 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 10:36:30.754   752  1441 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,06-30 10:36:30.754   752  1441 D ActivityManager: caller:android.app.ApplicationThreadProxy@2090ab21, r.packageName :com.android.calendar
,06-30 10:36:30.764   752  1691 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,06-30 10:36:30.764   752  1691 D ActivityManager: caller:android.app.ApplicationThreadProxy@3062107, r.packageName :com.android.calendar
,06-30 10:36:30.774   752  1377 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,06-30 10:36:30.774   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.774   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.774   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.774   752  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:36:30.814  7574  7574 E Zygote  : MountEmulatedStorage()
06-30 10:36:30.814  7574  7574 E Zygote  : v2
06-30 10:36:30.814  7574  7574 I libpersona: KNOX_SDCARD checking this for 10051
06-30 10:36:30.814  7574  7574 I libpersona: KNOX_SDCARD not a persona
,06-30 10:36:30.824  7574  7574 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,06-30 10:36:30.824  7574  7574 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:36:30.824  7574  7574 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,06-30 10:36:30.824   752  1377 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7574 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:36:30.834  6493  6493 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,06-30 10:36:30.834  6493  6493 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-30 10:36:30.834  6493  6493 D SecurityLogAgent: StateMachine : Current State = 1
,06-30 10:36:30.834   752   777 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:36:30.834   752  1590 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:36:30.834   752   776 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,06-30 10:36:30.834   752   776 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:36:30.834   752   776 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.834   752   776 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:30.834   752   776 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:36:30.854  7574  7574 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:36:30.854  7574  7574 D ActivityThread: Added TimaKeyStore provider
,06-30 10:36:30.874  7592  7592 E Zygote  : MountEmulatedStorage()
06-30 10:36:30.874  7592  7592 E Zygote  : v2
06-30 10:36:30.874  7592  7592 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:36:30.874  7592  7592 I libpersona: KNOX_SDCARD not a persona
,06-30 10:36:30.884  7592  7592 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,06-30 10:36:30.884  7592  7592 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:36:30.884  7592  7592 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 10:36:30.884   752   776 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7592 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 10:36:30.904  7574  7574 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,06-30 10:36:30.904  7592  7592 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:36:30.904   299   299 E SMD     : DCD ON
,06-30 10:36:30.904  7592  7592 D ActivityThread: Added TimaKeyStore provider
,06-30 10:36:30.914  7574  7574 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,06-30 10:36:30.914  7592  7592 D ResourcesManager: creating new AssetManager and set to /system/app/TimeService/TimeService.apk
,06-30 10:36:30.944  7592  7592 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1467275790945
06-30 10:36:30.944  7592  7592 D         : TimeServiceNative: User Time to be set is 1467275790945
06-30 10:36:30.944  7592  7592 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
06-30 10:36:30.944  7592  7592 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
06-30 10:36:30.944  7592  7592 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1467275790945
,06-30 10:36:30.944   340   730 D QC-time-services: Daemon: Connection accepted:time_genoff
,06-30 10:36:30.944  7592  7592 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
06-30 10:36:30.944   340  7608 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1467275790945
06-30 10:36:30.944   340  7608 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1467275790945, operation = 0
,06-30 10:36:30.944   340  7608 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/5/70 10:11:24
06-30 10:36:30.944   340  7608 D QC-time-services: Daemon:Value read from RTC seconds = 26647884000
06-30 10:36:30.944   340  7608 D QC-time-services: Daemon:new time 1467275790945 
06-30 10:36:30.944   340  7608 D QC-time-services: Daemon: delta 1440627906945 genoff 1440627906945 
06-30 10:36:30.944   340  7608 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440627906945 to memory
06-30 10:36:30.944   340  7608 D QC-time-services: Daemon:Opening File: /data/time/ats_2
06-30 10:36:30.944   340  7608 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,06-30 10:36:30.954   340  7608 D QC-time-services: Updating the TOD offset
06-30 10:36:30.954   340  7608 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440627906945 to memory
06-30 10:36:30.954   340  7608 D QC-time-services: Daemon:Opening File: /data/time/ats_1
06-30 10:36:30.954   340  7608 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,06-30 10:36:30.954  7592  7592 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,06-30 10:36:30.954   340  7608 E QC-time-services: Daemon:Update to modem bit set
06-30 10:36:30.954   340  7608 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
06-30 10:36:30.954   340  7608 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1124663106945
,06-30 10:36:30.954   752  1441 I ActivityManager: Killing 6734:com.vlingo.midas/u0a38 (adj 15): emptyCount ##41
,06-30 10:36:30.954   340   730 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
06-30 10:36:30.954   340   727 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,06-30 10:36:30.954  4660  4660 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:63 [0:0] onReceive: androidintentactionTIME_SET
,06-30 10:36:30.964  4660  4660 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:64 [0:0] appServiceStatus: 0
06-30 10:36:30.964  4660  4660 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:65 [0:0] [AR]: 0
06-30 10:36:30.964  4660  4660 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:66 [0:0] [AR]: Next time = 0
,06-30 10:36:30.964  4660  4660 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : androidintentactionTIME_SET, run:true
,06-30 10:36:30.964  4660  4660 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
06-30 10:36:30.964  4660  4660 D comsamsunglog: [MSC_Accu_Daemon]>>> daemonapp [Version : 150820735400 ] [ 1 ] 
06-30 10:36:30.964  4660  4660 D comsamsunglog: [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 10:36:30.964  4660  4660 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
,06-30 10:36:30.964  4660  4660 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,06-30 10:36:30.964  4660  4660 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,06-30 10:36:30.964  4660  4660 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,06-30 10:36:30.964  4660  4660 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,06-30 10:36:30.974  4660  4660 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,06-30 10:36:30.974  4660  4660 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 10:36:30.974  4660  4660 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,06-30 10:36:30.974  4660  4660 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,06-30 10:36:30.974  4660  4660 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,06-30 10:36:30.974  4660  4660 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,06-30 10:36:30.984  7574  7574 I CalendarProvider2: CalendarProvider2.onCreate() called
,06-30 10:36:30.984  4660  4660 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,06-30 10:36:31.084   752  1474 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,06-30 10:36:31.084   752  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@33b829ff, r.packageName :com.android.providers.calendar
,06-30 10:36:31.114   752  1441 I ActivityManager: Killing 6983:com.samsung.android.scloud.backup/u0a74 (adj 15): emptyCount ##41
,06-30 10:36:31.394   752  1049 I PowerManagerService: [PWL] Off : 140s ago
06-30 10:36:31.394   752  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
06-30 10:36:31.394   752  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
06-30 10:36:31.394   752  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10106, pid=7504, ws=null) (elapsedTime=1107)
,06-30 10:36:31.804  7436  7436 I Mms/MmsApp:  start initViewCache mms
,06-30 10:36:31.834  7436  7436 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1969.511458
,06-30 10:36:31.834  7436  7436 D Mms/ComposeMessageFragment: fillCache, easy = false
,06-30 10:36:31.954  7436  7436 D AbsListView: Get MotionRecognitionManager
,06-30 10:36:31.964   752  1691 D MotionRecognitionService:  ssp status : true
,06-30 10:36:31.964  7436  7436 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 133.332134
,06-30 10:36:32.084  7574  7574 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,06-30 10:36:32.084   752   999 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,06-30 10:36:32.094   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:36:32.094   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:32.094   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:36:32.094   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:36:32.124   752   999 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7625 uid=10171 gids={50171, 9997} abi=armeabi-v7a
,06-30 10:36:32.134  7625  7625 E Zygote  : MountEmulatedStorage()
06-30 10:36:32.134  7625  7625 E Zygote  : v2
06-30 10:36:32.134  7625  7625 I libpersona: KNOX_SDCARD checking this for 10171
06-30 10:36:32.134  7625  7625 I libpersona: KNOX_SDCARD not a persona
,06-30 10:36:32.154  7625  7625 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:36:32.154  7625  7625 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 10:36:32.154  7625  7625 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,06-30 10:36:32.154   752  1144 I ActivityManager: Killing 7007:com.android.chrome/u0a104 (adj 15): emptyCount ##41
,06-30 10:36:32.184  7625  7625 D TimaKeyStoreProvider: TimaSignature is unavailable,
06-30 10:36:32.184  7625  7625 D ActivityThread: Added TimaKeyStore provider
,06-30 10:36:32.214  7625  7625 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,06-30 10:36:32.214  7625  7625 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 10:36:32.214  7625  7625 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,06-30 10:36:32.234   752  1643 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,06-30 10:36:32.234   752  1643 D ActivityManager: caller:android.app.ApplicationThreadProxy@38941d2a, r.packageName :com.android.calendar
,06-30 10:36:32.234   752  1975 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,06-30 10:36:32.234   752  1975 D ActivityManager: caller:android.app.ApplicationThreadProxy@2abb50b8, r.packageName :com.android.calendar
,06-30 10:36:32.244   752  1643 I ActivityManager: Killing 7024:com.google.android.apps.magazines/u0a146 (adj 15): emptyCount ##41
,06-30 10:36:32.284  7436  7436 D Mms/BubbleViewCache: fillCache bubble = 8
,06-30 10:36:32.334   752  3003 D SSRM:n  : SIOP:: AP = 340, PST = 351, CUR = 450
,06-30 10:36:33.904   299   299 E SMD     : DCD ON
,06-30 10:36:35.073   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:36:36.073   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:36:36.903   299   299 E SMD     : DCD ON
,06-30 10:36:37.073   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:36:38.073   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:36:39.073   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:36:39.903   299   299 E SMD     : DCD ON
,06-30 10:36:40.073   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 10:36:42.403   752  3003 D SSRM:n  : SIOP:: AP = 330, PST = 350, CUR = 450
,06-30 10:36:42.903   299   299 E SMD     : DCD ON
,06-30 10:36:45.043   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:36:45.913   299   299 E SMD     : DCD ON
,06-30 10:36:48.473   752  1338 E Watchdog: !@Sync 6
,06-30 10:36:48.783   752  1113 V AlarmManager: waitForAlarm result :4
,06-30 10:36:48.833   752  1742 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:36:48.833   752  1742 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 10:36:48.833   752  1742 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:36:48.833   752  1742 D BatteryService: stay LED for fully charged
,06-30 10:36:48.833   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:36:48.843  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:36:48.843  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:36:48.843  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:36:48.853   752   752 I MotionRecognitionService: Plugged
,06-30 10:36:48.853  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:36:48.853  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:36:48.853   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:36:48.863  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:48.863  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:36:48.863  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:48.913   299   299 E SMD     : DCD ON
,06-30 10:36:51.913   299   299 E SMD     : DCD ON
,06-30 10:36:52.443   752  3003 D SSRM:n  : SIOP:: AP = 320, PST = 348, CUR = 450
,06-30 10:36:54.913   299   299 E SMD     : DCD ON
,06-30 10:36:57.913   299   299 E SMD     : DCD ON
,06-30 10:37:00.003   752  1113 V AlarmManager: waitForAlarm result :8
,06-30 10:37:00.063   752  1441 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:37:00.063   752  1441 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:37:00.063   752  1441 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:37:00.073   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:37:00.083  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:37:00.083  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:37:00.083   752   752 I MotionRecognitionService: Plugged
,06-30 10:37:00.083   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:37:00.083   752  1441 D BatteryService: stay LED for fully charged
,06-30 10:37:00.093  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:37:00.103  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:00.113  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:37:00.113  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:37:00.123  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:00.123  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:00.913   299   299 E SMD     : DCD ON
,06-30 10:37:02.493   752  3003 D SSRM:n  : SIOP:: AP = 320, PST = 343, CUR = 450
,06-30 10:37:03.913   299   299 E SMD     : DCD ON
,06-30 10:37:05.043   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:37:05.073   337   337 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 10:37:05.073   337   337 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 10:37:06.913   299   299 E SMD     : DCD ON
,06-30 10:37:09.913   299   299 E SMD     : DCD ON
,06-30 10:37:10.123   752   776 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:37:10.123   752   776 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:37:10.123   752   776 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:37:10.123   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:37:10.133  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:37:10.133  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:37:10.143   752   752 I MotionRecognitionService: Plugged
,06-30 10:37:10.143   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:37:10.143   752   776 D BatteryService: stay LED for fully charged
,06-30 10:37:10.143  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:37:10.143  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:10.153  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:10.153  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:37:10.153  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:37:10.163  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:11.393   752  1049 I PowerManagerService: [PWL] Off : 180s ago
,06-30 10:37:12.543   752  3003 D SSRM:n  : SIOP:: AP = 320, PST = 334, CUR = 450
,06-30 10:37:12.913   299   299 E SMD     : DCD ON
,06-30 10:37:15.083   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:37:15.913   299   299 E SMD     : DCD ON
,06-30 10:37:16.083   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:37:17.083   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:37:18.083   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:37:18.473   752  1338 E Watchdog: !@Sync 7
,06-30 10:37:18.913   299   299 E SMD     : DCD ON
,06-30 10:37:19.083   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:37:20.083   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-30 10:37:20.183   752  1441 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:37:21.923   299   299 E SMD     : DCD ON
,06-30 10:37:22.623   752  3003 D SSRM:n  : SIOP:: AP = 320, PST = 330, CUR = 450
,06-30 10:37:24.923   299   299 E SMD     : DCD ON
,06-30 10:37:25.053   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:37:25.083   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:37:26.083   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:37:27.093   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:37:27.923   299   299 E SMD     : DCD ON
,06-30 10:37:28.093   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:37:29.093   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:37:30.093   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 10:37:30.233   752  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:37:30.923   299   299 E SMD     : DCD ON
,06-30 10:37:32.673   752  3003 D SSRM:n  : SIOP:: AP = 320, PST = 327, CUR = 450
,06-30 10:37:33.923   299   299 E SMD     : DCD ON
,06-30 10:37:36.923   299   299 E SMD     : DCD ON
,06-30 10:37:39.923   299   299 E SMD     : DCD ON
,06-30 10:37:40.093   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:37:40.303   752  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:37:41.093   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:37:42.093   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:37:42.723   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 324, CUR = 450
,06-30 10:37:42.923   299   299 E SMD     : DCD ON
,06-30 10:37:43.093   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:37:44.093   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:37:45.063   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:37:45.093   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 10:37:45.923   299   299 E SMD     : DCD ON
,06-30 10:37:48.483   752  1338 E Watchdog: !@Sync 8
,06-30 10:37:48.923   299   299 E SMD     : DCD ON
,06-30 10:37:50.363   752  1463 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:37:51.923   299   299 E SMD     : DCD ON
,06-30 10:37:52.773   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 322, CUR = 450
,06-30 10:37:54.923   299   299 E SMD     : DCD ON
,06-30 10:37:56.443   752  1049 I PowerManagerService: [PWL] Off : 225s ago
,06-30 10:37:57.933   299   299 E SMD     : DCD ON
,06-30 10:38:00.093   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:38:00.423   752   776 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:38:00.423   752   776 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:38:00.423   752   776 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:38:00.433   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:38:00.433   752   752 I MotionRecognitionService: Plugged
,06-30 10:38:00.443   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:38:00.443   752   776 D BatteryService: stay LED for fully charged
,06-30 10:38:00.443  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:38:00.443  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:38:00.453  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:38:00.463  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:38:00.463  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:38:00.473  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:00.473  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:00.483  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:00.933   299   299 E SMD     : DCD ON
,06-30 10:38:01.103   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:38:01.623   287   287 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6c01090
,06-30 10:38:01.623   287   287 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: R/W request received
,06-30 10:38:01.623   287   287 I rmt_storage: wakelock acquired: 1, error no: 42
,06-30 10:38:01.623   287   660 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1228406016)
,06-30 10:38:01.693   287   660 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Bytes written = 1572864
,06-30 10:38:01.693   287   660 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Send response: res=0 err=0
06-30 10:38:01.693   287   660 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1228406016) wakelock released: 1, error no: 0
06-30 10:38:01.693   287   660 I rmt_storage: 
,06-30 10:38:01.703   287   287 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6c01090
,06-30 10:38:02.103   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:38:02.823   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 320, CUR = 450
,06-30 10:38:03.103   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:38:03.933   299   299 E SMD     : DCD ON
,06-30 10:38:04.103   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:38:05.063   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:38:05.103   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 10:38:06.933   299   299 E SMD     : DCD ON
,06-30 10:38:09.933   299   299 E SMD     : DCD ON
,06-30 10:38:10.483   752  1441 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:38:12.873   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 450
,06-30 10:38:12.933   299   299 E SMD     : DCD ON
,06-30 10:38:15.933   299   299 E SMD     : DCD ON
,06-30 10:38:18.483   752  1338 E Watchdog: !@Sync 9
,06-30 10:38:18.933   299   299 E SMD     : DCD ON
,06-30 10:38:20.543   752  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:38:21.933   299   299 E SMD     : DCD ON
,06-30 10:38:22.923   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 450
,06-30 10:38:24.933   299   299 E SMD     : DCD ON
,06-30 10:38:25.063   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:38:25.103   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:38:26.103   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:38:27.103   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:38:27.933   299   299 E SMD     : DCD ON
,06-30 10:38:28.103   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:38:29.113   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:38:30.113   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 10:38:30.603   752  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:38:30.603   752  1590 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:38:30.603   752  1590 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:38:30.613   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:38:30.613  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:38:30.623  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:38:30.623   752   752 I MotionRecognitionService: Plugged
,06-30 10:38:30.623   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:38:30.623   752  1590 D BatteryService: stay LED for fully charged
,06-30 10:38:30.633  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:38:30.643  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:38:30.643  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:38:30.663  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:30.663  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:30.663  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:30.933   299   299 E SMD     : DCD ON
,06-30 10:38:32.963   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 450
,06-30 10:38:33.943   299   299 E SMD     : DCD ON
,06-30 10:38:36.943   299   299 E SMD     : DCD ON
,06-30 10:38:39.943   299   299 E SMD     : DCD ON
,06-30 10:38:40.663   752  1691 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:38:42.943   299   299 E SMD     : DCD ON
,06-30 10:38:43.013   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 450
,06-30 10:38:45.073   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:38:45.653   752  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 10:38:45.663   752  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:38:45.663   752  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:38:45.673   752  1102 I TLC_TIMA_PKM_initialize: initializing...
,06-30 10:38:45.673   752  1102 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,06-30 10:38:45.683   752  1102 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
06-30 10:38:45.683   752  1102 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,06-30 10:38:45.683   752  1102 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
06-30 10:38:45.683   752  1102 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
06-30 10:38:45.683   752  1102 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,06-30 10:38:45.683   752  1102 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
06-30 10:38:45.683   752  1102 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,06-30 10:38:45.683   752  1102 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 10:38:45.703   752  1102 D QSEECOMAPI: : Loaded image: APP id = 4
,06-30 10:38:45.703   752  1102 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,06-30 10:38:45.713   752  1102 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-30 10:38:45.943   299   299 E SMD     : DCD ON
,06-30 10:38:46.443   752  1049 I PowerManagerService: [PWL] Off : 275s ago
,06-30 10:38:46.443   752  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,06-30 10:38:46.443   752  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,06-30 10:38:46.453   752  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=752, ws=null) (elapsedTime=782)
,06-30 10:38:48.483   752  1338 E Watchdog: !@Sync 10
,06-30 10:38:48.593   752  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 10:38:48.603   752  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:38:48.613   752  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:38:48.613   752  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:38:48.943   299   299 E SMD     : DCD ON
,06-30 10:38:50.713   752  1251 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:38:50.713   752  1251 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 10:38:50.713   752  1251 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:38:50.713   752  1251 D BatteryService: stay LED for fully charged
06-30 10:38:50.713   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:38:50.723   752   752 I MotionRecognitionService: Plugged
,06-30 10:38:50.723   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:38:50.733  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:38:50.733  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:38:50.733  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:38:50.733  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:38:50.733  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:38:50.763  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:50.763  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:50.763  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:51.943   299   299 E SMD     : DCD ON
,06-30 10:38:53.063   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 450
,06-30 10:38:54.943   299   299 E SMD     : DCD ON
,06-30 10:38:55.113   337   337 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 10:38:55.113   337   337 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 10:38:57.943   299   299 E SMD     : DCD ON
,06-30 10:39:00.943   299   299 E SMD     : DCD ON
,06-30 10:39:03.113   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,06-30 10:39:03.573   752  1113 V AlarmManager: waitForAlarm result :4
,06-30 10:39:03.593   752   999 D ActivityManager: startProcessLocked calleePkgName: com.blurb.checkout, hostingType: broadcast
,06-30 10:39:03.603   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:39:03.603   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:39:03.603   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:39:03.603   752   999 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 10:39:03.633   752  1691 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:39:03.643   752  1691 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:39:03.643   752  1691 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:39:03.643   752  1691 D BatteryService: stay LED for fully charged
,06-30 10:39:03.693   752   999 I ActivityManager: Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7669 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:39:03.703  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 10:39:03.703  1197  1197 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:39:03.703   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:39:03.703  7669  7669 E Zygote  : MountEmulatedStorage()
,06-30 10:39:03.713  7669  7669 E Zygote  : v2
,06-30 10:39:03.713  7669  7669 I libpersona: KNOX_SDCARD checking this for 10096
06-30 10:39:03.713  7669  7669 I libpersona: KNOX_SDCARD not a persona
06-30 10:39:03.713  1197  1197 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
06-30 10:39:03.713  1197  1197 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 10:39:03.723   752   752 I MotionRecognitionService: Plugged
06-30 10:39:03.723   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:39:03.743  7669  7669 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,06-30 10:39:03.743  7669  7669 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 10:39:03.743  7669  7669 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,06-30 10:39:03.743  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:39:03.743  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
06-30 10:39:03.743  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:39:03.743  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
06-30 10:39:03.743  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:03.743  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:03.753  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:39:03.753  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:39:03.773  7669  7669 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:39:03.773  7669  7669 D ActivityThread: Added TimaKeyStore provider
,06-30 10:39:03.793  7669  7669 D ResourcesManager: creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,06-30 10:39:03.803   752  1474 D ActivityManager: startService callerProcessName:com.blurb.checkout, calleePkgName: com.blurb.checkout
,06-30 10:39:03.803   752  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@16b892cd, r.packageName :com.blurb.checkout
,06-30 10:39:03.823  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 10:39:03.833  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 10:39:03.853   752  1441 I ActivityManager: Killing 6659:tv.peel.samsung.app/u0a152 (adj 15): emptyCount ##41
,06-30 10:39:03.943   299   299 E SMD     : DCD ON
,06-30 10:39:05.073   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:06.943   299   299 E SMD     : DCD ON
,06-30 10:39:09.953   299   299 E SMD     : DCD ON
,06-30 10:39:10.113   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:11.113   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:12.113   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:12.953   299   299 E SMD     : DCD ON
,06-30 10:39:13.113   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:13.163   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 10:39:13.703   752  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:39:13.703   752  1590 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 10:39:13.703   752  1590 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:39:13.703   752  1590 D BatteryService: stay LED for fully charged
06-30 10:39:13.703   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:39:13.703   752   752 I MotionRecognitionService: Plugged
,06-30 10:39:13.703   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:39:13.713  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:39:13.713  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:39:13.713  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:39:13.713  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:39:13.723  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:13.723  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:39:13.723  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:13.723  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:39:14.113   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:15.113   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-30 10:39:15.953   299   299 E SMD     : DCD ON
,06-30 10:39:18.483   752  1338 E Watchdog: !@Sync 11
,06-30 10:39:18.953   299   299 E SMD     : DCD ON
,06-30 10:39:20.113   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:21.123   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:21.953   299   299 E SMD     : DCD ON
,06-30 10:39:22.123   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:23.123   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:23.243   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 10:39:23.763   752  1469 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:39:24.123   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:24.953   299   299 E SMD     : DCD ON
,06-30 10:39:25.083   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:25.123   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 10:39:27.953   299   299 E SMD     : DCD ON
,06-30 10:39:30.953   299   299 E SMD     : DCD ON
,06-30 10:39:33.313   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 10:39:33.813   752  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:39:33.953   299   299 E SMD     : DCD ON
,06-30 10:39:35.123   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:36.123   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:36.953   299   299 E SMD     : DCD ON
,06-30 10:39:37.123   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:38.123   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:39.133   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:39.953   299   299 E SMD     : DCD ON
,06-30 10:39:40.133   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 10:39:41.453   752  1049 I PowerManagerService: [PWL] Off : 330s ago
,06-30 10:39:42.953   299   299 E SMD     : DCD ON
,06-30 10:39:43.353   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 10:39:43.883   752  1474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:39:43.883   752  1474 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:39:43.883   752  1474 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:39:43.883   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:39:43.893  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:39:43.893  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:39:43.903   752   752 I MotionRecognitionService: Plugged
,06-30 10:39:43.903   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:39:43.903   752  1474 D BatteryService: stay LED for fully charged
,06-30 10:39:43.913  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:39:43.923  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:43.923  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:39:43.923  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:39:43.943  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:43.943  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:45.083   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:45.953   299   299 E SMD     : DCD ON
,06-30 10:39:48.493   752  1338 E Watchdog: !@Sync 12
,06-30 10:39:48.963   299   299 E SMD     : DCD ON
,06-30 10:39:51.963   299   299 E SMD     : DCD ON
,06-30 10:39:53.403   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 10:39:53.943   752  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:39:53.943   752  1144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:39:53.943   752  1144 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:39:53.943   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:39:53.953  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:39:53.953  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:39:53.963   752   752 I MotionRecognitionService: Plugged
,06-30 10:39:53.963   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:39:53.963   752  1144 D BatteryService: stay LED for fully charged
,06-30 10:39:53.963  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:39:53.973  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:39:53.973  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:39:53.983  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:53.983  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:39:53.983  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:54.963   299   299 E SMD     : DCD ON
,06-30 10:39:55.133   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:56.133   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:57.133   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:57.963   299   299 E SMD     : DCD ON
,06-30 10:39:58.133   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:59.133   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:39:59.993   752  1113 V AlarmManager: waitForAlarm result :8
,06-30 10:40:00.133   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 10:40:00.963   299   299 E SMD     : DCD ON
,06-30 10:40:03.453   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 10:40:03.963   299   299 E SMD     : DCD ON
,06-30 10:40:04.003   752  1474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:40:04.003   752  1474 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:40:04.003   752  1474 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:40:04.013   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:40:04.013  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:40:04.023  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:40:04.023   752   752 I MotionRecognitionService: Plugged
,06-30 10:40:04.023   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:40:04.023   752  1474 D BatteryService: stay LED for fully charged
,06-30 10:40:04.033  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:40:04.043  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:04.043  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:04.043  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:40:04.043  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:40:04.053  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:05.083   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:40:06.963   299   299 E SMD     : DCD ON
,06-30 10:40:09.963   299   299 E SMD     : DCD ON
,06-30 10:40:12.963   299   299 E SMD     : DCD ON
,06-30 10:40:13.503   752  3003 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 10:40:14.063   752  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:40:15.963   299   299 E SMD     : DCD ON
,06-30 10:40:18.493   752  1338 E Watchdog: !@Sync 13
,06-30 10:40:18.963   299   299 E SMD     : DCD ON
,06-30 10:40:20.133   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:40:21.133   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:40:21.963   299   299 E SMD     : DCD ON
,06-30 10:40:22.133   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:40:23.143   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:40:23.543   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450
,06-30 10:40:24.123   752  1251 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:40:24.123   752  1251 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:40:24.123   752  1251 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:40:24.133   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:40:24.133  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:40:24.143   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:40:24.143  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:40:24.143   752   752 I MotionRecognitionService: Plugged
,06-30 10:40:24.143   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:40:24.143   752  1251 D BatteryService: stay LED for fully charged
,06-30 10:40:24.163  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:40:24.163  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:24.163  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:24.173  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:40:24.173  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:40:24.173  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:24.973   299   299 E SMD     : DCD ON
,06-30 10:40:25.093   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:40:25.143   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 10:40:27.973   299   299 E SMD     : DCD ON
,06-30 10:40:30.973   299   299 E SMD     : DCD ON
,06-30 10:40:33.593   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450
,06-30 10:40:33.973   299   299 E SMD     : DCD ON
,06-30 10:40:34.183   752  1742 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:40:34.183   752  1742 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:40:34.193   752  1742 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:40:34.193   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:40:34.193   752   752 I MotionRecognitionService: Plugged
,06-30 10:40:34.203   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:40:34.203  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:40:34.203  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:40:34.203   752  1742 D BatteryService: stay LED for fully charged
,06-30 10:40:34.213  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:40:34.223  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:34.223  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:40:34.233  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:40:34.243  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:34.243  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:36.973   299   299 E SMD     : DCD ON
,06-30 10:40:39.973   299   299 E SMD     : DCD ON
,06-30 10:40:41.453   752  1049 I PowerManagerService: [PWL] Off : 390s ago
,06-30 10:40:42.973   299   299 E SMD     : DCD ON
,06-30 10:40:43.643   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450
,06-30 10:40:44.243   752  1469 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:40:45.093   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:40:45.973   299   299 E SMD     : DCD ON
,06-30 10:40:48.493   752  1338 E Watchdog: !@Sync 14
,06-30 10:40:48.973   299   299 E SMD     : DCD ON
,06-30 10:40:50.143   337   337 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 10:40:50.143   337   337 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 10:40:51.973   299   299 E SMD     : DCD ON
,06-30 10:40:53.723   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450
,06-30 10:40:54.303   752  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:40:54.973   299   299 E SMD     : DCD ON
,06-30 10:40:57.973   299   299 E SMD     : DCD ON
,06-30 10:41:00.983   299   299 E SMD     : DCD ON
,06-30 10:41:03.783   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450
,06-30 10:41:03.983   299   299 E SMD     : DCD ON
,06-30 10:41:04.363   752  1474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:41:04.363   752  1474 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:41:04.363   752  1474 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:41:04.363   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:41:04.373  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:41:04.373  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:41:04.373   752   752 I MotionRecognitionService: Plugged
,06-30 10:41:04.383   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:41:04.383   752  1474 D BatteryService: stay LED for fully charged
,06-30 10:41:04.383  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:41:04.393  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:41:04.393  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:41:04.403  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:04.403  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:41:04.403  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:05.093   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:41:06.983   299   299 E SMD     : DCD ON
,06-30 10:41:09.983   299   299 E SMD     : DCD ON
,06-30 10:41:10.143   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:11.143   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:12.143   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:12.983   299   299 E SMD     : DCD ON
,06-30 10:41:13.143   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:13.833   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450
,06-30 10:41:14.143   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:14.423   752  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:41:14.423   752  1144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:41:14.423   752  1144 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:41:14.433   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:41:14.433  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:41:14.443   752   752 I MotionRecognitionService: Plugged
,06-30 10:41:14.443  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:41:14.443   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:41:14.443   752  1144 D BatteryService: stay LED for fully charged
,06-30 10:41:14.453  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:41:14.463  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:14.463  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:14.463  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:41:14.463  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:41:14.473  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:15.143   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-30 10:41:15.983   299   299 E SMD     : DCD ON
,06-30 10:41:18.503   752  1338 E Watchdog: !@Sync 15
,06-30 10:41:18.983   299   299 E SMD     : DCD ON
,06-30 10:41:20.153   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:21.153   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:21.983   299   299 E SMD     : DCD ON
,06-30 10:41:22.153   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:23.153   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:23.923   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,06-30 10:41:24.153   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:24.483   752  1474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:41:24.483   752  1474 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:41:24.483   752  1474 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:41:24.493   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:41:24.493  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:41:24.493  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:41:24.503   752   752 I MotionRecognitionService: Plugged
,06-30 10:41:24.503   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:41:24.503   752  1474 D BatteryService: stay LED for fully charged
,06-30 10:41:24.513  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:41:24.523  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:24.523  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:24.533  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:41:24.533  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:41:24.543  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:24.983   299   299 E SMD     : DCD ON
,06-30 10:41:25.103   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:41:25.153   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 10:41:27.983   299   299 E SMD     : DCD ON
,06-30 10:41:30.983   299   299 E SMD     : DCD ON
,06-30 10:41:33.963   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,06-30 10:41:33.983   299   299 E SMD     : DCD ON
,06-30 10:41:34.543   752  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:41:35.153   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:36.153   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:36.393   331   331 I bootchecker: bootchecker wake up!!
,06-30 10:41:36.993   299   299 E SMD     : DCD ON
,06-30 10:41:37.153   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:38.163   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:39.163   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:39.993   299   299 E SMD     : DCD ON
,06-30 10:41:40.163   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 10:41:42.993   299   299 E SMD     : DCD ON
,06-30 10:41:44.013   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,06-30 10:41:44.603   752  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:41:44.603   752  1377 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:41:44.603   752  1377 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:41:44.603   752  1377 D BatteryService: stay LED for fully charged
06-30 10:41:44.603   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:41:44.613   752   752 I MotionRecognitionService: Plugged
,06-30 10:41:44.613  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:41:44.613  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:41:44.613   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:41:44.613  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:41:44.623  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:44.623  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:41:44.623  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:41:44.623  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:41:44.623  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:45.103   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:41:45.993   299   299 E SMD     : DCD ON
,06-30 10:41:46.453   752  1049 I PowerManagerService: [PWL] Off : 455s ago
,06-30 10:41:48.503   752  1338 E Watchdog: !@Sync 16
,06-30 10:41:48.993   299   299 E SMD     : DCD ON
,06-30 10:41:51.993   299   299 E SMD     : DCD ON
,06-30 10:41:54.063   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:41:54.673   752  1463 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:41:54.993   299   299 E SMD     : DCD ON
,06-30 10:41:55.163   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:56.163   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:57.163   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:57.993   299   299 E SMD     : DCD ON
,06-30 10:41:58.163   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:41:59.163   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:42:00.163   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 10:42:00.993   299   299 E SMD     : DCD ON
,06-30 10:42:03.993   299   299 E SMD     : DCD ON
,06-30 10:42:04.113   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:42:04.733   752   776 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:42:05.113   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:42:06.993   299   299 E SMD     : DCD ON
,06-30 10:42:09.993   299   299 E SMD     : DCD ON
,06-30 10:42:12.993   299   299 E SMD     : DCD ON
,06-30 10:42:14.153   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:42:14.793   752  1441 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:42:14.803   752  1441 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:42:14.803   752  1441 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:42:14.803   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:42:14.803   752   752 I MotionRecognitionService: Plugged
,06-30 10:42:14.803   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:42:14.803  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:42:14.813  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:42:14.813  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:42:14.813  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:42:14.813   752  1441 D BatteryService: stay LED for fully charged
,06-30 10:42:14.813  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:42:14.813  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:42:14.823  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:42:14.823  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:16.003   299   299 E SMD     : DCD ON
,06-30 10:42:18.503   752  1338 E Watchdog: !@Sync 17
,06-30 10:42:19.003   299   299 E SMD     : DCD ON
,06-30 10:42:20.163   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:42:21.163   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:42:22.003   299   299 E SMD     : DCD ON
,06-30 10:42:22.173   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:42:23.173   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:42:24.173   337   337 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:42:24.223   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:42:24.853   752  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:42:24.863   752  1643 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:42:24.863   752  1643 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:42:24.863   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:42:24.863   752   752 I MotionRecognitionService: Plugged
,06-30 10:42:24.863   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:42:24.863  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:42:24.873  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:42:24.873  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:42:24.873  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:42:24.873  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:42:24.873   752  1643 D BatteryService: stay LED for fully charged
,06-30 10:42:24.883  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:24.883  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:42:24.883  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:25.003   299   299 E SMD     : DCD ON
,06-30 10:42:25.113   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:42:25.173   337   337 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 10:42:28.003   299   299 E SMD     : DCD ON
,06-30 10:42:31.003   299   299 E SMD     : DCD ON
,06-30 10:42:34.003   299   299 E SMD     : DCD ON
,06-30 10:42:34.263   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:42:34.913   752  1691 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:42:34.913   752  1691 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:42:34.923   752  1691 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:42:34.923   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:42:34.923   752   752 I MotionRecognitionService: Plugged
,06-30 10:42:34.923  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:42:34.923   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:42:34.933  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:42:34.933  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
06-30 10:42:34.933  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:42:34.933  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
06-30 10:42:34.933   752  1691 D BatteryService: stay LED for fully charged
,06-30 10:42:34.933  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:34.943  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:34.943  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:37.003   299   299 E SMD     : DCD ON
,06-30 10:42:40.003   299   299 E SMD     : DCD ON
,06-30 10:42:43.003   299   299 E SMD     : DCD ON
,06-30 10:42:44.313   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:42:44.973   752  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:42:45.113   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:42:46.003   299   299 E SMD     : DCD ON
,06-30 10:42:48.513   752  1338 E Watchdog: !@Sync 18
,06-30 10:42:49.003   299   299 E SMD     : DCD ON
,06-30 10:42:50.173   337   337 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 10:42:50.173   337   337 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 10:42:52.003   299   299 E SMD     : DCD ON
,06-30 10:42:54.363   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:42:55.013   299   299 E SMD     : DCD ON
,06-30 10:42:55.033   752  1474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:42:55.043   752  1474 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:42:55.043   752  1474 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:42:55.043   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:42:55.043   752   752 I MotionRecognitionService: Plugged
,06-30 10:42:55.043   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:42:55.043  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:42:55.053  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 10:42:55.053  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:42:55.053  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
06-30 10:42:55.053  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:42:55.053   752  1474 D BatteryService: stay LED for fully charged
06-30 10:42:55.053  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:55.053  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:42:55.053  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:42:56.463   752  1049 I PowerManagerService: [PWL] Off : 525s ago
,06-30 10:42:58.013   299   299 E SMD     : DCD ON
,06-30 10:43:01.013   299   299 E SMD     : DCD ON
,06-30 10:43:04.013   299   299 E SMD     : DCD ON
,06-30 10:43:04.413   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:43:05.093   752  1975 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:43:05.123   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:43:07.013   299   299 E SMD     : DCD ON
,06-30 10:43:10.013   299   299 E SMD     : DCD ON
,06-30 10:43:13.013   299   299 E SMD     : DCD ON
,06-30 10:43:14.453   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:43:15.163   752  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:43:15.173   337   337 I Atfwd_Daemon: Stop the daemon....
,06-30 10:43:16.013   299   299 E SMD     : DCD ON
,06-30 10:43:18.513   752  1338 E Watchdog: !@Sync 19
,06-30 10:43:19.013   299   299 E SMD     : DCD ON
,06-30 10:43:22.013   299   299 E SMD     : DCD ON
,06-30 10:43:24.503   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:43:25.013   299   299 E SMD     : DCD ON
,06-30 10:43:25.123   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:43:25.223   752  1550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:43:25.223   752  1550 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:43:25.223   752  1550 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:43:25.223   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:43:25.233  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:43:25.243   752   752 I MotionRecognitionService: Plugged
,06-30 10:43:25.243   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:43:25.243  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:43:25.243   752  1550 D BatteryService: stay LED for fully charged
,06-30 10:43:25.253  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:43:25.263  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:25.263  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:25.263  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:43:25.263  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:43:25.283  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:28.013   299   299 E SMD     : DCD ON
,06-30 10:43:31.023   299   299 E SMD     : DCD ON
,06-30 10:43:34.023   299   299 E SMD     : DCD ON
,06-30 10:43:34.553   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:43:35.283   752  1251 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:43:35.283   752  1251 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:43:35.283   752  1251 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:43:35.293   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:43:35.293  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:43:35.303  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:43:35.303   752   752 I MotionRecognitionService: Plugged
,06-30 10:43:35.303   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:43:35.303   752  1251 D BatteryService: stay LED for fully charged
,06-30 10:43:35.313  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:43:35.323  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:35.323  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:43:35.333  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:43:35.343  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:35.343  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:37.023   299   299 E SMD     : DCD ON
,06-30 10:43:40.023   299   299 E SMD     : DCD ON
,06-30 10:43:43.023   299   299 E SMD     : DCD ON
,06-30 10:43:44.603   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:43:45.123   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:43:45.343   752  1550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:43:45.653   752  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 10:43:45.653   752  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:43:45.663   752  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:43:46.023   299   299 E SMD     : DCD ON
,06-30 10:43:48.513   752  1338 E Watchdog: !@Sync 20
,06-30 10:43:48.573   752  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 10:43:48.573   752  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:43:48.583   752  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:43:48.583   752  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:43:49.023   299   299 E SMD     : DCD ON
,06-30 10:43:52.023   299   299 E SMD     : DCD ON
,06-30 10:43:54.643   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:43:55.023   299   299 E SMD     : DCD ON
,06-30 10:43:55.403   752  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:43:55.403   752  1590 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:43:55.403   752  1590 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:43:55.413   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:43:55.413  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:43:55.423  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:43:55.423   752   752 I MotionRecognitionService: Plugged
,06-30 10:43:55.423   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:43:55.433   752  1590 D BatteryService: stay LED for fully charged
,06-30 10:43:55.433  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:43:55.443  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:55.443  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:55.443  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:43:55.453  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:43:55.453  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:58.023   299   299 E SMD     : DCD ON
,06-30 10:44:01.023   299   299 E SMD     : DCD ON
,06-30 10:44:04.033   299   299 E SMD     : DCD ON
,06-30 10:44:04.693   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:44:05.123   752  3036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:44:05.463   752  1469 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:44:05.463   752  1469 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:44:05.473   752  1469 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:44:05.473   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:44:05.473  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:44:05.483  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:44:05.483   752   752 I MotionRecognitionService: Plugged
,06-30 10:44:05.483   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:44:05.483   752  1469 D BatteryService: stay LED for fully charged
,06-30 10:44:05.493  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:44:05.503  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:05.503  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:44:05.513  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:44:05.523  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:05.523  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:07.033   299   299 E SMD     : DCD ON
,06-30 10:44:10.033   299   299 E SMD     : DCD ON
,06-30 10:44:11.463   752  1049 I PowerManagerService: [PWL] Off : 600s ago
,06-30 10:44:13.033   299   299 E SMD     : DCD ON
,06-30 10:44:14.743   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:44:15.523   752  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:44:15.523   752  1590 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:44:15.523   752  1590 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:44:15.523   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:44:15.533  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:44:15.533  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:44:15.533   752   752 I MotionRecognitionService: Plugged
,06-30 10:44:15.533   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:44:15.543   752  1590 D BatteryService: stay LED for fully charged
,06-30 10:44:15.543  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:44:15.543  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:15.553  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:15.553  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:44:15.553  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:44:15.563  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:16.033   299   299 E SMD     : DCD ON
,06-30 10:44:18.523   752  1338 E Watchdog: !@Sync 21
,06-30 10:44:19.033   299   299 E SMD     : DCD ON
,06-30 10:44:22.033   299   299 E SMD     : DCD ON
,06-30 10:44:24.793   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:44:25.033   299   299 E SMD     : DCD ON
,06-30 10:44:25.583   752  1469 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:44:25.583   752  1469 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:44:25.583   752  1469 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:44:25.593   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:44:25.603  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:44:25.603  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:44:25.603   752   752 I MotionRecognitionService: Plugged
,06-30 10:44:25.603   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:44:25.603   752  1469 D BatteryService: stay LED for fully charged
,06-30 10:44:25.613  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:44:25.623  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:25.633  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:44:25.633  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:44:25.643  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:25.643  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:28.033   299   299 E SMD     : DCD ON
,06-30 10:44:31.033   299   299 E SMD     : DCD ON
,06-30 10:44:34.033   299   299 E SMD     : DCD ON
,06-30 10:44:34.843   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:44:35.643   752   776 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:44:37.033   299   299 E SMD     : DCD ON
,06-30 10:44:40.043   299   299 E SMD     : DCD ON
,06-30 10:44:43.043   299   299 E SMD     : DCD ON
,06-30 10:44:44.883   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:44:45.703   752  1691 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:44:45.703   752  1691 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:44:45.703   752  1691 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:44:45.703   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:44:45.713   752   752 I MotionRecognitionService: Plugged
,06-30 10:44:45.713   752  1691 D BatteryService: stay LED for fully charged
,06-30 10:44:45.713   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:44:45.723  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:44:45.723  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:44:45.723  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:44:45.733  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:44:45.733  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:44:45.743  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:45.743  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:44:45.743  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:46.043   299   299 E SMD     : DCD ON
,06-30 10:44:48.523   752  1338 E Watchdog: !@Sync 22
,06-30 10:44:49.043   299   299 E SMD     : DCD ON
,06-30 10:44:52.043   299   299 E SMD     : DCD ON
,06-30 10:44:54.933   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:44:55.043   299   299 E SMD     : DCD ON
,06-30 10:44:55.763   752  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:44:58.043   299   299 E SMD     : DCD ON
,06-30 10:45:01.043   299   299 E SMD     : DCD ON
,06-30 10:45:04.043   299   299 E SMD     : DCD ON
,06-30 10:45:04.983   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:45:05.823   752   777 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:45:05.833   752   777 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:45:05.833   752   777 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:45:05.833   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:45:05.843  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:45:05.843  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:45:05.853   752   752 I MotionRecognitionService: Plugged
06-30 10:45:05.853   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:45:05.853  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:05.853  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:05.853  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:05.853  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:45:05.853  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
06-30 10:45:05.853  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:45:05.853   752   777 D BatteryService: stay LED for fully charged
,06-30 10:45:07.043   299   299 E SMD     : DCD ON
,06-30 10:45:10.043   299   299 E SMD     : DCD ON
,06-30 10:45:13.043   299   299 E SMD     : DCD ON
,06-30 10:45:15.023   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:45:15.883   752  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:45:15.883   752  1144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:45:15.883   752  1144 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:45:15.893   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:45:15.903  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:45:15.903  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:45:15.903   752   752 I MotionRecognitionService: Plugged
,06-30 10:45:15.903   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:45:15.913   752  1144 D BatteryService: stay LED for fully charged
,06-30 10:45:15.913  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:45:15.923  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:15.923  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:45:15.923  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:45:15.943  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:15.943  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:16.053   299   299 E SMD     : DCD ON
,06-30 10:45:18.523   752  1338 E Watchdog: !@Sync 23
,06-30 10:45:19.053   299   299 E SMD     : DCD ON
,06-30 10:45:22.053   299   299 E SMD     : DCD ON
,06-30 10:45:25.053   299   299 E SMD     : DCD ON
,06-30 10:45:25.103   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:45:25.943   752  1474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:45:25.943   752  1474 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:45:25.953   752  1474 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:45:25.953   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:45:25.963  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:45:25.963  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:45:25.963  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:45:25.973   752   752 I MotionRecognitionService: Plugged
,06-30 10:45:25.973  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:45:25.973  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:45:25.973  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:25.973   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:45:25.973  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:25.973   752  1474 D BatteryService: stay LED for fully charged
,06-30 10:45:25.983  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:28.053   299   299 E SMD     : DCD ON
,06-30 10:45:31.053   299   299 E SMD     : DCD ON
,06-30 10:45:31.463   752  1049 I PowerManagerService: [PWL] Off : 680s ago
,06-30 10:45:34.053   299   299 E SMD     : DCD ON
,06-30 10:45:35.153   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:45:36.003   752  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:45:36.003   752  1144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:45:36.003   752  1144 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:45:36.013   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:45:36.013  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:45:36.023  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:45:36.023   752   752 I MotionRecognitionService: Plugged
,06-30 10:45:36.023   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:45:36.023   752  1144 D BatteryService: stay LED for fully charged
,06-30 10:45:36.033  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:45:36.043  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:36.043  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:36.043  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:36.053  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:45:36.053  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:45:37.053   299   299 E SMD     : DCD ON
,06-30 10:45:40.053   299   299 E SMD     : DCD ON
,06-30 10:45:43.053   299   299 E SMD     : DCD ON
,06-30 10:45:45.233   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:45:46.053   299   299 E SMD     : DCD ON
,06-30 10:45:46.073   752   777 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:45:48.533   752  1338 E Watchdog: !@Sync 24
,06-30 10:45:49.053   299   299 E SMD     : DCD ON
,06-30 10:45:52.053   299   299 E SMD     : DCD ON
,06-30 10:45:55.063   299   299 E SMD     : DCD ON
,06-30 10:45:55.283   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:45:56.123   752  1463 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:45:56.133   752  1463 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:45:56.133   752  1463 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:45:56.133   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:45:56.143  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:45:56.143  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:45:56.153   752   752 I MotionRecognitionService: Plugged
,06-30 10:45:56.153   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:45:56.153  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:56.153  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:56.153  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:45:56.153  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
06-30 10:45:56.153   752  1463 D BatteryService: stay LED for fully charged
,06-30 10:45:56.153  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:56.163  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:45:58.063   299   299 E SMD     : DCD ON
,06-30 10:46:01.063   299   299 E SMD     : DCD ON
,06-30 10:46:04.063   299   299 E SMD     : DCD ON
,06-30 10:46:05.333   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:46:06.183   752  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:46:06.193   752  1377 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:46:06.193   752  1377 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:46:06.193   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:46:06.203  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:46:06.203  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:46:06.213   752   752 I MotionRecognitionService: Plugged
,06-30 10:46:06.213   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:46:06.213  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:06.213  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:06.213   752  1377 D BatteryService: stay LED for fully charged
,06-30 10:46:06.213  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 10:46:06.213  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:46:06.213  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:06.223  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:46:07.063   299   299 E SMD     : DCD ON
,06-30 10:46:10.063   299   299 E SMD     : DCD ON
,06-30 10:46:13.063   299   299 E SMD     : DCD ON
,06-30 10:46:15.403   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:46:16.063   299   299 E SMD     : DCD ON
,06-30 10:46:16.243   752  1742 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:46:16.253   752  1742 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:46:16.253   752  1742 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:46:16.253   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:46:16.263  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:46:16.273  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:46:16.273  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:46:16.273   752   752 I MotionRecognitionService: Plugged
06-30 10:46:16.273  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:46:16.273   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:46:16.273  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:16.273  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:46:16.273   752  1742 D BatteryService: stay LED for fully charged
,06-30 10:46:16.273  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:16.283  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:46:18.533   752  1338 E Watchdog: !@Sync 25
,06-30 10:46:19.063   299   299 E SMD     : DCD ON
,06-30 10:46:22.063   299   299 E SMD     : DCD ON
,06-30 10:46:25.063   299   299 E SMD     : DCD ON
,06-30 10:46:25.483   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:46:26.313   752  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:46:26.313   752  1482 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:46:26.313   752  1482 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:46:26.323   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:46:26.323   752   752 I MotionRecognitionService: Plugged
,06-30 10:46:26.323   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:46:26.323  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:46:26.333  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:46:26.333  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:46:26.333  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:46:26.333  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:46:26.333   752  1482 D BatteryService: stay LED for fully charged
,06-30 10:46:26.333  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:26.343  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:46:26.343  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:28.063   299   299 E SMD     : DCD ON
,06-30 10:46:31.063   299   299 E SMD     : DCD ON
,06-30 10:46:34.073   299   299 E SMD     : DCD ON
,06-30 10:46:35.523   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:46:36.373   752  1463 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:46:36.373   752  1463 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:46:36.383   752  1463 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:46:36.383   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:46:36.383   752   752 I MotionRecognitionService: Plugged
,06-30 10:46:36.383   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:46:36.383  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:46:36.393  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:46:36.393  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:46:36.393  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:46:36.393  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:46:36.393   752  1463 D BatteryService: stay LED for fully charged
06-30 10:46:36.393  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:36.403  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:36.403  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:37.073   299   299 E SMD     : DCD ON
,06-30 10:46:40.073   299   299 E SMD     : DCD ON
,06-30 10:46:43.073   299   299 E SMD     : DCD ON
,06-30 10:46:45.573   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:46:46.073   299   299 E SMD     : DCD ON
,06-30 10:46:46.433   752  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:46:46.443   752  1377 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:46:46.443   752  1377 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:46:46.443   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:46:46.443   752   752 I MotionRecognitionService: Plugged
,06-30 10:46:46.443   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:46:46.453  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:46:46.453  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:46:46.453   752  1377 D BatteryService: stay LED for fully charged
,06-30 10:46:46.453  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:46:46.453  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:46.453  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:46.463  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 10:46:46.463  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:46:46.463  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:48.533   752  1338 E Watchdog: !@Sync 26
,06-30 10:46:49.073   299   299 E SMD     : DCD ON
,06-30 10:46:49.863   752  1113 V AlarmManager: waitForAlarm result :8
,06-30 10:46:52.073   299   299 E SMD     : DCD ON
,06-30 10:46:55.073   299   299 E SMD     : DCD ON
,06-30 10:46:55.623   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:46:56.473   752  1049 I PowerManagerService: [PWL] Off : 765s ago
,06-30 10:46:56.493   752  1742 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:46:58.073   299   299 E SMD     : DCD ON
,06-30 10:47:01.073   299   299 E SMD     : DCD ON
,06-30 10:47:04.073   299   299 E SMD     : DCD ON
,06-30 10:47:05.673   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:47:06.553   752   776 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:47:07.073   299   299 E SMD     : DCD ON
,06-30 10:47:10.083   299   299 E SMD     : DCD ON
,06-30 10:47:13.083   299   299 E SMD     : DCD ON
,06-30 10:47:15.713   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:47:16.083   299   299 E SMD     : DCD ON
,06-30 10:47:16.613   752  1691 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:47:18.533   752  1338 E Watchdog: !@Sync 27
,06-30 10:47:19.083   299   299 E SMD     : DCD ON
,06-30 10:47:22.083   299   299 E SMD     : DCD ON
,06-30 10:47:25.083   299   299 E SMD     : DCD ON
,06-30 10:47:25.763   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:47:26.673   752  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:47:28.083   299   299 E SMD     : DCD ON
,06-30 10:47:31.083   299   299 E SMD     : DCD ON
,06-30 10:47:34.083   299   299 E SMD     : DCD ON
,06-30 10:47:35.813   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:47:36.733   752  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:47:36.733   752  1377 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:47:36.743   752  1377 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:47:36.743   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:47:36.743   752   752 I MotionRecognitionService: Plugged
,06-30 10:47:36.743   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:47:36.743  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:47:36.753  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:47:36.753  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:47:36.753   752  1377 D BatteryService: stay LED for fully charged
06-30 10:47:36.753  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:36.753  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:36.753  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:47:36.753  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:47:36.763  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:37.083   299   299 E SMD     : DCD ON
,06-30 10:47:40.083   299   299 E SMD     : DCD ON
,06-30 10:47:43.083   299   299 E SMD     : DCD ON
,06-30 10:47:45.863   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:47:46.093   299   299 E SMD     : DCD ON
,06-30 10:47:46.793   752  1742 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:47:46.803   752  1742 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:47:46.803   752  1742 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:47:46.803   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:47:46.803   752   752 I MotionRecognitionService: Plugged
,06-30 10:47:46.803   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:47:46.803  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:47:46.813  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:47:46.813  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:47:46.813   752  1742 D BatteryService: stay LED for fully charged
06-30 10:47:46.813  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:46.813  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:47:46.813  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:47:46.823  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:46.823  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:48.543   752  1338 E Watchdog: !@Sync 28
,06-30 10:47:49.093   299   299 E SMD     : DCD ON
,06-30 10:47:52.093   299   299 E SMD     : DCD ON
,06-30 10:47:55.093   299   299 E SMD     : DCD ON
,06-30 10:47:55.933   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:47:56.853   752  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:47:56.863   752  1482 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:47:56.863   752  1482 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:47:56.863   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:47:56.863   752   752 I MotionRecognitionService: Plugged
,06-30 10:47:56.863   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:47:56.873  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:47:56.873  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:47:56.873  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:47:56.873  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:47:56.873  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:47:56.873   752  1482 D BatteryService: stay LED for fully charged
,06-30 10:47:56.883  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:56.883  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:47:56.883  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:58.093   299   299 E SMD     : DCD ON
,06-30 10:48:01.093   299   299 E SMD     : DCD ON
,06-30 10:48:04.093   299   299 E SMD     : DCD ON
,06-30 10:48:05.973   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:48:06.913   752  1463 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:48:06.913   752  1463 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:48:06.923   752  1463 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:48:06.923   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:48:06.923  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:48:06.923  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 10:48:06.923   752   752 I MotionRecognitionService: Plugged
06-30 10:48:06.923   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:48:06.933  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:48:06.933  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:48:06.933  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:48:06.933   752  1463 D BatteryService: stay LED for fully charged
,06-30 10:48:06.933  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:06.943  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:06.943  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:07.093   299   299 E SMD     : DCD ON
,06-30 10:48:10.093   299   299 E SMD     : DCD ON
,06-30 10:48:13.093   299   299 E SMD     : DCD ON
,06-30 10:48:16.023   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:48:16.093   299   299 E SMD     : DCD ON
,06-30 10:48:16.973   752  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:48:18.543   752  1338 E Watchdog: !@Sync 29
,06-30 10:48:19.093   299   299 E SMD     : DCD ON
,06-30 10:48:22.103   299   299 E SMD     : DCD ON
,06-30 10:48:25.103   299   299 E SMD     : DCD ON
,06-30 10:48:26.073   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:48:26.473   752  1049 I PowerManagerService: [PWL] Off : 855s ago
,06-30 10:48:27.033   752  1469 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:48:28.103   299   299 E SMD     : DCD ON
,06-30 10:48:31.103   299   299 E SMD     : DCD ON
,06-30 10:48:34.103   299   299 E SMD     : DCD ON
,06-30 10:48:36.123   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:48:37.093   752  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:48:37.093   752  1643 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:48:37.103   752  1643 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:48:37.103   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:48:37.103   299   299 E SMD     : DCD ON
,06-30 10:48:37.103  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:48:37.103  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:48:37.103   752   752 I MotionRecognitionService: Plugged
06-30 10:48:37.103   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:48:37.113  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:48:37.113  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:48:37.113  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:48:37.113  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:37.123   752  1643 D BatteryService: stay LED for fully charged
,06-30 10:48:37.123  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:37.123  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:40.103   299   299 E SMD     : DCD ON
,06-30 10:48:43.103   299   299 E SMD     : DCD ON
,06-30 10:48:45.653   752  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 10:48:45.663   752  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:48:45.663   752  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:48:46.103   299   299 E SMD     : DCD ON
,06-30 10:48:46.213   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:48:47.163   752  1691 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:48:47.163   752  1691 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 10:48:47.163   752  1691 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:48:47.163   752  1691 D BatteryService: stay LED for fully charged
06-30 10:48:47.163   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:48:47.163  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:48:47.163  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:48:47.163   752   752 I MotionRecognitionService: Plugged
,06-30 10:48:47.173   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:48:47.173  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:48:47.173  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:48:47.183  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:48:47.183  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:47.183  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:48:47.183  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:48.503   752  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 10:48:48.503   752  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:48:48.513   752  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:48:48.523   752  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:48:48.543   752  1338 E Watchdog: !@Sync 30
,06-30 10:48:49.103   299   299 E SMD     : DCD ON
,06-30 10:48:52.103   299   299 E SMD     : DCD ON
,06-30 10:48:55.103   299   299 E SMD     : DCD ON
,06-30 10:48:56.263   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:48:57.213   752  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:48:57.223   752  1590 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:48:57.223   752  1590 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:48:57.223   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:48:57.223   752   752 I MotionRecognitionService: Plugged
,06-30 10:48:57.223  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:48:57.223  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:48:57.223   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:48:57.233  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:48:57.233   752  1590 D BatteryService: stay LED for fully charged
,06-30 10:48:57.233  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:57.233  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:57.243  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:48:57.243  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:48:57.253  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:58.113   299   299 E SMD     : DCD ON
,06-30 10:49:01.113   299   299 E SMD     : DCD ON
,06-30 10:49:04.113   299   299 E SMD     : DCD ON
,06-30 10:49:06.313   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:49:07.113   299   299 E SMD     : DCD ON
,06-30 10:49:07.273   752  1691 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:49:07.283   752  1691 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:49:07.283   752  1691 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:49:07.283   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:49:07.283   752   752 I MotionRecognitionService: Plugged
,06-30 10:49:07.283   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:49:07.283  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:49:07.293  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:49:07.293   752  1691 D BatteryService: stay LED for fully charged
,06-30 10:49:07.293  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:49:07.293  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:07.293  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:07.293  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:49:07.293  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
06-30 10:49:07.303  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:10.113   299   299 E SMD     : DCD ON
,06-30 10:49:13.113   299   299 E SMD     : DCD ON
,06-30 10:49:16.113   299   299 E SMD     : DCD ON
,06-30 10:49:16.353   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:49:17.333   752  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:49:17.343   752  1590 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:49:17.343   752  1590 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:49:17.343   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:49:17.343   752   752 I MotionRecognitionService: Plugged
,06-30 10:49:17.343  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:49:17.343  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:49:17.353   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:49:17.353  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:49:17.353   752  1590 D BatteryService: stay LED for fully charged
,06-30 10:49:17.353  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:17.353  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:49:17.363  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:49:17.363  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:17.363  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:18.553   752  1338 E Watchdog: !@Sync 31
,06-30 10:49:19.113   299   299 E SMD     : DCD ON
,06-30 10:49:22.113   299   299 E SMD     : DCD ON
,06-30 10:49:25.113   299   299 E SMD     : DCD ON
,06-30 10:49:26.413   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:49:27.393   752  1441 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:49:28.113   299   299 E SMD     : DCD ON
,06-30 10:49:31.113   299   299 E SMD     : DCD ON
,06-30 10:49:34.113   299   299 E SMD     : DCD ON
,06-30 10:49:36.453   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:49:37.123   299   299 E SMD     : DCD ON
,06-30 10:49:37.453   752  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:49:40.123   299   299 E SMD     : DCD ON
,06-30 10:49:43.123   299   299 E SMD     : DCD ON
,06-30 10:49:46.123   299   299 E SMD     : DCD ON
,06-30 10:49:46.503   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:49:47.513   752  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:49:47.513   752  1377 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:49:47.513   752  1377 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:49:47.523   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:49:47.523   752   752 I MotionRecognitionService: Plugged
,06-30 10:49:47.523   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:49:47.523  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:49:47.533  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:49:47.533  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:49:47.533  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:49:47.533   752  1377 D BatteryService: stay LED for fully charged
,06-30 10:49:47.533  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:49:47.533  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:49:47.543  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:49:47.543  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:48.553   752  1338 E Watchdog: !@Sync 32
,06-30 10:49:49.123   299   299 E SMD     : DCD ON
,06-30 10:49:52.123   299   299 E SMD     : DCD ON
,06-30 10:49:55.123   299   299 E SMD     : DCD ON
,06-30 10:49:56.553   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:49:57.573   752  1742 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:49:57.573   752  1742 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:49:57.583   752  1742 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:49:57.583   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:49:57.583   752   752 I MotionRecognitionService: Plugged
,06-30 10:49:57.583   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:49:57.583  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:49:57.593  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:49:57.593  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:49:57.593  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:49:57.593  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:49:57.593   752  1742 D BatteryService: stay LED for fully charged
06-30 10:49:57.593  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:57.603  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:57.603  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:58.123   299   299 E SMD     : DCD ON
,06-30 10:50:01.123   299   299 E SMD     : DCD ON
,06-30 10:50:01.473   752  1049 I PowerManagerService: [PWL] Off : 950s ago
,06-30 10:50:04.123   299   299 E SMD     : DCD ON
,06-30 10:50:06.593   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:50:07.123   299   299 E SMD     : DCD ON
,06-30 10:50:07.633   752  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:50:07.633   752  1482 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:50:07.643   752  1482 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:50:07.643   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:50:07.643   752   752 I MotionRecognitionService: Plugged
,06-30 10:50:07.643  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:50:07.643   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:50:07.653  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:50:07.653  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:50:07.653  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:50:07.653  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:50:07.653   752  1482 D BatteryService: stay LED for fully charged
,06-30 10:50:07.653  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:07.663  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:07.663  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:10.123   299   299 E SMD     : DCD ON
,06-30 10:50:13.133   299   299 E SMD     : DCD ON
,06-30 10:50:16.133   299   299 E SMD     : DCD ON
,06-30 10:50:16.643   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:50:17.693   752  1463 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:50:18.553   752  1338 E Watchdog: !@Sync 33
,06-30 10:50:19.133   299   299 E SMD     : DCD ON
,06-30 10:50:22.133   299   299 E SMD     : DCD ON
,06-30 10:50:25.133   299   299 E SMD     : DCD ON
,06-30 10:50:26.693   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:50:27.753   752   776 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:50:28.133   299   299 E SMD     : DCD ON
,06-30 10:50:31.133   299   299 E SMD     : DCD ON
,06-30 10:50:34.133   299   299 E SMD     : DCD ON
,06-30 10:50:36.743   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:50:37.133   299   299 E SMD     : DCD ON
,06-30 10:50:37.813   752  1441 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:50:37.813   752  1441 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:50:37.813   752  1441 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:50:37.823   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:50:37.823   752   752 I MotionRecognitionService: Plugged
,06-30 10:50:37.823   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:50:37.823  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:50:37.833  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:50:37.833  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:50:37.833  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:37.833  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:50:37.833  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:50:37.833  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:37.843   752  1441 D BatteryService: stay LED for fully charged
,06-30 10:50:37.843  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:40.133   299   299 E SMD     : DCD ON
,06-30 10:50:43.133   299   299 E SMD     : DCD ON
,06-30 10:50:46.133   299   299 E SMD     : DCD ON
,06-30 10:50:46.783   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:50:47.873   752  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:50:47.883   752  1590 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:50:47.883   752  1590 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:50:47.883   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:50:47.883   752   752 I MotionRecognitionService: Plugged
,06-30 10:50:47.883   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:50:47.883  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:50:47.893  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:50:47.893  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:50:47.893  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:47.893   752  1590 D BatteryService: stay LED for fully charged
06-30 10:50:47.893  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:47.893  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:50:47.903  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:50:47.903  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:48.553   752  1338 E Watchdog: !@Sync 34
,06-30 10:50:49.143   299   299 E SMD     : DCD ON
,06-30 10:50:52.143   299   299 E SMD     : DCD ON
,06-30 10:50:55.143   299   299 E SMD     : DCD ON
,06-30 10:50:56.853   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:50:57.933   752  1691 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:50:57.943   752  1691 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:50:57.943   752  1691 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:50:57.943   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:50:57.943   752   752 I MotionRecognitionService: Plugged
,06-30 10:50:57.943   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:50:57.953  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:50:57.953  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:50:57.953  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:50:57.953  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:50:57.953  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:50:57.953   752  1691 D BatteryService: stay LED for fully charged
,06-30 10:50:57.963  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:57.963  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:50:57.963  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:58.143   299   299 E SMD     : DCD ON
,06-30 10:51:01.143   299   299 E SMD     : DCD ON
,06-30 10:51:04.143   299   299 E SMD     : DCD ON
,06-30 10:51:06.893   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:51:07.143   299   299 E SMD     : DCD ON
,06-30 10:51:07.993   752  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:51:08.003   752  1643 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:51:08.003   752  1643 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:51:08.003   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:51:08.003   752   752 I MotionRecognitionService: Plugged
,06-30 10:51:08.003   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:51:08.013  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:51:08.013  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:51:08.013  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:51:08.013  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:51:08.013  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:08.013   752  1643 D BatteryService: stay LED for fully charged
,06-30 10:51:08.023  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:51:08.023  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:08.023  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:51:10.143   299   299 E SMD     : DCD ON
,06-30 10:51:13.143   299   299 E SMD     : DCD ON
,06-30 10:51:16.143   299   299 E SMD     : DCD ON
,06-30 10:51:16.983   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:51:18.053   752  1691 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:51:18.563   752  1338 E Watchdog: !@Sync 35
,06-30 10:51:19.143   299   299 E SMD     : DCD ON
,06-30 10:51:22.143   299   299 E SMD     : DCD ON
,06-30 10:51:25.153   299   299 E SMD     : DCD ON
,06-30 10:51:27.033   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:51:28.113   752  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:51:28.113   752  1144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:51:28.123   752  1144 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:51:28.123   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:51:28.123   752   752 I MotionRecognitionService: Plugged
,06-30 10:51:28.123  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:51:28.123   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:51:28.123  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:51:28.133  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:51:28.133  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:51:28.133  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:51:28.133   752  1144 D BatteryService: stay LED for fully charged
,06-30 10:51:28.133  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:28.143  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:51:28.143  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:28.153   299   299 E SMD     : DCD ON
,06-30 10:51:31.153   299   299 E SMD     : DCD ON
,06-30 10:51:34.153   299   299 E SMD     : DCD ON
,06-30 10:51:37.083   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:51:37.153   299   299 E SMD     : DCD ON
,06-30 10:51:38.173   752   777 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:51:38.183   752   777 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:51:38.183   752   777 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:51:38.183   752   777 D BatteryService: stay LED for fully charged
06-30 10:51:38.183   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:51:38.183   752   752 I MotionRecognitionService: Plugged
,06-30 10:51:38.183   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:51:38.193  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:51:38.193  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:51:38.193  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:51:38.193  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:38.193  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:51:38.203  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
06-30 10:51:38.203  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:38.203  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:40.153   299   299 E SMD     : DCD ON
,06-30 10:51:41.483   752  1049 I PowerManagerService: [PWL] Off : 1050s ago
,06-30 10:51:43.153   299   299 E SMD     : DCD ON
,06-30 10:51:46.153   299   299 E SMD     : DCD ON
,06-30 10:51:47.123   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 10:51:48.233   752  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:51:48.243   752  1144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:51:48.243   752  1144 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:51:48.243   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:51:48.243   752   752 I MotionRecognitionService: Plugged
,06-30 10:51:48.243   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:51:48.243  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:51:48.253  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:51:48.253  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:51:48.253  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:51:48.253  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:51:48.253  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:51:48.253   752  1144 D BatteryService: stay LED for fully charged
,06-30 10:51:48.263  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:48.263  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:48.563   752  1338 E Watchdog: !@Sync 36
,06-30 10:51:49.153   299   299 E SMD     : DCD ON
,06-30 10:51:52.153   299   299 E SMD     : DCD ON
,06-30 10:51:55.153   299   299 E SMD     : DCD ON
,06-30 10:51:57.173   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 450
,06-30 10:51:58.153   299   299 E SMD     : DCD ON
,06-30 10:51:58.293   752   777 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:51:58.293   752   777 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:51:58.293   752   777 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:51:58.303   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:51:58.303   752   752 I MotionRecognitionService: Plugged
,06-30 10:51:58.303   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:51:58.303  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:51:58.313  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:51:58.313  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:51:58.313  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:51:58.313  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:51:58.313  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:58.313   752   777 D BatteryService: stay LED for fully charged
06-30 10:51:58.313  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:58.323  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:01.153   299   299 E SMD     : DCD ON
,06-30 10:52:04.163   299   299 E SMD     : DCD ON
,06-30 10:52:07.163   299   299 E SMD     : DCD ON
,06-30 10:52:07.223   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 450
,06-30 10:52:08.353   752  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:52:10.163   299   299 E SMD     : DCD ON
,06-30 10:52:13.163   299   299 E SMD     : DCD ON
,06-30 10:52:16.163   299   299 E SMD     : DCD ON
,06-30 10:52:17.263   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 450
,06-30 10:52:18.413   752  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:52:18.563   752  1338 E Watchdog: !@Sync 37
,06-30 10:52:19.163   299   299 E SMD     : DCD ON
,06-30 10:52:22.163   299   299 E SMD     : DCD ON
,06-30 10:52:25.163   299   299 E SMD     : DCD ON
,06-30 10:52:27.313   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 450
,06-30 10:52:28.163   299   299 E SMD     : DCD ON
,06-30 10:52:28.473   752  1550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:52:28.473   752  1550 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:52:28.473   752  1550 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:52:28.483   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:52:28.483   752   752 I MotionRecognitionService: Plugged
,06-30 10:52:28.483   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:52:28.483  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:52:28.493  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:52:28.493  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:52:28.493  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:52:28.493  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:52:28.493  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:28.493   752  1550 D BatteryService: stay LED for fully charged
06-30 10:52:28.493  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:28.503  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:31.163   299   299 E SMD     : DCD ON
,06-30 10:52:34.163   299   299 E SMD     : DCD ON
,06-30 10:52:37.163   299   299 E SMD     : DCD ON
,06-30 10:52:37.363   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 450
,06-30 10:52:40.163   299   299 E SMD     : DCD ON
,06-30 10:52:40.933   752  1113 V AlarmManager: waitForAlarm result :4
,06-30 10:52:40.983   752  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:52:40.993  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 10:52:40.993  1197  1197 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:52:41.003  1197  1197 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,06-30 10:52:41.003  1197  1197 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 10:52:41.013   752   752 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,06-30 10:52:41.013   752   752 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,06-30 10:52:41.023   752   752 D SensorManager: registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,06-30 10:52:41.073  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 10:52:41.093   752   777 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:52:41.093  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 10:52:41.103   752   777 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 10:52:41.103   752   777 D ActivityManager: caller:android.app.ApplicationThreadProxy@c24e85, r.packageName :com.google.android.gms
,06-30 10:52:41.123  1758  7758 I EventLogService: Aggregate from 1467275729901 (log), 1467274960867 (data)
,06-30 10:52:41.133   752  1441 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 10:52:41.133   752  1441 D ActivityManager: caller:android.app.ApplicationThreadProxy@1ab1b4a6, r.packageName :com.google.android.gms
,06-30 10:52:41.193   752  1742 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:52:41.383   752  1093 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,06-30 10:52:41.383   752  1093 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,06-30 10:52:41.393   752  1093 D SensorManager: unregisterListener ::   
06-30 10:52:41.393   752  1093 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,06-30 10:52:43.173   299   299 E SMD     : DCD ON
,06-30 10:52:46.073  1583  6990 D GCM     : Message class com.google.f.a.a.i
,06-30 10:52:46.083   752  1377 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:52:46.083   752  1474 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 10:52:46.173   299   299 E SMD     : DCD ON
,06-30 10:52:47.413   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 295, CUR = 450
,06-30 10:52:48.573   752  1338 E Watchdog: !@Sync 38
,06-30 10:52:49.173   299   299 E SMD     : DCD ON
,06-30 10:52:51.043   752  1441 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:52:51.053   752  1441 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:52:51.053   752  1441 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:52:51.053   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:52:51.063  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:52:51.063  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:52:51.063   752   752 I MotionRecognitionService: Plugged
06-30 10:52:51.063   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:52:51.073  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:52:51.073  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:52:51.073  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:52:51.073  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:52:51.073  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:51.073   752  1441 D BatteryService: stay LED for fully charged
,06-30 10:52:51.083  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:52.173   299   299 E SMD     : DCD ON
,06-30 10:52:55.173   299   299 E SMD     : DCD ON
,06-30 10:52:57.483   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 295, CUR = 450
,06-30 10:52:58.173   299   299 E SMD     : DCD ON
,06-30 10:52:59.993   752  1113 V AlarmManager: waitForAlarm result :8
,06-30 10:53:01.113   752  1691 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:53:01.113   752  1691 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:53:01.123   752  1691 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:53:01.123   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:53:01.123   752   752 I MotionRecognitionService: Plugged
,06-30 10:53:01.123   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:53:01.123  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:53:01.133  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:53:01.133  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:53:01.133  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:01.133  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:53:01.133  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
06-30 10:53:01.133   752  1691 D BatteryService: stay LED for fully charged
,06-30 10:53:01.133  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:01.143  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:01.173   299   299 E SMD     : DCD ON
,06-30 10:53:04.173   299   299 E SMD     : DCD ON
,06-30 10:53:07.173   299   299 E SMD     : DCD ON
,06-30 10:53:07.523   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 295, CUR = 450
,06-30 10:53:10.173   299   299 E SMD     : DCD ON
,06-30 10:53:11.173   752  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:53:13.173   299   299 E SMD     : DCD ON
,06-30 10:53:16.173   299   299 E SMD     : DCD ON
,06-30 10:53:17.623   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 450
,06-30 10:53:18.573   752  1338 E Watchdog: !@Sync 39
,06-30 10:53:19.173   299   299 E SMD     : DCD ON
,06-30 10:53:21.233   752  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:53:22.173   299   299 E SMD     : DCD ON
,06-30 10:53:25.183   299   299 E SMD     : DCD ON
,06-30 10:53:26.483   752  1049 I PowerManagerService: [PWL] Off : 1155s ago
,06-30 10:53:27.673   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450
,06-30 10:53:28.183   299   299 E SMD     : DCD ON
,06-30 10:53:31.183   299   299 E SMD     : DCD ON
,06-30 10:53:31.293   752  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:53:31.293   752  1144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:53:31.303   752  1144 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:53:31.303   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:53:31.303   752   752 I MotionRecognitionService: Plugged
,06-30 10:53:31.303   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:53:31.303  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:53:31.313  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:53:31.313  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:53:31.313  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:53:31.313  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:53:31.313   752  1144 D BatteryService: stay LED for fully charged
,06-30 10:53:31.313  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:31.323  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:31.323  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:53:34.183   299   299 E SMD     : DCD ON
,06-30 10:53:37.183   299   299 E SMD     : DCD ON
,06-30 10:53:37.723   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450
,06-30 10:53:40.183   299   299 E SMD     : DCD ON
,06-30 10:53:41.353   752  1474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:53:43.183   299   299 E SMD     : DCD ON
,06-30 10:53:45.653   752  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 10:53:45.663   752  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:53:45.663   752  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:53:46.183   299   299 E SMD     : DCD ON
,06-30 10:53:46.363   752   994 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 10:53:46.433   752  1125 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,06-30 10:53:46.433   752  1125 I ApplicationUsage: Updating Usage Statistics in DB @ 1467276826437
,06-30 10:53:46.433   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 10:53:46.443   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.443   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 10:53:46.443   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
06-30 10:53:46.443   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
06-30 10:53:46.443   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,06-30 10:53:46.443   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.443   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.443   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.443   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:53:46.443   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.443   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.443   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 10:53:46.443   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
06-30 10:53:46.443   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
06-30 10:53:46.443   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,06-30 10:53:46.453   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 10:53:46.453   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.453   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.453   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:53:46.453   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.453   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.453   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 10:53:46.453   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
06-30 10:53:46.453   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
06-30 10:53:46.453   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
06-30 10:53:46.453   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 10:53:46.453   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.453   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.453   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.453   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 10:53:46.453   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.453   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.453   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.453   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 10:53:46.463   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.463   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.463   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.463   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.463   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:53:46.463   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.463   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.463   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.463   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 10:53:46.463   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 10:53:46.463   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.463   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 10:53:46.463   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.463   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.463   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:53:46.463   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.463   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.463   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 10:53:46.463   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.463   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.463   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 10:53:46.463   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.463   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.463   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 10:53:46.463   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.463   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.463   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.473   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 10:53:46.473   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 10:53:46.473   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.473   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.473   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 10:53:46.473   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.473   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.473   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:53:46.473   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.473   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.473   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.473   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.473   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 10:53:46.473   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.473   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.473   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.473   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 10:53:46.473   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.473   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.473   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.473   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 10:53:46.473   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.473   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.473   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 10:53:46.473   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.483   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.483   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 10:53:46.483   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.483   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.483   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.483   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.483   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.483   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 10:53:46.483   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.483   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.483   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 10:53:46.483   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.483   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.483   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 10:53:46.483   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.483   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.483   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.483   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 10:53:46.483   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.483   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.483   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 10:53:46.483   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.483   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.483   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 10:53:46.483   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.483   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.483   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 10:53:46.483   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.483   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.483   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 10:53:46.483   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.493   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.493   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:53:46.493   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 10:53:46.493   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.493   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.493   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 10:53:46.493   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.493   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.493   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 10:53:46.493   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.493   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.493   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:53:46.493   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.493   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.493   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.493   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.493   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
06-30 10:53:46.493   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 10:53:46.493   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.493   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 10:53:46.493   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 10:53:46.493   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.493   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 10:53:46.493   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.503   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 10:53:46.503   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.503   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.503   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 10:53:46.503   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.503   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.503   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.503   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:53:46.503   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.503   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.503   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.503   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.503   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 10:53:46.503   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 10:53:46.503   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.503   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.503   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 10:53:46.503   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.503   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.503   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.503   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.503   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.503   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 10:53:46.503   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.503   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.503   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 10:53:46.503   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.503   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.503   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 10:53:46.503   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.513   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 10:53:46.513   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.513   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.513   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 10:53:46.513   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.513   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.513   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 10:53:46.513   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.513   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.513   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.513   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.513   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.513   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 10:53:46.513   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.513   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.513   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 10:53:46.513   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.513   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.513   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 10:53:46.513   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.513   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.513   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.513   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 10:53:46.523   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.523   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.523   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 10:53:46.523   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.523   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.523   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 10:53:46.523   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.523   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.523   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 10:53:46.523   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.523   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.523   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 10:53:46.523   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.523   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.523   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:53:46.523   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 10:53:46.523   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.523   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.523   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 10:53:46.523   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.523   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.523   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 10:53:46.523   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.523   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.523   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:53:46.523   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.523   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.523   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.523   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.523   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 10:53:46.533   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.533   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.533   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 10:53:46.533   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 10:53:46.533   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.533   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 10:53:46.533   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.533   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.533   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 10:53:46.533   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.533   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.533   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 10:53:46.533   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.533   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.533   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:53:46.533   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.533   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.533   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.533   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.533   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 10:53:46.533   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 10:53:46.533   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.533   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.533   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 10:53:46.533   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:53:46.543   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.543   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference,
06-30 10:53:46.543   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.543   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.543   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 10:53:46.543   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.543   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.543   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.543   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 10:53:46.543   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.543   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.543   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.543   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 10:53:46.543   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.543   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.543   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 10:53:46.543   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.543   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.543   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.543   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:53:46.543   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.543   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.543   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.543   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.543   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 10:53:46.543   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.543   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.543   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.543   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 10:53:46.543   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.543   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.543   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.553   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 10:53:46.553   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.553   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.553   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 10:53:46.553   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.553   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.553   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.553   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:53:46.553   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.553   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.553   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 10:53:46.553   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.553   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.553   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.553   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 10:53:46.553   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.553   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.553   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:53:46.553   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.553   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.553   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.553   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 10:53:46.553   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 10:53:46.553   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.553   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.553   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.553   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 10:53:46.553   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.553   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.553   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.563   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.563   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 10:53:46.563   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.563   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.563   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.563   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 10:53:46.563   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.563   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.563   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.563   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.563   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.563   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.563   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.563   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.563   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.563   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
06-30 10:53:46.573   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.573   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.573   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.573   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.573   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.573   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.573   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.573   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.573   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.573   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.573   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.573   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.573   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.573   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.573   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.573   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.573   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.573   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.573   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.573   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.573   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.573   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.573   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.573   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.573   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.573   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.573   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.573   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.573   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.583   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.583   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.583   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.583   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.583   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.583   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.583   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.583   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.583   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.583   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.583   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.583   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.583   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.583   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.583   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.583   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.583   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.583   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.583   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.593   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.593   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.593   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.593   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.593   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.593   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.593   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.593   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.593   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.593   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.593   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.593   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.593   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.593   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.593   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.593   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.593   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.593   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.603   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.603   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.603   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.603   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.603   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.603   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.603   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.603   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.603   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.603   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.603   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.603   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.603   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.603   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.603   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.603   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.603   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.603   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.603   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.613   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.613   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.613   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.613   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.613   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.613   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.613   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.613   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.613   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.613   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.613   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.613   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.613   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.613   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.613   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.613   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.613   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.613   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.613   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.613   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.613   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.613   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.613   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.623   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.623   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.623   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.623   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.623   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.623   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.623   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.623   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.623   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.623   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.623   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.623   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.623   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.623   752  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 10:53:46.623   752  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 10:53:46.623   752  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 10:53:46.623   752  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:53:46.623   752  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:53:46.623   752  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:53:46.623   752  1125 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1467276826630
,06-30 10:53:47.813   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 294, CUR = 450
,06-30 10:53:48.403   752  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 10:53:48.403   752  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:53:48.413   752  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:53:48.413   752  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:53:48.573   752  1338 E Watchdog: !@Sync 40
,06-30 10:53:49.183   299   299 E SMD     : DCD ON
,06-30 10:53:51.413   752  1463 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:53:51.423   752  1463 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:53:51.423   752  1463 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:53:51.423   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:53:51.423   752   752 I MotionRecognitionService: Plugged
,06-30 10:53:51.423  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:53:51.433  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:53:51.433   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:53:51.433  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:53:51.433   752  1463 D BatteryService: stay LED for fully charged
,06-30 10:53:51.433  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:51.433  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:53:51.443  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:53:51.443  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:51.443  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:52.183   299   299 E SMD     : DCD ON
,06-30 10:53:55.183   299   299 E SMD     : DCD ON
,06-30 10:53:57.863   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 295, CUR = 450
,06-30 10:53:58.183   299   299 E SMD     : DCD ON
,06-30 10:54:01.193   299   299 E SMD     : DCD ON
,06-30 10:54:01.473   752  1742 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:54:01.483   752  1742 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 10:54:01.483   752  1742 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:54:01.483   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:54:01.483   752   752 I MotionRecognitionService: Plugged
,06-30 10:54:01.483   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:54:01.483  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:54:01.483  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:54:01.493  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:54:01.493   752  1742 D BatteryService: stay LED for fully charged
,06-30 10:54:01.493  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:01.493  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:01.503  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:01.503  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:54:01.503  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:54:04.193   299   299 E SMD     : DCD ON
,06-30 10:54:07.193   299   299 E SMD     : DCD ON
,06-30 10:54:07.903   752  3003 D SSRM:n  : SIOP:: AP = 300, PST = 296, CUR = 450
,06-30 10:54:10.193   299   299 E SMD     : DCD ON
,06-30 10:54:11.543   752  1463 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:54:11.543   752  1463 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:54:11.543   752  1463 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:54:11.553   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:54:11.553  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:54:11.553  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:54:11.563   752   752 I MotionRecognitionService: Plugged
,06-30 10:54:11.563   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:54:11.563   752  1463 D BatteryService: stay LED for fully charged
,06-30 10:54:11.573  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:54:11.583  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:11.583  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:54:11.583  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:54:11.593  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:11.593  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:13.193   299   299 E SMD     : DCD ON
,06-30 10:54:16.193   299   299 E SMD     : DCD ON
,06-30 10:54:17.953   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 450
,06-30 10:54:18.583   752  1338 E Watchdog: !@Sync 41
,06-30 10:54:19.193   299   299 E SMD     : DCD ON
,06-30 10:54:21.603   752  1742 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:54:21.603   752  1742 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:54:21.603   752  1742 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:54:21.613   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:54:21.613  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:54:21.623  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:54:21.623   752   752 I MotionRecognitionService: Plugged
,06-30 10:54:21.623   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:54:21.623   752  1742 D BatteryService: stay LED for fully charged
,06-30 10:54:21.633  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:54:21.643  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:54:21.643  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:54:21.653  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:21.663  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:21.663  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:22.193   299   299 E SMD     : DCD ON
,06-30 10:54:25.193   299   299 E SMD     : DCD ON
,06-30 10:54:28.003   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 450
,06-30 10:54:28.193   299   299 E SMD     : DCD ON
,06-30 10:54:31.193   299   299 E SMD     : DCD ON
,06-30 10:54:31.653   752  1463 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:54:31.663   752  1463 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:54:31.663   752  1463 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:54:31.663   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:54:31.673  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:54:31.673  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:54:31.673   752   752 I MotionRecognitionService: Plugged
,06-30 10:54:31.683  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:54:31.683   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:54:31.683   752  1463 D BatteryService: stay LED for fully charged
,06-30 10:54:31.693  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:54:31.693  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:54:31.703  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:31.703  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:31.703  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:34.193   299   299 E SMD     : DCD ON
,06-30 10:54:37.203   299   299 E SMD     : DCD ON
,06-30 10:54:38.053   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 450
,06-30 10:54:40.203   299   299 E SMD     : DCD ON
,06-30 10:54:41.723   752  1742 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:54:43.203   299   299 E SMD     : DCD ON
,06-30 10:54:46.203   299   299 E SMD     : DCD ON
,06-30 10:54:48.093   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450
,06-30 10:54:48.583   752  1338 E Watchdog: !@Sync 42
,06-30 10:54:49.203   299   299 E SMD     : DCD ON
,06-30 10:54:51.783   752  1469 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:54:52.203   299   299 E SMD     : DCD ON
,06-30 10:54:55.203   299   299 E SMD     : DCD ON
,06-30 10:54:58.143   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450
,06-30 10:54:58.203   299   299 E SMD     : DCD ON
,06-30 10:55:01.203   299   299 E SMD     : DCD ON
,06-30 10:55:01.843   752  1550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:55:01.843   752  1550 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:55:01.853   752  1550 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:55:01.853   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:55:01.863  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:55:01.863  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:55:01.863  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:55:01.863   752   752 I MotionRecognitionService: Plugged
,06-30 10:55:01.873   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:55:01.873   752  1550 D BatteryService: stay LED for fully charged
,06-30 10:55:01.873  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:55:01.873  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:55:01.883  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:01.883  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:55:01.883  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:04.203   299   299 E SMD     : DCD ON
,06-30 10:55:07.203   299   299 E SMD     : DCD ON
,06-30 10:55:08.193   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450
,06-30 10:55:10.203   299   299 E SMD     : DCD ON
,06-30 10:55:11.903   752  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:55:11.913   752  1482 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:55:11.913   752  1482 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:55:11.913   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:55:11.923   752   752 I MotionRecognitionService: Plugged
,06-30 10:55:11.923  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:55:11.923  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:55:11.933  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:55:11.933   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:55:11.933   752  1482 D BatteryService: stay LED for fully charged
,06-30 10:55:11.933  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:11.933  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:11.933  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:11.933  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:55:11.943  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:55:13.203   299   299 E SMD     : DCD ON
,06-30 10:55:16.213   299   299 E SMD     : DCD ON
,06-30 10:55:16.483   752  1049 I PowerManagerService: [PWL] Off : 1265s ago
,06-30 10:55:18.243   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450
,06-30 10:55:18.583   752  1338 E Watchdog: !@Sync 43
,06-30 10:55:19.213   299   299 E SMD     : DCD ON
,06-30 10:55:21.963   752  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:55:21.963   752  1643 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:55:21.963   752  1643 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:55:21.963   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:55:21.973  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:55:21.973  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:55:21.973   752   752 I MotionRecognitionService: Plugged
,06-30 10:55:21.983   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:55:21.983   752  1643 D BatteryService: stay LED for fully charged
,06-30 10:55:21.983  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:55:21.993  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:55:21.993  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:55:22.003  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:22.003  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:22.003  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:22.213   299   299 E SMD     : DCD ON
,06-30 10:55:25.213   299   299 E SMD     : DCD ON
,06-30 10:55:28.213   299   299 E SMD     : DCD ON
,06-30 10:55:28.283   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450
,06-30 10:55:31.213   299   299 E SMD     : DCD ON
,06-30 10:55:32.023   752   777 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:55:32.023   752   777 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:55:32.023   752   777 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:55:32.033   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:55:32.033  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:55:32.033  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:55:32.043   752   752 I MotionRecognitionService: Plugged
,06-30 10:55:32.043   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:55:32.043   752   777 D BatteryService: stay LED for fully charged
,06-30 10:55:32.053  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:55:32.063  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:32.063  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:32.063  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:55:32.073  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:55:32.073  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:34.213   299   299 E SMD     : DCD ON
,06-30 10:55:37.213   299   299 E SMD     : DCD ON
,06-30 10:55:38.353   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450
,06-30 10:55:40.213   299   299 E SMD     : DCD ON
,06-30 10:55:42.083   752  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:55:42.083   752  1643 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:55:42.083   752  1643 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:55:42.083   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:55:42.093  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:55:42.093   752   752 I MotionRecognitionService: Plugged
,06-30 10:55:42.093  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:55:42.103   752   752 I MotionRecognitionService: setPowerConnected  = true
06-30 10:55:42.103   752  1643 D BatteryService: stay LED for fully charged
,06-30 10:55:42.103  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:55:42.113  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:42.113  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:42.113  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:55:42.113  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:55:42.123  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:43.213   299   299 E SMD     : DCD ON
,06-30 10:55:46.213   299   299 E SMD     : DCD ON
,06-30 10:55:48.393   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:55:48.583   752  1338 E Watchdog: !@Sync 44
,06-30 10:55:49.213   299   299 E SMD     : DCD ON
,06-30 10:55:52.143   752   777 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:55:52.143   752   777 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:55:52.143   752   777 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:55:52.143   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:55:52.153  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:55:52.153  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:55:52.163   752   752 I MotionRecognitionService: Plugged
,06-30 10:55:52.163   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:55:52.163   752   777 D BatteryService: stay LED for fully charged
,06-30 10:55:52.163  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:55:52.173  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:55:52.173  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:55:52.183  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:52.183  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:55:52.183  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:52.213   299   299 E SMD     : DCD ON
,06-30 10:55:55.223   299   299 E SMD     : DCD ON
,06-30 10:55:58.223   299   299 E SMD     : DCD ON
,06-30 10:55:58.443   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:56:01.223   299   299 E SMD     : DCD ON
,06-30 10:56:02.203   752  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:56:02.203   752  1643 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:56:02.213   752  1643 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:56:02.213   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:56:02.223  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:56:02.223  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:56:02.223  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:56:02.223   752   752 I MotionRecognitionService: Plugged
06-30 10:56:02.223   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:56:02.233   752  1643 D BatteryService: stay LED for fully charged
,06-30 10:56:02.233  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:56:02.233  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:56:02.243  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:02.243  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:56:02.243  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:04.223   299   299 E SMD     : DCD ON
,06-30 10:56:07.223   299   299 E SMD     : DCD ON
,06-30 10:56:08.493   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:56:10.223   299   299 E SMD     : DCD ON
,06-30 10:56:12.253   752   777 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:56:13.223   299   299 E SMD     : DCD ON
,06-30 10:56:16.223   299   299 E SMD     : DCD ON
,06-30 10:56:18.583   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:56:18.593   752  1338 E Watchdog: !@Sync 45
,06-30 10:56:19.223   299   299 E SMD     : DCD ON
,06-30 10:56:22.233   299   299 E SMD     : DCD ON
,06-30 10:56:22.323   752   776 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:56:22.323   752   776 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:56:22.323   752   776 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:56:22.323   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:56:22.333  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:56:22.333  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:56:22.333   752   752 I MotionRecognitionService: Plugged
,06-30 10:56:22.343   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:56:22.343   752   776 D BatteryService: stay LED for fully charged
,06-30 10:56:22.353  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:56:22.363  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:22.363  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:22.363  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:56:22.363  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:56:22.383  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:25.233   299   299 E SMD     : DCD ON
,06-30 10:56:28.233   299   299 E SMD     : DCD ON
,06-30 10:56:28.653   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:56:31.233   299   299 E SMD     : DCD ON
,06-30 10:56:32.383   752  1474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:56:32.383   752  1474 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:56:32.383   752  1474 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:56:32.393   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:56:32.393  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:56:32.403  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:56:32.403   752   752 I MotionRecognitionService: Plugged
,06-30 10:56:32.403   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:56:32.403   752  1474 D BatteryService: stay LED for fully charged
,06-30 10:56:32.413  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:56:32.423  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:32.423  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:56:32.423  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:56:32.443  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:32.443  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:34.233   299   299 E SMD     : DCD ON
,06-30 10:56:37.233   299   299 E SMD     : DCD ON
,06-30 10:56:38.693   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:56:40.233   299   299 E SMD     : DCD ON
,06-30 10:56:42.443   752   776 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:56:42.443   752   776 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:56:42.443   752   776 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:56:42.453   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:56:42.453  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:56:42.463  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:56:42.463   752   752 I MotionRecognitionService: Plugged
,06-30 10:56:42.463   752   752 I MotionRecognitionService: setPowerConnected  = true
06-30 10:56:42.463   752   776 D BatteryService: stay LED for fully charged
,06-30 10:56:42.473  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:56:42.483  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:42.483  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:56:42.483  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:56:42.493  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:42.493  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:43.233   299   299 E SMD     : DCD ON
,06-30 10:56:46.233   299   299 E SMD     : DCD ON
,06-30 10:56:48.593   752  1338 E Watchdog: !@Sync 46
,06-30 10:56:48.743   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:56:49.233   299   299 E SMD     : DCD ON
,06-30 10:56:52.233   299   299 E SMD     : DCD ON
,06-30 10:56:52.503   752  1474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:56:52.503   752  1474 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:56:52.503   752  1474 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:56:52.503   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:56:52.513  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:56:52.513  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:56:52.513   752   752 I MotionRecognitionService: Plugged
,06-30 10:56:52.523   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:56:52.523   752  1474 D BatteryService: stay LED for fully charged
,06-30 10:56:52.523  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:56:52.533  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:52.533  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:56:52.533  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:56:52.543  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:52.543  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:55.233   299   299 E SMD     : DCD ON
,06-30 10:56:58.233   299   299 E SMD     : DCD ON
,06-30 10:56:58.793   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:57:01.243   299   299 E SMD     : DCD ON
,06-30 10:57:02.563   752   776 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:57:02.573   752   776 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:57:02.573   752   776 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:57:02.573   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:57:02.583   752   752 I MotionRecognitionService: Plugged
,06-30 10:57:02.583  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:57:02.583  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:57:02.583  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:57:02.593  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:57:02.593  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:57:02.593   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:57:02.593  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:02.593  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:57:02.593  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:02.593   752   776 D BatteryService: stay LED for fully charged
,06-30 10:57:04.243   299   299 E SMD     : DCD ON
,06-30 10:57:07.243   299   299 E SMD     : DCD ON
,06-30 10:57:08.833   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:57:10.243   299   299 E SMD     : DCD ON
,06-30 10:57:11.483   752  1049 I PowerManagerService: [PWL] Off : 1380s ago
,06-30 10:57:12.623   752  1975 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:57:12.623   752  1975 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:57:12.623   752  1975 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:57:12.623   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:57:12.633  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:57:12.633  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:57:12.643   752   752 I MotionRecognitionService: Plugged
,06-30 10:57:12.643   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:57:12.643   752  1975 D BatteryService: stay LED for fully charged
,06-30 10:57:12.643  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:57:12.653  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:57:12.653  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:57:12.663  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:12.663  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:57:12.663  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:13.243   299   299 E SMD     : DCD ON
,06-30 10:57:16.243   299   299 E SMD     : DCD ON
,06-30 10:57:18.593   752  1338 E Watchdog: !@Sync 47
,06-30 10:57:18.883   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:57:19.243   299   299 E SMD     : DCD ON
,06-30 10:57:22.243   299   299 E SMD     : DCD ON
,06-30 10:57:22.683   752   776 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:57:22.683   752   776 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:57:22.683   752   776 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:57:22.683   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:57:22.693  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:57:22.693  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:57:22.693   752   752 I MotionRecognitionService: Plugged
,06-30 10:57:22.693   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:57:22.703   752   776 D BatteryService: stay LED for fully charged
,06-30 10:57:22.703  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
06-30 10:57:22.713  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:57:22.713  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:57:22.713  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 10:57:22.713  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
06-30 10:57:22.713  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:25.243   299   299 E SMD     : DCD ON
,06-30 10:57:28.243   299   299 E SMD     : DCD ON
,06-30 10:57:28.933   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:57:31.243   299   299 E SMD     : DCD ON
,06-30 10:57:32.743   752  1975 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:57:32.743   752  1975 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:57:32.743   752  1975 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:57:32.753   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:57:32.753  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:57:32.763  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:57:32.763   752   752 I MotionRecognitionService: Plugged
,06-30 10:57:32.763   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:57:32.763   752  1975 D BatteryService: stay LED for fully charged
,06-30 10:57:32.773  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:57:32.783  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:32.783  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:57:32.783  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:57:32.803  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:32.803  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:34.243   299   299 E SMD     : DCD ON
,06-30 10:57:37.253   299   299 E SMD     : DCD ON
,06-30 10:57:38.983   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:57:40.253   299   299 E SMD     : DCD ON
,06-30 10:57:42.803   752   776 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:57:42.813   752   776 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:57:42.813   752   776 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:57:42.813   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:57:42.823   752   752 I MotionRecognitionService: Plugged
,06-30 10:57:42.823  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:57:42.823  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:57:42.823  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:57:42.833   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:57:42.833  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:42.833  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:42.833  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:57:42.833  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:57:42.833   752   776 D BatteryService: stay LED for fully charged
,06-30 10:57:42.833  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:43.253   299   299 E SMD     : DCD ON
,06-30 10:57:46.253   299   299 E SMD     : DCD ON
,06-30 10:57:48.603   752  1338 E Watchdog: !@Sync 48
,06-30 10:57:49.023   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:57:49.253   299   299 E SMD     : DCD ON
,06-30 10:57:52.253   299   299 E SMD     : DCD ON
,06-30 10:57:52.853   752  1975 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:57:52.863   752  1975 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:57:52.863   752  1975 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:57:52.863   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:57:52.873  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:57:52.873  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:57:52.883   752   752 I MotionRecognitionService: Plugged,
06-30 10:57:52.883   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:57:52.883   752  1975 D BatteryService: stay LED for fully charged
,06-30 10:57:52.883  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:57:52.893  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:57:52.893  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:57:52.903  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:52.903  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:57:52.903  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:55.253   299   299 E SMD     : DCD ON
,06-30 10:57:58.253   299   299 E SMD     : DCD ON
,06-30 10:57:59.073   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:58:01.253   299   299 E SMD     : DCD ON
,06-30 10:58:02.923   752  1550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:58:04.253   299   299 E SMD     : DCD ON
,06-30 10:58:07.253   299   299 E SMD     : DCD ON
,06-30 10:58:09.123   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:58:10.253   299   299 E SMD     : DCD ON
,06-30 10:58:12.983   752  1251 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:58:12.983   752  1251 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:58:12.983   752  1251 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:58:12.983   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:58:12.993  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:58:12.993  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:58:12.993   752   752 I MotionRecognitionService: Plugged
,06-30 10:58:13.003   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:58:13.013  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:58:13.013   752  1251 D BatteryService: stay LED for fully charged
,06-30 10:58:13.013  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:58:13.013  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:58:13.013  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:58:13.013  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:58:13.013  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:58:13.253   299   299 E SMD     : DCD ON
,06-30 10:58:16.263   299   299 E SMD     : DCD ON
,06-30 10:58:18.603   752  1338 E Watchdog: !@Sync 49
,06-30 10:58:19.173   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:58:19.263   299   299 E SMD     : DCD ON
,06-30 10:58:22.263   299   299 E SMD     : DCD ON
,06-30 10:58:23.043   752  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:58:25.263   299   299 E SMD     : DCD ON
,06-30 10:58:28.263   299   299 E SMD     : DCD ON
,06-30 10:58:29.213   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:58:31.263   299   299 E SMD     : DCD ON
,06-30 10:58:33.113   752  1441 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:58:33.113   752  1441 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 10:58:33.113   752  1441 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 10:58:33.113   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:58:33.123  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:58:33.123  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 10:58:33.123   752   752 I MotionRecognitionService: Plugged
06-30 10:58:33.123   752   752 I MotionRecognitionService: setPowerConnected  = true
,06-30 10:58:33.133  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 10:58:33.133  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
,06-30 10:58:33.133  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:58:33.133   752  1441 D BatteryService: stay LED for fully charged
06-30 10:58:33.133  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:58:33.133  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:58:33.133  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:58:34.263   299   299 E SMD     : DCD ON
,06-30 10:58:37.263   299   299 E SMD     : DCD ON
,06-30 10:58:39.263   752  3003 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450
,06-30 10:58:40.263   299   299 E SMD     : DCD ON
,TIME-OUT KILL (timeout was 1400000ms),06-30 10:58:43.143   752  1691 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:58:43.143   752  1691 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 10:58:43.143   752  1691 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 10:58:43.143   752  1691 D BatteryService: stay LED for fully charged
06-30 10:58:43.143   752   752 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:58:43.153  2940  2940 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 10:58:43.153  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:58:43.153  2940  6584 D HeadsetStateMachine: Disconnected process message: 10
06-30 10:58:43.153   752   752 I MotionRecognitionService: Plugged
06-30 10:58:43.163   752   752 I MotionRecognitionService: setPowerConnected  = true
06-30 10:58:43.163  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 10:58:43.163  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
06-30 10:58:43.173  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:58:43.173  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:58:43.173  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:58:43.223  7794  7794 D AndroidRuntime: 
06-30 10:58:43.223  7794  7794 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 10:58:43.233  7794  7794 D AndroidRuntime: CheckJNI is OFF
06-30 10:58:43.233  7794  7794 D AndroidRuntime: readGMSProperty: start
06-30 10:58:43.233  7794  7794 D AndroidRuntime: readGMSProperty: already setted!!
06-30 10:58:43.233  7794  7794 D AndroidRuntime: readGMSProperty: end
06-30 10:58:43.233  7794  7794 D AndroidRuntime: addProductProperty: start
06-30 10:58:43.263   299   299 E SMD     : DCD ON
06-30 10:58:43.373  7794  7794 E AffinityControl: AffinityControl: registerfunction enter
06-30 10:58:43.393  7794  7794 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 10:58:43.403   752  1144 D PackageManager: START PACKAGE DELETE: observer{175573652}
06-30 10:58:43.403   752  1144 D PackageManager: pkg{<packageName>}
06-30 10:58:43.403   752  1144 D PackageManager: user{0}
06-30 10:58:43.403   752  1144 D PackageManager: caller{2000}
06-30 10:58:43.403   752  1144 D PackageManager: flags{2}
06-30 10:58:43.403   752  1144 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
06-30 10:58:43.403   752  1144 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-30 10:58:43.403   752  1144 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-30 10:58:43.403   752  1144 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 10:58:43.403   752  1144 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 10:58:43.403   752  1065 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-30 10:58:43.403   752  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
06-30 10:58:43.403   752  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
06-30 10:58:43.403   752  1065 D ApplicationPolicy: getApplicationUninstallationEnabled
06-30 10:58:43.403   752  1065 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
06-30 10:58:43.403   752  1065 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
06-30 10:58:43.403   752   999 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
06-30 10:58:43.403   752   999 I ActivityManager: Killing 6441:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
06-30 10:58:43.413   752   999 I ActivityManager:   Force finishing activity ActivityRecord{58cefeb u0 com.test.thalitest/.MainActivity t21}
06-30 10:58:43.413   752   999 D FocusedStackFrame: Set to : 0
06-30 10:58:43.413   266  1841 I SurfaceFlinger: id=11 Removed NainActivit (6/8)
06-30 10:58:43.413   266   451 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
06-30 10:58:43.553   752  3003 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:58:43.563   752  1065 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
06-30 10:58:43.613  1619  1619 I art     : Explicit concurrent mark sweep GC freed 38107(2MB) AllocSpace objects, 7(148KB) LOS objects, 40% free, 19MB/33MB, paused 420us total 34.732ms
06-30 10:58:43.623  5346  5346 I art     : Explicit concurrent mark sweep GC freed 37570(2036KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 15MB/26MB, paused 457us total 27.656ms
06-30 10:58:43.623   752  1044 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
06-30 10:58:43.633   752  1122 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-30 10:58:43.633   752  3238 E libprocessgroup: failed to kill 1 processes for processgroup 6441
06-30 10:58:43.633  1493  1915 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-30 10:58:43.633  1719  1719 E SamsungIME: mOCRHelper is null
06-30 10:58:43.653  3974  3974 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
06-30 10:58:43.653  1418  1418 D RegisteredServicesCache: empty dynamic service
06-30 10:58:43.663  3974  3974 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1467277123664
06-30 10:58:43.663   752  1146 V NetworkStats: removeUidsLocked() for UIDs [10079]
06-30 10:58:43.663   752  1146 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 10:58:43.663   752  1146 V NetworkStats: performPollLocked(flags=0x3)
06-30 10:58:43.663   752  1146 D NetworkStatsFactory: UpdateStatsForKnox
06-30 10:58:43.663   752  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:58:43.663  3974  3974 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
06-30 10:58:43.663   752  1146 V NetworkStats: performPollLocked() took 4ms
06-30 10:58:43.663   752  1146 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 10:58:43.673  3974  3974 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
06-30 10:58:43.693   752  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 10:58:43.693   752  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 10:58:43.723   752  1550 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
06-30 10:58:43.723   752  1550 D SecContentProvider2: mCursor = null
06-30 10:58:43.763   752   752 I art     : Explicit concurrent mark sweep GC freed 33915(2MB) AllocSpace objects, 26(416KB) LOS objects, 30% free, 36MB/52MB, paused 1.650ms total 154.107ms
06-30 10:58:43.763   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
06-30 10:58:43.763   752  1065 I art     : WaitForGcToComplete blocked for 96.996ms for cause Explicit
06-30 10:58:43.773   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
06-30 10:58:43.773   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
06-30 10:58:43.783   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
06-30 10:58:43.793   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
06-30 10:58:43.793   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
06-30 10:58:43.803   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
06-30 10:58:43.803   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
06-30 10:58:43.813   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
06-30 10:58:43.823   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
06-30 10:58:43.823   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
06-30 10:58:43.823   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
06-30 10:58:43.833   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
06-30 10:58:43.843   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
06-30 10:58:43.843   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
06-30 10:58:43.843  3974  3974 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
06-30 10:58:43.843   752   752 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
06-30 10:58:43.843   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
06-30 10:58:43.853   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
06-30 10:58:43.853   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
06-30 10:58:43.853  3974  3974 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
06-30 10:58:43.863   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
06-30 10:58:43.863  7535  7535 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
06-30 10:58:43.863   752   776 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
06-30 10:58:43.863   752   776 D ActivityManager: caller:android.app.ApplicationThreadProxy@1fc37ccb, r.packageName :com.sec.esdk.elm
06-30 10:58:43.863  7535  7535 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
06-30 10:58:43.863   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
06-30 10:58:43.873  3516  3516 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
06-30 10:58:43.873  3516  3516 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 10:58:43.873  3516  3516 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
06-30 10:58:43.873  3516  3516 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
06-30 10:58:43.873  3516  3516 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
06-30 10:58:43.873  3516  3516 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
06-30 10:58:43.873  3516  3516 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
06-30 10:58:43.873  3516  3516 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:58:43.873  3516  3516 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 10:58:43.873  3516  3516 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 10:58:43.873   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
06-30 10:58:43.873  3516  3516 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:58:43.873  3516  3516 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:58:43.873  3516  3516 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 10:58:43.873  3516  3516 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 10:58:43.873   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
06-30 10:58:43.873  7535  7535 D elm:14491: ElmAgentService : onCreate()
06-30 10:58:43.873  7535  7822 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
06-30 10:58:43.873  7535  7822 D elm:14491: MainReceiver.listeningToPackageRemoved()
06-30 10:58:43.873  7535  7822 D elm:14491: MDMBridge.getInstance()
06-30 10:58:43.873  7535  7822 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
06-30 10:58:43.873   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
06-30 10:58:43.883  7535  7822 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
06-30 10:58:43.883   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
06-30 10:58:43.883  1583  1583 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
06-30 10:58:43.883  1583  1583 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
06-30 10:58:43.883   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
06-30 10:58:43.883   752  1251 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:58:43.883  7535  7535 D elm:14491: ElmAgentService : onDestroy().
06-30 10:58:43.893   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
06-30 10:58:43.903   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
06-30 10:58:43.903   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
06-30 10:58:43.903   752  1975 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 10:58:43.903   752  1975 D ActivityManager: caller:android.app.ApplicationThreadProxy@2e0eda2, r.packageName :com.google.android.gms
06-30 10:58:43.903   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
06-30 10:58:43.903   752   752 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
06-30 10:58:43.903  1758  7824 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
06-30 10:58:43.913  1758  1758 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
06-30 10:58:43.913  1758  1758 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
06-30 10:58:43.913  1758  1758 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-30 10:58:43.913  1758  1758 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
06-30 10:58:43.913   752   752 D RCPManagerService: PackageReceiver onReceive()
06-30 10:58:43.913   752   752 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
06-30 10:58:43.913   752  1482 D ActivityManager: caller:android.app.ApplicationThreadProxy@28fac68f, r.packageName :com.google.android.gms
06-30 10:58:43.913   752   752 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
06-30 10:58:43.913   752   752 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 10:58:43.913   752   752 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-30 10:58:43.913   752   752 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
06-30 10:58:43.913   752   752 V EnterpriseBillingPolicy: uID is 10079
06-30 10:58:43.913   752   752 V EnterpriseBillingPolicy: Removed Packageuid is0
06-30 10:58:43.913   752   752 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
06-30 10:58:43.913  1758  1758 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
06-30 10:58:43.913  1758  1758 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
06-30 10:58:43.913  1758  1758 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-30 10:58:43.913  1758  1758 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
06-30 10:58:43.913   752   752 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
06-30 10:58:43.923   752   752 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-30 10:58:43.923   752   752 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-30 10:58:43.923   752   752 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
06-30 10:58:43.923   752   752 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
06-30 10:58:43.923  1758  7824 D AccountUtils: Clearing selected account for com.test.thalitest
06-30 10:58:43.923   752  1179 D TaskPersister: removeObsoleteFile: deleting file=21_task.xml
06-30 10:58:43.923   752  3003 D SSRM:aY : MSG_TYPE_APP_REMOVED::
06-30 10:58:43.923   752   752 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
06-30 10:58:43.933   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
06-30 10:58:43.933   752  1065 I art     : Explicit concurrent mark sweep GC freed 10159(551KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 2.356ms total 166.496ms
06-30 10:58:43.943   752  1463 D ActivityManager: caller:android.app.ApplicationThreadProxy@10e73cab, r.packageName :com.google.android.gms
06-30 10:58:43.943   752  1975 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.service.health, hostingType: broadcast
06-30 10:58:43.943   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:58:43.943   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:58:43.943   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:58:43.943   752  1975 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:58:43.953   752   994 D EnterpriseDeviceManagerService: Package has changed for user 0
06-30 10:58:43.953   752   994 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
06-30 10:58:43.953   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
06-30 10:58:43.963   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:43.963   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
06-30 10:58:43.983   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
06-30 10:58:43.983  7828  7828 E Zygote  : MountEmulatedStorage()
06-30 10:58:43.983  7828  7828 E Zygote  : v2
06-30 10:58:43.983  7828  7828 I libpersona: KNOX_SDCARD checking this for 10021
06-30 10:58:43.983  7828  7828 I libpersona: KNOX_SDCARD not a persona
06-30 10:58:43.983   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:43.983   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
06-30 10:58:43.993   752  1975 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7828 uid=10021 gids={50021, 9997} abi=armeabi-v7a
06-30 10:58:43.993   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
06-30 10:58:43.993   752  1377 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:58:43.993   752  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@170f0995, r.packageName :com.google.android.gms
06-30 10:58:43.993   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:43.993  1758  7824 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
06-30 10:58:44.003   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
06-30 10:58:44.003   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:44.003   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
06-30 10:58:44.003   752  1065 D PackageManager: delete codoeFile: 
06-30 10:58:44.003   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:44.003   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:44.003   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
06-30 10:58:44.003   752  1065 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
06-30 10:58:44.003   752  1065 I AASA_removePackage: UID=10079 Target=com.test.thalitest
06-30 10:58:44.003   752  1065 D PackageManager: result of delete: 1{175573652}
06-30 10:58:44.013  7828  7828 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:58:44.013  7828  7828 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 10:58:44.013   752  1590 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
06-30 10:58:44.013  7828  7828 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 10:58:44.013   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:44.013   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
06-30 10:58:44.013  7794  7794 D AndroidRuntime: Shutting down VM
06-30 10:58:44.023   752  1251 D ActivityManager: caller:android.app.ApplicationThreadProxy@132fe502, r.packageName :com.google.android.gms
06-30 10:58:44.033   752  1065 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
06-30 10:58:44.033   752  1065 D PackageManager: userId{-1}
06-30 10:58:44.033   752  1065 D PackageManager: andCode{true}
06-30 10:58:44.033   752  1742 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:58:44.033   752  1742 D ActivityManager: caller:android.app.ApplicationThreadProxy@36088a49, r.packageName :com.google.android.gms
06-30 10:58:44.033   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
06-30 10:58:44.033   752  1065 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
06-30 10:58:44.043  7828  7828 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:58:44.043  7828  7828 D ActivityThread: Added TimaKeyStore provider
06-30 10:58:44.043   752  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:58:44.043   752  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:58:44.043   752  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:58:44.043   752  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 10:58:44.043  1758  7836 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
06-30 10:58:44.043  1758  7836 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
06-30 10:58:44.053  1758  7836 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
06-30 10:58:44.053   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
06-30 10:58:44.053  1758  7836 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
06-30 10:58:44.053   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
06-30 10:58:44.053   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:44.053   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
06-30 10:58:44.063   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
06-30 10:58:44.063  1758  7836 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
06-30 10:58:44.063  1758  7836 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
06-30 10:58:44.063  1758  7836 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
06-30 10:58:44.063   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
06-30 10:58:44.073   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:44.073   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:44.073   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
06-30 10:58:44.073  1758  7836 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
06-30 10:58:44.073  1758  7836 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
06-30 10:58:44.073   752   994 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 10:58:44.073   752   994 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:58:44.073   752   994 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 10:58:44.073  1758  7836 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
06-30 10:58:44.073   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:44.073   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
06-30 10:58:44.083   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:44.083   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
06-30 10:58:44.083  7847  7847 E Zygote  : MountEmulatedStorage()
06-30 10:58:44.083  7847  7847 E Zygote  : v2
06-30 10:58:44.083  7847  7847 I libpersona: KNOX_SDCARD checking this for 10007
06-30 10:58:44.083  7847  7847 I libpersona: KNOX_SDCARD not a persona
06-30 10:58:44.083   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:44.093   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
06-30 10:58:44.093   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:44.093   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
06-30 10:58:44.093   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
06-30 10:58:44.093   752  1065 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7847 uid=10007 gids={50007, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
06-30 10:58:44.093  7847  7847 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 10:58:44.093  7847  7847 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 10:58:44.093  7847  7847 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 10:58:44.103   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:44.103   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
06-30 10:58:44.113   752  1251 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:58:44.113   752  1251 D ActivityManager: caller:android.app.ApplicationThreadProxy@338b97b9, r.packageName :com.google.android.gms
06-30 10:58:44.113  1445  1445 D SurfaceWidgetView: destroyHardwareResources():316904490
06-30 10:58:44.113  1583  1583 I ConfigService: onCreate
06-30 10:58:44.123  1583  1583 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-30 10:58:44.123  7847  7847 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:58:44.123  7828  7828 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
06-30 10:58:44.123  7847  7847 D ActivityThread: Added TimaKeyStore provider
06-30 10:58:44.123  1445  1445 D Launcher: onRestart, Launcher: 737061280
06-30 10:58:44.123  1445  1445 D Launcher: onStart, Launcher: 737061280
06-30 10:58:44.123  1445  1445 D Launcher.HomeView: onStart
06-30 10:58:44.123  1445  1445 V ActivityThread: updateVisibility : ActivityRecord{30107fb5 token=android.os.BinderProxy@258e1f55 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
06-30 10:58:44.123  1816  1856 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
06-30 10:58:44.123  1816  1986 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
06-30 10:58:44.123  1816  1986 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
06-30 10:58:44.123  1758  1758 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
06-30 10:58:44.133  1583  1583 I ConfigService: onBind returning update interface
06-30 10:58:44.133  1583  1583 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-30 10:58:44.133  1583  1583 I ConfigService: onBind returning service broker
06-30 10:58:44.133   752  1975 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:58:44.133   752  1975 D ActivityManager: caller:android.app.ApplicationThreadProxy@3cff38d6, r.packageName :com.google.android.gms
06-30 10:58:44.143   266   266 I SurfaceFlinger: id=13 createSurf (1080x1920),1 flag=4, Mauncher
06-30 10:58:44.143   752  1251 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:58:44.143  7847  7847 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DefaultContainerService/DefaultContainerService.apk
06-30 10:58:44.143   752  1251 D ActivityManager: caller:android.app.ApplicationThreadProxy@4272244, r.packageName :com.google.android.gms
06-30 10:58:44.143   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:44.143   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
06-30 10:58:44.143   752   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
06-30 10:58:44.153   752   777 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:58:44.153   752   777 D ActivityManager: caller:android.app.ApplicationThreadProxy@98e0c62, r.packageName :com.google.android.gms
06-30 10:58:44.163  1758  7841 W BaseAppContext: Using Auth Proxy for data requests.
06-30 10:58:44.163  1758  1758 I ConfigFetchService: service connected
06-30 10:58:44.163  1758  7864 E SQLiteLog: (539) recovered 2 pages from /data/data/com.google.android.gms/databases/DocList.db-journal
06-30 10:58:44.173   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 10:58:44.173   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
06-30 10:58:44.173   752   994 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
06-30 10:58:44.173   752   777 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 10:58:44.173   752   777 D ActivityManager: caller:android.app.ApplicationThreadProxy@564e129, r.packageName :com.google.android.gms
06-30 10:58:44.173   752   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}

```
