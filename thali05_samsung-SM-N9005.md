#### Test 75789268eab05ed_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
07-05 11:08:03.096   758  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:08:03.096   758  1480 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 11:08:03.096   758  1480 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 11:08:03.096   758  1480 D BatteryService: stay LED for fully charged
07-05 11:08:03.106   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 11:08:03.106   758   758 I MotionRecognitionService: Plugged
07-05 11:08:03.106   758   758 I MotionRecognitionService: setPowerConnected  = true
--------- beginning of main
07-05 11:08:03.106  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 11:08:03.106  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:08:03.116  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 11:08:03.116  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:08:03.116  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:08:03.116  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 11:08:03.116  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
07-05 11:08:03.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:08:03.376   758  3059 D SSRM:n  : SIOP:: AP = 340, PST = 369, CUR = 450
07-05 11:08:03.396  7349  7349 D AndroidRuntime: 
07-05 11:08:03.396  7349  7349 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 11:08:03.396  7349  7349 D AndroidRuntime: CheckJNI is OFF
07-05 11:08:03.406  7349  7349 D AndroidRuntime: readGMSProperty: start
07-05 11:08:03.406  7349  7349 D AndroidRuntime: readGMSProperty: already setted!!
07-05 11:08:03.406  7349  7349 D AndroidRuntime: readGMSProperty: end
07-05 11:08:03.406  7349  7349 D AndroidRuntime: addProductProperty: start
07-05 11:08:03.576  7349  7349 E AffinityControl: AffinityControl: registerfunction enter
07-05 11:08:03.606  7349  7349 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 11:08:03.626   758   778 E PersonaManagerService: inState():  stateMachine is null !!
07-05 11:08:03.626   758   778 I PersonaManagerService: PersonaId don't exist
07-05 11:08:03.626   758   778 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-05 11:08:03.636   758   778 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 11:08:03.636   758   778 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 11:08:03.636   758   778 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-05 11:08:03.656   758   778 W ActivityManager: mDVFSHelper.acquire()
07-05 11:08:03.656   758   778 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:08:03.656   758   778 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:08:03.656   758   778 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:08:03.656   758   778 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:08:03.706   305   305 E SMD     : DCD ON
07-05 11:08:03.716  7365  7365 E Zygote  : MountEmulatedStorage()
07-05 11:08:03.716   758   778 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7365 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 11:08:03.716  7365  7365 E Zygote  : v2
07-05 11:08:03.716  7365  7365 I libpersona: KNOX_SDCARD checking this for 10079
07-05 11:08:03.716  7365  7365 I libpersona: KNOX_SDCARD not a persona
07-05 11:08:03.726  7365  7365 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 11:08:03.726  7365  7365 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 11:08:03.726  7349  7349 D AndroidRuntime: Shutting down VM
07-05 11:08:03.726  7365  7365 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-05 11:08:03.746  7365  7365 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 11:08:03.746  7365  7365 D ActivityThread: Added TimaKeyStore provider
07-05 11:08:03.756  1445  1445 V ActivityThread: updateVisibility : ActivityRecord{2492b54a token=android.os.BinderProxy@1d98ec6a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-05 11:08:03.756  1816  1840 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
07-05 11:08:03.766   758  3059 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 11:08:03.776  7365  7365 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-05 11:08:03.776   758  3059 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 11:08:03.786  1445  1445 D SurfaceWidgetView: destroyHardwareResources():430515483
07-05 11:08:03.826   266   327 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
07-05 11:08:03.826   266  1124 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
07-05 11:08:03.836  1445  1445 D Launcher: onTrimMemory. Level: 20
07-05 11:08:03.866  7365  7365 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-05 11:08:03.866  7365  7365 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
07-05 11:08:03.876  7365  7365 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4383-4386)
07-05 11:08:03.876  7365  7365 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 11:08:03.896  7365  7365 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {218b20d2}
07-05 11:08:03.896  7365  7365 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 11:08:03.896  7365  7365 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 11:08:03.926  7365  7365 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 11:08:03.926  7365  7365 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 11:08:03.926  7365  7365 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-05 11:08:03.946  7365  7365 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-05 11:08:03.946  7365  7365 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-05 11:08:03.946  7365  7365 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-05 11:08:03.956  7365  7365 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-05 11:08:03.956  7365  7365 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-05 11:08:03.956  7365  7365 I Adreno-EGL: Build Date: 11/19/14 Wed
07-05 11:08:03.956  7365  7365 I Adreno-EGL: Local Branch: mybranch5813579
07-05 11:08:03.956  7365  7365 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-05 11:08:03.956  7365  7365 I Adreno-EGL: Local Patches: NONE
07-05 11:08:03.956  7365  7365 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-05 11:08:04.056  7365  7398 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-05 11:08:04.086  7365  7365 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 11:08:04.096  7365  7365 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-05 11:08:04.106  7365  7365 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-05 11:08:04.116  7365  7365 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 11:08:04.116  7365  7365 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 11:08:04.166  7365  7365 D Activity: performCreate Call secproduct feature valuefalse
,07-05 11:08:04.166  7365  7365 D Activity: performCreate Call debug elastic valuetrue
,07-05 11:08:04.176  7365  7414 D OpenGLRenderer: Render dirty regions requested: true
,07-05 11:08:04.176   758  1614 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-05 11:08:04.176   758  1614 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-05 11:08:04.176   758  1614 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-05 11:08:04.176   758   758 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-05 11:08:04.176   758   758 D PersonaManagerService: getPersonasForUser(): returning null!
,07-05 11:08:04.206   266   266 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,07-05 11:08:04.216  7365  7414 I OpenGLRenderer: Initialized EGL, version 1.4
,07-05 11:08:04.216  7365  7414 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3c8b218 ,&mEglDisplay = 1 , &mEglConfig = 8 
,07-05 11:08:04.216  7365  7414 D OpenGLRenderer: Enabling debug mode 0
,07-05 11:08:04.236  7365  7365 V ActivityThread: updateVisibility : ActivityRecord{3d221afc token=android.os.BinderProxy@2a1f24ce {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-05 11:08:04.266  7365  7365 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2a1f24ce time:154775
,07-05 11:08:04.286   758  1046 W ActivityManager: mDVFSHelper.release()
07-05 11:08:04.286   758  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2503f12f u0 com.test.thalitest/.MainActivity t23} time:154791
,07-05 11:08:04.286   758  1046 D MultiWindowConverter: This application or window do not support multiwindow
,07-05 11:08:04.316  7365  7365 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7365
,07-05 11:08:04.396  7365  7365 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 11:08:04.456  7365  7365 I chromium: [INFO:CONSOLE(90)] "Uncaught SyntaxError: Unexpected token function", source: file:///android_asset/www/js/thali_main.js (90)
,07-05 11:08:04.496  7365  7418 D jxcore_app_log: JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259431296
,07-05 11:08:04.506  7365  7418 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 11:08:04.506  7365  7418 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 11:08:04.506  7365  7418 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 11:08:04.506  7365  7418 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 11:08:04.506  7365  7418 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 11:08:04.506  7365  7418 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3aa03b2c added. We now have 1 listener(s)
,07-05 11:08:04.516  7365  7418 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:2A:28:2D
,07-05 11:08:04.516  7365  7418 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,07-05 11:08:04.516  7365  7418 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-05 11:08:04.516  7365  7418 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-05 11:08:04.526  7365  7418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 11:08:04.526  7365  7418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 11:08:04.526  7365  7418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 11:08:04.526  7365  7418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:2A:28:2D
07-05 11:08:04.526  7365  7418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 11:08:04.526  7365  7418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 11:08:04.526  7365  7418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 11:08:04.526  7365  7418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 11:08:04.526  7365  7418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 11:08:04.526  7365  7418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 11:08:04.526  7365  7418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 11:08:04.526  7365  7418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a3e4dfb added. We now have 1 listener(s)
07-05 11:08:04.526  7365  7418 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 11:08:04.526  7365  7418 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,07-05 11:08:04.536  7365  7418 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-05 11:08:04.536  7365  7418 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-05 11:08:04.536  7365  7418 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 11:08:04.536  7365  7418 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:2A:28:2D
07-05 11:08:04.536   758   778 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 11:08:04.536  7365  7418 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 11:08:04.536  7365  7418 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 11:08:04.536  7365  7418 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 11:08:04.536  7365  7418 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 11:08:04.536  7365  7418 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 11:08:04.536  7365  7418 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 11:08:04.536  7365  7418 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 11:08:04.536  7365  7418 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 11:08:04.536  7365  7418 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-05 11:08:04.536  7365  7418 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 11:08:04.536   758  1536 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 11:08:04.546  7365  7365 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 11:08:04.546   758  1480 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 11:08:04.546  7365  7418 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 11:08:04.546  7365  7365 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 11:08:04.556  7365  7365 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 11:08:04.886   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:08:05.266  7365  7424 W jxcore-log: Initializing JXcore engine
07-05 11:08:05.266  7365  7424 W jxcore-log: JXcore engine is ready
,07-05 11:08:05.316  1982  1982 E auditd  : In denial and Property audit_ondenial is set to 1 
,07-05 11:08:05.316  1982  1982 E audit   : type=1400 msg=audit(1467709685.306:203): avc:  denied  { ioctl } for  pid=7424 comm="Thread-1244" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-05 11:08:05.316  1982  1982 E audit   :  SEPF_SM-N9005_5.0-1_0032
07-05 11:08:05.316  1982  1982 E audit   : 
,07-05 11:08:05.316   758  1036 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
07-05 11:08:05.316  1982  1982 E audit   : type=1300 msg=audit(1467709685.306:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=984a08d8 items=0 ppid=353 ppcomm=main pid=7424 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1244" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-05 11:08:05.316  1982  1982 E audit   : type=1320 msg=audit(1467709685.306:203): 
07-05 11:08:05.316   758  1036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,07-05 11:08:05.316   758  1036 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,07-05 11:08:05.316  6778  6778 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-05 11:08:05.316  6778  6778 D SecurityLogAgent:  SeDenialReceiver : File path = null
,07-05 11:08:05.326  7365  7424 W jxcore-log: Starting JXcore engine
,07-05 11:08:05.406  7365  7424 W jxcore-log: Platform android
07-05 11:08:05.406  7365  7424 W jxcore-log: 
,07-05 11:08:05.406  7365  7424 W jxcore-log: Process ARCH arm
07-05 11:08:05.406  7365  7424 W jxcore-log: 
,07-05 11:08:05.596  7365  7424 I jxcore-log: JXcore Cordova bridge is ready!
07-05 11:08:05.596  7365  7424 I jxcore-log: 
,07-05 11:08:05.596  7365  7424 W jxcore-log: JXcore engine is started
,07-05 11:08:06.706   305   305 E SMD     : DCD ON
,07-05 11:08:09.026   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:09.706   305   305 E SMD     : DCD ON
,07-05 11:08:10.036   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:11.036   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:12.036   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:12.706   305   305 E SMD     : DCD ON
,07-05 11:08:13.036   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:13.416   758  3059 D SSRM:n  : SIOP:: AP = 350, PST = 364, CUR = 450
,07-05 11:08:13.656   758  1064 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-05 11:08:14.036   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 11:08:15.706   305   305 E SMD     : DCD ON
,07-05 11:08:18.296   758  1337 E Watchdog: !@Sync 5
,07-05 11:08:18.706   305   305 E SMD     : DCD ON
,07-05 11:08:21.706   305   305 E SMD     : DCD ON
,07-05 11:08:22.516   758  1111 V AlarmManager: waitForAlarm result :4
,07-05 11:08:22.546   758  1668 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 11:08:22.546  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 11:08:22.546  1191  1191 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:08:22.566  1191  1191 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 11:08:22.566  1191  1191 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 11:08:22.566   758  3047 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 11:08:22.566   758  3047 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:08:22.566   758  3047 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 11:08:22.566   758  3047 D BatteryService: stay LED for fully charged
,07-05 11:08:22.566   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 11:08:22.566   758   758 I MotionRecognitionService: Plugged
,07-05 11:08:22.566   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:08:22.576  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:08:22.576  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:08:22.576  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:08:22.576  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:08:22.576  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:08:22.576  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:08:22.586  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:08:22.586  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:08:22.596   758  3296 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-05 11:08:22.606   758  3296 D ActivityManager: caller:android.app.ApplicationThreadProxy@1f745f21, r.packageName :com.google.android.gms
,07-05 11:08:22.646  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:08:22.646  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:08:23.466   758  3059 D SSRM:n  : SIOP:: AP = 340, PST = 360, CUR = 450
,07-05 11:08:24.706   305   305 E SMD     : DCD ON
,07-05 11:08:24.886   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:08:27.706   305   305 E SMD     : DCD ON
,07-05 11:08:30.706   305   305 E SMD     : DCD ON
,07-05 11:08:32.396   758  1050 I PowerManagerService: [PWL] Off : 140s ago
,07-05 11:08:32.626   758  1143 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:08:32.636   758  1143 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:08:32.636   758  1143 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:08:32.636   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:08:32.636   758   758 I MotionRecognitionService: Plugged
,07-05 11:08:32.636   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:08:32.636  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:08:32.636  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:08:32.646  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:08:32.646   758  1143 D BatteryService: stay LED for fully charged
,07-05 11:08:32.646  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:08:32.646  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:08:32.646  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:08:32.646  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:08:32.656  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:08:33.516   758  3059 D SSRM:n  : SIOP:: AP = 340, PST = 356, CUR = 450
,07-05 11:08:33.706   305   305 E SMD     : DCD ON
,07-05 11:08:34.036   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:35.036   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:36.036   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:36.716   305   305 E SMD     : DCD ON
,07-05 11:08:37.036   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:38.036   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:39.036   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 11:08:39.716   305   305 E SMD     : DCD ON
,07-05 11:08:42.686   758   779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:08:42.716   305   305 E SMD     : DCD ON
,07-05 11:08:43.566   758  3059 D SSRM:n  : SIOP:: AP = 330, PST = 353, CUR = 450
,07-05 11:08:44.896   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:08:45.716   305   305 E SMD     : DCD ON
,07-05 11:08:48.296   758  1337 E Watchdog: !@Sync 6
,07-05 11:08:48.716   305   305 E SMD     : DCD ON
,07-05 11:08:51.716   305   305 E SMD     : DCD ON
,07-05 11:08:52.746   758  1668 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:08:53.606   758  3059 D SSRM:n  : SIOP:: AP = 330, PST = 351, CUR = 450
,07-05 11:08:54.716   305   305 E SMD     : DCD ON
,07-05 11:08:57.716   305   305 E SMD     : DCD ON
,07-05 11:08:59.996   758  1111 V AlarmManager: waitForAlarm result :8
,07-05 11:09:00.716   305   305 E SMD     : DCD ON
,07-05 11:09:02.806   758  3047 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:09:02.806   758  3047 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:09:02.806   758  3047 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:09:02.816   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:09:02.816  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:09:02.816  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:09:02.816   758   758 I MotionRecognitionService: Plugged
,07-05 11:09:02.816   758   758 I MotionRecognitionService: setPowerConnected  = true
07-05 11:09:02.826  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:09:02.826  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:09:02.826  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:09:02.826   758  3047 D BatteryService: stay LED for fully charged
07-05 11:09:02.826  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:09:02.826  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:09:02.826  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:09:03.656   758  3059 D SSRM:n  : SIOP:: AP = 330, PST = 349, CUR = 450
,07-05 11:09:03.716   305   305 E SMD     : DCD ON
,07-05 11:09:04.036   363   363 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 11:09:04.036   363   363 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 11:09:04.896   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:09:06.716   305   305 E SMD     : DCD ON
,07-05 11:09:09.716   305   305 E SMD     : DCD ON
,07-05 11:09:12.416   758  1050 I PowerManagerService: [PWL] Off : 180s ago
,07-05 11:09:12.726   305   305 E SMD     : DCD ON
,07-05 11:09:12.866   758  1614 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:09:12.866   758  1614 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:09:12.866   758  1614 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:09:12.876   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:09:12.876  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:09:12.876  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:09:12.876  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:09:12.886   758   758 I MotionRecognitionService: Plugged
,07-05 11:09:12.886   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:09:12.886  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:09:12.886  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:09:12.886  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:09:12.886   758  1614 D BatteryService: stay LED for fully charged
,07-05 11:09:12.886  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:09:12.886  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:09:13.696   758  3059 D SSRM:n  : SIOP:: AP = 330, PST = 344, CUR = 450
,07-05 11:09:14.046   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:15.046   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:15.726   305   305 E SMD     : DCD ON
,07-05 11:09:16.046   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:17.046   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:18.046   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:18.296   758  1337 E Watchdog: !@Sync 7
,07-05 11:09:18.726   305   305 E SMD     : DCD ON
,07-05 11:09:19.046   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 11:09:21.726   305   305 E SMD     : DCD ON
,07-05 11:09:22.926   758  3047 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:09:23.746   758  3059 D SSRM:n  : SIOP:: AP = 330, PST = 338, CUR = 450
,07-05 11:09:24.046   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:24.726   305   305 E SMD     : DCD ON
,07-05 11:09:24.896   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:09:25.046   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:26.046   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:27.056   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:27.726   305   305 E SMD     : DCD ON
,07-05 11:09:28.056   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:29.056   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 11:09:30.726   305   305 E SMD     : DCD ON
,07-05 11:09:33.726   305   305 E SMD     : DCD ON
,07-05 11:09:33.796   758  3059 D SSRM:n  : SIOP:: AP = 320, PST = 334, CUR = 450
,07-05 11:09:36.726   305   305 E SMD     : DCD ON
,07-05 11:09:39.056   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:39.546   758  1111 V AlarmManager: waitForAlarm result :4
,07-05 11:09:39.556  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 11:09:39.556  1191  1191 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:09:39.566  1191  1191 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 11:09:39.566  1191  1191 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 11:09:39.586   758  1602 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:09:39.636  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:09:39.636  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:09:39.726   305   305 E SMD     : DCD ON
,07-05 11:09:40.056   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:41.056   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:42.056   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:42.726   305   305 E SMD     : DCD ON
,07-05 11:09:43.056   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:43.846   758  3059 D SSRM:n  : SIOP:: AP = 320, PST = 332, CUR = 450
,07-05 11:09:44.056   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 11:09:44.906   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:09:45.726   305   305 E SMD     : DCD ON
,07-05 11:09:48.306   758  1337 E Watchdog: !@Sync 8
,07-05 11:09:48.726   305   305 E SMD     : DCD ON
,07-05 11:09:49.646   758  1143 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:09:49.646   758  1143 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:09:49.646   758  1143 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:09:49.656   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:09:49.656  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:09:49.656  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:09:49.656  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:09:49.666   758   758 I MotionRecognitionService: Plugged
,07-05 11:09:49.666   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:09:49.666  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:09:49.666  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 11:09:49.666   758  1143 D BatteryService: stay LED for fully charged
,07-05 11:09:49.666  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:09:49.666  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:09:49.666  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:09:51.736   305   305 E SMD     : DCD ON
,07-05 11:09:53.886   758  3059 D SSRM:n  : SIOP:: AP = 320, PST = 329, CUR = 450
,07-05 11:09:54.736   305   305 E SMD     : DCD ON
,07-05 11:09:57.416   758  1050 I PowerManagerService: [PWL] Off : 225s ago
,07-05 11:09:57.736   305   305 E SMD     : DCD ON
,07-05 11:09:59.056   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:00.006   758  1111 V AlarmManager: waitForAlarm result :8
,07-05 11:10:00.046   758   779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:10:00.056   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:00.736   305   305 E SMD     : DCD ON
,07-05 11:10:01.066   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:02.066   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:03.066   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:03.736   305   305 E SMD     : DCD ON
,07-05 11:10:03.936   758  3059 D SSRM:n  : SIOP:: AP = 320, PST = 327, CUR = 450
,07-05 11:10:04.066   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 11:10:04.906   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:10:06.736   305   305 E SMD     : DCD ON
,07-05 11:10:09.736   305   305 E SMD     : DCD ON
,07-05 11:10:10.106   758  1668 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:10:12.736   305   305 E SMD     : DCD ON
,07-05 11:10:13.986   758  3059 D SSRM:n  : SIOP:: AP = 320, PST = 325, CUR = 450
,07-05 11:10:15.736   305   305 E SMD     : DCD ON
,07-05 11:10:18.306   758  1337 E Watchdog: !@Sync 9
,07-05 11:10:18.736   305   305 E SMD     : DCD ON
,07-05 11:10:20.166   758  1602 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:10:21.736   305   305 E SMD     : DCD ON
,07-05 11:10:24.026   758  3059 D SSRM:n  : SIOP:: AP = 320, PST = 324, CUR = 450
,07-05 11:10:24.066   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:24.736   305   305 E SMD     : DCD ON
,07-05 11:10:24.916   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:10:25.066   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:26.066   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:27.066   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:27.746   305   305 E SMD     : DCD ON
,07-05 11:10:28.066   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:29.066   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 11:10:30.226   758   778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:10:30.746   305   305 E SMD     : DCD ON
,07-05 11:10:33.746   305   305 E SMD     : DCD ON
,07-05 11:10:34.086   758  3059 D SSRM:n  : SIOP:: AP = 320, PST = 323, CUR = 450
,07-05 11:10:36.746   305   305 E SMD     : DCD ON
,07-05 11:10:39.746   305   305 E SMD     : DCD ON
,07-05 11:10:40.286   758  1143 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:10:42.746   305   305 E SMD     : DCD ON
,07-05 11:10:44.136   758  3059 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 450
,07-05 11:10:44.916   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:10:45.396   758  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 11:10:45.406   758  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 11:10:45.406   758  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 11:10:45.416   758  1100 I TLC_TIMA_PKM_initialize: initializing...
,07-05 11:10:45.416   758  1100 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,07-05 11:10:45.416   758  1100 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,07-05 11:10:45.426   758  1100 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,07-05 11:10:45.426   758  1100 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,07-05 11:10:45.426   758  1100 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-05 11:10:45.426   758  1100 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,07-05 11:10:45.426   758  1100 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,07-05 11:10:45.426   758  1100 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-05 11:10:45.436   758  1100 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 11:10:45.446   758  1100 D QSEECOMAPI: : Loaded image: APP id = 2
,07-05 11:10:45.456   758  1100 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-05 11:10:45.466   758  1100 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-05 11:10:45.746   305   305 E SMD     : DCD ON
,07-05 11:10:47.416   758  1050 I PowerManagerService: [PWL] Off : 275s ago
,07-05 11:10:47.416   758  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,07-05 11:10:47.416   758  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,07-05 11:10:47.426   758  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=758, ws=null) (elapsedTime=2011)
,07-05 11:10:47.616   758  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 11:10:47.616   758  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 11:10:47.626   758  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:10:47.626   758  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:10:48.306   758  1337 E Watchdog: !@Sync 10
,07-05 11:10:48.746   305   305 E SMD     : DCD ON
,07-05 11:10:50.346   758  1234 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:10:51.746   305   305 E SMD     : DCD ON
,07-05 11:10:54.066   363   363 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 11:10:54.066   363   363 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 11:10:54.186   758  3059 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 450
,07-05 11:10:54.746   305   305 E SMD     : DCD ON
,07-05 11:10:57.746   305   305 E SMD     : DCD ON
,07-05 11:11:00.746   305   305 E SMD     : DCD ON
,07-05 11:11:03.746   305   305 E SMD     : DCD ON
,07-05 11:11:03.886   758  1111 V AlarmManager: waitForAlarm result :4
,07-05 11:11:03.896   758  1001 D ActivityManager: startProcessLocked calleePkgName: com.blurb.checkout, hostingType: broadcast
,07-05 11:11:03.896   758  1001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 11:11:03.896   758  1001 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:11:03.896   758  1001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 11:11:03.896   758  1001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 11:11:03.926   758  1668 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 11:11:03.926   758  1668 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 11:11:03.926   758  1668 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 11:11:03.926   758  1668 D BatteryService: stay LED for fully charged
,07-05 11:11:03.956  7478  7478 E Zygote  : MountEmulatedStorage()
,07-05 11:11:03.966   758  1001 I ActivityManager: Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7478 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 11:11:03.966   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:11:03.966  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 11:11:03.966  1191  1191 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:11:03.966  1191  1191 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 11:11:03.966  1191  1191 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 11:11:03.976  7478  7478 E Zygote  : v2
,07-05 11:11:03.976  7478  7478 I libpersona: KNOX_SDCARD checking this for 10096
07-05 11:11:03.976  7478  7478 I libpersona: KNOX_SDCARD not a persona
,07-05 11:11:03.976   758   758 I MotionRecognitionService: Plugged
,07-05 11:11:03.976   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:11:03.996  7478  7478 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 11:11:03.996  7478  7478 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 11:11:03.996  7478  7478 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-05 11:11:03.996  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:11:04.006  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:11:04.006  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:11:04.006  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:11:04.006  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:11:04.006  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:04.006  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:04.006  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:04.026  7478  7478 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 11:11:04.036  7478  7478 D ActivityThread: Added TimaKeyStore provider
,07-05 11:11:04.056  7478  7478 D ResourcesManager: creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,07-05 11:11:04.056  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:11:04.066  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:11:04.066   758  1433 D ActivityManager: startService callerProcessName:com.blurb.checkout, calleePkgName: com.blurb.checkout
,07-05 11:11:04.066   758  1433 D ActivityManager: caller:android.app.ApplicationThreadProxy@19ffdaa3, r.packageName :com.blurb.checkout
,07-05 11:11:04.106   758  1614 I ActivityManager: Killing 6735:com.sec.android.app.clockpackage/u0a106 (adj 15): emptyCount ##41
,07-05 11:11:04.216   758  3059 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 11:11:04.926   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:11:06.756   305   305 E SMD     : DCD ON
,07-05 11:11:09.066   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:09.756   305   305 E SMD     : DCD ON
,07-05 11:11:10.076   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:11.076   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:12.076   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:12.756   305   305 E SMD     : DCD ON
,07-05 11:11:13.076   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:13.996   758  1362 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:11:13.996   758  1362 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:11:13.996   758  1362 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:11:14.006   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:11:14.006  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:11:14.016  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:11:14.016   758   758 I MotionRecognitionService: Plugged
07-05 11:11:14.016   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:11:14.016   758  1362 D BatteryService: stay LED for fully charged
,07-05 11:11:14.016  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:11:14.026  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:11:14.026  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:11:14.036  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:14.036  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:11:14.036  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:14.076   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 11:11:14.266   758  3059 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 11:11:15.756   305   305 E SMD     : DCD ON
,07-05 11:11:18.316   758  1337 E Watchdog: !@Sync 11
,07-05 11:11:18.756   305   305 E SMD     : DCD ON
,07-05 11:11:19.076   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:20.076   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:21.076   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:21.756   305   305 E SMD     : DCD ON
,07-05 11:11:22.076   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:23.086   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:24.056   758  1234 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:11:24.086   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 11:11:24.316   758  3059 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 11:11:24.756   305   305 E SMD     : DCD ON
,07-05 11:11:24.926   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:11:27.756   305   305 E SMD     : DCD ON
,07-05 11:11:30.756   305   305 E SMD     : DCD ON
,07-05 11:11:33.756   305   305 E SMD     : DCD ON
,07-05 11:11:34.086   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:34.116   758  1461 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:11:34.116   758  1461 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:11:34.116   758  1461 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:11:34.116   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:11:34.126  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:11:34.126  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:11:34.126   758   758 I MotionRecognitionService: Plugged
,07-05 11:11:34.126   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:11:34.136   758  1461 D BatteryService: stay LED for fully charged
,07-05 11:11:34.136  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:11:34.136  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:11:34.136  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:11:34.156  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:34.156  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:34.156  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:34.366   758  3059 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 11:11:35.086   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:36.086   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:36.756   305   305 E SMD     : DCD ON
,07-05 11:11:37.086   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:38.086   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:39.086   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 11:11:39.756   305   305 E SMD     : DCD ON
,07-05 11:11:42.426   758  1050 I PowerManagerService: [PWL] Off : 330s ago
,07-05 11:11:42.756   305   305 E SMD     : DCD ON
,07-05 11:11:44.176   758  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:11:44.176   758  1536 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 11:11:44.176   758  1536 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:11:44.176   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:11:44.186  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:11:44.186  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:11:44.186   758   758 I MotionRecognitionService: Plugged
07-05 11:11:44.186   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:11:44.186   758  1536 D BatteryService: stay LED for fully charged
,07-05 11:11:44.196  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:11:44.196  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:44.196  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:44.196  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:11:44.206  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:11:44.216  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:44.416   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 450
,07-05 11:11:44.926   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:11:45.766   305   305 E SMD     : DCD ON
,07-05 11:11:48.316   758  1337 E Watchdog: !@Sync 12
,07-05 11:11:48.766   305   305 E SMD     : DCD ON
,07-05 11:11:51.766   305   305 E SMD     : DCD ON
,07-05 11:11:54.086   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:54.236   758  1461 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:11:54.236   758  1461 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:11:54.236   758  1461 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:11:54.236   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:11:54.246  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:11:54.246   758   758 I MotionRecognitionService: Plugged
,07-05 11:11:54.246   758   758 I MotionRecognitionService: setPowerConnected  = true
07-05 11:11:54.246  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:11:54.246   758  1461 D BatteryService: stay LED for fully charged,
,07-05 11:11:54.256  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:11:54.256  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:54.256  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:11:54.266  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:11:54.276  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:54.276  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:54.466   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 318, CUR = 450
,07-05 11:11:54.766   305   305 E SMD     : DCD ON
,07-05 11:11:55.086   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:56.096   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:57.096   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:57.766   305   305 E SMD     : DCD ON
,07-05 11:11:58.096   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:59.096   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 11:11:59.996   758  1111 V AlarmManager: waitForAlarm result :8
,07-05 11:12:00.766   305   305 E SMD     : DCD ON
,07-05 11:12:03.766   305   305 E SMD     : DCD ON
,07-05 11:12:04.296   758  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:12:04.516   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 450
,07-05 11:12:04.936   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:12:06.766   305   305 E SMD     : DCD ON
,07-05 11:12:09.766   305   305 E SMD     : DCD ON
,07-05 11:12:12.766   305   305 E SMD     : DCD ON
,07-05 11:12:14.356   758  3296 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:12:14.356   758  3296 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 11:12:14.356   758  3296 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:12:14.356   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:12:14.366  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:12:14.366  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:12:14.366   758   758 I MotionRecognitionService: Plugged
07-05 11:12:14.366   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:12:14.376   758  3296 D BatteryService: stay LED for fully charged
,07-05 11:12:14.376  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:12:14.376  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:12:14.376  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:12:14.396  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:12:14.396  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:12:14.396  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:12:14.566   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 450
,07-05 11:12:15.766   305   305 E SMD     : DCD ON
,07-05 11:12:18.316   758  1337 E Watchdog: !@Sync 13
,07-05 11:12:18.766   305   305 E SMD     : DCD ON
,07-05 11:12:19.096   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:20.096   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:21.096   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:21.766   305   305 E SMD     : DCD ON
,07-05 11:12:22.096   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:23.096   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:24.096   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 11:12:24.416   758  1644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:12:24.416   758  1644 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:12:24.416   758  1644 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:12:24.416   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:12:24.426  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:12:24.426   758   758 I MotionRecognitionService: Plugged
,07-05 11:12:24.426  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:12:24.426   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:12:24.436   758  1644 D BatteryService: stay LED for fully charged
,07-05 11:12:24.436  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:12:24.436  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:12:24.436  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:12:24.436  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:12:24.456  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:12:24.456  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:12:24.606   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 450
,07-05 11:12:24.776   305   305 E SMD     : DCD ON
,07-05 11:12:24.936   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:12:27.776   305   305 E SMD     : DCD ON
,07-05 11:12:30.776   305   305 E SMD     : DCD ON
,07-05 11:12:33.776   305   305 E SMD     : DCD ON
,07-05 11:12:34.476   758  3296 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:12:34.476   758  3296 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:12:34.476   758  3296 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 11:12:34.476   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:12:34.486   758   758 I MotionRecognitionService: Plugged
,07-05 11:12:34.486  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:12:34.486   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:12:34.486  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:12:34.496   758  3296 D BatteryService: stay LED for fully charged
,07-05 11:12:34.496  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:12:34.496  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:12:34.496  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:12:34.516  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:12:34.516  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:12:34.516  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:12:34.656   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 450
,07-05 11:12:36.776   305   305 E SMD     : DCD ON
,07-05 11:12:39.776   305   305 E SMD     : DCD ON
,07-05 11:12:42.426   758  1050 I PowerManagerService: [PWL] Off : 390s ago
,07-05 11:12:42.776   305   305 E SMD     : DCD ON
,07-05 11:12:44.536   758  1644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:12:44.706   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 450
,07-05 11:12:44.936   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:12:45.776   305   305 E SMD     : DCD ON
,07-05 11:12:48.326   758  1337 E Watchdog: !@Sync 14
,07-05 11:12:48.776   305   305 E SMD     : DCD ON
,07-05 11:12:49.096   363   363 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 11:12:49.096   363   363 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 11:12:51.776   305   305 E SMD     : DCD ON
,07-05 11:12:54.606   758   779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:12:54.616   758   779 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:12:54.616   758   779 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:12:54.616   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:12:54.616  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:12:54.616  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:12:54.616   758   758 I MotionRecognitionService: Plugged
,07-05 11:12:54.616   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:12:54.626  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:12:54.626  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:12:54.626  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:12:54.626  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:12:54.626   758   779 D BatteryService: stay LED for fully charged
07-05 11:12:54.626  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:12:54.626  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:12:54.746   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 450
,07-05 11:12:54.776   305   305 E SMD     : DCD ON
,07-05 11:12:57.776   305   305 E SMD     : DCD ON
,07-05 11:13:00.776   305   305 E SMD     : DCD ON
,07-05 11:13:03.776   305   305 E SMD     : DCD ON
,07-05 11:13:04.666   758  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:13:04.666   758  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:13:04.666   758  1319 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:13:04.666   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:13:04.676  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:13:04.676   758   758 I MotionRecognitionService: Plugged
,07-05 11:13:04.676  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 11:13:04.676   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:13:04.686  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:13:04.686  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
07-05 11:13:04.686  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:13:04.686  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:13:04.686   758  1319 D BatteryService: stay LED for fully charged
07-05 11:13:04.686  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:13:04.686  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:13:04.786   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,07-05 11:13:04.946   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:13:06.786   305   305 E SMD     : DCD ON
,07-05 11:13:09.106   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:09.786   305   305 E SMD     : DCD ON
,07-05 11:13:10.106   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:11.106   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:12.106   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:12.786   305   305 E SMD     : DCD ON
,07-05 11:13:13.106   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:14.106   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 11:13:14.726   758  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:13:14.726   758  1480 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:13:14.736   758  1480 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:13:14.736   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:13:14.736   758   758 I MotionRecognitionService: Plugged
,07-05 11:13:14.736   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:13:14.736  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:13:14.736  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:13:14.746  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:13:14.746  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:13:14.746  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:13:14.746  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:13:14.746  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:13:14.746   758  1480 D BatteryService: stay LED for fully charged
,07-05 11:13:14.746  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:13:14.826   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:13:15.786   305   305 E SMD     : DCD ON
,07-05 11:13:18.326   758  1337 E Watchdog: !@Sync 15
,07-05 11:13:18.786   305   305 E SMD     : DCD ON
,07-05 11:13:19.106   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:20.106   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:21.106   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:21.786   305   305 E SMD     : DCD ON
,07-05 11:13:22.116   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:23.116   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:24.116   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 11:13:24.786   305   305 E SMD     : DCD ON
,07-05 11:13:24.786   758  1602 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:13:24.796   758  1602 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:13:24.796   758  1602 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:13:24.796   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:13:24.796  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:13:24.796  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:13:24.796   758   758 I MotionRecognitionService: Plugged
07-05 11:13:24.796   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:13:24.806  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:13:24.806  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:13:24.806   758  1602 D BatteryService: stay LED for fully charged
,07-05 11:13:24.806  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:13:24.806  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:13:24.806  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:13:24.826  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:13:24.856   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:13:24.946   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:13:27.786   305   305 E SMD     : DCD ON
,07-05 11:13:30.786   305   305 E SMD     : DCD ON
,07-05 11:13:33.786   305   305 E SMD     : DCD ON
,07-05 11:13:34.116   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:34.846   758   779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:13:34.906   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:13:35.116   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:36.116   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:36.526   358   358 I bootchecker: bootchecker wake up!!
,07-05 11:13:36.796   305   305 E SMD     : DCD ON
,07-05 11:13:37.116   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:38.116   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:39.116   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 11:13:39.796   305   305 E SMD     : DCD ON
,07-05 11:13:42.796   305   305 E SMD     : DCD ON
,07-05 11:13:44.906   758  1614 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:13:44.906   758  1614 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:13:44.906   758  1614 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:13:44.916   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:13:44.916  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 11:13:44.916  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:13:44.926  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:13:44.926  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 11:13:44.926   758   758 I MotionRecognitionService: Plugged
07-05 11:13:44.926   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:13:44.926  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:13:44.926  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:13:44.926  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:13:44.926  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:13:44.926   758  1614 D BatteryService: stay LED for fully charged
,07-05 11:13:44.946   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:13:44.956   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:13:45.796   305   305 E SMD     : DCD ON
,07-05 11:13:47.426   758  1050 I PowerManagerService: [PWL] Off : 455s ago
,07-05 11:13:48.326   758  1337 E Watchdog: !@Sync 16
,07-05 11:13:48.796   305   305 E SMD     : DCD ON
,07-05 11:13:51.796   305   305 E SMD     : DCD ON
,07-05 11:13:54.116   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:54.796   305   305 E SMD     : DCD ON
,07-05 11:13:54.966   758  1234 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:13:55.006   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:13:55.126   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:56.126   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:57.126   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:57.796   305   305 E SMD     : DCD ON
,07-05 11:13:58.126   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:59.126   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 11:14:00.796   305   305 E SMD     : DCD ON
,07-05 11:14:03.796   305   305 E SMD     : DCD ON
,07-05 11:14:04.946   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:14:05.026   758  1461 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:14:05.056   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:14:06.796   305   305 E SMD     : DCD ON
,07-05 11:14:09.796   305   305 E SMD     : DCD ON
,07-05 11:14:12.796   305   305 E SMD     : DCD ON
,07-05 11:14:15.086   758  1644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:14:15.116   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:14:15.806   305   305 E SMD     : DCD ON
,07-05 11:14:18.336   758  1337 E Watchdog: !@Sync 17
,07-05 11:14:18.806   305   305 E SMD     : DCD ON
,07-05 11:14:19.126   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:20.126   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:21.126   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:21.806   305   305 E SMD     : DCD ON
,07-05 11:14:22.126   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:23.136   363   363 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:24.136   363   363 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 11:14:24.806   305   305 E SMD     : DCD ON
,07-05 11:14:24.956   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:14:25.146   758   779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:14:25.146   758   779 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:14:25.156   758   779 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:14:25.156   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:14:25.156   758   758 I MotionRecognitionService: Plugged
07-05 11:14:25.156   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:14:25.156  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 11:14:25.156  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:14:25.166  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:14:25.166  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:14:25.166  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:14:25.166  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:14:25.166   758   779 D BatteryService: stay LED for fully charged
,07-05 11:14:25.166  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:14:25.166  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:14:25.186   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:14:27.806   305   305 E SMD     : DCD ON
,07-05 11:14:30.806   305   305 E SMD     : DCD ON
,07-05 11:14:33.806   305   305 E SMD     : DCD ON
,07-05 11:14:35.206   758  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:14:35.236   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:14:36.806   305   305 E SMD     : DCD ON
,07-05 11:14:39.806   305   305 E SMD     : DCD ON
,07-05 11:14:42.806   305   305 E SMD     : DCD ON
,07-05 11:14:44.956   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:14:45.266   758  1234 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:14:45.296   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:14:45.806   305   305 E SMD     : DCD ON
,07-05 11:14:48.336   758  1337 E Watchdog: !@Sync 18
,07-05 11:14:48.806   305   305 E SMD     : DCD ON
,07-05 11:14:49.136   363   363 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 11:14:49.136   363   363 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 11:14:51.806   305   305 E SMD     : DCD ON
,07-05 11:14:54.816   305   305 E SMD     : DCD ON
,07-05 11:14:55.326   758  1461 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:14:55.356   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:14:57.436   758  1050 I PowerManagerService: [PWL] Off : 525s ago
,07-05 11:14:57.816   305   305 E SMD     : DCD ON
,07-05 11:15:00.816   305   305 E SMD     : DCD ON
,07-05 11:15:03.816   305   305 E SMD     : DCD ON
,07-05 11:15:04.966   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:15:05.396   758  1433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:15:05.396   758  1433 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:15:05.396   758  1433 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 11:15:05.396   758  1433 D BatteryService: stay LED for fully charged
07-05 11:15:05.396   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:15:05.396  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:15:05.406  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:15:05.406  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:15:05.406   758   758 I MotionRecognitionService: Plugged
,07-05 11:15:05.406   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:15:05.406  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:15:05.406  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:15:05.406  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:15:05.406  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:15:05.406  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:15:05.426   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:15:06.816   305   305 E SMD     : DCD ON
,07-05 11:15:09.816   305   305 E SMD     : DCD ON
,07-05 11:15:12.816   305   305 E SMD     : DCD ON
,07-05 11:15:14.146   363   363 I Atfwd_Daemon: Stop the daemon....
,07-05 11:15:15.456   758   778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:15:15.456   758   778 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:15:15.456   758   778 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 11:15:15.456   758   778 D BatteryService: stay LED for fully charged
07-05 11:15:15.456   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:15:15.456  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:15:15.456  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:15:15.456   758   758 I MotionRecognitionService: Plugged
07-05 11:15:15.456   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:15:15.466  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:15:15.466  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:15:15.466  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:15:15.466  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 11:15:15.466  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:15:15.466  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:15:15.486   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:15:15.816   305   305 E SMD     : DCD ON
,07-05 11:15:18.336   758  1337 E Watchdog: !@Sync 19
,07-05 11:15:18.816   305   305 E SMD     : DCD ON
,07-05 11:15:21.816   305   305 E SMD     : DCD ON
,07-05 11:15:24.816   305   305 E SMD     : DCD ON
,07-05 11:15:24.966   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:15:25.516   758  1433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:15:25.516   758  1433 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:15:25.516   758  1433 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 11:15:25.516   758  1433 D BatteryService: stay LED for fully charged
07-05 11:15:25.516   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:15:25.516  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:15:25.516  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:15:25.516   758   758 I MotionRecognitionService: Plugged
07-05 11:15:25.516   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:15:25.526  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:15:25.526  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:15:25.526  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:15:25.526  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
07-05 11:15:25.526  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:15:25.526  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:15:25.546   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:15:27.816   305   305 E SMD     : DCD ON
,07-05 11:15:30.816   305   305 E SMD     : DCD ON
,07-05 11:15:33.826   305   305 E SMD     : DCD ON
,07-05 11:15:35.576   758   778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:15:35.596   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:15:36.826   305   305 E SMD     : DCD ON
,07-05 11:15:39.826   305   305 E SMD     : DCD ON
,07-05 11:15:42.826   305   305 E SMD     : DCD ON
,07-05 11:15:44.966   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:15:45.396   758  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 11:15:45.396   758  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 11:15:45.406   758  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 11:15:45.616   758  1602 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:15:45.616   758  1602 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 11:15:45.616   758  1602 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 11:15:45.616   758  1602 D BatteryService: stay LED for fully charged
07-05 11:15:45.616   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:15:45.626   758   758 I MotionRecognitionService: Plugged
,07-05 11:15:45.626   758   758 I MotionRecognitionService: setPowerConnected  = true
07-05 11:15:45.626  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:15:45.626  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:15:45.626  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:15:45.636  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:15:45.636  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:15:45.636  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:15:45.636  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:15:45.636  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:15:45.666   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:15:45.826   305   305 E SMD     : DCD ON
,07-05 11:15:47.756   758  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 11:15:47.756   758  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 11:15:47.766   758  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:15:47.766   758  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:15:48.346   758  1337 E Watchdog: !@Sync 20
,07-05 11:15:48.826   305   305 E SMD     : DCD ON
,07-05 11:15:51.826   305   305 E SMD     : DCD ON
,07-05 11:15:54.826   305   305 E SMD     : DCD ON
,07-05 11:15:55.686   758   779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:15:55.686   758   779 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:15:55.686   758   779 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:15:55.696   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:15:55.696   758   758 I MotionRecognitionService: Plugged
,07-05 11:15:55.696  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 11:15:55.696  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:15:55.706  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:15:55.706   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:15:55.706  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:15:55.706  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:15:55.706  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:15:55.706   758   779 D BatteryService: stay LED for fully charged
,07-05 11:15:55.706  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:15:55.706  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:15:55.726   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:15:57.826   305   305 E SMD     : DCD ON
,07-05 11:16:00.826   305   305 E SMD     : DCD ON
,07-05 11:16:03.826   305   305 E SMD     : DCD ON
,07-05 11:16:04.976   758  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:16:05.746   758  1602 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:16:05.786   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:16:06.826   305   305 E SMD     : DCD ON
,07-05 11:16:09.826   305   305 E SMD     : DCD ON
,07-05 11:16:12.436   758  1050 I PowerManagerService: [PWL] Off : 600s ago
,07-05 11:16:12.836   305   305 E SMD     : DCD ON
,07-05 11:16:15.806   758  3047 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:16:15.836   305   305 E SMD     : DCD ON
,07-05 11:16:15.836   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:16:18.346   758  1337 E Watchdog: !@Sync 21
,07-05 11:16:18.836   305   305 E SMD     : DCD ON
,07-05 11:16:21.836   305   305 E SMD     : DCD ON
,07-05 11:16:24.836   305   305 E SMD     : DCD ON
,07-05 11:16:25.876   758  1362 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:16:25.896   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:16:27.836   305   305 E SMD     : DCD ON
,07-05 11:16:30.836   305   305 E SMD     : DCD ON
,07-05 11:16:33.836   305   305 E SMD     : DCD ON
,07-05 11:16:35.926   758  1433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:16:35.926   758  1433 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:16:35.936   758  1433 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 11:16:35.936   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:16:35.936   758  1433 D BatteryService: stay LED for fully charged
,07-05 11:16:35.946  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:16:35.946   758   758 I MotionRecognitionService: Plugged
,07-05 11:16:35.946  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:16:35.946   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:16:35.946  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:16:35.956  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:16:35.956  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:16:35.956  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:16:35.956  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:16:35.956  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:16:35.976   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 11:16:36.836   305   305 E SMD     : DCD ON
,07-05 11:16:39.836   305   305 E SMD     : DCD ON
,07-05 11:16:42.836   305   305 E SMD     : DCD ON
,07-05 11:16:45.836   305   305 E SMD     : DCD ON
,07-05 11:16:45.986   758   778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:16:45.986   758   778 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:16:45.996   758   778 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:16:45.996   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:16:46.006  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:16:46.006  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:16:46.006   758   758 I MotionRecognitionService: Plugged
,07-05 11:16:46.006   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:16:46.006   758   778 D BatteryService: stay LED for fully charged
,07-05 11:16:46.016  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:16:46.016  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:16:46.016  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:16:46.016  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:16:46.026  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:16:46.036  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:16:46.046   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450
,07-05 11:16:48.346   758  1337 E Watchdog: !@Sync 22
,07-05 11:16:48.836   305   305 E SMD     : DCD ON
,07-05 11:16:51.836   305   305 E SMD     : DCD ON
,07-05 11:16:54.846   305   305 E SMD     : DCD ON
,07-05 11:16:56.046   758  1433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:16:56.046   758  1433 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:16:56.046   758  1433 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:16:56.056   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:16:56.056   758   758 I MotionRecognitionService: Plugged
,07-05 11:16:56.056   758   758 I MotionRecognitionService: setPowerConnected  = true
07-05 11:16:56.056  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 11:16:56.056  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:16:56.056  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:16:56.066  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:16:56.066  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:16:56.066   758  1433 D BatteryService: stay LED for fully charged
,07-05 11:16:56.066  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:16:56.066  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:16:56.066  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:16:56.096   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450
,07-05 11:16:57.846   305   305 E SMD     : DCD ON
,07-05 11:17:00.846   305   305 E SMD     : DCD ON
,07-05 11:17:03.846   305   305 E SMD     : DCD ON
,07-05 11:17:06.106   758   778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:17:06.106   758   778 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:17:06.106   758   778 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450,
07-05 11:17:06.116   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:17:06.116   758   758 I MotionRecognitionService: Plugged
,07-05 11:17:06.116  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 11:17:06.116  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:17:06.126  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:17:06.126   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:17:06.126  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:17:06.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:17:06.126   758   778 D BatteryService: stay LED for fully charged
07-05 11:17:06.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:17:06.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:17:06.126  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:17:06.156   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450
,07-05 11:17:06.846   305   305 E SMD     : DCD ON
,07-05 11:17:09.846   305   305 E SMD     : DCD ON
,07-05 11:17:12.846   305   305 E SMD     : DCD ON
,07-05 11:17:15.846   305   305 E SMD     : DCD ON
,07-05 11:17:16.166   758  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:17:16.206   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450
,07-05 11:17:18.346   758  1337 E Watchdog: !@Sync 23
,07-05 11:17:18.846   305   305 E SMD     : DCD ON
,07-05 11:17:21.846   305   305 E SMD     : DCD ON
,07-05 11:17:24.846   305   305 E SMD     : DCD ON
,07-05 11:17:26.226   758  3296 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:17:26.236   758  3296 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:17:26.236   758  3296 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:17:26.236   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:17:26.236  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:17:26.236  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:17:26.236   758   758 I MotionRecognitionService: Plugged
07-05 11:17:26.236   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:17:26.236  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:17:26.246  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:17:26.246  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:17:26.246   758  3296 D BatteryService: stay LED for fully charged
,07-05 11:17:26.246  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:17:26.246  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:17:26.246  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:17:26.266   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450
,07-05 11:17:27.846   305   305 E SMD     : DCD ON
,07-05 11:17:30.856   305   305 E SMD     : DCD ON
,07-05 11:17:32.436   758  1050 I PowerManagerService: [PWL] Off : 680s ago
,07-05 11:17:33.856   305   305 E SMD     : DCD ON
,07-05 11:17:36.296   758  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:17:36.316   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450
,07-05 11:17:36.856   305   305 E SMD     : DCD ON
,07-05 11:17:39.856   305   305 E SMD     : DCD ON
,07-05 11:17:42.856   305   305 E SMD     : DCD ON
,07-05 11:17:45.856   305   305 E SMD     : DCD ON
,07-05 11:17:46.346   758  1668 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:17:46.376   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,07-05 11:17:48.356   758  1337 E Watchdog: !@Sync 24
,07-05 11:17:48.856   305   305 E SMD     : DCD ON
,07-05 11:17:51.856   305   305 E SMD     : DCD ON
,07-05 11:17:54.856   305   305 E SMD     : DCD ON
,07-05 11:17:56.406   758  1433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:17:56.406   758  1433 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:17:56.416   758  1433 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:17:56.416   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:17:56.416   758   758 I MotionRecognitionService: Plugged
,07-05 11:17:56.416  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 11:17:56.416  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:17:56.426  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:17:56.426   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:17:56.426  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:17:56.426  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:17:56.426  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:17:56.426  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:17:56.426   758  1433 D BatteryService: stay LED for fully charged
,07-05 11:17:56.426  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:17:56.446   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-05 11:17:57.856   305   305 E SMD     : DCD ON
,07-05 11:18:00.856   305   305 E SMD     : DCD ON
,07-05 11:18:03.856   305   305 E SMD     : DCD ON
,07-05 11:18:06.466   758   778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:18:06.476   758   778 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:18:06.476   758   778 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:18:06.476   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:18:06.476  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:18:06.476  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:18:06.476   758   758 I MotionRecognitionService: Plugged
,07-05 11:18:06.476   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:18:06.486  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:18:06.486  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:18:06.486  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 11:18:06.486   758   778 D BatteryService: stay LED for fully charged
,07-05 11:18:06.486  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:18:06.486  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:18:06.486  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:18:06.506   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 11:18:06.856   305   305 E SMD     : DCD ON
,07-05 11:18:09.866   305   305 E SMD     : DCD ON
,07-05 11:18:12.866   305   305 E SMD     : DCD ON
,07-05 11:18:15.866   305   305 E SMD     : DCD ON
,07-05 11:18:16.526   758  1143 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:18:16.536   758  1143 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:18:16.536   758  1143 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:18:16.536   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:18:16.536  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:18:16.536  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:18:16.536   758   758 I MotionRecognitionService: Plugged
,07-05 11:18:16.536   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:18:16.546  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:18:16.546  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:18:16.546  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:18:16.546   758  1143 D BatteryService: stay LED for fully charged
,07-05 11:18:16.546  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:18:16.546  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:18:16.546  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:18:16.566   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:18:18.356   758  1337 E Watchdog: !@Sync 25
,07-05 11:18:18.866   305   305 E SMD     : DCD ON
,07-05 11:18:21.866   305   305 E SMD     : DCD ON
,07-05 11:18:24.866   305   305 E SMD     : DCD ON
,07-05 11:18:26.586   758   778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:18:26.616   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:18:27.866   305   305 E SMD     : DCD ON
,07-05 11:18:30.866   305   305 E SMD     : DCD ON
,07-05 11:18:33.866   305   305 E SMD     : DCD ON
,07-05 11:18:36.646   758  1644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:18:36.656   758  1644 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:18:36.656   758  1644 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 11:18:36.656   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:18:36.656  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:18:36.656  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:18:36.656   758   758 I MotionRecognitionService: Plugged
07-05 11:18:36.656   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:18:36.666  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:18:36.666  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:18:36.666  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:18:36.666  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:18:36.666  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:18:36.666  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:18:36.666   758  1644 D BatteryService: stay LED for fully charged
,07-05 11:18:36.686   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:18:36.866   305   305 E SMD     : DCD ON
,07-05 11:18:39.866   305   305 E SMD     : DCD ON
,07-05 11:18:42.866   305   305 E SMD     : DCD ON
,07-05 11:18:45.866   305   305 E SMD     : DCD ON
,07-05 11:18:46.706   758  3296 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:18:46.736   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:18:48.356   758  1337 E Watchdog: !@Sync 26
,07-05 11:18:48.876   305   305 E SMD     : DCD ON
,07-05 11:18:51.876   305   305 E SMD     : DCD ON
,07-05 11:18:54.876   305   305 E SMD     : DCD ON
,07-05 11:18:56.766   758  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:18:56.796   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:18:57.456   758  1050 I PowerManagerService: [PWL] Off : 765s ago
,07-05 11:18:57.876   305   305 E SMD     : DCD ON
,07-05 11:19:00.876   305   305 E SMD     : DCD ON
,07-05 11:19:03.876   305   305 E SMD     : DCD ON
,07-05 11:19:06.836   758  1234 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:19:06.856   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:19:06.876   305   305 E SMD     : DCD ON
,07-05 11:19:09.876   305   305 E SMD     : DCD ON
,07-05 11:19:12.876   305   305 E SMD     : DCD ON
,07-05 11:19:15.876   305   305 E SMD     : DCD ON
,07-05 11:19:16.896   758   778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:19:16.896   758   778 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:19:16.896   758   778 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:19:16.896   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:19:16.906  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:19:16.906   758   758 I MotionRecognitionService: Plugged
,07-05 11:19:16.906  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:19:16.906   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:19:16.906   758   778 D BatteryService: stay LED for fully charged
,07-05 11:19:16.916  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:19:16.916  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:19:16.916  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:19:16.936   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:19:16.936  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:19:16.936  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:19:16.936  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:19:18.366   758  1337 E Watchdog: !@Sync 27
,07-05 11:19:18.876   305   305 E SMD     : DCD ON
,07-05 11:19:21.876   305   305 E SMD     : DCD ON
,07-05 11:19:24.446   758  1120 D InputReader: Input event: value=1
,07-05 11:19:24.446   758  1120 D InputReader: !@notifyKey(116), action=0
,07-05 11:19:24.456   758  1120 D InputManager-JNI: !@interceptKeyBeforeQueueing(116), action=0
,07-05 11:19:24.466   758  1120 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 758  pkgName : WAKEUP_BOOSTER@32
,07-05 11:19:24.476   758  1120 E SamsungWindowManager: mCoreNumLockHelper.acquire
,07-05 11:19:24.476   758  1120 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 758) eventTime = 834957 event = 1
,07-05 11:19:24.476   758  1120 I PowerManagerService: !@[ps] Screen__On  - 1 :  wakeUpWithReason: 1 (uid: 1000 pid: 758)
07-05 11:19:24.476   758  1120 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-05 11:19:24.486   758  1171 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@35695aab)
,07-05 11:19:24.486   758  1120 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
07-05 11:19:24.486   758  1120 D PowerManagerService: [s] UserActivityState : 0 -> 1
07-05 11:19:24.486  1191  1215 D KeyguardViewMediator: onScreenTurnedOn, seq = 2
07-05 11:19:24.486  1191  1215 D KeyguardViewMediator: notifyScreenOnLocked
,07-05 11:19:24.486  1191  1191 D KeyguardViewMediator: handleNotifyScreenOn
,07-05 11:19:24.486   758  1050 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-05 11:19:24.486   758  1050 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-05 11:19:24.486   758  1050 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 11:19:24.486  1191  1191 D StatusBarKeyguardViewManager: onScreenTurnedOn()
07-05 11:19:24.486  1191  1191 D KeyguardViewBase: screen on, instance 382d25ff
07-05 11:19:24.486   758  1044 D SContextService: 	.registerCallback : 1, client=
,07-05 11:19:24.486   758  1120 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
07-05 11:19:24.486   758  1120 D InputManager-JNI: !@handleInterceptActions(116), action=0, wmActions=0
,07-05 11:19:24.486   758  1044 W CAE     : setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
07-05 11:19:24.486   758  1044 I CAE     : setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
07-05 11:19:24.486   758  1044 I CAE     : setCAProperty(ContextAwareService.java:469) - result : true
07-05 11:19:24.486   758  1044 W CAE     : setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
,07-05 11:19:24.486   758  1044 D SContextService: sendAttribute() : service = Auto Rotation
07-05 11:19:24.486   758  1044 W CAE     : registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
07-05 11:19:24.486   758  1044 V CAE     : start(ContextProvider.java:126)
,07-05 11:19:24.486  1191  1191 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
07-05 11:19:24.486  1191  1191 D KeyguardSecurityView: showSecurityScreen(None)
07-05 11:19:24.486  1191  1191 D KeyguardUnlockView: outRect: Rect(0, 99 - 1080, 1920)
07-05 11:19:24.486  1191  1191 D KeyguardUnlockView: isValidRect: true
07-05 11:19:24.486  1191  1191 I WaterColor Keyguard: showUnlockAffordance
,07-05 11:19:24.496  1191  1191 D VisualEffectCircleUnlockEffect: KeyguardEffectViewNone : screenTurnedOn
07-05 11:19:24.496  1191  1191 I WaterColor Keyguard: screenTurnedOn
07-05 11:19:24.496  1191  1191 D SecKeyguardCircleView: onScreenTurnedOn
07-05 11:19:24.496  1191  1573 D TEST    : run!!!
,07-05 11:19:24.496  1191  1573 I WaterColorEffect_View: showAffordanceEffect
07-05 11:19:24.496  1191  1573 I WaterColor_Renderer: clearEffect()
,07-05 11:19:24.496   758  3296 E Sensors : Acc old sensor_state 8192, new sensor_state : 8193 en : 1
07-05 11:19:24.496   758  1171 D InputManager-JNI: setDeviceInteractive: 1
,07-05 11:19:24.496   758  1044 V CAE     : clear(AutoRotationRunner.java:182)
07-05 11:19:24.496   758  1176 D PowerManagerService: !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
,07-05 11:19:24.496   758  1176 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
07-05 11:19:24.496   758  1176 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
07-05 11:19:24.496   758  1176 I QCOM PowerHAL: Got set_interactive hint
,07-05 11:19:24.496   266   266 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6962000
07-05 11:19:24.496   266   266 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-05 11:19:24.496  1191  1573 I WaterColor_Renderer: dirty mode
,07-05 11:19:24.506   758  1046 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,07-05 11:19:24.506  1191  1191 D SensorManager: registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
,07-05 11:19:24.506   758  1044 V CAE     : enable(AutoRotationRunner.java:158)
07-05 11:19:24.506   758  1044 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
07-05 11:19:24.506   758  1044 D SensorHubManager: SendSensorHubData: send data = -79, 7, 0, 0
,07-05 11:19:24.516   324   324 D Sensorhubs: sendContextData: -79, 7, 0, 0
,07-05 11:19:24.516  1191  1191 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
07-05 11:19:24.516  1191  1191 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1845 should be AT_MOST
,07-05 11:19:24.536   758   758 V ActivityManager: Display changed displayId=0
,07-05 11:19:24.536  1191  1191 D QSpanel : label top:23
07-05 11:19:24.536  1191  1191 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-05 11:19:24.536  1191  1191 D QSpanel : label top:23
07-05 11:19:24.536  1191  1191 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-05 11:19:24.536  1191  1191 D QSpanel : label top:23
07-05 11:19:24.536  1191  1191 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-05 11:19:24.536  1191  1191 D QSpanel : label top:0
07-05 11:19:24.536  1191  1191 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-05 11:19:24.536  1191  1191 D QSpanel : label top:23
07-05 11:19:24.536  1191  1191 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-05 11:19:24.536  1191  1191 D QSpanel : label top:0
07-05 11:19:24.536  1191  1191 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-05 11:19:24.536  1191  1191 D QSpanel : label top:0
07-05 11:19:24.536  1191  1191 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-05 11:19:24.536  1191  1191 D QSpanel : label top:0
07-05 11:19:24.536  1191  1191 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-05 11:19:24.536  1191  1191 D QSpanel : label top:0
07-05 11:19:24.536  1191  1191 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-05 11:19:24.536  1191  1191 D QSpanel : label top:0
07-05 11:19:24.536  1191  1191 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-05 11:19:24.536   758   758 D LightsService: [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 758) 
07-05 11:19:24.536   758   758 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
07-05 11:19:24.536   758   758 D BatteryService: turn off LED
,07-05 11:19:24.536   758  1091 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
07-05 11:19:24.536   758  1091 D lights  : led_pattern : 0 +
07-05 11:19:24.536   758  1091 D lights  : led_pattern : 0 -
,07-05 11:19:24.536   758  7537 D InputManager-JNI: sysfs_write +: /sys/class/input/event3/device/enabled: 1
07-05 11:19:24.536   758  7538 D InputManager-JNI: sysfs_write +: /sys/class/input/event2/device/enabled: 1
07-05 11:19:24.536   758  7537 D InputManager-JNI: sysfs_write -: /sys/class/input/event3/device/enabled: 1
07-05 11:19:24.536   758  7536 D InputManager-JNI: sysfs_write +: /sys/class/input/event4/device/enabled: 1
,07-05 11:19:24.546   758  1091 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-05 11:19:24.546   758  1044 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-05 11:19:24.546   758  1044 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,07-05 11:19:24.556   758   778 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-05 11:19:24.556  1191  1191 D StatusBarKeyguardViewManager: callback.onShown()
,07-05 11:19:24.556  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 11:19:24.566  1191  1191 D KeyguardViewMediator: handleKeyguardDoneDrawing
07-05 11:19:24.566  1191  1191 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 7 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte level=2
07-05 11:19:24.566  1191  1191 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 7 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte
,07-05 11:19:24.566  1191  1191 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=2
07-05 11:19:24.566  1191  1191 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_2 mContentDescriptionPhoneSignal = Two bars of phone signal
07-05 11:19:24.566  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 11:19:24.566  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 11:19:24.566  1191  1191 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 11:19:24.566  1191  1191 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-05 11:19:24.566  1191  1191 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 11:19:24.566  1191  1191 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 7 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte level=2
07-05 11:19:24.566  1191  1191 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 7 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte
07-05 11:19:24.566  1191  1191 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=2
07-05 11:19:24.566  1191  1191 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_2 mContentDescriptionPhoneSignal = Two bars of phone signal
07-05 11:19:24.566  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 11:19:24.566  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 11:19:24.576   758   758 I CAE     : handleMessage(CaPowerManager.java:188) - AP_WAKEUP
07-05 11:19:24.576   758   758 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
07-05 11:19:24.576   758   758 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
07-05 11:19:24.576   758   758 D SensorHubManager: SendSensorHubData: send data = -76, 13, -47, 0
07-05 11:19:24.576   324   568 D Sensorhubs: sendContextData: -76, 13, -47, 0
07-05 11:19:24.586   758   758 D InputMethodManagerService: [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
07-05 11:19:24.586   758   758 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
07-05 11:19:24.596   758  1125 E MotionRecognitionService:  handler : SCREEN_ON end
07-05 11:19:24.596   758  1044 D CAE     : doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,07-05 11:19:24.596   758  1044 I CAE     : displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
07-05 11:19:24.596   758  1044 D CAE     : showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
07-05 11:19:24.596   758  1044 I CAE     : showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@2f10711e, Service : AUTO_ROTATION(1)
07-05 11:19:24.596   758  1044 W CAE     : registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
07-05 11:19:24.596   758  1044 D SContextService: addSContextService() : service = Auto Rotation
07-05 11:19:24.596   758  1044 D SContextService: ===== SContext Service List =====
07-05 11:19:24.596   758  1044 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@27ab7dff, Service : Auto Rotation
07-05 11:19:24.596   758  1044 D SContextManager:   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@22bde508, service=Auto Rotation
07-05 11:19:24.596   758  1044 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
07-05 11:19:24.596   758  1050 I DisplayPowerController: Unblocked screen on after 115 ms
07-05 11:19:24.596   758  1050 D DisplayPowerState: !@ ColorFade exit
07-05 11:19:24.606   758   758 D NotificationService: ACTION_SCREEN_ON
07-05 11:19:24.606   758   758 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 758) 
07-05 11:19:24.606   758   758 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
07-05 11:19:24.606   266  1733 I SurfaceFlinger: id=11 Removed DolorFade (8/8)
07-05 11:19:24.606   266  1733 I SurfaceFlinger: id=11 Removed DolorFade (-2/8)
07-05 11:19:24.606   758  1050 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-05 11:19:24.616   758  1050 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-05 11:19:24.616   758  1091 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
07-05 11:19:24.616   758  1091 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
07-05 11:19:24.616   758  1050 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 11:19:24.616   758  1175 D lights  : lcd : 203 +
07-05 11:19:24.616   758  1175 D lights  : lcd : 203 -
07-05 11:19:24.616   758  1050 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-05 11:19:24.616   758  1050 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 11:19:24.616   758  1050 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 11:19:24.616   758  1050 D PowerManagerService: SecHardwareInterface.setBatteryADC : true
07-05 11:19:24.616   758  1050 D PowerManagerService: [input device light] setInputDeviceLightOn is called : 1
07-05 11:19:24.616   312   674 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-05 11:19:24.616   312   674 V voice   : voice_set_parameters: enter: screen_state=on
07-05 11:19:24.616   312   674 V voice   : voice_set_parameters: exit with code(-2)
07-05 11:19:24.616   312   674 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-05 11:19:24.616   312   674 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-05 11:19:24.616   312   674 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-05 11:19:24.616   312   674 V audio_hw_primary: adev_set_parameters: exit
07-05 11:19:24.616   758  1172 D PowerManagerService: [input device light] handleInputDeviceLightOn
07-05 11:19:24.616   758  1172 D lights  : button : 1 +
07-05 11:19:24.616   758  1172 D lights  : button : 1 -
07-05 11:19:24.616   758  1050 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-05 11:19:24.616   758  1175 D lights  : lcd : 255 +
07-05 11:19:24.616   758  1175 D lights  : lcd : 255 -
07-05 11:19:24.616   758  1050 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 11:19:24.616   758  1050 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-05 11:19:24.616   758  1050 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 11:19:24.616   758  1148 E native  : do suspend false
07-05 11:19:24.626  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
07-05 11:19:24.626  1301  1301 I wpa_supplicant: reset timer : RESET_TIMER 1
07-05 11:19:24.626  1301  1301 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-05 11:19:24.626  1301  1301 I wpa_supplicant: P2P: Current p2p state = IDLE
07-05 11:19:24.626  1301  1301 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-05 11:19:24.626   758   758 I SecExternalDisplayIntents_Java: Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,07-05 11:19:24.636  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
07-05 11:19:24.656   758  7536 D InputManager-JNI: sysfs_write -: /sys/class/input/event4/device/enabled: 1
07-05 11:19:24.666   758  1120 D InputReader: Input event: value=0
07-05 11:19:24.666   758  1120 D InputReader: !@notifyKey(116), action=1
07-05 11:19:24.666   758  1120 D InputManager-JNI: !@interceptKeyBeforeQueueing(116), action=1
07-05 11:19:24.666   758  1120 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 758  tag : WAKEUP_BOOSTER@32
07-05 11:19:24.666   758  1120 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 758  pkgName : WAKEUP_BOOSTER@32
07-05 11:19:24.666   758  1120 E SamsungWindowManager: mCoreNumLockHelper.acquire
07-05 11:19:24.666   758  1120 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 758) eventTime = 835170 event = 1
07-05 11:19:24.666   758  1120 D InputManager-JNI: !@handleInterceptActions(116), action=1, wmActions=0
,07-05 11:19:24.746   266   515 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,07-05 11:19:24.746   266   266 E qdexternal: writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
07-05 11:19:24.746   266   266 D qdhwcomposer: hwc_blank: Done unblanking display: 0
07-05 11:19:24.746   758  1176 D SurfaceControl: Excessive delay in setPowerMode(): 252ms
07-05 11:19:24.746   758  1176 D PowerManagerService: Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 255ms
07-05 11:19:24.746   758  1046 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
07-05 11:19:24.746   758  1046 D IpRemoteDisplayController: Bridge Server is not available
,07-05 11:19:24.756   758   989 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,07-05 11:19:24.756   758   758 D PersonaManagerService: ACTION_SCREEN_ON onReceive
07-05 11:19:24.756   758  1067 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
,07-05 11:19:24.766  1413  1413 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_LOCKED by isKeyguardLocked()
,07-05 11:19:24.766  1413  1413 D NativeNfcManager: power state=3
,07-05 11:19:24.776  1413  7553 D NfcService: call the applyRouting
,07-05 11:19:24.776  1816  1816 D accuweather: [Accuweather J]>>> SWW:67 [0:0] =============== BR act = androidintentactionSCREEN_ON
07-05 11:19:24.776  1816  1816 D accuweather: [Accuweather J]>>> SWW:70 [0:0] =============== androidintentactionSCREEN_ON instance : [0]1
,07-05 11:19:24.786  1695  1695 I SamsungIME: getNextShiftState() cursorCapsMode : 0
,07-05 11:19:24.796   758  1433 D ActivityManager: caller:android.app.ApplicationThreadProxy@16a287cc, r.packageName :com.google.android.gms
,07-05 11:19:24.816   758  3059 D SSRM:a  : DeviceInfo:: 000100100000
07-05 11:19:24.816   758  3059 D SSRM:a  : SettingsAirViewInfo:: 010100000
,07-05 11:19:24.816   758  3059 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 11:19:24.816  1413  7553 D NfcService: index : 0
07-05 11:19:24.816  1413  7553 D NfcService: index : 1
07-05 11:19:24.816  1413  7553 D NfcService: index : 2
,07-05 11:19:24.826  4703  4703 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:43 [0:0] onReceive() action : androidintentactionSCREEN_ON
,07-05 11:19:24.826  4703  4703 E com.samsung.app: [MSC]>>>News_Daemon(E) DR:71 [0:0] [NameNotFoundException] process restart With Widget !!!!!
,07-05 11:19:24.826  4703  4703 W com.samsung.app: [MSC]>>>News_Daemon(E) U:95 [0:0]  ::::::::: Available Internal MemorySize ::::::::: = 25739256k
,07-05 11:19:24.836  4703  4703 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:104 [0:0] checkPackageNameList is Empty
,07-05 11:19:24.836  4703  4703 I com.samsung.app: [MSC]>>>News_Daemon(E) DR:110 [0:0] serviceStatus = 0 checkPackageNameList = 0
,07-05 11:19:24.836  4703  4703 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:145 [0:0] [CARS][AUTOREFRESHKEY] --> 0
,07-05 11:19:24.836  4703  4703 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:146 [0:0] [CARS][NRT] = 0
07-05 11:19:24.836  4703  4703 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:147 [0:0] [CARS][DT] = 1467710364842
,07-05 11:19:24.856   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:19:24.866  4703  4703 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,07-05 11:19:24.866  4703  4703 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
07-05 11:19:24.866  4703  4703 D comsamsunglog: [MSC_Accu_Daemon]>>> daemonapp [Version : 150820735400 ] [ 1 ] 
07-05 11:19:24.866  4703  4703 D comsamsunglog: [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
,07-05 11:19:24.866  4703  4703 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
07-05 11:19:24.866  4703  4703 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-05 11:19:24.866  4703  4703 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,07-05 11:19:24.866  4703  4703 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 11:19:24.876  4703  4703 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 11:19:24.876  4703  4703 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 11:19:24.876   305   305 E SMD     : DCD ON
,07-05 11:19:24.876  4703  4703 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 11:19:24.886  4703  4703 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,07-05 11:19:24.886  4703  4703 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:616 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
07-05 11:19:24.886  4703  4703 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 11:19:24.896  4703  4703 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:618 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,07-05 11:19:24.896  4703  4703 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:619 [0:0] [ASO][NUT] = 07/05/2016 04:28 PM
,07-05 11:19:24.896  4703  4703 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:620 [0:0] [ASO][CT] = 07/05/2016 11:19 AM
07-05 11:19:24.896  4703  4703 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-05 11:19:24.896  4703  4703 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,07-05 11:19:24.926   758  7538 D InputManager-JNI: sysfs_write -: /sys/class/input/event2/device/enabled: 1
,07-05 11:19:24.926   758  1171 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-05 11:19:24.926   758  1111 V AlarmManager: waitForAlarm result :8
,07-05 11:19:24.926   758  7556 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-05 11:19:24.926   758  7556 D NetworkStatsFactory: UpdateStatsForKnox
,07-05 11:19:24.926   758   758 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-05 11:19:24.946   758  7556 D NetworkStatsFactory: UpdateStatsForKnox
,07-05 11:19:24.986   758  7556 I BatteryStatsDumper: Screen bin #0: time=0 power=0.0
07-05 11:19:24.986   758  7556 I BatteryStatsDumper: Screen bin #1: time=0 power=0.0
07-05 11:19:24.986   758  7556 I BatteryStatsDumper: Screen bin #2: time=0 power=0.0
07-05 11:19:24.986   758  7556 I BatteryStatsDumper: Screen bin #3: time=0 power=0.0
07-05 11:19:24.986   758  7556 I BatteryStatsDumper: Screen bin #4: time=6426 power=0.366282
07-05 11:19:24.986   758  7556 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-05 11:19:24.996  1191  1191 I WaterColorEffect_View: showAffordanceEffect Renderer.handleTouchEvent(0, 540, 1009
,07-05 11:19:24.996  1191  1191 I WaterColor_Renderer: Renderer handleTouchEvent action = 0
,07-05 11:19:25.376   758  7556 I BatteryStatsDumper: Writing to database completed
,07-05 11:19:25.626   758  1091 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
07-05 11:19:25.626   758  1091 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-05 11:19:25.666   758   758 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 758  tag : WAKEUP_BOOSTER@32
,07-05 11:19:26.006  1191  1573 I WaterColor_Renderer: fps 60.396038
,07-05 11:19:26.116   758  1172 D PowerManagerService: [input device light] handleInputDeviceLightOff
,07-05 11:19:26.116   758  1172 D lights  : button : 0 +
,07-05 11:19:26.156   758  1172 D lights  : button : 0 -
,07-05 11:19:26.156  1191  1573 I WaterColor_Renderer: dirty mode
,07-05 11:19:26.156  1191  1573 I WaterColor_Renderer: fps 60.150375
,07-05 11:19:26.366   758  1120 D InputReader: Input event: value=1
07-05 11:19:26.366   758  1120 D InputReader: !@notifyKey(116), action=0
07-05 11:19:26.366   758  1120 D InputManager-JNI: !@interceptKeyBeforeQueueing(116), action=0
,07-05 11:19:26.366   758  1120 D InputManager-JNI: !@handleInterceptActions(116), action=0, wmActions=0
,07-05 11:19:26.586   758  1120 D InputReader: Input event: value=0
07-05 11:19:26.586   758  1120 D InputReader: !@notifyKey(116), action=1
07-05 11:19:26.586   758  1120 D InputManager-JNI: !@interceptKeyBeforeQueueing(116), action=1
,07-05 11:19:26.586   758  1120 D PowerManagerService: [api] [s] goToSleep: 4 (uid: 1000 pid: 758) eventTime = 837090
07-05 11:19:26.586   758  1120 I PowerManagerService: !@[ps] Screen__Off - 1 :  goToSleep:  (uid: 1000 pid: 758) (4)
,07-05 11:19:26.586   758  1120 I PowerManagerService: Going to sleep due to power button (uid 1000)...
07-05 11:19:26.586   758  1171 D InputManager-JNI: setDeviceInteractive: 0
07-05 11:19:26.586   758  1120 D InputManager-JNI: !@handleInterceptActions(116), action=1, wmActions=0
07-05 11:19:26.586   758  1050 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-05 11:19:26.586   758  1050 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 11:19:26.586   758  1050 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 11:19:26.586   758  1050 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
07-05 11:19:26.586   758  1050 D PowerManagerService: SecHardwareInterface.setBatteryADC : false
,07-05 11:19:26.586   758  1050 D PowerManagerService: handleSandman : startDream()
07-05 11:19:26.586   758  1050 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
07-05 11:19:26.586   758  1050 I PowerManagerService: Sleeping (uid 1000)...
07-05 11:19:26.586   758  1050 D PowerManagerService: [s] UserActivityState : 1 -> 0
07-05 11:19:26.586   758  1050 D PowerManagerService: [input device light] setInputDeviceLightOn is called : 0
07-05 11:19:26.586   758  1172 D PowerManagerService: [input device light] handleInputDeviceLightOff
07-05 11:19:26.586   758  7566 D InputManager-JNI: sysfs_write +: /sys/class/input/event2/device/enabled: 0
07-05 11:19:26.586   266   266 I SurfaceFlinger: id=14 createSurf (1080x1920),2 flag=404, DolorFade
,07-05 11:19:26.586   758  7566 D InputManager-JNI: sysfs_write -: /sys/class/input/event2/device/enabled: 0
,07-05 11:19:26.586   758  7565 D InputManager-JNI: sysfs_write +: /sys/class/input/event3/device/enabled: 0
07-05 11:19:26.586   758  7565 D InputManager-JNI: sysfs_write -: /sys/class/input/event3/device/enabled: 0
07-05 11:19:26.586   758  7564 D InputManager-JNI: sysfs_write +: /sys/class/input/event4/device/enabled: 0
,07-05 11:19:26.586   758  7564 D InputManager-JNI: sysfs_write -: /sys/class/input/event4/device/enabled: 0
07-05 11:19:26.586   758  1171 D SContextService: 	.unregisterCallback : 1, client=
07-05 11:19:26.586   758  1171 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@27ab7dff, Service = Auto Rotation, used = 1
07-05 11:19:26.586   758  1171 W CAE     : unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,07-05 11:19:26.586   758  1171 V CAE     : stop(ContextProvider.java:149)
07-05 11:19:26.586   758  1171 V CAE     : clear(AutoRotationRunner.java:182)
07-05 11:19:26.586   758  1171 V CAE     : disable(AutoRotationRunner.java:171)
07-05 11:19:26.586   758  1171 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
07-05 11:19:26.586   758  1171 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
07-05 11:19:26.586   324   324 D Sensorhubs: sendContextData: -78, 7, 0, 0
,07-05 11:19:26.596   758  1171 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-05 11:19:26.596   758  1171 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,07-05 11:19:26.646   758  1050 D DisplayPowerController: ColorFade: onAnimationStart
,07-05 11:19:26.646   758  1050 D DisplayPowerController: getFinalBrightness : 255 -> 0
07-05 11:19:26.646   758  1050 D DisplayPowerController: animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 11:19:26.646   758  1171 D CAE     : doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,07-05 11:19:26.646   758  1171 I CAE     : displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
07-05 11:19:26.646   758  1171 D CAE     : showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
07-05 11:19:26.646   758  1171 W CAE     : unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,07-05 11:19:26.646   758  1171 D SContextService: removeSContextService() : service = Auto Rotation
07-05 11:19:26.646   758  1171 D SContextService: ===== SContext Service List =====
07-05 11:19:26.646   758  1171 D SContextManager:   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@22bde508, service=Auto Rotation
,07-05 11:19:26.646  1191  3057 D PersonaManager: isKioskContainerExistOnDevice
07-05 11:19:26.646  1191  3057 D KeyguardViewMediator: onScreenTurnedOff(2)
07-05 11:19:26.646  1191  3057 I KeyguardEffectViewController: *** KeyguardEffectView getInstanceIfExists ***
07-05 11:19:26.656  1191  3057 D KeyguardEffectViewController: changeWallpaperByScreenOff()
,07-05 11:19:26.656  1191  3057 D KeyguardViewMediator: notifyScreenOffLocked
07-05 11:19:26.656  1191  3057 E KeyguardViewMediator: resetStateLocked
,07-05 11:19:26.656  1191  1191 D KeyguardViewMediator: handleNotifyScreenOff
07-05 11:19:26.656  1191  1191 D KeyguardViewBase: screen off, instance 382d25ff at 837161
07-05 11:19:26.656   758   758 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 758) 
07-05 11:19:26.656   758   758 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,07-05 11:19:26.656  1191  1191 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=true)
07-05 11:19:26.656  1191  1191 D KeyguardSecurityView: showSecurityScreen(None)
07-05 11:19:26.656   758   758 E LightSensor: Light old sensor_state 8193, new sensor_state : 8705 en : 1
,07-05 11:19:26.656  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
07-05 11:19:26.656  1191  1191 D KeyguardViewMediator: Kiosk container not exists on device.
07-05 11:19:26.656  1191  1191 D KeyguardViewMediator: handleReset
,07-05 11:19:26.656  1191  1191 D KeyguardEffectViewUtil: wallpaperType :1
,07-05 11:19:26.656  1191  1191 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
07-05 11:19:26.656  1191  1191 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
07-05 11:19:26.656  1191  1191 D PhoneStatusBar: updateKeyguardState :1
07-05 11:19:26.656  1191  1191 D StatusBar: LSSN:1
,07-05 11:19:26.656  1191  1191 D StatusBar: fullBouncer=false
,07-05 11:19:26.656  1191  1191 D StatusBar: SLN:S
07-05 11:19:26.656  1191  1191 E LSO     : LSO Service is not yet ready!!!
07-05 11:19:26.656  1191  1191 D StatusBar-QSPanel: setSingleLine:true
,07-05 11:19:26.656  1191  1191 D StatusBar-QSPanel: updateButtonInfo mButtonWidth : 206 mColumns:5 orien: 1 displayWidth:1032
07-05 11:19:26.656  1191  1191 D StatusBar-QSPanel: setSingleLine height:0
07-05 11:19:26.666  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:19:26.666  1191  1191 D STATUSBAR-PhoneStatusBar: showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
07-05 11:19:26.666   758   758 D SensorManager: registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
07-05 11:19:26.666  1191  1191 I PhoneStatusBar: Icon Only
07-05 11:19:26.666  1191  1191 I StatusBar: Icon Only
,07-05 11:19:26.666   758   758 D BatteryService: turn on LED for fully charged
07-05 11:19:26.666  1191  1191 D PanelView: There is/are notification(s) 
,07-05 11:19:26.666  1191  1191 D PhoneStatusBar: updateQSpanelHeight: 279 height:591
07-05 11:19:26.666   758  1175 D lights  : lcd : 242 +
,07-05 11:19:26.666  1191  1191 D PanelView: setQsHeight mQsMin:0 mQsMax:705 mQsEx:0.0mQsPeek:591
07-05 11:19:26.666  1191  1191 I KeyguardEffectViewController: setKeyguardShowing = true
07-05 11:19:26.666  1191  1191 D KeyguardEffectViewController: reset()
07-05 11:19:26.666  1191  1191 D VisualEffectCircleUnlockEffect: KeyguardEffectViewNone : reset
,07-05 11:19:26.666  1191  1191 I WaterColor Keyguard: reset
07-05 11:19:26.666  1191  1573 I WaterColor_Renderer: clearEffect()
07-05 11:19:26.666  1191  1573 I WaterColor_Renderer: dirty mode
,07-05 11:19:26.666  1191  1191 D KeyguardEffectViewController: isFestivalActivated()false
,07-05 11:19:26.666  1191  1191 I KeyguardEffectViewController: setFestivalKeyguardShowing = true ,:false
07-05 11:19:26.666  1191  1191 D KeyguardEffectViewController: isFestivalActivated()false
07-05 11:19:26.666  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
,07-05 11:19:26.666  1191  1191 I PhoneStatusBar: Icon Only
07-05 11:19:26.666  1191  1191 I StatusBar: Icon Only
,07-05 11:19:26.676  1191  1191 D PanelView: There is/are notification(s) 
,07-05 11:19:26.676  1191  1191 D PanelView: There is/are notification(s) 
,07-05 11:19:26.676   758   758 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
07-05 11:19:26.676   758   758 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
07-05 11:19:26.676   758   758 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
,07-05 11:19:26.676   758   758 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
07-05 11:19:26.676  1191  1191 D PhoneStatusBar: updateKeyguardPreviousState :1
07-05 11:19:26.676   324   568 D Sensorhubs: sendContextData: -76, 13, -46, 0
07-05 11:19:26.676  1191  1191 D PhoneStatusBar: makeExpandedVisible:true
,07-05 11:19:26.676  1191  1191 D KeyguardEffectViewUtil: wallpaperType :1
07-05 11:19:26.676  1191  1191 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
07-05 11:19:26.676  1191  1191 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-05 11:19:26.676   758   779 D SecContentProvider2: uri = 14 selection = getSealedState
07-05 11:19:26.676   758   779 D SecContentProvider2: mCursor = null
07-05 11:19:26.676  1191  1191 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME recent clock search >
07-05 11:19:26.676   758  1480 D SecContentProvider2: uri = 14 selection = getSealedState
07-05 11:19:26.676   758  1480 D SecContentProvider2: mCursor = null
,07-05 11:19:26.676   758  1644 D SecContentProvider2: uri = 14 selection = getSealedState
07-05 11:19:26.676   758  1644 D SecContentProvider2: mCursor = null
07-05 11:19:26.676   758  1362 D SecContentProvider2: uri = 14 selection = getSealedState
,07-05 11:19:26.676   758  1362 D SecContentProvider2: mCursor = null
07-05 11:19:26.676  1191  1191 D StatusBar-DoNotDistrub: isDisableAlert isDormantModeOn:false isNotificationDisabled:true
,07-05 11:19:26.686  1191  1191 D KeyguardProperties: isIgnoreNationalRoaming() = false
,07-05 11:19:26.686   758   758 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 9, 19, 26,
07-05 11:19:26.686   758   758 D SensorHubManager: SendSensorHubData: send data = -63, 14, 9, 19, 26
07-05 11:19:26.686   324   324 D Sensorhubs: sendContextData: -63, 14, 9, 19, 26
07-05 11:19:26.686  1191  1191 D PhoneStatusBar: HomeCitySettingsDialog available = false, show = true
07-05 11:19:26.686  1191  1191 V KeyguardUpdateMonitor: *** unregister callback for com.android.keyguard.sec.SecKeyguardCircleView$1@1d283959
,07-05 11:19:26.686   758  1433 E Sensors : Acc old sensor_state 8705, new sensor_state : 8704 en : 0
,07-05 11:19:26.696   758  1175 D lights  : lcd : 242 -
,07-05 11:19:26.696   758  1175 D lights  : lcd : 209 +
,07-05 11:19:26.706   758   758 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,07-05 11:19:26.706  1191  1191 D SensorManager: unregisterListener ::   
,07-05 11:19:26.706  1191  1191 D KeyguardUnlockEventHandler: cleanUp()
,07-05 11:19:26.706   758  1125 E MotionRecognitionService:  handler : SCREEN_OFF end 
,07-05 11:19:26.706  1191  1191 I SecAttributionInfoView: onDetachedFromWindow
07-05 11:19:26.706  1191  1191 V KeyguardUpdateMonitor: *** unregister callback for com.android.keyguard.KeyguardSimpleHostView$1@39ed0746
,07-05 11:19:26.706  1191  1191 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardSimpleHostView$1@2d38231b
,07-05 11:19:26.716  1191  1191 V KeyguardUpdateMonitor: *** unregister callback for null
,07-05 11:19:26.716  1191  1191 D KeyguardSecurityView: AUTO_WIPE = false , IT Policy = false
07-05 11:19:26.716  1191  1191 I KeyguardSecurityView: addAttributionInfoViewIfNecessary
,07-05 11:19:26.716   758   758 D NotificationService: ACTION_SCREEN_OFF
,07-05 11:19:26.716   758   758 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 758) 
07-05 11:19:26.716   758   758 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,07-05 11:19:26.716   312   755 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-05 11:19:26.716   312   755 V voice   : voice_set_parameters: enter: screen_state=off
07-05 11:19:26.716   312   755 V voice   : voice_set_parameters: exit with code(-2)
07-05 11:19:26.716   312   755 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-05 11:19:26.716   312   755 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-05 11:19:26.716   312   755 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-05 11:19:26.716   312   755 V audio_hw_primary: adev_set_parameters: exit
,07-05 11:19:26.716   758  1148 E native  : do suspend true
,07-05 11:19:26.726  1191  1191 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
,07-05 11:19:26.726  1191  1191 D KeyguardSecurityView: showSecurityScreen(None)
07-05 11:19:26.726  1191  1191 V KeyguardSecurityView: inflating id = 2130968634
,07-05 11:19:26.726  1191  1191 D SecKeyguardBottomAreaView: mUseBackUp= falsemUseCenteredMessageArea= false
,07-05 11:19:26.726  1191  1191 D SecKeyguardBottomAreaView: shortcut value[0-off / 1-camera] = 1
07-05 11:19:26.726  1191  1191 D SecKeyguardBottomAreaView: mKidsModeEnabled= false
,07-05 11:19:26.736  1191  1191 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardMessageArea$2@1d2bd5f7
,07-05 11:19:26.736  1191  1191 V KeyguardUpdateMonitor: *** unregister callback for null
07-05 11:19:26.736   758  1175 D lights  : lcd : 209 -
07-05 11:19:26.736   758  1175 D lights  : lcd : 142 +
,07-05 11:19:26.736   758   758 I SecExternalDisplayIntents_Java: Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,07-05 11:19:26.736   758   758 I BackgroundCompactionService: Schedule Type1 BGCompaction
,07-05 11:19:26.736  1191  1191 D KeyguardUnlockView: mIsHelpTextEnabled= true
,07-05 11:19:26.746  1191  1191 D KeyguardUnlockView: hideBouncer mBouncerHelpText != null
,07-05 11:19:26.746  1191  1191 D KeyguardEffectViewUtil: wallpaperType :1
07-05 11:19:26.746  1191  1191 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
07-05 11:19:26.746  1191  1191 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-05 11:19:26.746  1191  1191 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.sec.SecKeyguardCircleView$1@31bed382
,07-05 11:19:26.746  1191  1191 V KeyguardUpdateMonitor: *** unregister callback for null
,07-05 11:19:26.746  1191  1191 I SecAttributionInfoView: onAttachedToWindow
,07-05 11:19:26.746  1191  1191 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,07-05 11:19:26.746  1191  1191 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
07-05 11:19:26.746   758  1175 D lights  : lcd : 142 -
07-05 11:19:26.746   758  1175 D lights  : lcd : 109 +
,07-05 11:19:26.756  1191  1191 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,07-05 11:19:26.756  1191  1191 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,07-05 11:19:26.756  1191  1191 D VisualEffectCircleUnlockEffect: KeyguardEffectViewNone : screenTurnedOff
,07-05 11:19:26.756  1191  1191 I WaterColor Keyguard: screenTurnedOff
07-05 11:19:26.756  1191  1573 I WaterColor_Renderer: clearEffect()
,07-05 11:19:26.756  1191  1573 I WaterColor_Renderer: dirty mode
,07-05 11:19:26.756  1191  1191 D SecKeyguardCircleView: onScreenTurnedOff
,07-05 11:19:26.756  1191  1191 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
,07-05 11:19:26.756  1191  1191 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1845 should be AT_MOST
,07-05 11:19:26.766   758  1175 D lights  : lcd : 109 -
07-05 11:19:26.766   758  1175 D lights  : lcd : 76 +
,07-05 11:19:26.766  1191  1191 D QSpanel : label top:23
07-05 11:19:26.766  1191  1191 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-05 11:19:26.766  1191  1191 D QSpanel : label top:23
07-05 11:19:26.766  1191  1191 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-05 11:19:26.766  1191  1191 D QSpanel : label top:23
07-05 11:19:26.766  1191  1191 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-05 11:19:26.766  1191  1191 D QSpanel : label top:0
07-05 11:19:26.766  1191  1191 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-05 11:19:26.766  1191  1191 D QSpanel : label top:23
07-05 11:19:26.766  1191  1191 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-05 11:19:26.766  1191  1191 D QSpanel : label top:0
07-05 11:19:26.766  1191  1191 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-05 11:19:26.766  1191  1191 D QSpanel : label top:0
07-05 11:19:26.766  1191  1191 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-05 11:19:26.766  1191  1191 D QSpanel : label top:0
07-05 11:19:26.766  1191  1191 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-05 11:19:26.766  1191  1191 D QSpanel : label top:0
07-05 11:19:26.766  1191  1191 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-05 11:19:26.766  1191  1191 D QSpanel : label top:0
07-05 11:19:26.766  1191  1191 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
07-05 11:19:26.766  1191  1191 D ScrimController: updateScrimKeyguard() mDozing=false, mBouncerShowing=false
,07-05 11:19:26.776  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 11:19:26.776  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 11:19:26.776  1191  1191 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 11:19:26.776  1191  1191 D StatusBar.NetworkController: applyOpen
,07-05 11:19:26.776  1191  1191 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 11:19:26.776  1191  1191 D StatusBar.NetworkController: applyOpen
,07-05 11:19:26.776  1191  1191 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 11:19:26.776  1191  1191 D StatusBar.NetworkController: applyOpen
07-05 11:19:26.776  1191  1191 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 11:19:26.776  1191  1191 D StatusBar.NetworkController: applyOpen
,07-05 11:19:26.776  1191  1191 D KeyguardViewMediator: handleKeyguardDoneDrawing
,07-05 11:19:26.786   758  1175 D lights  : lcd : 76 -
07-05 11:19:26.786   758  1175 D lights  : lcd : 42 +
,07-05 11:19:26.786   758  1046 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
07-05 11:19:26.786   758  1046 D IpRemoteDisplayController: Bridge Server is not available
,07-05 11:19:26.796  1191  1191 D VolumePanel.3848c9f5: forceTimeout delay=0 callers=com.android.systemui.volume.VolumePanel.postDismiss:2103 com.android.systemui.volume.VolumePanel$8.onReceive:1167 android.app.LoadedApk$ReceiverDispatcher$Args.run:923 
,07-05 11:19:26.796  1191  1191 D VolumePanel: mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,07-05 11:19:26.796  1191  1191 D VolumePanel: mCoverBroadcastReceiver: Screen OFF start
07-05 11:19:26.796  1191  1191 D VolumePanel: mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
07-05 11:19:26.796  1191  1191 D VolumePanel: mCoverBroadcastReceiver: Screen OFF end
07-05 11:19:26.796  1191  1191 D VolumePanel: mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,07-05 11:19:26.796   758   989 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,07-05 11:19:26.796   758  1175 D lights  : lcd : 42 -
07-05 11:19:26.796   758  1175 D lights  : lcd : 9 +
,07-05 11:19:26.806   758   758 D PersonaManagerService: ACTION_SCREEN_OFF onReceive
,07-05 11:19:26.806   758  1067 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
,07-05 11:19:26.806  1413  1413 D NativeNfcManager: power state=2
,07-05 11:19:26.806   758  1050 D DisplayPowerController: getFinalBrightness : 255 -> 0
,07-05 11:19:26.806   758  1050 D DisplayPowerController: animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 11:19:26.806  1413  7573 D NfcService: call the applyRouting
,07-05 11:19:26.806  1191  1191 D STATUSBAR-PhoneStatusBar:      ACTION_SCREEN_OFF is finished!!!! 
,07-05 11:19:26.816   758  1175 D lights  : lcd : 9 -
07-05 11:19:26.816   758  1175 D lights  : lcd : 0 +
,07-05 11:19:26.826  1816  1816 D accuweather: [Accuweather J]>>> SWW:81 [0:0] =============== BR act = androidintentactionSCREEN_OFF
,07-05 11:19:26.836   758  1175 D lights  : lcd : 0 -
,07-05 11:19:26.836   758  1433 D ActivityManager: caller:android.app.ApplicationThreadProxy@3a020b82, r.packageName :com.google.android.gms
,07-05 11:19:26.836  1413  7573 D NfcService: index : 0
07-05 11:19:26.836  1413  7573 D NfcService: index : 1
07-05 11:19:26.836  1413  7573 D NfcService: index : 2
,07-05 11:19:26.846   758  3059 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 11:19:26.866   758  1050 D DisplayPowerState: !@ ColorFade entry
,07-05 11:19:26.866   758  1050 D DisplayPowerController: ColorFade: onAnimationEnd
,07-05 11:19:26.876   758  1143 W BroadcastQueue: Skipping deliver [sec] BroadcastRecord{3aecb293 u-1 android.intent.action.SCREEN_OFF} to ReceiverList{25c99a3e 1191 com.android.systemui/10067/u0 remote:10666af9}: filter unregistered
,07-05 11:19:26.886   758  1050 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-05 11:19:26.886   758  1050 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 11:19:26.886   758  1050 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-05 11:19:26.886   758  1050 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 11:19:26.886   758  1050 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-05 11:19:26.886   758  1050 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 11:19:26.886   758  1050 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 11:19:26.886   758  1050 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
07-05 11:19:26.886   758  1046 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,07-05 11:19:26.886   758  3059 D SSRM:n  : SIOP:: AP = 330, PST = 303, CUR = 450
,07-05 11:19:26.896   758   758 V ActivityManager: Display changed displayId=0
,07-05 11:19:26.896   266   266 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6962000
,07-05 11:19:26.896   266   266 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-05 11:19:26.906  1191  1191 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 6 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte level=2
,07-05 11:19:26.906  1191  1191 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 6 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte
07-05 11:19:26.916  1191  1191 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=2
07-05 11:19:26.916  1191  1191 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_2 mContentDescriptionPhoneSignal = Two bars of phone signal
07-05 11:19:26.916  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 11:19:26.916  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 11:19:26.916  1191  1191 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 6 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte level=2
07-05 11:19:26.916  1191  1191 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 6 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte
07-05 11:19:26.916  1191  1191 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=2
07-05 11:19:26.916  1191  1191 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_2 mContentDescriptionPhoneSignal = Two bars of phone signal
07-05 11:19:26.916  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 11:19:26.916  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 11:19:26.916   758  3296 W ActivityManager: getTasks: caller 10102 does not hold GET_TASKS; limiting output
,07-05 11:19:26.916   758  1362 W ActivityManager: getTasks: caller 10102 does not hold GET_TASKS; limiting output
,07-05 11:19:26.916   758  1171 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-05 11:19:26.936   758  1234 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:19:26.936   758  1234 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4298, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 11:19:26.936   758  1234 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 11:19:26.936   758  1234 D BatteryService: stay LED for fully charged
07-05 11:19:26.936   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 11:19:26.936   758   758 I MotionRecognitionService: Plugged
07-05 11:19:26.936   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:19:26.946  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:19:26.946  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 11:19:26.946  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:19:26.946  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:19:26.946  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:19:26.946  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 11:19:26.946  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
07-05 11:19:26.946  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:19:27.026   758  1091 D LightsService: [SvcLED]  onSensorChanged::light value = 30
,07-05 11:19:27.026   758  1091 E LightSensor: Light old sensor_state 8704, new sensor_state : 8192 en : 0
,07-05 11:19:27.026   758  1091 D SensorManager: unregisterListener ::   
,07-05 11:19:27.026   758  1091 D lights  : led_pattern : 5 +
,07-05 11:19:27.026   758  1091 D lights  : led_pattern : 5 -
07-05 11:19:27.026   758  1091 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-05 11:19:27.166   266   515 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
07-05 11:19:27.166   266   266 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-05 11:19:27.166   758  1176 D SurfaceControl: Excessive delay in setPowerMode(): 275ms
07-05 11:19:27.166   758  1176 D PowerManagerService: !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
07-05 11:19:27.166   758  1176 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
07-05 11:19:27.166   758  1176 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
07-05 11:19:27.166   758  1176 I QCOM PowerHAL: Got set_interactive hint
,07-05 11:19:27.166   758  1176 D PowerManagerService: Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 277ms
,07-05 11:19:27.166   758  1050 I PowerManagerService: [PWL] Off : 0s ago
,07-05 11:19:27.876   305   305 E SMD     : DCD ON
,07-05 11:19:28.626  1301  1301 I wpa_supplicant: nl80211: Received scan results (10 BSSes)
,07-05 11:19:28.646   758  1147 D WifiP2pService: InactiveState{ what=147461 }
,07-05 11:19:28.656   758  1147 D WifiP2pService: P2pEnabledState{ what=147461 }
,07-05 11:19:28.656   758  1147 D WifiP2pService: DefaultState{ what=147461 }
,07-05 11:19:30.886   305   305 E SMD     : DCD ON
,07-05 11:19:31.766  1191  1191 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
,07-05 11:19:31.766  1191  1191 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1845 should be AT_MOST
,07-05 11:19:32.166   758  1050 I PowerManagerService: [PWL] Off : 5s ago
,07-05 11:19:33.886   305   305 E SMD     : DCD ON
,07-05 11:19:36.886   305   305 E SMD     : DCD ON
,07-05 11:19:36.936   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 304, CUR = 450
,07-05 11:19:37.006   758  1461 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:19:37.006   758  1461 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:19:37.006   758  1461 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:19:37.006   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:19:37.016  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:19:37.026  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:19:37.026   758   758 I MotionRecognitionService: Plugged
,07-05 11:19:37.026   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:19:37.026   758  1461 D BatteryService: stay LED for fully charged
,07-05 11:19:37.036  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:19:37.046  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:19:37.046  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:19:37.056  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:19:37.056  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:19:37.056  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:19:39.736   758  1111 V AlarmManager: waitForAlarm result :8
,07-05 11:19:39.886   305   305 E SMD     : DCD ON
,07-05 11:19:42.166   758  1050 I PowerManagerService: [PWL] Off : 15s ago
,07-05 11:19:42.886   305   305 E SMD     : DCD ON
,07-05 11:19:45.886   305   305 E SMD     : DCD ON
,07-05 11:19:46.976   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 305, CUR = 450
,07-05 11:19:47.066   758  1668 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:19:47.066   758  1668 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:19:47.066   758  1668 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:19:47.076   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:19:47.086  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:19:47.086  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:19:47.086   758   758 I MotionRecognitionService: Plugged
,07-05 11:19:47.096   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:19:47.096   758  1668 D BatteryService: stay LED for fully charged
,07-05 11:19:47.106  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:19:47.116  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:19:47.116  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:19:47.126  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:19:47.126  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:19:47.136  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:19:48.366   758  1337 E Watchdog: !@Sync 28
,07-05 11:19:48.886   305   305 E SMD     : DCD ON
,07-05 11:19:51.886   305   305 E SMD     : DCD ON
,07-05 11:19:54.886   305   305 E SMD     : DCD ON
,07-05 11:19:57.026   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 306, CUR = 450
,07-05 11:19:57.126   758  1461 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:19:57.136   758  1461 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:19:57.136   758  1461 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:19:57.136   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:19:57.146   758   758 I MotionRecognitionService: Plugged
,07-05 11:19:57.156  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:19:57.156  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:19:57.156   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:19:57.166   758  1461 D BatteryService: stay LED for fully charged
,07-05 11:19:57.166   758  1050 I PowerManagerService: [PWL] Off : 30s ago
,07-05 11:19:57.186  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:19:57.186  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:19:57.186  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 11:19:57.186  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:19:57.186  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:19:57.186  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:19:57.886   305   305 E SMD     : DCD ON
,07-05 11:19:59.996   758  1111 V AlarmManager: waitForAlarm result :8
,07-05 11:20:00.886   305   305 E SMD     : DCD ON
,07-05 11:20:03.886   305   305 E SMD     : DCD ON
,07-05 11:20:06.896   305   305 E SMD     : DCD ON
,07-05 11:20:07.076   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450
,07-05 11:20:07.186   758  1668 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:20:07.186   758  1668 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:20:07.196   758  1668 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:20:07.196   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:20:07.206  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:20:07.206  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:20:07.216   758   758 I MotionRecognitionService: Plugged
,07-05 11:20:07.216   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:20:07.226   758  1668 D BatteryService: stay LED for fully charged
,07-05 11:20:07.236  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:20:07.236  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:07.236  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:20:07.236  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
07-05 11:20:07.246  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:07.246  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:09.896   305   305 E SMD     : DCD ON
,07-05 11:20:12.896   305   305 E SMD     : DCD ON
,07-05 11:20:15.896   305   305 E SMD     : DCD ON
,07-05 11:20:17.126   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450
,07-05 11:20:17.176   758  1050 I PowerManagerService: [PWL] Off : 50s ago
,07-05 11:20:17.246   758  1461 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:20:17.256   758  1461 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:20:17.256   758  1461 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:20:17.256   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:20:17.266  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:20:17.266  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:20:17.276   758   758 I MotionRecognitionService: Plugged
,07-05 11:20:17.276   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:20:17.286   758  1461 D BatteryService: stay LED for fully charged
,07-05 11:20:17.286  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:20:17.296  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:20:17.296  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:20:17.306  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:17.306  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:20:17.306  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:18.366   758  1337 E Watchdog: !@Sync 29
,07-05 11:20:18.896   305   305 E SMD     : DCD ON
,07-05 11:20:21.896   305   305 E SMD     : DCD ON
,07-05 11:20:24.896   305   305 E SMD     : DCD ON
,07-05 11:20:27.176   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450
,07-05 11:20:27.306   758  1668 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:20:27.896   305   305 E SMD     : DCD ON
,07-05 11:20:30.896   305   305 E SMD     : DCD ON
,07-05 11:20:33.896   305   305 E SMD     : DCD ON
,07-05 11:20:36.896   305   305 E SMD     : DCD ON
,07-05 11:20:37.226   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450
,07-05 11:20:37.366   758  3296 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:20:37.366   758  3296 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:20:37.376   758  3296 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:20:37.376   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:20:37.386  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:20:37.386  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:20:37.386   758   758 I MotionRecognitionService: Plugged
,07-05 11:20:37.396   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:20:37.396   758  3296 D BatteryService: stay LED for fully charged
,07-05 11:20:37.416  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:20:37.416  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:37.426  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:37.426  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:37.436  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:20:37.436  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:20:39.896   305   305 E SMD     : DCD ON
,07-05 11:20:42.176   758  1050 I PowerManagerService: [PWL] Off : 75s ago
,07-05 11:20:42.906   305   305 E SMD     : DCD ON
,07-05 11:20:45.396   758  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 11:20:45.396   758  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 11:20:45.406   758  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 11:20:45.906   305   305 E SMD     : DCD ON
,07-05 11:20:47.286   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 307, CUR = 450
,07-05 11:20:47.426   758  1644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:20:47.426   758  1644 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:20:47.426   758  1644 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:20:47.426   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:20:47.436  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:20:47.436  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:20:47.436   758   758 I MotionRecognitionService: Plugged
,07-05 11:20:47.436   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:20:47.436   758  1644 D BatteryService: stay LED for fully charged
,07-05 11:20:47.446  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:20:47.446  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:47.456  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:20:47.456  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:20:47.466  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:47.466  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:47.896   758  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 11:20:47.906   758  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 11:20:47.906   758  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:20:47.906   758  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:20:48.376   758  1337 E Watchdog: !@Sync 30
,07-05 11:20:48.906   305   305 E SMD     : DCD ON
,07-05 11:20:51.906   305   305 E SMD     : DCD ON
,07-05 11:20:54.906   305   305 E SMD     : DCD ON
,07-05 11:20:57.336   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 308, CUR = 450
,07-05 11:20:57.476   758  3296 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:20:57.906   305   305 E SMD     : DCD ON
,07-05 11:21:00.906   305   305 E SMD     : DCD ON
,07-05 11:21:02.166   758   771 I art     : Background sticky concurrent mark sweep GC freed 126465(9MB) AllocSpace objects, 256(4MB) LOS objects, 13% free, 49MB/57MB, paused 1.663ms total 117.273ms
,07-05 11:21:03.906   305   305 E SMD     : DCD ON
,07-05 11:21:06.906   305   305 E SMD     : DCD ON
,07-05 11:21:07.396   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450
,07-05 11:21:07.546   758  3047 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:21:09.906   305   305 E SMD     : DCD ON
,07-05 11:21:12.176   758  1050 I PowerManagerService: [PWL] Off : 105s ago
,07-05 11:21:12.906   305   305 E SMD     : DCD ON
,07-05 11:21:15.906   305   305 E SMD     : DCD ON
,07-05 11:21:17.446   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450
,07-05 11:21:18.376   758  1337 E Watchdog: !@Sync 31
,07-05 11:21:18.906   305   305 E SMD     : DCD ON
,07-05 11:21:21.916   305   305 E SMD     : DCD ON
,07-05 11:21:24.916   305   305 E SMD     : DCD ON
,07-05 11:21:26.766   758  1111 V AlarmManager: waitForAlarm result :4
,07-05 11:21:26.826   758  1362 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:21:26.826   758  1362 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:21:26.826   758  1362 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:21:26.836  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 11:21:26.836  1191  1191 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:21:26.836   758  1362 D BatteryService: stay LED for fully charged
,07-05 11:21:26.836  1191  1191 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 11:21:26.836  1191  1191 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 11:21:26.846   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:21:26.856  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:21:26.856  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:21:26.856   758   758 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
,07-05 11:21:26.856  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:21:26.876  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:21:26.876  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:21:26.876  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:21:26.876  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:21:26.886   758   758 I MotionRecognitionService: Plugged
,07-05 11:21:26.886  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:21:26.886   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:21:26.896   758   758 I BackgroundCompactionService: onStart. jobID=801
,07-05 11:21:26.896   758   758 I BackgroundCompactionService: onStart done. jobID=801
,07-05 11:21:26.906   758  7588 I BackgroundCompactionService: Execute BGCompaction (type1). (1 times)
,07-05 11:21:26.906   758  7588 I BackgroundCompactionService: compact_memory command done
,07-05 11:21:26.936  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:21:26.936  3747  4115 D GCM     : Message class com.google.f.a.a.i
,07-05 11:21:26.936   758  1362 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 11:21:26.936   758  1234 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 11:21:26.946  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:21:27.496   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 304, CUR = 450
,07-05 11:21:27.916   305   305 E SMD     : DCD ON
,07-05 11:21:30.916   305   305 E SMD     : DCD ON
,07-05 11:21:33.916   305   305 E SMD     : DCD ON
,07-05 11:21:36.876   758  1602 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:21:36.886   758  1602 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:21:36.886   758  1602 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:21:36.886   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:21:36.896   758   758 I MotionRecognitionService: Plugged
,07-05 11:21:36.896  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:21:36.906  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:21:36.906   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:21:36.906   758  1602 D BatteryService: stay LED for fully charged
,07-05 11:21:36.916   305   305 E SMD     : DCD ON
,07-05 11:21:36.916  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:21:36.926  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:21:36.936  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:21:36.936  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:21:36.936  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:21:36.946  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:21:37.556   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,07-05 11:21:39.916   305   305 E SMD     : DCD ON
,07-05 11:21:42.916   305   305 E SMD     : DCD ON
,07-05 11:21:45.916   305   305 E SMD     : DCD ON
,07-05 11:21:46.946   758  1614 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:21:46.956   758  1614 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:21:46.956   758  1614 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:21:46.956   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:21:46.966  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:21:46.966  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:21:46.966   758   758 I MotionRecognitionService: Plugged
,07-05 11:21:46.966   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:21:46.976   758  1614 D BatteryService: stay LED for fully charged
,07-05 11:21:46.986  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:21:46.996  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:21:47.006  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:21:47.006  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:21:47.006  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:21:47.006  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:21:47.186   758  1050 I PowerManagerService: [PWL] Off : 140s ago
,07-05 11:21:47.606   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,07-05 11:21:48.376   758  1337 E Watchdog: !@Sync 32
,07-05 11:21:48.916   305   305 E SMD     : DCD ON
,07-05 11:21:51.916   305   305 E SMD     : DCD ON
,07-05 11:21:54.916   305   305 E SMD     : DCD ON
,07-05 11:21:57.006   758  1602 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:21:57.016   758  1602 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:21:57.016   758  1602 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:21:57.016   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:21:57.026  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:21:57.026  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:21:57.036   758   758 I MotionRecognitionService: Plugged
,07-05 11:21:57.036   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:21:57.046   758  1602 D BatteryService: stay LED for fully charged
,07-05 11:21:57.056  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:21:57.056  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:21:57.056  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:21:57.066  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:21:57.076  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:21:57.076  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:21:57.656   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,07-05 11:21:57.916   305   305 E SMD     : DCD ON
,07-05 11:21:59.996   758  1111 V AlarmManager: waitForAlarm result :8
,07-05 11:22:00.926   305   305 E SMD     : DCD ON
,07-05 11:22:03.926   305   305 E SMD     : DCD ON
,07-05 11:22:06.926   305   305 E SMD     : DCD ON
,07-05 11:22:07.066   758  1614 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:22:07.066   758  1614 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:22:07.076   758  1614 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:22:07.076   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:22:07.086  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:22:07.086  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:22:07.096   758   758 I MotionRecognitionService: Plugged
,07-05 11:22:07.096   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:22:07.106   758  1614 D BatteryService: stay LED for fully charged
,07-05 11:22:07.106  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:22:07.106  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:22:07.116  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:22:07.116  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:22:07.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:22:07.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:22:07.696   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,07-05 11:22:09.926   305   305 E SMD     : DCD ON
,07-05 11:22:12.926   305   305 E SMD     : DCD ON
,07-05 11:22:15.926   305   305 E SMD     : DCD ON
,07-05 11:22:17.126   758  1602 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:22:17.746   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,07-05 11:22:18.386   758  1337 E Watchdog: !@Sync 33
,07-05 11:22:18.926   305   305 E SMD     : DCD ON
,07-05 11:22:21.926   305   305 E SMD     : DCD ON
,07-05 11:22:24.926   305   305 E SMD     : DCD ON
,07-05 11:22:27.186   758  1433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:22:27.196   758  1050 I PowerManagerService: [PWL] Off : 180s ago
,07-05 11:22:27.796   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-05 11:22:27.926   305   305 E SMD     : DCD ON
,07-05 11:22:30.926   305   305 E SMD     : DCD ON
,07-05 11:22:33.926   305   305 E SMD     : DCD ON
,07-05 11:22:36.926   305   305 E SMD     : DCD ON
,07-05 11:22:37.246   758  3296 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:22:37.846   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 11:22:39.936   305   305 E SMD     : DCD ON
,07-05 11:22:42.936   305   305 E SMD     : DCD ON
,07-05 11:22:45.936   305   305 E SMD     : DCD ON
,07-05 11:22:47.306   758  1644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:22:47.896   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 11:22:48.386   758  1337 E Watchdog: !@Sync 34
,07-05 11:22:48.936   305   305 E SMD     : DCD ON
,07-05 11:22:51.936   305   305 E SMD     : DCD ON
,07-05 11:22:54.936   305   305 E SMD     : DCD ON
,07-05 11:22:57.366   758  1614 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:22:57.936   305   305 E SMD     : DCD ON
,07-05 11:22:57.946   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 11:23:00.936   305   305 E SMD     : DCD ON
,07-05 11:23:03.936   305   305 E SMD     : DCD ON
,07-05 11:23:06.936   305   305 E SMD     : DCD ON
,07-05 11:23:07.426   758  1234 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:23:07.996   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:23:09.936   305   305 E SMD     : DCD ON
,07-05 11:23:12.196   758  1050 I PowerManagerService: [PWL] Off : 225s ago
,07-05 11:23:12.936   305   305 E SMD     : DCD ON
,07-05 11:23:15.936   305   305 E SMD     : DCD ON
,07-05 11:23:17.486   758   778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:23:18.036   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:23:18.386   758  1337 E Watchdog: !@Sync 35
,07-05 11:23:18.946   305   305 E SMD     : DCD ON
,07-05 11:23:21.946   305   305 E SMD     : DCD ON
,07-05 11:23:24.946   305   305 E SMD     : DCD ON
,07-05 11:23:27.556   758  1668 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:23:27.566   758  1668 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:23:27.566   758  1668 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:23:27.566   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:23:27.576  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:23:27.576  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:23:27.576   758   758 I MotionRecognitionService: Plugged
,07-05 11:23:27.576   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:23:27.586   758  1668 D BatteryService: stay LED for fully charged
,07-05 11:23:27.596  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:23:27.606  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:23:27.606  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:23:27.606  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:23:27.616  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:23:27.616  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:23:27.946   305   305 E SMD     : DCD ON
,07-05 11:23:28.086   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:23:30.946   305   305 E SMD     : DCD ON
,07-05 11:23:33.946   305   305 E SMD     : DCD ON
,07-05 11:23:36.946   305   305 E SMD     : DCD ON
,07-05 11:23:37.616   758  1644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:23:38.136   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:23:39.946   305   305 E SMD     : DCD ON
,07-05 11:23:42.946   305   305 E SMD     : DCD ON
,07-05 11:23:45.946   305   305 E SMD     : DCD ON
,07-05 11:23:47.676   758  1614 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:23:47.676   758  1614 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:23:47.676   758  1614 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:23:47.686   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:23:47.696   758   758 I MotionRecognitionService: Plugged
,07-05 11:23:47.696   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:23:47.696   758  1614 D BatteryService: stay LED for fully charged
,07-05 11:23:47.696  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:23:47.706  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:23:47.706  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:23:47.716  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:23:47.716  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:23:47.726  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:23:47.726  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:23:47.726  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:23:48.186   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:23:48.386   758  1337 E Watchdog: !@Sync 36
,07-05 11:23:48.946   305   305 E SMD     : DCD ON
,07-05 11:23:51.946   305   305 E SMD     : DCD ON
,07-05 11:23:54.946   305   305 E SMD     : DCD ON
,07-05 11:23:57.736   758  1602 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:23:57.736   758  1602 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:23:57.746   758  1602 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:23:57.746   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:23:57.756  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:23:57.756  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:23:57.766   758   758 I MotionRecognitionService: Plugged
,07-05 11:23:57.766   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:23:57.766   758  1602 D BatteryService: stay LED for fully charged
,07-05 11:23:57.776  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:23:57.786  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:23:57.796  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:23:57.796  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:23:57.806  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:23:57.806  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:23:57.956   305   305 E SMD     : DCD ON
,07-05 11:23:58.236   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:24:00.956   305   305 E SMD     : DCD ON
,07-05 11:24:02.206   758  1050 I PowerManagerService: [PWL] Off : 275s ago
,07-05 11:24:03.956   305   305 E SMD     : DCD ON
,07-05 11:24:06.956   305   305 E SMD     : DCD ON
,07-05 11:24:07.796   758  1614 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:24:07.796   758  1614 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:24:07.796   758  1614 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:24:07.806   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:24:07.816  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:24:07.816  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:24:07.816   758   758 I MotionRecognitionService: Plugged
,07-05 11:24:07.816   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:24:07.826   758  1614 D BatteryService: stay LED for fully charged
,07-05 11:24:07.836  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:24:07.846  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:24:07.846  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:24:07.856  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:24:07.856  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:24:07.856  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:24:08.286   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:24:09.956   305   305 E SMD     : DCD ON
,07-05 11:24:12.956   305   305 E SMD     : DCD ON
,07-05 11:24:15.956   305   305 E SMD     : DCD ON
,07-05 11:24:17.856   758  1602 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:24:18.326   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:24:18.396   758  1337 E Watchdog: !@Sync 37
,07-05 11:24:18.956   305   305 E SMD     : DCD ON
,07-05 11:24:21.956   305   305 E SMD     : DCD ON
,07-05 11:24:24.966   305   305 E SMD     : DCD ON
,07-05 11:24:27.916   758  1433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:24:27.966   305   305 E SMD     : DCD ON
,07-05 11:24:28.376   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:24:30.966   305   305 E SMD     : DCD ON
,07-05 11:24:33.966   305   305 E SMD     : DCD ON
,07-05 11:24:36.966   305   305 E SMD     : DCD ON
,07-05 11:24:37.976   758  3296 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:24:38.426   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:24:39.966   305   305 E SMD     : DCD ON
,07-05 11:24:42.966   305   305 E SMD     : DCD ON
,07-05 11:24:45.966   305   305 E SMD     : DCD ON
,07-05 11:24:48.036   758  1644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:24:48.396   758  1337 E Watchdog: !@Sync 38
,07-05 11:24:48.476   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:24:48.966   305   305 E SMD     : DCD ON
,07-05 11:24:51.966   305   305 E SMD     : DCD ON
,07-05 11:24:54.966   305   305 E SMD     : DCD ON
,07-05 11:24:57.206   758  1050 I PowerManagerService: [PWL] Off : 330s ago
,07-05 11:24:57.966   305   305 E SMD     : DCD ON
,07-05 11:24:58.096   758  1614 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:24:58.096   758  1614 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:24:58.096   758  1614 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:24:58.106   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:24:58.116  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:24:58.116  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:24:58.116   758   758 I MotionRecognitionService: Plugged
,07-05 11:24:58.116   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:24:58.126   758  1614 D BatteryService: stay LED for fully charged
,07-05 11:24:58.136  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:24:58.146  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:24:58.146  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:24:58.156  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:24:58.156  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:24:58.156  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:24:58.526   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:24:59.996   758  1111 V AlarmManager: waitForAlarm result :8
,07-05 11:25:00.016  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 11:25:00.016  1191  1191 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:25:00.016  1191  1191 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 11:25:00.026  1191  1191 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 11:25:00.116  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:25:00.116  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:25:00.966   305   305 E SMD     : DCD ON
,07-05 11:25:03.976   305   305 E SMD     : DCD ON
,07-05 11:25:06.976   305   305 E SMD     : DCD ON
,07-05 11:25:08.156   758  3047 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:25:08.626   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:25:09.976   305   305 E SMD     : DCD ON
,07-05 11:25:12.976   305   305 E SMD     : DCD ON
,07-05 11:25:15.976   305   305 E SMD     : DCD ON
,07-05 11:25:18.216   758   779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:25:18.226   758   779 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:25:18.226   758   779 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:25:18.226   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:25:18.236  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:25:18.246  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:25:18.246   758   758 I MotionRecognitionService: Plugged
,07-05 11:25:18.246   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:25:18.256   758   779 D BatteryService: stay LED for fully charged
,07-05 11:25:18.256  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:25:18.266  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:25:18.266  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:25:18.276  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:25:18.276  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:25:18.276  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:25:18.396   758  1337 E Watchdog: !@Sync 39
,07-05 11:25:18.676   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:25:18.976   305   305 E SMD     : DCD ON
,07-05 11:25:21.976   305   305 E SMD     : DCD ON
,07-05 11:25:24.976   305   305 E SMD     : DCD ON
,07-05 11:25:27.976   305   305 E SMD     : DCD ON
,07-05 11:25:28.286   758  1362 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:25:28.726   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:25:30.976   305   305 E SMD     : DCD ON
,07-05 11:25:33.976   305   305 E SMD     : DCD ON
,07-05 11:25:36.976   305   305 E SMD     : DCD ON
,07-05 11:25:38.346   758  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:25:38.776   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:25:39.986   305   305 E SMD     : DCD ON
,07-05 11:25:42.986   305   305 E SMD     : DCD ON
,07-05 11:25:45.396   758  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 11:25:45.406   758  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 11:25:45.406   758  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 11:25:45.986   305   305 E SMD     : DCD ON
,07-05 11:25:46.036   758   989 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 11:25:46.086   758  1123 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,07-05 11:25:46.086   758  1123 I ApplicationUsage: Updating Usage Statistics in DB @ 1467710746092
,07-05 11:25:46.096   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.096   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.096   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.096   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,07-05 11:25:46.096   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,07-05 11:25:46.106   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,07-05 11:25:46.106   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.106   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.106   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 11:25:46.106   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.106   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.106   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.106   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.106   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-05 11:25:46.106   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
07-05 11:25:46.106   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,07-05 11:25:46.106   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.106   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.106   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.106   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.106   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.106   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.106   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.106   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-05 11:25:46.106   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,07-05 11:25:46.106   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,07-05 11:25:46.106   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.116   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.116   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 11:25:46.116   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.116   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.116   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.116   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.116   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-05 11:25:46.116   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
07-05 11:25:46.116   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,07-05 11:25:46.116   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.116   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.116   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 11:25:46.116   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.116   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.116   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.116   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.116   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.116   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.116   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.116   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.116   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.116   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.116   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.116   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.116   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.116   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.116   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.116   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 11:25:46.116   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.116   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.126   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.126   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.126   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.126   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.126   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.126   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.126   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.126   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.126   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.126   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.126   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.126   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.126   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.126   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.126   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.126   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.126   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.126   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.126   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.126   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.126   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.126   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.126   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.126   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.136   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.136   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.136   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.136   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.136   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 11:25:46.136   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.136   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.136   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 11:25:46.136   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.136   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.136   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.136   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.136   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.136   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.136   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 11:25:46.136   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.136   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 11:25:46.136   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 11:25:46.136   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.136   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.136   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.136   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.136   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.136   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.136   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 11:25:46.136   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.136   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.136   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 11:25:46.136   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.146   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.146   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.146   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.146   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.146   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.146   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 11:25:46.146   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.146   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.146   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.146   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.146   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.146   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.146   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.146   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.146   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.146   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.146   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.146   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.146   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.146   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.146   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.146   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.146   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.146   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.146   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.156   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 11:25:46.156   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.156   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.156   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.156   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.156   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.156   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 11:25:46.156   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.156   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.156   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.156   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.156   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.156   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.156   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.156   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.156   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.156   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.156   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.156   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.156   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.156   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.166   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 11:25:46.166   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.166   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.166   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.166   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.166   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.166   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.166   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.166   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.166   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.166   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 11:25:46.166   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.166   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.166   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.166   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.166   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.166   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 11:25:46.166   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 11:25:46.166   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.166   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.166   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.176   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.176   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.176   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.176   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.176   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.176   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.176   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.176   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.176   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.176   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.176   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.176   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 11:25:46.176   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.176   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.176   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.176   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.176   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 11:25:46.176   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.176   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.176   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.176   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.186   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.186   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 11:25:46.186   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.186   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.186   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.186   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 11:25:46.186   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.186   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.186   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.186   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.186   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.186   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.186   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.186   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.186   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 11:25:46.186   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.186   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.186   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.186   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.186   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.186   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.196   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 11:25:46.196   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.196   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.196   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.196   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.196   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 11:25:46.196   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.196   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.196   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.196   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.196   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.196   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.196   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.196   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.196   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.196   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.196   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.196   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.196   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.196   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.196   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.206   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.206   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.206   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.206   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.206   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.206   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.206   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.206   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.206   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.206   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.206   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.206   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.206   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.206   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.206   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.206   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.206   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 11:25:46.216   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.216   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.216   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 11:25:46.216   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.216   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.216   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.216   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.216   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.216   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 11:25:46.216   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.216   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.216   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:25:46.216   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.216   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.216   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 11:25:46.216   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.216   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.216   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.216   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.216   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.216   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.216   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.216   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.216   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.216   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.226   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.226   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.226   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.226   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.226   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.226   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.226   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.226   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.226   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.226   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.226   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.226   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.226   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.226   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.226   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.226   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.236   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.236   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.236   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.236   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.236   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.236   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.236   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.236   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.236   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.236   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.236   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.236   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.236   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.236   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.236   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.236   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.236   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.236   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.236   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.236   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.236   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.246   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.246   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.246   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.246   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.246   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.246   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.246   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.246   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.246   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.246   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.246   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.246   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.246   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.246   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.246   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.246   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.246   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.246   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.246   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.246   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.246   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.256   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.256   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.256   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.256   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.256   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.256   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.256   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.256   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.256   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.256   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.256   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.256   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.256   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.256   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.256   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.256   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.256   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.256   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.256   758  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 11:25:46.256   758  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 11:25:46.256   758  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 11:25:46.256   758  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:25:46.256   758  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:25:46.256   758  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:25:46.256   758  1123 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1467710746269
,07-05 11:25:47.666   758  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 11:25:47.666   758  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 11:25:47.676   758  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:25:47.676   758  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:25:48.406   758  1337 E Watchdog: !@Sync 40
,07-05 11:25:48.406   758  1433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:25:48.416   758  1433 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:25:48.416   758  1433 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:25:48.416   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:25:48.426  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:25:48.426  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:25:48.436   758   758 I MotionRecognitionService: Plugged
,07-05 11:25:48.436   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:25:48.436   758  1433 D BatteryService: stay LED for fully charged
,07-05 11:25:48.466  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:25:48.466  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:25:48.466  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:25:48.486  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:25:48.486  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:25:48.486  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:25:48.816   758  3059 D SSRM:n  : SIOP:: AP = 310, PST = 301, CUR = 450
,07-05 11:25:48.986   305   305 E SMD     : DCD ON
,07-05 11:25:51.986   305   305 E SMD     : DCD ON
,07-05 11:25:54.986   305   305 E SMD     : DCD ON
,07-05 11:25:57.216   758  1050 I PowerManagerService: [PWL] Off : 390s ago
,07-05 11:25:57.986   305   305 E SMD     : DCD ON
,07-05 11:25:58.466   758  3296 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:25:58.476   758  3296 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:25:58.476   758  3296 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:25:58.476   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:25:58.486   758   758 I MotionRecognitionService: Plugged
,07-05 11:25:58.486  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:25:58.486  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:25:58.486   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:25:58.496   758  3296 D BatteryService: stay LED for fully charged
,07-05 11:25:58.506  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:25:58.506  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:25:58.506  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:25:58.526  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:25:58.526  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:25:58.526  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:25:58.876   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 11:25:59.996   758  1111 V AlarmManager: waitForAlarm result :8
,07-05 11:26:00.986   305   305 E SMD     : DCD ON
,07-05 11:26:03.986   305   305 E SMD     : DCD ON
,07-05 11:26:06.986   305   305 E SMD     : DCD ON
,07-05 11:26:08.526   758  1433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:26:08.916   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 11:26:09.986   305   305 E SMD     : DCD ON
,07-05 11:26:12.986   305   305 E SMD     : DCD ON
,07-05 11:26:15.986   305   305 E SMD     : DCD ON
,07-05 11:26:18.406   758  1337 E Watchdog: !@Sync 41
,07-05 11:26:18.596   758  3047 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:26:18.596   758  3047 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:26:18.596   758  3047 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:26:18.606   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:26:18.616  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:26:18.616  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:26:18.616   758   758 I MotionRecognitionService: Plugged
,07-05 11:26:18.616   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:26:18.626   758  3047 D BatteryService: stay LED for fully charged
,07-05 11:26:18.636  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:26:18.646  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:26:18.646  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:26:18.656  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:26:18.656  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:26:18.656  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:26:18.966   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 11:26:18.996   305   305 E SMD     : DCD ON
,07-05 11:26:21.996   305   305 E SMD     : DCD ON
,07-05 11:26:24.996   305   305 E SMD     : DCD ON
,07-05 11:26:27.996   305   305 E SMD     : DCD ON
,07-05 11:26:28.656   758  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:26:28.656   758  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:26:28.666   758  1319 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:26:28.666   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:26:28.676  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:26:28.676  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:26:28.686   758   758 I MotionRecognitionService: Plugged
,07-05 11:26:28.686   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:26:28.696   758  1319 D BatteryService: stay LED for fully charged
,07-05 11:26:28.706  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:26:28.706  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:26:28.706  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:26:28.706  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:26:28.726  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:26:28.726  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:26:29.016   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 11:26:30.996   305   305 E SMD     : DCD ON
,07-05 11:26:33.996   305   305 E SMD     : DCD ON
,07-05 11:26:36.996   305   305 E SMD     : DCD ON
,07-05 11:26:38.716   758  3047 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:26:38.716   758  3047 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:26:38.716   758  3047 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:26:38.726   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:26:38.736  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:26:38.736  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:26:38.736   758   758 I MotionRecognitionService: Plugged
,07-05 11:26:38.746   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:26:38.746   758  3047 D BatteryService: stay LED for fully charged
,07-05 11:26:38.756  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:26:38.766  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:26:38.766  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:26:38.776  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:26:38.776  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:26:38.776  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:26:39.066   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 11:26:39.996   305   305 E SMD     : DCD ON
,07-05 11:26:42.996   305   305 E SMD     : DCD ON
,07-05 11:26:45.996   305   305 E SMD     : DCD ON
,07-05 11:26:48.406   758  1337 E Watchdog: !@Sync 42
,07-05 11:26:48.776   758  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:26:48.776   758  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:26:48.776   758  1319 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:26:48.786   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:26:48.796  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:26:48.796  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:26:48.796   758   758 I MotionRecognitionService: Plugged
,07-05 11:26:48.806   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:26:48.806   758  1319 D BatteryService: stay LED for fully charged
,07-05 11:26:48.806  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:26:48.816  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:26:48.816  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:26:48.826  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:26:48.826  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:26:48.826  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:26:48.996   305   305 E SMD     : DCD ON
,07-05 11:26:49.116   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 11:26:51.996   305   305 E SMD     : DCD ON
,07-05 11:26:54.996   305   305 E SMD     : DCD ON
,07-05 11:26:58.006   305   305 E SMD     : DCD ON
,07-05 11:26:58.836   758  3047 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:26:58.846   758  3047 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:26:58.846   758  3047 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:26:58.846   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:26:58.856  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:26:58.856  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:26:58.866   758   758 I MotionRecognitionService: Plugged
,07-05 11:26:58.866   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:26:58.866   758  3047 D BatteryService: stay LED for fully charged
,07-05 11:26:58.876  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:26:58.886  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:26:58.896  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:26:58.896  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:26:58.906  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:26:58.906  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:26:59.166   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 11:27:01.006   305   305 E SMD     : DCD ON
,07-05 11:27:02.216   758  1050 I PowerManagerService: [PWL] Off : 455s ago
,07-05 11:27:04.006   305   305 E SMD     : DCD ON
,07-05 11:27:07.006   305   305 E SMD     : DCD ON
,07-05 11:27:08.896   758  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:27:08.896   758  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:27:08.896   758  1319 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:27:08.906   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:27:08.916  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:27:08.916  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:27:08.916   758   758 I MotionRecognitionService: Plugged
,07-05 11:27:08.916   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:27:08.926   758  1319 D BatteryService: stay LED for fully charged
,07-05 11:27:08.936  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:27:08.946  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:27:08.956  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:27:08.956  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:27:08.956  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:27:08.956  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:27:09.216   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 11:27:10.006   305   305 E SMD     : DCD ON
,07-05 11:27:13.006   305   305 E SMD     : DCD ON
,07-05 11:27:16.006   305   305 E SMD     : DCD ON
,07-05 11:27:18.416   758  1337 E Watchdog: !@Sync 43
,07-05 11:27:18.956   758  3047 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:27:19.006   305   305 E SMD     : DCD ON
,07-05 11:27:19.296   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 11:27:22.006   305   305 E SMD     : DCD ON
,07-05 11:27:25.006   305   305 E SMD     : DCD ON
,07-05 11:27:28.006   305   305 E SMD     : DCD ON
,07-05 11:27:29.016   758   779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:27:29.016   758   779 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:27:29.026   758   779 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:27:29.026   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:27:29.036  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:27:29.036  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:27:29.046   758   758 I MotionRecognitionService: Plugged
,07-05 11:27:29.046   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:27:29.046   758   779 D BatteryService: stay LED for fully charged
,07-05 11:27:29.056  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:27:29.066  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:27:29.066  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:27:29.076  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:27:29.076  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:27:29.076  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:27:29.336   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:27:31.006   305   305 E SMD     : DCD ON
,07-05 11:27:34.016   305   305 E SMD     : DCD ON
,07-05 11:27:37.016   305   305 E SMD     : DCD ON
,07-05 11:27:39.076   758  1362 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:27:39.076   758  1362 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:27:39.076   758  1362 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:27:39.086   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:27:39.096   758   758 I MotionRecognitionService: Plugged
,07-05 11:27:39.096  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:27:39.096  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:27:39.106   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:27:39.106   758  1362 D BatteryService: stay LED for fully charged
,07-05 11:27:39.106  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:27:39.116  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:27:39.116  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:27:39.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:27:39.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:27:39.126  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:27:39.386   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:27:40.016   305   305 E SMD     : DCD ON
,07-05 11:27:43.016   305   305 E SMD     : DCD ON
,07-05 11:27:46.016   305   305 E SMD     : DCD ON
,07-05 11:27:48.416   758  1337 E Watchdog: !@Sync 44
,07-05 11:27:49.016   305   305 E SMD     : DCD ON
,07-05 11:27:49.136   758   779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:27:49.446   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:27:52.016   305   305 E SMD     : DCD ON
,07-05 11:27:55.016   305   305 E SMD     : DCD ON
,07-05 11:27:58.016   305   305 E SMD     : DCD ON
,07-05 11:27:59.196   758  1143 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:27:59.196   758  1143 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:27:59.196   758  1143 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:27:59.206   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:27:59.216  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:27:59.216  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:27:59.216   758   758 I MotionRecognitionService: Plugged
,07-05 11:27:59.216   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:27:59.226   758  1143 D BatteryService: stay LED for fully charged
,07-05 11:27:59.236  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:27:59.246  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:27:59.246  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:27:59.256  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:27:59.256  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:27:59.256  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:27:59.496   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:28:01.016   305   305 E SMD     : DCD ON
,07-05 11:28:04.016   305   305 E SMD     : DCD ON
,07-05 11:28:07.016   305   305 E SMD     : DCD ON
,07-05 11:28:09.256   758  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:28:09.546   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:28:10.016   305   305 E SMD     : DCD ON
,07-05 11:28:12.216   758  1050 I PowerManagerService: [PWL] Off : 525s ago
,07-05 11:28:13.026   305   305 E SMD     : DCD ON
,07-05 11:28:16.026   305   305 E SMD     : DCD ON
,07-05 11:28:18.416   758  1337 E Watchdog: !@Sync 45
,07-05 11:28:19.026   305   305 E SMD     : DCD ON
,07-05 11:28:19.316   758  1433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:28:19.316   758  1433 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:28:19.316   758  1433 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:28:19.326   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:28:19.336   758   758 I MotionRecognitionService: Plugged
,07-05 11:28:19.336   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:28:19.336  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:28:19.346  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:28:19.346   758  1433 D BatteryService: stay LED for fully charged
,07-05 11:28:19.356  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:28:19.366  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:28:19.366  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:28:19.376  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:28:19.376  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:28:19.376  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:28:19.596   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:28:22.026   305   305 E SMD     : DCD ON
,07-05 11:28:25.026   305   305 E SMD     : DCD ON
,07-05 11:28:28.026   305   305 E SMD     : DCD ON
,07-05 11:28:29.376   758  3296 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:28:29.376   758  3296 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:28:29.376   758  3296 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:28:29.386   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:28:29.396  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:28:29.396  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:28:29.406   758   758 I MotionRecognitionService: Plugged
,07-05 11:28:29.406   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:28:29.406   758  3296 D BatteryService: stay LED for fully charged
,07-05 11:28:29.406  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:28:29.416  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:28:29.416  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:28:29.426  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:28:29.426  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:28:29.426  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:28:29.646   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:28:31.026   305   305 E SMD     : DCD ON
,07-05 11:28:34.026   305   305 E SMD     : DCD ON
,07-05 11:28:37.026   305   305 E SMD     : DCD ON
,07-05 11:28:39.436   758  1433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:28:39.436   758  1433 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:28:39.436   758  1433 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:28:39.446   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:28:39.456  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:28:39.456  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:28:39.456   758   758 I MotionRecognitionService: Plugged
,07-05 11:28:39.456   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:28:39.466   758  1433 D BatteryService: stay LED for fully charged
,07-05 11:28:39.476  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:28:39.486  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:28:39.506  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:28:39.506  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:28:39.506  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:28:39.506  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:28:39.696   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:28:40.026   305   305 E SMD     : DCD ON
,07-05 11:28:43.026   305   305 E SMD     : DCD ON
,07-05 11:28:46.026   305   305 E SMD     : DCD ON
,07-05 11:28:48.426   758  1337 E Watchdog: !@Sync 46
,07-05 11:28:49.026   305   305 E SMD     : DCD ON
,07-05 11:28:49.496   758  3296 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:28:49.746   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:28:52.026   305   305 E SMD     : DCD ON
,07-05 11:28:55.036   305   305 E SMD     : DCD ON
,07-05 11:28:58.036   305   305 E SMD     : DCD ON
,07-05 11:28:59.556   758  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:28:59.566   758  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:28:59.566   758  1319 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:28:59.566   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:28:59.576  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:28:59.576  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:28:59.586   758   758 I MotionRecognitionService: Plugged
,07-05 11:28:59.586   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:28:59.596   758  1319 D BatteryService: stay LED for fully charged
,07-05 11:28:59.606  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:28:59.616  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:28:59.616  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:28:59.626  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:28:59.626  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:28:59.626  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:28:59.796   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:29:01.036   305   305 E SMD     : DCD ON
,07-05 11:29:04.036   305   305 E SMD     : DCD ON
,07-05 11:29:07.036   305   305 E SMD     : DCD ON
,07-05 11:29:09.616   758  3047 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:29:09.846   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:29:10.036   305   305 E SMD     : DCD ON
,07-05 11:29:13.036   305   305 E SMD     : DCD ON
,07-05 11:29:16.036   305   305 E SMD     : DCD ON
,07-05 11:29:18.426   758  1337 E Watchdog: !@Sync 47
,07-05 11:29:19.036   305   305 E SMD     : DCD ON
,07-05 11:29:19.676   758   779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:29:19.896   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:29:22.036   305   305 E SMD     : DCD ON
,07-05 11:29:25.036   305   305 E SMD     : DCD ON
,07-05 11:29:27.226   758  1050 I PowerManagerService: [PWL] Off : 600s ago
,07-05 11:29:28.036   305   305 E SMD     : DCD ON
,07-05 11:29:29.736   758  1143 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:29:29.936   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:29:31.036   305   305 E SMD     : DCD ON
,07-05 11:29:34.046   305   305 E SMD     : DCD ON
,07-05 11:29:37.046   305   305 E SMD     : DCD ON
,07-05 11:29:39.796   758  3296 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:29:39.796   758  3296 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:29:39.796   758  3296 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:29:39.806   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:29:39.816  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:29:39.816  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:29:39.816   758   758 I MotionRecognitionService: Plugged
,07-05 11:29:39.826   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:29:39.836   758  3296 D BatteryService: stay LED for fully charged
,07-05 11:29:39.836  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:29:39.846  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:29:39.856  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:29:39.856  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:29:39.866  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:29:39.866  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:29:39.986   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:29:40.046   305   305 E SMD     : DCD ON
,07-05 11:29:43.046   305   305 E SMD     : DCD ON
,07-05 11:29:46.046   305   305 E SMD     : DCD ON
,07-05 11:29:48.426   758  1337 E Watchdog: !@Sync 48
,07-05 11:29:49.046   305   305 E SMD     : DCD ON
,07-05 11:29:49.856   758  1433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:29:50.036   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:29:52.046   305   305 E SMD     : DCD ON
,07-05 11:29:55.046   305   305 E SMD     : DCD ON
,07-05 11:29:58.046   305   305 E SMD     : DCD ON
,07-05 11:29:59.916   758  3047 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:29:59.926   758  3047 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:29:59.926   758  3047 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:29:59.926   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:29:59.936  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:29:59.946  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:29:59.946   758   758 I MotionRecognitionService: Plugged
,07-05 11:29:59.946   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:29:59.956   758  3047 D BatteryService: stay LED for fully charged
,07-05 11:29:59.956  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:29:59.956  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:29:59.966  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:29:59.966  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:29:59.966  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:29:59.976  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:30:00.076   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:30:01.046   305   305 E SMD     : DCD ON
,07-05 11:30:04.046   305   305 E SMD     : DCD ON
,07-05 11:30:07.046   305   305 E SMD     : DCD ON
,07-05 11:30:09.976   758  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:30:09.986   758  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:30:09.986   758  1319 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:30:09.986   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:30:09.996  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:30:10.006  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:30:10.006   758   758 I MotionRecognitionService: Plugged
,07-05 11:30:10.006   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:30:10.006   758  1319 D BatteryService: stay LED for fully charged
,07-05 11:30:10.006  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:30:10.016  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:30:10.016  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:30:10.026  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:30:10.026  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:30:10.026  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:30:10.046   305   305 E SMD     : DCD ON
,07-05 11:30:10.126   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:30:13.056   305   305 E SMD     : DCD ON
,07-05 11:30:16.056   305   305 E SMD     : DCD ON
,07-05 11:30:18.436   758  1337 E Watchdog: !@Sync 49
,07-05 11:30:19.056   305   305 E SMD     : DCD ON
,07-05 11:30:20.036   758  3047 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:30:20.216   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:30:22.056   305   305 E SMD     : DCD ON
,07-05 11:30:25.056   305   305 E SMD     : DCD ON
,07-05 11:30:28.056   305   305 E SMD     : DCD ON
,07-05 11:30:30.096   758   779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:30:30.096   758   779 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:30:30.096   758   779 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:30:30.106   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:30:30.116  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:30:30.116  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:30:30.126   758   779 D BatteryService: stay LED for fully charged
,07-05 11:30:30.126   758   758 I MotionRecognitionService: Plugged
,07-05 11:30:30.136   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:30:30.136  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:30:30.146  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:30:30.156  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:30:30.156  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:30:30.166  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:30:30.166  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:30:30.246   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:30:31.056   305   305 E SMD     : DCD ON
,07-05 11:30:34.056   305   305 E SMD     : DCD ON
,07-05 11:30:37.056   305   305 E SMD     : DCD ON
,07-05 11:30:40.056   305   305 E SMD     : DCD ON
,07-05 11:30:40.156   758  1362 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:30:40.166   758  1362 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:30:40.166   758  1362 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:30:40.166   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:30:40.176  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:30:40.176  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:30:40.196   758  1362 D BatteryService: stay LED for fully charged
,07-05 11:30:40.206   758   758 I MotionRecognitionService: Plugged
,07-05 11:30:40.206  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:30:40.206   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:30:40.206  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:30:40.216  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:30:40.226  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:30:40.226  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:30:40.226  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:30:40.286   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:30:43.056   305   305 E SMD     : DCD ON
,07-05 11:30:45.396   758  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 11:30:45.406   758  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 11:30:45.406   758  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 11:30:46.056   305   305 E SMD     : DCD ON
,07-05 11:30:47.226   758  1050 I PowerManagerService: [PWL] Off : 680s ago
,07-05 11:30:47.226   758  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
07-05 11:30:47.226   758  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,07-05 11:30:47.236   758  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=758, ws=null) (elapsedTime=1823)
,07-05 11:30:47.826   758  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 11:30:47.826   758  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 11:30:47.836   758  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:30:47.836   758  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:30:48.436   758  1337 E Watchdog: !@Sync 50
,07-05 11:30:49.056   305   305 E SMD     : DCD ON
,07-05 11:30:50.226   758   779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:30:50.226   758   779 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:30:50.236   758   779 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:30:50.236   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:30:50.246  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:30:50.246  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:30:50.256   758   758 I MotionRecognitionService: Plugged
,07-05 11:30:50.256   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:30:50.256   758   779 D BatteryService: stay LED for fully charged
,07-05 11:30:50.256  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:30:50.266  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:30:50.266  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:30:50.276  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:30:50.276  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:30:50.276  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:30:50.316   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:30:52.066   305   305 E SMD     : DCD ON
,07-05 11:30:55.066   305   305 E SMD     : DCD ON
,07-05 11:30:58.066   305   305 E SMD     : DCD ON
,07-05 11:31:00.286   758  1362 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:31:00.356   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:31:01.066   305   305 E SMD     : DCD ON
,07-05 11:31:04.066   305   305 E SMD     : DCD ON
,07-05 11:31:07.066   305   305 E SMD     : DCD ON
,07-05 11:31:10.066   305   305 E SMD     : DCD ON
,07-05 11:31:10.356   758  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:31:10.366   758  1480 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 11:31:10.366   758  1480 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 11:31:10.366   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:31:10.366   758  1480 D BatteryService: stay LED for fully charged
,07-05 11:31:10.376  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:31:10.386  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:31:10.396   758   758 I MotionRecognitionService: Plugged
,07-05 11:31:10.396   758   758 I MotionRecognitionService: setPowerConnected  = true
,07-05 11:31:10.406  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 11:31:10.406  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:31:10.406  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:31:10.416  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 11:31:10.416  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:31:10.426  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:31:10.436   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:31:13.066   305   305 E SMD     : DCD ON
,07-05 11:31:16.066   305   305 E SMD     : DCD ON
,07-05 11:31:18.436   758  1337 E Watchdog: !@Sync 51
,07-05 11:31:19.066   305   305 E SMD     : DCD ON
,07-05 11:31:20.476   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:31:22.066   305   305 E SMD     : DCD ON
,07-05 11:31:24.976   758  1111 V AlarmManager: waitForAlarm result :4
,07-05 11:31:25.026  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 11:31:25.036  1191  1191 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:31:25.036  1191  1191 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 11:31:25.046  1191  1191 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 11:31:25.056   758   758 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-05 11:31:25.066   758   758 E LightSensor: Light old sensor_state 8192, new sensor_state : 8704 en : 1
,07-05 11:31:25.066   758  1644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:31:25.066   305   305 E SMD     : DCD ON
,07-05 11:31:25.076   758   758 D SensorManager: registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,07-05 11:31:25.126   758  1668 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 11:31:25.126   758  1668 D ActivityManager: caller:android.app.ApplicationThreadProxy@1e585932, r.packageName :com.google.android.gms
,07-05 11:31:25.136  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:31:25.146  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:31:25.166  2286  7662 I EventLogService: Aggregate from 1467709280436 (log), 1467709280436 (data)
,07-05 11:31:25.186  3747  4225 I art     : Explicit concurrent mark sweep GC freed 14526(767KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 18MB/31MB, paused 410us total 20.598ms
,07-05 11:31:25.446   758  1091 D LightsService: [SvcLED]  onSensorChanged::light value = 30
,07-05 11:31:25.446   758  1091 E LightSensor: Light old sensor_state 8704, new sensor_state : 8192 en : 0
,07-05 11:31:25.456   758  1091 D SensorManager: unregisterListener ::   
,07-05 11:31:25.456   758  1091 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-05 11:31:28.066   305   305 E SMD     : DCD ON
,07-05 11:31:30.536   758  3059 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 11:31:31.076   305   305 E SMD     : DCD ON
,TIME-OUT KILL (timeout was 1400000ms),07-05 11:31:34.076   305   305 E SMD     : DCD ON
07-05 11:31:34.286  7676  7676 D AndroidRuntime: 
07-05 11:31:34.286  7676  7676 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 11:31:34.286  7676  7676 D AndroidRuntime: CheckJNI is OFF
07-05 11:31:34.286  7676  7676 D AndroidRuntime: readGMSProperty: start
07-05 11:31:34.286  7676  7676 D AndroidRuntime: readGMSProperty: already setted!!
07-05 11:31:34.286  7676  7676 D AndroidRuntime: readGMSProperty: end
07-05 11:31:34.296  7676  7676 D AndroidRuntime: addProductProperty: start
07-05 11:31:34.456  7676  7676 E AffinityControl: AffinityControl: registerfunction enter
07-05 11:31:34.486  7676  7676 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-05 11:31:34.486   758  1143 D PackageManager: START PACKAGE DELETE: observer{541059039}
07-05 11:31:34.486   758  1143 D PackageManager: pkg{<packageName>}
07-05 11:31:34.486   758  1143 D PackageManager: user{0}
07-05 11:31:34.486   758  1143 D PackageManager: caller{2000}
07-05 11:31:34.486   758  1143 D PackageManager: flags{2}
07-05 11:31:34.486   758  1143 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-05 11:31:34.486   758  1143 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-05 11:31:34.486   758  1143 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-05 11:31:34.486   758  1143 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 11:31:34.486   758  1143 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 11:31:34.496   758  1064 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-05 11:31:34.496   758  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-05 11:31:34.496   758  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-05 11:31:34.496   758  1064 D ApplicationPolicy: getApplicationUninstallationEnabled
07-05 11:31:34.496   758  1064 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-05 11:31:34.496   758  1064 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
07-05 11:31:34.496   758  1001 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
07-05 11:31:34.496   758  1001 I ActivityManager: Killing 7365:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
07-05 11:31:34.496   758  1001 I ActivityManager:   Force finishing activity ActivityRecord{2503f12f u0 com.test.thalitest/.MainActivity t23}
07-05 11:31:34.506   758  1001 D FocusedStackFrame: Set to : 0
07-05 11:31:34.506   266  1124 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
07-05 11:31:34.506   266   343 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
07-05 11:31:34.526   758  3059 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 11:31:34.536   758  3059 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 11:31:34.616   758  1064 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
07-05 11:31:34.646  1607  1607 I art     : Explicit concurrent mark sweep GC freed 1564(74KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 19MB/32MB, paused 392us total 23.921ms
07-05 11:31:34.656  6187  6187 I art     : Explicit concurrent mark sweep GC freed 20181(2MB) AllocSpace objects, 2(40KB) LOS objects, 31% free, 17MB/25MB, paused 434us total 25.059ms
07-05 11:31:34.676  4888  4888 I art     : Explicit concurrent mark sweep GC freed 288(26KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 766us total 32.360ms
07-05 11:31:34.696  7243  7243 I art     : Explicit concurrent mark sweep GC freed 9741(555KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 310us total 73.296ms
07-05 11:31:34.706  4203  4203 I art     : Explicit concurrent mark sweep GC freed 4801(283KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 15MB/26MB, paused 338us total 19.954ms
07-05 11:31:34.706   758   989 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
07-05 11:31:34.706   758   989 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
07-05 11:31:34.706   758  1046 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
07-05 11:31:34.706  1695  1695 E SamsungIME: mOCRHelper is null
07-05 11:31:34.716  2011  2393 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-05 11:31:34.716  1445  1445 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
07-05 11:31:34.716  1445  1445 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 11:31:34.716  1445  1445 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-05 11:31:34.716  1445  1445 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
07-05 11:31:34.716   758  1120 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-05 11:31:34.726  1445  1445 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 11:31:34.726  1445  1445 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 11:31:34.726  1445  1445 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-05 11:31:34.726  4332  4332 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-05 11:31:34.726  1413  1413 D RegisteredServicesCache: empty dynamic service
07-05 11:31:34.726   758  1145 V NetworkStats: removeUidsLocked() for UIDs [10079]
07-05 11:31:34.726   758  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 11:31:34.726   758  1145 V NetworkStats: performPollLocked(flags=0x3)
07-05 11:31:34.726   758  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-05 11:31:34.726   758  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 11:31:34.736  4332  4332 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1467711094734
07-05 11:31:34.736   758  1145 V NetworkStats: performPollLocked() took 5ms
07-05 11:31:34.736   758  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 11:31:34.746  1445  1445 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
07-05 11:31:34.746  1445  1445 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 11:31:34.746  1445  1445 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-05 11:31:34.746   758  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 11:31:34.746   758  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 11:31:34.756  4332  4332 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
07-05 11:31:34.756   758  3275 E libprocessgroup: failed to kill 1 processes for processgroup 7365
07-05 11:31:34.756  4332  4332 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
07-05 11:31:34.786  7193  7193 I art     : Explicit concurrent mark sweep GC freed 5363(264KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 497us total 105.550ms
07-05 11:31:34.806   758   758 I art     : Explicit concurrent mark sweep GC freed 46691(3MB) AllocSpace objects, 13(12MB) LOS objects, 30% free, 36MB/52MB, paused 1.572ms total 109.578ms
07-05 11:31:34.806   758  1064 I art     : WaitForGcToComplete blocked for 72.788ms for cause Explicit
07-05 11:31:34.806   758   758 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
07-05 11:31:34.816   758   758 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
07-05 11:31:34.816   758   989 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
07-05 11:31:34.826   758  1602 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-05 11:31:34.826   758  1602 D SecContentProvider2: mCursor = null
07-05 11:31:34.836   758   758 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
07-05 11:31:34.846   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
07-05 11:31:34.856   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
07-05 11:31:34.856   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
07-05 11:31:34.866   758   989 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
07-05 11:31:34.866   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
07-05 11:31:34.876   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
07-05 11:31:34.886  4332  4332 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
07-05 11:31:34.886   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
07-05 11:31:34.896   758   989 D EnterpriseDeviceManagerService: Package has changed for user 0
07-05 11:31:34.896   758   989 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-05 11:31:34.896  4332  4332 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
07-05 11:31:34.906   758   758 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
07-05 11:31:34.906   758   989 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
07-05 11:31:34.906   758   758 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
07-05 11:31:34.906  6753  6753 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
07-05 11:31:34.906   758  1644 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-05 11:31:34.906   758  1644 D ActivityManager: caller:android.app.ApplicationThreadProxy@16f57851, r.packageName :com.sec.esdk.elm
07-05 11:31:34.916   758   758 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
07-05 11:31:34.916  6753  6753 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
07-05 11:31:34.916  3555  3555 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
07-05 11:31:34.916  3555  3555 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 11:31:34.916  3555  3555 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
07-05 11:31:34.916  3555  3555 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-05 11:31:34.916  3555  3555 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-05 11:31:34.916  3555  3555 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-05 11:31:34.916  3555  3555 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-05 11:31:34.916  3555  3555 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:31:34.916  3555  3555 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:31:34.916  3555  3555 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-05 11:31:34.916  3555  3555 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 11:31:34.916  3555  3555 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 11:31:34.916  3555  3555 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-05 11:31:34.916  3555  3555 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-05 11:31:34.926  6753  6753 D elm:14491: ElmAgentService : onCreate()
07-05 11:31:34.926  6753  7703 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-05 11:31:34.926   758   758 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
07-05 11:31:34.926   758   758 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
07-05 11:31:34.926  6753  7703 D elm:14491: MainReceiver.listeningToPackageRemoved()
07-05 11:31:34.926  6753  7703 D elm:14491: MDMBridge.getInstance()
07-05 11:31:34.926  6753  7703 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
07-05 11:31:34.926  6753  7703 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
07-05 11:31:34.926  3747  3747 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-05 11:31:34.926  3747  3747 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
07-05 11:31:34.936   758   758 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
07-05 11:31:34.936   758   758 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
07-05 11:31:34.936   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
07-05 11:31:34.936   758  1614 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 11:31:34.936  6753  6753 D elm:14491: ElmAgentService : onDestroy().
07-05 11:31:34.936   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
07-05 11:31:34.946   758   989 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 11:31:34.946   758   989 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
07-05 11:31:34.946   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
07-05 11:31:34.946   758  1480 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-05 11:31:34.946   758  1480 D ActivityManager: caller:android.app.ApplicationThreadProxy@3673c2bb, r.packageName :com.google.android.gms
07-05 11:31:34.956  2286  2286 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
07-05 11:31:34.956  2286  2286 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
07-05 11:31:34.956  2286  2286 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-05 11:31:34.956  2286  2286 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-05 11:31:34.956  2286  7705 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-05 11:31:34.956  2286  7705 D AccountUtils: Clearing selected account for com.test.thalitest
07-05 11:31:34.966   758  1461 D ActivityManager: caller:android.app.ApplicationThreadProxy@369f9584, r.packageName :com.google.android.gms
07-05 11:31:34.966   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
07-05 11:31:34.966  2286  2286 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
07-05 11:31:34.966  2286  2286 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
07-05 11:31:34.966  2286  2286 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-05 11:31:34.966  2286  2286 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-05 11:31:34.966   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
07-05 11:31:34.966   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
07-05 11:31:34.966   758  3296 D ActivityManager: caller:android.app.ApplicationThreadProxy@289765ee, r.packageName :com.google.android.gms
07-05 11:31:34.966   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
07-05 11:31:34.976   758   989 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 11:31:34.976   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
07-05 11:31:34.976   758   989 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
07-05 11:31:34.976   758  1602 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 11:31:34.976   758  1602 D ActivityManager: caller:android.app.ApplicationThreadProxy@13f48aa1, r.packageName :com.google.android.gms
07-05 11:31:34.976   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
07-05 11:31:34.976  2286  7705 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
07-05 11:31:34.986   758  1433 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
07-05 11:31:34.986   758  1668 D ActivityManager: caller:android.app.ApplicationThreadProxy@1f530eaa, r.packageName :com.google.android.gms
07-05 11:31:34.986   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
07-05 11:31:34.996   758  1614 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 11:31:34.996   758  1614 D ActivityManager: caller:android.app.ApplicationThreadProxy@3fca4d, r.packageName :com.google.android.gms
07-05 11:31:34.996   758   758 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
07-05 11:31:34.996   758   758 D RCPManagerService: PackageReceiver onReceive()
07-05 11:31:34.996   758   758 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
07-05 11:31:34.996   758   758 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-05 11:31:34.996  7035  7035 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
07-05 11:31:34.996   758   758 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 11:31:34.996  7035  7035 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
07-05 11:31:34.996  7035  7035 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
07-05 11:31:34.996   758   758 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-05 11:31:34.996   758   758 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-05 11:31:34.996   758   758 V EnterpriseBillingPolicy: uID is 10079
07-05 11:31:34.996   758   758 V EnterpriseBillingPolicy: Removed Packageuid is0
07-05 11:31:34.996   758   758 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-05 11:31:34.996   758   758 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
07-05 11:31:34.996   758   758 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-05 11:31:34.996   758   758 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-05 11:31:34.996   758   758 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-05 11:31:34.996   758   758 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-05 11:31:35.006   758  1178 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
07-05 11:31:35.006   758   758 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
07-05 11:31:35.006   758   989 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 11:31:35.006   758   989 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
07-05 11:31:35.016  7052  7052 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-05 11:31:35.016  7052  7052 I PCWCLIENTTRACE_PushUtil: sales region : global
07-05 11:31:35.016  7052  7052 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-05 11:31:35.016  7052  7052 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
07-05 11:31:35.026   758   989 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 11:31:35.026   758   989 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
07-05 11:31:35.036   758  1362 D ActivityManager: startService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.sec.android.app.shealth
07-05 11:31:35.036   758  1362 D ActivityManager: caller:android.app.ApplicationThreadProxy@2f744d7c, r.packageName :com.sec.android.app.shealth
07-05 11:31:35.056  2286  7712 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
07-05 11:31:35.056  2286  7712 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
07-05 11:31:35.056   758  1234 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 11:31:35.056   758  1234 D ActivityManager: caller:android.app.ApplicationThreadProxy@3b239e26, r.packageName :com.google.android.gms
07-05 11:31:35.056  2286  7712 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
07-05 11:31:35.056  2286  7712 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
07-05 11:31:35.066  2286  7712 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
07-05 11:31:35.066  2286  7712 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
07-05 11:31:35.066  2286  7712 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
07-05 11:31:35.076   758  3059 I SQLiteConnectionPool: exportDB...
07-05 11:31:35.076   758  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 11:31:35.076   758  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4297, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 11:31:35.076   758  1319 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 11:31:35.076   758  1319 D BatteryService: stay LED for fully charged
07-05 11:31:35.076   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 11:31:35.076  2286  7712 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
07-05 11:31:35.076  3747  3747 I ConfigService: onCreate
07-05 11:31:35.076  3747  3747 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-05 11:31:35.076   758   758 I MotionRecognitionService: Plugged
07-05 11:31:35.076   758   758 I MotionRecognitionService: setPowerConnected  = true
07-05 11:31:35.076  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 11:31:35.076  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:31:35.086  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 11:31:35.086  3004  3279 D HeadsetStateMachine: Disconnected process message: 10
07-05 11:31:35.086  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 11:31:35.086   758  1234 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 11:31:35.086   758  1234 D ActivityManager: caller:android.app.ApplicationThreadProxy@3189ef5f, r.packageName :com.google.android.gms
07-05 11:31:35.086  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:31:35.086  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:31:35.086  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:31:35.086   758  1461 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 11:31:35.096   758  1461 D ActivityManager: caller:android.app.ApplicationThreadProxy@178c6a75, r.packageName :com.google.android.gms
07-05 11:31:35.096  2286  7712 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
07-05 11:31:35.096   758  3047 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
07-05 11:31:35.096  3747  3747 I ConfigService: onBind returning update interface
07-05 11:31:35.096   758  3047 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.096   758  3047 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.096   758  3047 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.096   758  3047 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.106  2286  7712 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
07-05 11:31:35.116   758   989 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 11:31:35.126   758   989 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 11:31:35.126   758   989 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
07-05 11:31:35.126   758  3059 I SQLiteConnectionPool: ...exportDB
07-05 11:31:35.136   758  3059 D SSRM:aY : MSG_TYPE_APP_REMOVED::
07-05 11:31:35.136  7716  7716 E Zygote  : MountEmulatedStorage()
07-05 11:31:35.136  7716  7716 E Zygote  : v2
07-05 11:31:35.136  7716  7716 I libpersona: KNOX_SDCARD checking this for 10043
07-05 11:31:35.136  7716  7716 I libpersona: KNOX_SDCARD not a persona
07-05 11:31:35.136   758  1064 I art     : Explicit concurrent mark sweep GC freed 21658(1270KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 36MB/52MB, paused 2.339ms total 329.808ms
07-05 11:31:35.146   758  3047 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7716 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 11:31:35.156  7716  7716 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 11:31:35.156  7716  7716 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 11:31:35.156  7716  7716 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-05 11:31:35.166   758  1668 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 11:31:35.166   758  1668 D ActivityManager: caller:android.app.ApplicationThreadProxy@1c286644, r.packageName :com.google.android.gms
07-05 11:31:35.166  2286  2286 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-05 11:31:35.166  3747  3747 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-05 11:31:35.166  3747  3747 I ConfigService: onBind returning service broker
07-05 11:31:35.186  7716  7716 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 11:31:35.186  2286  7729 I PeopleContactsSync: CP2 sync disabled
07-05 11:31:35.186  7716  7716 D ActivityThread: Added TimaKeyStore provider
07-05 11:31:35.206   758  1362 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 11:31:35.206   758  1362 D ActivityManager: caller:android.app.ApplicationThreadProxy@1d67a2b0, r.packageName :com.google.android.gms
07-05 11:31:35.206  2286  7732 E SQLiteLog: (539) recovered 2 pages from /data/data/com.google.android.gms/databases/DocList.db-journal
07-05 11:31:35.206  2286  2286 I ConfigFetchService: service connected
07-05 11:31:35.206  2286  4249 I Icing   : doRemovePackageData com.test.thalitest
07-05 11:31:35.206  2286  7713 W BaseAppContext: Using Auth Proxy for data requests.
07-05 11:31:35.216   758   989 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 11:31:35.216   758   989 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
07-05 11:31:35.216  7716  7716 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
07-05 11:31:35.216  1445  1445 D SurfaceWidgetView: destroyHardwareResources():430515483
07-05 11:31:35.216  1445  1445 D Launcher: onRestart, Launcher: 285643865
07-05 11:31:35.216  1445  1445 D Launcher: onStart, Launcher: 285643865
07-05 11:31:35.216  1445  1445 D Launcher.HomeView: onStart
07-05 11:31:35.216  1445  1445 V ActivityThread: updateVisibility : ActivityRecord{2492b54a token=android.os.BinderProxy@1d98ec6a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-05 11:31:35.216  1816  1840 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
07-05 11:31:35.216  1816  2000 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
07-05 11:31:35.216  1816  2000 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
07-05 11:31:35.226   758   989 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
07-05 11:31:35.236   758   989 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
07-05 11:31:35.236  2286  7713 W BaseAppContext: Using Auth Proxy for data requests.
07-05 11:31:35.236   758   989 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
07-05 11:31:35.236   266   266 I SurfaceFlinger: id=15 createSurf (1080x1920),1 flag=4, Mauncher
07-05 11:31:35.246   758   989 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 11:31:35.246   758   989 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
07-05 11:31:35.246   758   989 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
07-05 11:31:35.256   758   989 D ResourcesManager: creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
07-05 11:31:35.256  7716  7716 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
07-05 11:31:35.256  7716  7716 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
07-05 11:31:35.256   758   989 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
07-05 11:31:35.266   758   989 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 11:31:35.266   758   989 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 11:31:35.266   758   989 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
07-05 11:31:35.266   758   989 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-05 11:31:35.266   758   989 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 11:31:35.266   758   989 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 11:31:35.266   758   989 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 11:31:35.266   758   989 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
07-05 11:31:35.276   758   989 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
07-05 11:31:35.276   758  1064 D PackageManager: delete codoeFile: 
07-05 11:31:35.276  7716  7716 D SPPClientService: PushLog.txt file is not deleted.
07-05 11:31:35.276  7716  7716 D SPPClientService: PushLog.txt file is not deleted.
07-05 11:31:35.276  7716  7716 D SPPClientService: ============PushLog. stop!
07-05 11:31:35.276   758   989 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
07-05 11:31:35.286   758   989 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 11:31:35.286   758   989 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
07-05 11:31:35.286   758  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1cfe4642 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t20} time:1565794
07-05 11:31:35.286   758   989 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 11:31:35.286   758   989 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
07-05 11:31:35.286   758  1064 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
07-05 11:31:35.286   758  1064 I AASA_removePackage: UID=10079 Target=com.test.thalitest
07-05 11:31:35.286   758  1046 D MultiWindowConverter: MultiWindow Gesture is not supported with launcher
07-05 11:31:35.286   758  1064 D PackageManager: result of delete: 1{541059039}
07-05 11:31:35.296   758   989 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 11:31:35.296   758   989 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}

```
