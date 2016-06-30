#### Test 7578926851a8f91_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
06-30 12:54:33.137   306   306 E SMD     : DCD ON
,06-30 12:54:34.066  7226  7226 D AndroidRuntime: 
06-30 12:54:34.066  7226  7226 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 12:54:34.076  7226  7226 D AndroidRuntime: CheckJNI is OFF
06-30 12:54:34.076  7226  7226 D AndroidRuntime: readGMSProperty: start
06-30 12:54:34.076  7226  7226 D AndroidRuntime: readGMSProperty: already setted!!
06-30 12:54:34.076  7226  7226 D AndroidRuntime: readGMSProperty: end
06-30 12:54:34.076  7226  7226 D AndroidRuntime: addProductProperty: start
06-30 12:54:34.246  7226  7226 E AffinityControl: AffinityControl: registerfunction enter
06-30 12:54:34.266  7226  7226 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 12:54:34.276   903  1368 E PersonaManagerService: inState():  stateMachine is null !!
06-30 12:54:34.276   903  1368 I PersonaManagerService: PersonaId don't exist
06-30 12:54:34.276   903  1368 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
06-30 12:54:34.286   903  1368 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
06-30 12:54:34.286   903  1368 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 12:54:34.286   903  1368 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
06-30 12:54:34.286   903  1368 W ActivityManager: mDVFSHelper.acquire()
06-30 12:54:34.296   903  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:54:34.296   903  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:54:34.296   903  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:54:34.296   903  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:54:34.346   903  1368 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7241 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-30 12:54:34.356  7226  7226 D AndroidRuntime: Shutting down VM
06-30 12:54:34.366  7241  7241 E Zygote  : MountEmulatedStorage()
06-30 12:54:34.366  7241  7241 E Zygote  : v2
06-30 12:54:34.366  7241  7241 I libpersona: KNOX_SDCARD checking this for 10079
06-30 12:54:34.366  7241  7241 I libpersona: KNOX_SDCARD not a persona
06-30 12:54:34.376  7241  7241 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 12:54:34.376  7241  7241 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 12:54:34.376  7241  7241 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
06-30 12:54:34.396  7241  7241 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 12:54:34.396  7241  7241 D ActivityThread: Added TimaKeyStore provider
06-30 12:54:34.406  1459  1459 V ActivityThread: updateVisibility : ActivityRecord{2f134015 token=android.os.BinderProxy@1c326fb5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-30 12:54:34.406  1765  1779 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
06-30 12:54:34.426   903  3071 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 12:54:34.436  7241  7241 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
06-30 12:54:34.436  1459  1459 D SurfaceWidgetView: destroyHardwareResources():237694218
06-30 12:54:34.496   266  1948 I SurfaceFlinger: id=7 Removed Mauncher (6/8)
06-30 12:54:34.496   266   406 I SurfaceFlinger: id=7 Removed Mauncher (-2/8)
06-30 12:54:34.496  1459  1459 D Launcher: onTrimMemory. Level: 20
06-30 12:54:34.536  7241  7241 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
06-30 12:54:34.536  7241  7241 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
06-30 12:54:34.556  7241  7241 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3787-3790)
06-30 12:54:34.556  7241  7241 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 12:54:34.586  7241  7241 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {123a8bd}
,06-30 12:54:34.586  7241  7241 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 12:54:34.586  7241  7241 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 12:54:34.626  7241  7241 I BrowserStartupController: Initializing chromium process, singleProcess=true
,06-30 12:54:34.626  7241  7241 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 12:54:34.626  7241  7241 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-30 12:54:34.666  7241  7241 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,06-30 12:54:34.666  7241  7241 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
06-30 12:54:34.666  7241  7241 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,06-30 12:54:34.676  7241  7241 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
06-30 12:54:34.676  7241  7241 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
06-30 12:54:34.676  7241  7241 I Adreno-EGL: Build Date: 11/19/14 Wed
06-30 12:54:34.676  7241  7241 I Adreno-EGL: Local Branch: mybranch5813579
06-30 12:54:34.676  7241  7241 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
06-30 12:54:34.676  7241  7241 I Adreno-EGL: Local Patches: NONE
06-30 12:54:34.676  7241  7241 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,06-30 12:54:34.876  7241  7275 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,06-30 12:54:34.916   903   981 W ActivityManager: Activity pause timeout for ActivityRecord{1e149fbb u0 com.test.thalitest/.MainActivity t23}
,06-30 12:54:34.936  7241  7241 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 12:54:34.956  7241  7241 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 12:54:34.976  7241  7241 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,06-30 12:54:34.986  7241  7241 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 12:54:34.986  7241  7241 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 12:54:35.106  7241  7241 D Activity: performCreate Call secproduct feature valuefalse
06-30 12:54:35.106  7241  7241 D Activity: performCreate Call debug elastic valuetrue
,06-30 12:54:35.136  7241  7291 D OpenGLRenderer: Render dirty regions requested: true
,06-30 12:54:35.136   903  1451 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,06-30 12:54:35.136   903  1451 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-30 12:54:35.136   903  1451 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,06-30 12:54:35.136   903   903 D KnoxTimeoutHandler: handleActiveUserChange for user 0
06-30 12:54:35.136   903   903 D PersonaManagerService: getPersonasForUser(): returning null!
,06-30 12:54:35.146  7241  7241 V ActivityThread: updateVisibility : ActivityRecord{7edf64f token=android.os.BinderProxy@12975d29 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,06-30 12:54:35.156   266   266 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,06-30 12:54:35.176  7241  7291 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 12:54:35.176  7241  7291 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3cabcb8 ,&mEglDisplay = 1 , &mEglConfig = 8 
,06-30 12:54:35.176  7241  7291 D OpenGLRenderer: Enabling debug mode 0
,06-30 12:54:35.216  7241  7241 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@12975d29 time:294450
,06-30 12:54:35.236   903  1031 W ActivityManager: mDVFSHelper.release()
06-30 12:54:35.236   903  1031 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e149fbb u0 com.test.thalitest/.MainActivity t23} time:294470
,06-30 12:54:35.236   903  1031 D MultiWindowConverter: This application or window do not support multiwindow
,06-30 12:54:35.286  7241  7241 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7241
,06-30 12:54:35.416  7241  7241 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 12:54:35.566  7241  7294 D jxcore_app_log: JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1360019072
,06-30 12:54:35.586  7241  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 12:54:35.586  7241  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 12:54:35.586  7241  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 12:54:35.586  7241  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 12:54:35.586  7241  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 12:54:35.586  7241  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c5f113f added. We now have 1 listener(s)
,06-30 12:54:35.596  7241  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:2A:28:2D
,06-30 12:54:35.596  7241  7294 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,06-30 12:54:35.606  7241  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,06-30 12:54:35.606  7241  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 12:54:35.626  7241  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 12:54:35.626  7241  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 12:54:35.626  7241  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 12:54:35.626  7241  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:2A:28:2D
06-30 12:54:35.626  7241  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 12:54:35.626  7241  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 12:54:35.626  7241  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 12:54:35.626  7241  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 12:54:35.626  7241  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 12:54:35.626  7241  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 12:54:35.626  7241  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,06-30 12:54:35.626  7241  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a89d6a added. We now have 1 listener(s)
06-30 12:54:35.626  7241  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 12:54:35.636  7241  7294 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,06-30 12:54:35.646  7241  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
06-30 12:54:35.646  7241  7294 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,06-30 12:54:35.656   903  3071 D SSRM:n  : SIOP:: AP = 320, PST = 311, CUR = 450
,06-30 12:54:35.666  7241  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 12:54:35.666  7241  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:2A:28:2D
,06-30 12:54:35.666   903  1259 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:54:35.676  7241  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:54:35.676  7241  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:54:35.676  7241  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 12:54:35.676  7241  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 12:54:35.676  7241  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 12:54:35.676  7241  7294 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 12:54:35.676  7241  7294 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 12:54:35.676  7241  7294 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 12:54:35.676  7241  7294 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,06-30 12:54:35.676  7241  7294 D io.jxcore.node.ConnectivityMonitor: start: OK
,06-30 12:54:35.676   903  1730 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:54:35.676  7241  7294 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 12:54:35.676  7241  7241 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 12:54:35.676   903  3765 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:54:35.676  7241  7241 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 12:54:35.726  7241  7241 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 12:54:36.126   306   306 E SMD     : DCD ON
,06-30 12:54:36.296   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:36.726  7241  7299 W jxcore-log: Initializing JXcore engine
06-30 12:54:36.726  7241  7299 W jxcore-log: JXcore engine is ready
,06-30 12:54:36.776  1950  1950 E auditd  : In denial and Property audit_ondenial is set to 1 
06-30 12:54:36.776  1950  1950 E audit   : type=1400 msg=audit(1467284076.776:203): avc:  denied  { ioctl } for  pid=7299 comm="Thread-1223" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
06-30 12:54:36.776  1950  1950 E audit   :  SEPF_SM-N9005_5.0-1_0032
06-30 12:54:36.776  1950  1950 E audit   : 
06-30 12:54:36.776  1950  1950 E audit   : type=1300 msg=audit(1467284076.776:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=1 a3=9aac08d8 items=0 ppid=333 ppcomm=main pid=7299 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1223" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
06-30 12:54:36.776  1950  1950 E audit   : type=1320 msg=audit(1467284076.776:203): 
,06-30 12:54:36.776   903  1020 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
,06-30 12:54:36.776   903  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,06-30 12:54:36.786   903  1020 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,06-30 12:54:36.786  7241  7299 W jxcore-log: Starting JXcore engine
,06-30 12:54:36.806  6632  6632 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,06-30 12:54:36.806  6632  6632 D SecurityLogAgent:  SeDenialReceiver : File path = null
,06-30 12:54:36.876  7241  7299 W jxcore-log: Platform android
06-30 12:54:36.876  7241  7299 W jxcore-log: 
06-30 12:54:36.876  7241  7299 W jxcore-log: Process ARCH arm
06-30 12:54:36.876  7241  7299 W jxcore-log: 
,06-30 12:54:36.936   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:54:37.076  7241  7299 I jxcore-log: JXcore Cordova bridge is ready!
06-30 12:54:37.076  7241  7299 I jxcore-log: 
06-30 12:54:37.076  7241  7299 W jxcore-log: JXcore engine is started
,06-30 12:54:37.086  7241  7294 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 12:54:37.086  7241  7241 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-30 12:54:37.296   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:38.296   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:39.126   306   306 E SMD     : DCD ON
,06-30 12:54:39.296   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:40.306   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:40.346   903  1649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:54:40.346   903  1649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 12:54:40.346   903  1649 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 12:54:40.346   903  1649 D BatteryService: stay LED for fully charged
06-30 12:54:40.346   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:54:40.356  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:54:40.356  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:54:40.356   903   903 I MotionRecognitionService: Plugged
06-30 12:54:40.356   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:54:40.356  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:54:40.356  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:40.356  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:54:40.356  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:54:40.376  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:40.376  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:41.306   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 12:54:42.136   306   306 E SMD     : DCD ON
,06-30 12:54:44.296   903  1051 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,06-30 12:54:45.136   306   306 E SMD     : DCD ON
,06-30 12:54:45.706   903  3071 D SSRM:n  : SIOP:: AP = 350, PST = 315, CUR = 450
,06-30 12:54:46.956  7241  7299 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
06-30 12:54:46.956  7241  7299 I jxcore-log: 
,06-30 12:54:46.956  7241  7299 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
06-30 12:54:46.956  7241  7299 I jxcore-log: 
,06-30 12:54:46.956   903  1317 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:54:46.956  7241  7299 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:54:46.956  7241  7299 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:54:46.956  7241  7299 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 12:54:46.956  7241  7299 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 12:54:46.956  7241  7299 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 12:54:46.956  7241  7299 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 12:54:46.956  7241  7299 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 12:54:46.956  7241  7299 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-30 12:54:46.966  7241  7299 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,06-30 12:54:46.966  7241  7299 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-30 12:54:46.966  7241  7299 I jxcore-log: 
,06-30 12:54:46.966  7241  7299 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
06-30 12:54:46.966  7241  7299 I jxcore-log: 
,06-30 12:54:47.296  7241  7299 I jxcore-log: Unit Test app is loaded
06-30 12:54:47.296  7241  7299 I jxcore-log: 
,06-30 12:54:47.296  7241  7299 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-30 12:54:47.296  7241  7299 I jxcore-log: 
,06-30 12:54:47.306  7241  7299 I jxcore-log: My device name is: samsung-SM-N9005
06-30 12:54:47.306  7241  7299 I jxcore-log: 
,06-30 12:54:47.306  7241  7299 I jxcore-log: WARN testUtils: myNameCallback not set!
06-30 12:54:47.306  7241  7299 I jxcore-log: 
,06-30 12:54:47.316  7241  7241 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,06-30 12:54:48.136   306   306 E SMD     : DCD ON
,06-30 12:54:50.396   903  1258 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:54:50.396   903  1258 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 12:54:50.396   903  1258 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 12:54:50.396   903  1258 D BatteryService: stay LED for fully charged
06-30 12:54:50.396   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:54:50.406   903   903 I MotionRecognitionService: Plugged
06-30 12:54:50.406   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:54:50.406  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:54:50.406  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:54:50.416  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:54:50.426  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:54:50.426  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:54:50.436  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:50.436  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:54:50.436  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:51.046  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
06-30 12:54:51.046  7241  7299 I jxcore-log: 
,06-30 12:54:51.136   306   306 E SMD     : DCD ON
,06-30 12:54:51.436  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
06-30 12:54:51.436  7241  7299 I jxcore-log: 
,06-30 12:54:51.456  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
06-30 12:54:51.456  7241  7299 I jxcore-log: 
,06-30 12:54:51.456  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
06-30 12:54:51.456  7241  7299 I jxcore-log: 
,06-30 12:54:51.476  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
06-30 12:54:51.476  7241  7299 I jxcore-log: 
,06-30 12:54:51.476  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-30 12:54:51.476  7241  7299 I jxcore-log: 
,06-30 12:54:53.376  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
06-30 12:54:53.376  7241  7299 I jxcore-log: 
,06-30 12:54:53.396  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
06-30 12:54:53.396  7241  7299 I jxcore-log: 
,06-30 12:54:53.396  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
06-30 12:54:53.396  7241  7299 I jxcore-log: 
,06-30 12:54:53.556  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
06-30 12:54:53.556  7241  7299 I jxcore-log: 
,06-30 12:54:53.636  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-30 12:54:53.636  7241  7299 I jxcore-log: 
,06-30 12:54:53.686  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-30 12:54:53.686  7241  7299 I jxcore-log: 
,06-30 12:54:53.696  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-30 12:54:53.696  7241  7299 I jxcore-log: 
,06-30 12:54:53.876  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
06-30 12:54:53.876  7241  7299 I jxcore-log: 
,06-30 12:54:53.906  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-30 12:54:53.906  7241  7299 I jxcore-log: 
,06-30 12:54:53.906  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-30 12:54:53.906  7241  7299 I jxcore-log: 
,06-30 12:54:53.906  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-30 12:54:53.906  7241  7299 I jxcore-log: 
,06-30 12:54:53.926  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-30 12:54:53.926  7241  7299 I jxcore-log: 
,06-30 12:54:53.946  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-30 12:54:53.946  7241  7299 I jxcore-log: 
,06-30 12:54:54.026  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
06-30 12:54:54.026  7241  7299 I jxcore-log: 
,06-30 12:54:54.036  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
06-30 12:54:54.036  7241  7299 I jxcore-log: 
,06-30 12:54:54.056  7241  7299 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
06-30 12:54:54.056  7241  7299 I jxcore-log: 
,06-30 12:54:54.066  7241  7299 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,06-30 12:54:54.066  7241  7299 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
06-30 12:54:54.066  7241  7299 I jxcore-log: 
,06-30 12:54:54.136   306   306 E SMD     : DCD ON
,06-30 12:54:55.756   903  3071 D SSRM:n  : SIOP:: AP = 350, PST = 319, CUR = 450
,06-30 12:54:56.556   903  1099 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 12:54:56.566   903  1098 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 12:54:56.566   903  1099 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 12:54:56.576   903  1099 I TLC_TIMA_PKM_initialize: initializing...
,06-30 12:54:56.576   903  1099 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,06-30 12:54:56.576   903  1099 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,06-30 12:54:56.586   903  1099 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,06-30 12:54:56.586   903  1099 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,06-30 12:54:56.586   903  1099 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,06-30 12:54:56.586   903  1099 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,06-30 12:54:56.586   903  1099 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,06-30 12:54:56.596   903  1099 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
06-30 12:54:56.596   903  1099 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 12:54:56.616   903  1099 D QSEECOMAPI: : Loaded image: APP id = 2
,06-30 12:54:56.626   903  1099 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,06-30 12:54:56.626   903  1099 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-30 12:54:56.946   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:54:57.136   306   306 E SMD     : DCD ON
,06-30 12:54:59.396   903  1035 I PowerManagerService: [PWL] Off : 275s ago
,06-30 12:54:59.396   903  1035 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,06-30 12:54:59.396   903  1035 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,06-30 12:54:59.396   903  1035 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=903, ws=null) (elapsedTime=2831)
,06-30 12:54:59.426   903  1338 E Watchdog: !@Sync 10
,06-30 12:54:59.486   903  1099 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 12:54:59.486   903  1099 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 12:54:59.496   903  1099 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 12:54:59.506   903  1099 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 12:55:00.136   306   306 E SMD     : DCD ON
,06-30 12:55:00.456   903  1448 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:00.466   903  1448 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:55:00.466   903  1448 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 12:55:00.466   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:55:00.476  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:55:00.476  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:55:00.476   903   903 I MotionRecognitionService: Plugged
06-30 12:55:00.476   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:55:00.476   903  1448 D BatteryService: stay LED for fully charged
,06-30 12:55:00.476  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:55:00.486  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:55:00.486  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:55:00.496  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:00.496  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:00.496  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:03.136   306   306 E SMD     : DCD ON
,06-30 12:55:05.806   903  3071 D SSRM:n  : SIOP:: AP = 330, PST = 321, CUR = 450
,06-30 12:55:06.136   306   306 E SMD     : DCD ON
,06-30 12:55:06.306   343   343 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 12:55:06.306   343   343 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 12:55:09.136   306   306 E SMD     : DCD ON
,06-30 12:55:12.136   306   306 E SMD     : DCD ON
,06-30 12:55:15.136   306   306 E SMD     : DCD ON
,06-30 12:55:15.846   903  3071 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 450
,06-30 12:55:15.886   903  1110 V AlarmManager: waitForAlarm result :4
,06-30 12:55:15.906   903   981 D ActivityManager: startProcessLocked calleePkgName: com.blurb.checkout, hostingType: broadcast
,06-30 12:55:15.916   903   981 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:55:15.916   903   981 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:55:15.916   903   981 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:55:15.916   903   981 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:55:15.946   903  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:15.946   903  1482 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:55:15.946   903  1482 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 12:55:15.946   903  1482 D BatteryService: stay LED for fully charged
,06-30 12:55:15.986   903   981 I ActivityManager: Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7306 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 12:55:15.986  7306  7306 E Zygote  : MountEmulatedStorage()
,06-30 12:55:15.986  7306  7306 E Zygote  : v2
06-30 12:55:15.986  7306  7306 I libpersona: KNOX_SDCARD checking this for 10096
06-30 12:55:15.986  7306  7306 I libpersona: KNOX_SDCARD not a persona
,06-30 12:55:15.996   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:55:16.006  7306  7306 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,06-30 12:55:16.006  7306  7306 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 12:55:16.006  7306  7306 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,06-30 12:55:16.006  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 12:55:16.006  1191  1191 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 12:55:16.006   903   903 I MotionRecognitionService: Plugged
06-30 12:55:16.006  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:55:16.006   903   903 I MotionRecognitionService: setPowerConnected  = true
06-30 12:55:16.006  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:55:16.006  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
06-30 12:55:16.016  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 12:55:16.016  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
06-30 12:55:16.016  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:16.016  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:16.026  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:16.026  1191  1191 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
06-30 12:55:16.026  1191  1191 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 12:55:16.036  7306  7306 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:55:16.036  7306  7306 D ActivityThread: Added TimaKeyStore provider
,06-30 12:55:16.056  7306  7306 D ResourcesManager: creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,06-30 12:55:16.066   903  1368 D ActivityManager: startService callerProcessName:com.blurb.checkout, calleePkgName: com.blurb.checkout
,06-30 12:55:16.066   903  1368 D ActivityManager: caller:android.app.ApplicationThreadProxy@18f03f4d, r.packageName :com.blurb.checkout
,06-30 12:55:16.076  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:55:16.086  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:55:16.096   903  1141 I ActivityManager: Killing 6594:com.sec.android.app.clockpackage/u0a106 (adj 15): emptyCount ##41
,06-30 12:55:16.946   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:18.136   306   306 E SMD     : DCD ON
,06-30 12:55:21.146   306   306 E SMD     : DCD ON
,06-30 12:55:21.306   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:22.306   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:23.306   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:24.146   306   306 E SMD     : DCD ON
,06-30 12:55:24.306   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:25.306   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:25.896   903  3071 D SSRM:n  : SIOP:: AP = 310, PST = 322, CUR = 450
,06-30 12:55:26.006   903  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:26.006   903  1730 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:55:26.006   903  1730 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 12:55:26.016   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:55:26.016   903   903 I MotionRecognitionService: Plugged
,06-30 12:55:26.016   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:55:26.026  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:55:26.026  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:55:26.026   903  1730 D BatteryService: stay LED for fully charged
,06-30 12:55:26.026  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:55:26.026  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:55:26.036  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:26.036  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:26.036  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:26.036  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:55:26.306   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-30 12:55:27.146   306   306 E SMD     : DCD ON
,06-30 12:55:29.426   903  1338 E Watchdog: !@Sync 11
,06-30 12:55:30.146   306   306 E SMD     : DCD ON
,06-30 12:55:31.306   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:32.306   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:33.146   306   306 E SMD     : DCD ON
,06-30 12:55:33.316   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:34.316   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:35.316   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:35.946   903  3071 D SSRM:n  : SIOP:: AP = 310, PST = 322, CUR = 450
,06-30 12:55:36.066   903  1649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:36.146   306   306 E SMD     : DCD ON
,06-30 12:55:36.316   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 12:55:36.946   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:39.146   306   306 E SMD     : DCD ON
,06-30 12:55:42.146   306   306 E SMD     : DCD ON
,06-30 12:55:45.146   306   306 E SMD     : DCD ON
,06-30 12:55:45.996   903  3071 D SSRM:n  : SIOP:: AP = 310, PST = 322, CUR = 450
,06-30 12:55:46.126   903  1317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:46.126   903  1317 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:55:46.126   903  1317 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 12:55:46.136   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:55:46.136   903   903 I MotionRecognitionService: Plugged
,06-30 12:55:46.136   903   903 I MotionRecognitionService: setPowerConnected  = true
06-30 12:55:46.136  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:55:46.146  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
06-30 12:55:46.146  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 12:55:46.146  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
06-30 12:55:46.146  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:46.146   903  1317 D BatteryService: stay LED for fully charged
06-30 12:55:46.146  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:46.156  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:46.156  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:55:46.316   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:47.316   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:48.146   306   306 E SMD     : DCD ON
,06-30 12:55:48.316   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:49.316   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:50.316   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:51.146   306   306 E SMD     : DCD ON
,06-30 12:55:51.316   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 12:55:54.146   306   306 E SMD     : DCD ON
,06-30 12:55:54.406   903  1035 I PowerManagerService: [PWL] Off : 330s ago
,06-30 12:55:56.046   903  3071 D SSRM:n  : SIOP:: AP = 310, PST = 322, CUR = 450
,06-30 12:55:56.186   903   919 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:56.186   903   919 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:55:56.196   903   919 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 12:55:56.196   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:55:56.196  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:55:56.206  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:55:56.206   903   903 I MotionRecognitionService: Plugged
,06-30 12:55:56.206   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:55:56.206  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:56.206   903   919 D BatteryService: stay LED for fully charged
,06-30 12:55:56.206  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:56.216  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:55:56.216  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:55:56.216  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:55:56.216  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:56.956   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:57.156   306   306 E SMD     : DCD ON
,06-30 12:55:59.436   903  1338 E Watchdog: !@Sync 12
,06-30 12:55:59.986   903  1110 V AlarmManager: waitForAlarm result :8
,06-30 12:56:00.156   306   306 E SMD     : DCD ON
,06-30 12:56:03.156   306   306 E SMD     : DCD ON
,06-30 12:56:06.086   903  3071 D SSRM:n  : SIOP:: AP = 310, PST = 322, CUR = 450
,06-30 12:56:06.156   306   306 E SMD     : DCD ON
,06-30 12:56:06.246   903  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:06.326   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:07.326   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:08.326   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:09.156   306   306 E SMD     : DCD ON
,06-30 12:56:09.326   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:10.326   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:11.326   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 12:56:12.156   306   306 E SMD     : DCD ON
,06-30 12:56:15.156   306   306 E SMD     : DCD ON
,06-30 12:56:16.136   903  3071 D SSRM:n  : SIOP:: AP = 310, PST = 321, CUR = 450
,06-30 12:56:16.306   903  1259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:16.316   903  1259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 12:56:16.316   903  1259 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 12:56:16.316   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:56:16.316   903   903 I MotionRecognitionService: Plugged
,06-30 12:56:16.316   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:56:16.326  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:56:16.326  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:56:16.326  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:56:16.326  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:56:16.326   903  1259 D BatteryService: stay LED for fully charged
,06-30 12:56:16.326  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:16.336  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:16.336  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:16.336  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:56:16.956   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:56:18.156   306   306 E SMD     : DCD ON
,06-30 12:56:21.156   306   306 E SMD     : DCD ON
,06-30 12:56:24.156   306   306 E SMD     : DCD ON
,06-30 12:56:26.186   903  3071 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 450
,06-30 12:56:26.366   903  1258 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:26.376   903  1258 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:56:26.376   903  1258 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 12:56:26.376   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:56:26.376   903   903 I MotionRecognitionService: Plugged
,06-30 12:56:26.376   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:56:26.386  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:56:26.386  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:56:26.386   903  1258 D BatteryService: stay LED for fully charged
,06-30 12:56:26.386  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:26.386  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:56:26.386  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:56:26.396  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:26.396  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:56:26.396  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:56:27.156   306   306 E SMD     : DCD ON
,06-30 12:56:29.436   903  1338 E Watchdog: !@Sync 13
,06-30 12:56:30.156   306   306 E SMD     : DCD ON
,06-30 12:56:31.326   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:32.326   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:33.166   306   306 E SMD     : DCD ON
,06-30 12:56:33.326   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:34.336   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:35.336   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:36.166   306   306 E SMD     : DCD ON
,06-30 12:56:36.226   903  3071 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 450
,06-30 12:56:36.336   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 12:56:36.426   903  1259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:36.426   903  1259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:56:36.436   903  1259 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 12:56:36.436   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:56:36.436   903   903 I MotionRecognitionService: Plugged
,06-30 12:56:36.436   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:56:36.446  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:56:36.446  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:56:36.446   903  1259 D BatteryService: stay LED for fully charged
,06-30 12:56:36.446  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:36.446  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:36.446  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:36.456  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 12:56:36.456  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:56:36.456  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:56:36.966   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:56:39.166   306   306 E SMD     : DCD ON
,06-30 12:56:42.166   306   306 E SMD     : DCD ON
,06-30 12:56:45.166   306   306 E SMD     : DCD ON
,06-30 12:56:46.276   903  3071 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,06-30 12:56:46.486   903  1258 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:46.486   903  1258 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:56:46.496   903  1258 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 12:56:46.496   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:56:46.496   903   903 I MotionRecognitionService: Plugged
,06-30 12:56:46.496   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:56:46.496  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:56:46.506  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:56:46.506  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:46.506   903  1258 D BatteryService: stay LED for fully charged
,06-30 12:56:46.506  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:56:46.506  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:56:46.516  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:46.516  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:46.516  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:56:48.166   306   306 E SMD     : DCD ON
,06-30 12:56:51.166   306   306 E SMD     : DCD ON
,06-30 12:56:54.166   306   306 E SMD     : DCD ON
,06-30 12:56:54.406   903  1035 I PowerManagerService: [PWL] Off : 390s ago
,06-30 12:56:56.326   903  3071 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 12:56:56.556   903  1259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:56.556   903  1259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:56:56.556   903  1259 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 12:56:56.556   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:56:56.556  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:56:56.556  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:56:56.556   903   903 I MotionRecognitionService: Plugged
06-30 12:56:56.556   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:56:56.566  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:56:56.566  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:56:56.566  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:56:56.566   903  1259 D BatteryService: stay LED for fully charged
,06-30 12:56:56.576  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:56.576  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:56.576  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:56.966   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:56:57.166   306   306 E SMD     : DCD ON
,06-30 12:56:59.436   903  1338 E Watchdog: !@Sync 14
,06-30 12:57:00.166   306   306 E SMD     : DCD ON
,06-30 12:57:01.336   343   343 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 12:57:01.336   343   343 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 12:57:03.166   306   306 E SMD     : DCD ON
,06-30 12:57:06.166   306   306 E SMD     : DCD ON
,06-30 12:57:06.376   903  3071 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 12:57:06.616   903  1258 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:06.616   903  1258 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:57:06.616   903  1258 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 12:57:06.616   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:57:06.626  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:57:06.626  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:57:06.636   903   903 I MotionRecognitionService: Plugged
,06-30 12:57:06.636   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:57:06.636   903  1258 D BatteryService: stay LED for fully charged
,06-30 12:57:06.646  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:57:06.656  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:06.656  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:57:06.656  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:57:06.666  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:06.676  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:09.176   306   306 E SMD     : DCD ON
,06-30 12:57:12.176   306   306 E SMD     : DCD ON
,06-30 12:57:15.176   306   306 E SMD     : DCD ON
,06-30 12:57:16.416   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450
,06-30 12:57:16.676   903  1259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:16.676   903  1259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:57:16.686   903  1259 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 12:57:16.686   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:57:16.686   903   903 I MotionRecognitionService: Plugged
,06-30 12:57:16.686   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:57:16.686  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:57:16.696  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:57:16.696  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:57:16.696  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:57:16.696  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:57:16.696   903  1259 D BatteryService: stay LED for fully charged
06-30 12:57:16.696  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:16.706  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:16.706  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:16.976   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:57:18.176   306   306 E SMD     : DCD ON
,06-30 12:57:21.176   306   306 E SMD     : DCD ON
,06-30 12:57:21.336   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:22.336   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:23.336   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:24.176   306   306 E SMD     : DCD ON
,06-30 12:57:24.336   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:25.336   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:26.336   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-30 12:57:26.466   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450
,06-30 12:57:26.736   903  1258 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:26.736   903  1258 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:57:26.746   903  1258 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 12:57:26.746   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:57:26.746   903   903 I MotionRecognitionService: Plugged
,06-30 12:57:26.746   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:57:26.746  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:57:26.756  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:57:26.756  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:57:26.756  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:26.756  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:57:26.756  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:57:26.766   903  1258 D BatteryService: stay LED for fully charged
,06-30 12:57:26.766  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:26.766  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:27.176   306   306 E SMD     : DCD ON
,06-30 12:57:29.446   903  1338 E Watchdog: !@Sync 15
,06-30 12:57:30.176   306   306 E SMD     : DCD ON
,06-30 12:57:31.346   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:32.346   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:33.176   306   306 E SMD     : DCD ON
,06-30 12:57:33.346   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:34.346   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:35.346   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:36.176   306   306 E SMD     : DCD ON
,06-30 12:57:36.346   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 12:57:36.516   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450
,06-30 12:57:36.796   903   920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:36.806   903   920 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:57:36.806   903   920 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 12:57:36.806   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:57:36.806   903   903 I MotionRecognitionService: Plugged
,06-30 12:57:36.806   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:57:36.816  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:57:36.816  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:57:36.816  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:57:36.816   903   920 D BatteryService: stay LED for fully charged
,06-30 12:57:36.816  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:57:36.816  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:57:36.826  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:36.826  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:57:36.826  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:36.986   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:57:39.176   306   306 E SMD     : DCD ON
,06-30 12:57:42.176   306   306 E SMD     : DCD ON
,06-30 12:57:45.176   306   306 E SMD     : DCD ON
,06-30 12:57:46.346   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:46.556   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450
,06-30 12:57:46.856   903  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:47.346   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:47.606   339   339 I bootchecker: bootchecker wake up!!
,06-30 12:57:48.186   306   306 E SMD     : DCD ON
,06-30 12:57:48.346   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:49.356   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:50.356   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:51.186   306   306 E SMD     : DCD ON
,06-30 12:57:51.356   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 12:57:54.186   306   306 E SMD     : DCD ON
,06-30 12:57:56.606   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450
,06-30 12:57:56.916   903  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:56.986   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:57:57.186   306   306 E SMD     : DCD ON
,06-30 12:57:59.406   903  1035 I PowerManagerService: [PWL] Off : 455s ago
,06-30 12:57:59.446   903  1338 E Watchdog: !@Sync 16
,06-30 12:58:00.186   306   306 E SMD     : DCD ON
,06-30 12:58:03.186   306   306 E SMD     : DCD ON
,06-30 12:58:06.186   306   306 E SMD     : DCD ON
,06-30 12:58:06.356   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:06.656   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450
,06-30 12:58:06.976   903  1448 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:06.986   903  1448 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:58:06.986   903  1448 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 12:58:06.986   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:58:06.986   903   903 I MotionRecognitionService: Plugged
,06-30 12:58:06.986   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:58:06.996  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:58:06.996  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:58:06.996  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:58:06.996   903  1448 D BatteryService: stay LED for fully charged
,06-30 12:58:06.996  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:58:06.996  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:58:07.006  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:07.006  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:07.006  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:07.356   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:08.356   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:09.186   306   306 E SMD     : DCD ON
,06-30 12:58:09.356   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:10.356   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:11.356   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 12:58:12.186   306   306 E SMD     : DCD ON
,06-30 12:58:15.186   306   306 E SMD     : DCD ON
,06-30 12:58:16.706   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,06-30 12:58:16.986   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:58:17.036   903  1471 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:18.186   306   306 E SMD     : DCD ON
,06-30 12:58:21.186   306   306 E SMD     : DCD ON
,06-30 12:58:24.196   306   306 E SMD     : DCD ON
,06-30 12:58:26.756   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,06-30 12:58:27.096   903   919 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:27.196   306   306 E SMD     : DCD ON
,06-30 12:58:29.446   903  1338 E Watchdog: !@Sync 17
,06-30 12:58:30.196   306   306 E SMD     : DCD ON
,06-30 12:58:31.356   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:32.366   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:33.196   306   306 E SMD     : DCD ON
,06-30 12:58:33.366   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:34.366   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:35.366   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:36.196   306   306 E SMD     : DCD ON
,06-30 12:58:36.366   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 12:58:36.806   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,06-30 12:58:36.996   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:58:37.156   903  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:37.166   903  1730 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:58:37.166   903  1730 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 12:58:37.166   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:58:37.166   903   903 I MotionRecognitionService: Plugged
,06-30 12:58:37.166  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:58:37.176  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:58:37.176   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:58:37.176   903  1730 D BatteryService: stay LED for fully charged
,06-30 12:58:37.176  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:58:37.176  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:58:37.176  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:58:37.186  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:37.186  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:37.186  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:39.196   306   306 E SMD     : DCD ON
,06-30 12:58:42.196   306   306 E SMD     : DCD ON
,06-30 12:58:45.196   306   306 E SMD     : DCD ON
,06-30 12:58:46.846   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 12:58:47.216   903   920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:48.196   306   306 E SMD     : DCD ON
,06-30 12:58:51.196   306   306 E SMD     : DCD ON
,06-30 12:58:54.196   306   306 E SMD     : DCD ON
,06-30 12:58:56.896   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 12:58:56.996   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:58:57.196   306   306 E SMD     : DCD ON
,06-30 12:58:57.276   903  3050 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:57.286   903  3050 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:58:57.286   903  3050 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 12:58:57.286   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:58:57.286   903   903 I MotionRecognitionService: Plugged
,06-30 12:58:57.286   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:58:57.296  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:58:57.296  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:58:57.296  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:58:57.296  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:58:57.296   903  3050 D BatteryService: stay LED for fully charged
,06-30 12:58:57.306  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:58:57.306  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:57.306  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:58:57.306  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:59.446   903  1338 E Watchdog: !@Sync 18
,06-30 12:59:00.206   306   306 E SMD     : DCD ON
,06-30 12:59:01.366   343   343 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 12:59:01.366   343   343 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 12:59:03.206   306   306 E SMD     : DCD ON
,06-30 12:59:06.206   306   306 E SMD     : DCD ON
,06-30 12:59:06.946   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 12:59:07.336   903  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:07.346   903  1482 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:59:07.346   903  1482 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 12:59:07.346   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:59:07.346   903   903 I MotionRecognitionService: Plugged
,06-30 12:59:07.346   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:59:07.346  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:59:07.346  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:59:07.356   903  1482 D BatteryService: stay LED for fully charged
,06-30 12:59:07.356  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:59:07.356  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:07.356  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:07.366  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:07.366  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:59:07.366  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:59:09.206   306   306 E SMD     : DCD ON
,06-30 12:59:09.416   903  1035 I PowerManagerService: [PWL] Off : 525s ago
,06-30 12:59:12.206   306   306 E SMD     : DCD ON
,06-30 12:59:15.206   306   306 E SMD     : DCD ON
,06-30 12:59:16.996   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 12:59:16.996   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:59:17.406   903  3050 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:17.406   903  3050 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:59:17.406   903  3050 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 12:59:17.416   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:59:17.416  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:59:17.426  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:59:17.426   903   903 I MotionRecognitionService: Plugged
,06-30 12:59:17.426   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:59:17.426   903  3050 D BatteryService: stay LED for fully charged
,06-30 12:59:17.436  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:59:17.446  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:17.446  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:17.446  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:59:17.446  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:59:17.456  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:18.206   306   306 E SMD     : DCD ON
,06-30 12:59:21.206   306   306 E SMD     : DCD ON
,06-30 12:59:24.206   306   306 E SMD     : DCD ON
,06-30 12:59:26.376   343   343 I Atfwd_Daemon: Stop the daemon....
,06-30 12:59:27.046   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 12:59:27.206   306   306 E SMD     : DCD ON
,06-30 12:59:27.466   903  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:27.476   903  1482 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:59:27.476   903  1482 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 12:59:27.476   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:59:27.486  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:59:27.486  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:59:27.496   903   903 I MotionRecognitionService: Plugged
,06-30 12:59:27.496  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:27.496   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:59:27.496  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:27.496   903  1482 D BatteryService: stay LED for fully charged
,06-30 12:59:27.496  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:27.496  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:59:27.496  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:59:27.506  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:59:29.456   903  1338 E Watchdog: !@Sync 19
,06-30 12:59:30.206   306   306 E SMD     : DCD ON
,06-30 12:59:33.206   306   306 E SMD     : DCD ON
,06-30 12:59:36.206   306   306 E SMD     : DCD ON
,06-30 12:59:37.006   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:59:37.106   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 12:59:37.526   903  3050 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:37.526   903  3050 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:59:37.526   903  3050 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 12:59:37.536   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:59:37.536  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:59:37.546  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:59:37.546   903   903 I MotionRecognitionService: Plugged
,06-30 12:59:37.546   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:59:37.546   903  3050 D BatteryService: stay LED for fully charged
,06-30 12:59:37.556  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:59:37.566  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:37.566  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:37.566  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:59:37.566  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:59:37.576  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:39.216   306   306 E SMD     : DCD ON
,06-30 12:59:42.216   306   306 E SMD     : DCD ON
,06-30 12:59:45.216   306   306 E SMD     : DCD ON
,06-30 12:59:47.166   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 12:59:47.586   903  3712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:47.586   903  3712 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:59:47.586   903  3712 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 12:59:47.586   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:59:47.596  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:59:47.596  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:59:47.606   903   903 I MotionRecognitionService: Plugged,
06-30 12:59:47.606   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:59:47.606   903  3712 D BatteryService: stay LED for fully charged
,06-30 12:59:47.606  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:59:47.616  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:59:47.616  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:59:47.626  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:47.626  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:59:47.626  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:48.216   306   306 E SMD     : DCD ON
,06-30 12:59:51.216   306   306 E SMD     : DCD ON
,06-30 12:59:54.216   306   306 E SMD     : DCD ON
,06-30 12:59:56.556   903  1099 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 12:59:56.556   903  1099 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 12:59:56.556   903  1098 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 12:59:57.006   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:59:57.216   306   306 E SMD     : DCD ON
,06-30 12:59:57.226   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 12:59:57.646   903  3050 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:59.436   903  1099 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 12:59:59.436   903  1099 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 12:59:59.446   903  1099 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 12:59:59.456   903  1099 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 12:59:59.456   903  1338 E Watchdog: !@Sync 20
,06-30 13:00:00.216   306   306 E SMD     : DCD ON
,06-30 13:00:03.216   306   306 E SMD     : DCD ON
,06-30 13:00:06.216   306   306 E SMD     : DCD ON
,06-30 13:00:07.286   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:00:07.706   903  1471 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:09.216   306   306 E SMD     : DCD ON
,06-30 13:00:12.216   306   306 E SMD     : DCD ON
,06-30 13:00:15.216   306   306 E SMD     : DCD ON
,06-30 13:00:17.016   903  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:00:17.336   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:00:17.766   903   919 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:18.226   306   306 E SMD     : DCD ON
,06-30 13:00:21.226   306   306 E SMD     : DCD ON
,06-30 13:00:24.226   306   306 E SMD     : DCD ON
,06-30 13:00:24.416   903  1035 I PowerManagerService: [PWL] Off : 600s ago
,06-30 13:00:27.226   306   306 E SMD     : DCD ON
,06-30 13:00:27.386   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:00:27.826   903  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:29.456   903  1338 E Watchdog: !@Sync 21
,06-30 13:00:30.226   306   306 E SMD     : DCD ON
,06-30 13:00:33.226   306   306 E SMD     : DCD ON
,06-30 13:00:36.226   306   306 E SMD     : DCD ON
,06-30 13:00:37.446   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:00:37.886   903  3712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:39.226   306   306 E SMD     : DCD ON
,06-30 13:00:42.226   306   306 E SMD     : DCD ON
,06-30 13:00:45.226   306   306 E SMD     : DCD ON
,06-30 13:00:47.496   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:00:47.946   903  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:48.226   306   306 E SMD     : DCD ON
,06-30 13:00:51.226   306   306 E SMD     : DCD ON
,06-30 13:00:54.236   306   306 E SMD     : DCD ON
,06-30 13:00:57.236   306   306 E SMD     : DCD ON
,06-30 13:00:57.546   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:00:58.006   903  1317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:59.466   903  1338 E Watchdog: !@Sync 22
,06-30 13:01:00.236   306   306 E SMD     : DCD ON
,06-30 13:01:03.236   306   306 E SMD     : DCD ON
,06-30 13:01:06.236   306   306 E SMD     : DCD ON
,06-30 13:01:07.606   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:01:08.066   903   920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:08.066   903   920 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:01:08.066   903   920 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:01:08.076   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:01:08.076  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:01:08.086  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:01:08.086   903   903 I MotionRecognitionService: Plugged
,06-30 13:01:08.086   903   903 I MotionRecognitionService: setPowerConnected  = true
06-30 13:01:08.086   903   920 D BatteryService: stay LED for fully charged
,06-30 13:01:08.096  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:01:08.106  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:08.116  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:01:08.116  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:01:08.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:08.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:09.236   306   306 E SMD     : DCD ON
,06-30 13:01:12.236   306   306 E SMD     : DCD ON
,06-30 13:01:15.236   306   306 E SMD     : DCD ON
,06-30 13:01:17.646   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:01:18.126   903  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:18.126   903  1730 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:01:18.126   903  1730 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:01:18.126   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:01:18.136  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:01:18.136  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:01:18.136   903   903 I MotionRecognitionService: Plugged
,06-30 13:01:18.146   903  1730 D BatteryService: stay LED for fully charged
06-30 13:01:18.146   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:01:18.146  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:01:18.156  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:01:18.156  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:01:18.166  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:18.166  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:01:18.166  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:18.236   306   306 E SMD     : DCD ON
,06-30 13:01:21.236   306   306 E SMD     : DCD ON
,06-30 13:01:24.236   306   306 E SMD     : DCD ON
,06-30 13:01:27.236   306   306 E SMD     : DCD ON
,06-30 13:01:27.706   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:01:28.186   903   920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:29.466   903  1338 E Watchdog: !@Sync 23
,06-30 13:01:30.246   306   306 E SMD     : DCD ON
,06-30 13:01:33.246   306   306 E SMD     : DCD ON
,06-30 13:01:36.246   306   306 E SMD     : DCD ON
,06-30 13:01:37.766   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:01:38.246   903  3050 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:38.246   903  3050 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:01:38.246   903  3050 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:01:38.246   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:01:38.256  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:01:38.256  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:01:38.266   903   903 I MotionRecognitionService: Plugged
,06-30 13:01:38.266   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:01:38.276   903  3050 D BatteryService: stay LED for fully charged
,06-30 13:01:38.276  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:01:38.286  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:38.286  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:38.286  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:01:38.296  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:01:38.296  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:39.246   306   306 E SMD     : DCD ON
,06-30 13:01:42.246   306   306 E SMD     : DCD ON
,06-30 13:01:44.416   903  1035 I PowerManagerService: [PWL] Off : 680s ago
,06-30 13:01:45.246   306   306 E SMD     : DCD ON
,06-30 13:01:47.826   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:01:48.246   306   306 E SMD     : DCD ON
,06-30 13:01:48.316   903  3712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:48.316   903  3712 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:01:48.316   903  3712 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:01:48.326   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:01:48.326   903   903 I MotionRecognitionService: Plugged
,06-30 13:01:48.326  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:01:48.326  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:01:48.336  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:01:48.336   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:01:48.336  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:48.336  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:01:48.336  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:01:48.336  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:01:48.336   903  3712 D BatteryService: stay LED for fully charged
,06-30 13:01:48.346  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:51.246   306   306 E SMD     : DCD ON
,06-30 13:01:54.246   306   306 E SMD     : DCD ON
,06-30 13:01:57.246   306   306 E SMD     : DCD ON
,06-30 13:01:57.876   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:01:58.376   903  1368 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:59.466   903  1338 E Watchdog: !@Sync 24
,06-30 13:02:00.246   306   306 E SMD     : DCD ON
,06-30 13:02:03.246   306   306 E SMD     : DCD ON
,06-30 13:02:06.256   306   306 E SMD     : DCD ON
,06-30 13:02:07.926   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:02:08.436   903  1649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:09.256   306   306 E SMD     : DCD ON
,06-30 13:02:12.256   306   306 E SMD     : DCD ON
,06-30 13:02:15.256   306   306 E SMD     : DCD ON
,06-30 13:02:17.986   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:02:18.256   306   306 E SMD     : DCD ON
,06-30 13:02:18.496   903  1258 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:18.506   903  1258 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:02:18.506   903  1258 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:02:18.506   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:02:18.506   903   903 I MotionRecognitionService: Plugged
,06-30 13:02:18.506   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:02:18.506  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:02:18.516  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:02:18.516  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:02:18.516  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:02:18.516  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:02:18.516   903  1258 D BatteryService: stay LED for fully charged
,06-30 13:02:18.526  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:02:18.526  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:18.526  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:21.256   306   306 E SMD     : DCD ON
,06-30 13:02:24.256   306   306 E SMD     : DCD ON
,06-30 13:02:27.256   306   306 E SMD     : DCD ON
,06-30 13:02:28.036   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:02:28.556   903  1259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:28.556   903  1259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:02:28.566   903  1259 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:02:28.566   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:02:28.566   903   903 I MotionRecognitionService: Plugged
,06-30 13:02:28.566   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:02:28.566  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:02:28.576  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:02:28.576  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:02:28.576  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:02:28.576  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:02:28.576  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:02:28.576   903  1259 D BatteryService: stay LED for fully charged
,06-30 13:02:28.586  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:28.596  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:29.476   903  1338 E Watchdog: !@Sync 25
,06-30 13:02:30.256   306   306 E SMD     : DCD ON
,06-30 13:02:33.256   306   306 E SMD     : DCD ON
,06-30 13:02:36.256   306   306 E SMD     : DCD ON
,06-30 13:02:38.086   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:02:38.616   903  1317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:38.626   903  1317 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:02:38.626   903  1317 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:02:38.626   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:02:38.626   903   903 I MotionRecognitionService: Plugged
,06-30 13:02:38.626   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:02:38.626  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:02:38.636  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:02:38.636  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:02:38.636  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:02:38.636  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:02:38.636   903  1317 D BatteryService: stay LED for fully charged
06-30 13:02:38.636  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:38.646  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:38.646  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:39.256   306   306 E SMD     : DCD ON
,06-30 13:02:42.256   306   306 E SMD     : DCD ON
,06-30 13:02:45.266   306   306 E SMD     : DCD ON
,06-30 13:02:48.146   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:02:48.266   306   306 E SMD     : DCD ON
,06-30 13:02:48.676   903   919 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:48.676   903   919 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:02:48.676   903   919 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:02:48.686   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:02:48.686   903   903 I MotionRecognitionService: Plugged
,06-30 13:02:48.686   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:02:48.686  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:02:48.696  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:02:48.696  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:02:48.696  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:02:48.696  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:02:48.696  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:48.706  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:48.706   903   919 D BatteryService: stay LED for fully charged
,06-30 13:02:48.706  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:51.266   306   306 E SMD     : DCD ON
,06-30 13:02:54.266   306   306 E SMD     : DCD ON
,06-30 13:02:57.266   306   306 E SMD     : DCD ON
,06-30 13:02:58.206   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:02:58.736   903  1258 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:59.476   903  1338 E Watchdog: !@Sync 26
,06-30 13:03:00.266   306   306 E SMD     : DCD ON
,06-30 13:03:03.266   306   306 E SMD     : DCD ON
,06-30 13:03:06.266   306   306 E SMD     : DCD ON
,06-30 13:03:08.266   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:03:08.796   903  3712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:08.796   903  3712 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:03:08.806   903  3712 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:03:08.806   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:03:08.806   903   903 I MotionRecognitionService: Plugged
,06-30 13:03:08.806   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:03:08.806  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:03:08.816  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:03:08.816  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:03:08.816  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:03:08.816  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:03:08.816   903  3712 D BatteryService: stay LED for fully charged
06-30 13:03:08.816  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:08.816  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:08.826  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:09.266   306   306 E SMD     : DCD ON
,06-30 13:03:09.416   903  1035 I PowerManagerService: [PWL] Off : 765s ago
,06-30 13:03:12.266   306   306 E SMD     : DCD ON
,06-30 13:03:15.266   306   306 E SMD     : DCD ON
,06-30 13:03:18.266   306   306 E SMD     : DCD ON
,06-30 13:03:18.326   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:03:18.856   903  1141 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:18.866   903  1141 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:03:18.866   903  1141 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:03:18.866   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:03:18.866   903   903 I MotionRecognitionService: Plugged
,06-30 13:03:18.866  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:03:18.876  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:03:18.876   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:03:18.876   903  1141 D BatteryService: stay LED for fully charged
,06-30 13:03:18.876  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:03:18.876  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:03:18.876  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:03:18.886  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:18.886  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:18.886  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:21.276   306   306 E SMD     : DCD ON
,06-30 13:03:24.276   306   306 E SMD     : DCD ON
,06-30 13:03:27.276   306   306 E SMD     : DCD ON
,06-30 13:03:28.366   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:03:28.916   903   920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:29.476   903  1338 E Watchdog: !@Sync 27
,06-30 13:03:30.276   306   306 E SMD     : DCD ON
,06-30 13:03:33.276   306   306 E SMD     : DCD ON
,06-30 13:03:36.276   306   306 E SMD     : DCD ON
,06-30 13:03:38.426   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:03:38.976   903  3050 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:38.976   903  3050 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:03:38.986   903  3050 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:03:38.986   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:03:38.986   903   903 I MotionRecognitionService: Plugged
,06-30 13:03:38.986  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:03:38.986  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:03:38.986   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:03:38.996  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:03:38.996  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:03:38.996  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:03:38.996   903  3050 D BatteryService: stay LED for fully charged
06-30 13:03:38.996  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:39.016  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:39.016  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:39.276   306   306 E SMD     : DCD ON
,06-30 13:03:42.276   306   306 E SMD     : DCD ON
,06-30 13:03:45.276   306   306 E SMD     : DCD ON
,06-30 13:03:48.276   306   306 E SMD     : DCD ON
,06-30 13:03:48.486   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:03:49.036   903  1368 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:51.276   306   306 E SMD     : DCD ON
,06-30 13:03:54.276   306   306 E SMD     : DCD ON
,06-30 13:03:57.276   306   306 E SMD     : DCD ON
,06-30 13:03:58.546   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:03:59.096   903  1649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:59.106   903  1649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:03:59.106   903  1649 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:03:59.106   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:03:59.106   903   903 I MotionRecognitionService: Plugged
,06-30 13:03:59.106  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:03:59.116  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:03:59.116   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:03:59.116  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:03:59.116  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:03:59.116   903  1649 D BatteryService: stay LED for fully charged
06-30 13:03:59.116  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:03:59.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:59.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:03:59.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:59.486   903  1338 E Watchdog: !@Sync 28
,06-30 13:04:00.286   306   306 E SMD     : DCD ON
,06-30 13:04:03.286   306   306 E SMD     : DCD ON
,06-30 13:04:06.286   306   306 E SMD     : DCD ON
,06-30 13:04:08.596   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:04:09.156   903  1471 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:09.166   903  1471 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:04:09.166   903  1471 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:04:09.166   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:04:09.166   903   903 I MotionRecognitionService: Plugged
,06-30 13:04:09.166   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:04:09.166  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:04:09.176  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:04:09.176   903  1471 D BatteryService: stay LED for fully charged
,06-30 13:04:09.176  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:04:09.176  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:04:09.176  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:04:09.176  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:04:09.186  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:04:09.186  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:04:09.286   306   306 E SMD     : DCD ON
,06-30 13:04:12.286   306   306 E SMD     : DCD ON
,06-30 13:04:15.286   306   306 E SMD     : DCD ON
,06-30 13:04:18.286   306   306 E SMD     : DCD ON
,06-30 13:04:18.646   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:04:19.216   903  1649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:21.286   306   306 E SMD     : DCD ON
,06-30 13:04:24.286   306   306 E SMD     : DCD ON
,06-30 13:04:27.286   306   306 E SMD     : DCD ON
,06-30 13:04:28.706   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:04:29.276   903  1317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:29.486   903  1338 E Watchdog: !@Sync 29
,06-30 13:04:30.286   306   306 E SMD     : DCD ON
,06-30 13:04:33.286   306   306 E SMD     : DCD ON
,06-30 13:04:36.286   306   306 E SMD     : DCD ON
,06-30 13:04:38.766   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:04:39.296   306   306 E SMD     : DCD ON
,06-30 13:04:39.336   903  3712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:39.426   903  1035 I PowerManagerService: [PWL] Off : 855s ago
,06-30 13:04:42.296   306   306 E SMD     : DCD ON
,06-30 13:04:45.296   306   306 E SMD     : DCD ON
,06-30 13:04:48.296   306   306 E SMD     : DCD ON
,06-30 13:04:48.826   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:04:49.406   903  3050 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:51.296   306   306 E SMD     : DCD ON
,06-30 13:04:54.296   306   306 E SMD     : DCD ON
,06-30 13:04:56.556   903  1099 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 13:04:56.556   903  1099 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:04:56.566   903  1098 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:04:57.296   306   306 E SMD     : DCD ON
,06-30 13:04:58.876   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:04:59.466   903  1368 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:59.466   903  1368 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:04:59.476   903  1368 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:04:59.476   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:04:59.486  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:04:59.486  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:04:59.486   903  1338 E Watchdog: !@Sync 30
,06-30 13:04:59.486   903  1368 D BatteryService: stay LED for fully charged
,06-30 13:04:59.486   903   903 I MotionRecognitionService: Plugged
,06-30 13:04:59.486   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:04:59.496  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:04:59.496  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:04:59.496  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:04:59.496  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:04:59.496   903  1099 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 13:04:59.496   903  1099 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:04:59.506  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:04:59.506  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:04:59.506   903  1099 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:04:59.506   903  1099 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:05:00.296   306   306 E SMD     : DCD ON
,06-30 13:05:03.296   306   306 E SMD     : DCD ON
,06-30 13:05:06.296   306   306 E SMD     : DCD ON
,06-30 13:05:08.946   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:05:09.296   306   306 E SMD     : DCD ON
,06-30 13:05:09.526   903  1649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:09.536   903  1649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:05:09.536   903  1649 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:05:09.536   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:05:09.546  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:05:09.556  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:05:09.556  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:05:09.556  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:05:09.556   903   903 I MotionRecognitionService: Plugged
,06-30 13:05:09.556   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:05:09.556  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:09.556   903  1649 D BatteryService: stay LED for fully charged
,06-30 13:05:09.566  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:09.566  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:05:09.566  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:12.296   306   306 E SMD     : DCD ON
,06-30 13:05:15.306   306   306 E SMD     : DCD ON
,06-30 13:05:18.306   306   306 E SMD     : DCD ON
,06-30 13:05:19.006   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:05:19.596   903  1110 V AlarmManager: waitForAlarm result :4
,06-30 13:05:19.616   903   903 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,06-30 13:05:19.616  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 13:05:19.616  1191  1191 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:05:19.626  1191  1191 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,06-30 13:05:19.626  1191  1191 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 13:05:19.636   903   903 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,06-30 13:05:19.636   903   919 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:19.636   903   919 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:05:19.636   903   919 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:05:19.636   903   919 D BatteryService: stay LED for fully charged
,06-30 13:05:19.656   903   903 D SensorManager: registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,06-30 13:05:19.666   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:05:19.676  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:05:19.676  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:05:19.686  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:05:19.686  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:05:19.686  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:19.686  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:19.696  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:19.696   903   903 I MotionRecognitionService: Plugged
,06-30 13:05:19.696   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:05:19.706  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:05:19.706  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:05:19.716   903  1317 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 13:05:19.716   903  1317 D ActivityManager: caller:android.app.ApplicationThreadProxy@19d5967c, r.packageName :com.google.android.gms
06-30 13:05:19.716  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:05:19.896   903  1649 I art     : Explicit concurrent mark sweep GC freed 210163(14MB) AllocSpace objects, 255(6MB) LOS objects, 30% free, 36MB/52MB, paused 1.363ms total 148.634ms
,06-30 13:05:19.906  3829  4246 D GCM     : Message class com.google.f.a.a.i
,06-30 13:05:19.906   903  1482 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:05:19.916   903  1471 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:05:19.966  3829  3945 I art     : Explicit concurrent mark sweep GC freed 15364(853KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 18MB/31MB, paused 417us total 19.908ms
,06-30 13:05:19.966  2259  7384 I EventLogService: Aggregate from 1467282644813 (log), 1467282644813 (data)
,06-30 13:05:20.016   903  1090 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,06-30 13:05:20.016   903  1090 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,06-30 13:05:20.026   903  1090 D SensorManager: unregisterListener ::   
06-30 13:05:20.026   903  1090 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,06-30 13:05:21.306   306   306 E SMD     : DCD ON
,06-30 13:05:24.306   306   306 E SMD     : DCD ON
,06-30 13:05:27.306   306   306 E SMD     : DCD ON
,06-30 13:05:29.066   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:05:29.486   903  1338 E Watchdog: !@Sync 31
,06-30 13:05:29.706   903  1471 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:29.716   903  1471 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:05:29.716   903  1471 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:05:29.716   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:05:29.726  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:05:29.726  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:05:29.726   903   903 I MotionRecognitionService: Plugged
06-30 13:05:29.736   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:05:29.736  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:29.736  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:05:29.736  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:05:29.736  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:05:29.736  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:29.736   903  1471 D BatteryService: stay LED for fully charged
,06-30 13:05:29.746  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:30.306   306   306 E SMD     : DCD ON
,06-30 13:05:33.306   306   306 E SMD     : DCD ON
,06-30 13:05:36.306   306   306 E SMD     : DCD ON
,06-30 13:05:39.126   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:05:39.306   306   306 E SMD     : DCD ON
,06-30 13:05:39.756   903  1317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:39.756   903  1317 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:05:39.756   903  1317 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:05:39.756   903  1317 D BatteryService: stay LED for fully charged
,06-30 13:05:39.756   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:05:39.766  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:05:39.766  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:05:39.766  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:05:39.776   903   903 I MotionRecognitionService: Plugged
,06-30 13:05:39.776   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:05:39.776  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:39.776  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:05:39.776  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:05:39.776  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:39.776  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:42.306   306   306 E SMD     : DCD ON
,06-30 13:05:45.306   306   306 E SMD     : DCD ON
,06-30 13:05:48.306   306   306 E SMD     : DCD ON
,06-30 13:05:49.186   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:05:49.816   903  1448 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:49.816   903  1448 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:05:49.816   903  1448 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:05:49.826   903  1448 D BatteryService: stay LED for fully charged
,06-30 13:05:49.826   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:05:49.826  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:05:49.826  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:05:49.836  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:05:49.836  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:05:49.836   903   903 I MotionRecognitionService: Plugged
,06-30 13:05:49.836   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:05:49.836  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:05:49.836  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:49.836  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:49.836  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:51.316   306   306 E SMD     : DCD ON
,06-30 13:05:54.316   306   306 E SMD     : DCD ON
,06-30 13:05:57.316   306   306 E SMD     : DCD ON
,06-30 13:05:59.236   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:05:59.486   903  1338 E Watchdog: !@Sync 32
,06-30 13:06:00.006   903  1110 V AlarmManager: waitForAlarm result :8
,06-30 13:06:00.046   903  1317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:00.056   903  1317 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:06:00.056   903  1317 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:06:00.056   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:06:00.066  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:06:00.066  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:06:00.066   903   903 I MotionRecognitionService: Plugged
06-30 13:06:00.066   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:06:00.076  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:06:00.076  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:00.076  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:06:00.076  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:06:00.076  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:00.076   903  1317 D BatteryService: stay LED for fully charged
,06-30 13:06:00.086  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:00.316   306   306 E SMD     : DCD ON
,06-30 13:06:03.316   306   306 E SMD     : DCD ON
,06-30 13:06:06.316   306   306 E SMD     : DCD ON
,06-30 13:06:09.286   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:06:09.316   306   306 E SMD     : DCD ON
,06-30 13:06:10.116   903  1448 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:12.316   306   306 E SMD     : DCD ON
,06-30 13:06:14.426   903  1035 I PowerManagerService: [PWL] Off : 950s ago
,06-30 13:06:15.316   306   306 E SMD     : DCD ON
,06-30 13:06:18.316   306   306 E SMD     : DCD ON
,06-30 13:06:19.336   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:06:20.176   903  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:21.316   306   306 E SMD     : DCD ON
,06-30 13:06:24.316   306   306 E SMD     : DCD ON
,06-30 13:06:27.326   306   306 E SMD     : DCD ON
,06-30 13:06:29.386   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:06:29.496   903  1338 E Watchdog: !@Sync 33
,06-30 13:06:30.236   903   919 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:30.326   306   306 E SMD     : DCD ON
,06-30 13:06:33.326   306   306 E SMD     : DCD ON
,06-30 13:06:36.326   306   306 E SMD     : DCD ON
,06-30 13:06:39.326   306   306 E SMD     : DCD ON
,06-30 13:06:39.446   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:06:40.296   903  3050 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:40.306   903  3050 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:06:40.306   903  3050 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:06:40.306   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:06:40.306   903   903 I MotionRecognitionService: Plugged
,06-30 13:06:40.306   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:06:40.306  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:06:40.316  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:06:40.316  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:06:40.316  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:06:40.316  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:06:40.316  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:40.316   903  3050 D BatteryService: stay LED for fully charged
,06-30 13:06:40.326  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:06:40.326  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:42.326   306   306 E SMD     : DCD ON
,06-30 13:06:45.326   306   306 E SMD     : DCD ON
,06-30 13:06:48.326   306   306 E SMD     : DCD ON
,06-30 13:06:49.506   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:06:50.356   903  1368 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:51.326   306   306 E SMD     : DCD ON
,06-30 13:06:54.326   306   306 E SMD     : DCD ON
,06-30 13:06:57.326   306   306 E SMD     : DCD ON
,06-30 13:06:59.496   903  1338 E Watchdog: !@Sync 34
,06-30 13:06:59.556   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:07:00.326   306   306 E SMD     : DCD ON
,06-30 13:07:00.416   903  1448 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:03.326   306   306 E SMD     : DCD ON
,06-30 13:07:06.336   306   306 E SMD     : DCD ON
,06-30 13:07:09.336   306   306 E SMD     : DCD ON
,06-30 13:07:09.606   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:07:10.476   903  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:10.486   903  1730 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:07:10.486   903  1730 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:07:10.486   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:07:10.486   903   903 I MotionRecognitionService: Plugged
,06-30 13:07:10.486   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:07:10.496  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:07:10.496  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:07:10.496   903  1730 D BatteryService: stay LED for fully charged
,06-30 13:07:10.496  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:07:10.496  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:10.496  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:07:10.506  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:07:10.506  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:07:10.506  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:12.336   306   306 E SMD     : DCD ON
,06-30 13:07:15.336   306   306 E SMD     : DCD ON
,06-30 13:07:18.336   306   306 E SMD     : DCD ON
,06-30 13:07:19.646   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:07:20.556   903  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:21.336   306   306 E SMD     : DCD ON
,06-30 13:07:24.336   306   306 E SMD     : DCD ON
,06-30 13:07:27.336   306   306 E SMD     : DCD ON
,06-30 13:07:29.496   903  1338 E Watchdog: !@Sync 35
,06-30 13:07:29.706   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:07:30.336   306   306 E SMD     : DCD ON
,06-30 13:07:30.616   903  3712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:30.616   903  3712 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:07:30.616   903  3712 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:07:30.616   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:07:30.626   903   903 I MotionRecognitionService: Plugged
,06-30 13:07:30.626  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:07:30.626  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:07:30.626   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:07:30.636  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:07:30.636   903  3712 D BatteryService: stay LED for fully charged
,06-30 13:07:30.636  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:30.636  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:30.636  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:07:30.636  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:07:30.636  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:33.336   306   306 E SMD     : DCD ON
,06-30 13:07:36.336   306   306 E SMD     : DCD ON
,06-30 13:07:39.336   306   306 E SMD     : DCD ON
,06-30 13:07:39.766   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:07:40.676   903   919 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:40.686   903   919 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:07:40.686   903   919 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:07:40.686   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:07:40.686   903   903 I MotionRecognitionService: Plugged
,06-30 13:07:40.686   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:07:40.686  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:07:40.696  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:07:40.696  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:07:40.696  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:07:40.696  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:07:40.696   903   919 D BatteryService: stay LED for fully charged
,06-30 13:07:40.706  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:07:40.706  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:40.706  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:42.346   306   306 E SMD     : DCD ON
,06-30 13:07:45.346   306   306 E SMD     : DCD ON
,06-30 13:07:48.346   306   306 E SMD     : DCD ON
,06-30 13:07:49.826   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:07:50.736   903  1649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:51.346   306   306 E SMD     : DCD ON
,06-30 13:07:54.346   306   306 E SMD     : DCD ON
,06-30 13:07:54.436   903  1035 I PowerManagerService: [PWL] Off : 1050s ago
,06-30 13:07:57.346   306   306 E SMD     : DCD ON
,06-30 13:07:59.506   903  1338 E Watchdog: !@Sync 36
,06-30 13:07:59.866   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:08:00.346   306   306 E SMD     : DCD ON
,06-30 13:08:00.796   903  1368 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:03.346   306   306 E SMD     : DCD ON
,06-30 13:08:06.346   306   306 E SMD     : DCD ON
,06-30 13:08:09.346   306   306 E SMD     : DCD ON
,06-30 13:08:09.916   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:08:10.856   903  1448 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:10.866   903  1448 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:08:10.866   903  1448 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:08:10.866   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:08:10.866   903   903 I MotionRecognitionService: Plugged
,06-30 13:08:10.866  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:08:10.866  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:08:10.866   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:08:10.876  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:08:10.876   903  1448 D BatteryService: stay LED for fully charged
,06-30 13:08:10.876  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:10.876  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:10.886  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:08:10.886  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:08:10.896  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:12.346   306   306 E SMD     : DCD ON
,06-30 13:08:15.346   306   306 E SMD     : DCD ON
,06-30 13:08:18.356   306   306 E SMD     : DCD ON
,06-30 13:08:19.966   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:08:20.916   903   920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:20.926   903   920 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:08:20.926   903   920 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:08:20.926   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:08:20.926   903   903 I MotionRecognitionService: Plugged
,06-30 13:08:20.926   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:08:20.936  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:08:20.936  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:08:20.936  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:20.936  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:08:20.936  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:08:20.936   903   920 D BatteryService: stay LED for fully charged
,06-30 13:08:20.936  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:20.946  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:20.946  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:08:21.356   306   306 E SMD     : DCD ON
,06-30 13:08:24.356   306   306 E SMD     : DCD ON
,06-30 13:08:27.356   306   306 E SMD     : DCD ON
,06-30 13:08:29.506   903  1338 E Watchdog: !@Sync 37
,06-30 13:08:30.026   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:08:30.356   306   306 E SMD     : DCD ON
,06-30 13:08:30.976   903  1448 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:30.986   903  1448 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:08:30.986   903  1448 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:08:30.986   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:08:30.986   903   903 I MotionRecognitionService: Plugged
,06-30 13:08:30.986  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:08:30.986  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:08:30.996   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:08:30.996   903  1448 D BatteryService: stay LED for fully charged
,06-30 13:08:30.996  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:08:30.996  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:30.996  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:08:31.006  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:08:31.006  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:31.006  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:33.356   306   306 E SMD     : DCD ON
,06-30 13:08:36.356   306   306 E SMD     : DCD ON
,06-30 13:08:39.356   306   306 E SMD     : DCD ON
,06-30 13:08:40.086   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:08:41.036   903  1317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:41.046   903  1317 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:08:41.046   903  1317 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:08:41.046   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:08:41.046   903   903 I MotionRecognitionService: Plugged
,06-30 13:08:41.046   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:08:41.046  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:08:41.056  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:08:41.056  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:08:41.056  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:08:41.056   903  1317 D BatteryService: stay LED for fully charged
,06-30 13:08:41.056  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:08:41.066  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:41.066  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:08:41.066  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:42.356   306   306 E SMD     : DCD ON
,06-30 13:08:45.356   306   306 E SMD     : DCD ON
,06-30 13:08:48.356   306   306 E SMD     : DCD ON
,06-30 13:08:50.146   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:08:51.096   903  1448 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:51.096   903  1448 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:08:51.096   903  1448 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:08:51.106   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:08:51.106   903   903 I MotionRecognitionService: Plugged
,06-30 13:08:51.106   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:08:51.106  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:08:51.116  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:08:51.116  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:08:51.116  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:08:51.116  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:08:51.116  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:08:51.116   903  1448 D BatteryService: stay LED for fully charged
,06-30 13:08:51.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:51.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:51.356   306   306 E SMD     : DCD ON
,06-30 13:08:54.366   306   306 E SMD     : DCD ON
,06-30 13:08:57.366   306   306 E SMD     : DCD ON
,06-30 13:08:59.506   903  1338 E Watchdog: !@Sync 38
,06-30 13:09:00.186   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:09:00.366   306   306 E SMD     : DCD ON
,06-30 13:09:01.156   903   920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:01.166   903   920 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:09:01.166   903   920 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:09:01.166   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:09:01.166   903   903 I MotionRecognitionService: Plugged
,06-30 13:09:01.166   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:09:01.166  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:09:01.176  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:09:01.176  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:09:01.176   903   920 D BatteryService: stay LED for fully charged
,06-30 13:09:01.176  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:01.176  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
06-30 13:09:01.186  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:09:01.186  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:01.186  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:03.366   306   306 E SMD     : DCD ON
,06-30 13:09:06.366   306   306 E SMD     : DCD ON
,06-30 13:09:09.366   306   306 E SMD     : DCD ON
,06-30 13:09:10.246   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:09:11.216   903  1471 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:11.226   903  1471 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:09:11.226   903  1471 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:09:11.226   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:09:11.226   903   903 I MotionRecognitionService: Plugged
,06-30 13:09:11.226   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:09:11.226  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:09:11.236  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:09:11.236  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:09:11.236  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:09:11.236  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:11.236   903  1471 D BatteryService: stay LED for fully charged
,06-30 13:09:11.246  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:09:11.246  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:11.246  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:09:12.366   306   306 E SMD     : DCD ON
,06-30 13:09:15.366   306   306 E SMD     : DCD ON
,06-30 13:09:18.366   306   306 E SMD     : DCD ON
,06-30 13:09:20.336   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:09:21.276   903   920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:21.366   306   306 E SMD     : DCD ON
,06-30 13:09:24.366   306   306 E SMD     : DCD ON
,06-30 13:09:27.366   306   306 E SMD     : DCD ON
,06-30 13:09:29.506   903  1338 E Watchdog: !@Sync 39
,06-30 13:09:30.376   306   306 E SMD     : DCD ON
,06-30 13:09:30.416   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:09:31.336   903  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:31.336   903  1451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:09:31.346   903  1451 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:09:31.346   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:09:31.346   903   903 I MotionRecognitionService: Plugged
,06-30 13:09:31.346   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:09:31.346  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:09:31.356  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:09:31.356  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:09:31.356  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:09:31.356  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:09:31.356   903  1451 D BatteryService: stay LED for fully charged
,06-30 13:09:31.356  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:31.366  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:31.366  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:33.376   306   306 E SMD     : DCD ON
,06-30 13:09:36.376   306   306 E SMD     : DCD ON
,06-30 13:09:39.376   306   306 E SMD     : DCD ON
,06-30 13:09:39.436   903  1035 I PowerManagerService: [PWL] Off : 1155s ago
,06-30 13:09:40.466   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:09:41.396   903  1258 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:42.376   306   306 E SMD     : DCD ON
,06-30 13:09:45.376   306   306 E SMD     : DCD ON
,06-30 13:09:48.376   306   306 E SMD     : DCD ON
,06-30 13:09:50.506   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:09:51.376   306   306 E SMD     : DCD ON
,06-30 13:09:51.456   903  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:54.376   306   306 E SMD     : DCD ON
,06-30 13:09:56.556   903  1099 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 13:09:56.556   903  1099 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:09:56.566   903  1098 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:09:57.346   903   977 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 13:09:57.376   306   306 E SMD     : DCD ON
,06-30 13:09:57.406   903  1122 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,06-30 13:09:57.416   903  1122 I ApplicationUsage: Updating Usage Statistics in DB @ 1467284997424
,06-30 13:09:57.416   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.416   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.416   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:57.416   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
06-30 13:09:57.416   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
06-30 13:09:57.416   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,06-30 13:09:57.416   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.416   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.416   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.416   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:57.416   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.416   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.416   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.416   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
06-30 13:09:57.416   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,06-30 13:09:57.426   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
06-30 13:09:57.426   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.426   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:57.426   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.426   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:57.426   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.426   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.426   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:57.426   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
06-30 13:09:57.426   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
06-30 13:09:57.426   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,06-30 13:09:57.426   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.426   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.426   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:57.426   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.426   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.426   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.426   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.426   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
06-30 13:09:57.426   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,06-30 13:09:57.426   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
06-30 13:09:57.426   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:57.426   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:57.426   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:57.436   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.436   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.436   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.436   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.436   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:57.436   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.436   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.436   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:57.436   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.436   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.436   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:57.436   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.436   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.436   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:57.436   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.436   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.436   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:57.436   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.436   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.436   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:57.436   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.436   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.436   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.436   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.436   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:57.436   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.436   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.436   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:57.446   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.446   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.446   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:57.446   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.446   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.446   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:57.446   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.446   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.446   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:57.446   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.446   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.446   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.446   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:57.446   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.446   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.446   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.446   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.446   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:57.446   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.446   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.446   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.446   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:57.446   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:57.446   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.446   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.456   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.456   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:57.456   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.456   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.456   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.456   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:57.456   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.456   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.456   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.456   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.456   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.456   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:57.456   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.456   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.456   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:57.456   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:57.456   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.456   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:57.456   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.456   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.456   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:57.456   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.456   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.456   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:57.456   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.456   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.456   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:57.456   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.456   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.456   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.466   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.466   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.466   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:57.466   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:57.466   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.466   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.466   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:57.466   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.466   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.466   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.466   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.466   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.466   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:57.466   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.466   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.466   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:57.466   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.466   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.466   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.466   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.466   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:57.466   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:57.466   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
06-30 13:09:57.466   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.476   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:57.476   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.476   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.476   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:57.476   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.476   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.476   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.476   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.476   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:57.476   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.476   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.476   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:57.476   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.476   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.476   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.476   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.476   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.476   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.476   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:57.476   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.476   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.476   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:57.476   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.476   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.476   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.476   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.476   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.476   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:57.476   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.476   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:57.486   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:57.486   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.486   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:57.486   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.486   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.486   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.486   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.486   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.486   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:57.486   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.486   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.486   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.486   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.486   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:57.486   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.486   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.486   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.486   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.486   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.486   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:57.486   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.486   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.486   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.486   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.486   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.486   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.486   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.486   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.486   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.496   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.496   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:57.496   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.496   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.496   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.496   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.496   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:57.496   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.496   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.496   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.496   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.496   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.496   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.496   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.506   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.506   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.506   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.506   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.506   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.506   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.506   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.506   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.506   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.506   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.506   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.506   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.506   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.506   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.506   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.506   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.506   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.506   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.506   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.506   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.506   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.506   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.506   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.506   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.506   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.506   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.506   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.506   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.516   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.516   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.516   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.516   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.516   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.516   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.516   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.516   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.516   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.516   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.516   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.516   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.516   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.516   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.526   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.526   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.526   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.526   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.526   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.526   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.526   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.526   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.526   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.526   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.526   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.526   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.536   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.536   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.536   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.536   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:57.536   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.536   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.536   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.536   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.536   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.536   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.536   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.536   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.536   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.536   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.546   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.546   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.546   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.546   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.546   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.546   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.546   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.546   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.546   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.546   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.546   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.546   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.546   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.546   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.546   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.546   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.556   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.556   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.556   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.556   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.556   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.556   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.556   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.556   903  1122 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.556   903  1122 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.556   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.556   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.556   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.556   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.556   903  1122 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.556   903  1122 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.556   903  1122 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.556   903  1122 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.556   903  1122 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1467284997567
,06-30 13:09:59.456   903  1099 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 13:09:59.456   903  1099 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:09:59.466   903  1099 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:09:59.476   903  1099 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:09:59.516   903  1338 E Watchdog: !@Sync 40
,06-30 13:10:00.376   306   306 E SMD     : DCD ON
,06-30 13:10:00.556   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:10:01.526   903  3765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:03.376   306   306 E SMD     : DCD ON
,06-30 13:10:06.376   306   306 E SMD     : DCD ON
,06-30 13:10:09.376   306   306 E SMD     : DCD ON
,06-30 13:10:10.606   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:10:11.586   903  1317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:11.596   903  1317 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:10:11.596   903  1317 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:10:11.596   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:10:11.606  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:10:11.606  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:10:11.616   903   903 I MotionRecognitionService: Plugged
,06-30 13:10:11.616   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:10:11.616   903  1317 D BatteryService: stay LED for fully charged
,06-30 13:10:11.616  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:10:11.626  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:11.636  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:10:11.636  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:10:11.646  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:11.646  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:12.386   306   306 E SMD     : DCD ON
,06-30 13:10:15.386   306   306 E SMD     : DCD ON
,06-30 13:10:18.386   306   306 E SMD     : DCD ON
,06-30 13:10:20.656   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:10:21.386   306   306 E SMD     : DCD ON
,06-30 13:10:21.646   903  1471 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:21.656   903  1471 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:10:21.656   903  1471 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:10:21.656   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:10:21.666   903   903 I MotionRecognitionService: Plugged
,06-30 13:10:21.666   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:10:21.666  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:10:21.676  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:10:21.676  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:10:21.676  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:10:21.676  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:10:21.676  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:10:21.676  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:21.676   903  1471 D BatteryService: stay LED for fully charged
,06-30 13:10:21.686  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:24.386   306   306 E SMD     : DCD ON
,06-30 13:10:27.386   306   306 E SMD     : DCD ON
,06-30 13:10:29.516   903  1338 E Watchdog: !@Sync 41
,06-30 13:10:30.386   306   306 E SMD     : DCD ON
,06-30 13:10:30.696   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:10:31.716   903  1317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:31.716   903  1317 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:10:31.716   903  1317 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:10:31.726   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:10:31.726   903   903 I MotionRecognitionService: Plugged
,06-30 13:10:31.726   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:10:31.726  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:10:31.736  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:10:31.736  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:10:31.736  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:31.736  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:10:31.736  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:10:31.736   903  1317 D BatteryService: stay LED for fully charged
06-30 13:10:31.736  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:31.736  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:33.386   306   306 E SMD     : DCD ON
,06-30 13:10:36.386   306   306 E SMD     : DCD ON
,06-30 13:10:39.386   306   306 E SMD     : DCD ON
,06-30 13:10:40.746   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:10:41.776   903  3765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:41.786   903  3765 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:10:41.786   903  3765 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:10:41.786   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:10:41.786   903   903 I MotionRecognitionService: Plugged
,06-30 13:10:41.786  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:10:41.796  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:10:41.796   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:10:41.796  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:10:41.796   903  3765 D BatteryService: stay LED for fully charged
,06-30 13:10:41.796  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:41.796  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
06-30 13:10:41.806  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:10:41.806  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:41.806  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:42.386   306   306 E SMD     : DCD ON
,06-30 13:10:45.386   306   306 E SMD     : DCD ON
,06-30 13:10:48.386   306   306 E SMD     : DCD ON
,06-30 13:10:50.806   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:10:51.396   306   306 E SMD     : DCD ON
,06-30 13:10:51.836   903  1368 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:51.836   903  1368 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:10:51.846   903  1368 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:10:51.846   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:10:51.846   903   903 I MotionRecognitionService: Plugged
,06-30 13:10:51.846   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:10:51.846  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:10:51.856  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:10:51.856  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:10:51.856  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:10:51.856  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:10:51.856   903  1368 D BatteryService: stay LED for fully charged
06-30 13:10:51.856  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:51.876  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:51.876  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:54.396   306   306 E SMD     : DCD ON
,06-30 13:10:57.396   306   306 E SMD     : DCD ON
,06-30 13:10:59.516   903  1338 E Watchdog: !@Sync 42
,06-30 13:11:00.396   306   306 E SMD     : DCD ON
,06-30 13:11:00.886   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:11:01.896   903  3765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:01.896   903  3765 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:11:01.906   903  3765 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:11:01.906   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:11:01.906   903   903 I MotionRecognitionService: Plugged
,06-30 13:11:01.906   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:11:01.906  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:11:01.916  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:11:01.916  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:11:01.916  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:11:01.916   903  3765 D BatteryService: stay LED for fully charged
,06-30 13:11:01.916  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:11:01.916  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
06-30 13:11:01.926  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:11:01.926  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:03.396   306   306 E SMD     : DCD ON
,06-30 13:11:06.396   306   306 E SMD     : DCD ON
,06-30 13:11:09.396   306   306 E SMD     : DCD ON
,06-30 13:11:10.926   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:11:11.956   903  1317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:11.956   903  1317 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:11:11.966   903  1317 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:11:11.966   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:11:11.966   903   903 I MotionRecognitionService: Plugged
,06-30 13:11:11.966   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:11:11.976  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:11:11.976  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:11:11.976  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:11:11.976  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:11:11.976   903  1317 D BatteryService: stay LED for fully charged
,06-30 13:11:11.976  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:11.986  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:11.986  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:11.986  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:11:12.396   306   306 E SMD     : DCD ON
,06-30 13:11:15.396   306   306 E SMD     : DCD ON
,06-30 13:11:18.396   306   306 E SMD     : DCD ON
,06-30 13:11:21.006   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:11:21.396   306   306 E SMD     : DCD ON
,06-30 13:11:22.016   903  1471 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:24.396   306   306 E SMD     : DCD ON
,06-30 13:11:27.406   306   306 E SMD     : DCD ON
,06-30 13:11:29.456   903  1035 I PowerManagerService: [PWL] Off : 1265s ago
,06-30 13:11:29.526   903  1338 E Watchdog: !@Sync 43
,06-30 13:11:30.406   306   306 E SMD     : DCD ON
,06-30 13:11:31.056   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:11:32.076   903  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:32.086   903  1730 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:11:32.086   903  1730 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:11:32.086   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:11:32.086   903   903 I MotionRecognitionService: Plugged
,06-30 13:11:32.086  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:11:32.086   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:11:32.086  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:11:32.096  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:11:32.096  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:11:32.096  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:11:32.096   903  1730 D BatteryService: stay LED for fully charged
,06-30 13:11:32.106  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:32.106  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:32.106  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:33.406   306   306 E SMD     : DCD ON
,06-30 13:11:36.406   306   306 E SMD     : DCD ON
,06-30 13:11:39.406   306   306 E SMD     : DCD ON
,06-30 13:11:41.096   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:11:42.136   903  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:42.146   903  1451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:11:42.146   903  1451 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:11:42.146   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:11:42.146   903   903 I MotionRecognitionService: Plugged
,06-30 13:11:42.146   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:11:42.156  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:11:42.156  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:11:42.156  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:11:42.156  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:11:42.156   903  1451 D BatteryService: stay LED for fully charged
,06-30 13:11:42.156  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:11:42.166  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:42.166  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:11:42.166  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:42.406   306   306 E SMD     : DCD ON
,06-30 13:11:45.406   306   306 E SMD     : DCD ON
,06-30 13:11:48.406   306   306 E SMD     : DCD ON
,06-30 13:11:51.146   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:11:51.406   306   306 E SMD     : DCD ON
,06-30 13:11:52.196   903  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:52.196   903  1730 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:11:52.206   903  1730 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:11:52.206   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:11:52.206   903   903 I MotionRecognitionService: Plugged
,06-30 13:11:52.206   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:11:52.206  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:11:52.216  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:11:52.216  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:11:52.216  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:11:52.216  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:11:52.216  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:11:52.216   903  1730 D BatteryService: stay LED for fully charged
,06-30 13:11:52.226  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:52.226  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:54.406   306   306 E SMD     : DCD ON
,06-30 13:11:57.406   306   306 E SMD     : DCD ON
,06-30 13:11:59.526   903  1338 E Watchdog: !@Sync 44
,06-30 13:12:00.406   306   306 E SMD     : DCD ON
,06-30 13:12:01.196   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:12:02.256   903  1448 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:02.256   903  1448 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:12:02.256   903  1448 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:12:02.266   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:12:02.266   903   903 I MotionRecognitionService: Plugged
,06-30 13:12:02.266   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:12:02.266  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:12:02.276  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:12:02.276  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:12:02.276  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:12:02.276  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:12:02.276  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
06-30 13:12:02.276   903  1448 D BatteryService: stay LED for fully charged
06-30 13:12:02.276  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:02.276  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:03.416   306   306 E SMD     : DCD ON
,06-30 13:12:06.416   306   306 E SMD     : DCD ON
,06-30 13:12:09.416   306   306 E SMD     : DCD ON
,06-30 13:12:11.246   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:12:12.316   903   920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:12.316   903   920 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:12:12.326   903   920 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:12:12.326   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:12:12.326   903   903 I MotionRecognitionService: Plugged
,06-30 13:12:12.326  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:12:12.326   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:12:12.326  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:12:12.336  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:12:12.336  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:12:12.336  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:12:12.336  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:12.336   903   920 D BatteryService: stay LED for fully charged
,06-30 13:12:12.346  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:12.346  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:12.416   306   306 E SMD     : DCD ON
,06-30 13:12:15.416   306   306 E SMD     : DCD ON
,06-30 13:12:18.416   306   306 E SMD     : DCD ON
,06-30 13:12:21.286   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:12:21.416   306   306 E SMD     : DCD ON
,06-30 13:12:22.376   903  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:24.416   306   306 E SMD     : DCD ON
,06-30 13:12:27.416   306   306 E SMD     : DCD ON
,06-30 13:12:29.526   903  1338 E Watchdog: !@Sync 45
,06-30 13:12:30.416   306   306 E SMD     : DCD ON
,06-30 13:12:31.336   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:12:32.436   903  3712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:32.446   903  3712 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:12:32.446   903  3712 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:12:32.446   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:12:32.446   903   903 I MotionRecognitionService: Plugged
,06-30 13:12:32.446   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:12:32.446  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:12:32.456  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:12:32.456  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:12:32.456   903  3712 D BatteryService: stay LED for fully charged
,06-30 13:12:32.456  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:32.456  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:12:32.456  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:12:32.466  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:32.466  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:33.416   306   306 E SMD     : DCD ON
,06-30 13:12:36.416   306   306 E SMD     : DCD ON
,06-30 13:12:39.426   306   306 E SMD     : DCD ON
,06-30 13:12:41.386   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:12:42.426   306   306 E SMD     : DCD ON
,06-30 13:12:42.496   903   919 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:42.496   903   919 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:12:42.506   903   919 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:12:42.506   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:12:42.506   903   903 I MotionRecognitionService: Plugged
,06-30 13:12:42.506   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:12:42.506  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:12:42.516  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:12:42.516  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:12:42.516   903   919 D BatteryService: stay LED for fully charged
06-30 13:12:42.516  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:42.516  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:12:42.516  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:12:42.526  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:12:42.526  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:45.426   306   306 E SMD     : DCD ON
,06-30 13:12:48.426   306   306 E SMD     : DCD ON
,06-30 13:12:51.426   306   306 E SMD     : DCD ON
,06-30 13:12:51.466   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:12:52.556   903  1258 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:52.566   903  1258 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:12:52.566   903  1258 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:12:52.566   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:12:52.566   903   903 I MotionRecognitionService: Plugged
,06-30 13:12:52.566   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:12:52.566  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:12:52.576  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:12:52.576  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:12:52.576  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:12:52.576  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:12:52.576   903  1258 D BatteryService: stay LED for fully charged
,06-30 13:12:52.576  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:52.586  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:52.586  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:54.426   306   306 E SMD     : DCD ON
,06-30 13:12:57.426   306   306 E SMD     : DCD ON
,06-30 13:12:59.536   903  1338 E Watchdog: !@Sync 46
,06-30 13:13:00.426   306   306 E SMD     : DCD ON
,06-30 13:13:01.516   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:13:02.616   903  1141 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:02.616   903  1141 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:13:02.616   903  1141 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:13:02.626   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:13:02.626   903   903 I MotionRecognitionService: Plugged
,06-30 13:13:02.626   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:13:02.626  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:13:02.636  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:13:02.636  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:13:02.636  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:13:02.636  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:13:02.636  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:13:02.636   903  1141 D BatteryService: stay LED for fully charged
,06-30 13:13:02.636  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:02.646  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:03.426   306   306 E SMD     : DCD ON
,06-30 13:13:06.426   306   306 E SMD     : DCD ON
,06-30 13:13:09.426   306   306 E SMD     : DCD ON
,06-30 13:13:11.566   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:13:12.426   306   306 E SMD     : DCD ON
,06-30 13:13:12.676   903  3712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:15.426   306   306 E SMD     : DCD ON
,06-30 13:13:18.436   306   306 E SMD     : DCD ON
,06-30 13:13:21.436   306   306 E SMD     : DCD ON
,06-30 13:13:21.606   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:13:22.736   903  1259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:22.746   903  1259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:13:22.746   903  1259 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:13:22.746   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:13:22.746   903   903 I MotionRecognitionService: Plugged
,06-30 13:13:22.746   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:13:22.756  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:13:22.756  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:13:22.756   903  1259 D BatteryService: stay LED for fully charged
,06-30 13:13:22.756  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:13:22.756  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:22.756  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:13:22.756  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
06-30 13:13:22.766  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:22.766  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:24.436   306   306 E SMD     : DCD ON
,06-30 13:13:24.456   903  1035 I PowerManagerService: [PWL] Off : 1380s ago
,06-30 13:13:27.436   306   306 E SMD     : DCD ON
,06-30 13:13:29.536   903  1338 E Watchdog: !@Sync 47
,06-30 13:13:30.436   306   306 E SMD     : DCD ON
,06-30 13:13:31.656   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:13:32.796   903  3050 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:32.796   903  3050 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:13:32.806   903  3050 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:13:32.806   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:13:32.806   903   903 I MotionRecognitionService: Plugged
,06-30 13:13:32.806   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:13:32.806  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:13:32.816  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:13:32.816  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:13:32.816  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:13:32.816  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:13:32.816   903  3050 D BatteryService: stay LED for fully charged
,06-30 13:13:32.826  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:32.836  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:32.836  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:33.436   306   306 E SMD     : DCD ON
,06-30 13:13:36.436   306   306 E SMD     : DCD ON
,06-30 13:13:39.436   306   306 E SMD     : DCD ON
,06-30 13:13:41.706   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:13:42.436   306   306 E SMD     : DCD ON
,06-30 13:13:42.856   903  1259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:45.436   306   306 E SMD     : DCD ON
,06-30 13:13:48.436   306   306 E SMD     : DCD ON
,06-30 13:13:51.436   306   306 E SMD     : DCD ON
,06-30 13:13:51.786   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:13:52.916   903  1471 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:54.446   306   306 E SMD     : DCD ON
,06-30 13:13:57.446   306   306 E SMD     : DCD ON
,06-30 13:13:59.536   903  1338 E Watchdog: !@Sync 48
,06-30 13:14:00.446   306   306 E SMD     : DCD ON
,06-30 13:14:01.836   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:14:02.966   903  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:03.446   306   306 E SMD     : DCD ON
,06-30 13:14:06.446   306   306 E SMD     : DCD ON
,06-30 13:14:09.446   306   306 E SMD     : DCD ON
,06-30 13:14:11.876   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:14:12.446   306   306 E SMD     : DCD ON
,06-30 13:14:13.036   903   919 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:15.446   306   306 E SMD     : DCD ON
,06-30 13:14:18.446   306   306 E SMD     : DCD ON
,06-30 13:14:21.446   306   306 E SMD     : DCD ON
,06-30 13:14:21.956   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:14:23.096   903  1649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:23.106   903  1649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:14:23.106   903  1649 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:14:23.106   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:14:23.106   903   903 I MotionRecognitionService: Plugged
,06-30 13:14:23.106   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:14:23.116  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:14:23.116  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:14:23.116   903  1649 D BatteryService: stay LED for fully charged
06-30 13:14:23.116  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:14:23.116  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:14:23.116  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:14:23.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:23.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:23.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:24.446   306   306 E SMD     : DCD ON
,06-30 13:14:27.446   306   306 E SMD     : DCD ON
,06-30 13:14:29.536   903  1338 E Watchdog: !@Sync 49
,06-30 13:14:30.456   306   306 E SMD     : DCD ON
,06-30 13:14:31.996   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:14:33.156   903  1259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:33.166   903  1259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:14:33.166   903  1259 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:14:33.166   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:14:33.166   903   903 I MotionRecognitionService: Plugged
,06-30 13:14:33.166   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:14:33.166  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:14:33.176  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:14:33.176   903  1259 D BatteryService: stay LED for fully charged
,06-30 13:14:33.176  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:14:33.176  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:14:33.176  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:14:33.186  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:33.186  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:14:33.186  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:33.456   306   306 E SMD     : DCD ON
,06-30 13:14:36.456   306   306 E SMD     : DCD ON
,06-30 13:14:39.456   306   306 E SMD     : DCD ON
,06-30 13:14:42.046   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:14:42.456   306   306 E SMD     : DCD ON
,06-30 13:14:43.216   903  1649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:45.456   306   306 E SMD     : DCD ON
,06-30 13:14:48.456   306   306 E SMD     : DCD ON
,06-30 13:14:51.456   306   306 E SMD     : DCD ON
,06-30 13:14:52.096   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:14:53.276   903  1368 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:53.276   903  1368 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:14:53.286   903  1368 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:14:53.286   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:14:53.286   903   903 I MotionRecognitionService: Plugged
,06-30 13:14:53.286   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:14:53.286  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:14:53.296  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:14:53.296  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:14:53.296   903  1368 D BatteryService: stay LED for fully charged
,06-30 13:14:53.296  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:53.296  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:53.296  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:14:53.296  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
06-30 13:14:53.306  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:54.456   306   306 E SMD     : DCD ON
,06-30 13:14:56.556   903  1099 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 13:14:56.556   903  1099 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:14:56.566   903  1098 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:14:57.456   306   306 E SMD     : DCD ON
,06-30 13:14:59.396   903  1099 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 13:14:59.396   903  1099 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:14:59.406   903  1099 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:14:59.416   903  1099 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:14:59.546   903  1338 E Watchdog: !@Sync 50
,06-30 13:15:00.456   306   306 E SMD     : DCD ON
,06-30 13:15:02.136   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:15:03.336   903  1471 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:15:03.346   903  1471 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:15:03.346   903  1471 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:15:03.346   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:15:03.346   903   903 I MotionRecognitionService: Plugged
,06-30 13:15:03.346   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:15:03.346  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:15:03.356  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:15:03.356  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:15:03.356   903  1471 D BatteryService: stay LED for fully charged
,06-30 13:15:03.356  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:03.356  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:15:03.356  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:15:03.366  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:03.366  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:03.456   306   306 E SMD     : DCD ON
,06-30 13:15:06.456   306   306 E SMD     : DCD ON
,06-30 13:15:09.466   306   306 E SMD     : DCD ON
,06-30 13:15:12.186   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:15:12.466   306   306 E SMD     : DCD ON
,06-30 13:15:13.396   903  1317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:15:13.406   903  1317 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:15:13.406   903  1317 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:15:13.406   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:15:13.406   903   903 I MotionRecognitionService: Plugged
,06-30 13:15:13.406   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:15:13.406  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:15:13.416  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:15:13.416  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:15:13.416  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:15:13.416  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:15:13.416   903  1317 D BatteryService: stay LED for fully charged
,06-30 13:15:13.426  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:13.426  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:13.426  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:15.466   306   306 E SMD     : DCD ON
,06-30 13:15:18.466   306   306 E SMD     : DCD ON
,06-30 13:15:21.466   306   306 E SMD     : DCD ON
,06-30 13:15:22.236   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:15:23.456   903  3765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:15:23.456   903  3765 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:15:23.456   903  3765 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:15:23.466   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:15:23.466   903   903 I MotionRecognitionService: Plugged
,06-30 13:15:23.466   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:15:23.466  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:15:23.476  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:15:23.476  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:15:23.476  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:15:23.476  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:15:23.476  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:23.486  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:23.486  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:15:23.486   903  3765 D BatteryService: stay LED for fully charged
,06-30 13:15:24.456   903  1035 I PowerManagerService: [PWL] Off : 1500s ago
,06-30 13:15:24.466   306   306 E SMD     : DCD ON
,06-30 13:15:27.466   306   306 E SMD     : DCD ON
,06-30 13:15:29.546   903  1338 E Watchdog: !@Sync 51
,06-30 13:15:30.466   306   306 E SMD     : DCD ON
,06-30 13:15:32.286   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:15:33.466   306   306 E SMD     : DCD ON
,06-30 13:15:33.516   903  1368 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:15:33.526   903  1368 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:15:33.526   903  1368 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:15:33.526   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:15:33.526   903   903 I MotionRecognitionService: Plugged
,06-30 13:15:33.526   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:15:33.526  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:15:33.536  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:15:33.536  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:15:33.536   903  1368 D BatteryService: stay LED for fully charged
,06-30 13:15:33.536  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:33.536  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:33.536  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:15:33.546  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:15:33.546  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:36.466   306   306 E SMD     : DCD ON
,06-30 13:15:39.466   306   306 E SMD     : DCD ON
,06-30 13:15:42.326   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:15:42.466   306   306 E SMD     : DCD ON
,06-30 13:15:43.576   903  1471 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:15:43.586   903  1471 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:15:43.586   903  1471 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:15:43.586   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:15:43.586   903   903 I MotionRecognitionService: Plugged
,06-30 13:15:43.586   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:15:43.586  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:15:43.596  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:15:43.596  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:15:43.596  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:15:43.596  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:15:43.596   903  1471 D BatteryService: stay LED for fully charged
,06-30 13:15:43.596  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:43.606  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:43.606  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:45.476   306   306 E SMD     : DCD ON
,06-30 13:15:48.476   306   306 E SMD     : DCD ON
,06-30 13:15:51.476   306   306 E SMD     : DCD ON
,06-30 13:15:52.396   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:15:53.636   903  1317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:15:53.646   903  1317 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:15:53.646   903  1317 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:15:53.646   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:15:53.646   903   903 I MotionRecognitionService: Plugged
,06-30 13:15:53.646   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:15:53.656  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:15:53.656  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:15:53.656  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:15:53.656   903  1317 D BatteryService: stay LED for fully charged
,06-30 13:15:53.656  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:53.656  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:15:53.656  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:15:53.666  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:53.666  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:54.476   306   306 E SMD     : DCD ON
,06-30 13:15:57.476   306   306 E SMD     : DCD ON
,06-30 13:15:59.546   903  1338 E Watchdog: !@Sync 52
,06-30 13:16:00.476   306   306 E SMD     : DCD ON
,06-30 13:16:02.446   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:16:03.476   306   306 E SMD     : DCD ON
,06-30 13:16:03.696   903  3765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:16:06.476   306   306 E SMD     : DCD ON
,06-30 13:16:09.476   306   306 E SMD     : DCD ON
,06-30 13:16:12.476   306   306 E SMD     : DCD ON
,06-30 13:16:12.496   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:16:13.756   903  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:16:13.756   903  1730 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:16:13.766   903  1730 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:16:13.766   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:16:13.766   903   903 I MotionRecognitionService: Plugged
,06-30 13:16:13.766   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:16:13.766  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:16:13.766  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:16:13.776  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:16:13.776  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:16:13.776  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:16:13.776   903  1730 D BatteryService: stay LED for fully charged
,06-30 13:16:13.786  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:16:13.786  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:16:13.786  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:16:15.476   306   306 E SMD     : DCD ON
,06-30 13:16:18.476   306   306 E SMD     : DCD ON
,06-30 13:16:21.476   306   306 E SMD     : DCD ON
,06-30 13:16:22.566   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:16:23.816   903  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:16:24.486   306   306 E SMD     : DCD ON
,06-30 13:16:27.486   306   306 E SMD     : DCD ON
,06-30 13:16:29.546   903  1338 E Watchdog: !@Sync 53
,06-30 13:16:30.486   306   306 E SMD     : DCD ON
,06-30 13:16:32.646   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:16:33.486   306   306 E SMD     : DCD ON
,06-30 13:16:33.876   903  3712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:16:33.876   903  3712 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:16:33.886   903  3712 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:16:33.886   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:16:33.886   903   903 I MotionRecognitionService: Plugged
,06-30 13:16:33.886   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:16:33.886  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:16:33.896  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:16:33.896  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:16:33.896  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:16:33.896   903  3712 D BatteryService: stay LED for fully charged
,06-30 13:16:33.896  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:16:33.896  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:16:33.906  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:16:33.906  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:16:36.486   306   306 E SMD     : DCD ON
,06-30 13:16:39.486   306   306 E SMD     : DCD ON
,06-30 13:16:42.486   306   306 E SMD     : DCD ON
,06-30 13:16:42.686   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:16:43.936   903   919 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:16:45.486   306   306 E SMD     : DCD ON
,06-30 13:16:48.486   306   306 E SMD     : DCD ON
,06-30 13:16:51.486   306   306 E SMD     : DCD ON
,06-30 13:16:52.746   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:16:53.996   903  1649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:16:53.996   903  1649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:16:53.996   903  1649 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:16:54.006   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:16:54.006   903   903 I MotionRecognitionService: Plugged
,06-30 13:16:54.006   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:16:54.006  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:16:54.016  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:16:54.016  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:16:54.016  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:16:54.016  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:16:54.016  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:16:54.016   903  1649 D BatteryService: stay LED for fully charged
,06-30 13:16:54.026  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:16:54.026  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:16:54.486   306   306 E SMD     : DCD ON
,06-30 13:16:57.486   306   306 E SMD     : DCD ON
,06-30 13:16:59.556   903  1338 E Watchdog: !@Sync 54
,06-30 13:17:00.496   306   306 E SMD     : DCD ON
,06-30 13:17:02.806   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:17:03.496   306   306 E SMD     : DCD ON
,06-30 13:17:04.056   903  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:17:06.496   306   306 E SMD     : DCD ON
,06-30 13:17:09.496   306   306 E SMD     : DCD ON
,06-30 13:17:12.496   306   306 E SMD     : DCD ON
,06-30 13:17:12.846   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:17:14.116   903  3765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:17:15.496   306   306 E SMD     : DCD ON
,06-30 13:17:18.496   306   306 E SMD     : DCD ON
,06-30 13:17:21.496   306   306 E SMD     : DCD ON
,06-30 13:17:22.896   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:17:24.176   903   920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:17:24.496   306   306 E SMD     : DCD ON
,06-30 13:17:27.496   306   306 E SMD     : DCD ON
,06-30 13:17:29.456   903  1035 I PowerManagerService: [PWL] Off : 1625s ago
,06-30 13:17:29.556   903  1338 E Watchdog: !@Sync 55
,06-30 13:17:30.496   306   306 E SMD     : DCD ON
,06-30 13:17:32.946   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:17:33.496   306   306 E SMD     : DCD ON
,06-30 13:17:34.236   903  1141 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:17:36.506   306   306 E SMD     : DCD ON
,06-30 13:17:39.506   306   306 E SMD     : DCD ON
,06-30 13:17:42.506   306   306 E SMD     : DCD ON
,06-30 13:17:42.996   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:17:44.296   903  1649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:17:44.296   903  1649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:17:44.306   903  1649 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:17:44.306   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:17:44.306   903   903 I MotionRecognitionService: Plugged
,06-30 13:17:44.306   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:17:44.316  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:17:44.316  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:17:44.316  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:17:44.316  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:17:44.316   903  1649 D BatteryService: stay LED for fully charged
,06-30 13:17:44.316  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:17:44.326  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:17:44.326  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:17:44.326  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:17:45.506   306   306 E SMD     : DCD ON
,06-30 13:17:48.506   306   306 E SMD     : DCD ON
,06-30 13:17:51.506   306   306 E SMD     : DCD ON
,06-30 13:17:53.046   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:17:54.356   903  1259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:17:54.506   306   306 E SMD     : DCD ON
,06-30 13:17:57.506   306   306 E SMD     : DCD ON
,06-30 13:17:59.556   903  1338 E Watchdog: !@Sync 56
,06-30 13:18:00.506   306   306 E SMD     : DCD ON
,06-30 13:18:03.106   903  3071 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 13:18:03.506   306   306 E SMD     : DCD ON
,06-30 13:18:04.416   903  1471 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:18:04.416   903  1471 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:18:04.426   903  1471 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:18:04.426   903   903 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:18:04.426   903   903 I MotionRecognitionService: Plugged
,06-30 13:18:04.426   903   903 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:18:04.436  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:18:04.436  3007  3007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:18:04.436  3007  3223 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:18:04.436  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:18:04.436  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:18:04.436   903  1471 D BatteryService: stay LED for fully charged
,06-30 13:18:04.446  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:18:04.446  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:18:04.446  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,TIME-OUT KILL (timeout was 1400000ms),06-30 13:18:04.936  7437  7437 D AndroidRuntime: 
06-30 13:18:04.936  7437  7437 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 13:18:04.936  7437  7437 D AndroidRuntime: CheckJNI is OFF
06-30 13:18:04.936  7437  7437 D AndroidRuntime: readGMSProperty: start
06-30 13:18:04.936  7437  7437 D AndroidRuntime: readGMSProperty: already setted!!
06-30 13:18:04.946  7437  7437 D AndroidRuntime: readGMSProperty: end
06-30 13:18:04.946  7437  7437 D AndroidRuntime: addProductProperty: start
06-30 13:18:05.116  7437  7437 E AffinityControl: AffinityControl: registerfunction enter
06-30 13:18:05.136  7437  7437 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 13:18:05.146   903  3712 D PackageManager: START PACKAGE DELETE: observer{1071534721}
06-30 13:18:05.146   903  3712 D PackageManager: pkg{<packageName>}
06-30 13:18:05.146   903  3712 D PackageManager: user{0}
06-30 13:18:05.146   903  3712 D PackageManager: caller{2000}
06-30 13:18:05.146   903  3712 D PackageManager: flags{2}
06-30 13:18:05.146   903  3712 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
06-30 13:18:05.146   903  3712 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-30 13:18:05.146   903  3712 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-30 13:18:05.146   903  3712 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 13:18:05.146   903  3712 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 13:18:05.146   903  1051 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-30 13:18:05.146   903  1051 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
06-30 13:18:05.146   903  1051 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
06-30 13:18:05.146   903  1051 D ApplicationPolicy: getApplicationUninstallationEnabled
06-30 13:18:05.146   903  1051 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
06-30 13:18:05.146   903  1051 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
06-30 13:18:05.146   903   981 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
06-30 13:18:05.146   903   981 I ActivityManager: Killing 7241:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
06-30 13:18:05.156   903   981 I ActivityManager:   Force finishing activity ActivityRecord{1e149fbb u0 com.test.thalitest/.MainActivity t23}
06-30 13:18:05.156   903   981 D FocusedStackFrame: Set to : 0
06-30 13:18:05.156   266  1699 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
06-30 13:18:05.156   266  1948 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
06-30 13:18:05.356   903  3071 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:18:05.366   903  1051 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
06-30 13:18:05.396  1608  1608 I art     : Explicit concurrent mark sweep GC freed 477(31KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 19MB/32MB, paused 397us total 26.993ms
06-30 13:18:05.416  5123  5123 I art     : Explicit concurrent mark sweep GC freed 32756(1818KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 15MB/26MB, paused 10.434ms total 35.496ms
06-30 13:18:05.436   903  3318 E libprocessgroup: failed to kill 1 processes for processgroup 7241
06-30 13:18:05.436  7097  7097 I art     : Explicit concurrent mark sweep GC freed 6541(419KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 16MB/21MB, paused 453us total 64.652ms
06-30 13:18:05.436  7037  7037 I art     : Explicit concurrent mark sweep GC freed 2168(128KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 581us total 50.510ms
06-30 13:18:05.446   903  1031 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
06-30 13:18:05.446  4934  4934 I art     : Explicit concurrent mark sweep GC freed 853(47KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 314us total 79.495ms
06-30 13:18:05.456   903  1116 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-30 13:18:05.456  1459  1459 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
06-30 13:18:05.456  1459  1459 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 13:18:05.456  2010  2374 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-30 13:18:05.456  1459  1459 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
06-30 13:18:05.456  1419  1419 D RegisteredServicesCache: empty dynamic service
06-30 13:18:05.466  1459  1459 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
06-30 13:18:05.466  1688  1688 E SamsungIME: mOCRHelper is null
06-30 13:18:05.466  1459  1459 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 13:18:05.466  1459  1459 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 13:18:05.466  1459  1459 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
06-30 13:18:05.466  4354  4354 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
06-30 13:18:05.466   903  1143 V NetworkStats: removeUidsLocked() for UIDs [10079]
06-30 13:18:05.466   903  1143 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:18:05.466   903  1143 V NetworkStats: performPollLocked(flags=0x3)
06-30 13:18:05.466  4354  4354 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1467285485482
06-30 13:18:05.476   903  1143 D NetworkStatsFactory: UpdateStatsForKnox
06-30 13:18:05.476   903  1143 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:18:05.476  1459  1459 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
06-30 13:18:05.476  1459  1459 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 13:18:05.476  1459  1459 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
06-30 13:18:05.476   903  1143 V NetworkStats: performPollLocked() took 8ms
06-30 13:18:05.476   903  1143 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:18:05.476   903  1144 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:18:05.476   903  1144 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:18:05.506  4354  4354 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
06-30 13:18:05.516  6071  6071 I art     : Explicit concurrent mark sweep GC freed 20343(2MB) AllocSpace objects, 2(40KB) LOS objects, 31% free, 17MB/25MB, paused 447us total 90.243ms
06-30 13:18:05.516  4354  4354 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
06-30 13:18:05.576   903   903 I art     : Explicit concurrent mark sweep GC freed 76553(7MB) AllocSpace objects, 240(3MB) LOS objects, 30% free, 35MB/51MB, paused 1.952ms total 192.050ms
06-30 13:18:05.576   903   903 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
06-30 13:18:05.576   903  1051 I art     : WaitForGcToComplete blocked for 114.552ms for cause Explicit
06-30 13:18:05.596   903   903 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
06-30 13:18:05.606   903   903 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
06-30 13:18:05.606   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
06-30 13:18:05.606   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
06-30 13:18:05.616   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
06-30 13:18:05.626   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
06-30 13:18:05.636   903  3712 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
06-30 13:18:05.636   903  3712 D SecContentProvider2: mCursor = null
06-30 13:18:05.646   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
06-30 13:18:05.646   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
06-30 13:18:05.666   903   903 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
06-30 13:18:05.666   903   903 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
06-30 13:18:05.676   903   903 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
06-30 13:18:05.686   903   903 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
06-30 13:18:05.686   903   903 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
06-30 13:18:05.696   903   903 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
06-30 13:18:05.696   903   903 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
06-30 13:18:05.706   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
06-30 13:18:05.706   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
06-30 13:18:05.706   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
06-30 13:18:05.716   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
06-30 13:18:05.716   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
06-30 13:18:05.716   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
06-30 13:18:05.726   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
06-30 13:18:05.726   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
06-30 13:18:05.736  4354  4354 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
06-30 13:18:05.736   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
06-30 13:18:05.736   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
06-30 13:18:05.736   903   903 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
06-30 13:18:05.746   903   903 D RCPManagerService: PackageReceiver onReceive()
06-30 13:18:05.746   903   903 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
06-30 13:18:05.746   903   903 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
06-30 13:18:05.746   903   903 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 13:18:05.746   903   903 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-30 13:18:05.756   903   903 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
06-30 13:18:05.756   903   903 V EnterpriseBillingPolicy: uID is 10079
06-30 13:18:05.756   903   903 V EnterpriseBillingPolicy: Removed Packageuid is0
06-30 13:18:05.756   903   903 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
06-30 13:18:05.756   903   903 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
06-30 13:18:05.756   903   903 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-30 13:18:05.756   903   903 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-30 13:18:05.756   903   903 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
06-30 13:18:05.756   903   903 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
06-30 13:18:05.756  4354  4354 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
06-30 13:18:05.756   903  3071 D SSRM:aY : MSG_TYPE_APP_REMOVED::
06-30 13:18:05.756   903  1176 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
06-30 13:18:05.756  6609  6609 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
06-30 13:18:05.756   903  1451 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
06-30 13:18:05.756   903  1451 D ActivityManager: caller:android.app.ApplicationThreadProxy@2dc99096, r.packageName :com.sec.esdk.elm
06-30 13:18:05.766   903   903 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
06-30 13:18:05.766  6609  6609 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
06-30 13:18:05.766  3617  3617 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
06-30 13:18:05.766  3617  3617 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 13:18:05.766  3617  3617 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
06-30 13:18:05.766  3617  3617 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
06-30 13:18:05.766  3617  3617 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
06-30 13:18:05.766  3617  3617 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
06-30 13:18:05.766  3617  3617 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
06-30 13:18:05.766  3617  3617 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:18:05.766  3617  3617 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:18:05.766  3617  3617 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 13:18:05.766  3617  3617 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:18:05.766  3617  3617 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:18:05.766  3617  3617 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 13:18:05.766  3617  3617 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 13:18:05.776  6609  6609 D elm:14491: ElmAgentService : onCreate()
06-30 13:18:05.776  6609  7465 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
06-30 13:18:05.776  6609  7465 D elm:14491: MainReceiver.listeningToPackageRemoved()
06-30 13:18:05.776  6609  7465 D elm:14491: MDMBridge.getInstance()
06-30 13:18:05.776  6609  7465 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
06-30 13:18:05.776  6609  7465 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
06-30 13:18:05.776  3829  3829 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
06-30 13:18:05.776  3829  3829 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
06-30 13:18:05.786   903   920 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:18:05.786  6609  6609 D elm:14491: ElmAgentService : onDestroy().
06-30 13:18:05.786   903  1110 V AlarmManager: waitForAlarm result :8
06-30 13:18:05.796   903  1141 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 13:18:05.806   903  1141 D ActivityManager: caller:android.app.ApplicationThreadProxy@76ea004, r.packageName :com.google.android.gms
06-30 13:18:05.816  2259  7467 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
06-30 13:18:05.816  2259  2259 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
06-30 13:18:05.816  2259  2259 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
06-30 13:18:05.816  2259  2259 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-30 13:18:05.816  2259  2259 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
06-30 13:18:05.816  2259  7467 D AccountUtils: Clearing selected account for com.test.thalitest
06-30 13:18:05.816   903  1448 D ActivityManager: caller:android.app.ApplicationThreadProxy@2e37b870, r.packageName :com.google.android.gms
06-30 13:18:05.826  2259  2259 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
06-30 13:18:05.826  2259  2259 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
06-30 13:18:05.826  2259  2259 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-30 13:18:05.826  2259  2259 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
06-30 13:18:05.826   903  1451 D ActivityManager: caller:android.app.ApplicationThreadProxy@248a1c6e, r.packageName :com.google.android.gms
06-30 13:18:05.826   903  1482 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 13:18:05.826   903  1482 D ActivityManager: caller:android.app.ApplicationThreadProxy@3f37eb9c, r.packageName :com.google.android.gms
06-30 13:18:05.836  2259  7467 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
06-30 13:18:05.836   903  1051 I art     : Explicit concurrent mark sweep GC freed 13374(707KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 35MB/51MB, paused 4.290ms total 251.736ms
06-30 13:18:05.836   903  1259 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
06-30 13:18:05.856  6859  6859 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
06-30 13:18:05.856  6859  6859 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
06-30 13:18:05.856  6859  6859 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
06-30 13:18:05.856   903  1368 D ActivityManager: caller:android.app.ApplicationThreadProxy@17749107, r.packageName :com.google.android.gms
06-30 13:18:05.866   903  3050 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 13:18:05.866   903  3050 D ActivityManager: caller:android.app.ApplicationThreadProxy@213f36a3, r.packageName :com.google.android.gms
06-30 13:18:05.876  6874  6874 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
06-30 13:18:05.876  6874  6874 I PCWCLIENTTRACE_PushUtil: sales region : global
06-30 13:18:05.876  6874  6874 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
06-30 13:18:05.876  6874  6874 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
06-30 13:18:05.886  2259  7473 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
06-30 13:18:05.886  2259  7473 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
06-30 13:18:05.886  2259  7473 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
06-30 13:18:05.886  2259  7473 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
06-30 13:18:05.896   903  1471 D ActivityManager: startService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.sec.android.app.shealth
06-30 13:18:05.896   903  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@16cd8d59, r.packageName :com.sec.android.app.shealth
06-30 13:18:05.916  2259  7473 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
06-30 13:18:05.916  2259  7473 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
06-30 13:18:05.916  2259  7473 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
06-30 13:18:05.926   903  1448 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 13:18:05.926   903  1448 D ActivityManager: caller:android.app.ApplicationThreadProxy@398499ff, r.packageName :com.google.android.gms
06-30 13:18:05.936  3829  3829 I ConfigService: onCreate
06-30 13:18:05.936  3829  3829 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-30 13:18:05.936   903  1448 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 13:18:05.936   903  1448 D ActivityManager: caller:android.app.ApplicationThreadProxy@3bf200b8, r.packageName :com.google.android.gms
06-30 13:18:05.946   903  3050 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 13:18:05.946   903  3050 D ActivityManager: caller:android.app.ApplicationThreadProxy@34227064, r.packageName :com.google.android.gms
06-30 13:18:05.946  2259  2259 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
06-30 13:18:05.946  2259  7473 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
06-30 13:18:05.946  2259  7473 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
06-30 13:18:05.946  2259  7475 W BaseAppContext: Using Auth Proxy for data requests.
06-30 13:18:05.946  3829  3829 I ConfigService: onBind returning update interface
06-30 13:18:05.946   903  1258 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 13:18:05.956   903  1258 D ActivityManager: caller:android.app.ApplicationThreadProxy@14e05782, r.packageName :com.google.android.gms
06-30 13:18:05.956   903  1730 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
06-30 13:18:05.956  3829  3829 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-30 13:18:05.956  3829  3829 I ConfigService: onBind returning service broker
06-30 13:18:05.956   903  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:18:05.956   903  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:18:05.956   903  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:18:05.956   903  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:18:05.956  2259  7473 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
06-30 13:18:05.966  2259  7479 I PeopleContactsSync: CP2 sync disabled
06-30 13:18:05.966   903  1051 D PackageManager: delete codoeFile: 
06-30 13:18:05.976   903  1051 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
06-30 13:18:05.976   903  1051 I AASA_removePackage: UID=10079 Target=com.test.thalitest
06-30 13:18:05.976   903  1051 D PackageManager: result of delete: 1{1071534721}
06-30 13:18:05.976  7437  7437 D AndroidRuntime: Shutting down VM
06-30 13:18:05.996  7480  7480 E Zygote  : MountEmulatedStorage()
06-30 13:18:05.996  7480  7480 E Zygote  : v2
06-30 13:18:05.996  7480  7480 I libpersona: KNOX_SDCARD checking this for 10043
06-30 13:18:05.996  7480  7480 I libpersona: KNOX_SDCARD not a persona
06-30 13:18:05.996   903  1730 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7480 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 13:18:06.006   903   919 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 13:18:06.006   903   919 D ActivityManager: caller:android.app.ApplicationThreadProxy@3cc82ed0, r.packageName :com.google.android.gms
06-30 13:18:06.026  7480  7480 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:18:06.026  7480  7480 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 13:18:06.026  7480  7480 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
06-30 13:18:06.026  2259  4206 I Icing   : doRemovePackageData com.test.thalitest
06-30 13:18:06.036  2259  7475 W BaseAppContext: Using Auth Proxy for data requests.
06-30 13:18:06.046   903  1471 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
06-30 13:18:06.046   903  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@245f7ec9, r.packageName :com.samsung.android.app.galaxyfinder
06-30 13:18:06.046  7480  7480 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:18:06.046  7480  7480 D ActivityThread: Added TimaKeyStore provider
06-30 13:18:06.066  7480  7480 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
06-30 13:18:06.066  1459  1459 D SurfaceWidgetView: destroyHardwareResources():237694218
06-30 13:18:06.076  1459  1459 D Launcher: onRestart, Launcher: 158220672
06-30 13:18:06.076  1459  1459 D Launcher: onStart, Launcher: 158220672
06-30 13:18:06.076  1459  1459 D Launcher.HomeView: onStart
06-30 13:18:06.076  1459  1459 V ActivityThread: updateVisibility : ActivityRecord{2f134015 token=android.os.BinderProxy@1c326fb5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
06-30 13:18:06.076  1765  7253 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
06-30 13:18:06.076  1765  1942 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
06-30 13:18:06.076  1765  1942 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
06-30 13:18:06.086  2259  7472 E SQLiteLog: (539) recovered 2 pages from /data/data/com.google.android.gms/databases/DocList.db-journal
06-30 13:18:06.086   266   266 I SurfaceFlinger: id=14 createSurf (1080x1920),1 flag=4, Mauncher
06-30 13:18:06.096   903   977 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
06-30 13:18:06.096  7480  7480 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
06-30 13:18:06.096  7480  7480 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
06-30 13:18:06.096   903   977 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
06-30 13:18:06.106  7480  7480 D SPPClientService: PushLog.txt file is not deleted.
06-30 13:18:06.106  7480  7480 D SPPClientService: PushLog.txt file is not deleted.
06-30 13:18:06.106  7480  7480 D SPPClientService: ============PushLog. stop!
06-30 13:18:06.106   903   977 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
06-30 13:18:06.116   903   977 D EnterpriseDeviceManagerService: Package has changed for user 0
06-30 13:18:06.116   903   977 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
06-30 13:18:06.116   903   977 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
06-30 13:18:06.116   903   977 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
06-30 13:18:06.126   903   977 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:18:06.126   903   977 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
06-30 13:18:06.136  6557  6557 I SA      : [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
06-30 13:18:06.136  6557  6557 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
06-30 13:18:06.136   903   977 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
06-30 13:18:06.136   903   977 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
06-30 13:18:06.146   903  1451 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
06-30 13:18:06.146   903  1451 D ActivityManager: caller:android.app.ApplicationThreadProxy@37ebe4a6, r.packageName :com.android.providers.contacts
06-30 13:18:06.146   903   977 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:18:06.146   903   977 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
06-30 13:18:06.146   903   977 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
06-30 13:18:06.156   903  1031 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1b9343be u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t20} time:1705394
06-30 13:18:06.156   903  1031 D MultiWindowConverter: MultiWindow Gesture is not supported with launcher
06-30 13:18:06.166   903   977 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:18:06.166   903   977 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
06-30 13:18:06.166   903   977 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:18:06.166   903   977 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
06-30 13:18:06.166  5841  5841 D Mms/FreeMessageReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
06-30 13:18:06.176   903  1141 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
06-30 13:18:06.176   903  1141 D ActivityManager: caller:android.app.ApplicationThreadProxy@21ecec00, r.packageName :com.android.mms
06-30 13:18:06.176  5841  7500 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
06-30 13:18:06.176  5841  7500 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
06-30 13:18:06.176  2259  7472 W FieldDefinition: Ignoring isIndexed constraint as field also has uniqueness constraint (on just this field, and therefore SQLite will have to create an index on that. For field: com.google.android.gms.drive.database.model.ax@1d56f136
06-30 13:18:06.186   903  3712 I TactileAssist: enable value -1
06-30 13:18:06.186   903  3712 I TactileAssist: internal enable value -1
06-30 13:18:06.186   903  3712 I TactileAssist: intensity value -1
06-30 13:18:06.186   903  3712 I TactileAssist: saveAppList value true
06-30 13:18:06.186   903  3712 I TactileAssist: List of disabled apps :
06-30 13:18:06.196   903   977 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:18:06.196   903   977 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:18:06.196   903   977 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
06-30 13:18:06.196   903   920 D SettingsProvider: name = reading_mode_app_list
06-30 13:18:06.196  6952  6952 D Compatibility: onReceive() it will make start service
06-30 13:18:06.206   903  1730 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
06-30 13:18:06.206   903  1730 D ActivityManager: caller:android.app.ApplicationThreadProxy@2834c82c, r.packageName :com.sec.android.app.soundalive
06-30 13:18:06.206   903  1051 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
06-30 13:18:06.206   903  1051 D PackageManager: userId{-1}
06-30 13:18:06.206   903  1051 D PackageManager: andCode{true}
06-30 13:18:06.206   903  1051 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
06-30 13:18:06.206   903   977 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:18:06.206   903   977 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
06-30 13:18:06.206  6952  7501 D Compatibility: onHandleIntent()
06-30 13:18:06.206  6952  7501 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10079, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
06-30 13:18:06.206   903   977 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
06-30 13:18:06.216  6952  7501 D Compatibility: found: 2
06-30 13:18:06.216  6952  7501 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
06-30 13:18:06.216  6952  7501 D Compatibility: skipping ResolveInfo{97fe03 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
06-30 13:18:06.216  6952  7501 D Compatibility: considering ResolveInfo{96e4180 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
06-30 13:18:06.216  6952  7501 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
06-30 13:18:06.216  6952  7501 D Compatibility: enabling receiver ResolveInfo{4e713b9 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
06-30 13:18:06.216   903  1368 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox

```
