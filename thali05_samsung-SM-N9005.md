#### Test 757892682551a10_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
,06-30 13:55:19.497   302   302 E SMD     : DCD ON
06-30 13:55:19.777  7433  7433 D AndroidRuntime: 
06-30 13:55:19.777  7433  7433 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 13:55:19.787  7433  7433 D AndroidRuntime: CheckJNI is OFF
06-30 13:55:19.787  7433  7433 D AndroidRuntime: readGMSProperty: start
06-30 13:55:19.787  7433  7433 D AndroidRuntime: readGMSProperty: already setted!!
06-30 13:55:19.787  7433  7433 D AndroidRuntime: readGMSProperty: end
06-30 13:55:19.787  7433  7433 D AndroidRuntime: addProductProperty: start
06-30 13:55:19.917  7433  7433 E AffinityControl: AffinityControl: registerfunction enter
06-30 13:55:19.937  7433  7433 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 13:55:19.947   754  1144 E PersonaManagerService: inState():  stateMachine is null !!
06-30 13:55:19.947   754  1144 I PersonaManagerService: PersonaId don't exist
06-30 13:55:19.947   754  1144 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
06-30 13:55:19.947   754  1144 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
06-30 13:55:19.947   754  1144 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 13:55:19.947   754  1144 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
06-30 13:55:19.957   754  1144 W ActivityManager: mDVFSHelper.acquire()
06-30 13:55:19.957   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:19.957   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:19.957   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:19.957   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:19.997  7447  7447 E Zygote  : MountEmulatedStorage()
06-30 13:55:19.997  7447  7447 I libpersona: KNOX_SDCARD checking this for 10079
06-30 13:55:19.997  7447  7447 E Zygote  : v2
06-30 13:55:19.997  7447  7447 I libpersona: KNOX_SDCARD not a persona
06-30 13:55:20.007   754  1144 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7447 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-30 13:55:20.017  7447  7447 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:20.017  7447  7447 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 13:55:20.017  7447  7447 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
06-30 13:55:20.017  7433  7433 D AndroidRuntime: Shutting down VM
06-30 13:55:20.037  7447  7447 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:55:20.037  7447  7447 D ActivityThread: Added TimaKeyStore provider
06-30 13:55:20.047  1449  1449 V ActivityThread: updateVisibility : ActivityRecord{1f158be6 token=android.os.BinderProxy@8e4051d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-30 13:55:20.047  1792  1807 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
06-30 13:55:20.057   754  3297 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:20.067  7447  7447 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
06-30 13:55:20.067   754  3297 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:20.077  1449  1449 D SurfaceWidgetView: destroyHardwareResources():573337542
06-30 13:55:20.127   266   409 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
06-30 13:55:20.127   266  1643 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
06-30 13:55:20.147  1449  1449 D Launcher: onTrimMemory. Level: 20
06-30 13:55:20.147  7447  7447 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
06-30 13:55:20.147  7447  7447 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
06-30 13:55:20.167  7447  7447 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4896-4898)
06-30 13:55:20.167  7447  7447 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:55:20.197  7447  7447 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b03a5f0}
06-30 13:55:20.197  7447  7447 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:55:20.197  7447  7447 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 13:55:20.227  7447  7447 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 13:55:20.227  7447  7447 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:55:20.227  7447  7447 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-30 13:55:20.227   754  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:55:20.227   754  1584 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:55:20.227   754  1584 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:55:20.227   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:55:20.227   754  1584 D BatteryService: stay LED for fully charged
,06-30 13:55:20.237   754   754 I MotionRecognitionService: Plugged
06-30 13:55:20.237   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:55:20.237  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:55:20.237  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:55:20.237  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:55:20.237  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:55:20.237  3234  3454 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:55:20.237  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:55:20.237  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:20.237  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:20.247  7447  7447 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,06-30 13:55:20.247  7447  7447 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
06-30 13:55:20.247  7447  7447 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,06-30 13:55:20.257  7447  7447 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
06-30 13:55:20.257  7447  7447 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
06-30 13:55:20.257  7447  7447 I Adreno-EGL: Build Date: 11/19/14 Wed
06-30 13:55:20.257  7447  7447 I Adreno-EGL: Local Branch: mybranch5813579
06-30 13:55:20.257  7447  7447 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
06-30 13:55:20.257  7447  7447 I Adreno-EGL: Local Patches: NONE
06-30 13:55:20.257  7447  7447 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,06-30 13:55:20.347  7447  7486 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,06-30 13:55:20.387  7447  7447 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 13:55:20.387  7447  7447 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 13:55:20.407  7447  7447 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,06-30 13:55:20.407  7447  7447 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:55:20.407  7447  7447 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 13:55:20.457  7447  7447 D Activity: performCreate Call secproduct feature valuefalse
,06-30 13:55:20.457  7447  7447 D Activity: performCreate Call debug elastic valuetrue
,06-30 13:55:20.467  7447  7502 D OpenGLRenderer: Render dirty regions requested: true
,06-30 13:55:20.477   754  1652 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,06-30 13:55:20.477   754  1652 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-30 13:55:20.477   754  1652 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
06-30 13:55:20.477   754   754 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,06-30 13:55:20.477   754   754 D PersonaManagerService: getPersonasForUser(): returning null!
,06-30 13:55:20.497   266   266 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,06-30 13:55:20.507  7447  7502 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 13:55:20.507  7447  7502 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0x9e307060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,06-30 13:55:20.507  7447  7502 D OpenGLRenderer: Enabling debug mode 0
,06-30 13:55:20.527  7447  7447 V ActivityThread: updateVisibility : ActivityRecord{22532eaa token=android.os.BinderProxy@1695194c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,06-30 13:55:20.547  7447  7447 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1695194c time:305276
,06-30 13:55:20.567   754  1045 W ActivityManager: mDVFSHelper.release()
06-30 13:55:20.567   754  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{804c7a1 u0 com.test.thalitest/.MainActivity t23} time:305297
,06-30 13:55:20.577   754  1045 D MultiWindowConverter: This application or window do not support multiwindow
,06-30 13:55:20.607  7447  7447 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7447
,06-30 13:55:20.687  7447  7447 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 13:55:20.777  7447  7506 D jxcore_app_log: JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259431296
,06-30 13:55:20.787  7447  7506 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 13:55:20.787  7447  7506 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 13:55:20.787  7447  7506 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 13:55:20.787  7447  7506 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 13:55:20.787  7447  7506 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,06-30 13:55:20.787  7447  7506 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14ec965a added. We now have 1 listener(s)
,06-30 13:55:20.787  7447  7506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:2A:28:2D
,06-30 13:55:20.797  7447  7506 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,06-30 13:55:20.797  7447  7506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 13:55:20.797  7447  7506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 13:55:20.797  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 13:55:20.797  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 13:55:20.797  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 13:55:20.797  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:2A:28:2D
06-30 13:55:20.797  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 13:55:20.797  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 13:55:20.797  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 13:55:20.797  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 13:55:20.797  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 13:55:20.797  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 13:55:20.797  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 13:55:20.797  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1aa68d81 added. We now have 1 listener(s)
06-30 13:55:20.797  7447  7506 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:55:20.807  7447  7506 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,06-30 13:55:20.807  7447  7506 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,06-30 13:55:20.807  7447  7506 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,06-30 13:55:20.807  7447  7506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 13:55:20.817  7447  7506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:2A:28:2D
,06-30 13:55:20.817   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:20.817  7447  7506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:55:20.817  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:20.817  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:20.817  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:20.817  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:20.817  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 13:55:20.817  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 13:55:20.817  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 13:55:20.817  7447  7506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 13:55:20.817  7447  7506 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 13:55:20.817   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:20.817  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:20.817   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:20.817  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:55:20.817  7447  7506 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 13:55:20.857  7447  7447 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 13:55:21.677  7447  7514 W jxcore-log: Initializing JXcore engine
,06-30 13:55:21.677  7447  7514 W jxcore-log: JXcore engine is ready
,06-30 13:55:21.737  1947  1947 E auditd  : In denial and Property audit_ondenial is set to 1 
,06-30 13:55:21.737  1947  1947 E audit   : type=1400 msg=audit(1467287721.727:203): avc:  denied  { ioctl } for  pid=7514 comm="Thread-1253" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,06-30 13:55:21.737  1947  1947 E audit   :  SEPF_SM-N9005_5.0-1_0032
06-30 13:55:21.737  1947  1947 E audit   : 
,06-30 13:55:21.737   754  1034 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
06-30 13:55:21.737   754  1034 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,06-30 13:55:21.737   754  1007 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,06-30 13:55:21.737   754  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:21.737   754  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:21.737   754  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:21.737   754  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:21.737  1947  1947 E audit   : type=1300 msg=audit(1467287721.727:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=1 a3=98ea08d8 items=0 ppid=336 ppcomm=main pid=7514 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1253" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
06-30 13:55:21.737  1947  1947 E audit   : type=1320 msg=audit(1467287721.727:203): 
,06-30 13:55:21.737   754  1034 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,06-30 13:55:21.767  7447  7514 W jxcore-log: Starting JXcore engine
,06-30 13:55:21.777   754  1007 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7516 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 13:55:21.787  7516  7516 E Zygote  : MountEmulatedStorage()
06-30 13:55:21.787  7516  7516 E Zygote  : v2
06-30 13:55:21.787  7516  7516 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:55:21.787  7516  7516 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:21.807  7516  7516 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:21.807  7516  7516 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 13:55:21.807  7516  7516 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:55:21.807   754  3297 D SSRM:n  : SIOP:: AP = 330, PST = 317, CUR = 450
,06-30 13:55:21.837  7516  7516 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:21.837  7516  7516 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:21.857  7516  7516 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,06-30 13:55:21.867  7516  7516 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,06-30 13:55:21.877  7516  7516 D SecurityLogAgent:  SeDenialReceiver : File path = null
,06-30 13:55:21.877   754  1571 I ActivityManager: Killing 6688:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 15): emptyCount ##41
,06-30 13:55:21.877  7447  7514 W jxcore-log: Platform android
06-30 13:55:21.877  7447  7514 W jxcore-log: 
,06-30 13:55:21.877  7447  7514 W jxcore-log: Process ARCH arm
06-30 13:55:21.877  7447  7514 W jxcore-log: 
,06-30 13:55:22.077  7447  7514 I jxcore-log: JXcore Cordova bridge is ready!
06-30 13:55:22.077  7447  7514 I jxcore-log: 
,06-30 13:55:22.077  7447  7514 W jxcore-log: JXcore engine is started
,06-30 13:55:22.077  7447  7506 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 13:55:22.077  7447  7447 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-30 13:55:22.487   302   302 E SMD     : DCD ON
,06-30 13:55:25.487   302   302 E SMD     : DCD ON
,06-30 13:55:28.487   302   302 E SMD     : DCD ON
,06-30 13:55:30.007   754  1065 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,06-30 13:55:30.327   754  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:55:30.327   754  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:55:30.327   754  1343 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:55:30.327   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:55:30.327   754  1343 D BatteryService: stay LED for fully charged
,06-30 13:55:30.327   754   754 I MotionRecognitionService: Plugged
06-30 13:55:30.327   754   754 I MotionRecognitionService: setPowerConnected  = true
06-30 13:55:30.337  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:55:30.337  3234  3454 D HeadsetStateMachine: Disconnected process message: 10
06-30 13:55:30.337  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:55:30.337  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:55:30.337  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:55:30.337  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:30.337  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:55:30.337  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:31.487   302   302 E SMD     : DCD ON
,06-30 13:55:31.537   754  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 13:55:31.537   754  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:55:31.537   754  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:55:31.547   754  1102 I TLC_TIMA_PKM_initialize: initializing...
06-30 13:55:31.547   754  1102 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
06-30 13:55:31.547   754  1102 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
06-30 13:55:31.547   754  1102 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
06-30 13:55:31.547   754  1102 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
06-30 13:55:31.547   754  1102 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
06-30 13:55:31.547   754  1102 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
06-30 13:55:31.547   754  1102 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
06-30 13:55:31.547   754  1102 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,06-30 13:55:31.547   754  1102 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 13:55:31.577   754  1102 D QSEECOMAPI: : Loaded image: APP id = 2
,06-30 13:55:31.577   754  1102 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,06-30 13:55:31.587   754  1102 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-30 13:55:31.847   754  3297 D SSRM:n  : SIOP:: AP = 360, PST = 321, CUR = 450
,06-30 13:55:31.857  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
06-30 13:55:31.857  7447  7514 I jxcore-log: 
,06-30 13:55:31.867  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
06-30 13:55:31.867  7447  7514 I jxcore-log: 
,06-30 13:55:31.867   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:31.867  7447  7514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:55:31.867  7447  7514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:31.867  7447  7514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:31.867  7447  7514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:31.867  7447  7514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:31.867  7447  7514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 13:55:31.867  7447  7514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 13:55:31.867  7447  7514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-30 13:55:31.877  7447  7514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,06-30 13:55:31.877  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-30 13:55:31.877  7447  7514 I jxcore-log: 
,06-30 13:55:31.877  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
06-30 13:55:31.877  7447  7514 I jxcore-log: 
,06-30 13:55:32.127   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:55:32.237  7447  7514 I jxcore-log: Unit Test app is loaded
06-30 13:55:32.237  7447  7514 I jxcore-log: 
,06-30 13:55:32.247  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-30 13:55:32.247  7447  7514 I jxcore-log: 
,06-30 13:55:32.247  7447  7514 I jxcore-log: My device name is: samsung-SM-N9005
06-30 13:55:32.247  7447  7514 I jxcore-log: 
,06-30 13:55:32.247  7447  7447 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,06-30 13:55:32.257  7447  7514 I jxcore-log: WARN testUtils: myNameCallback not set!
06-30 13:55:32.257  7447  7514 I jxcore-log: 
,06-30 13:55:32.307  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:55:32.307  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a2fc63b added. We now have 2 listener(s)
06-30 13:55:32.307  7447  7506 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 13:55:32.307  7447  7506 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:55:32.307  7447  7506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,06-30 13:55:32.307  7447  7506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:55:32.307  7447  7506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:55:32.307  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a2fc63b removed from the list
,06-30 13:55:32.307  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:55:32.307  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15f9158 added. We now have 2 listener(s)
,06-30 13:55:32.307  7447  7506 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 13:55:32.307  7447  7506 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:55:32.307  7447  7506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:55:32.307  7447  7506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:55:32.307  7447  7506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:55:32.307  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15f9158 removed from the list
,06-30 13:55:32.307  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:55:32.307  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3609e2b1 added. We now have 2 listener(s)
06-30 13:55:32.307  7447  7506 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 13:55:32.317  7447  7506 I WifiManager: packageName : com.test.thalitest
,06-30 13:55:32.317   754  1697 D SecContentProvider: uri = 18 selection = isWifiEnabled
06-30 13:55:32.317   754  1697 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
06-30 13:55:32.317   754  1697 D SecContentProvider2: mCursor = null
,06-30 13:55:32.317   754  1697 D WifiService: setWifiEnabled: false pid=7447, uid=10079
06-30 13:55:32.317   754  1697 D SettingsProvider: name = wifi_on
,06-30 13:55:32.317   754  1149 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,06-30 13:55:32.327  1284  1284 I wpa_supplicant: reset timer : RESET_TIMER 0
06-30 13:55:32.327  1284  1284 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
06-30 13:55:32.327  7447  7506 D BluetoothAdapter: disable()
06-30 13:55:32.327  1284  1284 I wpa_supplicant: P2P: Current p2p state = IDLE
06-30 13:55:32.327   754  1378 D SettingsProvider: name = bluetooth_on
,06-30 13:55:32.327   754  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,06-30 13:55:32.327  3234  3289 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
06-30 13:55:32.327  3234  3289 D BluetoothAdapterProperties: Setting state to 13
06-30 13:55:32.327  3234  3289 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
06-30 13:55:32.327  3234  3289 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-30 13:55:32.327  3234  3289 D BluetoothAdapterService: updateAdapterState state is 13
,06-30 13:55:32.327   754  1584 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:32.327   754  1584 D ActivityManager: caller:android.app.ApplicationThreadProxy@42f8a80, r.packageName :com.android.bluetooth
06-30 13:55:32.327  7447  7506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 13:55:32.327  3234  3234 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,06-30 13:55:32.327  3234  3289 D BluetoothAdapterService: Autoconnection is available 
06-30 13:55:32.327  3234  3234 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@106f1062, channel: 19, state: LISTENING
06-30 13:55:32.337  3234  3234 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@106f1062, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@20474a0a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@241405f3mSocket: android.net.LocalSocket@348c2b0 impl:android.net.LocalSocketImpl@156cb529 fd:FileDescriptor[78]
06-30 13:55:32.337  3234  3234 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@348c2b0 impl:android.net.LocalSocketImpl@156cb529 fd:FileDescriptor[78]
06-30 13:55:32.327  3234  3289 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,06-30 13:55:32.337  3234  3289 D BluetoothAdapterService: terminating service from this receiver
,06-30 13:55:32.337  1284  1284 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,06-30 13:55:32.337  4615  4615 D BluetoothPbap: Proxy object disconnected
,06-30 13:55:32.337   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:32.337  3234  3289 D BluetoothAdapterProperties: onBluetoothDisable()
,06-30 13:55:32.337   754  1476 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,06-30 13:55:32.337  3234  3289 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,06-30 13:55:32.347  3234  3292 D BluetoothAdapterProperties: Scan Mode:20
,06-30 13:55:32.347  3234  3289 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,06-30 13:55:32.347   754   754 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:32.347  3234  3289 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,06-30 13:55:32.347  3234  3289 E bt-btif : cmd socket is not created
06-30 13:55:32.347  1189  1189 D BluetoothTile:  onBluetoothStateChange:
,06-30 13:55:32.347   754   754 I InputMethodManagerService: [BT Setting State] State =13
,06-30 13:55:32.347  3234  6009 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,06-30 13:55:32.347  3234  3295 D bt_vendor: op for 7
06-30 13:55:32.347  3234  3293 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,06-30 13:55:32.347  3234  3289 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,06-30 13:55:32.357  1189  1608 D BluetoothTile:  handleUpdatestate:false name:null
,06-30 13:55:32.357  1189  1189 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,06-30 13:55:32.357  3234  3295 D bt_upio : proc btwrite assertion
06-30 13:55:32.357  1189  1189 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:32.357   754  1149 E native  : do suspend true
,06-30 13:55:32.357  1189  1608 D BluetoothTile:  handleUpdatestate:false name:null
,06-30 13:55:32.357  3234  3295 D bt_vendor: op for 7
06-30 13:55:32.357  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:32.367  3234  3295 D bt_vendor: op for 7
,06-30 13:55:32.367  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:32.367  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,06-30 13:55:32.367  3234  3295 D bt_vendor: op for 7
06-30 13:55:32.367  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:32.367   754  1378 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,06-30 13:55:32.367   754   781 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,06-30 13:55:32.367  3234  3295 D bt_vendor: op for 7
06-30 13:55:32.367  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:32.367  1189  1189 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
06-30 13:55:32.367  7447  7506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:55:32.367  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:32.367  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:32.367  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:32.367  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:32.367  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 13:55:32.367  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 13:55:32.367  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-30 13:55:32.367  7447  7506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,06-30 13:55:32.367  7447  7506 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 13:55:32.367  3234  3295 D bt_vendor: op for 7
06-30 13:55:32.367  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:32.367   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:32.367   754  1148 D WifiP2pService: InactiveState{ what=143375 }
06-30 13:55:32.367   754  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-30 13:55:32.367  3234  3293 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
06-30 13:55:32.367  3234  3295 D bt_vendor: op for 7
06-30 13:55:32.367  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:32.377  3234  3293 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:55:32.377  3234  3293 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
06-30 13:55:32.377  3234  3293 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
06-30 13:55:32.377  3234  3293 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:55:32.377  3234  3293 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,06-30 13:55:32.377  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:32.377  3234  3234 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@385f0e4f, channel: 5, state: LISTENING
06-30 13:55:32.377  3234  3234 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@385f0e4f, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4a5c27b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16ef59dcmSocket: android.net.LocalSocket@d727ae5 impl:android.net.LocalSocketImpl@d4e49ba fd:FileDescriptor[80]
,06-30 13:55:32.377  3234  3234 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d727ae5 impl:android.net.LocalSocketImpl@d4e49ba fd:FileDescriptor[80]
06-30 13:55:32.377  3234  3234 I BtOppRfcommListener: stopping Accept Thread
06-30 13:55:32.377   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:32.377  3234  3295 D bt_vendor: op for 7
06-30 13:55:32.377  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:32.377  3234  3234 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@4a8406b, channel: 12, state: LISTENING
06-30 13:55:32.377  3234  3234 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@4a8406b, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f25132d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d0637c8mSocket: android.net.LocalSocket@d54e061 impl:android.net.LocalSocketImpl@35874786 fd:FileDescriptor[84]
06-30 13:55:32.377  3234  3234 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d54e061 impl:android.net.LocalSocketImpl@35874786 fd:FileDescriptor[84]
,06-30 13:55:32.377  3234  6009 I BtOppRfcommListener: BluetoothSocket listen thread finished
,06-30 13:55:32.377  3234  3295 D bt_vendor: op for 7
06-30 13:55:32.377  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:32.377  3234  3295 D bt_vendor: op for 7
,06-30 13:55:32.377  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:32.377   295  1063 D CommandListener: Clearing all IP addresses on wlan0
,06-30 13:55:32.387  3234  3295 D bt_vendor: op for 7
,06-30 13:55:32.387  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:32.387  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 13:55:32.387  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
,06-30 13:55:32.387  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 13:55:32.387  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 13:55:32.387  1189  1189 D QSpanel : label top:23
06-30 13:55:32.387  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 13:55:32.387  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
,06-30 13:55:32.387   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:32.387  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 13:55:32.387  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 13:55:32.387  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 13:55:32.387  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 13:55:32.387  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:32.387   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:32.397  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,06-30 13:55:32.397  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:32.397  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:32.397  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:32.397  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:32.397  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:32.397  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 13:55:32.397  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 13:55:32.397  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 13:55:32.397  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
06-30 13:55:32.397  7447  7447 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,06-30 13:55:32.397   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:32.397  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:55:32.407  4615  4615 D PbapServerProfile: Bluetooth service disconnected
06-30 13:55:32.407  1757  1757 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,06-30 13:55:32.407  4615  4615 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:32.407  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,06-30 13:55:32.407   754  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,06-30 13:55:32.407   754  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@237128b9, r.packageName :com.android.settings
,06-30 13:55:32.417   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:32.417   754  1570 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,06-30 13:55:32.417   754  1766 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:32.417   754  1766 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:32.417   754  1766 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
06-30 13:55:32.417   754  1766 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:32.417   754  1766 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,06-30 13:55:32.417   754  1766 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 13:55:32.417   754  1766 I qtaguid : Tagging socket 367 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 754, getuid(): 1000
,06-30 13:55:32.427   754  1766 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 13:55:32.427   754  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-30 13:55:32.427   754  1151 E ConnectivityService: updateNetworkInfo()
06-30 13:55:32.427   754  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 13:55:32.427   754  1151 E ConnectivityService: updateNetworkInfo()
06-30 13:55:32.427   754  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
06-30 13:55:32.427   754  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,06-30 13:55:32.427   754   754 I WifiTrafficPoller: evaluateTrafficStatsPolling
,06-30 13:55:32.437  1627  1627 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,06-30 13:55:32.447   754   754 D WifiScanningService: SCAN_AVAILABLE : 1
,06-30 13:55:32.447   754   754 D RttService: SCAN_AVAILABLE : 1
06-30 13:55:32.447   754  1167 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,06-30 13:55:32.447   754  1168 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:32.447   754  1148 D WifiP2pService: InactiveState{ what=131204 }
06-30 13:55:32.447   754  1148 D WifiP2pService: P2pEnabledState{ what=131204 }
,06-30 13:55:32.447   754  1148 D WifiP2pService: sending p2p connection changed broadcast: FAILED
06-30 13:55:32.447   754  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:32.447   754  1045 D WifiDisplayAdapter: onP2pDisconnected
06-30 13:55:32.447   754  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
06-30 13:55:32.447   754  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
06-30 13:55:32.457  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
06-30 13:55:32.457  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:32.457  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
06-30 13:55:32.457  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:32.457  1189  1189 D StatusBar.NetworkController: applyOpen
06-30 13:55:32.457  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:32.457  1189  1189 D StatusBar.NetworkController: applyOpen
06-30 13:55:32.457  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:32.457  1189  1189 D StatusBar.NetworkController: applyOpen
06-30 13:55:32.457  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:32.457  1189  1189 D StatusBar.NetworkController: applyOpen
06-30 13:55:32.457   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:32.457   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:32.457   754  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
06-30 13:55:32.457   754  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
06-30 13:55:32.457   754  1045 D WifiDisplayController: disconnect
06-30 13:55:32.457   754  1045 D WifiDisplayController: updateConnection
06-30 13:55:32.457   754  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
06-30 13:55:32.457   754  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
06-30 13:55:32.467   754   754 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
06-30 13:55:32.467   754  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
06-30 13:55:32.467   754  1149 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
06-30 13:55:32.467   754  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
06-30 13:55:32.467   754  1045 D WifiDisplayAdapter: onP2pDisconnected
06-30 13:55:32.467   754  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
06-30 13:55:32.467   754  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
06-30 13:55:32.467   754  1148 D WifiP2pService: P2pDisablingState
06-30 13:55:32.467   754  1148 D WifiP2pService: P2pDisablingState{ what=147458 }
06-30 13:55:32.467   754  1148 D WifiP2pService: p2p socket connection lost
06-30 13:55:32.467   754  1148 D WifiP2pService: P2pDisabledState
06-30 13:55:32.467  1189  1189 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
06-30 13:55:32.477   754  1553 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
06-30 13:55:32.477  1189  1189 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
06-30 13:55:32.477   754  1149 E native  : do suspend true
06-30 13:55:32.477  4615  4615 D DockEventReceiver: finishStartingService: stopping service
06-30 13:55:32.477   754  1148 D WifiP2pService: P2pDisabledState{ what=143375 }
06-30 13:55:32.487   754  1148 D WifiP2pService: DefaultState{ what=143375 }
06-30 13:55:32.487  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
06-30 13:55:32.487   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:32.487  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:32.487  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
06-30 13:55:32.497  4615  4615 D BluetoothNotiBroadcastReceiver: onReceive
06-30 13:55:32.497   754  1378 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
06-30 13:55:32.497   754  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:32.497   754  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:32.497   754  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:32.497   754  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:32.497   295  1063 D CommandListener: Clearing all IP addresses on wlan0
06-30 13:55:32.497   754  1151 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
06-30 13:55:32.497   754  1151 D ConnectivityService: calling update connectivity
06-30 13:55:32.497   754  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:32.497   754  1766 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
06-30 13:55:32.497   754  1766 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
06-30 13:55:32.497   754  1044 D EntConnectivity: Not allowed due to - mEnabled false
06-30 13:55:32.497   754  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:32.507   754  1151 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:32.507   754  1151 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
06-30 13:55:32.507   754  1766 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:32.507   754  1766 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:32.507   754  1766 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
06-30 13:55:32.507  1189  1604 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
06-30 13:55:32.507   754  1151 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:32.507   754  1151 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:32.507   754  1151 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,fe80::ea50:8bff:fed7:fd2b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
06-30 13:55:32.507  1425  1425 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:32.507   754  1151 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
06-30 13:55:32.507   754  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,06-30 13:55:32.537  7568  7568 E Zygote  : MountEmulatedStorage()
06-30 13:55:32.537  7568  7568 E Zygote  : v2
06-30 13:55:32.537  7568  7568 I libpersona: KNOX_SDCARD checking this for 10140
06-30 13:55:32.537  7568  7568 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:32.547   754  1378 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7568 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,06-30 13:55:32.547   754  1151 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:32.547   754  1146 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:32.547   754  1146 V NetworkStats: updateIfacesLocked()
06-30 13:55:32.547   754  1146 V NetworkStats: performPollLocked(flags=0x1)
,06-30 13:55:32.547   754  1151 E ConnectivityService: updateNetworkInfo()
06-30 13:55:32.547   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
06-30 13:55:32.547   754  1152 D Tethering: MasterInitialState.processMessage what=3
06-30 13:55:32.547   754  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
06-30 13:55:32.547   754  1151 E ConnectivityService: updateNetworkInfo()
06-30 13:55:32.547   754  1151 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 13:55:32.547   754  1146 D NetworkStatsFactory: UpdateStatsForKnox
06-30 13:55:32.547   754  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
06-30 13:55:32.547  3234  3289 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
06-30 13:55:32.547   754  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:32.547  3234  3289 D BtConfig.SecureMode: isSecureModeOn:false
06-30 13:55:32.547   754  1151 E ConnectivityService: EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,fe80::ea50:8bff:fed7:fd2b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
06-30 13:55:32.547  3234  3289 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
06-30 13:55:32.557   754  1153 D SmartBondingService: getSBEnabled() enabled =false
06-30 13:55:32.547  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
06-30 13:55:32.557   754  1153 D SmartBondingService: getSBEnabled() enabled =false
06-30 13:55:32.547  3234  3289 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
06-30 13:55:32.557   754  1153 D SmartBondingService: getSBEnabled() enabled =false
06-30 13:55:32.547  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
06-30 13:55:32.547  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,06-30 13:55:32.557  1284  1284 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,06-30 13:55:32.557   754  1146 V NetworkStats: performPollLocked() took 4ms
,06-30 13:55:32.557   754   754 I WifiTrafficPoller: evaluateTrafficStatsPolling
06-30 13:55:32.557   754  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 13:55:32.557   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
06-30 13:55:32.557   754  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 13:55:32.557   754  1149 D SecContentProvider2: mCursor = null
,06-30 13:55:32.567  7568  7568 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:32.567  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
06-30 13:55:32.567  7568  7568 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 13:55:32.567   754  1553 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:32.567   754  1553 D ActivityManager: caller:android.app.ApplicationThreadProxy@26e530a, r.packageName :com.android.bluetooth
06-30 13:55:32.567  7568  7568 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
06-30 13:55:32.567  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
06-30 13:55:32.567  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
06-30 13:55:32.567  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
06-30 13:55:32.567  3234  3234 D HeadsetService: Received stop request...Stopping profile...
06-30 13:55:32.567   754  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 13:55:32.567   754  1544 D ActivityManager: caller:android.app.ApplicationThreadProxy@2a02977b, r.packageName :com.android.bluetooth
06-30 13:55:32.567  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:32.567  1189  1189 D StatusBar.NetworkController: getUpdateDataNetType(): 0
06-30 13:55:32.567  1189  1189 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
06-30 13:55:32.567  1189  1189 D StatusBar.NetworkController: updateDataNetType()
,06-30 13:55:32.567  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
06-30 13:55:32.567  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 13:55:32.567   754   754 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,06-30 13:55:32.567  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
06-30 13:55:32.567  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:32.567  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:32.567  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:32.567  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:32.567  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:32.567  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:32.567  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:32.567  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 13:55:32.567   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:32.567   754   781 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:32.567   754   781 D ActivityManager: caller:android.app.ApplicationThreadProxy@11642998, r.packageName :com.android.bluetooth
,06-30 13:55:32.567   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:32.567   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:32.567   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:32.567   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:32.567   754  1147 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
06-30 13:55:32.567  4615  4615 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:32.567  4615  4615 D HeadsetProfile: Bluetooth service disconnected
06-30 13:55:32.567   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 13:55:32.577  7447  7447 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:55:32.577  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
06-30 13:55:32.577  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 13:55:32.577   754  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,06-30 13:55:32.577  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,06-30 13:55:32.577  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:32.577  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:32.577  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:32.577  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:32.577  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:32.577  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:32.577  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:32.577  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 13:55:32.577  7447  7447 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:55:32.577  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 13:55:32.577   754  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
06-30 13:55:32.577  1189  1189 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,06-30 13:55:32.577   754  1357 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 13:55:32.577   754  1357 D ActivityManager: caller:android.app.ApplicationThreadProxy@2fe235f1, r.packageName :com.android.bluetooth
06-30 13:55:32.577  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
06-30 13:55:32.577  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,06-30 13:55:32.587  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,06-30 13:55:32.587   754   781 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:32.587   754   781 D ActivityManager: caller:android.app.ApplicationThreadProxy@392695d6, r.packageName :com.android.bluetooth
,06-30 13:55:32.587  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
06-30 13:55:32.587  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:32.587  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,06-30 13:55:32.587   754  1421 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:32.587   754  1421 D ActivityManager: caller:android.app.ApplicationThreadProxy@10993057, r.packageName :com.android.bluetooth
06-30 13:55:32.587  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
06-30 13:55:32.587  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,06-30 13:55:32.587  3234  3289 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
06-30 13:55:32.587   754  1553 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:32.587   754  1553 D ActivityManager: caller:android.app.ApplicationThreadProxy@383e4744, r.packageName :com.android.bluetooth
,06-30 13:55:32.587  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
06-30 13:55:32.587  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,06-30 13:55:32.587  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
06-30 13:55:32.587  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
06-30 13:55:32.587  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,06-30 13:55:32.587   754  1144 D SecContentProvider2: uri = 14 selection = getSealedState
06-30 13:55:32.587   754  1144 D SecContentProvider2: mCursor = null
,06-30 13:55:32.587  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
06-30 13:55:32.587  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
06-30 13:55:32.587  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
06-30 13:55:32.587  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
06-30 13:55:32.587  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
06-30 13:55:32.587  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,06-30 13:55:32.587  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
06-30 13:55:32.587  3234  3289 D BluetoothAdapterState: Stopping profile services that were post enabled
,06-30 13:55:32.587  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
06-30 13:55:32.587  3234  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 13:55:32.587  3234  3234 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
06-30 13:55:32.587  3234  3234 D A2dpService: Received stop request...Stopping profile...
06-30 13:55:32.587  3234  3234 V Avrcp   : doQuit
,06-30 13:55:32.587  3234  3480 D A2dpStateMachine: Exit Disconnected: -1
,06-30 13:55:32.597  3234  3234 D Avrcp   : Unregistering previous receiver
,06-30 13:55:32.597  1284  1284 I wpa_supplicant: Blacklist: Clear (all) 
,06-30 13:55:32.597  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:32.597   754  1246 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
06-30 13:55:32.597   754  1246 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
06-30 13:55:32.597   754   754 D BluetoothA2dp: Proxy object disconnected
06-30 13:55:32.597   754   754 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,06-30 13:55:32.597  1189  1189 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,06-30 13:55:32.597  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte
06-30 13:55:32.597  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=2
06-30 13:55:32.597  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_2 mContentDescriptionPhoneSignal = Two bars of phone signal
,06-30 13:55:32.597  3234  3234 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
06-30 13:55:32.597  3234  3234 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,06-30 13:55:32.597  3234  3234 D HidService: Received stop request...Stopping profile...
,06-30 13:55:32.597  3234  3234 D HidService: Stopping Bluetooth HidService
06-30 13:55:32.597  3234  3234 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
06-30 13:55:32.597  3234  3234 W bt-btif : cleanup: HH disabling or disabled already, status = 0
06-30 13:55:32.597  3234  3234 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
06-30 13:55:32.597  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:32.597  3234  3234 D HealthService: Received stop request...Stopping profile...
06-30 13:55:32.597  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:32.597  3387  3387 D BluetoothA2dp: Proxy object disconnected
06-30 13:55:32.597  4615  4615 D BluetoothA2dp: Proxy object disconnected
06-30 13:55:32.597  4615  4615 D A2dpProfile: Bluetooth service disconnected
,06-30 13:55:32.597  4615  4615 D BluetoothInputDevice: Proxy object disconnected
06-30 13:55:32.597  4615  4615 D HidProfile: Bluetooth service disconnected
,06-30 13:55:32.607  3234  3234 D PanService: Received stop request...Stopping profile...
06-30 13:55:32.607  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:32.607  3234  3234 D BluetoothMapService: Received stop request...Stopping profile...
,06-30 13:55:32.607   754   754 D BluetoothPan: BluetoothPAN Proxy object disconnected
06-30 13:55:32.607  4615  4615 D BluetoothPan: BluetoothPAN Proxy object disconnected
06-30 13:55:32.607  4615  4615 D PanProfile: Bluetooth service disconnected
,06-30 13:55:32.607  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
06-30 13:55:32.607  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:32.607  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
06-30 13:55:32.607  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:32.607  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
06-30 13:55:32.607  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:32.607  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:32.607  1189  1189 D StatusBar.NetworkController: applyOpen
06-30 13:55:32.607  3234  3234 D SapService: Received stop request...Stopping profile...
06-30 13:55:32.607  3234  3234 D SapService: Stopping Bluetooth SapService
06-30 13:55:32.607  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
06-30 13:55:32.607  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
06-30 13:55:32.607  3234  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 13:55:32.607  3234  3234 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
06-30 13:55:32.607  3234  3234 D BluetoothA2dp: Proxy object disconnected
06-30 13:55:32.607  3234  3234 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
06-30 13:55:32.607  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:32.607  1189  1189 D StatusBar.NetworkController: applyOpen
06-30 13:55:32.607   754  1652 I AudioService: getStreamVolume 3 index 70
06-30 13:55:32.607  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:32.607  4615  4615 D BluetoothMap: Proxy object disconnected
,06-30 13:55:32.607  3234  3481 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
06-30 13:55:32.617  3234  3234 I GKI_LINUX: GKI_exit_task 2 done
06-30 13:55:32.617  3234  3234 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
06-30 13:55:32.617  3234  3234 V Avrcp   : cleanup
06-30 13:55:32.617  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,06-30 13:55:32.617  3234  3234 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
06-30 13:55:32.617  3234  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:32.617  3234  3234 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:32.617  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
06-30 13:55:32.617  3234  3234 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
06-30 13:55:32.617  3234  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:32.617  3234  3234 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:32.617  3234  3234 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
06-30 13:55:32.617  3234  3234 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
06-30 13:55:32.617  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
06-30 13:55:32.617  3234  3234 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
06-30 13:55:32.617  3234  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:32.617  3234  3234 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:32.617  3234  3234 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
06-30 13:55:32.617  3234  3234 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,06-30 13:55:32.617  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
06-30 13:55:32.617  3234  3234 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
06-30 13:55:32.617  3234  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 13:55:32.617  3234  3234 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
06-30 13:55:32.617  1189  1189 D StatusBar.NetworkController: applyOpen
06-30 13:55:32.617  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
06-30 13:55:32.617  3234  3234 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
06-30 13:55:32.617  3234  3234 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
06-30 13:55:32.617  3234  3289 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
06-30 13:55:32.617  3234  3234 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
06-30 13:55:32.617  3234  3289 D BluetoothAdapterProperties: Setting state to 10
06-30 13:55:32.617  3234  3289 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
06-30 13:55:32.617  3234  3289 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-30 13:55:32.617  3234  3289 D BluetoothAdapterService: updateAdapterState state is 10
,06-30 13:55:32.617  3234  3289 D BluetoothAdapterService: Autoconnection is available 
06-30 13:55:32.617  3234  3289 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
06-30 13:55:32.617  3234  3289 I BluetoothAdapterState: Entering OffState
06-30 13:55:32.617  7568  7568 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:32.617  7568  7568 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:32.617  4615  4615 D MapProfile: Bluetooth service disconnected
,06-30 13:55:32.617  3387  3397 D BluetoothA2dp: onBluetoothStateChange: up=false
,06-30 13:55:32.617  4615  4615 D Bluetoothsap: BluetoothSAP Proxy object disconnected
06-30 13:55:32.617  4615  4615 D SapProfile: Bluetooth service disconnected
,06-30 13:55:32.627  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 13:55:32.627  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:32.627  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,06-30 13:55:32.627  4615  4634 D Bluetoothsap: onBluetoothStateChange: up=false
06-30 13:55:32.627  4615  4634 D Bluetoothsap: Unbinding service...
,06-30 13:55:32.627  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 13:55:32.627  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:32.627  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,06-30 13:55:32.627  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:32.627  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:32.627  3234  3246 D BluetoothA2dp: onBluetoothStateChange: up=false
06-30 13:55:32.627  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,06-30 13:55:32.627  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:32.637  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,06-30 13:55:32.637  1284  1284 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,06-30 13:55:32.637  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:32.637  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,06-30 13:55:32.637  1189  1189 D StatusBar.NetworkController: applyOpen
06-30 13:55:32.637  1189  1189 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:32.637  1189  1189 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
06-30 13:55:32.637  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,06-30 13:55:32.637  1189  1189 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:32.637   754  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,06-30 13:55:32.637  1189  1189 D HotspotTile: onReceive : 0, 0
06-30 13:55:32.637  4615  4627 D BluetoothMap: onBluetoothStateChange: up=false
06-30 13:55:32.637  1189  1189 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,06-30 13:55:32.637  4615  6107 D BluetoothA2dp: onBluetoothStateChange: up=false
,06-30 13:55:32.647  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
06-30 13:55:32.647  4615  4627 D BluetoothPbap: onBluetoothStateChange: up=false
,06-30 13:55:32.647  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
06-30 13:55:32.647  1189  1189 I PhoneStatusBar: Icon Only
06-30 13:55:32.647  1189  1189 I StatusBar: Icon Only
,06-30 13:55:32.647  1189  1189 D PanelView: There is/are notification(s) 
,06-30 13:55:32.647  4615  6107 D BluetoothInputDevice: onBluetoothStateChange: up=false
,06-30 13:55:32.647  1189  1189 D PanelView: There is/are notification(s) 
,06-30 13:55:32.647  1284  1284 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,06-30 13:55:32.647  1284  1284 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,06-30 13:55:32.647  1284  1284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
06-30 13:55:32.647  1284  1284 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,06-30 13:55:32.657   754   754 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:32.657   754   754 I InputMethodManagerService: [BT Setting State] State =10
06-30 13:55:32.657   754   754 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,06-30 13:55:32.657  1757  1757 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,06-30 13:55:32.657  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,06-30 13:55:32.667  1189  1189 D QSpanel : label top:23
06-30 13:55:32.667  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 13:55:32.667  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 13:55:32.667  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 13:55:32.667  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 13:55:32.667  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 13:55:32.667  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 13:55:32.667  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 13:55:32.667  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 13:55:32.667  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 13:55:32.667  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 13:55:32.667  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
06-30 13:55:32.667  4615  4615 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:32.667  1189  1189 D BluetoothTile:  onBluetoothPairedDevicesChanged:
06-30 13:55:32.667  1189  1189 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:32.667  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
06-30 13:55:32.667  7568  7568 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
,06-30 13:55:32.667  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
06-30 13:55:32.677   754  1357 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
06-30 13:55:32.677   754  1476 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
06-30 13:55:32.677  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
06-30 13:55:32.677  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
06-30 13:55:32.677  1189  1189 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,06-30 13:55:32.677  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,06-30 13:55:32.677  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,06-30 13:55:32.677  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,06-30 13:55:32.677  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,06-30 13:55:32.677  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,06-30 13:55:32.687  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,06-30 13:55:32.687  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
,06-30 13:55:32.687  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
06-30 13:55:32.687  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 13:55:32.687  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 13:55:32.687  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 13:55:32.687  1189  1189 D QSpanel : label top:23
06-30 13:55:32.687  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 13:55:32.687  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 13:55:32.687  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 13:55:32.687  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 13:55:32.687  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 13:55:32.687  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 13:55:32.687  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,06-30 13:55:32.687  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,06-30 13:55:32.727  1284  1284 I wpa_supplicant: Blacklist: Clear (all) 
,06-30 13:55:32.897  1284  1284 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,06-30 13:55:32.897   754  1152 D Tethering: InitialState.processMessage what=4
06-30 13:55:32.897   754  1152 E Tethering: No numeric data
06-30 13:55:32.897   754  1152 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
06-30 13:55:32.897   754  1146 V NetworkStats: performPollLocked(flags=0x1)
06-30 13:55:32.897   754  1146 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:32.897   754  1146 D NetworkStatsFactory: UpdateStatsForKnox
06-30 13:55:32.897   754  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:32.897  1189  1189 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
06-30 13:55:32.897  1189  1189 D HotspotTile: updateTetherState():false, false
,06-30 13:55:32.897   754  1146 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:32.897   754  1146 V NetworkStats: performPollLocked() took 2ms
06-30 13:55:32.897   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:32.897   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 13:55:32.907   754  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
06-30 13:55:32.907   754  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,06-30 13:55:32.907   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:32.907  1997  1997 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 13:55:32.907   754  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,06-30 13:55:32.907  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
06-30 13:55:32.907  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:55:32.907  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,06-30 13:55:32.907  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:55:32.907  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
06-30 13:55:32.917  1189  1189 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-30 13:55:32.917  1189  1189 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,06-30 13:55:32.917  1189  1189 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:32.917  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,06-30 13:55:32.917  1189  1189 D HotspotTile: onReceive : 1, 0
,06-30 13:55:32.917  4615  4615 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:32.937  1189  1189 D QSpanel : label top:23
,06-30 13:55:32.937  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 13:55:32.937  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 13:55:32.937  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 13:55:32.937  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 13:55:32.937  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
,06-30 13:55:32.937  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 13:55:32.937  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 13:55:32.937  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 13:55:32.937  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 13:55:32.937  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 13:55:32.947  7568  7568 D StrictMode: StrictMode policy violation; ~duration=215 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 13:55:32.947  7568  7568 D StrictMode: StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 13:55:32.947  7568  7568 D StrictMode: StrictMode policy violation; ~duration=159 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.io.File.doAccess(File.java:283)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.io.File.exists(File.java:363)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:5938)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 13:55:32.947  7568  7568 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 13:55:32.947  7568  7568 D StrictMode: StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 13:55:32.947   754  1584 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
06-30 13:55:32.947  7568  7568 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.r.k.c(PG:1187)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.r.k.a(PG:2107)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.r.v.a(PG:1206)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.r.y.a(PG:2233)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.r.e.b(PG:170)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.r.e.b(PG:13188)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 13:55:32.947  7568  7568 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.r.k.c(PG:1187)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.r.k.b(PG:14147)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.r.k.c(PG:583)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.r.v.a(PG:1206)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.r.y.a(PG:2233)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.r.e.b(PG:170)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.r.e.b(PG:13188)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 13:55:32.947  7568  7568 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.io.File.doAccess(File.java:283)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.io.File.exists(File.java:363)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 13:55:32.947  7568  7568 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 13:55:32.947   754  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:32.947   754  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:32.947   754  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:32.947   754  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:32.977  7568  7598 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,06-30 13:55:32.987  7606  7606 E Zygote  : MountEmulatedStorage()
06-30 13:55:32.987  7606  7606 I libpersona: KNOX_SDCARD checking this for 10038
06-30 13:55:32.987  7606  7606 E Zygote  : v2
06-30 13:55:32.987  7606  7606 I libpersona: KNOX_SDCARD not a persona
06-30 13:55:32.997   754  1584 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7606 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
06-30 13:55:32.997   754  1584 I ActivityManager: Killing 6703:com.android.calendar/u0a172 (adj 15): emptyCount ##41
,06-30 13:55:33.027  7606  7606 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:33.027  7606  7606 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 13:55:33.027  7606  7606 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 13:55:33.047  7606  7606 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:33.047   754  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:33.057  7606  7606 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:33.057   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:33.057   754   754 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:33.057   754  1004 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:33.057   754  1004 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:33.057   754   754 I ApplicationPolicy: updateDataUsageMap
,06-30 13:55:33.067   754  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,06-30 13:55:33.067   754  1570 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:33.067   754  1153 D SmartBondingService: getSBEnabled() enabled =false
06-30 13:55:33.067   754  1153 D SmartBondingService: getSBEnabled() enabled =false
,06-30 13:55:33.067   754  1153 D SmartBondingService: getSBEnabled() enabled =false
,06-30 13:55:33.067  1490  1490 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,06-30 13:55:33.077  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:55:33.077   754   781 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:33.077  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:55:33.107   754  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,06-30 13:55:33.187   754  1553 I art     : Explicit concurrent mark sweep GC freed 196378(11MB) AllocSpace objects, 71(15MB) LOS objects, 30% free, 36MB/52MB, paused 1.411ms total 132.525ms
,06-30 13:55:33.187   754  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,06-30 13:55:33.207  7606  7606 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,06-30 13:55:33.217  7606  7606 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,06-30 13:55:33.227  1997  2069 I art     : Explicit concurrent mark sweep GC freed 17706(1042KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 19MB/31MB, paused 481us total 27.858ms
,06-30 13:55:33.357  7606  7606 I VlingoApplication: VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,06-30 13:55:33.387  7447  7506 I WifiManager: packageName : com.test.thalitest
,06-30 13:55:33.387   754   783 D SecContentProvider: uri = 18 selection = isWifiEnabled
06-30 13:55:33.387   754   783 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
06-30 13:55:33.387   754   783 D SecContentProvider2: mCursor = null
,06-30 13:55:33.387   754   783 D WifiService: setWifiEnabled: true pid=7447, uid=10079
,06-30 13:55:33.387   754   783 W ActivityManager: Permission Denial: getCurrentUser() from pid=7447, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
06-30 13:55:33.387   754   783 W WifiService: Failed getting userId using ActivityManagerNative
06-30 13:55:33.387   754   783 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7447, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
06-30 13:55:33.387   754   783 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
06-30 13:55:33.387   754   783 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
06-30 13:55:33.387   754   783 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
06-30 13:55:33.387   754   783 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
06-30 13:55:33.387   754   783 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,06-30 13:55:33.387   754   783 D SettingsProvider: name = wifi_on
,06-30 13:55:33.397   754  1149 E WifiHW  : ##################### set firmware type 0 #####################
,06-30 13:55:33.397   295  1063 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
06-30 13:55:33.397   295  1063 I WifiHW  : module is semco
06-30 13:55:33.397   295  1063 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
06-30 13:55:33.397   295  1063 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
06-30 13:55:33.397   295  1063 E WifiHW  : TEMP_FAILURE_RETRY complete
06-30 13:55:33.397   295  1063 D SoftapController: Softap fwReload - Ok
,06-30 13:55:33.397   295  1063 D CommandListener: Setting iface cfg
06-30 13:55:33.397   295  1063 D CommandListener: Trying to bring down wlan0
,06-30 13:55:33.397   295  1063 D CommandListener: Clearing all IP addresses on wlan0
,06-30 13:55:33.397   754  1149 E WifiHW  : supplicant_name : p2p_supplicant
,06-30 13:55:33.437  7623  7623 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
06-30 13:55:33.437  7623  7623 I wpa_supplicant: Successfully initialized wpa_supplicant
,06-30 13:55:33.437  7623  7623 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
06-30 13:55:33.437  7623  7623 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,06-30 13:55:33.437   359   359 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7623
06-30 13:55:33.437   359   359 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
06-30 13:55:33.437  7623  7623 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
06-30 13:55:33.437  7623  7623 I wpa_supplicant: ssSupport state is = 1
,06-30 13:55:33.437  7623  7623 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,06-30 13:55:33.437  7623  7623 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,06-30 13:55:33.437   359   359 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7623
06-30 13:55:33.437   359   359 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,06-30 13:55:33.497  7606  7606 E BluetoothHeadset: BTStateChangeCB is registed
,06-30 13:55:33.497   754  1144 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,06-30 13:55:33.497  7606  7606 E BluetoothHeadset: BluetoothHeadset service is binded
,06-30 13:55:33.497   754  1149 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,06-30 13:55:33.497   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:33.507  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 13:55:33.507  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:33.507  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
06-30 13:55:33.507  1189  1189 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-30 13:55:33.507  1189  1189 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
06-30 13:55:33.507  1189  1189 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:33.507  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
06-30 13:55:33.507  1189  1189 D HotspotTile: onReceive : 2, 0
,06-30 13:55:33.507   754  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
06-30 13:55:33.507  4615  4615 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:33.507   754  1697 I ActivityManager: Killing 6735:flipboard.app/u0a125 (adj 15): emptyCount ##41
,06-30 13:55:33.507  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:55:33.507  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:55:33.507  4615  4615 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,06-30 13:55:33.517  4615  4615 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,06-30 13:55:33.517   754  1246 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:33.517  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
06-30 13:55:33.517   754  1343 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
06-30 13:55:33.517  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
06-30 13:55:33.517  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
06-30 13:55:33.517  4615  4615 I NearbySettings: MountReceiver.onReceive - Set preference state off
,06-30 13:55:33.517  4615  4727 V NearbySettings: MountReceiver.mPrefHandler - 7002
,06-30 13:55:33.527  1189  1189 D QSpanel : label top:23
06-30 13:55:33.527  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 13:55:33.527  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 13:55:33.527  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 13:55:33.527  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 13:55:33.527  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 13:55:33.527  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 13:55:33.527  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 13:55:33.527  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 13:55:33.527  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 13:55:33.527  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 13:55:33.527   754  1421 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:33.537  5780  5780 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,06-30 13:55:33.547  7606  7606 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,06-30 13:55:33.557  4615  4615 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,06-30 13:55:33.557  4615  4615 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,06-30 13:55:33.557   754  1553 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:33.557  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,06-30 13:55:33.557   754  1697 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
06-30 13:55:33.557  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
06-30 13:55:33.557  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
06-30 13:55:33.557  4615  4615 I NearbySettings: MountReceiver.onReceive - Set preference state off
06-30 13:55:33.557  4615  4727 V NearbySettings: MountReceiver.mPrefHandler - 7002
,06-30 13:55:33.557  6536  6536 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,06-30 13:55:33.567   754  1544 D ActivityManager: startProcessLocked calleePkgName: com.samsung.shareshot, hostingType: broadcast
,06-30 13:55:33.567   754  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:33.567   754  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:33.567   754  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:33.567   754  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:33.607  7631  7631 E Zygote  : MountEmulatedStorage()
,06-30 13:55:33.607  7631  7631 E Zygote  : v2
06-30 13:55:33.607  7631  7631 I libpersona: KNOX_SDCARD checking this for 10192
06-30 13:55:33.607  7631  7631 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:33.607   754  1544 I ActivityManager: Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=7631 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 13:55:33.667  7631  7631 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:33.667  7631  7631 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 13:55:33.667  7631  7631 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:55:33.687  7631  7631 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:33.687  7631  7631 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:33.697  7631  7631 D ResourcesManager: creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,06-30 13:55:33.717  7631  7631 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,06-30 13:55:33.717   359   359 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,06-30 13:55:33.727  7631  7631 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,06-30 13:55:33.727  7631  7631 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,06-30 13:55:33.727  7631  7631 D WifiDirectBR: stopServiceTest : false
,06-30 13:55:33.727   754  1144 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,06-30 13:55:33.727   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:33.727   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:33.727   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:33.727   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:33.767  7647  7647 E Zygote  : MountEmulatedStorage()
06-30 13:55:33.767  7647  7647 E Zygote  : v2
06-30 13:55:33.767  7647  7647 I libpersona: KNOX_SDCARD checking this for 10131
06-30 13:55:33.767  7647  7647 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:33.777   754  1144 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7647 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
06-30 13:55:33.777   754  1144 I ActivityManager: Killing 6311:com.google.android.gm/u0a128 (adj 15): emptyCount ##41
,06-30 13:55:33.817   754  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 13:55:33.817   754  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:55:33.827   754  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:55:33.827   754  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:55:33.837  7647  7647 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:33.837  7647  7647 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 13:55:33.837  7647  7647 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 13:55:33.857  7647  7647 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:33.857  7647  7647 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:33.867  7647  7647 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,06-30 13:55:33.877  7647  7647 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-30 13:55:33.887  3234  3295 D bt_vendor: op for 7
,06-30 13:55:33.967  7623  7623 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,06-30 13:55:33.997  7623  7623 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
06-30 13:55:33.997  7623  7623 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,06-30 13:55:33.997   359   359 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7623
06-30 13:55:33.997   359   359 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
06-30 13:55:33.997  7623  7623 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
06-30 13:55:33.997  7623  7623 I wpa_supplicant: ssSupport state is = 1
,06-30 13:55:33.997  7623  7623 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 13:55:33.997  7623  7623 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 13:55:33.997  7623  7623 E wpa_supplicant: SIM READ ERROR
06-30 13:55:33.997  7623  7623 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 13:55:33.997  7623  7623 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 13:55:33.997  7623  7623 E wpa_supplicant: SIM READ ERROR
06-30 13:55:33.997  7623  7623 I wpa_supplicant: Blacklist: Clear (all) 
,06-30 13:55:33.997  7623  7623 I wpa_supplicant: wpa_default_ap_write_once
06-30 13:55:33.997  7623  7623 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
06-30 13:55:33.997  7623  7623 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 13:55:33.997  7623  7623 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
06-30 13:55:33.997  7623  7623 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 13:55:33.997  7623  7623 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,06-30 13:55:33.997  7623  7623 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-30 13:55:34.047  7647  7647 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,06-30 13:55:34.047  7647  7670 I Babel   : MmsConfig: mnc/mcc: 0/0
06-30 13:55:34.047  7647  7670 I Babel   : MmsConfig.loadMmsSettings
06-30 13:55:34.047  7647  7670 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
06-30 13:55:34.047  7647  7670 I Babel   : MmsConfig.loadFromDatabase
,06-30 13:55:34.057  7647  7670 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,06-30 13:55:34.057  7647  7670 I Babel   : MmsConfig.loadFromResources
,06-30 13:55:34.067  7647  7670 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,06-30 13:55:34.067  7647  7670 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,06-30 13:55:34.067   754  1246 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,06-30 13:55:34.067  7647  7647 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 13:55:34.097  7647  7647 I Babel_StickerModule: App launched.
,06-30 13:55:34.097  7647  7647 I Babel_StickerModule: Trying first logged in account.
,06-30 13:55:34.107  7647  7647 W Babel_StickerModule: Unable to load, account not configured.
,06-30 13:55:34.107  7631  7631 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,06-30 13:55:34.117  4615  4615 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,06-30 13:55:34.127  4615  4615 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,06-30 13:55:34.127   754   783 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:34.127  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,06-30 13:55:34.127   754  1697 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
06-30 13:55:34.127  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
06-30 13:55:34.127  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,06-30 13:55:34.127  4615  4615 I NearbySettings: MountReceiver.onReceive - Set preference state off
06-30 13:55:34.127  4615  4727 V NearbySettings: MountReceiver.mPrefHandler - 7002
,06-30 13:55:34.127   308   735 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,06-30 13:55:34.127   308   735 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
06-30 13:55:34.127   308   735 W QCamera2Factory: getCameraInfo: X
,06-30 13:55:34.127   754  1421 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:34.127   308   981 W QCamera2Factory: getCameraInfo: E, camera_id = 1
,06-30 13:55:34.127   308   981 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
06-30 13:55:34.127   308   981 W QCamera2HWI: __dbg: info->orientation : 270 rc = 0
06-30 13:55:34.127   308   981 W QCamera2Factory: getCameraInfo: X
,06-30 13:55:34.137  5780  5780 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,06-30 13:55:34.147  5780  5780 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,06-30 13:55:34.147  7647  7647 W AudioCapabilities: Unsupported mime audio/evrc
,06-30 13:55:34.147   754  1320 E Watchdog: !@Sync 10
,06-30 13:55:34.147  7647  7647 W AudioCapabilities: Unsupported mime audio/qcelp
,06-30 13:55:34.157  7647  7647 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-30 13:55:34.157   754  1144 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:34.157  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,06-30 13:55:34.157  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,06-30 13:55:34.157  7516  7516 D SecurityLogAgent: StateMachine : Current State = 1
,06-30 13:55:34.157  7516  7516 D SecurityLogAgent: StateMachine : Changed Current State = 1
,06-30 13:55:34.167  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,06-30 13:55:34.167   754  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
06-30 13:55:34.167   754  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@6d0770e, r.packageName :com.android.settings
,06-30 13:55:34.177  1627  1627 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,06-30 13:55:34.177  4615  4615 D DockEventReceiver: finishStartingService: stopping service
,06-30 13:55:34.177  4615  4615 D BluetoothNotiBroadcastReceiver: onReceive
,06-30 13:55:34.177  7647  7647 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,06-30 13:55:34.177  7647  7647 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,06-30 13:55:34.187  7647  7647 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,06-30 13:55:34.187  5780  5780 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,06-30 13:55:34.187   754  1343 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:34.187  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State = 1
06-30 13:55:34.197  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,06-30 13:55:34.197  7516  7516 D SecurityLogAgent: StateMachine : Current State = 1
,06-30 13:55:34.197  7516  7516 D SecurityLogAgent: StateMachine : Changed Current State = 1
06-30 13:55:34.197  7647  7647 W AudioCapabilities: Unsupported mime audio/x-ima
,06-30 13:55:34.197  7647  7647 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,06-30 13:55:34.197  7647  7647 W AudioCapabilities: Unsupported mime audio/qcelp
,06-30 13:55:34.197  7647  7647 W AudioCapabilities: Unsupported mime audio/evrc
,06-30 13:55:34.207  7135  7135 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
06-30 13:55:34.207  7135  7135 I PCWCLIENTTRACE_PushUtil: sales region : global
06-30 13:55:34.207  7135  7135 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
06-30 13:55:34.207  7135  7135 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:34.207  7135  7135 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,06-30 13:55:34.207  7647  7647 W VideoCapabilities: Unsupported mime video/wvc1
,06-30 13:55:34.207  7647  7647 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,06-30 13:55:34.217  5271  5271 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,06-30 13:55:34.217   754  1246 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,06-30 13:55:34.217   754  1246 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:34.217   754  1246 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:34.217   754  1246 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:34.217   754  1246 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:34.227  7647  7647 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,06-30 13:55:34.227  7647  7647 W VideoCapabilities: Unsupported mime video/wvc1
,06-30 13:55:34.227  7647  7647 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,06-30 13:55:34.227  7647  7647 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,06-30 13:55:34.227  7647  7647 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,06-30 13:55:34.237  7647  7647 W VideoCapabilities: Unsupported mime video/mp43
,06-30 13:55:34.237  7647  7647 W VideoCapabilities: Unsupported mime video/sorenson
,06-30 13:55:34.247  7647  7647 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,06-30 13:55:34.257  7647  7647 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,06-30 13:55:34.267  7678  7678 E Zygote  : MountEmulatedStorage()
06-30 13:55:34.267  7678  7678 E Zygote  : v2
06-30 13:55:34.267  7678  7678 I libpersona: KNOX_SDCARD checking this for 10004
06-30 13:55:34.267  7678  7678 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:34.277   754  1246 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7678 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 13:55:34.297  7678  7678 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:34.297  7678  7678 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 13:55:34.297  7678  7678 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:55:34.327  7678  7678 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:34.327  7678  7678 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:34.327   754  1421 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,06-30 13:55:34.337  7678  7678 D ResourcesManager: creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,06-30 13:55:34.357  3234  3425 D bt_upio : ..proc_btwrite_timeout..
,06-30 13:55:34.357   754  1476 I ActivityManager: Killing 6128:com.sec.android.app.music:service/u0a49 (adj 15): emptyCount ##41
,06-30 13:55:34.397  7447  7506 I WifiManager: packageName : com.test.thalitest
,06-30 13:55:34.397   754  1553 D SecContentProvider: uri = 18 selection = isWifiEnabled
06-30 13:55:34.397   754  1553 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
06-30 13:55:34.397   754  1553 D SecContentProvider2: mCursor = null
,06-30 13:55:34.397   754  1553 D WifiService: setWifiEnabled: false pid=7447, uid=10079
06-30 13:55:34.397   754  1553 D SettingsProvider: name = wifi_on
,06-30 13:55:34.417   754  1357 I ActivityManager: Killing 6170:com.sec.android.app.myfiles/u0a56 (adj 15): emptyCount ##41
,06-30 13:55:34.417   754  1357 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,06-30 13:55:34.417   754  1357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:34.417   754  1357 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:34.417   754  1357 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:34.417   754  1357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:34.497   302   302 E SMD     : DCD ON
,06-30 13:55:34.547   754  1357 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7700 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 13:55:34.547  7700  7700 E Zygote  : MountEmulatedStorage()
06-30 13:55:34.547  7700  7700 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:55:34.547  7700  7700 E Zygote  : v2
06-30 13:55:34.547  7700  7700 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:34.577  7700  7700 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:34.577  7700  7700 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 13:55:34.577  7700  7700 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:55:34.597  7700  7700 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:34.597  7700  7700 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:34.607  7700  7700 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,06-30 13:55:34.637  7700  7700 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,06-30 13:55:34.657   754  1152 E Tethering: No numeric data
,06-30 13:55:34.657   754  1152 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,06-30 13:55:34.657  1189  1189 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
06-30 13:55:34.657  1189  1189 D HotspotTile: updateTetherState():false, false
06-30 13:55:34.657   754  1146 V NetworkStats: performPollLocked(flags=0x1)
,06-30 13:55:34.657   754  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 13:55:34.657  7700  7700 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
06-30 13:55:34.657   754  1146 D NetworkStatsFactory: UpdateStatsForKnox
,06-30 13:55:34.657   754  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:34.667   754  1146 V NetworkStats: performPollLocked() took 3ms
,06-30 13:55:34.667   754  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 13:55:34.667   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:34.667   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 13:55:34.717  7623  7623 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,06-30 13:55:34.767  7700  7700 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,06-30 13:55:34.777  7700  7700 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,06-30 13:55:34.777  7700  7700 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:34.777  7700  7700 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,06-30 13:55:34.807  7623  7623 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,06-30 13:55:34.807  7623  7623 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
06-30 13:55:34.807  7623  7623 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
06-30 13:55:34.807   359   359 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7623
06-30 13:55:34.807   359   359 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,06-30 13:55:34.807  7623  7623 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
06-30 13:55:34.807  7623  7623 I wpa_supplicant: ssSupport state is = 1
,06-30 13:55:34.807  7623  7623 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
06-30 13:55:34.807  7623  7623 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
06-30 13:55:34.807   359   359 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7623
06-30 13:55:34.807   359   359 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
06-30 13:55:34.807  7623  7623 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
06-30 13:55:34.807  7623  7623 I wpa_supplicant: ssSupport state is = 1
,06-30 13:55:34.807  7623  7623 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 13:55:34.807  7623  7623 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 13:55:34.807  7623  7623 E wpa_supplicant: SIM READ ERROR
06-30 13:55:34.807  7623  7623 I wpa_supplicant: wpa_default_ap_write_once
06-30 13:55:34.807  7623  7623 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
06-30 13:55:34.807  7623  7623 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-30 13:55:34.847   754   783 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,06-30 13:55:34.847   754   783 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:34.847   754   783 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:34.847   754   783 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:34.847   754   783 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:34.857  7623  7623 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
06-30 13:55:34.857  7623  7623 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,06-30 13:55:34.887  7717  7717 E Zygote  : MountEmulatedStorage()
,06-30 13:55:34.887  7717  7717 E Zygote  : v2
06-30 13:55:34.887  7717  7717 I libpersona: KNOX_SDCARD checking this for 10014
06-30 13:55:34.887  7717  7717 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:34.897   754   783 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7717 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 13:55:34.907  7623  7623 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
06-30 13:55:34.907  7623  7623 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
06-30 13:55:34.907  7623  7623 I wpa_supplicant: Skip scan - bUseNetwork false
,06-30 13:55:34.907   754  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
06-30 13:55:34.907   336   336 I art     : Explicit concurrent mark sweep GC freed 8748(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 294us total 12.555ms
,06-30 13:55:34.907   754  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,06-30 13:55:34.907  7623  7623 I wpa_supplicant: HOTSPOT20_ENABLE called
06-30 13:55:34.907  7623  7623 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 13:55:34.907  7623  7623 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 13:55:34.907  7623  7623 E wpa_supplicant: SIM READ ERROR
06-30 13:55:34.907  7623  7623 I wpa_supplicant: Blacklist: Clear (all) 
,06-30 13:55:34.917   336   336 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 267us total 9.696ms
,06-30 13:55:34.917  7623  7623 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,06-30 13:55:34.927   336   336 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 266us total 9.295ms
,06-30 13:55:34.927  7623  7623 I wpa_supplicant: Skip scan - bUseNetwork false
,06-30 13:55:34.927   754  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,06-30 13:55:34.927   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:34.927   754  1149 D WifiConfigStore: Loading config and enabling all networks 
,06-30 13:55:34.937   754  1149 E WifiConfigStore: Not a HS20
,06-30 13:55:34.937   754  1149 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,06-30 13:55:34.937   754  1149 D WifiNative-HAL: callSECApiInt - ID [65]
,06-30 13:55:34.937  7717  7717 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:34.937  7717  7717 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 13:55:34.947  4615  4615 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:34.947  7717  7717 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
06-30 13:55:34.947   754  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,06-30 13:55:34.947  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 13:55:34.947  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:34.947  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
06-30 13:55:34.947  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:34.947  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:34.947  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:34.947  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:34.947  7447  7447 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:55:34.947  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:34.947  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:34.947  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:34.947  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:34.947  1189  1189 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-30 13:55:34.947  1189  1189 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
06-30 13:55:34.947  1189  1189 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-30 13:55:34.947  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,06-30 13:55:34.947  1189  1189 D HotspotTile: onReceive : 3, 0
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:34.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 13:55:34.947  7447  7447 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:55:34.947   754  1149 D WifiNative-HAL: callSECApiBoolean - ID [13]
06-30 13:55:34.947  7623  7623 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
06-30 13:55:34.947  7623  7623 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
06-30 13:55:34.947  7623  7623 I wpa_supplicant: reset timer : RESET_TIMER 0
06-30 13:55:34.947  7623  7623 I wpa_supplicant: P2P: Current p2p state = IDLE
06-30 13:55:34.947  7623  7623 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
06-30 13:55:34.947  7623  7623 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
06-30 13:55:34.947  7623  7623 I wpa_supplicant: First Scan Start
,06-30 13:55:34.947  7647  7647 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 13:55:34.957  7623  7623 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,06-30 13:55:34.957   754  1149 D WifiNative-HAL: Setting external_sim to 1
06-30 13:55:34.957   754  1149 D WifiStateMachine: Setting OUI to DA-A1-19
06-30 13:55:34.957   754  1149 I WifiNative-HAL: startHal
06-30 13:55:34.957   754  1149 E wifi    : getStaticLongField sWifiHalHandle 0x939bd86c
06-30 13:55:34.957   754  1149 D wifi    : halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x501fb2
06-30 13:55:34.957   754  1149 I WifiNative-HAL: Could not start hal
,06-30 13:55:34.967  1189  1189 D QSpanel : label top:23
06-30 13:55:34.967  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 13:55:34.967  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 13:55:34.967  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 13:55:34.967  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 13:55:34.967  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 13:55:34.967  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 13:55:34.967  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 13:55:34.967  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 13:55:34.967  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 13:55:34.967  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 13:55:34.967  7717  7717 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:34.967  7717  7717 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:34.967   754  1149 E native  : do suspend true
,06-30 13:55:34.977   754  1148 D WifiP2pService: P2pDisabledState{ what=131203 }
,06-30 13:55:34.977   295  1063 D CommandListener: Setting iface cfg
06-30 13:55:34.977   295  1063 D CommandListener: Trying to bring up p2p0
,06-30 13:55:34.977   754  1148 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
06-30 13:55:34.977   754  1148 D WifiP2pService: P2pEnablingState
06-30 13:55:34.977   754  1148 D WifiP2pService: P2pEnablingState{ what=147457 }
06-30 13:55:34.977   754  1148 D WifiP2pService: P2p socket connection successful
,06-30 13:55:34.977   754  1148 D WifiP2pService: P2pEnabledState
,06-30 13:55:34.977   754  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,06-30 13:55:34.977   754   754 D WifiScanningService: SCAN_AVAILABLE : 3
06-30 13:55:34.977   754   754 D RttService: SCAN_AVAILABLE : 3
06-30 13:55:34.977   754  1167 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:34.977   754  1167 I WifiNative-HAL: startHal
06-30 13:55:34.977   754  1167 E wifi    : getStaticLongField sWifiHalHandle 0x9ae6899c
06-30 13:55:34.977   754  1167 D wifi    : halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x801f7e
06-30 13:55:34.977   754  1167 I WifiNative-HAL: Could not start hal
06-30 13:55:34.977   754  1167 E WifiScanningService: could not start HAL
06-30 13:55:34.977   754  1168 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,06-30 13:55:34.977   754  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,06-30 13:55:34.977   754  1151 E ConnectivityService: updateNetworkInfo()
06-30 13:55:34.987   754  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,06-30 13:55:34.987   754   754 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
06-30 13:55:34.987   754  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
06-30 13:55:34.987   754  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
06-30 13:55:34.987   754   754 D WifiScanningService: SCAN_AVAILABLE : 1
06-30 13:55:34.987   754   754 D RttService: SCAN_AVAILABLE : 1
,06-30 13:55:34.987   754  1167 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:34.987   754  1045 D WifiDisplayController: disconnect
06-30 13:55:34.987   754  1168 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:34.987   754  1045 D WifiDisplayController: updateConnection
06-30 13:55:34.987   754  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
06-30 13:55:34.987   754  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:34.987   754  1045 D WifiDisplayAdapter: onP2pDisconnected
06-30 13:55:34.987   754  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
06-30 13:55:34.987   754  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
06-30 13:55:34.987   754  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-30 13:55:34.987   754  1148 D WifiNative-HAL: p2pGetDeviceAddress
,06-30 13:55:34.987  1189  1189 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
06-30 13:55:34.987   754  1148 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:d7:fd:2b
06-30 13:55:34.987   754  1571 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
06-30 13:55:34.987  1189  1189 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,06-30 13:55:34.987   754  1148 D WifiP2pService: DeviceAddress: ea:fd:2b
06-30 13:55:34.987   754  1149 D WifiStateMachine: DefaultState::Handling CMD_SEC_STRING_API
06-30 13:55:34.987   754  1050 I PowerManagerService: [PWL] Off : 275s ago
06-30 13:55:34.987   754  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
06-30 13:55:34.987   754  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,06-30 13:55:34.987   754  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=754, ws=null) (elapsedTime=2437)
06-30 13:55:34.987   754  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy Note3
06-30 13:55:34.987   754  1045 D WifiDisplayController:  deviceAddress: ea:50:8b:d7:fd:2b
06-30 13:55:34.987   754  1045 D WifiDisplayController:  primary type: 10-0050F204-5
06-30 13:55:34.987   754  1045 D WifiDisplayController:  secondary type: null
06-30 13:55:34.987   754  1045 D WifiDisplayController:  wps: 0
06-30 13:55:34.987   754  1045 D WifiDisplayController:  grpcapab: 0
06-30 13:55:34.987   754  1045 D WifiDisplayController:  devcapab: 0
06-30 13:55:34.987   754  1045 D WifiDisplayController:  status: 3
06-30 13:55:34.987   754  1045 D WifiDisplayController:  wfdInfo: null
06-30 13:55:34.987   754  1045 D WifiDisplayController:  groupownerAddress: null
06-30 13:55:34.987   754  1045 D WifiDisplayController:  GOdeviceName: null
06-30 13:55:34.987   754  1045 D WifiDisplayController:  interfaceAddress: 
06-30 13:55:34.987   754  1045 D WifiDisplayController:  SConnectInfo : null
,06-30 13:55:34.997  7717  7717 D ResourcesManager: creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,06-30 13:55:34.997   754  1148 D WifiP2pService: sending p2p persistent groups changed broadcast
,06-30 13:55:34.997   754  1148 D WifiP2pService: InactiveState
06-30 13:55:34.997   754  1148 D WifiP2pService: InactiveState{ what=131204 }
,06-30 13:55:34.997   754  1148 D WifiP2pService: P2pEnabledState{ what=131204 }
,06-30 13:55:35.007   754  1148 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,06-30 13:55:35.007   754  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:35.007   754  1045 D WifiDisplayAdapter: onP2pDisconnected
06-30 13:55:35.007   754  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
06-30 13:55:35.007   754  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,06-30 13:55:35.007   754  1151 E ConnectivityService: updateNetworkInfo()
,06-30 13:55:35.007   754  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,06-30 13:55:35.007   754   754 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
06-30 13:55:35.007   754  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
06-30 13:55:35.007   754  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
06-30 13:55:35.007   754  1045 D WifiDisplayController: disconnect
06-30 13:55:35.007   754  1045 D WifiDisplayController: updateConnection
06-30 13:55:35.007   754  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
06-30 13:55:35.007   754  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
06-30 13:55:35.007   754  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-30 13:55:35.007  1189  1189 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
06-30 13:55:35.007   754  1476 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
06-30 13:55:35.007  1189  1189 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,06-30 13:55:35.007   754  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
06-30 13:55:35.007   754  1045 D WifiDisplayAdapter: onP2pDisconnected
06-30 13:55:35.007   754  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
06-30 13:55:35.007   754  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,06-30 13:55:35.007   754  1151 E ConnectivityService: updateNetworkInfo()
06-30 13:55:35.007   754  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,06-30 13:55:35.007   754  1148 D WifiP2pService: P2pDisablingState
06-30 13:55:35.007   754  1148 D WifiP2pService: P2pDisablingState{ what=143376 }
06-30 13:55:35.007   754  1148 D WifiP2pService: DefaultState{ what=143376 }
06-30 13:55:35.007   754  1148 D WifiP2pService: P2pDisablingState{ what=147458 }
,06-30 13:55:35.007   754  1148 D WifiP2pService: p2p socket connection lost
,06-30 13:55:35.007   295  1063 D CommandListener: Clearing all IP addresses on wlan0
,06-30 13:55:35.017  7623  7623 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,06-30 13:55:35.017   754  1148 D WifiP2pService: P2pDisabledState
06-30 13:55:35.017   754   754 I WifiTrafficPoller: evaluateTrafficStatsPolling
,06-30 13:55:35.017   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:35.017  4615  4615 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:35.017  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 13:55:35.017   754  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
06-30 13:55:35.017  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:35.017  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,06-30 13:55:35.017  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:35.017  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:35.017  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:35.017  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:35.017  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:35.017  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:35.017  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:35.017  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 13:55:35.017  7447  7447 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:55:35.017  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
06-30 13:55:35.017  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:35.017  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,06-30 13:55:35.017  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:35.027  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:35.027  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,06-30 13:55:35.027  1189  1189 D StatusBar.NetworkController: applyOpen
06-30 13:55:35.027  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:35.027  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:35.027  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:35.027  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:35.027  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:35.027  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:35.027  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:35.027  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 13:55:35.027  7447  7447 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:55:35.027  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,06-30 13:55:35.027  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:35.027  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:35.027  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:35.027  1189  1189 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-30 13:55:35.027  1189  1189 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,06-30 13:55:35.027  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
06-30 13:55:35.027  1189  1189 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:35.027  1189  1189 D HotspotTile: onReceive : 0, 0
,06-30 13:55:35.027   754  1116 V AlarmManager: waitForAlarm result :4
,06-30 13:55:35.047  1189  1189 D QSpanel : label top:23
,06-30 13:55:35.047  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 13:55:35.047  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 13:55:35.047  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 13:55:35.047  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 13:55:35.047  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
,06-30 13:55:35.047  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 13:55:35.047  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 13:55:35.047  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 13:55:35.047  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 13:55:35.047  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 13:55:35.047  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 13:55:35.047  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:55:35.047  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
06-30 13:55:35.047  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 13:55:35.057   754  1421 I ActivityManager: Killing 6958:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): emptyCount ##41
,06-30 13:55:35.067  7717  7717 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,06-30 13:55:35.077  7717  7717 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,06-30 13:55:35.097  7717  7717 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,06-30 13:55:35.097  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:55:35.097  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:55:35.097   754  1571 I ActivityManager: Killing 6562:com.sec.knox.bridge/1000 (adj 15): emptyCount ##41
,06-30 13:55:35.107  7623  7623 I wpa_supplicant: Blacklist: Clear (all) 
,06-30 13:55:35.107   754  1343 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 13:55:35.107   754  1343 D ActivityManager: caller:android.app.ApplicationThreadProxy@35b02e72, r.packageName :com.google.android.gms
,06-30 13:55:35.117  2217  2217 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,06-30 13:55:35.117  2217  7736 I iu.SyncManager: SYNC; picasa accounts
,06-30 13:55:35.127  2217  7736 I iu.UploadsManager: num queued entries: 0
,06-30 13:55:35.127  2217  7736 I iu.UploadsManager: num updated entries: 0
,06-30 13:55:35.127  2217  7736 I iu.SyncManager: NEXT; no task
,06-30 13:55:35.137  7623  7623 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,06-30 13:55:35.137  7623  7623 I wpa_supplicant: wlan0: State: SCANNING -> DISCONNECTED
06-30 13:55:35.137  7623  7623 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,06-30 13:55:35.137   754  1246 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 13:55:35.137   754  1246 D ActivityManager: caller:android.app.ApplicationThreadProxy@2856b2c3, r.packageName :com.google.android.gms
,06-30 13:55:35.147  2217  2217 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy}
,06-30 13:55:35.147  2217  2217 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy} to Chimera receiver impl com.google.android.gms.kids.account.SystemEventReceiver
06-30 13:55:35.147  2217  2217 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,06-30 13:55:35.147  2217  2217 I Kids    : [GCoreUtils] Current gmscore version, 7571438 is smaller than the required version 8400000
,06-30 13:55:35.157  2602  2602 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,06-30 13:55:35.157  2602  2602 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1467287735171
,06-30 13:55:35.157  2602  2602 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,06-30 13:55:35.157   754   781 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:35.157   754  1476 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:35.157  2602  2602 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,06-30 13:55:35.157  2602  2602 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,06-30 13:55:35.157   754  1246 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.pinboard, hostingType: broadcast
,06-30 13:55:35.157   754  1246 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:35.157   754  1246 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:35.157   754  1246 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:35.157   754  1246 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:35.197  7623  7623 I wpa_supplicant: Blacklist: Clear (all) 
,06-30 13:55:35.247  7739  7739 E Zygote  : MountEmulatedStorage()
06-30 13:55:35.247  7739  7739 E Zygote  : v2
06-30 13:55:35.247  7739  7739 I libpersona: KNOX_SDCARD checking this for 10036
06-30 13:55:35.247  7739  7739 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:35.257   754  1246 I ActivityManager: Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7739 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,06-30 13:55:35.287  7739  7739 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:35.287  7739  7739 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 13:55:35.287  7739  7739 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:55:35.307  7739  7739 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:35.307  7739  7739 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:35.317  7739  7739 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,06-30 13:55:35.317  7739  7739 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 13:55:35.317  7739  7739 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-30 13:55:35.337  7739  7739 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
,06-30 13:55:35.357   754  1343 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:35.357   754  1378 I ActivityManager: Killing 6611:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): emptyCount ##41
,06-30 13:55:35.357   754  1571 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,06-30 13:55:35.357   754  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:35.357   754  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:35.357   754  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:35.357   754  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:35.367  7623  7623 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
06-30 13:55:35.367  7623  7623 I wpa_supplicant: ELOOP: remaining timeout: 0.085361 eloop_data=0xb6588200 user_data=0x0 handler=0xb6f3aaf1
06-30 13:55:35.367  7623  7623 I wpa_supplicant: ELOOP: remaining timeout: 0.122112 eloop_data=0xb6588c00 user_data=0x0 handler=0xb6f3aaf1
06-30 13:55:35.367   754  1152 D Tethering: InitialState.processMessage what=4
06-30 13:55:35.367   754  1152 E Tethering: No numeric data
,06-30 13:55:35.407  7447  7506 D BluetoothAdapter: enable()
,06-30 13:55:35.407  7754  7754 E Zygote  : MountEmulatedStorage()
06-30 13:55:35.407  7754  7754 E Zygote  : v2
06-30 13:55:35.407  7754  7754 I libpersona: KNOX_SDCARD checking this for 10042
06-30 13:55:35.407  7754  7754 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:35.417   754  1571 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7754 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,06-30 13:55:35.457  7754  7754 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:35.457  7754  7754 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 13:55:35.457  7754  7754 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:55:35.457   754  1152 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
06-30 13:55:35.457   754  1476 W ActivityManager: Permission Denial: getCurrentUser() from pid=7447, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,06-30 13:55:35.457   754  1476 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
06-30 13:55:35.457   754  1476 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7447, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
06-30 13:55:35.457   754  1476 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
06-30 13:55:35.457   754  1476 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
06-30 13:55:35.457   754  1476 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
06-30 13:55:35.457   754  1476 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
06-30 13:55:35.457   754  1476 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
06-30 13:55:35.457   754  1476 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
06-30 13:55:35.457   754  1476 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,06-30 13:55:35.457   754  1146 V NetworkStats: performPollLocked(flags=0x1)
06-30 13:55:35.457   754  1146 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:35.457   754  1476 D SettingsProvider: name = bluetooth_on
06-30 13:55:35.457  1189  1189 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
06-30 13:55:35.457  1189  1189 D HotspotTile: updateTetherState():false, false
,06-30 13:55:35.457   754  1146 D NetworkStatsFactory: UpdateStatsForKnox
,06-30 13:55:35.457   754  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:35.457   754  1146 V NetworkStats: performPollLocked() took 4ms
,06-30 13:55:35.457   754  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 13:55:35.467   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:35.467   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 13:55:35.467   754  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,06-30 13:55:35.467   754  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,06-30 13:55:35.467  7647  7647 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:35.467   754  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,06-30 13:55:35.467   754  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,06-30 13:55:35.467   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:35.467  1997  1997 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 13:55:35.477   754  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
06-30 13:55:35.477  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:35.477   754  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,06-30 13:55:35.477  3234  3289 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
06-30 13:55:35.477  3234  3289 D BluetoothAdapterProperties: Setting state to 11
06-30 13:55:35.477  3234  3289 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
06-30 13:55:35.477  3234  3289 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-30 13:55:35.477  3234  3289 D BluetoothAdapterService: updateAdapterState state is 11
,06-30 13:55:35.477  3234  3289 D BluetoothAdapterService: Autoconnection is available 
06-30 13:55:35.477  3234  3289 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
06-30 13:55:35.477  3234  3289 D BtConfig.SecureMode: isSecureModeOn:false
06-30 13:55:35.477  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:55:35.477  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
06-30 13:55:35.477   754   754 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:35.477   754   754 I InputMethodManagerService: [BT Setting State] State =11
06-30 13:55:35.477  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 13:55:35.477  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:35.477  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
06-30 13:55:35.477  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
06-30 13:55:35.477  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
,06-30 13:55:35.477  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
06-30 13:55:35.477  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
06-30 13:55:35.477  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
06-30 13:55:35.477  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
06-30 13:55:35.477  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
06-30 13:55:35.477  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
06-30 13:55:35.477  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
06-30 13:55:35.477  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
06-30 13:55:35.477  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
06-30 13:55:35.477  4615  4615 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
06-30 13:55:35.477  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,06-30 13:55:35.477  1189  1189 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-30 13:55:35.477  1189  1189 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
06-30 13:55:35.477  1189  1189 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:35.477  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
06-30 13:55:35.477  4615  4615 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:35.477   754  1144 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:35.477   754  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@2c5ab679, r.packageName :com.android.bluetooth
,06-30 13:55:35.477  1189  1189 D HotspotTile: onReceive : 1, 0
,06-30 13:55:35.477  1189  1189 D BluetoothTile:  onBluetoothPairedDevicesChanged:
06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
06-30 13:55:35.477  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,06-30 13:55:35.477  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
06-30 13:55:35.477  1189  1189 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:35.477   754  1697 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 13:55:35.477   754  1697 D ActivityManager: caller:android.app.ApplicationThreadProxy@167b81f, r.packageName :com.android.bluetooth
06-30 13:55:35.477  7606  7606 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:35.477  1757  1757 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
06-30 13:55:35.477  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,06-30 13:55:35.487   754  1571 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,06-30 13:55:35.487   754  1476 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,06-30 13:55:35.487  1189  1189 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,06-30 13:55:35.487  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
06-30 13:55:35.487  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 13:55:35.487  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,06-30 13:55:35.487  3234  3234 D HeadsetService: Received start request. Starting profile...
06-30 13:55:35.487  3234  3234 D HeadsetStateMachine: make
06-30 13:55:35.487   754  1652 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 13:55:35.487   754  1652 D ActivityManager: caller:android.app.ApplicationThreadProxy@dc74135, r.packageName :com.android.bluetooth
,06-30 13:55:35.487  3234  3234 E HeadsetStateMachine: # of Max HF connection is 2
,06-30 13:55:35.497  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
06-30 13:55:35.497  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 13:55:35.497  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,06-30 13:55:35.497   754  1378 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 13:55:35.497   754  1378 D ActivityManager: caller:android.app.ApplicationThreadProxy@559b73b, r.packageName :com.android.bluetooth
,06-30 13:55:35.497  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
06-30 13:55:35.497  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-30 13:55:35.497  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,06-30 13:55:35.497   754  1584 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:35.497   754  1584 D ActivityManager: caller:android.app.ApplicationThreadProxy@2737bbb1, r.packageName :com.android.bluetooth
,06-30 13:55:35.497  7754  7754 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:35.497  7754  7754 D ActivityThread: Added TimaKeyStore provider
06-30 13:55:35.497   754   783 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,06-30 13:55:35.497  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
06-30 13:55:35.497  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:35.497  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,06-30 13:55:35.497   754  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:35.497   754  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@b5b61ed, r.packageName :com.android.bluetooth
,06-30 13:55:35.507   754  1421 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
06-30 13:55:35.507  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
06-30 13:55:35.507  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 13:55:35.507  3234  3289 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,06-30 13:55:35.507  3234  3234 I bluedroid: get_profile_interface handsfree
,06-30 13:55:35.507  1189  1189 D QSpanel : label top:23
06-30 13:55:35.507  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 13:55:35.507  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 13:55:35.507  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 13:55:35.507  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 13:55:35.507  1189  1189 D QSpanel : label top:23
06-30 13:55:35.507  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 13:55:35.507  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 13:55:35.507  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 13:55:35.507  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 13:55:35.507  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 13:55:35.507  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 13:55:35.507   754  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 13:55:35.507   754  1544 D ActivityManager: caller:android.app.ApplicationThreadProxy@e992fe9, r.packageName :com.android.bluetooth
,06-30 13:55:35.517  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
06-30 13:55:35.517  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
06-30 13:55:35.517  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
06-30 13:55:35.517  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
06-30 13:55:35.517  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
06-30 13:55:35.517  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
06-30 13:55:35.517  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
06-30 13:55:35.517  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
06-30 13:55:35.517  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
06-30 13:55:35.517  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
06-30 13:55:35.517  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
06-30 13:55:35.517  3234  3234 E DualScoManager: Dual Sco Manager already instantiated
06-30 13:55:35.517  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
06-30 13:55:35.517  3234  3234 I DualScoManager: Set HeadsetServiceHelper
06-30 13:55:35.517  3234  3234 D BluetoothAtMessage: createCMTIContentObservers
06-30 13:55:35.517  3234  3289 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
06-30 13:55:35.517   754  1570 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
06-30 13:55:35.517   754  1570 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 13:55:35.517   754  1570 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 13:55:35.517   754  1570 D SettingsProvider: selectionArgs: false
06-30 13:55:35.517   754  1570 D SettingsProvider: selectionArgs: 1002
06-30 13:55:35.517   754  1570 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 13:55:35.517   754  1570 D SettingsProvider: ret = -1
,06-30 13:55:35.517  3234  7768 D HeadsetStateMachine: Enter Disconnected: -2
,06-30 13:55:35.517  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
06-30 13:55:35.517  3234  7768 E HeadsetStateMachine: set to mRemoteBrsf = 0
,06-30 13:55:35.517  3234  3234 D A2dpService: Received start request. Starting profile...
06-30 13:55:35.517  3234  3234 V Avrcp   : make
06-30 13:55:35.517  3234  3234 V Avrcp   : Avrcp
06-30 13:55:35.517  3234  3234 I bluedroid: get_profile_interface avrcp
,06-30 13:55:35.517  3234  3234 V Avrcp   : start
06-30 13:55:35.517  3234  7768 D HeadsetStateMachine: map size, before remove : 0
06-30 13:55:35.517  3234  7768 D HeadsetStateMachine: map size, after remove: 0
06-30 13:55:35.517  3234  7768 D HeadsetStateMachine: mNextConnectingDevice : null
,06-30 13:55:35.517  7754  7754 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,06-30 13:55:35.517  3234  3234 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,06-30 13:55:35.517  3234  3234 V Avrcp   : ++registerMediaPlayers++
,06-30 13:55:35.517  3234  3234 I Avrcp   : No of Audio players :: 2
06-30 13:55:35.517  3234  3234 I Avrcp   : App Package name is com.google.android.music
,06-30 13:55:35.517  3234  3234 I Avrcp   : App pkg name is Google Play Music
06-30 13:55:35.517  3234  3234 I Avrcp   : Name::Google Play Music
06-30 13:55:35.517  3234  3234 V Avrcp   : MediaPlayerInfo: mPlayerId=1
06-30 13:55:35.517  3234  3234 I Avrcp   : App Package name is com.sec.android.app.music
,06-30 13:55:35.527  3234  3234 I Avrcp   : App pkg name is Music
,06-30 13:55:35.527  3234  3234 I Avrcp   : Name::Music
06-30 13:55:35.527  3234  3234 V Avrcp   : MediaPlayerInfo: mPlayerId=2
06-30 13:55:35.527  3234  3234 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,06-30 13:55:35.527  3234  3234 I Avrcp   : No of Video players :: 1
06-30 13:55:35.527  3234  3234 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,06-30 13:55:35.527  3234  3234 I Avrcp   : Video App pkg name is Video Player
06-30 13:55:35.527  3234  3234 I Avrcp   : Name::Video Player
06-30 13:55:35.527  3234  3234 V Avrcp   : MediaPlayerInfo: mPlayerId=3
06-30 13:55:35.527  3234  3234 I Avrcp   : Add tempPlayer
06-30 13:55:35.527  3234  3234 V Avrcp   : MediaPlayerInfo: mPlayerId=4
06-30 13:55:35.527  3234  3234 I Avrcp   : Total no of players: 4
06-30 13:55:35.527  3234  3234 V Avrcp   : swapping the samsung player with 1st player
06-30 13:55:35.527  3234  3234 I Avrcp   :  Updating now playing list upon AVRCP Start
06-30 13:55:35.527  3234  7771 V Avrcp   : handleMessage, msg=207
06-30 13:55:35.527  3234  7771 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,06-30 13:55:35.527  3234  3234 D A2dpStateMachine: make
,06-30 13:55:35.527  3234  3234 I bluedroid: get_profile_interface a2dp
,06-30 13:55:35.527  3234  7773 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
06-30 13:55:35.527  3234  3234 E bt-btif : warning : media task started media_task_refcnt 1 
,06-30 13:55:35.527  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
06-30 13:55:35.527  3234  7772 D A2dpStateMachine: Enter Disconnected: -2
,06-30 13:55:35.527  3234  3234 D HidService: Received start request. Starting profile...
06-30 13:55:35.527  3234  3234 I bluedroid: get_profile_interface hidhost
06-30 13:55:35.527  3234  3234 D HidService: setHidService(): set to: null
06-30 13:55:35.527  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:35.527  3234  3234 D HealthService: Received start request. Starting profile...
,06-30 13:55:35.527  3234  7771 D BluetoothMediaBrowser: no now playing list
06-30 13:55:35.527  3234  7771 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
06-30 13:55:35.527  3234  7771 D Avrcp   :  checkNowPlayingList start
,06-30 13:55:35.537  3234  3234 I bluedroid: get_profile_interface health
,06-30 13:55:35.537  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
06-30 13:55:35.537  3234  3234 D HeadsetStateMachine: Try to query the phonestate on bind
,06-30 13:55:35.537  1404  1420 I Telecom : BluetoothPhoneService: queryPhoneState
,06-30 13:55:35.537  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
06-30 13:55:35.537  3234  3234 D PanService: Received start request. Starting profile...
06-30 13:55:35.537  3234  3234 D BluetoothPanServiceJni: initializeNative(L110): pan
06-30 13:55:35.537  3234  3234 I bluedroid: get_profile_interface pan
06-30 13:55:35.537  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
06-30 13:55:35.537  3234  3234 D BluetoothMapService: Received start request. Starting profile...
06-30 13:55:35.537   754  1697 D ActivityManager: getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
,06-30 13:55:35.537   754  1697 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:35.537   754  1697 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:35.537   754  1697 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:35.537   754  1697 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:35.547  7754  7754 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,06-30 13:55:35.577  7777  7777 E Zygote  : MountEmulatedStorage()
06-30 13:55:35.577  7777  7777 E Zygote  : v2
06-30 13:55:35.577  7777  7777 I libpersona: KNOX_SDCARD checking this for 10186
06-30 13:55:35.577  7777  7777 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:35.587   754  1697 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=7777 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,06-30 13:55:35.587   754  1246 I ActivityManager: Killing 6865:com.android.defcontainer/u0a7 (adj 15): emptyCount ##41
,06-30 13:55:35.647  7777  7777 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:35.647  7777  7777 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 13:55:35.647  7777  7777 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:55:35.657   754  1570 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:35.657  7168  7168 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,06-30 13:55:35.657  3699  7785 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,06-30 13:55:35.657   754  1544 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:35.657  3699  7785 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,06-30 13:55:35.667  3699  7785 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,06-30 13:55:35.667   754   783 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,06-30 13:55:35.667   754   783 D ActivityManager: caller:android.app.ApplicationThreadProxy@165a05d, r.packageName :com.sec.spp.push
,06-30 13:55:35.667   754  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,06-30 13:55:35.667  3699  7785 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,06-30 13:55:35.677  7777  7777 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:35.677  7777  7777 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:35.677  3699  7785 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,06-30 13:55:35.687  7211  7211 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,06-30 13:55:35.687  7211  7211 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,06-30 13:55:35.687  7211  7211 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
06-30 13:55:35.687  7168  7790 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,06-30 13:55:35.687  7777  7777 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,06-30 13:55:35.687  7211  7211 I SA      : [SLFUCHKMGR] constructor called
,06-30 13:55:35.687  7777  7777 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,06-30 13:55:35.687  7777  7777 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 13:55:35.687  7777  7777 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
06-30 13:55:35.687  7777  7777 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 13:55:35.687  7777  7777 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-30 13:55:35.697  7211  7211 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
06-30 13:55:35.697  7211  7211 I SA      : [OR] == isSIMCardReady false ==
,06-30 13:55:35.707  7211  7211 I SA      : [SCU] == networkStateCheck == false
06-30 13:55:35.707  7211  7211 I SA      : [OR] onReceive END
,06-30 13:55:35.707   754  1144 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,06-30 13:55:35.707   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:35.707   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:35.707   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:35.707   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:35.747  7796  7796 E Zygote  : MountEmulatedStorage()
06-30 13:55:35.747  7796  7796 E Zygote  : v2
06-30 13:55:35.747  7796  7796 I libpersona: KNOX_SDCARD checking this for 10074
06-30 13:55:35.747  7796  7796 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:35.757   754  1144 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7796 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,06-30 13:55:35.787  7796  7796 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:35.787  7796  7796 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 13:55:35.787  7796  7796 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:55:35.797   754  1584 D RCPManagerService: exchangeData() failure , invalid userId
,06-30 13:55:35.807  7796  7796 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:35.817  7796  7796 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:35.827  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:35.827  3234  3234 D HeadsetStateMachine: Proxy object connected
06-30 13:55:35.827  3234  3234 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
06-30 13:55:35.827  3234  3234 D HeadsetPhoneState: sendDeviceDataStateChanged
06-30 13:55:35.827  3234  3234 D HeadsetPhoneState: Signal level : previous=0 curr=2
,06-30 13:55:35.827  3234  3234 D SapService: Received start request. Starting profile...
06-30 13:55:35.827  3234  3234 D BluetoothSAPServiceJni: initializeNative(L209): sap
06-30 13:55:35.827  3234  3234 I bluedroid: get_profile_interface sap
06-30 13:55:35.827  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
06-30 13:55:35.827  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
06-30 13:55:35.827  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:55:35.827  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
06-30 13:55:35.827  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,06-30 13:55:35.827  3234  7768 D HeadsetStateMachine: Disconnected process message: 11
06-30 13:55:35.827  3234  7768 D HeadsetStateMachine: Disconnected process message: 18
06-30 13:55:35.827  3234  7768 D HeadsetStateMachine: Disconnected process message: 10
06-30 13:55:35.827  3234  7768 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-30 13:55:35.827  3234  7768 D HeadsetStateMachine: Disconnected process message: 11
,06-30 13:55:35.827  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
06-30 13:55:35.827  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,06-30 13:55:35.837   754  1343 I ActivityManager: Killing 4243:com.google.android.gms.wearable/u0a15 (adj 15): emptyCount ##41
,06-30 13:55:35.837  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
06-30 13:55:35.837  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
06-30 13:55:35.837  3234  3289 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
06-30 13:55:35.837  3234  3289 I bluedroid: enable
,06-30 13:55:35.837   754  1570 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
06-30 13:55:35.837  3234  3292 E bt-btif : Calling BTA_HhEnable
06-30 13:55:35.837  3234  3292 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
06-30 13:55:35.837  3234  3292 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
06-30 13:55:35.837  3234  3292 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
06-30 13:55:35.837  3234  3292 D BluetoothAdapterProperties: Address is:B0:C5:59:2A:28:2D
06-30 13:55:35.837  3234  3292 E BluetoothServiceJni: populateRssiValuesNative
06-30 13:55:35.837  3234  3292 I bluedroid: getModelRssiValues
06-30 13:55:35.837  3234  3292 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
06-30 13:55:35.837  3234  3292 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,06-30 13:55:35.837  7796  7796 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
06-30 13:55:35.837   754  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:35.837   754  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:35.837   754  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:35.837   754  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:35.847  3234  3295 D bt_vendor: op for 7
,06-30 13:55:35.847  3234  3295 D bt_upio : proc btwrite assertion
,06-30 13:55:35.857  3234  3295 D bt_vendor: op for 7
,06-30 13:55:35.857  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.857  3234  3295 D bt_vendor: op for 7
,06-30 13:55:35.857  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.857  3234  3295 D bt_vendor: op for 7
,06-30 13:55:35.857  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.857  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.857  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.857   754  1246 D RCPManagerService: exchangeData() failure , invalid userId
,06-30 13:55:35.857  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.857  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.857  3234  3295 D bt_vendor: op for 7
,06-30 13:55:35.857  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.867  3234  3295 D bt_vendor: op for 7
,06-30 13:55:35.867  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.867  3234  3295 D bt_vendor: op for 7
,06-30 13:55:35.867  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.877  7817  7817 E Zygote  : MountEmulatedStorage()
06-30 13:55:35.877  7817  7817 I libpersona: KNOX_SDCARD checking this for 10092
06-30 13:55:35.877  7817  7817 E Zygote  : v2
06-30 13:55:35.877  7817  7817 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:35.887   754  1570 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7817 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,06-30 13:55:35.887   754   754 D SettingsProvider: name = bluetooth_name
,06-30 13:55:35.887  3234  3292 D BluetoothAdapterProperties: Name is: Galaxy Note3
,06-30 13:55:35.917  7817  7817 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:35.917  7817  7817 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 13:55:35.917  7817  7817 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,06-30 13:55:35.917   754  1246 D RCPManagerService: exchangeData() failure , invalid userId
,06-30 13:55:35.917  3234  3292 D BluetoothAdapterProperties: Scan Mode:20
06-30 13:55:35.917  3234  3292 D BluetoothAdapterProperties: Discoverable Timeout:120
06-30 13:55:35.917  3234  3292 D BluetoothAdapterProperties: LE Address is:F0:8B:B2:54:50:5A
06-30 13:55:35.917  3234  3292 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
,06-30 13:55:35.917  3234  3292 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
06-30 13:55:35.917  3234  3292 E bt-btif : btif_sock_init: !radio_req && !rfc_init
06-30 13:55:35.917  3234  3292 E bt-btif : JVenable fails
06-30 13:55:35.917  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:55:35.917  3234  3292 D bte_conf: Device ID record 1 : primary
06-30 13:55:35.917  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.917  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:35.917  3234  3292 D bte_conf:   vendorId            = 0075
,06-30 13:55:35.917  3234  3292 D bte_conf:   vendorIdSource      = 0001
06-30 13:55:35.917  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:35.917  3234  3292 D bte_conf:   product             = 0100
06-30 13:55:35.917  3234  3292 D bte_conf:   version             = 0200
06-30 13:55:35.917  3234  3292 D bte_conf:   clientExecutableURL = 
06-30 13:55:35.917  3234  3292 D bte_conf:   serviceDescription  = 
,06-30 13:55:35.917  3234  3292 D bte_conf:   documentationURL    = 
06-30 13:55:35.917  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.917  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:35.917  3234  3292 D bte_conf: bte_load_did_conf no section named DID2.
06-30 13:55:35.917  3234  3292 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
06-30 13:55:35.917  3234  3289 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
06-30 13:55:35.917  3234  3289 D BluetoothAdapterProperties: ScanMode =  20
06-30 13:55:35.917  3234  3289 D BluetoothAdapterProperties: State =  11
06-30 13:55:35.917  3234  3292 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,06-30 13:55:35.917  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.917  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.917   754   781 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
06-30 13:55:35.917  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.917  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:35.917  3234  3289 D BluetoothAdapterProperties: Setting state to 12
06-30 13:55:35.917  3234  3289 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,06-30 13:55:35.917  3234  3292 D BluetoothAdapterProperties: Scan Mode:21
06-30 13:55:35.917  3234  3292 D BluetoothAdapterProperties: Discoverable Timeout:120
06-30 13:55:35.917  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.917  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.917  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.917  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:35.917   754  1378 D SettingsProvider: name = bluetooth_a2dp_sink_mode
06-30 13:55:35.917   754  1378 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 13:55:35.917   754  1378 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 13:55:35.917   754  1378 D SettingsProvider: selectionArgs: false
06-30 13:55:35.917   754  1378 D SettingsProvider: selectionArgs: 1002
06-30 13:55:35.917   754  1378 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 13:55:35.917   754  1378 D SettingsProvider: ret = -1
06-30 13:55:35.917  3234  3289 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-30 13:55:35.917  3234  3289 D BluetoothAdapterService: updateAdapterState state is 12
,06-30 13:55:35.927   754  1652 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:35.927   754  1652 D ActivityManager: caller:android.app.ApplicationThreadProxy@3178f51e, r.packageName :com.android.bluetooth
06-30 13:55:35.927  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.927  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.927  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.927  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.927  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.927  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:35.927  3234  3289 D BluetoothAdapterService: Autoconnection is available 
06-30 13:55:35.927  3234  3289 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
06-30 13:55:35.927  3234  3289 D BluetoothAdapterService: starting service from this receiver
06-30 13:55:35.927  3234  3234 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,06-30 13:55:35.927  3234  3234 I BluetoothPbapService: Handler(): got msg=1
06-30 13:55:35.927   754  1553 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:35.927   754  1553 D ActivityManager: caller:android.app.ApplicationThreadProxy@3ae8abcc, r.packageName :com.android.bluetooth
,06-30 13:55:35.927   754  1343 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,06-30 13:55:35.927  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:35.927  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:35.927  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:35.927  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:35.927  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:35.927  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:35.927  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:35.927  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:35.927  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.927  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.927  3234  3289 I BluetoothAdapterState: Entering On State from state = 11
06-30 13:55:35.927   754  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,06-30 13:55:35.927  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.927  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:35.927  4615  4627 E BluetoothHeadset: BluetoothHeadset service is binded
06-30 13:55:35.927  7447  7447 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:55:35.927  3387  3397 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-30 13:55:35.937  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.937  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.937  3234  7827 V BluetoothPbapService: PBAP Service initSocket try: 0
,06-30 13:55:35.937  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.937  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.937  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.937  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:35.937   754  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,06-30 13:55:35.937  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.937  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:35.937   754  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,06-30 13:55:35.937  3234  7827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-30 13:55:35.937  1404  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,06-30 13:55:35.947  4615  4615 D HeadsetProfile: Bluetooth service connected
,06-30 13:55:35.947  3234  7827 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
06-30 13:55:35.947  3234  7827 D BluetoothSocket: bindListen(), new LocalSocket 
06-30 13:55:35.947  3234  7827 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
06-30 13:55:35.947  3234  7827 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@189546be
06-30 13:55:35.947  3234  3295 D bt_vendor: op for 7
06-30 13:55:35.947  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:35.947  3234  7827 D BluetoothSocket: channel: 19
06-30 13:55:35.947  3234  7827 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
06-30 13:55:35.947  4615  6107 D Bluetoothsap: onBluetoothStateChange: up=true
06-30 13:55:35.947  4615  6107 D Bluetoothsap: Binding service...
,06-30 13:55:35.947  4615  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,06-30 13:55:35.947  3387  3387 D BluetoothA2dp: Proxy object connected
06-30 13:55:35.947   754  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,06-30 13:55:35.947  4615  6107 D Bluetoothsap: bindService called to Bluetooth SAP Service
06-30 13:55:35.947  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:35.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:35.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:35.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:35.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:35.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:35.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:35.947  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 13:55:35.947   754  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,06-30 13:55:35.947  7447  7447 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:55:35.947  3387  3397 E BluetoothHeadset: BluetoothHeadset service is binded
06-30 13:55:35.947   754  1044 D BluetoothPan: Binding service...
06-30 13:55:35.947  4615  4615 D Bluetoothsap: BluetoothSAP Proxy object connected
06-30 13:55:35.947   754  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,06-30 13:55:35.957  4615  4615 D SapProfile: Bluetooth service connected
06-30 13:55:35.957  4615  4615 D Bluetoothsap: getConnectedDevices()
,06-30 13:55:35.957   754   754 D BluetoothPan: BluetoothPAN Proxy object connected
,06-30 13:55:35.957   754  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,06-30 13:55:35.957  1404  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,06-30 13:55:35.957  3234  3243 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-30 13:55:35.957  7817  7817 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:35.957  7817  7817 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:35.967   754  1044 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,06-30 13:55:35.967  3234  3234 D BluetoothA2dp: Proxy object connected
06-30 13:55:35.967  3234  3234 D BluetoothAdapterService: Bluetooth A2dp source service connected
,06-30 13:55:35.967   754  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-30 13:55:35.977   754  1652 I ActivityManager: Killing 7069:com.google.android.partnersetup/u0a19 (adj 15): emptyCount ##41
,06-30 13:55:35.977   754  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,06-30 13:55:35.977   754   754 D BluetoothA2dp: Proxy object connected
,06-30 13:55:35.977  4615  4627 D BluetoothMap: onBluetoothStateChange: up=true
,06-30 13:55:35.977   754  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,06-30 13:55:35.977  4615  6107 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-30 13:55:35.987  4615  4615 D BluetoothMap: Proxy object connected
06-30 13:55:35.987  4615  4615 D MapProfile: Bluetooth service connected
,06-30 13:55:35.987   754  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,06-30 13:55:35.987   754  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,06-30 13:55:35.987  1425  1664 E BluetoothHeadset: BluetoothHeadset service is binded
,06-30 13:55:35.987  4615  4634 D BluetoothPan: Binding service...
,06-30 13:55:35.987   754  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,06-30 13:55:35.987   754  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,06-30 13:55:35.987   754  1044 E BluetoothHeadset: BluetoothHeadset service is binded
06-30 13:55:35.987  4615  4627 D BluetoothPbap: onBluetoothStateChange: up=true
,06-30 13:55:35.987   754  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,06-30 13:55:35.987   754  1553 D RCPManagerService: exchangeData() failure , invalid userId
06-30 13:55:35.987  4615  6107 D BluetoothInputDevice: onBluetoothStateChange: up=true
,06-30 13:55:35.997   754  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,06-30 13:55:35.997  7817  7817 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,06-30 13:55:35.997   754  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
06-30 13:55:35.997  4615  4615 D BluetoothA2dp: Proxy object connected
06-30 13:55:35.997  4615  4615 D A2dpProfile: Bluetooth service connected
06-30 13:55:35.997  1404  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,06-30 13:55:35.997   754  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,06-30 13:55:35.997  1757  1757 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,06-30 13:55:35.997   754   754 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:35.997   754   754 I InputMethodManagerService: [BT Setting State] State =12
06-30 13:55:35.997   754   754 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
06-30 13:55:35.997  1189  1189 D BluetoothTile:  onBluetoothStateChange:
,06-30 13:55:36.007  1404  1404 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2376d7c, true
,06-30 13:55:36.007  1404  1404 D BluetoothHeadset: registerMessageListener
,06-30 13:55:36.007  1189  1189 D BluetoothTile:  onBluetoothPairedDevicesChanged:
06-30 13:55:36.007  3234  3652 D HeadsetService: registerMessageListener
06-30 13:55:36.007  1189  1189 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:36.007  3234  3652 D HeadsetService: registerMessageListener
,06-30 13:55:36.007  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,06-30 13:55:36.007  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
06-30 13:55:36.007  3234  7768 D HeadsetStateMachine: Disconnected process message: 70
06-30 13:55:36.007  3234  7768 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2811331f
06-30 13:55:36.007  7606  7606 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:36.007  4615  4615 D BluetoothPan: BluetoothPAN Proxy object connected
06-30 13:55:36.007  4615  4615 D PanProfile: Bluetooth service connected
,06-30 13:55:36.017  3234  7839 D BluetoothMapMasInstance: set MAP SDP message type : 1
,06-30 13:55:36.017  1189  1608 D BluetoothTile:  handleUpdatestate:false name:null
06-30 13:55:36.017  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,06-30 13:55:36.017  3234  7768 D HeadsetStateMachine: Disconnected process message: 9
06-30 13:55:36.017  3234  7768 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,06-30 13:55:36.017  3234  7839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-30 13:55:36.017   308   667 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,06-30 13:55:36.017   308   667 V voice   : voice_set_parameters: enter: A2dpSuspended=false
06-30 13:55:36.017   308   667 V voice   : voice_set_parameters: exit with code(-2)
,06-30 13:55:36.017   308   667 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
06-30 13:55:36.017   308   667 V msm8974_platform: platform_set_parameters: exit with code(-2)
06-30 13:55:36.017   754  1697 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
06-30 13:55:36.017   308   667 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
06-30 13:55:36.017   308   667 V audio_hw_primary: adev_set_parameters: exit
,06-30 13:55:36.017  3234  7768 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
06-30 13:55:36.017   754  1144 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
06-30 13:55:36.017  3234  3295 D bt_vendor: op for 7
,06-30 13:55:36.017  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:36.017  3234  7839 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
06-30 13:55:36.017  1189  1189 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
06-30 13:55:36.017  3234  7839 D BluetoothSocket: bindListen(), new LocalSocket 
06-30 13:55:36.017  3234  7839 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,06-30 13:55:36.027  3234  7839 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35e0666c
06-30 13:55:36.027  3234  7839 D BluetoothSocket: channel: 5
06-30 13:55:36.027  4615  4615 D BluetoothPbap: Proxy object connected
06-30 13:55:36.027  4615  4615 D PbapServerProfile: Bluetooth service connected
06-30 13:55:36.027  4615  4615 D BluetoothInputDevice: Proxy object connected
06-30 13:55:36.027  4615  4615 D HidProfile: Bluetooth service connected
,06-30 13:55:36.027  4615  4615 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:36.027  4615  4615 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
06-30 13:55:36.027  4615  4615 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,06-30 13:55:36.037  7796  7796 I sCloudBackupApp: sCloudBackupApp Version Info : 3.13.7.KK_APP
,06-30 13:55:36.037  7796  7796 I SCloudBackupReceiver: Other Intent
,06-30 13:55:36.037  7817  7817 D BadgeProvider: onCreate
06-30 13:55:36.037   754  1144 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,06-30 13:55:36.037   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:36.037   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:36.037   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:36.037   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:36.037  7817  7817 D BadgeProvider: DatabaseHelper
,06-30 13:55:36.047  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 13:55:36.047  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 13:55:36.047  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 13:55:36.047  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 13:55:36.047  1189  1189 D QSpanel : label top:23
06-30 13:55:36.047  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 13:55:36.047  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 13:55:36.047  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 13:55:36.047  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 13:55:36.047  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 13:55:36.047  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 13:55:36.117  7841  7841 E Zygote  : MountEmulatedStorage()
06-30 13:55:36.117  7841  7841 E Zygote  : v2
06-30 13:55:36.117  7841  7841 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:55:36.117  7841  7841 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:36.117   754  1144 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7841 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 13:55:36.127   754  1144 I ActivityManager: Killing 7091:com.samsung.groupcast/u0a20 (adj 15): emptyCount ##41
,06-30 13:55:36.157  7841  7841 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:36.157  7841  7841 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 13:55:36.157  7841  7841 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:55:36.167  7817  7832 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,06-30 13:55:36.187  7841  7841 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:36.187  7841  7841 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:36.187  7817  7832 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
06-30 13:55:36.187  7817  7832 D BadgeProvider: sendNotify, [notify] : null
06-30 13:55:36.187  7817  7832 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
06-30 13:55:36.187  1449  1449 D Launcher.Model: reloadBadges entered.
06-30 13:55:36.187  7817  7832 D BadgeProvider: update, [BadgeCount] : badgecount=0
06-30 13:55:36.187  7817  7832 D BadgeProvider: update, [UpdateCount] : 1
,06-30 13:55:36.207  7841  7841 D ResourcesManager: creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,06-30 13:55:36.207  7841  7841 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 13:55:36.217   754  1584 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,06-30 13:55:36.227  7841  7841 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,06-30 13:55:36.227  7841  7841 I KnoxUsageLogPro: premStatus:2
,06-30 13:55:36.227  7841  7841 I KnoxUsageLogPro: isEulaShown : false
06-30 13:55:36.227  7841  7841 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,06-30 13:55:36.237   754   781 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,06-30 13:55:36.237   754   781 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:36.237   754   781 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:36.237   754   781 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:36.237   754   781 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:36.277  7857  7857 E Zygote  : MountEmulatedStorage()
,06-30 13:55:36.277  7857  7857 E Zygote  : v2
06-30 13:55:36.277  7857  7857 I libpersona: KNOX_SDCARD checking this for 10104
06-30 13:55:36.277  7857  7857 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:36.277   754   783 I art     : Explicit concurrent mark sweep GC freed 44532(2MB) AllocSpace objects, 1(16KB) LOS objects, 30% free, 35MB/51MB, paused 1.451ms total 91.123ms
,06-30 13:55:36.287   754   781 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7857 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 13:55:36.307  7857  7857 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:36.307  7857  7857 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 13:55:36.307  7857  7857 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,06-30 13:55:36.307   754  1476 I ActivityManager: Killing 7114:com.sec.android.service.health/u0a21 (adj 15): emptyCount ##41
,06-30 13:55:36.327  7857  7857 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:36.337  7857  7857 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:36.347  7857  7857 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,06-30 13:55:36.417   754  1357 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,06-30 13:55:36.417   754  1357 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:36.417   754  1357 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:36.417   754  1357 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:36.417   754  1357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:36.457  7876  7876 E Zygote  : MountEmulatedStorage()
06-30 13:55:36.457  7876  7876 E Zygote  : v2
06-30 13:55:36.457  7876  7876 I libpersona: KNOX_SDCARD checking this for 10146
06-30 13:55:36.457  7876  7876 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:36.467   754  1357 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7876 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 13:55:36.467   754  1357 I ActivityManager: Killing 6419:sstream.app/u0a25 (adj 15): emptyCount ##41
,06-30 13:55:36.537  7876  7876 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:36.537  7876  7876 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 13:55:36.537  7447  7506 D BluetoothAdapter: disable()
,06-30 13:55:36.537  7876  7876 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 13:55:36.537   754  1378 D SettingsProvider: name = bluetooth_on
,06-30 13:55:36.537  3234  3289 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,06-30 13:55:36.537  3234  3289 D BluetoothAdapterProperties: Setting state to 13
06-30 13:55:36.537  3234  3289 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
06-30 13:55:36.537  3234  3289 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-30 13:55:36.537  3234  3289 D BluetoothAdapterService: updateAdapterState state is 13
,06-30 13:55:36.537   754  1697 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:36.537   754  1697 D ActivityManager: caller:android.app.ApplicationThreadProxy@36d734eb, r.packageName :com.android.bluetooth
,06-30 13:55:36.537  3234  3234 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
06-30 13:55:36.537  3234  3289 D BluetoothAdapterService: Autoconnection is available 
06-30 13:55:36.537  3234  3289 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
06-30 13:55:36.537  3234  3289 D BluetoothAdapterService: terminating service from this receiver
06-30 13:55:36.537  3234  3234 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3348b435, channel: 19, state: LISTENING
06-30 13:55:36.537  3234  3234 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3348b435, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@189546be, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@12db10camSocket: android.net.LocalSocket@c9fe23b impl:android.net.LocalSocketImpl@ba37d58 fd:FileDescriptor[78]
06-30 13:55:36.537  3234  3234 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@c9fe23b impl:android.net.LocalSocketImpl@ba37d58 fd:FileDescriptor[78]
,06-30 13:55:36.547  3234  3289 D BluetoothAdapterProperties: onBluetoothDisable()
,06-30 13:55:36.547   754   754 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:36.547   754   783 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
06-30 13:55:36.547   754   754 I InputMethodManagerService: [BT Setting State] State =13
06-30 13:55:36.547  3234  3289 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
06-30 13:55:36.547  3234  3295 D bt_vendor: op for 7
06-30 13:55:36.547  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:36.547  3234  3295 D bt_vendor: op for 7
06-30 13:55:36.547  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:36.547  3234  3295 D bt_vendor: op for 7
06-30 13:55:36.547  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:36.547  1189  1189 D BluetoothTile:  onBluetoothStateChange:
,06-30 13:55:36.547  1757  1757 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
06-30 13:55:36.547  1189  1189 D BluetoothTile:  onBluetoothPairedDevicesChanged:
06-30 13:55:36.547  1189  1189 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:36.547  1189  1608 D BluetoothTile:  handleUpdatestate:false name:null
,06-30 13:55:36.547   754  1697 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,06-30 13:55:36.547  7606  7606 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:36.547  4615  4615 D BluetoothPbap: Proxy object disconnected
06-30 13:55:36.547  4615  4615 D PbapServerProfile: Bluetooth service disconnected
06-30 13:55:36.547  4615  4615 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:36.547  1189  1608 D BluetoothTile:  handleUpdatestate:false name:null
,06-30 13:55:36.547   754   783 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
06-30 13:55:36.547  3234  3292 D BluetoothAdapterProperties: Scan Mode:20
06-30 13:55:36.547  3234  3289 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
06-30 13:55:36.547  3234  3289 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,06-30 13:55:36.547  3234  3289 E bt-btif : cmd socket is not created
06-30 13:55:36.547  3234  3289 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
06-30 13:55:36.547  3234  3293 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
06-30 13:55:36.547  3234  3295 D bt_vendor: op for 7
06-30 13:55:36.547  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:36.557  1189  1189 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
06-30 13:55:36.557  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
06-30 13:55:36.557  3234  3234 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@edd5eb1, channel: 5, state: LISTENING
06-30 13:55:36.557  3234  3234 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@edd5eb1, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35e0666c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@35016f96mSocket: android.net.LocalSocket@25a06717 impl:android.net.LocalSocketImpl@377f1704 fd:FileDescriptor[80]
06-30 13:55:36.557  3234  3234 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@25a06717 impl:android.net.LocalSocketImpl@377f1704 fd:FileDescriptor[80]
06-30 13:55:36.557  3234  3295 D bt_vendor: op for 7
06-30 13:55:36.557  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:36.557  3234  3295 D bt_vendor: op for 7
06-30 13:55:36.557  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:36.557  3234  3295 D bt_vendor: op for 7
06-30 13:55:36.557  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:36.557  3234  3295 D bt_vendor: op for 7
06-30 13:55:36.557  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:36.557  3234  3293 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
06-30 13:55:36.557  3234  3293 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:55:36.557  3234  3293 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
06-30 13:55:36.557  3234  3293 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
06-30 13:55:36.557  3234  3293 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:55:36.557  3234  3293 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
06-30 13:55:36.567  3234  3295 D bt_vendor: op for 7
06-30 13:55:36.567  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:36.567  3234  3295 D bt_vendor: op for 7
06-30 13:55:36.567  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:36.567  3234  3295 D bt_vendor: op for 7
06-30 13:55:36.567  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:36.567  7876  7876 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:36.567  7876  7876 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:36.577  7876  7876 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,06-30 13:55:36.597  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 13:55:36.597  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 13:55:36.597  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 13:55:36.597  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 13:55:36.597  1189  1189 D QSpanel : label top:23
06-30 13:55:36.597  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 13:55:36.597  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 13:55:36.597  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 13:55:36.597  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 13:55:36.597  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 13:55:36.597  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 13:55:36.607  7447  7447 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:36.607  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 13:55:36.607  7447  7447 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:55:36.757  3234  3289 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
06-30 13:55:36.757  3234  3289 D BtConfig.SecureMode: isSecureModeOn:false
06-30 13:55:36.757  3234  3289 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
06-30 13:55:36.757  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
06-30 13:55:36.757  3234  3289 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
06-30 13:55:36.757  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
06-30 13:55:36.757  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-30 13:55:36.757  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,06-30 13:55:36.757   754  1570 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:36.757   754  1570 D ActivityManager: caller:android.app.ApplicationThreadProxy@1aac28e1, r.packageName :com.android.bluetooth
06-30 13:55:36.757  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
06-30 13:55:36.757  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
06-30 13:55:36.757  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,06-30 13:55:36.757   754  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:36.757   754  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@ec82606, r.packageName :com.android.bluetooth
06-30 13:55:36.757  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
06-30 13:55:36.757  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 13:55:36.757  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,06-30 13:55:36.757   754   781 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:36.757   754   781 D ActivityManager: caller:android.app.ApplicationThreadProxy@357234c7, r.packageName :com.android.bluetooth
06-30 13:55:36.757  3234  3234 D HeadsetService: Received stop request...Stopping profile...
06-30 13:55:36.757  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
06-30 13:55:36.757  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 13:55:36.757  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,06-30 13:55:36.757   754   783 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:36.757   754   783 D ActivityManager: caller:android.app.ApplicationThreadProxy@269f4af4, r.packageName :com.android.bluetooth
,06-30 13:55:36.757  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
06-30 13:55:36.757  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
06-30 13:55:36.757  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-30 13:55:36.757  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,06-30 13:55:36.757   754  1421 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 13:55:36.757   754  1421 D ActivityManager: caller:android.app.ApplicationThreadProxy@2761721d, r.packageName :com.android.bluetooth
06-30 13:55:36.757  3234  3234 D A2dpService: Received stop request...Stopping profile...
06-30 13:55:36.757  3234  3234 V Avrcp   : doQuit
06-30 13:55:36.757  3234  7772 D A2dpStateMachine: Exit Disconnected: -1
06-30 13:55:36.757  3234  3234 D Avrcp   : Unregistering previous receiver
,06-30 13:55:36.757  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
06-30 13:55:36.757  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:36.757  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,06-30 13:55:36.757  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:36.757   754  1570 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 13:55:36.757   754  1570 D ActivityManager: caller:android.app.ApplicationThreadProxy@14b09c92, r.packageName :com.android.bluetooth
06-30 13:55:36.767  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
06-30 13:55:36.767  3234  3234 D HidService: Received stop request...Stopping profile...
06-30 13:55:36.767  3234  3234 D HidService: Stopping Bluetooth HidService
06-30 13:55:36.767  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 13:55:36.767  3234  3234 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
06-30 13:55:36.767  3234  3234 W bt-btif : cleanup: HH disabling or disabled already, status = 0
06-30 13:55:36.767  3234  3234 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
06-30 13:55:36.767  3234  3289 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
06-30 13:55:36.767  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:36.767   754  1697 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:36.767   754  1697 D ActivityManager: caller:android.app.ApplicationThreadProxy@9d35663, r.packageName :com.android.bluetooth
06-30 13:55:36.767   754   754 D AudioService: onServiceDisconnected: Bluetooth profile: 1
06-30 13:55:36.767   754   754 D BluetoothA2dp: Proxy object disconnected
06-30 13:55:36.767   754   754 D AudioService: onServiceDisconnected: Bluetooth profile: 2
06-30 13:55:36.767  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
06-30 13:55:36.767  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
06-30 13:55:36.767  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
06-30 13:55:36.767  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
06-30 13:55:36.767  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
06-30 13:55:36.767  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
06-30 13:55:36.767  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
06-30 13:55:36.767  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
06-30 13:55:36.767  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
06-30 13:55:36.767  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
06-30 13:55:36.767  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
06-30 13:55:36.767  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
06-30 13:55:36.767  3234  3289 D BluetoothAdapterState: Stopping profile services that were post enabled
06-30 13:55:36.767  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
06-30 13:55:36.767  3234  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 13:55:36.767  3234  3234 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
06-30 13:55:36.767  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
06-30 13:55:36.767  3234  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 13:55:36.767  3234  3234 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,06-30 13:55:36.767  3234  3234 D HealthService: Received stop request...Stopping profile...
06-30 13:55:36.767  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:36.767  4615  4615 D HeadsetProfile: Bluetooth service disconnected
06-30 13:55:36.767  4615  4615 D BluetoothA2dp: Proxy object disconnected
06-30 13:55:36.767  4615  4615 D A2dpProfile: Bluetooth service disconnected
06-30 13:55:36.767  4615  4615 D BluetoothInputDevice: Proxy object disconnected
06-30 13:55:36.767  4615  4615 D HidProfile: Bluetooth service disconnected
,06-30 13:55:36.767  3234  3234 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
06-30 13:55:36.767  3234  3234 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,06-30 13:55:36.767  3234  3234 D PanService: Received stop request...Stopping profile...
06-30 13:55:36.767  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:36.767  3234  3234 D BluetoothA2dp: Proxy object disconnected
06-30 13:55:36.767  3234  3234 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
06-30 13:55:36.767  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
06-30 13:55:36.767  3234  3234 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
06-30 13:55:36.767  3234  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:36.767  3234  3234 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,06-30 13:55:36.767  3234  7773 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,06-30 13:55:36.767  3234  3234 I GKI_LINUX: GKI_exit_task 2 done
06-30 13:55:36.767  3234  3234 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
06-30 13:55:36.767  3234  3234 V Avrcp   : cleanup
06-30 13:55:36.767   754   754 D BluetoothPan: BluetoothPAN Proxy object disconnected
06-30 13:55:36.767  3234  3234 D BluetoothMapService: Received stop request...Stopping profile...
,06-30 13:55:36.767  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:36.777  7606  7606 W BluetoothHeadset: Proxy not attached to service
,06-30 13:55:36.777  3387  3387 D BluetoothA2dp: Proxy object disconnected
06-30 13:55:36.777  3234  3234 D SapService: Received stop request...Stopping profile...
06-30 13:55:36.777  3234  3234 D SapService: Stopping Bluetooth SapService
06-30 13:55:36.777  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:36.777  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
06-30 13:55:36.777  3234  3234 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
06-30 13:55:36.777  3234  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:36.777  3234  3234 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:36.777  3234  3234 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
06-30 13:55:36.777  3234  3234 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
06-30 13:55:36.777  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
06-30 13:55:36.777  3234  3234 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
06-30 13:55:36.777  3234  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:36.777  3234  3234 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:36.777  3234  3234 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
06-30 13:55:36.777  3234  3234 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,06-30 13:55:36.777  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
06-30 13:55:36.777  3234  3234 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
06-30 13:55:36.777  3234  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 13:55:36.777  3234  3234 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,06-30 13:55:36.777  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
06-30 13:55:36.777  3234  3234 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
06-30 13:55:36.777  3234  3289 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
06-30 13:55:36.777  3234  3289 D BluetoothAdapterProperties: Setting state to 10
06-30 13:55:36.777  3234  3234 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
06-30 13:55:36.777  3234  3289 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
06-30 13:55:36.777  3234  3234 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
06-30 13:55:36.777  3234  3289 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-30 13:55:36.777  3234  3289 D BluetoothAdapterService: updateAdapterState state is 10
06-30 13:55:36.777  4615  4615 D BluetoothPan: BluetoothPAN Proxy object disconnected
06-30 13:55:36.777  4615  4615 D PanProfile: Bluetooth service disconnected
06-30 13:55:36.777  4615  4615 D BluetoothMap: Proxy object disconnected
06-30 13:55:36.777  4615  4615 D MapProfile: Bluetooth service disconnected
,06-30 13:55:36.777  3234  3289 D BluetoothAdapterService: Autoconnection is available 
06-30 13:55:36.777  3234  3289 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
06-30 13:55:36.777  3234  3289 I BluetoothAdapterState: Entering OffState
,06-30 13:55:36.777  3387  3399 D BluetoothA2dp: onBluetoothStateChange: up=false
,06-30 13:55:36.777  4615  4627 D Bluetoothsap: onBluetoothStateChange: up=false
06-30 13:55:36.777  4615  4627 D Bluetoothsap: Unbinding service...
,06-30 13:55:36.777  3234  3243 D BluetoothA2dp: onBluetoothStateChange: up=false
,06-30 13:55:36.777   754  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
06-30 13:55:36.777  4615  4634 D BluetoothMap: onBluetoothStateChange: up=false
,06-30 13:55:36.777  4615  6107 D BluetoothA2dp: onBluetoothStateChange: up=false
,06-30 13:55:36.787  4615  4634 D BluetoothPbap: onBluetoothStateChange: up=false
,06-30 13:55:36.787  4615  6107 D BluetoothInputDevice: onBluetoothStateChange: up=false
,06-30 13:55:36.787   754   754 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:36.787  1757  1757 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
06-30 13:55:36.787   754   754 I InputMethodManagerService: [BT Setting State] State =10
06-30 13:55:36.787  4615  4615 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:36.787   754   754 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
06-30 13:55:36.787  7606  7606 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:36.787  1189  1189 D BluetoothTile:  onBluetoothPairedDevicesChanged:
06-30 13:55:36.787  1189  1189 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:36.787  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,06-30 13:55:36.787   754  1652 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,06-30 13:55:36.787   754  1144 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,06-30 13:55:36.787  1189  1189 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,06-30 13:55:36.807   265   555 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
06-30 13:55:36.807   265   555 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 13:55:36.807  7876  7896 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,06-30 13:55:36.807  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 13:55:36.807  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 13:55:36.807  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 13:55:36.807  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 13:55:36.807  1189  1189 D QSpanel : label top:23
06-30 13:55:36.807  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 13:55:36.807  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 13:55:36.807  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 13:55:36.807  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 13:55:36.807  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 13:55:36.807  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 13:55:36.807   265   555 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
06-30 13:55:36.807   265   555 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 13:55:36.817  7876  7896 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,06-30 13:55:36.817   265   555 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
06-30 13:55:36.817   265   555 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 13:55:36.817  7876  7898 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,06-30 13:55:36.817   265   555 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
06-30 13:55:36.817   265   555 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 13:55:36.817  7876  7898 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,06-30 13:55:36.967  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
06-30 13:55:36.967  7447  7514 I jxcore-log: 
,06-30 13:55:36.977  7876  7876 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,06-30 13:55:36.977  7876  7876 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,06-30 13:55:36.997  7876  7876 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1718-1720)
,06-30 13:55:36.997  7876  7876 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 13:55:36.997  7876  7876 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {16ef59dc}
,06-30 13:55:36.997  7876  7876 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 13:55:36.997  7876  7876 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 13:55:37.027  7876  7876 I BrowserStartupController: Initializing chromium process, singleProcess=true
,06-30 13:55:37.027  7876  7876 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 13:55:37.027  7876  7876 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-30 13:55:37.037  7876  7876 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,06-30 13:55:37.037  7876  7876 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
06-30 13:55:37.037  7876  7876 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,06-30 13:55:37.047  7876  7876 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
06-30 13:55:37.047  7876  7876 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
06-30 13:55:37.047  7876  7876 I Adreno-EGL: Build Date: 11/19/14 Wed
06-30 13:55:37.047  7876  7876 I Adreno-EGL: Local Branch: mybranch5813579
06-30 13:55:37.047  7876  7876 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
06-30 13:55:37.047  7876  7876 I Adreno-EGL: Local Patches: NONE
06-30 13:55:37.047  7876  7876 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,06-30 13:55:37.117  7876  7926 W AudioManagerAndroid: Requires BLUETOOTH permission
,06-30 13:55:37.127  7876  7876 I NSApplication: Starting up...
,06-30 13:55:37.137   754   783 I ActivityManager: Killing 6512:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): emptyCount ##41
,06-30 13:55:37.197   754   781 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,06-30 13:55:37.197   754   781 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:37.197   754   781 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:37.197   754   781 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:37.197   754   781 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:37.287  7934  7934 E Zygote  : MountEmulatedStorage()
06-30 13:55:37.287  7934  7934 E Zygote  : v2
06-30 13:55:37.287  7934  7934 I libpersona: KNOX_SDCARD checking this for 10158
06-30 13:55:37.287  7934  7934 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:37.287   754   781 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7934 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,06-30 13:55:37.317  7934  7934 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:37.317  7934  7934 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 13:55:37.317  7934  7934 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:55:37.337  7934  7934 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:37.337  7934  7934 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:37.347  7934  7934 D ResourcesManager: creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,06-30 13:55:37.347  7934  7934 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 13:55:37.347  7934  7934 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
06-30 13:55:37.347  7934  7934 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,06-30 13:55:37.367  7934  7934 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:37.367  7934  7934 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,06-30 13:55:37.367  7934  7934 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,06-30 13:55:37.387  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
06-30 13:55:37.387  7447  7514 I jxcore-log: 
,06-30 13:55:37.387   754  1544 D RCPManagerService: exchangeData() failure , invalid userId
,06-30 13:55:37.397   754   783 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:37.397  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,06-30 13:55:37.397  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-30 13:55:37.397  7516  7516 D SecurityLogAgent: StateMachine : Current State = 1
06-30 13:55:37.397  7516  7516 D SecurityLogAgent: StateMachine : Changed Current State = 1
,06-30 13:55:37.397   754  1584 I ActivityManager: Killing 5677:com.sec.android.app.shealth/u0a40 (adj 15): emptyCount ##41
,06-30 13:55:37.397   754  1343 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:37.397   754  1553 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:37.397   754  1584 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,06-30 13:55:37.397   754  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:37.397   754  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:37.397   754  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:55:37.397   754  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:37.417  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
06-30 13:55:37.417  7447  7514 I jxcore-log: 
,06-30 13:55:37.417  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
06-30 13:55:37.417  7447  7514 I jxcore-log: 
,06-30 13:55:37.437  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
06-30 13:55:37.437  7447  7514 I jxcore-log: 
,06-30 13:55:37.437  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-30 13:55:37.437  7447  7514 I jxcore-log: 
,06-30 13:55:37.447  7949  7949 E Zygote  : MountEmulatedStorage()
,06-30 13:55:37.447  7949  7949 E Zygote  : v2
06-30 13:55:37.447  7949  7949 I libpersona: KNOX_SDCARD checking this for 10200
06-30 13:55:37.447  7949  7949 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:37.447   754  1584 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7949 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,06-30 13:55:37.497   302   302 E SMD     : DCD ON
,06-30 13:55:37.507  7949  7949 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:37.507  7949  7949 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 13:55:37.507  7949  7949 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,06-30 13:55:37.527  7949  7949 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:37.527  7949  7949 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:37.537  7949  7949 D ResourcesManager: creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,06-30 13:55:37.537  7447  7506 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:55:37.537  7447  7506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,06-30 13:55:37.557   754  1570 I ActivityManager: Killing 7185:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
,06-30 13:55:37.557  5780  5780 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,06-30 13:55:37.567   754  1144 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:37.567  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State = 1
06-30 13:55:37.567  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-30 13:55:37.567  7516  7516 D SecurityLogAgent: StateMachine : Current State = 1
06-30 13:55:37.567  7516  7516 D SecurityLogAgent: StateMachine : Changed Current State = 1
,06-30 13:55:37.577  5780  5780 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,06-30 13:55:37.577   754  1571 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:37.577  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State = 1
06-30 13:55:37.577  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-30 13:55:37.577  7516  7516 D SecurityLogAgent: StateMachine : Current State = 1
06-30 13:55:37.577  7516  7516 D SecurityLogAgent: StateMachine : Changed Current State = 1
,06-30 13:55:37.587  7631  7631 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,06-30 13:55:37.587  4615  4615 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,06-30 13:55:37.587  4615  4615 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
06-30 13:55:37.587   754  1544 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:37.587  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
06-30 13:55:37.587  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
06-30 13:55:37.587   754  1246 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
06-30 13:55:37.587  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
06-30 13:55:37.587  4615  4615 I NearbySettings: MountReceiver.onReceive - Set preference state off
06-30 13:55:37.587  4615  4727 V NearbySettings: MountReceiver.mPrefHandler - 7002
,06-30 13:55:37.597  6536  6536 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,06-30 13:55:37.597  7631  7631 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,06-30 13:55:37.597  7631  7631 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
06-30 13:55:37.597  7631  7631 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,06-30 13:55:37.597  7631  7631 D WifiDirectBR: stopServiceTest : false
,06-30 13:55:37.597  7631  7631 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,06-30 13:55:37.607  4615  4615 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,06-30 13:55:37.607  4615  4615 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
06-30 13:55:37.607   754  1544 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:37.607  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
06-30 13:55:37.607   754  1570 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,06-30 13:55:37.607  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
06-30 13:55:37.607  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
06-30 13:55:37.607  4615  4615 I NearbySettings: MountReceiver.onReceive - Set preference state off
06-30 13:55:37.607  4615  4727 V NearbySettings: MountReceiver.mPrefHandler - 7002
,06-30 13:55:37.617   754  1652 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:37.617  5780  5780 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,06-30 13:55:37.627  5780  5780 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,06-30 13:55:37.627   754  1343 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:37.627  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State = 1
06-30 13:55:37.627  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-30 13:55:37.627  7516  7516 D SecurityLogAgent: StateMachine : Current State = 1
06-30 13:55:37.627  7516  7516 D SecurityLogAgent: StateMachine : Changed Current State = 1
,06-30 13:55:37.647  5780  5780 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,06-30 13:55:37.647   754   783 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:37.647  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State = 1
06-30 13:55:37.647  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-30 13:55:37.647  7516  7516 D SecurityLogAgent: StateMachine : Current State = 1
06-30 13:55:37.647  7516  7516 D SecurityLogAgent: StateMachine : Changed Current State = 1
,06-30 13:55:37.657  1627  1627 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,06-30 13:55:37.657  4615  4615 D BluetoothNotiBroadcastReceiver: onReceive
,06-30 13:55:37.667  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,06-30 13:55:37.667   754  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
06-30 13:55:37.667   754  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@235354, r.packageName :com.android.settings
,06-30 13:55:37.677  1627  1627 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,06-30 13:55:37.677  4615  4615 D DockEventReceiver: finishStartingService: stopping service
,06-30 13:55:37.677  4615  4615 D BluetoothNotiBroadcastReceiver: onReceive
,06-30 13:55:37.677  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
06-30 13:55:37.677  3234  3234 D BtConfig.SecureMode: isSecureModeOn:false
,06-30 13:55:37.677   754  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 13:55:37.677   754  1544 D ActivityManager: caller:android.app.ApplicationThreadProxy@5a1cbf2, r.packageName :com.android.bluetooth
,06-30 13:55:37.687  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,06-30 13:55:37.687   754  1544 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
06-30 13:55:37.687   754  1544 D ActivityManager: caller:android.app.ApplicationThreadProxy@fc63f9f, r.packageName :com.android.settings
,06-30 13:55:37.697  1627  1627 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,06-30 13:55:37.697  4615  4615 D DockEventReceiver: finishStartingService: stopping service
,06-30 13:55:37.697  4615  4615 D BluetoothNotiBroadcastReceiver: onReceive
,06-30 13:55:37.707  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,06-30 13:55:37.717   754  1144 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
06-30 13:55:37.717   754  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@f0fd4b5, r.packageName :com.android.settings
,06-30 13:55:37.717  1627  1627 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,06-30 13:55:37.717  4615  4615 D DockEventReceiver: finishStartingService: stopping service
,06-30 13:55:37.717  4615  4615 D BluetoothNotiBroadcastReceiver: onReceive
,06-30 13:55:37.847  3234  3425 D bt_upio : ..proc_btwrite_timeout..
,06-30 13:55:38.067  3234  3295 D bt_vendor: op for 7
,06-30 13:55:38.537  7447  7506 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:55:38.537  7447  7506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:55:38.537  7447  7506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:55:38.537  7447  7506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:55:38.537  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3609e2b1 removed from the list
,06-30 13:55:38.537  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:55:38.537  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@64a8b17 added. We now have 2 listener(s)
06-30 13:55:38.537  7447  7506 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 13:55:38.547  7447  7506 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:55:38.547  7447  7506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:55:38.547  7447  7506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:55:38.547  7447  7506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:55:38.547  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@64a8b17 removed from the list
06-30 13:55:38.547  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:55:38.547  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee86b04 added. We now have 2 listener(s)
06-30 13:55:38.547  7447  7506 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 13:55:38.547  7447  7506 D BluetoothAdapter: disable()
06-30 13:55:38.547   754  1570 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,06-30 13:55:38.557  7447  7506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:38.557  7447  7506 D BluetoothAdapter: enable()
,06-30 13:55:38.557   754  1571 W ActivityManager: Permission Denial: getCurrentUser() from pid=7447, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
06-30 13:55:38.557   754  1571 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
06-30 13:55:38.557   754  1571 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7447, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
06-30 13:55:38.557   754  1571 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
06-30 13:55:38.557   754  1571 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
06-30 13:55:38.557   754  1571 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
06-30 13:55:38.557   754  1571 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
06-30 13:55:38.557   754  1571 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
06-30 13:55:38.557   754  1571 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
06-30 13:55:38.557   754  1571 D SettingsProvider: name = bluetooth_on
06-30 13:55:38.557   754  1571 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,06-30 13:55:38.567   754  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,06-30 13:55:38.567   754  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,06-30 13:55:38.577   754  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,06-30 13:55:38.577  3234  3289 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,06-30 13:55:38.577  3234  3289 D BluetoothAdapterProperties: Setting state to 11
06-30 13:55:38.577  3234  3289 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,06-30 13:55:38.577  3234  3289 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-30 13:55:38.577  3234  3289 D BluetoothAdapterService: updateAdapterState state is 11
,06-30 13:55:38.577  3234  3289 D BluetoothAdapterService: Autoconnection is available 
06-30 13:55:38.577  3234  3289 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
06-30 13:55:38.577  3234  3289 D BtConfig.SecureMode: isSecureModeOn:false
,06-30 13:55:38.577  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
06-30 13:55:38.577  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,06-30 13:55:38.577  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-30 13:55:38.577  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
06-30 13:55:38.577  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,06-30 13:55:38.577  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
06-30 13:55:38.577  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,06-30 13:55:38.577  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
06-30 13:55:38.587  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 13:55:38.587  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
,06-30 13:55:38.587  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-30 13:55:38.587  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
06-30 13:55:38.587  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:38.587  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
,06-30 13:55:38.587  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 13:55:38.587  3234  3289 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
06-30 13:55:38.587   754   754 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:38.587   754   754 I InputMethodManagerService: [BT Setting State] State =11
06-30 13:55:38.587  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
06-30 13:55:38.587  3234  3289 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,06-30 13:55:38.587  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
06-30 13:55:38.587  3234  3289 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
06-30 13:55:38.587  1757  1757 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,06-30 13:55:38.587  4615  4615 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:38.587  7606  7606 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:38.587  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
06-30 13:55:38.587  1189  1189 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,06-30 13:55:38.587  3234  3289 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
06-30 13:55:38.587  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
06-30 13:55:38.587  3234  3289 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,06-30 13:55:38.587  3234  3289 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
06-30 13:55:38.587  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
06-30 13:55:38.587  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-30 13:55:38.587  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,06-30 13:55:38.587  1189  1189 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:38.587   754  1421 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
06-30 13:55:38.587  1627  1627 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,06-30 13:55:38.597  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,06-30 13:55:38.597   754  1246 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,06-30 13:55:38.597   754  1652 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 13:55:38.597   754  1652 D ActivityManager: caller:android.app.ApplicationThreadProxy@bd936bb, r.packageName :com.android.bluetooth
06-30 13:55:38.597  1189  1189 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,06-30 13:55:38.597  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
06-30 13:55:38.597  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
06-30 13:55:38.597  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,06-30 13:55:38.597  3234  3234 D HeadsetService: Received start request. Starting profile...
06-30 13:55:38.597  3234  3234 D HeadsetStateMachine: make
06-30 13:55:38.597   754  1571 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:38.597   754  1571 D ActivityManager: caller:android.app.ApplicationThreadProxy@33360731, r.packageName :com.android.bluetooth
,06-30 13:55:38.597  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
06-30 13:55:38.597  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 13:55:38.597  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,06-30 13:55:38.607  3234  3234 E HeadsetStateMachine: # of Max HF connection is 2
,06-30 13:55:38.607  4615  4615 D BluetoothNotiBroadcastReceiver: onReceive
,06-30 13:55:38.607   754  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 13:55:38.607   754  1544 D ActivityManager: caller:android.app.ApplicationThreadProxy@45a8397, r.packageName :com.android.bluetooth
,06-30 13:55:38.607   754  1476 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,06-30 13:55:38.607  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
06-30 13:55:38.607  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 13:55:38.607  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,06-30 13:55:38.617  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
,06-30 13:55:38.617  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 13:55:38.617  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 13:55:38.617  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 13:55:38.617  1189  1189 D QSpanel : label top:23
06-30 13:55:38.617  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 13:55:38.617  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 13:55:38.617  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
,06-30 13:55:38.617  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 13:55:38.617  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 13:55:38.617  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 13:55:38.617   754  1246 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,06-30 13:55:38.617   754  1357 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:38.617  3234  3234 I bluedroid: get_profile_interface handsfree
06-30 13:55:38.617   754  1357 D ActivityManager: caller:android.app.ApplicationThreadProxy@ba56b69, r.packageName :com.android.bluetooth
,06-30 13:55:38.617  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
06-30 13:55:38.617  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-30 13:55:38.617  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,06-30 13:55:38.617  3234  3234 E DualScoManager: Dual Sco Manager already instantiated
06-30 13:55:38.617   754  1343 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:38.617  3234  3234 I DualScoManager: Set HeadsetServiceHelper
06-30 13:55:38.617   754  1343 D ActivityManager: caller:android.app.ApplicationThreadProxy@27c44e8f, r.packageName :com.android.bluetooth
06-30 13:55:38.617  3234  3234 D BluetoothAtMessage: createCMTIContentObservers
,06-30 13:55:38.617   754  1652 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
06-30 13:55:38.617   754  1652 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 13:55:38.617   754  1652 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 13:55:38.617   754  1652 D SettingsProvider: selectionArgs: false
06-30 13:55:38.617   754  1652 D SettingsProvider: selectionArgs: 1002
06-30 13:55:38.617   754  1652 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 13:55:38.617  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
06-30 13:55:38.617  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:55:38.617  3234  3289 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,06-30 13:55:38.617   754  1652 D SettingsProvider: ret = -1
06-30 13:55:38.627   754   781 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:38.627   754   781 D ActivityManager: caller:android.app.ApplicationThreadProxy@f205525, r.packageName :com.android.bluetooth
,06-30 13:55:38.627  3234  7978 D HeadsetStateMachine: Enter Disconnected: -2
,06-30 13:55:38.627  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
06-30 13:55:38.627  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 13:55:38.627  3234  3289 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
06-30 13:55:38.627  3234  7978 E HeadsetStateMachine: set to mRemoteBrsf = 0
06-30 13:55:38.627   754  1571 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 13:55:38.627   754  1571 D ActivityManager: caller:android.app.ApplicationThreadProxy@39648c6, r.packageName :com.android.bluetooth
06-30 13:55:38.627  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:38.627  3234  3234 D A2dpService: Received start request. Starting profile...
06-30 13:55:38.627  3234  3234 V Avrcp   : make
06-30 13:55:38.627  3234  3234 V Avrcp   : Avrcp
06-30 13:55:38.627  3234  3234 I bluedroid: get_profile_interface avrcp
06-30 13:55:38.627  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
06-30 13:55:38.627  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
06-30 13:55:38.627  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
06-30 13:55:38.627  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
06-30 13:55:38.627  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
06-30 13:55:38.627  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
06-30 13:55:38.627  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
06-30 13:55:38.627  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
06-30 13:55:38.627  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
06-30 13:55:38.627  3234  3289 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
06-30 13:55:38.627  3234  3289 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
06-30 13:55:38.627  3234  3289 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
06-30 13:55:38.627  3234  7978 D HeadsetStateMachine: map size, before remove : 0
06-30 13:55:38.627  3234  3289 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
06-30 13:55:38.627  3234  7978 D HeadsetStateMachine: map size, after remove: 0
06-30 13:55:38.627  3234  7978 D HeadsetStateMachine: mNextConnectingDevice : null
06-30 13:55:38.627  3234  3234 V Avrcp   : start
,06-30 13:55:38.627  3234  3234 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,06-30 13:55:38.627  3234  3234 V Avrcp   : ++registerMediaPlayers++
,06-30 13:55:38.627  3234  3234 I Avrcp   : No of Audio players :: 2
06-30 13:55:38.627  3234  3234 I Avrcp   : App Package name is com.google.android.music
,06-30 13:55:38.627  3234  3234 I Avrcp   : App pkg name is Google Play Music
06-30 13:55:38.627  3234  3234 I Avrcp   : Name::Google Play Music
06-30 13:55:38.627  3234  3234 V Avrcp   : MediaPlayerInfo: mPlayerId=1
06-30 13:55:38.627  3234  3234 I Avrcp   : App Package name is com.sec.android.app.music
,06-30 13:55:38.627  3234  3234 I Avrcp   : App pkg name is Music
06-30 13:55:38.627  3234  3234 I Avrcp   : Name::Music
06-30 13:55:38.627  3234  3234 V Avrcp   : MediaPlayerInfo: mPlayerId=2
06-30 13:55:38.627  3234  3234 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,06-30 13:55:38.637  3234  3234 I Avrcp   : No of Video players :: 1
06-30 13:55:38.637  3234  3234 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,06-30 13:55:38.637  3234  3234 I Avrcp   : Video App pkg name is Video Player
06-30 13:55:38.637  3234  3234 I Avrcp   : Name::Video Player
06-30 13:55:38.637  3234  3234 V Avrcp   : MediaPlayerInfo: mPlayerId=3
06-30 13:55:38.637  3234  3234 I Avrcp   : Add tempPlayer
06-30 13:55:38.637  3234  3234 V Avrcp   : MediaPlayerInfo: mPlayerId=4
06-30 13:55:38.637  3234  3234 I Avrcp   : Total no of players: 4
06-30 13:55:38.637  3234  3234 V Avrcp   : swapping the samsung player with 1st player
06-30 13:55:38.637  3234  3234 I Avrcp   :  Updating now playing list upon AVRCP Start
,06-30 13:55:38.637  3234  7979 V Avrcp   : handleMessage, msg=207
06-30 13:55:38.637  3234  7979 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,06-30 13:55:38.637  3234  3234 D A2dpStateMachine: make
,06-30 13:55:38.637  3234  3234 I bluedroid: get_profile_interface a2dp
,06-30 13:55:38.637  3234  7981 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
06-30 13:55:38.637  3234  3234 E bt-btif : warning : media task started media_task_refcnt 1 
06-30 13:55:38.637  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
06-30 13:55:38.637  3234  7980 D A2dpStateMachine: Enter Disconnected: -2
,06-30 13:55:38.637  3234  3234 D HeadsetStateMachine: Try to query the phonestate on bind
06-30 13:55:38.637  1404  1437 I Telecom : BluetoothPhoneService: queryPhoneState
,06-30 13:55:38.637  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,06-30 13:55:38.637  3234  3234 D HidService: Received start request. Starting profile...
06-30 13:55:38.637  3234  3234 I bluedroid: get_profile_interface hidhost
06-30 13:55:38.637  3234  3234 D HidService: setHidService(): set to: null
06-30 13:55:38.637  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
06-30 13:55:38.637  3234  3234 D HeadsetStateMachine: Proxy object connected
06-30 13:55:38.637  3234  3234 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
06-30 13:55:38.637  3234  3234 D HeadsetPhoneState: sendDeviceDataStateChanged
06-30 13:55:38.637  3234  7978 D HeadsetStateMachine: Disconnected process message: 11
06-30 13:55:38.637  3234  7978 D HeadsetStateMachine: Disconnected process message: 18
,06-30 13:55:38.637  3234  3234 D HeadsetPhoneState: Signal level : previous=0 curr=2
06-30 13:55:38.637  3234  3234 D HealthService: Received start request. Starting profile...
,06-30 13:55:38.647  3234  3234 I bluedroid: get_profile_interface health
,06-30 13:55:38.647  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:38.647  3234  3234 D PanService: Received start request. Starting profile...
06-30 13:55:38.647  3234  3234 D BluetoothPanServiceJni: initializeNative(L110): pan
06-30 13:55:38.647  3234  3234 I bluedroid: get_profile_interface pan
06-30 13:55:38.647  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:38.647  3234  3234 D BluetoothMapService: Received start request. Starting profile...
,06-30 13:55:38.647  3234  7979 D BluetoothMediaBrowser: no now playing list
06-30 13:55:38.647  3234  7979 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
06-30 13:55:38.647  3234  7979 D Avrcp   :  checkNowPlayingList start
,06-30 13:55:38.657  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
06-30 13:55:38.657  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:55:38.657  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
06-30 13:55:38.657  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
06-30 13:55:38.657  3234  7978 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-30 13:55:38.657  3234  7978 D HeadsetStateMachine: Disconnected process message: 11
06-30 13:55:38.657  3234  3234 D SapService: Received start request. Starting profile...
06-30 13:55:38.657  3234  3234 D BluetoothSAPServiceJni: initializeNative(L209): sap
06-30 13:55:38.657  3234  3234 I bluedroid: get_profile_interface sap
06-30 13:55:38.657  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
06-30 13:55:38.657  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
06-30 13:55:38.657  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
06-30 13:55:38.657  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
06-30 13:55:38.657  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,06-30 13:55:38.667  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
06-30 13:55:38.667  3234  3234 E BluetoothAdapterService(950758963): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,06-30 13:55:38.667  3234  3289 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
06-30 13:55:38.667  3234  3289 I bluedroid: enable
,06-30 13:55:38.667  3234  3292 E bt-btif : Calling BTA_HhEnable
06-30 13:55:38.667  3234  3292 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
06-30 13:55:38.667  3234  3292 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
06-30 13:55:38.667  3234  3292 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
06-30 13:55:38.667  3234  3292 D BluetoothAdapterProperties: Address is:B0:C5:59:2A:28:2D
06-30 13:55:38.667  3234  3292 E BluetoothServiceJni: populateRssiValuesNative
06-30 13:55:38.667  3234  3292 I bluedroid: getModelRssiValues
06-30 13:55:38.667  3234  3292 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
06-30 13:55:38.667  3234  3292 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
06-30 13:55:38.667  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.667  3234  3295 D bt_upio : proc btwrite assertion
,06-30 13:55:38.667  3234  3292 D BluetoothAdapterProperties: Name is: Galaxy Note3
06-30 13:55:38.667   754   754 D SettingsProvider: name = bluetooth_name
06-30 13:55:38.667  3234  3292 D BluetoothAdapterProperties: Scan Mode:20
06-30 13:55:38.667  3234  3292 D BluetoothAdapterProperties: Discoverable Timeout:120
06-30 13:55:38.677  3234  3292 D BluetoothAdapterProperties: LE Address is:F0:8B:B2:54:50:5A
06-30 13:55:38.677  3234  3292 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
06-30 13:55:38.677  3234  3292 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,06-30 13:55:38.677  3234  3292 E bt-btif : btif_sock_init: !radio_req && !rfc_init
06-30 13:55:38.677  3234  3292 E bt-btif : JVenable fails
06-30 13:55:38.677  3234  3292 D bte_conf: Device ID record 1 : primary
06-30 13:55:38.677  3234  3292 D bte_conf:   vendorId            = 0075
06-30 13:55:38.677  3234  3292 D bte_conf:   vendorIdSource      = 0001
06-30 13:55:38.677  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.677  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.677  3234  3292 D bte_conf:   product             = 0100
06-30 13:55:38.677  3234  3292 D bte_conf:   version             = 0200
06-30 13:55:38.677  3234  3292 D bte_conf:   clientExecutableURL = 
06-30 13:55:38.677  3234  3292 D bte_conf:   serviceDescription  = 
06-30 13:55:38.677  3234  3292 D bte_conf:   documentationURL    = 
06-30 13:55:38.677  3234  3292 D bte_conf: bte_load_did_conf no section named DID2.
,06-30 13:55:38.677  3234  3292 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
06-30 13:55:38.677  3234  3289 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
06-30 13:55:38.677  3234  3289 D BluetoothAdapterProperties: ScanMode =  20
06-30 13:55:38.677  3234  3289 D BluetoothAdapterProperties: State =  11
06-30 13:55:38.677  3234  3292 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
06-30 13:55:38.677   754  1584 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
06-30 13:55:38.677  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:38.677  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.677  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.677  3234  3289 D BluetoothAdapterProperties: Setting state to 12
06-30 13:55:38.677  3234  3289 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,06-30 13:55:38.677  3234  3292 D BluetoothAdapterProperties: Scan Mode:21
06-30 13:55:38.677  3234  3292 D BluetoothAdapterProperties: Discoverable Timeout:120
06-30 13:55:38.677   754  1544 D SettingsProvider: name = bluetooth_a2dp_sink_mode
06-30 13:55:38.677   754  1544 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 13:55:38.677   754  1544 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 13:55:38.677   754  1544 D SettingsProvider: selectionArgs: false
06-30 13:55:38.677   754  1544 D SettingsProvider: selectionArgs: 1002
06-30 13:55:38.677   754  1544 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 13:55:38.677   754  1544 D SettingsProvider: ret = -1
06-30 13:55:38.677  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.677  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:38.677  3234  3289 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-30 13:55:38.677  3234  3289 D BluetoothAdapterService: updateAdapterState state is 12
,06-30 13:55:38.677   754   783 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:38.677   754   783 D ActivityManager: caller:android.app.ApplicationThreadProxy@179bf97f, r.packageName :com.android.bluetooth
06-30 13:55:38.677  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.677  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.677  3234  3289 D BluetoothAdapterService: Autoconnection is available 
06-30 13:55:38.677  3234  3289 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
06-30 13:55:38.677  3234  3289 D BluetoothAdapterService: starting service from this receiver
,06-30 13:55:38.677  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.677  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:38.677   754  1357 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:38.677   754  1357 D ActivityManager: caller:android.app.ApplicationThreadProxy@3749d195, r.packageName :com.android.bluetooth
,06-30 13:55:38.677  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.677  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.677  3234  3234 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
06-30 13:55:38.677  3234  3234 I BluetoothPbapService: Handler(): got msg=1
,06-30 13:55:38.677   754  1144 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
06-30 13:55:38.677  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.677  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.687  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.687  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.687  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:38.687  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:38.687  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:38.687  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:38.687  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:38.687  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:38.687  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:38.687  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 13:55:38.687  3234  3289 I BluetoothAdapterState: Entering On State from state = 11
06-30 13:55:38.687   754  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
06-30 13:55:38.687  3234  7986 V BluetoothPbapService: PBAP Service initSocket try: 0
,06-30 13:55:38.687  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.687  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:38.687  4615  4627 E BluetoothHeadset: BluetoothHeadset service is binded
,06-30 13:55:38.687  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.687  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.687  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.687  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.687   754  1044 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
06-30 13:55:38.687  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.687  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.687  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.687  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.687  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.687  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:38.687  7447  7447 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:55:38.687  3234  7986 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-30 13:55:38.687  7606  7617 E BluetoothHeadset: BluetoothHeadset service is binded
06-30 13:55:38.687  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.687  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:38.687  3387  3397 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-30 13:55:38.687  3234  7986 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
,06-30 13:55:38.687  3234  7986 D BluetoothSocket: bindListen(), new LocalSocket 
06-30 13:55:38.687  3234  7986 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
06-30 13:55:38.697  3234  7986 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@5ac00b
06-30 13:55:38.697  3234  7986 D BluetoothSocket: channel: 19
06-30 13:55:38.697  3234  7986 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
06-30 13:55:38.697  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.697  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.697  4615  4615 D HeadsetProfile: Bluetooth service connected
,06-30 13:55:38.697  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.697  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.697   754  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,06-30 13:55:38.697  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.697  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.697  3387  3387 D BluetoothA2dp: Proxy object connected
06-30 13:55:38.697   754  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,06-30 13:55:38.697  1404  1420 E BluetoothHeadset: BluetoothHeadset service is binded
,06-30 13:55:38.697  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.697  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:38.697  4615  4634 D Bluetoothsap: onBluetoothStateChange: up=true
06-30 13:55:38.697  4615  4634 D Bluetoothsap: Binding service...
,06-30 13:55:38.697  4615  4634 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,06-30 13:55:38.697  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.697  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.697   754  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
06-30 13:55:38.697  4615  4634 D Bluetoothsap: bindService called to Bluetooth SAP Service
,06-30 13:55:38.697  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.697  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.707  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.707  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.707  4615  4615 D Bluetoothsap: BluetoothSAP Proxy object connected
06-30 13:55:38.707  4615  4615 D SapProfile: Bluetooth service connected
06-30 13:55:38.707  4615  4615 D Bluetoothsap: getConnectedDevices()
,06-30 13:55:38.707  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.707  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.707  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.707  3234  3295 D bt_upio : BT_WAKE is asserted already
,06-30 13:55:38.717   754  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,06-30 13:55:38.717  3387  7835 E BluetoothHeadset: BluetoothHeadset service is binded
06-30 13:55:38.717   754  1044 D BluetoothPan: Binding service...
,06-30 13:55:38.717   754  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,06-30 13:55:38.717   754   754 D BluetoothPan: BluetoothPAN Proxy object connected
,06-30 13:55:38.717   754  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,06-30 13:55:38.717  1404  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,06-30 13:55:38.717  3234  3243 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-30 13:55:38.717   754  1044 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,06-30 13:55:38.717  3234  3234 D BluetoothA2dp: Proxy object connected
06-30 13:55:38.717   754  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
06-30 13:55:38.717  3234  3234 D BluetoothAdapterService: Bluetooth A2dp source service connected
,06-30 13:55:38.717   754  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
06-30 13:55:38.717   754   754 D BluetoothA2dp: Proxy object connected
,06-30 13:55:38.717  4615  4627 D BluetoothMap: onBluetoothStateChange: up=true
,06-30 13:55:38.727   754  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,06-30 13:55:38.727  4615  4634 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-30 13:55:38.727   754  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,06-30 13:55:38.727  4615  4615 D BluetoothMap: Proxy object connected
06-30 13:55:38.727  4615  4615 D MapProfile: Bluetooth service connected
,06-30 13:55:38.727  4615  4615 D BluetoothA2dp: Proxy object connected
06-30 13:55:38.727  4615  4615 D A2dpProfile: Bluetooth service connected
,06-30 13:55:38.727   754  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,06-30 13:55:38.727  1425  2125 E BluetoothHeadset: BluetoothHeadset service is binded
,06-30 13:55:38.727  4615  6107 D BluetoothPan: Binding service...
,06-30 13:55:38.727   754  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
06-30 13:55:38.727  4615  4615 D BluetoothPan: BluetoothPAN Proxy object connected
,06-30 13:55:38.727  4615  4615 D PanProfile: Bluetooth service connected
06-30 13:55:38.727   754  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
06-30 13:55:38.727   754  1044 E BluetoothHeadset: BluetoothHeadset service is binded
06-30 13:55:38.727  4615  4634 D BluetoothPbap: onBluetoothStateChange: up=true
,06-30 13:55:38.727   754  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,06-30 13:55:38.737  4615  4627 D BluetoothInputDevice: onBluetoothStateChange: up=true
,06-30 13:55:38.737  4615  4615 D BluetoothPbap: Proxy object connected
06-30 13:55:38.737  4615  4615 D PbapServerProfile: Bluetooth service connected
,06-30 13:55:38.737   754  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,06-30 13:55:38.737  4615  4615 D BluetoothInputDevice: Proxy object connected
,06-30 13:55:38.737  4615  4615 D HidProfile: Bluetooth service connected
06-30 13:55:38.737   754  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,06-30 13:55:38.737  1404  1420 E BluetoothHeadset: BluetoothHeadset service is binded
06-30 13:55:38.737   754  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,06-30 13:55:38.737   754   754 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:38.737   754   754 I InputMethodManagerService: [BT Setting State] State =12
06-30 13:55:38.737   754   754 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,06-30 13:55:38.737  1189  1189 D BluetoothTile:  onBluetoothStateChange:
,06-30 13:55:38.737  4615  4615 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:38.737  1757  1757 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
06-30 13:55:38.737  7606  7606 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:38.737  1404  1404 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3edd9605, true
,06-30 13:55:38.747  1404  1404 D BluetoothHeadset: registerMessageListener
06-30 13:55:38.747  1189  1189 D BluetoothTile:  onBluetoothPairedDevicesChanged:
06-30 13:55:38.747  1189  1189 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:38.747  4615  4615 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
06-30 13:55:38.747  4615  4615 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,06-30 13:55:38.757  3234  3246 D HeadsetService: registerMessageListener
,06-30 13:55:38.757  3234  3246 D HeadsetService: registerMessageListener
06-30 13:55:38.757  3234  7978 D HeadsetStateMachine: Disconnected process message: 70
06-30 13:55:38.757  3234  7978 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@20a94ee8
06-30 13:55:38.757  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,06-30 13:55:38.757  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
06-30 13:55:38.757  3234  7988 D BluetoothMapMasInstance: set MAP SDP message type : 1
,06-30 13:55:38.757  3234  7978 D HeadsetStateMachine: Disconnected process message: 9
06-30 13:55:38.757  3234  7978 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,06-30 13:55:38.757   308   667 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
06-30 13:55:38.757   308   667 V voice   : voice_set_parameters: enter: A2dpSuspended=false
06-30 13:55:38.757   308   667 V voice   : voice_set_parameters: exit with code(-2)
06-30 13:55:38.757   308   667 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
06-30 13:55:38.757   308   667 V msm8974_platform: platform_set_parameters: exit with code(-2)
06-30 13:55:38.757   308   667 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
06-30 13:55:38.757   754  1476 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
06-30 13:55:38.757   308   667 V audio_hw_primary: adev_set_parameters: exit
,06-30 13:55:38.757  3234  7988 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-30 13:55:38.757  3234  7978 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
06-30 13:55:38.757   754  1144 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,06-30 13:55:38.757  3234  7988 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
06-30 13:55:38.757  3234  7988 D BluetoothSocket: bindListen(), new LocalSocket 
06-30 13:55:38.757  3234  7988 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
06-30 13:55:38.757  3234  7988 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d917901
06-30 13:55:38.757  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.757  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:38.757  3234  7988 D BluetoothSocket: channel: 5
,06-30 13:55:38.757  1189  1189 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
06-30 13:55:38.757  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,06-30 13:55:38.757  1189  1608 D BluetoothTile:  handleUpdatestate:false name:null
06-30 13:55:38.757  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
06-30 13:55:38.757   754  1571 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
06-30 13:55:38.757   754  1571 D ActivityManager: caller:android.app.ApplicationThreadProxy@386bd461, r.packageName :com.android.settings
,06-30 13:55:38.767  1627  1627 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,06-30 13:55:38.767  4615  4615 D DockEventReceiver: finishStartingService: stopping service
,06-30 13:55:38.767  4615  4615 D BluetoothNotiBroadcastReceiver: onReceive
,06-30 13:55:38.767  3234  3234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ab6e33
,06-30 13:55:38.767  3234  3234 D BtConfig.SecureMode: isSecureModeOn:false
,06-30 13:55:38.767   754  1570 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 13:55:38.777   754  1570 D ActivityManager: caller:android.app.ApplicationThreadProxy@3d3a8c47, r.packageName :com.android.bluetooth
,06-30 13:55:38.777   754   783 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,06-30 13:55:38.777  7447  7506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:38.777  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:38.777  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:38.777  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:38.777  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:38.777  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:38.777  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:38.777  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 13:55:38.787  7447  7506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:55:38.787  7447  7506 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:55:38.787  7447  7506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:55:38.787  7447  7506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:55:38.787  7447  7506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:55:38.787  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee86b04 removed from the list
,06-30 13:55:38.787  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:55:38.787  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32a8f8ed added. We now have 2 listener(s)
06-30 13:55:38.787  7447  7506 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 13:55:38.787  7447  7506 I WifiManager: packageName : com.test.thalitest
,06-30 13:55:38.787   754  1584 D SecContentProvider: uri = 18 selection = isWifiEnabled
06-30 13:55:38.787   754  1584 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
06-30 13:55:38.787   754  1584 D SecContentProvider2: mCursor = null
,06-30 13:55:38.787   754  1584 D WifiService: setWifiEnabled: false pid=7447, uid=10079
06-30 13:55:38.787   754  1584 D SettingsProvider: name = wifi_on
,06-30 13:55:38.787  3234  7993 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-30 13:55:38.787  3234  7993 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[83]}
06-30 13:55:38.787  3234  7993 D BluetoothSocket: bindListen(), new LocalSocket 
06-30 13:55:38.787  3234  7993 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
06-30 13:55:38.787  3234  3295 D bt_vendor: op for 7
06-30 13:55:38.787  3234  3295 D bt_upio : BT_WAKE is asserted already
06-30 13:55:38.787  3234  7993 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c1ba43d
06-30 13:55:38.787  3234  7993 D BluetoothSocket: channel: 12
06-30 13:55:38.787  3234  7993 I BtOppRfcommListener: Accept thread started.
,06-30 13:55:38.797  7447  7506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:55:38.797  7447  7506 I WifiManager: packageName : com.test.thalitest
06-30 13:55:38.797   754  1553 D SecContentProvider: uri = 18 selection = isWifiEnabled
06-30 13:55:38.797   754  1553 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
06-30 13:55:38.797   754  1553 D SecContentProvider2: mCursor = null
,06-30 13:55:38.797   754  1553 D WifiService: setWifiEnabled: true pid=7447, uid=10079
,06-30 13:55:38.797   754  1553 W ActivityManager: Permission Denial: getCurrentUser() from pid=7447, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
06-30 13:55:38.797   754  1553 W WifiService: Failed getting userId using ActivityManagerNative
06-30 13:55:38.797   754  1553 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7447, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
06-30 13:55:38.797   754  1553 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
06-30 13:55:38.797   754  1553 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
06-30 13:55:38.797   754  1553 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
06-30 13:55:38.797   754  1553 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
06-30 13:55:38.797   754  1553 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,06-30 13:55:38.797   754  1553 D SettingsProvider: name = wifi_on
,06-30 13:55:38.797   754  1149 E WifiHW  : ##################### set firmware type 0 #####################
,06-30 13:55:38.797   295  1063 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,06-30 13:55:38.807   295  1063 I WifiHW  : module is semco
06-30 13:55:38.807   295  1063 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
06-30 13:55:38.807   295  1063 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
06-30 13:55:38.807   295  1063 E WifiHW  : TEMP_FAILURE_RETRY complete
06-30 13:55:38.807   295  1063 D SoftapController: Softap fwReload - Ok
,06-30 13:55:38.807   295  1063 D CommandListener: Setting iface cfg
06-30 13:55:38.807   295  1063 D CommandListener: Trying to bring down wlan0
,06-30 13:55:38.807   295  1063 D CommandListener: Clearing all IP addresses on wlan0
06-30 13:55:38.807  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 13:55:38.807  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 13:55:38.807  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 13:55:38.807  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
,06-30 13:55:38.807  1189  1189 D QSpanel : label top:23
06-30 13:55:38.807  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 13:55:38.807  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 13:55:38.807  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 13:55:38.807  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 13:55:38.807  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 13:55:38.807  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 13:55:38.807   754  1149 E WifiHW  : supplicant_name : p2p_supplicant
,06-30 13:55:38.837  7997  7997 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
06-30 13:55:38.837  7997  7997 I wpa_supplicant: Successfully initialized wpa_supplicant
,06-30 13:55:38.837  7997  7997 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
06-30 13:55:38.837  7997  7997 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,06-30 13:55:38.847   359   359 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7997
06-30 13:55:38.847   359   359 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
06-30 13:55:38.847  7997  7997 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
06-30 13:55:38.847  7997  7997 I wpa_supplicant: ssSupport state is = 1
,06-30 13:55:38.847  7997  7997 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,06-30 13:55:38.847  7997  7997 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,06-30 13:55:38.847   359   359 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7997
06-30 13:55:38.847   359   359 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,06-30 13:55:38.907   754  1149 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,06-30 13:55:38.907   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:38.907   754  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
06-30 13:55:38.907  4615  4615 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:38.917  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:55:38.917  5780  5780 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,06-30 13:55:38.917  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 13:55:38.917  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:38.917  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,06-30 13:55:38.917  1189  1189 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-30 13:55:38.917  1189  1189 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
06-30 13:55:38.917  1189  1189 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:38.917  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,06-30 13:55:38.917  1189  1189 D HotspotTile: onReceive : 2, 0
,06-30 13:55:38.917   754  1378 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:38.917  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State = 1
06-30 13:55:38.917  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-30 13:55:38.917  7516  7516 D SecurityLogAgent: StateMachine : Current State = 1
06-30 13:55:38.917  7516  7516 D SecurityLogAgent: StateMachine : Changed Current State = 1
,06-30 13:55:38.937  1189  1189 D QSpanel : label top:23
06-30 13:55:38.937  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 13:55:38.937  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 13:55:38.937  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 13:55:38.937  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 13:55:38.937  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 13:55:38.937  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 13:55:38.937  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 13:55:38.937  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
06-30 13:55:38.937  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 13:55:38.937  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 13:55:39.117   359   359 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,06-30 13:55:39.367  7997  7997 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,06-30 13:55:39.387  7997  7997 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
06-30 13:55:39.387  7997  7997 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
06-30 13:55:39.387   359   359 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 7997
06-30 13:55:39.387   359   359 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
06-30 13:55:39.387  7997  7997 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
06-30 13:55:39.387  7997  7997 I wpa_supplicant: ssSupport state is = 1
06-30 13:55:39.387  7997  7997 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 13:55:39.387  7997  7997 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 13:55:39.387  7997  7997 E wpa_supplicant: SIM READ ERROR
06-30 13:55:39.387  7997  7997 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 13:55:39.387  7997  7997 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 13:55:39.387  7997  7997 E wpa_supplicant: SIM READ ERROR
06-30 13:55:39.387  7997  7997 I wpa_supplicant: Blacklist: Clear (all) 
06-30 13:55:39.387  7997  7997 I wpa_supplicant: wpa_default_ap_write_once
06-30 13:55:39.387  7997  7997 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
06-30 13:55:39.387  7997  7997 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 13:55:39.387  7997  7997 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
06-30 13:55:39.387  7997  7997 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 13:55:39.387  7997  7997 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 13:55:39.387  7997  7997 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-30 13:55:39.557  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
,06-30 13:55:39.557  7447  7514 I jxcore-log: 
,06-30 13:55:39.567  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,06-30 13:55:39.567  7447  7514 I jxcore-log: 
,06-30 13:55:39.577  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
,06-30 13:55:39.577  7447  7514 I jxcore-log: 
,06-30 13:55:39.737  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
06-30 13:55:39.737  7447  7514 I jxcore-log: ,
,06-30 13:55:39.817  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-30 13:55:39.817  7447  7514 I jxcore-log: 
,06-30 13:55:39.877  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-30 13:55:39.877  7447  7514 I jxcore-log: 
,06-30 13:55:39.877  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-30 13:55:39.877  7447  7514 I jxcore-log: 
,06-30 13:55:40.057   754  1152 E Tethering: No numeric data
,06-30 13:55:40.057   754  1152 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,06-30 13:55:40.057   754  1146 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:40.057   754  1146 V NetworkStats: performPollLocked(flags=0x1)
,06-30 13:55:40.057   754  1146 D NetworkStatsFactory: UpdateStatsForKnox
06-30 13:55:40.057   754  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:40.067  1189  1189 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
06-30 13:55:40.067  1189  1189 D HotspotTile: updateTetherState():false, false
,06-30 13:55:40.067   754  1146 V NetworkStats: performPollLocked() took 4ms
06-30 13:55:40.067   754  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 13:55:40.067   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 13:55:40.067   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 13:55:40.067  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
06-30 13:55:40.067  7447  7514 I jxcore-log: 
,06-30 13:55:40.087  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-30 13:55:40.087  7447  7514 I jxcore-log: 
,06-30 13:55:40.097  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-30 13:55:40.097  7447  7514 I jxcore-log: 
,06-30 13:55:40.097  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-30 13:55:40.097  7447  7514 I jxcore-log: 
,06-30 13:55:40.107  7997  7997 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,06-30 13:55:40.117  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-30 13:55:40.117  7447  7514 I jxcore-log: 
,06-30 13:55:40.127  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-30 13:55:40.127  7447  7514 I jxcore-log: 
,06-30 13:55:40.147  7997  7997 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,06-30 13:55:40.147  7997  7997 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
06-30 13:55:40.147  7997  7997 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,06-30 13:55:40.147   359   359 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 7997
06-30 13:55:40.147   359   359 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,06-30 13:55:40.147  7997  7997 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
06-30 13:55:40.147  7997  7997 I wpa_supplicant: ssSupport state is = 1
,06-30 13:55:40.147  7997  7997 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
06-30 13:55:40.147  7997  7997 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,06-30 13:55:40.147   359   359 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 7997
06-30 13:55:40.147   359   359 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
06-30 13:55:40.147  7997  7997 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
06-30 13:55:40.147  7997  7997 I wpa_supplicant: ssSupport state is = 1
06-30 13:55:40.147  7997  7997 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 13:55:40.147  7997  7997 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 13:55:40.157  7997  7997 E wpa_supplicant: SIM READ ERROR
,06-30 13:55:40.157  7997  7997 I wpa_supplicant: wpa_default_ap_write_once
06-30 13:55:40.157  7997  7997 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
06-30 13:55:40.157  7997  7997 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-30 13:55:40.187  7997  7997 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
06-30 13:55:40.187  7997  7997 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,06-30 13:55:40.217  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
06-30 13:55:40.217  7447  7514 I jxcore-log: 
,06-30 13:55:40.217  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
06-30 13:55:40.217  7447  7514 I jxcore-log: 
,06-30 13:55:40.227  7997  7997 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
06-30 13:55:40.227  7997  7997 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
06-30 13:55:40.227  7997  7997 I wpa_supplicant: Skip scan - bUseNetwork false
,06-30 13:55:40.227   754  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,06-30 13:55:40.227   754  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
06-30 13:55:40.227  7997  7997 I wpa_supplicant: HOTSPOT20_ENABLE called
06-30 13:55:40.227  7997  7997 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 13:55:40.227  7997  7997 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 13:55:40.227  7997  7997 E wpa_supplicant: SIM READ ERROR
06-30 13:55:40.227  7997  7997 I wpa_supplicant: Blacklist: Clear (all) 
,06-30 13:55:40.247  7447  7514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
06-30 13:55:40.247  7447  7514 I jxcore-log: 
06-30 13:55:40.247  7997  7997 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,06-30 13:55:40.247  7997  7997 I wpa_supplicant: Skip scan - bUseNetwork false
,06-30 13:55:40.257   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:40.257   754  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,06-30 13:55:40.257   754  1149 D WifiConfigStore: Loading config and enabling all networks 
,06-30 13:55:40.257   754  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
06-30 13:55:40.257  7447  7514 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,06-30 13:55:40.257  7447  7514 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
06-30 13:55:40.257  7447  7514 I jxcore-log: 
06-30 13:55:40.257  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 13:55:40.257  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:40.257  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,06-30 13:55:40.257  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,06-30 13:55:40.267  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:40.267  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:40.267  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:40.267  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:40.267  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:40.267  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:40.267  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:40.267  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:40.267  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:40.267  4615  4615 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:40.267   754  1149 E WifiConfigStore: Not a HS20
06-30 13:55:40.267  7447  7447 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:55:40.267  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,06-30 13:55:40.267  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:40.267  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,06-30 13:55:40.267  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:40.267   754  1149 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,06-30 13:55:40.267  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,06-30 13:55:40.277  1189  1189 D StatusBar.NetworkController: applyOpen
06-30 13:55:40.277  5780  5780 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
06-30 13:55:40.277  1189  1189 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:40.277  1189  1189 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
06-30 13:55:40.277  1189  1189 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-30 13:55:40.277  1189  1608 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
06-30 13:55:40.277   754  1149 D WifiNative-HAL: callSECApiInt - ID [65]
,06-30 13:55:40.277  1189  1189 D HotspotTile: onReceive : 3, 0
,06-30 13:55:40.277   754  1246 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:40.277  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State = 1
06-30 13:55:40.277  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-30 13:55:40.277  7516  7516 D SecurityLogAgent: StateMachine : Current State = 1
06-30 13:55:40.277  7516  7516 D SecurityLogAgent: StateMachine : Changed Current State = 1
,06-30 13:55:40.287   754  1149 D WifiNative-HAL: callSECApiBoolean - ID [13]
06-30 13:55:40.287  7997  7997 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
06-30 13:55:40.287  7997  7997 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,06-30 13:55:40.287  7997  7997 I wpa_supplicant: reset timer : RESET_TIMER 0
06-30 13:55:40.287  7997  7997 I wpa_supplicant: P2P: Current p2p state = IDLE
06-30 13:55:40.287  7997  7997 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
06-30 13:55:40.287  7997  7997 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
06-30 13:55:40.287  7997  7997 I wpa_supplicant: First Scan Start
,06-30 13:55:40.287  7997  7997 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,06-30 13:55:40.287   754  1149 D WifiNative-HAL: Setting external_sim to 1
06-30 13:55:40.287  7647  7647 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 13:55:40.287   754  1149 D WifiStateMachine: Setting OUI to DA-A1-19
06-30 13:55:40.287   754  1149 I WifiNative-HAL: startHal
06-30 13:55:40.287   754  1149 E wifi    : getStaticLongField sWifiHalHandle 0x939bd86c
06-30 13:55:40.287   754  1149 D wifi    : halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x302542
06-30 13:55:40.287   754  1149 I WifiNative-HAL: Could not start hal
,06-30 13:55:40.287  3234  3295 D bt_vendor: op for 7
,06-30 13:55:40.297  1189  1189 D QSpanel : label top:23
,06-30 13:55:40.297  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
06-30 13:55:40.297  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
06-30 13:55:40.297  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
06-30 13:55:40.297  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
06-30 13:55:40.297  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
06-30 13:55:40.297  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
06-30 13:55:40.297  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
06-30 13:55:40.297  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
,06-30 13:55:40.297  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
06-30 13:55:40.297  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,06-30 13:55:40.307   754  1149 E native  : do suspend true
,06-30 13:55:40.307   754  1148 D WifiP2pService: P2pDisabledState{ what=131203 }
06-30 13:55:40.307   754  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,06-30 13:55:40.307   754   754 D WifiScanningService: SCAN_AVAILABLE : 3
06-30 13:55:40.307   754   754 D RttService: SCAN_AVAILABLE : 3
06-30 13:55:40.307   754  1167 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:40.307   754  1167 I WifiNative-HAL: startHal
06-30 13:55:40.307   754  1167 E wifi    : getStaticLongField sWifiHalHandle 0x9ae6899c
06-30 13:55:40.307   754  1167 D wifi    : halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x102546
06-30 13:55:40.307   754  1167 I WifiNative-HAL: Could not start hal
06-30 13:55:40.307   754  1167 E WifiScanningService: could not start HAL
06-30 13:55:40.307   754  1168 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:40.307   295  1063 D CommandListener: Setting iface cfg
06-30 13:55:40.307   295  1063 D CommandListener: Trying to bring up p2p0
,06-30 13:55:40.307   754  1148 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
06-30 13:55:40.307   754  1148 D WifiP2pService: P2pEnablingState
06-30 13:55:40.307   754  1148 D WifiP2pService: P2pEnablingState{ what=147457 }
06-30 13:55:40.307   754  1148 D WifiP2pService: P2p socket connection successful
06-30 13:55:40.307   754  1148 D WifiP2pService: P2pEnabledState
,06-30 13:55:40.307   754  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,06-30 13:55:40.307   754  1151 E ConnectivityService: updateNetworkInfo()
06-30 13:55:40.307   754  1149 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
06-30 13:55:40.307   754  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
06-30 13:55:40.307   754  1149 D WifiNative-HAL: callSECStringApiVoid - ID [215]
06-30 13:55:40.307   754  1149 E WifiNative-HAL: invaild command id : 215
06-30 13:55:40.317   754  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
06-30 13:55:40.317   754  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
06-30 13:55:40.317   754  1045 D WifiDisplayController: disconnect
06-30 13:55:40.317   754  1045 D WifiDisplayController: updateConnection
06-30 13:55:40.317   754  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
06-30 13:55:40.317   754  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:40.317   754  1045 D WifiDisplayAdapter: onP2pDisconnected
06-30 13:55:40.317   754  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
06-30 13:55:40.317   754  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
06-30 13:55:40.317   754  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-30 13:55:40.317   754   754 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
06-30 13:55:40.317   754  1148 D WifiNative-HAL: p2pGetDeviceAddress
,06-30 13:55:40.317   754  1148 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:d7:fd:2b
06-30 13:55:40.317  7631  7631 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,06-30 13:55:40.317   754  1148 D WifiP2pService: DeviceAddress: ea:fd:2b
06-30 13:55:40.317   754  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy Note3
06-30 13:55:40.317   754  1045 D WifiDisplayController:  deviceAddress: ea:50:8b:d7:fd:2b
06-30 13:55:40.317   754  1045 D WifiDisplayController:  primary type: 10-0050F204-5
06-30 13:55:40.317   754  1045 D WifiDisplayController:  secondary type: null
06-30 13:55:40.317   754  1045 D WifiDisplayController:  wps: 0
06-30 13:55:40.317   754  1045 D WifiDisplayController:  grpcapab: 0
06-30 13:55:40.317   754  1045 D WifiDisplayController:  devcapab: 0
06-30 13:55:40.317   754  1045 D WifiDisplayController:  status: 3
06-30 13:55:40.317   754  1045 D WifiDisplayController:  wfdInfo: null
06-30 13:55:40.317   754  1045 D WifiDisplayController:  groupownerAddress: null
06-30 13:55:40.317   754  1045 D WifiDisplayController:  GOdeviceName: null
06-30 13:55:40.317   754  1045 D WifiDisplayController:  interfaceAddress: 
06-30 13:55:40.317   754  1045 D WifiDisplayController:  SConnectInfo : null
,06-30 13:55:40.317  1189  1189 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
06-30 13:55:40.317   754  1343 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-30 13:55:40.317  1189  1189 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,06-30 13:55:40.317  4615  4615 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
06-30 13:55:40.317  4615  4615 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,06-30 13:55:40.317   754  1421 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:40.317  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
06-30 13:55:40.317   754  1697 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:40.317  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
06-30 13:55:40.317  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,06-30 13:55:40.317  4615  4615 I NearbySettings: MountReceiver.onReceive - Set preference state off
06-30 13:55:40.327  4615  4727 V NearbySettings: MountReceiver.mPrefHandler - 7002
,06-30 13:55:40.327  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-30 13:55:40.327  7447  7514 I jxcore-log: 
06-30 13:55:40.327  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-30 13:55:40.327  7447  7514 I jxcore-log: 
,06-30 13:55:40.327  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.327  7447  7514 I jxcore-log: 
,06-30 13:55:40.327  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.327  7447  7514 I jxcore-log: 
06-30 13:55:40.327  6536  6536 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,06-30 13:55:40.327  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-30 13:55:40.327  7447  7514 I jxcore-log: 
,06-30 13:55:40.327  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-30 13:55:40.327  7447  7514 I jxcore-log: 
,06-30 13:55:40.327  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.327  7447  7514 I jxcore-log: 
,06-30 13:55:40.327  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.327  7447  7514 I jxcore-log: 
06-30 13:55:40.327  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.327  7447  7514 I jxcore-log: 
,06-30 13:55:40.327   754  1148 D WifiP2pService: sending p2p persistent groups changed broadcast
06-30 13:55:40.327   754  1148 D WifiP2pService: InactiveState
06-30 13:55:40.327  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.327  7447  7514 I jxcore-log: 
06-30 13:55:40.327   754  1148 D WifiP2pService: InactiveState{ what=143376 }
,06-30 13:55:40.327  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.327  7447  7514 I jxcore-log: 
06-30 13:55:40.327   754  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
06-30 13:55:40.327  7631  7631 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
06-30 13:55:40.327  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.327  7447  7514 I jxcore-log: 
06-30 13:55:40.337  7631  7631 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,06-30 13:55:40.337  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.337  7447  7514 I jxcore-log: 
06-30 13:55:40.337  7631  7631 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
06-30 13:55:40.337  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.337  7447  7514 I jxcore-log: 
,06-30 13:55:40.337  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
06-30 13:55:40.337  7447  7514 I jxcore-log: 
06-30 13:55:40.337  7631  7631 D WifiDirectBR: stopServiceTest : false
,06-30 13:55:40.357  7997  7997 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,06-30 13:55:40.357  7997  7997 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,06-30 13:55:40.357   754  1148 D WifiP2pService: InactiveState{ what=143376 }
,06-30 13:55:40.357   754  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
,06-30 13:55:40.387  7997  7997 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,06-30 13:55:40.387   754  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 13:55:40.387   754  1149 D SecContentProvider2: mCursor = null
,06-30 13:55:40.387   754  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 13:55:40.387   754  1149 D SecContentProvider2: mCursor = null
,06-30 13:55:40.417  7447  7506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:40.417  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:40.417  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:40.417  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:40.417  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:40.417  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:40.417  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:40.417  7447  7506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 13:55:40.417  7447  7506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:55:40.417  7447  7506 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:55:40.417  7447  7506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:55:40.417  7447  7506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:55:40.417  7447  7506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:55:40.417  7447  7506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32a8f8ed removed from the list
,06-30 13:55:40.417  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
06-30 13:55:40.417  7447  7514 I jxcore-log: 
,06-30 13:55:40.417  7447  7506 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,06-30 13:55:40.417  7447  7506 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
06-30 13:55:40.417  7447  7506 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
06-30 13:55:40.417  7447  7506 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
06-30 13:55:40.417  7447  7506 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
06-30 13:55:40.417  7447  7506 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,06-30 13:55:40.427  7447  7506 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
06-30 13:55:40.427  7447  7506 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,06-30 13:55:40.427  7447  7506 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,06-30 13:55:40.427  7447  7506 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
06-30 13:55:40.427  7447  7506 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
06-30 13:55:40.427  7447  7506 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
06-30 13:55:40.427  7447  7506 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
06-30 13:55:40.427  7447  7506 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,06-30 13:55:40.427  7447  7506 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
06-30 13:55:40.427  7447  7506 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
06-30 13:55:40.427  7447  7506 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
06-30 13:55:40.427  7447  7506 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
06-30 13:55:40.427  7447  7506 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
06-30 13:55:40.427  7447  7506 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
06-30 13:55:40.427  7447  7506 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,06-30 13:55:40.427  7447  7506 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,06-30 13:55:40.427  7447  7506 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@32ac4a23 Bundle[{}]
,06-30 13:55:40.427  7447  7506 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 13:55:40.427  7447  7506 I io.jxcore.node.LifeCycleMonitor: stop: OK
,06-30 13:55:40.437  7447  7506 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
06-30 13:55:40.437  7447  7506 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,06-30 13:55:40.437  7447  7506 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,06-30 13:55:40.437  7447  7506 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,06-30 13:55:40.447  7447  8003 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1276, name: My test thread name)
,06-30 13:55:40.447  7447  8003 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1276, thread name: My test thread name)
06-30 13:55:40.447  7447  8003 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1276, name: My test thread name)
,06-30 13:55:40.447  7447  8004 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1278, name: My test thread name)
,06-30 13:55:40.447  7447  8004 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1278, thread name: My test thread name)
06-30 13:55:40.447  7447  8004 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1278, name: My test thread name)
,06-30 13:55:40.457  7447  7506 E THALI UNIT TEST: Total number of executed tests: 36
06-30 13:55:40.457  7447  7506 E THALI UNIT TEST: Number of passed tests: 36
06-30 13:55:40.457  7447  7506 E THALI UNIT TEST: Number of failed tests:  0
,06-30 13:55:40.457  7447  7506 E THALI UNIT TEST: Number of ignored tests: 0
06-30 13:55:40.457  7447  7506 E THALI UNIT TEST: Total duration: 8155 ms
06-30 13:55:40.457  7447  7506 I System.out: Tests succeded_00
06-30 13:55:40.457  7447  7506 W PluginManager: THREAD WARNING: exec() call to JXcore.Test blocked the main thread for 8206ms. Plugin should use CordovaInterface.getThreadPool().
,06-30 13:55:40.497   302   302 E SMD     : DCD ON
,06-30 13:55:40.667  3234  3425 D bt_upio : ..proc_btwrite_timeout..
,06-30 13:55:40.807   343   343 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 13:55:40.807   343   343 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 13:55:41.047  7997  7997 I wpa_supplicant: nl80211: Received scan results (15 BSSes)
,06-30 13:55:41.047  7997  7997 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,06-30 13:55:41.047  7997  7997 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
06-30 13:55:41.047  7997  7997 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,06-30 13:55:41.047  7997  7997 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,06-30 13:55:41.067   754  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 13:55:41.067   754  1149 D SecContentProvider2: mCursor = null
,06-30 13:55:41.117  7997  7997 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,06-30 13:55:41.117  7997  7997 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,06-30 13:55:41.117  7997  7997 I wpa_supplicant: Associated with F4.99.3E
06-30 13:55:41.117  7997  7997 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
06-30 13:55:41.117  7997  7997 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,06-30 13:55:41.127   754  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 13:55:41.127   754  1149 D SecContentProvider2: mCursor = null
,06-30 13:55:41.127   754  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 13:55:41.127   754  1149 D SecContentProvider2: mCursor = null
,06-30 13:55:41.137  7997  7997 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,06-30 13:55:41.137  7997  7997 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
06-30 13:55:41.137  7997  7997 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,06-30 13:55:41.137  7997  7997 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-30 13:55:41.137  7997  7997 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
06-30 13:55:41.147  7997  7997 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,06-30 13:55:41.147  7997  7997 I wpa_supplicant: Blacklist: Clear (temp) 
06-30 13:55:41.147  7997  7997 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,06-30 13:55:41.147   754  1149 D WifiNative-HAL: callSECApiVoid - ID [50]
,06-30 13:55:41.157   754  1149 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
06-30 13:55:41.157   754  1151 D ConnectivityService: Got NetworkAgent Messenger
06-30 13:55:41.157   754  1151 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
06-30 13:55:41.157   754  1151 E ConnectivityService: updateNetworkInfo()
06-30 13:55:41.157   754  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 13:55:41.157   754  1151 D ConnectivityService: NetworkAgent connected
06-30 13:55:41.157   754  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,06-30 13:55:41.157  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 13:55:41.157  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:41.157  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,06-30 13:55:41.167   754  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,06-30 13:55:41.177   295  1063 D CommandListener: Setting iface cfg
,06-30 13:55:41.177  4615  4615 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
06-30 13:55:41.177  4615  4615 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,06-30 13:55:41.177   754   783 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:41.177  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,06-30 13:55:41.177   754  1584 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:41.177   754  1149 E WifiStateMachine: Start Dhcp Watchdog 2
06-30 13:55:41.177  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
06-30 13:55:41.177  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
06-30 13:55:41.177  4615  4615 I NearbySettings: MountReceiver.onReceive - Set preference state off
,06-30 13:55:41.177  4615  4727 V NearbySettings: MountReceiver.mPrefHandler - 7002
,06-30 13:55:41.177   754  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 13:55:41.187   754  1149 D SecContentProvider2: mCursor = null
,06-30 13:55:41.187  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 13:55:41.187  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:41.187  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,06-30 13:55:41.197   754  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,06-30 13:55:41.197   754  1144 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:41.197  5780  5780 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,06-30 13:55:41.267   754  1149 E native  : do suspend false
,06-30 13:55:41.277   754  1148 D WifiP2pService: InactiveState{ what=143375 }
06-30 13:55:41.277   754  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-30 13:55:41.277   754  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 13:55:41.277   754  1149 D SecContentProvider2: mCursor = null
,06-30 13:55:41.497  8009  8009 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,06-30 13:55:41.497  8009  8009 I dhcpcd  : version 5.5.6 starting
,06-30 13:55:41.497  8009  8009 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,06-30 13:55:41.627  8009  8009 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-30 13:55:41.627  8009  8009 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
06-30 13:55:41.627  8009  8009 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
06-30 13:55:41.627  8009  8009 I dhcpcd  : bssid match
06-30 13:55:41.627  8009  8009 I dhcpcd  : wlan0: rebinding lease of 192.168.1.119
,06-30 13:55:41.657  8009  8009 I dhcpcd  : wlan0: acknowledged 192.168.1.119 from 192.168.1.1
,06-30 13:55:41.667  8009  8009 I dhcpcd  : wlan0: leased 192.168.1.119 for 172800 seconds
,06-30 13:55:41.667   754  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,06-30 13:55:41.827   754  1357 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,06-30 13:55:41.847  7876  7897 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,06-30 13:55:41.897   754  3297 D SSRM:n  : SIOP:: AP = 380, PST = 327, CUR = 450
,06-30 13:55:41.907   754  1007 W ProcessCpuTracker: Skipping unknown process pid 8028
,06-30 13:55:41.907   754  1007 W ProcessCpuTracker: Skipping unknown process pid 8035
,06-30 13:55:41.917  3234  3290 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,06-30 13:55:42.087   754  1149 E native  : do suspend true
,06-30 13:55:42.087   754  1148 D WifiP2pService: InactiveState{ what=143375 }
,06-30 13:55:42.097   754  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-30 13:55:42.097   754  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,06-30 13:55:42.097   754  1149 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
06-30 13:55:42.097   754  1149 E WifiStateMachine: VerifyingLinkState enter
,06-30 13:55:42.097  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 13:55:42.097  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:42.097  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
06-30 13:55:42.097   754  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,06-30 13:55:42.097   754  1151 E ConnectivityService: updateNetworkInfo()
06-30 13:55:42.097   754  1151 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 13:55:42.097   754  1151 D ConnectivityService: Adding iface wlan0 to network 503
,06-30 13:55:42.107   754  1162 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,06-30 13:55:42.107   754  1162 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 13:55:42.107   754  1162 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 13:55:42.107   754  1162 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,06-30 13:55:42.107   754  1162 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,06-30 13:55:42.117  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 13:55:42.117  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:42.117  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,06-30 13:55:42.117   754  1149 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,06-30 13:55:42.117   754  1149 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,06-30 13:55:42.117   754   754 I WifiTrafficPoller: evaluateTrafficStatsPolling
,06-30 13:55:42.137  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 13:55:42.137  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:42.137  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,06-30 13:55:42.137   754  1151 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,06-30 13:55:42.137   754  1151 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,06-30 13:55:42.137   754  1151 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
06-30 13:55:42.137   754  1151 E ConnectivityService: Unexpected mtu value: 0, wlan0
06-30 13:55:42.137   754  1151 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
06-30 13:55:42.137   754  1151 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.119
,06-30 13:55:42.147   295  1063 V         : QcRouteController
,06-30 13:55:42.147   754   754 I WifiTrafficPoller: evaluateTrafficStatsPolling
,06-30 13:55:42.147   754   754 I WifiTrafficPoller: mBoosterFLAG : 0
06-30 13:55:42.147   754   754 I WifiTrafficPoller: current booster mode : FullMode
,06-30 13:55:42.147   754   754 D WifiNative-HAL: callSECApiVoid - ID [212]
,06-30 13:55:42.157  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,06-30 13:55:42.157  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,06-30 13:55:42.157  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,06-30 13:55:42.157  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:42.157  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:42.157  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:42.157  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:42.157  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:42.167  4615  4615 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,06-30 13:55:42.167  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,06-30 13:55:42.167  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:42.167   295  1063 V         : QcRouteController
,06-30 13:55:42.167  4615  4615 I NearbySettings: MountReceiver.onReceive - Keep current state
,06-30 13:55:42.187   754  1343 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.187   295  1063 V         : QcRouteController
,06-30 13:55:42.187  5780  5780 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,06-30 13:55:42.207  4615  4615 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,06-30 13:55:42.207  4615  4615 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,06-30 13:55:42.207   754  1144 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.207   295  1063 V         : QcRouteController
06-30 13:55:42.207  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,06-30 13:55:42.207   754  1571 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.207  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,06-30 13:55:42.207  4615  4615 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,06-30 13:55:42.207  4615  4615 I NearbySettings: MountReceiver.onReceive - Set preference state off
,06-30 13:55:42.217  4615  4727 V NearbySettings: MountReceiver.mPrefHandler - 7002
,06-30 13:55:42.217   754  1378 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.217  5780  5780 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,06-30 13:55:42.237   295  1063 V         : QcRouteController
,06-30 13:55:42.237  4615  4615 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,06-30 13:55:42.237  4615  4615 I NearbySettings: MountReceiver.onReceive - Keep current state
,06-30 13:55:42.237   754  1553 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,06-30 13:55:42.247   754  1357 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.247  5780  5780 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
06-30 13:55:42.247   295  1063 V         : QcRouteController
,06-30 13:55:42.247   295  1063 V         : QcRouteController
,06-30 13:55:42.257   266   266 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,06-30 13:55:42.267   295  1063 V         : QcRouteController
,06-30 13:55:42.267   754  1476 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=754
,06-30 13:55:42.297   754  1151 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,06-30 13:55:42.297   754  1151 D ConnectivityService: LTETest block dns file not exists
,06-30 13:55:42.297   754  1151 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
06-30 13:55:42.297   754  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
06-30 13:55:42.297   754  1151 D ConnectivityService: calling update connectivity
,06-30 13:55:42.297   754  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
06-30 13:55:42.297   754  1151 E ConnectivityService: updateNetworkInfo()
,06-30 13:55:42.297   754  1044 D EntConnectivity: Not allowed due to - mEnabled false
06-30 13:55:42.297   754  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
,06-30 13:55:42.297   754  1151 E ConnectivityService: updateNetworkInfo()
06-30 13:55:42.297   754  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 13:55:42.297   754  1151 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
06-30 13:55:42.297   754  1151 D ConnectivityService: calling update connectivity
,06-30 13:55:42.297   754  1151 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
06-30 13:55:42.297   754  8005 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:42.297   754  8005 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
06-30 13:55:42.297   754  8005 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:42.297   754  8005 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
06-30 13:55:42.297   754  1151 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 13:55:42.297   754  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,06-30 13:55:42.297   754  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 13:55:42.297   754  8005 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:55:42.307   754  1151 D ConnectivityService: currentScore = 0, newScore = 60
06-30 13:55:42.307   754  1151 D ConnectivityService:    accepting network in place of null
06-30 13:55:42.307   754  1151 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 13:55:42.307  1425  1425 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 13:55:42.307   754  1151 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,06-30 13:55:42.307   754  1151 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
06-30 13:55:42.307   754  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,06-30 13:55:42.307   754  1151 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:42.307   754  1152 D Tethering: MasterInitialState.processMessage what=3
06-30 13:55:42.307   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
06-30 13:55:42.307   754  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
06-30 13:55:42.307   754  1153 D SmartBondingService: getSBEnabled() enabled =false
06-30 13:55:42.307   754  1153 D SmartBondingService: getSBEnabled() enabled =false
06-30 13:55:42.307   754  1153 D SmartBondingService: getSBEnabled() enabled =false
,06-30 13:55:42.307   754  1151 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
06-30 13:55:42.307   754  1146 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:42.307   754  1146 V NetworkStats: updateIfacesLocked()
06-30 13:55:42.307   754  1146 V NetworkStats: performPollLocked(flags=0x1)
06-30 13:55:42.307   754  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,06-30 13:55:42.307   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:42.307   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:42.307   754  1146 D NetworkStatsFactory: UpdateStatsForKnox
06-30 13:55:42.307   754  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.307   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:42.307   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:42.307   754  1147 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
06-30 13:55:42.307   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:42.307   754  1151 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
06-30 13:55:42.307   754  1044 D EntConnectivity: Not allowed due to - mEnabled false
06-30 13:55:42.307   754  1151 D ConnectivityService: calling update connectivity
06-30 13:55:42.307   754  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:42.307  1189  1189 D StatusBar.NetworkController: getUpdateDataNetType(): 0
06-30 13:55:42.307   754  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:42.307  1189  1189 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
06-30 13:55:42.307   754  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:42.307  1189  1189 D StatusBar.NetworkController: updateDataNetType()
,06-30 13:55:42.317   754  1146 V NetworkStats: performPollLocked() took 4ms
06-30 13:55:42.317   754  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 13:55:42.317   754  1570 I AudioService: getStreamVolume 3 index 70
,06-30 13:55:42.317  1189  1604 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,06-30 13:55:42.317   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:55:42.317   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 13:55:42.317  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
06-30 13:55:42.317  1189  1189 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,06-30 13:55:42.327   754  1544 D SecContentProvider2: uri = 14 selection = getSealedState
06-30 13:55:42.327   754  1544 D SecContentProvider2: mCursor = null
,06-30 13:55:42.327   754  1357 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
,06-30 13:55:42.327   754  1357 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
06-30 13:55:42.327  1189  1189 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
06-30 13:55:42.327  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte
,06-30 13:55:42.327  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=2
06-30 13:55:42.327  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_2 mContentDescriptionPhoneSignal = Two bars of phone signal
06-30 13:55:42.327  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:42.327  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,06-30 13:55:42.327  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:42.327  1189  1189 D StatusBar.NetworkController: applyOpen
06-30 13:55:42.327  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:42.327  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:42.327  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:42.327  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:42.327  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
06-30 13:55:42.327  1189  1189 D StatusBar.NetworkController: applyOpen
,06-30 13:55:42.327  1189  1189 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,06-30 13:55:42.327  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
06-30 13:55:42.327  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
,06-30 13:55:42.327  1189  1189 I PhoneStatusBar: Icon Only
06-30 13:55:42.327  1189  1189 I StatusBar: Icon Only
,06-30 13:55:42.327  1189  1189 D PanelView: There is/are notification(s) 
,06-30 13:55:42.337  1189  1189 D PanelView: There is/are notification(s) 
,06-30 13:55:42.387   754  8005 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 13:55:42.457   754  8005 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 30 Jun 2016 11:55:42 GMT], X-Android-Received-Millis=[1467287742467], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467287742434]}
,06-30 13:55:42.457   754  8005 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
06-30 13:55:42.457   754  8005 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
06-30 13:55:42.457   754  1151 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
06-30 13:55:42.457   754  1151 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
06-30 13:55:42.457   754  1151 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 13:55:42.457   754  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:42.457   754  1151 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
06-30 13:55:42.457   754  1151 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,06-30 13:55:42.457   754  1151 D ConnectivityService: calling update connectivity
06-30 13:55:42.457   754  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:42.457   754  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,06-30 13:55:42.457   754  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:42.457   754  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
06-30 13:55:42.457  1189  1604 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,06-30 13:55:42.457   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.457  1189  1189 D StatusBar.NetworkController: getUpdateDataNetType(): 0
06-30 13:55:42.457  1189  1189 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
06-30 13:55:42.457  1189  1189 D StatusBar.NetworkController: updateDataNetType()
,06-30 13:55:42.457  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
06-30 13:55:42.457  1189  1189 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,06-30 13:55:42.467   754  1571 D SecContentProvider2: uri = 14 selection = getSealedState
06-30 13:55:42.467   754  1571 D SecContentProvider2: mCursor = null
,06-30 13:55:42.467   754  1544 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
06-30 13:55:42.467   754  1544 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
,06-30 13:55:42.467  1189  1189 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
06-30 13:55:42.467  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte
06-30 13:55:42.467  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=2
06-30 13:55:42.467  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_2 mContentDescriptionPhoneSignal = Two bars of phone signal
,06-30 13:55:42.467  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
06-30 13:55:42.467  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,06-30 13:55:42.477  1189  1189 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,06-30 13:55:42.477  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
,06-30 13:55:42.477  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
06-30 13:55:42.477  1189  1189 I PhoneStatusBar: Icon Only
06-30 13:55:42.477  1189  1189 I StatusBar: Icon Only
,06-30 13:55:42.477  1189  1189 D PanelView: There is/are notification(s) 
,06-30 13:55:42.477  1189  1189 D PanelView: There is/are notification(s) 
,06-30 13:55:42.807   754  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:42.817   754   754 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.817   754  1004 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:42.817   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.817   754   754 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.817   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:42.817   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.817   754   754 D SmartBondingService: SmartBondingReceiver: wifi is connected
06-30 13:55:42.817   754   754 D SmartBondingService: SmartBondingReceiver: wifi ap is not changed
06-30 13:55:42.817   754   754 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.817   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.817   754   754 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:42.817   754  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
06-30 13:55:42.817   754  1153 D SmartBondingService: getSBEnabled() enabled =false
06-30 13:55:42.817   754  1153 D SmartBondingService: getSBEnabled() enabled =false
,06-30 13:55:42.817   754  1153 D SmartBondingService: getSBEnabled() enabled =false
,06-30 13:55:42.827   754  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,06-30 13:55:42.827  7447  7447 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:42.827  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:42.827  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:42.827  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:42.827  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:42.827  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 13:55:42.827  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 13:55:42.827  7447  7447 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-30 13:55:42.827   754   754 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.827  7447  7447 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,06-30 13:55:42.827   754   754 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:42.827   754   754 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.837  7447  7514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-30 13:55:42.837  7447  7514 I jxcore-log: 
,06-30 13:55:42.837   754  1004 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.837   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.847   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:42.847   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:42.847   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.847   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:42.847   754  1144 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.847   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.847   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.847  5271  5271 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-30 13:55:42.847  1490  1490 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,06-30 13:55:42.857   754  1553 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.857  7135  7135 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,06-30 13:55:42.857  7135  7135 I PCWCLIENTTRACE_PushUtil: sales region : global
06-30 13:55:42.857  7135  7135 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
06-30 13:55:42.857  7135  7135 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:42.867   754  1116 V AlarmManager: waitForAlarm result :4
,06-30 13:55:42.877  5271  5271 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,06-30 13:55:42.887  7700  7700 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:42.897  7700  7700 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,06-30 13:55:42.907   754  1004 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.907   754  1571 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:55:42.907   754  1571 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:55:42.907   754  1571 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:55:42.907   754  1571 D BatteryService: stay LED for fully charged
06-30 13:55:42.907   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:55:42.917   754   754 I MotionRecognitionService: Plugged
06-30 13:55:42.917   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:55:42.917  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:55:42.917  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
06-30 13:55:42.917  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:55:42.917  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:55:42.917  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:55:42.917  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:55:42.917  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:55:42.917  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:42.967  7717  7717 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,06-30 13:55:42.977  7717  7717 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,06-30 13:55:42.977  7717  7717 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,06-30 13:55:42.987   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.987   754  1343 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 13:55:42.987   754  1343 D ActivityManager: caller:android.app.ApplicationThreadProxy@1c0daabe, r.packageName :com.google.android.gms
,06-30 13:55:42.987   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.987   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.987   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.997   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.997   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:42.997   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:42.997  2217  2217 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,06-30 13:55:42.997  2217  7736 I iu.UploadsManager: num queued entries: 0
,06-30 13:55:42.997  2217  7736 I iu.UploadsManager: num updated entries: 0
06-30 13:55:42.997  2217  7736 I iu.SyncManager: NEXT; no task
,06-30 13:55:43.007   754  1652 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 13:55:43.007   754  1652 D ActivityManager: caller:android.app.ApplicationThreadProxy@28cbc71f, r.packageName :com.google.android.gms
,06-30 13:55:43.017  2217  2217 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy}
06-30 13:55:43.017  2217  2217 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy} to Chimera receiver impl com.google.android.gms.kids.account.SystemEventReceiver
06-30 13:55:43.017  2217  2217 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,06-30 13:55:43.017   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.017  2217  2217 I Kids    : [GCoreUtils] Current gmscore version, 7571438 is smaller than the required version 8400000
,06-30 13:55:43.017  2602  2602 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,06-30 13:55:43.027  2602  2602 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1467287743037
,06-30 13:55:43.027  2602  2602 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,06-30 13:55:43.027   754  1697 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:43.027   754  1378 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.027  2602  2602 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,06-30 13:55:43.027  2602  2602 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().START
,06-30 13:55:43.027  2602  2602 I KLMS-2.4.511: : NetworkChangeOperations(): uploadRequestLog().START 
,06-30 13:55:43.027  2602  2602 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,06-30 13:55:43.037   754  1584 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.047   754  1697 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,06-30 13:55:43.047   754  1697 D ActivityManager: caller:android.app.ApplicationThreadProxy@24d76835, r.packageName :com.samsung.android.app.galaxyfinder
,06-30 13:55:43.057  7754  7754 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,06-30 13:55:43.077  7168  7168 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,06-30 13:55:43.077   754   781 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.077  3699  8111 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,06-30 13:55:43.077  3699  8111 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,06-30 13:55:43.077  7211  7211 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,06-30 13:55:43.087  3699  8111 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,06-30 13:55:43.087  7211  7211 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
06-30 13:55:43.087  7211  7211 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,06-30 13:55:43.087  7211  7211 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
06-30 13:55:43.087  7211  7211 I SA      : [OR] == isSIMCardReady false ==
,06-30 13:55:43.087   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:43.087  7211  7211 I SA      : [SCU] == networkStateCheck == true
,06-30 13:55:43.087  7211  7211 I SA      : [DM] getCountryCodeFromCSC : PL
06-30 13:55:43.087  7211  7211 I SA      : isChinaCountryCode : false
06-30 13:55:43.087  7211  7211 I SA      : [SCU] is ChinestModel Data Restricted   : false
,06-30 13:55:43.087  7211  7211 I SA      : [OR] == networkStateCheck true ==
,06-30 13:55:43.087  7211  7211 I SA      : [OR] GetMyCountryZoneTask
,06-30 13:55:43.087  7211  7211 I SA      : [OR] onReceive END
,06-30 13:55:43.097   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.097   754  1553 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,06-30 13:55:43.097   754  1553 D ActivityManager: caller:android.app.ApplicationThreadProxy@206fb63b, r.packageName :com.android.providers.downloads
,06-30 13:55:43.097  7211  8113 I SA      : [SRS] prepareGetMyCountryZone
,06-30 13:55:43.097  7796  7796 I SCloudBackupReceiver: Other Intent
,06-30 13:55:43.097  7841  7841 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,06-30 13:55:43.097  7841  7841 I KnoxUsageLogPro: premStatus:2
,06-30 13:55:43.107  7841  7841 I KnoxUsageLogPro: isEulaShown : false
,06-30 13:55:43.107  7841  7841 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,06-30 13:55:43.107  7211  8113 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,06-30 13:55:43.107  7211  8113 I SA      : [SSP] query invoked
,06-30 13:55:43.117  3699  8111 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,06-30 13:55:43.117  3699  8111 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,06-30 13:55:43.117  3699  8111 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,06-30 13:55:43.127  3699  8111 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,06-30 13:55:43.127  3699  8111 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,06-30 13:55:43.127  3699  8111 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,06-30 13:55:43.127  3699  8111 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,06-30 13:55:43.127   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.127   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.127  3699  8111 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,06-30 13:55:43.137  3699  8111 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,06-30 13:55:43.147   754  1544 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.147  3699  8111 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,06-30 13:55:43.207   754  1584 I art     : Explicit concurrent mark sweep GC freed 63135(3MB) AllocSpace objects, 5(80KB) LOS objects, 30% free, 36MB/52MB, paused 1.389ms total 97.979ms
,06-30 13:55:43.227   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:43.227  7211  8113 I SA      : [TPMU] GetMccFromDB : null
06-30 13:55:43.227  7211  8113 I SA      : [SCU] getMccFromPreferece mcc = 260
,06-30 13:55:43.227  7211  8113 I SA      : [TPM] isNoProxy(default) : true
,06-30 13:55:43.237  7211  8113 E File    : fail readDirectory() errno=2
,06-30 13:55:43.237   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.237   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.247  7934  7934 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:43.247  7934  7934 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
06-30 13:55:43.247  7934  7934 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,06-30 13:55:43.247   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.247   754   783 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.257   754  1246 D RCPManagerService: exchangeData() failure , invalid userId
,06-30 13:55:43.257   754  1652 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:43.257  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,06-30 13:55:43.257  7516  7516 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-30 13:55:43.257  7516  7516 D SecurityLogAgent: StateMachine : Current State = 1
,06-30 13:55:43.257   754  1357 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.257  7516  7516 D SecurityLogAgent: StateMachine : Changed Current State = 1
,06-30 13:55:43.267   754  1571 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.267   754  1553 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.267   754  1570 D ActivityManager: startService callerProcessName:com.sec.android.app.SmartClipService, calleePkgName: com.sec.android.app.SmartClipService
,06-30 13:55:43.267   754  1570 D ActivityManager: caller:android.app.ApplicationThreadProxy@37a49b04, r.packageName :com.sec.android.app.SmartClipService
,06-30 13:55:43.277   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.277  5646  5646 D WaitQueueForNetworkActivate: notifyNetworkActivated
,06-30 13:55:43.277   754  1544 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
06-30 13:55:43.277   754  1544 D ActivityManager: caller:android.app.ApplicationThreadProxy@16968ed, r.packageName :com.sec.android.app.samsungapps
,06-30 13:55:43.287  5646  5646 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,06-30 13:55:43.287  5646  5646 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
06-30 13:55:43.287  5646  5646 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
06-30 13:55:43.287  5646  5646 D InitializeManagerStateMachine: exit::IDLE
06-30 13:55:43.287  5646  5646 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,06-30 13:55:43.287   754  1697 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:43.287   754  1570 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.287  5646  5646 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
06-30 13:55:43.287  5646  5646 D InitializeManagerStateMachine: exit::NETWORK_CHECK
06-30 13:55:43.287  5646  5646 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
06-30 13:55:43.287  5646  5646 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
06-30 13:55:43.287  5646  5646 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
06-30 13:55:43.287  5646  5646 D InitializeManagerStateMachine: entry::SUCCESS
06-30 13:55:43.287  5646  5646 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,06-30 13:55:43.287  5646  5646 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
06-30 13:55:43.287  5646  5646 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,06-30 13:55:43.287   754  1246 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:43.287  5646  5646 D InitializeManagerStateMachine: exit::SUCCESS
06-30 13:55:43.287  5646  5646 D InitializeManagerStateMachine: entry::IDLE
,06-30 13:55:43.297  1627  8116 D GCM     : Connected
,06-30 13:55:43.297   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.307   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.307   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.307   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.307   754  1151 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,06-30 13:55:43.327   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.327  1627  8116 D GCM     : Message class com.google.f.a.a.p
,06-30 13:55:43.327   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.327   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.497   302   302 E SMD     : DCD ON
,06-30 13:55:43.737  7211  8113 I SA      : [RC New] Execute method=[GET] start
,06-30 13:55:43.767  7211  8113 I SA      : [RC New] Security=[true]
,06-30 13:55:43.767  7211  8113 I System.out: Thread-1200(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,06-30 13:55:43.777  7211  8113 I System.out: Thread-1200(ApacheHTTPLog):isShipBuild true
,06-30 13:55:43.777  7211  8113 I System.out: Thread-1200(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,06-30 13:55:44.387  7211  8113 I SA      : [RC New] [v2liruge] api execute + 620
,06-30 13:55:44.387  7211  8113 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,06-30 13:55:44.387  7211  8113 I System.out: AsyncTask #1 calls detatch()
,06-30 13:55:44.397  7211  8113 I SA      : [TPMU] getNetworkMcc : 260
,06-30 13:55:44.417  7211  8113 I SA      : [SCU] saveMccToPreferece Start
,06-30 13:55:44.417  7211  8113 I SA      : [SCU] RegionMCC : 260
06-30 13:55:44.417  7211  8113 I SA      : [SSP] query invoked
,06-30 13:55:44.417  7211  8113 I SA      : [TPMU] GetMccFromDB : null
,06-30 13:55:44.417  7211  8113 I SA      : [SCU] getMccFromPreferece mcc = 260
06-30 13:55:44.417  7211  8113 I SA      : [SCU] saveMccToPreferece End
,06-30 13:55:44.417  7211  8113 I SA      : [RC New] executeRequest [v2liruge] end. 683
,06-30 13:55:44.417  7211  8113 I SA      : [RC New] Execute end
,06-30 13:55:44.427  7211  7211 I SA      : [OR] GetMyCountryZoneTask mcc = 260
,06-30 13:55:44.427  7211  7211 I SA      : [OR] GetMyCountryZoneTask Success
,06-30 13:55:45.137   754  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,06-30 13:55:45.147   754  1151 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,fe80::ea50:8bff:fed7:fd2b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,06-30 13:55:45.147   754  1151 D ConnectivityService: identical MTU - not setting
,06-30 13:55:45.147   754  1151 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
06-30 13:55:45.147   754  1151 D ConnectivityService: updateSourceRoutes : add src route for:fe80::ea50:8bff:fed7:fd2b
,06-30 13:55:45.147   295  1063 V         : QcRouteController
,06-30 13:55:45.147   754   754 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,06-30 13:55:45.147   754   754 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:45.157   754  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,06-30 13:55:45.157   754  1153 D SmartBondingService: getSBEnabled() enabled =false
06-30 13:55:45.157   754  1153 D SmartBondingService: getSBEnabled() enabled =false
,06-30 13:55:45.157   754  1153 D SmartBondingService: getSBEnabled() enabled =false
,06-30 13:55:45.177   295  1063 V         : QcRouteController
,06-30 13:55:45.177   754  1151 W NetworkManagementService: route cmd failed: 
06-30 13:55:45.177   754  1151 W NetworkManagementService: com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '98 route replace src v6 wlan0 fe80::ea50:8bff:fed7:fd2b 2 ::' failed with '400 98 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
06-30 13:55:45.177   754  1151 W NetworkManagementService: '
06-30 13:55:45.177   754  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
06-30 13:55:45.177   754  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
06-30 13:55:45.177   754  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
06-30 13:55:45.177   754  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
06-30 13:55:45.177   754  1151 W NetworkManagementService: 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2844)
06-30 13:55:45.177   754  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5632)
06-30 13:55:45.177   754  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5444)
06-30 13:55:45.177   754  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.access$2400(ConnectivityService.java:230)
06-30 13:55:45.177   754  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2387)
06-30 13:55:45.177   754  1151 W NetworkManagementService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:55:45.177   754  1151 W NetworkManagementService: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:55:45.177   754  1151 W NetworkManagementService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:55:45.177   754  1151 V Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true
06-30 13:55:45.177   754  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
06-30 13:55:45.177   754  1151 D ConnectivityService: calling update connectivity
06-30 13:55:45.177   754  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:45.177   754  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:45.177   754  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,06-30 13:55:45.177  1189  1604 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,06-30 13:55:45.177   754  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,06-30 13:55:45.177   754  1151 D ConnectivityService: calling update connectivity
06-30 13:55:45.177   754  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:45.177   754  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,06-30 13:55:45.177   754  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,06-30 13:55:45.177  1189  1604 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,06-30 13:55:45.517   754  1149 E WifiStateMachine: CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,06-30 13:55:45.767   266   950 I SurfaceFlinger: id=14 Removed Uoast (8/9)
,06-30 13:55:45.767   266   409 I SurfaceFlinger: id=14 Removed Uoast (-2/9)
,06-30 13:55:45.767   754  1246 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=754 (0x0)
,06-30 13:55:45.767   754  1246 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=754, ws=WorkSource{10067}) (elapsedTime=3500)
,06-30 13:55:45.937  8009  8009 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-30 13:55:46.087   754  1584 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,06-30 13:55:46.087   754  1584 D ActivityManager: caller:android.app.ApplicationThreadProxy@1130b1b3, r.packageName :com.sec.spp.push
,06-30 13:55:46.117   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:46.497   302   302 E SMD     : DCD ON
,06-30 13:55:46.847   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:47.317   754  1116 V AlarmManager: waitForAlarm result :4
,06-30 13:55:47.317   754  1116 D ActivityManager: caller:null, r.packageName :com.google.android.googlequicksearchbox
,06-30 13:55:47.357  1490  8138 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,06-30 13:55:47.867  7135  7135 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,06-30 13:55:47.887   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:47.887  7135  8142 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,06-30 13:55:47.907  7135  8142 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,06-30 13:55:47.907  7135  8142 E art     : No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,06-30 13:55:47.907  7135  8142 W PCWCLIENTTRACE_SecurePreferencesJNI: GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,06-30 13:55:47.917  7135  8142 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,06-30 13:55:47.917  7135  8142 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,06-30 13:55:47.917  7135  8142 I PCWCLIENTTRACE_PushUtil: sales region : global
06-30 13:55:47.917  7135  8142 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,06-30 13:55:47.917  7135  8142 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,06-30 13:55:49.507   302   302 E SMD     : DCD ON
,06-30 13:55:49.937  8009  8009 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-30 13:55:51.237   754  1116 V AlarmManager: waitForAlarm result :4
,06-30 13:55:51.247   754  1007 D ActivityManager: startProcessLocked calleePkgName: com.blurb.checkout, hostingType: broadcast
,06-30 13:55:51.257   754  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:51.257   754  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:51.257   754  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:51.267   754  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:55:51.327   754  1007 I ActivityManager: Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8144 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 13:55:51.327  8144  8144 E Zygote  : MountEmulatedStorage()
,06-30 13:55:51.327  8144  8144 E Zygote  : v2
,06-30 13:55:51.327  8144  8144 I libpersona: KNOX_SDCARD checking this for 10096
06-30 13:55:51.327  8144  8144 I libpersona: KNOX_SDCARD not a persona
,06-30 13:55:51.337   336   336 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 293us total 24.416ms
,06-30 13:55:51.347  8144  8144 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:55:51.347  8144  8144 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 13:55:51.347  8144  8144 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,06-30 13:55:51.367   336   336 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 264us total 9.396ms
,06-30 13:55:51.387   336   336 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 263us total 14.439ms
,06-30 13:55:51.397  8144  8144 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:55:51.407  8144  8144 D ActivityThread: Added TimaKeyStore provider
,06-30 13:55:51.417  8144  8144 D ResourcesManager: creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,06-30 13:55:51.427   754  1421 D ActivityManager: startService callerProcessName:com.blurb.checkout, calleePkgName: com.blurb.checkout
,06-30 13:55:51.427   754  1421 D ActivityManager: caller:android.app.ApplicationThreadProxy@2ad2469c, r.packageName :com.blurb.checkout
,06-30 13:55:51.457   754   781 I ActivityManager: Killing 6144:com.sec.android.gallery3d/u0a53 (adj 15): emptyCount ##41
,06-30 13:55:51.947   754  3297 D SSRM:n  : SIOP:: AP = 350, PST = 330, CUR = 450
,06-30 13:55:52.127   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:55:52.507   302   302 E SMD     : DCD ON
,06-30 13:55:52.967   754  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:55:52.967   754  1144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:55:52.967   754  1144 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:55:52.967   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:55:52.977  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:55:52.977  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:55:52.977   754   754 I MotionRecognitionService: Plugged
06-30 13:55:52.977   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:55:52.987   754  1144 D BatteryService: stay LED for fully charged
,06-30 13:55:52.987  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:55:52.987  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:52.987  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:52.997  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:55:52.997  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:55:53.007  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:53.307   754  1343 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,06-30 13:55:53.307   754  1343 D ActivityManager: caller:android.app.ApplicationThreadProxy@94ce47a, r.packageName :com.sec.android.app.samsungapps
,06-30 13:55:53.317  5646  5646 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,06-30 13:55:53.317  5646  5646 D PreloadUpdateManagerStateMachine: exit::IDLE
06-30 13:55:53.317  5646  5646 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,06-30 13:55:53.317  5646  5646 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
06-30 13:55:53.317  5646  5646 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,06-30 13:55:53.317  5646  5646 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,06-30 13:55:53.317  5646  5646 D PreloadUpdateManagerStateMachine: entry::IDLE
,06-30 13:55:53.947  8009  8009 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
06-30 13:55:53.947  8009  8009 I dhcpcd  : wlan0: no IPv6 Routers available
,06-30 13:55:55.497   302   302 E SMD     : DCD ON
,06-30 13:55:55.817   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:55:56.817   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:55:57.817   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:55:58.057   754  1007 I ActivityManager: Waited long enough for: ServiceRecord{1f75b4ca u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,06-30 13:55:58.497   302   302 E SMD     : DCD ON
,06-30 13:55:58.827   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:55:59.827   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:55:59.987   754  1116 V AlarmManager: waitForAlarm result :8
,06-30 13:56:00.817   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-30 13:56:01.497   302   302 E SMD     : DCD ON
,06-30 13:56:01.987   754  3297 D SSRM:n  : SIOP:: AP = 330, PST = 331, CUR = 450
,06-30 13:56:03.017   754  1652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:56:03.017   754  1652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:56:03.027   754  1652 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:56:03.027   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:56:03.037  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:56:03.037  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:56:03.037   754   754 I MotionRecognitionService: Plugged
,06-30 13:56:03.037   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:56:03.037   754  1652 D BatteryService: stay LED for fully charged
,06-30 13:56:03.047  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:03.047  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:56:03.047  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:56:03.047  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:03.047  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:56:03.047  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:04.147   754  1320 E Watchdog: !@Sync 11
,06-30 13:56:04.497   302   302 E SMD     : DCD ON
,06-30 13:56:05.817   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:56:06.827   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:56:07.497   302   302 E SMD     : DCD ON
,06-30 13:56:07.827   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:56:08.827   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:56:09.837   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:56:10.497   302   302 E SMD     : DCD ON
,06-30 13:56:10.827   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 13:56:12.037   754  3297 D SSRM:n  : SIOP:: AP = 330, PST = 332, CUR = 450
,06-30 13:56:12.127   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:56:13.077   754  1246 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:56:13.077   754  1246 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:56:13.087   754  1246 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:56:13.087   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:56:13.087   754   754 I MotionRecognitionService: Plugged
,06-30 13:56:13.087  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:56:13.097  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:56:13.097   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:56:13.097  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:13.097   754  1246 D BatteryService: stay LED for fully charged
,06-30 13:56:13.097  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:13.097  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:13.097  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:56:13.097  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:56:13.097  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:56:13.507   302   302 E SMD     : DCD ON
,06-30 13:56:16.497   302   302 E SMD     : DCD ON
,06-30 13:56:19.517   302   302 E SMD     : DCD ON
,06-30 13:56:20.837   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:56:21.837   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:56:22.087   754  3297 D SSRM:n  : SIOP:: AP = 320, PST = 333, CUR = 450
,06-30 13:56:22.517   302   302 E SMD     : DCD ON
,06-30 13:56:22.837   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:56:23.137   754  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:56:23.137   754  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:56:23.137   754  1476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:56:23.147   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:56:23.147   754   754 I MotionRecognitionService: Plugged
,06-30 13:56:23.147   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:56:23.147   754  1476 D BatteryService: stay LED for fully charged
,06-30 13:56:23.147  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:56:23.157  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:56:23.157  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:56:23.157  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:56:23.157  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:56:23.157  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:23.157  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:23.157  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:23.837   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:56:24.837   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:56:25.507   302   302 E SMD     : DCD ON
,06-30 13:56:25.837   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 13:56:28.507   302   302 E SMD     : DCD ON
,06-30 13:56:29.997   754  1050 I PowerManagerService: [PWL] Off : 330s ago
,06-30 13:56:31.507   302   302 E SMD     : DCD ON
,06-30 13:56:32.137   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:56:32.137   754  3297 D SSRM:n  : SIOP:: AP = 320, PST = 334, CUR = 450
,06-30 13:56:33.197   754   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:56:34.167   754  1320 E Watchdog: !@Sync 12
,06-30 13:56:34.507   302   302 E SMD     : DCD ON
,06-30 13:56:37.507   302   302 E SMD     : DCD ON
,06-30 13:56:40.507   302   302 E SMD     : DCD ON
,06-30 13:56:40.847   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:56:41.847   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:56:42.187   754  3297 D SSRM:n  : SIOP:: AP = 320, PST = 335, CUR = 450
,06-30 13:56:42.837   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:56:43.257   754   783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:56:43.517   302   302 E SMD     : DCD ON
,06-30 13:56:43.837   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:56:44.847   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:56:45.837   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 13:56:46.517   302   302 E SMD     : DCD ON
,06-30 13:56:49.517   302   302 E SMD     : DCD ON
,06-30 13:56:52.137   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:56:52.237   754  3297 D SSRM:n  : SIOP:: AP = 320, PST = 336, CUR = 450
,06-30 13:56:52.527   302   302 E SMD     : DCD ON
,06-30 13:56:53.317   754  1357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:56:53.317   754  1357 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:56:53.327   754  1357 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:56:53.327   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:56:53.327   754   754 I MotionRecognitionService: Plugged
,06-30 13:56:53.327   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:56:53.327   754  1357 D BatteryService: stay LED for fully charged
,06-30 13:56:53.337  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:56:53.337  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:56:53.337  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:53.337  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:53.337  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:56:53.337  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:56:53.337  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:53.337  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:56:55.527   302   302 E SMD     : DCD ON
,06-30 13:56:58.517   302   302 E SMD     : DCD ON
,06-30 13:57:01.527   302   302 E SMD     : DCD ON
,06-30 13:57:02.277   754  3297 D SSRM:n  : SIOP:: AP = 320, PST = 335, CUR = 450
,06-30 13:57:03.377   754  1652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:57:03.377   754  1652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:57:03.377   754  1652 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:57:03.387   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:57:03.387  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:57:03.397  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:57:03.397   754   754 I MotionRecognitionService: Plugged
,06-30 13:57:03.397   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:57:03.397   754  1652 D BatteryService: stay LED for fully charged
,06-30 13:57:03.397  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:03.407  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:03.407  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:57:03.407  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:03.407  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:57:03.407  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:57:04.157   754  1320 E Watchdog: !@Sync 13
,06-30 13:57:04.517   302   302 E SMD     : DCD ON
,06-30 13:57:05.837   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:57:06.847   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:57:07.527   302   302 E SMD     : DCD ON
,06-30 13:57:07.847   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:57:08.847   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:57:09.847   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:57:10.527   302   302 E SMD     : DCD ON
,06-30 13:57:10.847   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 13:57:12.147   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:57:12.327   754  3297 D SSRM:n  : SIOP:: AP = 320, PST = 331, CUR = 450
,06-30 13:57:13.437   754  1571 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:57:13.437   754  1571 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:57:13.437   754  1571 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:57:13.447   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:57:13.447   754   754 I MotionRecognitionService: Plugged
,06-30 13:57:13.447   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:57:13.447   754  1571 D BatteryService: stay LED for fully charged
,06-30 13:57:13.447  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:57:13.447  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:57:13.457  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:57:13.457  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:13.457  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:13.457  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:13.457  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:57:13.457  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:57:13.527   302   302 E SMD     : DCD ON
,06-30 13:57:16.517   302   302 E SMD     : DCD ON
,06-30 13:57:19.527   302   302 E SMD     : DCD ON
,06-30 13:57:22.377   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 324, CUR = 450
,06-30 13:57:22.517   302   302 E SMD     : DCD ON
,06-30 13:57:23.497   754  1378 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:57:25.537   302   302 E SMD     : DCD ON
,06-30 13:57:28.527   302   302 E SMD     : DCD ON
,06-30 13:57:29.997   754  1050 I PowerManagerService: [PWL] Off : 390s ago
,06-30 13:57:31.537   302   302 E SMD     : DCD ON
,06-30 13:57:32.157   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:57:32.427   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 320, CUR = 450
,06-30 13:57:33.557   754  1357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:57:33.557   754  1357 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:57:33.557   754  1357 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:57:33.557   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:57:33.567  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:57:33.567  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:57:33.567   754   754 I MotionRecognitionService: Plugged
06-30 13:57:33.567   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:57:33.567  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:57:33.567   754  1357 D BatteryService: stay LED for fully charged
,06-30 13:57:33.577  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:57:33.577  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:57:33.587  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:33.587  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:57:33.587  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:34.167   754  1320 E Watchdog: !@Sync 14
,06-30 13:57:34.537   302   302 E SMD     : DCD ON
,06-30 13:57:35.847   343   343 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 13:57:35.847   343   343 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 13:57:37.527   302   302 E SMD     : DCD ON
,06-30 13:57:40.537   302   302 E SMD     : DCD ON
,06-30 13:57:42.477   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 318, CUR = 450
,06-30 13:57:43.527   302   302 E SMD     : DCD ON
,06-30 13:57:43.617   754   783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:57:43.617   754   783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:57:43.617   754   783 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:57:43.617   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:57:43.627  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:57:43.627  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:57:43.627   754   754 I MotionRecognitionService: Plugged
06-30 13:57:43.627   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:57:43.627  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:57:43.627   754   783 D BatteryService: stay LED for fully charged
,06-30 13:57:43.637  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:57:43.637  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:57:43.647  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:43.647  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:57:43.647  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:46.537   302   302 E SMD     : DCD ON
,06-30 13:57:49.527   302   302 E SMD     : DCD ON
,06-30 13:57:52.157   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:57:52.527   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 450
,06-30 13:57:52.527   302   302 E SMD     : DCD ON
,06-30 13:57:53.667   754   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:57:53.677   754   781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:57:53.677   754   781 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:57:53.677   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:57:53.687   754   754 I MotionRecognitionService: Plugged
,06-30 13:57:53.687  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:57:53.687  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:57:53.687   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:57:53.687  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:57:53.697  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:57:53.697   754   781 D BatteryService: stay LED for fully charged
,06-30 13:57:53.697  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:57:53.697  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:53.697  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:57:53.697  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:57:55.527   302   302 E SMD     : DCD ON
,06-30 13:57:55.857   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:57:56.857   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:57:57.847   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:57:58.537   302   302 E SMD     : DCD ON
,06-30 13:57:58.847   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:57:59.847   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:00.857   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-30 13:58:01.537   302   302 E SMD     : DCD ON
,06-30 13:58:02.577   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 450
,06-30 13:58:03.737   754  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:58:03.737   754  1421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:58:03.737   754  1421 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:58:03.747   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:58:03.747   754   754 I MotionRecognitionService: Plugged
06-30 13:58:03.747   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:58:03.747   754  1421 D BatteryService: stay LED for fully charged
,06-30 13:58:03.757  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:58:03.757  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:58:03.757  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:58:03.757  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:03.757  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:58:03.757  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:58:03.757  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:58:03.757  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:58:04.167   754  1320 E Watchdog: !@Sync 15
,06-30 13:58:04.537   302   302 E SMD     : DCD ON
,06-30 13:58:05.857   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:06.857   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:07.537   302   302 E SMD     : DCD ON
,06-30 13:58:07.857   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:08.867   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:09.857   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:10.547   302   302 E SMD     : DCD ON
,06-30 13:58:10.857   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 13:58:12.167   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:58:12.627   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 450
,06-30 13:58:13.547   302   302 E SMD     : DCD ON
,06-30 13:58:13.797   754  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:58:13.807   754  1144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:58:13.807   754  1144 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:58:13.807   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:58:13.807   754   754 I MotionRecognitionService: Plugged
,06-30 13:58:13.807   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:58:13.817  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:58:13.817  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:58:13.817  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:58:13.817  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:58:13.817  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:13.817   754  1144 D BatteryService: stay LED for fully charged
,06-30 13:58:13.817  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:13.817  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:58:13.817  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:58:16.547   302   302 E SMD     : DCD ON
,06-30 13:58:19.537   302   302 E SMD     : DCD ON
,06-30 13:58:20.857   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:21.857   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:22.077   339   339 I bootchecker: bootchecker wake up!!
,06-30 13:58:22.547   302   302 E SMD     : DCD ON
,06-30 13:58:22.677   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 450
,06-30 13:58:22.867   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:23.857   754  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:58:23.857   754  1421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:58:23.867   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:23.867   754  1421 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:58:23.867   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:58:23.867   754   754 I MotionRecognitionService: Plugged
06-30 13:58:23.867   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:58:23.877  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:58:23.877  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:58:23.877  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:58:23.877  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:23.877  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:58:23.877  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
06-30 13:58:23.877  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:58:23.877   754  1421 D BatteryService: stay LED for fully charged
06-30 13:58:23.877  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:58:24.867   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:25.547   302   302 E SMD     : DCD ON
,06-30 13:58:25.867   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 13:58:28.537   302   302 E SMD     : DCD ON
,06-30 13:58:31.547   302   302 E SMD     : DCD ON
,06-30 13:58:32.167   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:58:32.727   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 450
,06-30 13:58:33.917   754  1697 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:58:33.927   754  1697 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:58:33.927   754  1697 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 13:58:33.927   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,06-30 13:58:33.927   754   754 I MotionRecognitionService: Plugged
,06-30 13:58:33.927   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:58:33.937  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:58:33.937  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:58:33.937   754  1697 D BatteryService: stay LED for fully charged
,06-30 13:58:33.937  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:58:33.937  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:58:33.937  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:58:33.937  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:58:33.937  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:58:33.937  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:34.167   754  1320 E Watchdog: !@Sync 16
,06-30 13:58:34.547   302   302 E SMD     : DCD ON
,06-30 13:58:35.007   754  1050 I PowerManagerService: [PWL] Off : 455s ago
,06-30 13:58:37.547   302   302 E SMD     : DCD ON
,06-30 13:58:40.547   302   302 E SMD     : DCD ON
,06-30 13:58:40.877   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:41.867   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:42.767   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,06-30 13:58:42.867   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:43.557   302   302 E SMD     : DCD ON
,06-30 13:58:43.867   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:43.977   754  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:58:44.877   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:58:45.877   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 13:58:46.557   302   302 E SMD     : DCD ON
,06-30 13:58:49.557   302   302 E SMD     : DCD ON
,06-30 13:58:52.167   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:58:52.547   302   302 E SMD     : DCD ON
,06-30 13:58:52.817   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 13:58:54.037   754  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:58:54.037   754  1144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:58:54.047   754  1144 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:58:54.047   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:58:54.047   754   754 I MotionRecognitionService: Plugged
,06-30 13:58:54.047   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:58:54.047   754  1144 D BatteryService: stay LED for fully charged
,06-30 13:58:54.057  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:58:54.057  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:58:54.057  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:58:54.057  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:58:54.057  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:54.057  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:54.057  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:58:54.057  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:58:55.547   302   302 E SMD     : DCD ON
,06-30 13:58:58.557   302   302 E SMD     : DCD ON
,06-30 13:58:59.987   754  1116 V AlarmManager: waitForAlarm result :8
,06-30 13:59:00.007  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 13:59:00.007  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:59:00.017  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,06-30 13:59:00.017  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 13:59:00.087  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:59:00.087  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:59:01.557   302   302 E SMD     : DCD ON
,06-30 13:59:02.867   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 13:59:04.097   754   783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:59:04.107   754   783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:59:04.107   754   783 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:59:04.107   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:59:04.107  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:59:04.107  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:59:04.107   754   754 I MotionRecognitionService: Plugged
,06-30 13:59:04.107   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:59:04.117  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:59:04.117  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:59:04.117  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:59:04.117   754   783 D BatteryService: stay LED for fully charged
,06-30 13:59:04.117  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:04.117  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:59:04.117  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:04.167   754  1320 E Watchdog: !@Sync 17
,06-30 13:59:04.557   302   302 E SMD     : DCD ON
,06-30 13:59:05.877   343   343 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 13:59:06.887   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:59:07.547   302   302 E SMD     : DCD ON
,06-30 13:59:07.877   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:59:08.887   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:59:09.877   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:59:10.557   302   302 E SMD     : DCD ON
,06-30 13:59:10.877   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 13:59:12.177   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:59:12.907   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 13:59:13.557   302   302 E SMD     : DCD ON
,06-30 13:59:14.157   754   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:59:14.157   754   781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:59:14.167   754   781 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:59:14.167   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:59:14.167  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:59:14.167  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:59:14.167   754   754 I MotionRecognitionService: Plugged
,06-30 13:59:14.167   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:59:14.177  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:59:14.177  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:14.177  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:59:14.177  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:59:14.177  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:14.177   754   781 D BatteryService: stay LED for fully charged
,06-30 13:59:14.187  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:16.557   302   302 E SMD     : DCD ON
,06-30 13:59:17.027   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:17.027  7568  8184 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,06-30 13:59:17.037  7568  8184 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:59:17.037  7568  8184 I System.out: (HTTPLog)-Static: isShipBuild true
06-30 13:59:17.037  7568  8184 I System.out: (HTTPLog)-Thread-1250-396178269: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
06-30 13:59:17.037  7568  8184 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:59:17.097  7568  8184 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 13:59:17.477  1627  1749 I art     : Explicit concurrent mark sweep GC freed 16121(892KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 18MB/31MB, paused 403us total 22.974ms
,06-30 13:59:17.527   754  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@2f028ecc, r.packageName :com.google.android.gms
,06-30 13:59:17.557   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:17.577   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:17.577   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:17.607   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:17.607   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:17.637  2217  2217 V Herrevad: NQAS connected
,06-30 13:59:17.647   754  1571 D ActivityManager: caller:android.app.ApplicationThreadProxy@bbbfd91, r.packageName :com.google.android.gms
,06-30 13:59:19.557   302   302 E SMD     : DCD ON
,06-30 13:59:21.507   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:22.557   302   302 E SMD     : DCD ON
,06-30 13:59:22.957   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 13:59:24.217   754  1571 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:59:24.227   754  1571 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:59:24.227   754  1571 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:59:24.227   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:59:24.227  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:59:24.227  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:59:24.227   754   754 I MotionRecognitionService: Plugged
06-30 13:59:24.227   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:59:24.237  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:59:24.237  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:59:24.237  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:59:24.237   754  1571 D BatteryService: stay LED for fully charged
,06-30 13:59:24.237  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:24.237  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:59:24.237  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:25.517   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:25.567   302   302 E SMD     : DCD ON
,06-30 13:59:28.567   302   302 E SMD     : DCD ON
,06-30 13:59:29.517   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:31.567   302   302 E SMD     : DCD ON
,06-30 13:59:32.177   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:59:33.007   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 13:59:33.527   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:34.167   754  1320 E Watchdog: !@Sync 18
,06-30 13:59:34.277   754   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:59:34.287   754   781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:59:34.287   754   781 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:59:34.287   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:59:34.287  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:59:34.287  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:59:34.287   754   754 I MotionRecognitionService: Plugged
06-30 13:59:34.287   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:59:34.297  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:59:34.297  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:34.297  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:59:34.297  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:59:34.297   754   781 D BatteryService: stay LED for fully charged
06-30 13:59:34.297  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:34.297  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:34.567   302   302 E SMD     : DCD ON
,06-30 13:59:35.887   343   343 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 13:59:35.887   343   343 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 13:59:37.527   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:37.557   302   302 E SMD     : DCD ON
,06-30 13:59:40.557   302   302 E SMD     : DCD ON
,06-30 13:59:41.527   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:43.057   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 13:59:43.557   302   302 E SMD     : DCD ON
,06-30 13:59:44.337   754  1553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:59:44.347   754  1553 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:59:44.347   754  1553 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:59:44.347   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:59:44.347   754   754 I MotionRecognitionService: Plugged
,06-30 13:59:44.347   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:59:44.357  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:59:44.357  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:59:44.357  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:44.357  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:59:44.357   754  1553 D BatteryService: stay LED for fully charged
,06-30 13:59:44.357  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:59:44.357  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:59:44.357  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:59:44.357  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:59:44.997   754  1050 I PowerManagerService: [PWL] Off : 525s ago
,06-30 13:59:45.537   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:46.557   302   302 E SMD     : DCD ON
,06-30 13:59:49.537   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:49.557   302   302 E SMD     : DCD ON
,06-30 13:59:52.177   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:59:52.567   302   302 E SMD     : DCD ON
,06-30 13:59:53.107   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 13:59:53.547   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:54.397   754  1571 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:59:54.407   754  1571 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:59:54.407   754  1571 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 13:59:54.407   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:59:54.407  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:59:54.407  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:59:54.407   754   754 I MotionRecognitionService: Plugged
06-30 13:59:54.407   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:59:54.417  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:59:54.417   754  1571 D BatteryService: stay LED for fully charged
,06-30 13:59:54.417  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:59:54.417  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:59:54.417  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:59:54.417  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:54.417  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:55.577   302   302 E SMD     : DCD ON
,06-30 13:59:57.547   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:59:58.567   302   302 E SMD     : DCD ON
,06-30 13:59:59.997   754  1116 V AlarmManager: waitForAlarm result :8
,06-30 14:00:00.887   343   343 I Atfwd_Daemon: Stop the daemon....
,06-30 14:00:01.557   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:00:01.577   302   302 E SMD     : DCD ON
,06-30 14:00:03.147   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:00:04.167   754  1320 E Watchdog: !@Sync 19
,06-30 14:00:04.457   754  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:00:04.567   302   302 E SMD     : DCD ON
,06-30 14:00:05.557   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:00:07.567   302   302 E SMD     : DCD ON
,06-30 14:00:09.577   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:00:10.567   302   302 E SMD     : DCD ON
,06-30 14:00:12.177   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 14:00:13.197   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:00:13.567   302   302 E SMD     : DCD ON
,06-30 14:00:13.587   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:00:14.517   754  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:00:14.527   754  1421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:00:14.527   754  1421 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:00:14.527   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:00:14.527   754   754 I MotionRecognitionService: Plugged
,06-30 14:00:14.527   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:00:14.527   754  1421 D BatteryService: stay LED for fully charged
,06-30 14:00:14.537  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:00:14.537  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:00:14.537  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:00:14.537  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:00:14.537  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:00:14.537  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:00:14.537  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:00:14.537  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:00:16.567   302   302 E SMD     : DCD ON
,06-30 14:00:17.597   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:00:19.577   302   302 E SMD     : DCD ON
,06-30 14:00:21.597   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:00:22.567   302   302 E SMD     : DCD ON
,06-30 14:00:23.247   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:00:24.577   754  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:00:24.587   754  1570 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:00:24.587   754  1570 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:00:24.587   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:00:24.587   754   754 I MotionRecognitionService: Plugged
,06-30 14:00:24.587   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:00:24.587   754  1570 D BatteryService: stay LED for fully charged
,06-30 14:00:24.597  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:00:24.597  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:00:24.597  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:00:24.597  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:00:24.597  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:00:24.597  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:00:24.597  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:00:24.597  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:00:25.567   302   302 E SMD     : DCD ON
,06-30 14:00:25.597   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:00:28.567   302   302 E SMD     : DCD ON
,06-30 14:00:29.607   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:00:31.537   754  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 14:00:31.537   754  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:00:31.547   754  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 14:00:31.587   302   302 E SMD     : DCD ON
,06-30 14:00:32.187   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 14:00:33.297   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:00:33.607   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:00:33.767   754  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 14:00:33.767   754  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:00:33.777   754  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:00:33.777   754  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:00:34.187   754  1320 E Watchdog: !@Sync 20
,06-30 14:00:34.587   302   302 E SMD     : DCD ON
,06-30 14:00:34.637   754  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:00:37.597   302   302 E SMD     : DCD ON
,06-30 14:00:37.617   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:00:40.587   302   302 E SMD     : DCD ON
,06-30 14:00:41.627   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:00:43.347   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:00:43.597   302   302 E SMD     : DCD ON
,06-30 14:00:44.697   754  1378 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:00:45.627   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:00:46.587   302   302 E SMD     : DCD ON
,06-30 14:00:49.587   302   302 E SMD     : DCD ON
,06-30 14:00:49.627   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:00:52.197   754  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 14:00:52.587   302   302 E SMD     : DCD ON
,06-30 14:00:53.407   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:00:53.637   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:00:54.757   754  1246 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:00:55.597   302   302 E SMD     : DCD ON
,06-30 14:00:57.637   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:00:58.587   302   302 E SMD     : DCD ON
,06-30 14:01:00.007   754  1050 I PowerManagerService: [PWL] Off : 600s ago
,06-30 14:01:01.597   302   302 E SMD     : DCD ON
,06-30 14:01:01.657   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:01:03.447   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:01:04.177   754  1320 E Watchdog: !@Sync 21
,06-30 14:01:04.587   302   302 E SMD     : DCD ON
,06-30 14:01:04.807   754  1553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:01:04.817   754  1553 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:01:04.817   754  1553 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:01:04.817   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:01:04.827  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:01:04.827  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:01:04.827   754   754 I MotionRecognitionService: Plugged
,06-30 14:01:04.827   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:01:04.827   754  1553 D BatteryService: stay LED for fully charged
,06-30 14:01:04.827  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:01:04.837  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:01:04.837  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:01:04.867  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:04.867  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:04.867  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:05.657   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:01:07.597   302   302 E SMD     : DCD ON
,06-30 14:01:09.657   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:01:10.597   302   302 E SMD     : DCD ON
,06-30 14:01:13.497   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:01:13.607   302   302 E SMD     : DCD ON
,06-30 14:01:13.657   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:01:14.867   754  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:01:14.877   754  1570 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:01:14.877   754  1570 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:01:14.877   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:01:14.887   754   754 I MotionRecognitionService: Plugged
,06-30 14:01:14.887   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:01:14.887  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:01:14.887  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:01:14.887   754  1570 D BatteryService: stay LED for fully charged
,06-30 14:01:14.887  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:01:14.897  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:01:14.897  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:01:14.907  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:14.907  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:01:14.907  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:16.607   302   302 E SMD     : DCD ON
,06-30 14:01:17.667   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:01:19.597   302   302 E SMD     : DCD ON
,06-30 14:01:21.677   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:01:22.597   302   302 E SMD     : DCD ON
,06-30 14:01:23.547   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:01:24.937   754  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:01:24.947   754  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:01:24.947   754  1343 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:01:24.947   754  1343 D BatteryService: stay LED for fully charged
06-30 14:01:24.947   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:01:24.957   754   754 I MotionRecognitionService: Plugged
,06-30 14:01:24.957   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:01:24.957  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:01:24.957  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:01:24.957  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:01:24.957  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:01:24.957  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:24.957  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:24.967  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:24.967  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:01:25.607   302   302 E SMD     : DCD ON
,06-30 14:01:25.687   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:01:28.607   302   302 E SMD     : DCD ON
,06-30 14:01:29.687   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:01:31.607   302   302 E SMD     : DCD ON
,06-30 14:01:33.597   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:01:33.687   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:01:34.187   754  1320 E Watchdog: !@Sync 22
,06-30 14:01:34.597   302   302 E SMD     : DCD ON
,06-30 14:01:34.987   754  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:01:37.607   302   302 E SMD     : DCD ON
,06-30 14:01:37.687   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:01:40.597   302   302 E SMD     : DCD ON
,06-30 14:01:41.697   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:01:43.607   302   302 E SMD     : DCD ON
,06-30 14:01:43.657   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:01:45.057   754  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:01:45.057   754  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:01:45.057   754  1476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:01:45.067   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:01:45.067   754   754 I MotionRecognitionService: Plugged
,06-30 14:01:45.067   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:01:45.067   754  1476 D BatteryService: stay LED for fully charged
,06-30 14:01:45.077  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:01:45.077  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:01:45.087  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:45.087  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:01:45.087  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:01:45.087  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:45.087  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:01:45.087  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:01:45.707   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:01:46.607   302   302 E SMD     : DCD ON
,06-30 14:01:49.617   302   302 E SMD     : DCD ON
,06-30 14:01:49.707   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:01:52.607   302   302 E SMD     : DCD ON
,06-30 14:01:53.697   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:01:53.717   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:01:55.117   754  1378 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:01:55.607   302   302 E SMD     : DCD ON
,06-30 14:01:57.727   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:01:58.607   302   302 E SMD     : DCD ON
,06-30 14:02:01.607   302   302 E SMD     : DCD ON
,06-30 14:02:01.727   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:02:03.747   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:02:04.197   754  1320 E Watchdog: !@Sync 23
,06-30 14:02:04.617   302   302 E SMD     : DCD ON
,06-30 14:02:05.187   754  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:02:05.727   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:02:07.607   302   302 E SMD     : DCD ON
,06-30 14:02:09.737   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:02:10.607   302   302 E SMD     : DCD ON
,06-30 14:02:13.617   302   302 E SMD     : DCD ON
,06-30 14:02:13.747   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:02:13.787   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:02:15.237   754  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:02:15.237   754  1144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 14:02:15.237   754  1144 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:02:15.237   754  1144 D BatteryService: stay LED for fully charged
06-30 14:02:15.237   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:02:15.237  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:02:15.237  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:02:15.237   754   754 I MotionRecognitionService: Plugged
06-30 14:02:15.247   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:02:15.247  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:02:15.247  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:15.247  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:02:15.247  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
06-30 14:02:15.247  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:15.257  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:16.607   302   302 E SMD     : DCD ON
,06-30 14:02:17.747   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:02:19.607   302   302 E SMD     : DCD ON
,06-30 14:02:20.007   754  1050 I PowerManagerService: [PWL] Off : 680s ago
,06-30 14:02:21.747   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:02:22.617   302   302 E SMD     : DCD ON
,06-30 14:02:23.837   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:02:25.297   754  1571 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:02:25.297   754  1571 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 14:02:25.297   754  1571 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:02:25.297   754  1571 D BatteryService: stay LED for fully charged
06-30 14:02:25.297   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:02:25.297  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:02:25.297  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:02:25.297   754   754 I MotionRecognitionService: Plugged
06-30 14:02:25.297   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:02:25.307  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:02:25.307  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:02:25.307  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:02:25.307  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:02:25.307  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:25.307  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:25.627   302   302 E SMD     : DCD ON
,06-30 14:02:25.747   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:02:28.617   302   302 E SMD     : DCD ON
,06-30 14:02:29.757   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:02:31.617   302   302 E SMD     : DCD ON
,06-30 14:02:33.767   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:02:33.887   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:02:34.197   754  1320 E Watchdog: !@Sync 24
,06-30 14:02:34.617   302   302 E SMD     : DCD ON
,06-30 14:02:35.357   754  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:02:35.357   754  1570 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 14:02:35.357   754  1570 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:02:35.357   754  1570 D BatteryService: stay LED for fully charged
06-30 14:02:35.357   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:02:35.357   754   754 I MotionRecognitionService: Plugged
,06-30 14:02:35.357   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:02:35.367  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:02:35.367  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 14:02:35.367  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:02:35.367  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:02:35.367  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:02:35.367  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:35.367  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:02:35.367  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:37.617   302   302 E SMD     : DCD ON
,06-30 14:02:37.777   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:02:40.617   302   302 E SMD     : DCD ON
,06-30 14:02:41.767   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:02:43.627   302   302 E SMD     : DCD ON
,06-30 14:02:43.937   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:02:45.417   754  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:02:45.417   754  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 14:02:45.417   754  1343 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:02:45.417   754  1343 D BatteryService: stay LED for fully charged
06-30 14:02:45.417   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:02:45.417  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:02:45.417  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:02:45.417   754   754 I MotionRecognitionService: Plugged
06-30 14:02:45.417   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:02:45.427  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:02:45.427  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:02:45.427  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:02:45.427  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:45.427  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:02:45.427  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:02:45.767   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:02:46.617   302   302 E SMD     : DCD ON
,06-30 14:02:49.617   302   302 E SMD     : DCD ON
,06-30 14:02:49.787   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:02:52.627   302   302 E SMD     : DCD ON
,06-30 14:02:53.777   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:02:53.977   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:02:55.477   754  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:02:55.477   754  1584 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 14:02:55.477   754  1584 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:02:55.477   754  1584 D BatteryService: stay LED for fully charged
06-30 14:02:55.477   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:02:55.487  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:02:55.487  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:02:55.487  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:55.487  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:55.487  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:02:55.487  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:02:55.487  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:02:55.487   754   754 I MotionRecognitionService: Plugged
06-30 14:02:55.487   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:02:55.507  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:55.627   302   302 E SMD     : DCD ON
,06-30 14:02:57.787   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:02:58.627   302   302 E SMD     : DCD ON
,06-30 14:03:01.627   302   302 E SMD     : DCD ON
,06-30 14:03:01.797   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:03:04.037   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:03:04.187   754  1320 E Watchdog: !@Sync 25
,06-30 14:03:04.637   302   302 E SMD     : DCD ON
,06-30 14:03:05.527   754  1378 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:03:05.537   754  1378 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:03:05.537   754  1378 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:03:05.537   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:03:05.537  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:03:05.547   754   754 I MotionRecognitionService: Plugged
,06-30 14:03:05.547   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:03:05.547  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:03:05.547   754  1378 D BatteryService: stay LED for fully charged
,06-30 14:03:05.547  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:03:05.547  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:05.547  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:03:05.547  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:05.557  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:03:05.557  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:03:05.797   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:03:07.637   302   302 E SMD     : DCD ON
,06-30 14:03:09.807   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:03:10.627   302   302 E SMD     : DCD ON
,06-30 14:03:13.627   302   302 E SMD     : DCD ON
,06-30 14:03:13.807   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:03:14.077   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:03:15.597   754  1697 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:03:15.597   754  1697 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 14:03:15.597   754  1697 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:03:15.597   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:03:15.597   754   754 I MotionRecognitionService: Plugged
,06-30 14:03:15.607  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:03:15.607   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:03:15.607  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:03:15.607  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:03:15.607   754  1697 D BatteryService: stay LED for fully charged
,06-30 14:03:15.607  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:03:15.617  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:03:15.617  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:03:15.627  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:15.627  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:16.627   302   302 E SMD     : DCD ON
,06-30 14:03:17.807   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:03:19.637   302   302 E SMD     : DCD ON
,06-30 14:03:21.817   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:03:22.627   302   302 E SMD     : DCD ON
,06-30 14:03:24.127   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:03:25.627   302   302 E SMD     : DCD ON
,06-30 14:03:25.657   754   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:03:25.667   754   781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:03:25.667   754   781 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:03:25.667   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:03:25.677  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:03:25.677   754   754 I MotionRecognitionService: Plugged
,06-30 14:03:25.677  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:03:25.677   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:03:25.677   754   781 D BatteryService: stay LED for fully charged
,06-30 14:03:25.687  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:03:25.687  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:25.687  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:25.687  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:03:25.697  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:03:25.707  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:25.827   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:03:28.627   302   302 E SMD     : DCD ON
,06-30 14:03:29.827   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:03:31.627   302   302 E SMD     : DCD ON
,06-30 14:03:33.837   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:03:34.007   754  1116 V AlarmManager: waitForAlarm result :8
,06-30 14:03:34.177   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:03:34.197   754  1320 E Watchdog: !@Sync 26
,06-30 14:03:34.627   302   302 E SMD     : DCD ON
,06-30 14:03:35.717   754  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:03:35.717   754  1421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 14:03:35.717   754  1421 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:03:35.717   754  1421 D BatteryService: stay LED for fully charged
06-30 14:03:35.717   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:03:35.717  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:03:35.717  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:03:35.717   754   754 I MotionRecognitionService: Plugged
06-30 14:03:35.717   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:03:35.727  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:03:35.727  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:03:35.727  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:03:35.727  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:35.727  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:35.747  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:37.637   302   302 E SMD     : DCD ON
,06-30 14:03:37.837   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:03:40.627   302   302 E SMD     : DCD ON
,06-30 14:03:41.837   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:03:43.637   302   302 E SMD     : DCD ON
,06-30 14:03:44.217   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:03:45.017   754  1050 I PowerManagerService: [PWL] Off : 765s ago
,06-30 14:03:45.777   754  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:03:45.777   754  1570 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:03:45.777   754  1570 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:03:45.787   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:03:45.787   754   754 I MotionRecognitionService: Plugged
,06-30 14:03:45.787   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:03:45.787   754  1570 D BatteryService: stay LED for fully charged
,06-30 14:03:45.787  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:03:45.797  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:03:45.797  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:03:45.797  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:45.797  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:03:45.797  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:03:45.797  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:03:45.797  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:45.847   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:03:46.637   302   302 E SMD     : DCD ON
,06-30 14:03:49.647   302   302 E SMD     : DCD ON
,06-30 14:03:49.857   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:03:52.637   302   302 E SMD     : DCD ON
,06-30 14:03:53.857   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:03:54.267   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,06-30 14:03:55.637   302   302 E SMD     : DCD ON
,06-30 14:03:55.837   754  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:03:55.837   754  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:03:55.837   754  1343 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:03:55.847   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:03:55.847  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:03:55.857  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:03:55.857   754   754 I MotionRecognitionService: Plugged
06-30 14:03:55.857   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:03:55.857   754  1343 D BatteryService: stay LED for fully charged
,06-30 14:03:55.857  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:55.867  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:03:55.867  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:03:55.867  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:03:55.867  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:55.867  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:03:57.857   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:03:58.637   302   302 E SMD     : DCD ON
,06-30 14:04:01.647   302   302 E SMD     : DCD ON
,06-30 14:04:01.867   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:04:04.207   754  1320 E Watchdog: !@Sync 27
,06-30 14:04:04.317   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450
,06-30 14:04:04.637   302   302 E SMD     : DCD ON
,06-30 14:04:05.877   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:04:05.897   754  1652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:04:07.647   302   302 E SMD     : DCD ON
,06-30 14:04:09.877   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:04:10.637   302   302 E SMD     : DCD ON
,06-30 14:04:13.637   302   302 E SMD     : DCD ON
,06-30 14:04:13.877   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:04:14.357   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450
,06-30 14:04:15.957   754  1378 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:04:15.957   754  1378 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 14:04:15.957   754  1378 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:04:15.957   754  1378 D BatteryService: stay LED for fully charged
06-30 14:04:15.957   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:04:15.957  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:04:15.957  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:04:15.957   754   754 I MotionRecognitionService: Plugged
06-30 14:04:15.957   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:04:15.967  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:04:15.967  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:04:15.967  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:04:15.967  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:04:15.967  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
06-30 14:04:15.967  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:04:16.647   302   302 E SMD     : DCD ON
,06-30 14:04:17.897   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:04:19.657   302   302 E SMD     : DCD ON
,06-30 14:04:21.887   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:04:22.657   302   302 E SMD     : DCD ON
,06-30 14:04:24.407   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450
,06-30 14:04:25.657   302   302 E SMD     : DCD ON
,06-30 14:04:25.897   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:04:26.017   754  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:04:28.657   302   302 E SMD     : DCD ON
,06-30 14:04:29.897   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:04:31.657   302   302 E SMD     : DCD ON
,06-30 14:04:33.917   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:04:34.207   754  1320 E Watchdog: !@Sync 28
,06-30 14:04:34.457   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450
,06-30 14:04:34.647   302   302 E SMD     : DCD ON
,06-30 14:04:36.077   754  1553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:04:37.657   302   302 E SMD     : DCD ON
,06-30 14:04:37.907   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:04:40.657   302   302 E SMD     : DCD ON
,06-30 14:04:41.917   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:04:43.657   302   302 E SMD     : DCD ON
,06-30 14:04:44.507   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450
,06-30 14:04:45.927   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:04:46.137   754  1357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:04:46.657   302   302 E SMD     : DCD ON
,06-30 14:04:49.647   302   302 E SMD     : DCD ON
,06-30 14:04:49.937   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:04:52.657   302   302 E SMD     : DCD ON
,06-30 14:04:53.937   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:04:54.557   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450
,06-30 14:04:55.657   302   302 E SMD     : DCD ON
,06-30 14:04:56.197   754  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:04:57.947   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:04:58.667   302   302 E SMD     : DCD ON
,06-30 14:05:01.667   302   302 E SMD     : DCD ON
,06-30 14:05:01.947   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:05:04.197   754  1320 E Watchdog: !@Sync 29
,06-30 14:05:04.607   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,06-30 14:05:04.657   302   302 E SMD     : DCD ON
,06-30 14:05:05.947   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:05:06.257   754  1571 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:05:07.657   302   302 E SMD     : DCD ON
,06-30 14:05:09.957   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:05:10.667   302   302 E SMD     : DCD ON
,06-30 14:05:13.657   302   302 E SMD     : DCD ON
,06-30 14:05:13.967   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:05:14.647   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,06-30 14:05:15.017   754  1050 I PowerManagerService: [PWL] Off : 855s ago
,06-30 14:05:16.317   754   783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:05:16.317   754   783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 14:05:16.317   754   783 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:05:16.317   754   783 D BatteryService: stay LED for fully charged
06-30 14:05:16.317   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:05:16.317  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:05:16.317  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:05:16.317   754   754 I MotionRecognitionService: Plugged
06-30 14:05:16.317   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:05:16.317  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:05:16.327  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:05:16.327  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:05:16.327  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:05:16.327  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:05:16.327  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:05:16.667   302   302 E SMD     : DCD ON
,06-30 14:05:17.977   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:05:19.657   302   302 E SMD     : DCD ON
,06-30 14:05:21.977   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:05:22.667   302   302 E SMD     : DCD ON
,06-30 14:05:24.697   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,06-30 14:05:25.667   302   302 E SMD     : DCD ON
,06-30 14:05:25.977   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:05:26.377   754  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:05:26.377   754  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:05:26.387   754  1476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:05:26.387   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:05:26.387   754   754 I MotionRecognitionService: Plugged
,06-30 14:05:26.387   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:05:26.387   754  1476 D BatteryService: stay LED for fully charged
,06-30 14:05:26.387  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:05:26.397  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:05:26.397  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:05:26.397  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:05:26.397  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:05:26.397  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:05:26.397  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 14:05:26.397  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:05:28.657   302   302 E SMD     : DCD ON
,06-30 14:05:29.987   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:05:31.547   754  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 14:05:31.547   754  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 14:05:31.547   754  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:05:31.667   302   302 E SMD     : DCD ON
,06-30 14:05:33.777   754  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 14:05:33.777   754  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:05:33.777   754  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:05:33.787   754  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:05:33.987   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:05:34.207   754  1320 E Watchdog: !@Sync 30
,06-30 14:05:34.667   302   302 E SMD     : DCD ON
,06-30 14:05:34.747   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 301, CUR = 450
,06-30 14:05:36.437   754  1357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:05:36.437   754  1357 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:05:36.447   754  1357 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:05:36.447   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:05:36.447  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:05:36.447  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:05:36.447   754   754 I MotionRecognitionService: Plugged
,06-30 14:05:36.447   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:05:36.447  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:05:36.457  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:05:36.457   754  1357 D BatteryService: stay LED for fully charged
,06-30 14:05:36.457  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:05:36.457  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:05:36.457  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:05:36.457  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:05:37.667   302   302 E SMD     : DCD ON
,06-30 14:05:37.987   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:05:40.667   302   302 E SMD     : DCD ON
,06-30 14:05:41.997   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:05:43.677   302   302 E SMD     : DCD ON
,06-30 14:05:44.797   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 302, CUR = 450
,06-30 14:05:46.007   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:05:46.497   754   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:05:46.667   302   302 E SMD     : DCD ON
,06-30 14:05:49.667   302   302 E SMD     : DCD ON
,06-30 14:05:50.007   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:05:52.667   302   302 E SMD     : DCD ON
,06-30 14:05:54.017   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:05:54.837   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,06-30 14:05:55.677   302   302 E SMD     : DCD ON
,06-30 14:05:56.557   754  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:05:58.017   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:05:58.677   302   302 E SMD     : DCD ON
,06-30 14:06:01.677   302   302 E SMD     : DCD ON
,06-30 14:06:02.027   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:06:04.217   754  1320 E Watchdog: !@Sync 31
,06-30 14:06:04.667   302   302 E SMD     : DCD ON
,06-30 14:06:04.887   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,06-30 14:06:06.027   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:06:06.617   754  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:06:06.617   754  1544 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:06:06.627   754  1544 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:06:06.627   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:06:06.627  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:06:06.627  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:06:06.627   754   754 I MotionRecognitionService: Plugged
06-30 14:06:06.627   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:06:06.627  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:06:06.637  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:06:06.637  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:06:06.637   754  1544 D BatteryService: stay LED for fully charged
,06-30 14:06:06.637  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:06.637  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:06:06.637  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:07.667   302   302 E SMD     : DCD ON
,06-30 14:06:10.037   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:06:10.677   302   302 E SMD     : DCD ON
,06-30 14:06:13.677   302   302 E SMD     : DCD ON
,06-30 14:06:14.037   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:06:14.937   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,06-30 14:06:16.677   302   302 E SMD     : DCD ON
,06-30 14:06:16.687   754  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:06:16.687   754  1421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:06:16.687   754  1421 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:06:16.687   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:06:16.697  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:06:16.697   754   754 I MotionRecognitionService: Plugged
,06-30 14:06:16.697  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:06:16.697   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:06:16.707   754  1421 D BatteryService: stay LED for fully charged
,06-30 14:06:16.707  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:06:16.707  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:06:16.717  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:06:16.727  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:16.727  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:06:16.727  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:18.047   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:06:19.677   302   302 E SMD     : DCD ON
,06-30 14:06:22.047   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:06:22.677   302   302 E SMD     : DCD ON
,06-30 14:06:25.007   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,06-30 14:06:25.677   302   302 E SMD     : DCD ON
,06-30 14:06:26.067   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:06:26.737   754  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:06:26.747   754  1570 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:06:26.747   754  1570 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:06:26.747   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:06:26.747  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:06:26.747  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:06:26.747   754   754 I MotionRecognitionService: Plugged
,06-30 14:06:26.747   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:06:26.757  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:06:26.757  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
06-30 14:06:26.757  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:06:26.757   754  1570 D BatteryService: stay LED for fully charged
,06-30 14:06:26.757  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:06:26.757  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:26.757  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:28.677   302   302 E SMD     : DCD ON
,06-30 14:06:30.057   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:06:31.677   302   302 E SMD     : DCD ON
,06-30 14:06:34.067   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:06:34.217   754  1320 E Watchdog: !@Sync 32
,06-30 14:06:34.677   302   302 E SMD     : DCD ON
,06-30 14:06:35.067   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,06-30 14:06:36.807   754  1246 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:06:36.807   754  1246 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:06:36.807   754  1246 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:06:36.807   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:06:36.817  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:06:36.817  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:06:36.817   754   754 I MotionRecognitionService: Plugged
,06-30 14:06:36.817   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:06:36.827   754  1246 D BatteryService: stay LED for fully charged
,06-30 14:06:36.827  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:06:36.827  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:36.827  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:06:36.827  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:06:36.847  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:36.847  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:37.687   302   302 E SMD     : DCD ON
,06-30 14:06:38.067   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:06:40.687   302   302 E SMD     : DCD ON
,06-30 14:06:42.077   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:06:43.677   302   302 E SMD     : DCD ON
,06-30 14:06:45.117   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,06-30 14:06:46.077   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:06:46.697   302   302 E SMD     : DCD ON
,06-30 14:06:46.857   754  1652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:06:46.857   754  1652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:06:46.867   754  1652 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:06:46.867   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:06:46.867   754   754 I MotionRecognitionService: Plugged
,06-30 14:06:46.867   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:06:46.867   754  1652 D BatteryService: stay LED for fully charged
,06-30 14:06:46.867  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:06:46.877  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:06:46.877  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:06:46.877  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:46.877  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:46.877  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:06:46.877  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:06:46.877  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:49.687   302   302 E SMD     : DCD ON
,06-30 14:06:50.027   754  1050 I PowerManagerService: [PWL] Off : 950s ago
,06-30 14:06:50.087   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:06:52.697   302   302 E SMD     : DCD ON
,06-30 14:06:54.087   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:06:55.157   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,06-30 14:06:55.697   302   302 E SMD     : DCD ON
,06-30 14:06:56.917   754  1553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:06:58.097   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:06:58.687   302   302 E SMD     : DCD ON
,06-30 14:07:01.687   302   302 E SMD     : DCD ON
,06-30 14:07:02.107   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:07:04.217   754  1320 E Watchdog: !@Sync 33
,06-30 14:07:04.687   302   302 E SMD     : DCD ON
,06-30 14:07:05.207   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,06-30 14:07:06.107   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:07:06.977   754  1246 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:07:06.977   754  1246 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:07:06.977   754  1246 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:07:06.977   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:07:06.987  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:07:06.987  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:07:06.987  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:07:06.997  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:07:06.997   754   754 I MotionRecognitionService: Plugged
06-30 14:07:06.997   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:07:06.997   754  1246 D BatteryService: stay LED for fully charged
,06-30 14:07:06.997  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:06.997  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:07:06.997  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:07:06.997  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:07.697   302   302 E SMD     : DCD ON
,06-30 14:07:10.107   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:07:10.687   302   302 E SMD     : DCD ON
,06-30 14:07:13.697   302   302 E SMD     : DCD ON
,06-30 14:07:14.107   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:07:15.257   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,06-30 14:07:16.687   302   302 E SMD     : DCD ON
,06-30 14:07:17.037   754  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:07:18.117   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:07:19.687   302   302 E SMD     : DCD ON
,06-30 14:07:22.127   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:07:22.697   302   302 E SMD     : DCD ON
,06-30 14:07:25.317   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:07:25.707   302   302 E SMD     : DCD ON
,06-30 14:07:26.127   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:07:27.097   754  1378 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:07:27.097   754  1378 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:07:27.097   754  1378 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:07:27.107   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:07:27.107   754   754 I MotionRecognitionService: Plugged
,06-30 14:07:27.107   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:07:27.107   754  1378 D BatteryService: stay LED for fully charged
,06-30 14:07:27.107  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:07:27.117  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:07:27.117  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:07:27.117  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:27.117  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:07:27.117  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:07:27.117  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
06-30 14:07:27.117  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:28.707   302   302 E SMD     : DCD ON
,06-30 14:07:30.137   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:07:31.697   302   302 E SMD     : DCD ON
,06-30 14:07:34.147   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:07:34.227   754  1320 E Watchdog: !@Sync 34
,06-30 14:07:34.707   302   302 E SMD     : DCD ON
,06-30 14:07:35.367   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:07:37.157   754  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:07:37.697   302   302 E SMD     : DCD ON
,06-30 14:07:38.147   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:07:40.707   302   302 E SMD     : DCD ON
,06-30 14:07:42.157   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:07:43.707   302   302 E SMD     : DCD ON
,06-30 14:07:45.437   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:07:46.167   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:07:46.707   302   302 E SMD     : DCD ON
,06-30 14:07:47.217   754  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:07:47.217   754  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:07:47.217   754  1476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:07:47.227   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:07:47.227   754   754 I MotionRecognitionService: Plugged
,06-30 14:07:47.227   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:07:47.227   754  1476 D BatteryService: stay LED for fully charged
,06-30 14:07:47.227  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:07:47.237  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:07:47.237  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:07:47.237  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:47.237  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:47.237  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 14:07:47.237  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:07:47.237  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:49.697   302   302 E SMD     : DCD ON
,06-30 14:07:50.167   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:07:52.697   302   302 E SMD     : DCD ON
,06-30 14:07:54.167   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:07:55.487   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:07:55.707   302   302 E SMD     : DCD ON
,06-30 14:07:57.277   754  1697 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:07:57.277   754  1697 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:07:57.277   754  1697 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:07:57.287   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:07:57.287   754   754 I MotionRecognitionService: Plugged
,06-30 14:07:57.287   754   754 I MotionRecognitionService: setPowerConnected  = true
06-30 14:07:57.287   754  1697 D BatteryService: stay LED for fully charged
,06-30 14:07:57.287  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:07:57.297  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:07:57.297  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:07:57.297  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:07:57.297  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:57.297  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:07:57.297  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:57.297  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:07:58.177   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:07:58.707   302   302 E SMD     : DCD ON
,06-30 14:08:01.717   302   302 E SMD     : DCD ON
,06-30 14:08:02.187   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:08:04.227   754  1320 E Watchdog: !@Sync 35
,06-30 14:08:04.707   302   302 E SMD     : DCD ON
,06-30 14:08:05.537   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:08:06.187   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:08:07.337   754  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:08:07.707   302   302 E SMD     : DCD ON
,06-30 14:08:10.197   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:08:10.707   302   302 E SMD     : DCD ON
,06-30 14:08:13.717   302   302 E SMD     : DCD ON
,06-30 14:08:14.197   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:08:15.577   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:08:16.707   302   302 E SMD     : DCD ON
,06-30 14:08:17.397   754  1553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:08:17.397   754  1553 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:08:17.397   754  1553 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:08:17.407   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:08:17.407   754   754 I MotionRecognitionService: Plugged
,06-30 14:08:17.407   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:08:17.407   754  1553 D BatteryService: stay LED for fully charged
,06-30 14:08:17.407  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:08:17.417  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:08:17.417  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:08:17.417  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:08:17.417  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:08:17.417  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:08:17.417  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:08:17.417  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:18.207   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:08:19.707   302   302 E SMD     : DCD ON
,06-30 14:08:22.217   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:08:22.717   302   302 E SMD     : DCD ON
,06-30 14:08:25.627   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:08:25.707   302   302 E SMD     : DCD ON
,06-30 14:08:26.217   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:08:27.457   754  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:08:28.707   302   302 E SMD     : DCD ON
,06-30 14:08:30.017   754  1050 I PowerManagerService: [PWL] Off : 1050s ago
,06-30 14:08:30.217   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:08:31.707   302   302 E SMD     : DCD ON
,06-30 14:08:34.217   754  1320 E Watchdog: !@Sync 36
,06-30 14:08:34.227   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:08:34.707   302   302 E SMD     : DCD ON
,06-30 14:08:35.677   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:08:37.517   754  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:08:37.517   754  1584 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:08:37.517   754  1584 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:08:37.527   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:08:37.527   754   754 I MotionRecognitionService: Plugged
,06-30 14:08:37.527   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:08:37.527  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:08:37.537  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:08:37.537  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
06-30 14:08:37.537  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:08:37.537  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:08:37.537   754  1584 D BatteryService: stay LED for fully charged
,06-30 14:08:37.537  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:08:37.537  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:37.537  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:37.707   302   302 E SMD     : DCD ON
,06-30 14:08:38.227   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:08:40.707   302   302 E SMD     : DCD ON
,06-30 14:08:42.237   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:08:43.727   302   302 E SMD     : DCD ON
,06-30 14:08:45.727   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:08:46.237   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:08:46.727   302   302 E SMD     : DCD ON
,06-30 14:08:47.577   754   783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:08:47.577   754   783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:08:47.577   754   783 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:08:47.587   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:08:47.587   754   754 I MotionRecognitionService: Plugged
,06-30 14:08:47.587   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:08:47.587   754   783 D BatteryService: stay LED for fully charged
,06-30 14:08:47.587  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:08:47.597  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:08:47.597  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:08:47.597  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:47.597  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:08:47.597  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:47.597  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 14:08:47.597  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:08:49.727   302   302 E SMD     : DCD ON
,06-30 14:08:50.247   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:08:52.727   302   302 E SMD     : DCD ON
,06-30 14:08:54.247   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:08:55.727   302   302 E SMD     : DCD ON
,06-30 14:08:55.767   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:08:57.637   754  1571 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:08:57.637   754  1571 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:08:57.637   754  1571 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:08:57.647   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:08:57.647   754   754 I MotionRecognitionService: Plugged
,06-30 14:08:57.647   754   754 I MotionRecognitionService: setPowerConnected  = true
06-30 14:08:57.647   754  1571 D BatteryService: stay LED for fully charged
,06-30 14:08:57.647  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:08:57.657  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:08:57.657  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:08:57.657  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:08:57.657  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:08:57.657  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:08:57.657  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:57.657  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:58.267   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:08:58.727   302   302 E SMD     : DCD ON
,06-30 14:09:01.727   302   302 E SMD     : DCD ON
,06-30 14:09:02.267   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:09:04.237   754  1320 E Watchdog: !@Sync 37
,06-30 14:09:04.727   302   302 E SMD     : DCD ON
,06-30 14:09:05.827   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:09:06.277   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:09:07.697   754   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:09:07.697   754   781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:09:07.697   754   781 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:09:07.707   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:09:07.707   754   754 I MotionRecognitionService: Plugged
,06-30 14:09:07.707   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:09:07.707   754   781 D BatteryService: stay LED for fully charged
,06-30 14:09:07.707  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:09:07.717  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:09:07.717  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:07.717  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:09:07.717  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:07.717  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:09:07.717  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:09:07.717  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:09:07.717   302   302 E SMD     : DCD ON
,06-30 14:09:10.277   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:09:10.717   302   302 E SMD     : DCD ON
,06-30 14:09:13.727   302   302 E SMD     : DCD ON
,06-30 14:09:14.277   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:09:15.877   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:09:16.717   302   302 E SMD     : DCD ON
,06-30 14:09:17.757   754  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:09:17.757   754  1421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:09:17.757   754  1421 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:09:17.767   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:09:17.767   754   754 I MotionRecognitionService: Plugged
,06-30 14:09:17.767   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:09:17.767   754  1421 D BatteryService: stay LED for fully charged
,06-30 14:09:17.767  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:09:17.777  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:09:17.777  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:09:17.777  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:17.777  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:09:17.777  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:17.777  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 14:09:17.777  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:09:18.287   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:09:19.727   302   302 E SMD     : DCD ON
,06-30 14:09:22.287   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:09:22.717   302   302 E SMD     : DCD ON
,06-30 14:09:25.727   302   302 E SMD     : DCD ON
,06-30 14:09:25.927   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:09:26.297   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:09:27.827   754  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:09:27.827   754  1570 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:09:27.827   754  1570 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:09:27.827   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:09:27.827  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:09:27.827  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:09:27.827   754   754 I MotionRecognitionService: Plugged
06-30 14:09:27.827   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:09:27.827  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:09:27.837  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:09:27.837  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:09:27.837   754  1570 D BatteryService: stay LED for fully charged
,06-30 14:09:27.837  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:09:27.837  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:27.837  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:28.727   302   302 E SMD     : DCD ON
,06-30 14:09:30.307   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:09:31.737   302   302 E SMD     : DCD ON
,06-30 14:09:34.237   754  1320 E Watchdog: !@Sync 38
,06-30 14:09:34.317   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:09:34.727   302   302 E SMD     : DCD ON
,06-30 14:09:35.977   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:09:37.737   302   302 E SMD     : DCD ON
,06-30 14:09:37.877   754  1246 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:09:37.877   754  1246 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:09:37.887   754  1246 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:09:37.887   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:09:37.887  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:09:37.897  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:09:37.897   754   754 I MotionRecognitionService: Plugged
,06-30 14:09:37.897   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:09:37.897   754  1246 D BatteryService: stay LED for fully charged
,06-30 14:09:37.897  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:37.907  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:37.907  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:09:37.907  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:37.907  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 14:09:37.907  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:09:38.317   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:09:40.727   302   302 E SMD     : DCD ON
,06-30 14:09:42.317   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:09:43.737   302   302 E SMD     : DCD ON
,06-30 14:09:46.027   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:09:46.327   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:09:46.727   302   302 E SMD     : DCD ON
,06-30 14:09:47.937   754  1652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:09:47.937   754  1652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
06-30 14:09:47.947   754  1652 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:09:47.947   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:09:47.947  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:09:47.947  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:09:47.947   754   754 I MotionRecognitionService: Plugged
06-30 14:09:47.947   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:09:47.947  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:09:47.957   754  1652 D BatteryService: stay LED for fully charged
,06-30 14:09:47.957  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:09:47.957  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:09:47.967  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:47.977  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:09:47.977  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:49.727   302   302 E SMD     : DCD ON
,06-30 14:09:50.327   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:09:52.727   302   302 E SMD     : DCD ON
,06-30 14:09:54.337   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:09:55.727   302   302 E SMD     : DCD ON
,06-30 14:09:56.077   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:09:57.997   754  1553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:09:57.997   754  1553 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:09:58.007   754  1553 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:09:58.007   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:09:58.007  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:09:58.007  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:09:58.007   754   754 I MotionRecognitionService: Plugged
,06-30 14:09:58.007   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:09:58.017  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:09:58.017  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
06-30 14:09:58.017  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:09:58.017   754  1553 D BatteryService: stay LED for fully charged
,06-30 14:09:58.017  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:58.017  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:09:58.017  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:58.337   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:09:58.727   302   302 E SMD     : DCD ON
,06-30 14:10:01.727   302   302 E SMD     : DCD ON
,06-30 14:10:02.347   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:10:04.227   754  1320 E Watchdog: !@Sync 39
,06-30 14:10:04.737   302   302 E SMD     : DCD ON
,06-30 14:10:06.117   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:10:06.357   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:10:07.737   302   302 E SMD     : DCD ON
,06-30 14:10:08.057   754  1571 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:10:10.367   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:10:10.737   302   302 E SMD     : DCD ON
,06-30 14:10:13.737   302   302 E SMD     : DCD ON
,06-30 14:10:14.367   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:10:15.027   754  1050 I PowerManagerService: [PWL] Off : 1155s ago
,06-30 14:10:16.167   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:10:16.737   302   302 E SMD     : DCD ON
,06-30 14:10:18.117   754  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:10:18.117   754  1584 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:10:18.127   754  1584 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:10:18.127   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:10:18.127   754   754 I MotionRecognitionService: Plugged
,06-30 14:10:18.127   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:10:18.127   754  1584 D BatteryService: stay LED for fully charged
,06-30 14:10:18.127  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:10:18.137  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:10:18.137  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:10:18.137  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:10:18.137  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:10:18.137  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 14:10:18.137  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:10:18.137  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:10:18.387   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:10:19.747   302   302 E SMD     : DCD ON
,06-30 14:10:22.387   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:10:22.747   302   302 E SMD     : DCD ON
,06-30 14:10:25.737   302   302 E SMD     : DCD ON
,06-30 14:10:26.217   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:10:26.397   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:10:28.177   754  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:10:28.737   302   302 E SMD     : DCD ON
,06-30 14:10:30.397   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:10:31.547   754  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 14:10:31.547   754  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 14:10:31.547   754  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:10:31.737   302   302 E SMD     : DCD ON
,06-30 14:10:31.937   754  1004 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 14:10:31.977   754  1125 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,06-30 14:10:31.987   754  1125 I ApplicationUsage: Updating Usage Statistics in DB @ 1467288631998
,06-30 14:10:31.987   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 14:10:31.987   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 14:10:31.987   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 14:10:31.987   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
06-30 14:10:31.987   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
06-30 14:10:31.987   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
06-30 14:10:31.987   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:31.987   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:31.987   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:31.987   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 14:10:31.987   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:31.987   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:31.987   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:31.987   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
06-30 14:10:31.987   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
06-30 14:10:31.987   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,06-30 14:10:31.987   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:31.987   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:31.987   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:31.987   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:31.987   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:31.987   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:31.997   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:31.997   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:31.997   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 14:10:31.997   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:31.997   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 14:10:31.997   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:31.997   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:31.997   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:31.997   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:31.997   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:31.997   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:31.997   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:31.997   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 14:10:31.997   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 14:10:31.997   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:31.997   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:31.997   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:31.997   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:31.997   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 14:10:31.997   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:31.997   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:31.997   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:31.997   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 14:10:32.007   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.007   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.007   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.007   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.007   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.007   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.007   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 14:10:32.007   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.007   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.007   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 14:10:32.007   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.007   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.007   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.007   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.007   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.007   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.007   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.007   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.007   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.007   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.007   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 14:10:32.007   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.007   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 14:10:32.017   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.017   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.017   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.017   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 14:10:32.017   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.017   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 14:10:32.017   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.017   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.017   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.017   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.017   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.017   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.017   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.017   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.017   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 14:10:32.017   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.017   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.017   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 14:10:32.017   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.017   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.017   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.017   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.017   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.017   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.017   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.017   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.017   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.027   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.027   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.027   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 14:10:32.027   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 14:10:32.027   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 14:10:32.027   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.027   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.027   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.027   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.027   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.027   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.027   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.027   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 14:10:32.027   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.027   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 14:10:32.027   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.027   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.027   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.027   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 14:10:32.027   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.027   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.037   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 14:10:32.037   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.037   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.037   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.037   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.037   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.037   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.037   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.037   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.037   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.037   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.037   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.037   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.037   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.037   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.037   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.037   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.037   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.037   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.037   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.037   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.047   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.047   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.047   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.047   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.047   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.047   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.047   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.047   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.047   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.047   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.047   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.047   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.047   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.047   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.047   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.047   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.047   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.047   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.057   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.057   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.057   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.057   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.057   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.057   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.057   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.057   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.057   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.057   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.057   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.057   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.057   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.057   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.057   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.057   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.057   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.057   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.057   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.057   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.067   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.067   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.067   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.067   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.067   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.067   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.067   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.067   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.067   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.067   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.067   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.067   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.067   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.067   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.067   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.067   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.067   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.067   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.067   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.067   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.067   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.067   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.067   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.067   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.067   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 14:10:32.067   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.067   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.067   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.067   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.067   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.067   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.067   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.067   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.067   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.077   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.077   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.077   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.077   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.077   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.077   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.077   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.077   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.077   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.077   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.077   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.077   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.077   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.077   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.087   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.087   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.087   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.087   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.087   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.087   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.087   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.087   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.087   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.087   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.087   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.087   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.087   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.087   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.087   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.087   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.097   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.097   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.097   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.097   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.097   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.097   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.097   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.097   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.097   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.097   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.097   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.097   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.097   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.097   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.097   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.097   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.107   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.107   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 14:10:32.107   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.107   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.107   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.107   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.107   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.107   754  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 14:10:32.107   754  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 14:10:32.107   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 14:10:32.107   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 14:10:32.107   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
06-30 14:10:32.107   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 14:10:32.107   754  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 14:10:32.107   754  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:10:32.107   754  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:10:32.107   754  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:10:32.107   754  1125 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1467288632120
,06-30 14:10:33.697   754  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 14:10:33.697   754  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:10:33.707   754  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:10:33.707   754  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:10:34.227   754  1320 E Watchdog: !@Sync 40
,06-30 14:10:34.407   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:10:34.747   302   302 E SMD     : DCD ON
,06-30 14:10:36.267   754  3297 D SSRM:n  : SIOP:: AP = 310, PST = 301, CUR = 450
,06-30 14:10:37.747   302   302 E SMD     : DCD ON
,06-30 14:10:38.237   754  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:10:38.237   754  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:10:38.237   754  1343 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:10:38.247   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:10:38.247   754   754 I MotionRecognitionService: Plugged
,06-30 14:10:38.247   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:10:38.247   754  1343 D BatteryService: stay LED for fully charged
,06-30 14:10:38.247  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:10:38.257  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:10:38.257  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:10:38.257  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:10:38.257  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:10:38.257  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 14:10:38.257  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:10:38.257  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:10:38.397   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:10:40.747   302   302 E SMD     : DCD ON
,06-30 14:10:42.407   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:10:43.747   302   302 E SMD     : DCD ON
,06-30 14:10:46.317   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,06-30 14:10:46.407   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:10:46.747   302   302 E SMD     : DCD ON
,06-30 14:10:48.297   754  1652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:10:49.757   302   302 E SMD     : DCD ON
,06-30 14:10:50.417   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:10:52.757   302   302 E SMD     : DCD ON
,06-30 14:10:54.417   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:10:55.747   302   302 E SMD     : DCD ON
,06-30 14:10:56.357   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,06-30 14:10:58.367   754  1571 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:10:58.427   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:10:58.747   302   302 E SMD     : DCD ON
,06-30 14:11:01.757   302   302 E SMD     : DCD ON
,06-30 14:11:02.427   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:11:04.237   754  1320 E Watchdog: !@Sync 41
,06-30 14:11:04.747   302   302 E SMD     : DCD ON
,06-30 14:11:06.407   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,06-30 14:11:06.437   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:11:07.747   302   302 E SMD     : DCD ON
,06-30 14:11:08.427   754  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:11:10.437   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:11:10.747   302   302 E SMD     : DCD ON
,06-30 14:11:13.757   302   302 E SMD     : DCD ON
,06-30 14:11:14.447   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:11:16.457   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,06-30 14:11:16.747   302   302 E SMD     : DCD ON
,06-30 14:11:18.457   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:11:18.487   754  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:11:19.747   302   302 E SMD     : DCD ON
,06-30 14:11:22.457   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:11:22.757   302   302 E SMD     : DCD ON
,06-30 14:11:25.767   302   302 E SMD     : DCD ON
,06-30 14:11:26.457   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:11:26.507   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,06-30 14:11:28.547   754  1357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:11:28.547   754  1357 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 14:11:28.547   754  1357 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:11:28.547   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:11:28.557  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:11:28.557   754   754 I MotionRecognitionService: Plugged
,06-30 14:11:28.557   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:11:28.557   754  1357 D BatteryService: stay LED for fully charged
,06-30 14:11:28.567  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:11:28.567  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:11:28.567  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:11:28.567  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:11:28.567  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:11:28.567  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:11:28.567  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:11:28.767   302   302 E SMD     : DCD ON
,06-30 14:11:30.467   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:11:31.757   302   302 E SMD     : DCD ON
,06-30 14:11:34.247   754  1320 E Watchdog: !@Sync 42
,06-30 14:11:34.467   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:11:34.767   302   302 E SMD     : DCD ON
,06-30 14:11:36.557   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,06-30 14:11:37.757   302   302 E SMD     : DCD ON
,06-30 14:11:38.467   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:11:38.607   754  1553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:11:38.607   754  1553 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:11:38.607   754  1553 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:11:38.607   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:11:38.617  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:11:38.617   754   754 I MotionRecognitionService: Plugged
,06-30 14:11:38.617  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:11:38.617   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:11:38.627   754  1553 D BatteryService: stay LED for fully charged
,06-30 14:11:38.627  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:11:38.627  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:11:38.637  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:11:38.637  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:11:38.647  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:11:38.647  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:11:40.767   302   302 E SMD     : DCD ON
,06-30 14:11:42.487   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:11:43.767   302   302 E SMD     : DCD ON
,06-30 14:11:46.487   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:11:46.607   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,06-30 14:11:46.767   302   302 E SMD     : DCD ON
,06-30 14:11:48.667   754  1697 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:11:49.767   302   302 E SMD     : DCD ON
,06-30 14:11:50.487   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:11:52.767   302   302 E SMD     : DCD ON
,06-30 14:11:54.497   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:11:55.757   302   302 E SMD     : DCD ON
,06-30 14:11:56.647   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,06-30 14:11:58.507   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:11:58.727   754  1357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:11:58.727   754  1357 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:11:58.737   754  1357 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:11:58.737   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:11:58.747  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:11:58.747  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:11:58.747   754   754 I MotionRecognitionService: Plugged
06-30 14:11:58.747   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:11:58.747   754  1357 D BatteryService: stay LED for fully charged
,06-30 14:11:58.747  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:11:58.757  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:11:58.757  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:11:58.757   302   302 E SMD     : DCD ON
,06-30 14:11:58.767  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:11:58.767  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:11:58.767  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:01.767   302   302 E SMD     : DCD ON
,06-30 14:12:02.507   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:12:04.237   754  1320 E Watchdog: !@Sync 43
,06-30 14:12:04.777   302   302 E SMD     : DCD ON
,06-30 14:12:05.027   754  1050 I PowerManagerService: [PWL] Off : 1265s ago
,06-30 14:12:06.517   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:12:06.697   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,06-30 14:12:07.777   302   302 E SMD     : DCD ON
,06-30 14:12:08.787   754  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:12:08.787   754  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:12:08.797   754  1476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:12:08.797   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:12:08.797  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:12:08.797  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:12:08.797   754   754 I MotionRecognitionService: Plugged
,06-30 14:12:08.797   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:12:08.807  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:12:08.807  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
06-30 14:12:08.807  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:12:08.807   754  1476 D BatteryService: stay LED for fully charged
,06-30 14:12:08.807  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:08.807  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:12:08.807  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:10.517   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:12:10.767   302   302 E SMD     : DCD ON
,06-30 14:12:13.777   302   302 E SMD     : DCD ON
,06-30 14:12:14.527   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:12:16.757   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:12:16.767   302   302 E SMD     : DCD ON
,06-30 14:12:18.527   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:12:18.847   754  1697 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:12:18.857   754  1697 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:12:18.857   754  1697 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:12:18.857   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:12:18.857  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:12:18.857  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:12:18.857   754   754 I MotionRecognitionService: Plugged
06-30 14:12:18.857   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:12:18.857  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:12:18.867  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:12:18.867  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:12:18.867   754  1697 D BatteryService: stay LED for fully charged
,06-30 14:12:18.867  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:12:18.867  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:18.867  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:19.777   302   302 E SMD     : DCD ON
,06-30 14:12:22.537   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:12:22.777   302   302 E SMD     : DCD ON
,06-30 14:12:25.767   302   302 E SMD     : DCD ON
,06-30 14:12:26.537   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:12:26.817   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:12:28.777   302   302 E SMD     : DCD ON
,06-30 14:12:28.907   754  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:12:28.907   754  1144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:12:28.917   754  1144 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:12:28.917   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:12:28.917  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:12:28.927  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:12:28.927   754   754 I MotionRecognitionService: Plugged
06-30 14:12:28.927   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:12:28.937   754  1144 D BatteryService: stay LED for fully charged
,06-30 14:12:28.937  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:12:28.937  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:28.937  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:28.937  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:12:28.947  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:12:28.957  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:30.537   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:12:31.777   302   302 E SMD     : DCD ON
,06-30 14:12:34.237   754  1320 E Watchdog: !@Sync 44
,06-30 14:12:34.557   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:12:34.777   302   302 E SMD     : DCD ON
,06-30 14:12:36.857   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:12:37.767   302   302 E SMD     : DCD ON
,06-30 14:12:38.547   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:12:38.967   754  1652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:12:38.967   754  1652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:12:38.977   754  1652 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:12:38.977   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:12:38.977   754   754 I MotionRecognitionService: Plugged
,06-30 14:12:38.977   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:12:38.977   754  1652 D BatteryService: stay LED for fully charged
,06-30 14:12:38.977  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:12:38.987  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:12:38.987  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:38.987  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:12:38.987  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:38.987  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:12:38.987  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:12:38.987  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:12:40.777   302   302 E SMD     : DCD ON
,06-30 14:12:42.567   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:12:43.777   302   302 E SMD     : DCD ON
,06-30 14:12:46.567   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:12:46.777   302   302 E SMD     : DCD ON
,06-30 14:12:46.907   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:12:49.027   754  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:12:49.777   302   302 E SMD     : DCD ON
,06-30 14:12:50.567   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:12:52.787   302   302 E SMD     : DCD ON
,06-30 14:12:54.577   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:12:55.787   302   302 E SMD     : DCD ON
,06-30 14:12:56.967   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:12:58.587   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:12:58.787   302   302 E SMD     : DCD ON
,06-30 14:12:59.087   754  1144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:12:59.087   754  1144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:12:59.087   754  1144 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:12:59.097   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,06-30 14:12:59.097  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:12:59.097  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:12:59.097   754   754 I MotionRecognitionService: Plugged
06-30 14:12:59.097   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:12:59.097  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:12:59.107  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:12:59.107  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:12:59.107   754  1144 D BatteryService: stay LED for fully charged
,06-30 14:12:59.107  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:12:59.107  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:59.107  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:01.777   302   302 E SMD     : DCD ON
,06-30 14:13:02.587   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:13:04.247   754  1320 E Watchdog: !@Sync 45
,06-30 14:13:04.787   302   302 E SMD     : DCD ON
,06-30 14:13:06.597   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:13:07.017   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:13:07.777   302   302 E SMD     : DCD ON
,06-30 14:13:09.147   754  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:13:09.147   754  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:13:09.157   754  1476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:13:09.157   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:13:09.157   754   754 I MotionRecognitionService: Plugged
,06-30 14:13:09.157   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:13:09.157   754  1476 D BatteryService: stay LED for fully charged
,06-30 14:13:09.167  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:13:09.167  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:13:09.167  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:09.167  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:13:09.167  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:09.167  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:13:09.167  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:13:09.167  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:13:10.607   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:13:10.777   302   302 E SMD     : DCD ON
,06-30 14:13:13.787   302   302 E SMD     : DCD ON
,06-30 14:13:14.607   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:13:16.797   302   302 E SMD     : DCD ON
,06-30 14:13:17.067   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:13:18.617   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:13:19.207   754  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:13:19.207   754  1570 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:13:19.217   754  1570 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:13:19.217   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:13:19.217   754   754 I MotionRecognitionService: Plugged
,06-30 14:13:19.217   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:13:19.217   754  1570 D BatteryService: stay LED for fully charged
,06-30 14:13:19.217  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:13:19.227  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:13:19.227  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:13:19.227  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:13:19.227  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:19.227  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 14:13:19.227  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:13:19.227  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:19.797   302   302 E SMD     : DCD ON
,06-30 14:13:22.627   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:13:22.787   302   302 E SMD     : DCD ON
,06-30 14:13:25.797   302   302 E SMD     : DCD ON
,06-30 14:13:26.627   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:13:27.117   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:13:28.797   302   302 E SMD     : DCD ON
,06-30 14:13:29.267   754  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:13:30.627   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:13:31.787   302   302 E SMD     : DCD ON
,06-30 14:13:34.247   754  1320 E Watchdog: !@Sync 46
,06-30 14:13:34.637   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:13:34.787   302   302 E SMD     : DCD ON
,06-30 14:13:37.157   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:13:37.787   302   302 E SMD     : DCD ON
,06-30 14:13:38.647   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:13:39.327   754  1652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:13:39.327   754  1652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:13:39.327   754  1652 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:13:39.337   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:13:39.337   754   754 I MotionRecognitionService: Plugged
,06-30 14:13:39.337   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:13:39.337   754  1652 D BatteryService: stay LED for fully charged
,06-30 14:13:39.337  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:13:39.347  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:13:39.347  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:39.347  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:13:39.347  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:39.347  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 14:13:39.347  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:13:39.347  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:40.797   302   302 E SMD     : DCD ON
,06-30 14:13:42.657   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:13:43.787   302   302 E SMD     : DCD ON
,06-30 14:13:46.647   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:13:46.787   302   302 E SMD     : DCD ON
,06-30 14:13:47.207   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:13:49.387   754   783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:13:49.387   754   783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:13:49.387   754   783 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:13:49.397   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:13:49.397   754   754 I MotionRecognitionService: Plugged
,06-30 14:13:49.397   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:13:49.397   754   783 D BatteryService: stay LED for fully charged
,06-30 14:13:49.397  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:13:49.407  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:13:49.407  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:13:49.407  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:13:49.407  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:13:49.407  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:49.407  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:13:49.407  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:49.787   302   302 E SMD     : DCD ON
,06-30 14:13:50.667   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:13:52.797   302   302 E SMD     : DCD ON
,06-30 14:13:54.667   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:13:55.807   302   302 E SMD     : DCD ON
,06-30 14:13:57.257   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:13:58.677   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:13:58.807   302   302 E SMD     : DCD ON
,06-30 14:13:59.447   754  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:14:00.027   754  1050 I PowerManagerService: [PWL] Off : 1380s ago
,06-30 14:14:01.807   302   302 E SMD     : DCD ON
,06-30 14:14:02.677   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:14:04.257   754  1320 E Watchdog: !@Sync 47
,06-30 14:14:04.807   302   302 E SMD     : DCD ON
,06-30 14:14:06.677   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:14:07.307   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:14:07.797   302   302 E SMD     : DCD ON
,06-30 14:14:09.507   754  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:14:09.517   754  1421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:14:09.517   754  1421 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:14:09.517   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:14:09.527  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:14:09.527  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:14:09.527   754   754 I MotionRecognitionService: Plugged
,06-30 14:14:09.527   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:14:09.537   754  1421 D BatteryService: stay LED for fully charged
,06-30 14:14:09.537  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:14:09.537  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:14:09.537  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:14:09.557  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:09.557  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:09.557  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:10.687   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:14:10.797   302   302 E SMD     : DCD ON
,06-30 14:14:13.797   302   302 E SMD     : DCD ON
,06-30 14:14:14.687   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:14:16.807   302   302 E SMD     : DCD ON
,06-30 14:14:17.357   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:14:18.697   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:14:19.567   754  1553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:14:19.577   754  1553 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:14:19.577   754  1553 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:14:19.577   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:14:19.587  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:14:19.587   754   754 I MotionRecognitionService: Plugged
,06-30 14:14:19.587  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:14:19.587   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:14:19.597   754  1553 D BatteryService: stay LED for fully charged
,06-30 14:14:19.597  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:14:19.597  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:19.597  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:14:19.597  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:14:19.617  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:19.617  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:19.807   302   302 E SMD     : DCD ON
,06-30 14:14:22.697   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:14:22.817   302   302 E SMD     : DCD ON
,06-30 14:14:25.807   302   302 E SMD     : DCD ON
,06-30 14:14:26.707   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:14:27.437   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:14:28.817   302   302 E SMD     : DCD ON
,06-30 14:14:29.627   754  1246 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:14:30.707   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:14:31.817   302   302 E SMD     : DCD ON
,06-30 14:14:34.247   754  1320 E Watchdog: !@Sync 48
,06-30 14:14:34.727   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:14:34.817   302   302 E SMD     : DCD ON
,06-30 14:14:37.477   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:14:37.807   302   302 E SMD     : DCD ON
,06-30 14:14:38.717   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:14:39.687   754  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:14:39.697   754  1421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:14:39.697   754  1421 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:14:39.697   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:14:39.697  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:14:39.697  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:14:39.697   754   754 I MotionRecognitionService: Plugged
,06-30 14:14:39.697   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:14:39.707  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:14:39.707  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
06-30 14:14:39.707  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:14:39.707   754  1421 D BatteryService: stay LED for fully charged
,06-30 14:14:39.707  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:39.707  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:14:39.707  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:40.817   302   302 E SMD     : DCD ON
,06-30 14:14:42.737   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:14:43.817   302   302 E SMD     : DCD ON
,06-30 14:14:46.737   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:14:46.817   302   302 E SMD     : DCD ON
,06-30 14:14:47.527   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:14:49.747   754  1697 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:14:49.747   754  1697 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:14:49.757   754  1697 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:14:49.757   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:14:49.757   754   754 I MotionRecognitionService: Plugged
,06-30 14:14:49.757   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:14:49.757  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:14:49.767  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:14:49.767  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:49.767   754  1697 D BatteryService: stay LED for fully charged
,06-30 14:14:49.767  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:49.767  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:49.767  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:14:49.767  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
06-30 14:14:49.767  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:14:49.807   302   302 E SMD     : DCD ON
,06-30 14:14:50.747   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:14:52.807   302   302 E SMD     : DCD ON
,06-30 14:14:54.747   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:14:55.807   302   302 E SMD     : DCD ON
,06-30 14:14:57.567   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:14:58.747   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:14:58.807   302   302 E SMD     : DCD ON
,06-30 14:14:59.807   754  1246 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:15:01.827   302   302 E SMD     : DCD ON
,06-30 14:15:02.757   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:15:04.257   754  1320 E Watchdog: !@Sync 49
,06-30 14:15:04.827   302   302 E SMD     : DCD ON
,06-30 14:15:06.757   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:15:07.617   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:15:07.827   302   302 E SMD     : DCD ON
,06-30 14:15:09.867   754  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:15:10.777   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:15:10.827   302   302 E SMD     : DCD ON
,06-30 14:15:13.827   302   302 E SMD     : DCD ON
,06-30 14:15:14.767   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:15:16.817   302   302 E SMD     : DCD ON
,06-30 14:15:17.667   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:15:18.787   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:15:19.827   302   302 E SMD     : DCD ON
,06-30 14:15:19.927   754  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:15:19.927   754  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:15:19.937   754  1343 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:15:19.937   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:15:19.937   754   754 I MotionRecognitionService: Plugged
,06-30 14:15:19.937   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:15:19.937   754  1343 D BatteryService: stay LED for fully charged
,06-30 14:15:19.937  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:15:19.947  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:15:19.947  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:15:19.947  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:15:19.947  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:15:19.947  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 14:15:19.947  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:15:19.947  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:15:22.787   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:15:22.827   302   302 E SMD     : DCD ON
,06-30 14:15:25.817   302   302 E SMD     : DCD ON
,06-30 14:15:26.787   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:15:27.717   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:15:28.827   302   302 E SMD     : DCD ON
,06-30 14:15:29.987   754  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:15:30.797   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:15:31.547   754  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 14:15:31.547   754  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 14:15:31.547   754  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:15:31.817   302   302 E SMD     : DCD ON
,06-30 14:15:33.757   754  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 14:15:33.757   754  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:15:33.757   754  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:15:33.767   754  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:15:34.267   754  1320 E Watchdog: !@Sync 50
,06-30 14:15:34.807   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:15:34.827   302   302 E SMD     : DCD ON
,06-30 14:15:37.757   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:15:37.837   302   302 E SMD     : DCD ON
,06-30 14:15:38.807   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:15:40.047   754  1697 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:15:40.047   754  1697 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:15:40.057   754  1697 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:15:40.057   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:15:40.057  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:15:40.057  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:15:40.057   754   754 I MotionRecognitionService: Plugged
,06-30 14:15:40.057   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:15:40.067  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:15:40.067   754  1697 D BatteryService: stay LED for fully charged
,06-30 14:15:40.067  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:15:40.067  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:15:40.067  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:15:40.067  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
06-30 14:15:40.067  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:15:40.837   302   302 E SMD     : DCD ON
,06-30 14:15:42.807   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:15:43.837   302   302 E SMD     : DCD ON
,06-30 14:15:46.817   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:15:46.827   302   302 E SMD     : DCD ON
,06-30 14:15:47.807   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:15:49.827   302   302 E SMD     : DCD ON
,06-30 14:15:50.117   754  1246 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:15:50.817   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:15:52.827   302   302 E SMD     : DCD ON
,06-30 14:15:54.837   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:15:55.837   302   302 E SMD     : DCD ON
,06-30 14:15:57.857   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:15:58.837   302   302 E SMD     : DCD ON
,06-30 14:15:58.837   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:16:00.037   754  1050 I PowerManagerService: [PWL] Off : 1500s ago
,06-30 14:16:00.177   754  1357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:16:01.837   302   302 E SMD     : DCD ON
,06-30 14:16:02.847   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:16:04.267   754  1320 E Watchdog: !@Sync 51
,06-30 14:16:04.837   302   302 E SMD     : DCD ON
,06-30 14:16:06.847   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:16:07.837   302   302 E SMD     : DCD ON
,06-30 14:16:07.907   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:16:10.237   754  1571 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:16:10.837   302   302 E SMD     : DCD ON
,06-30 14:16:10.857   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:16:13.827   302   302 E SMD     : DCD ON
,06-30 14:16:14.857   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:16:16.827   302   302 E SMD     : DCD ON
,06-30 14:16:17.957   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:16:18.857   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:16:19.837   302   302 E SMD     : DCD ON
,06-30 14:16:20.297   754  1652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:16:22.837   302   302 E SMD     : DCD ON
,06-30 14:16:22.867   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:16:25.837   302   302 E SMD     : DCD ON
,06-30 14:16:26.877   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:16:27.997   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:16:28.837   302   302 E SMD     : DCD ON
,06-30 14:16:30.357   754  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:16:30.877   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:16:31.847   302   302 E SMD     : DCD ON
,06-30 14:16:34.267   754  1320 E Watchdog: !@Sync 52
,06-30 14:16:34.847   302   302 E SMD     : DCD ON
,06-30 14:16:34.877   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:16:37.847   302   302 E SMD     : DCD ON
,06-30 14:16:38.047   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:16:38.887   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:16:40.417   754  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:16:40.427   754  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:16:40.427   754  1476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:16:40.427   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:16:40.437   754   754 I MotionRecognitionService: Plugged
,06-30 14:16:40.437   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:16:40.437   754  1476 D BatteryService: stay LED for fully charged
,06-30 14:16:40.437  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:16:40.437  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:16:40.437  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:16:40.447  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:16:40.447  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:16:40.457  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:16:40.457  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:16:40.457  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:16:40.837   302   302 E SMD     : DCD ON
,06-30 14:16:42.897   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:16:43.837   302   302 E SMD     : DCD ON
,06-30 14:16:46.847   302   302 E SMD     : DCD ON
,06-30 14:16:46.907   754  1553 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:16:48.097   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:16:49.847   302   302 E SMD     : DCD ON
,06-30 14:16:50.477   754   783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:16:50.477   754   783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 14:16:50.477   754   783 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:16:50.477   754   783 D BatteryService: stay LED for fully charged
06-30 14:16:50.477   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:16:50.477  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:16:50.477  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:16:50.477   754   754 I MotionRecognitionService: Plugged
06-30 14:16:50.477   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:16:50.477  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:16:50.477  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:16:50.487  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:16:50.487  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:16:50.487  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 14:16:50.487  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:16:50.897   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:16:52.847   302   302 E SMD     : DCD ON
,06-30 14:16:54.917   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:16:55.847   302   302 E SMD     : DCD ON
,06-30 14:16:58.137   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:16:58.857   302   302 E SMD     : DCD ON
,06-30 14:16:58.907   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:17:00.537   754  1378 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:17:00.537   754  1378 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:17:00.537   754  1378 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:17:00.537   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:17:00.547  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:17:00.547  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:17:00.547   754   754 I MotionRecognitionService: Plugged
,06-30 14:17:00.547   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:17:00.557   754  1378 D BatteryService: stay LED for fully charged
,06-30 14:17:00.557  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:17:00.557  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:17:00.557  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:17:00.557  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:17:00.577  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:17:00.577  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:17:01.857   302   302 E SMD     : DCD ON
,06-30 14:17:02.917   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:17:04.277   754  1320 E Watchdog: !@Sync 53
,06-30 14:17:04.857   302   302 E SMD     : DCD ON
,06-30 14:17:06.917   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:17:07.847   302   302 E SMD     : DCD ON
,06-30 14:17:08.187   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:17:10.597   754   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:17:10.597   754   781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:17:10.597   754   781 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:17:10.597   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:17:10.607  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:17:10.607  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:17:10.607   754   754 I MotionRecognitionService: Plugged
,06-30 14:17:10.607   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:17:10.617   754   781 D BatteryService: stay LED for fully charged
,06-30 14:17:10.617  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:17:10.617  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:17:10.617  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:17:10.627  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:17:10.627  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:17:10.637  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:17:10.857   302   302 E SMD     : DCD ON
,06-30 14:17:10.937   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:17:13.847   302   302 E SMD     : DCD ON
,06-30 14:17:14.927   754  1570 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:17:16.857   302   302 E SMD     : DCD ON
,06-30 14:17:18.237   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:17:18.937   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:17:19.857   302   302 E SMD     : DCD ON
,06-30 14:17:20.657   754  1652 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:17:20.657   754  1652 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:17:20.657   754  1652 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:17:20.657   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:17:20.667   754   754 I MotionRecognitionService: Plugged
,06-30 14:17:20.667  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:17:20.667  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:17:20.667   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:17:20.677   754  1652 D BatteryService: stay LED for fully charged
,06-30 14:17:20.677  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:17:20.677  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:17:20.677  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:17:20.697  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:17:20.697  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:17:20.697  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:17:22.857   302   302 E SMD     : DCD ON
,06-30 14:17:22.937   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:17:25.857   302   302 E SMD     : DCD ON
,06-30 14:17:26.947   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:17:28.277   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:17:28.847   302   302 E SMD     : DCD ON
,06-30 14:17:30.707   754  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:17:30.957   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:17:31.847   302   302 E SMD     : DCD ON
,06-30 14:17:34.277   754  1320 E Watchdog: !@Sync 54
,06-30 14:17:34.857   302   302 E SMD     : DCD ON
,06-30 14:17:34.967   754  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:17:37.867   302   302 E SMD     : DCD ON
,06-30 14:17:38.327   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:17:38.977   754  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:17:40.767   754   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:17:40.767   754   781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:17:40.767   754   781 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:17:40.777   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:17:40.777   754   754 I MotionRecognitionService: Plugged
,06-30 14:17:40.777   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:17:40.777   754   781 D BatteryService: stay LED for fully charged
,06-30 14:17:40.777  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:17:40.787  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:17:40.787  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:17:40.787  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:17:40.787  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:17:40.787  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:17:40.787  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:17:40.787  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:17:40.857   302   302 E SMD     : DCD ON
,06-30 14:17:42.977   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:17:43.867   302   302 E SMD     : DCD ON
,06-30 14:17:46.867   302   302 E SMD     : DCD ON
,06-30 14:17:46.987   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:17:48.377   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:17:49.857   302   302 E SMD     : DCD ON
,06-30 14:17:50.827   754  1357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:17:50.997   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:17:52.867   302   302 E SMD     : DCD ON
,06-30 14:17:54.997   754  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:17:55.857   302   302 E SMD     : DCD ON
,06-30 14:17:58.427   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:17:58.867   302   302 E SMD     : DCD ON
,06-30 14:17:59.007   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:18:00.887   754  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:18:00.897   754  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:18:00.897   754  1343 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:18:00.897   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:18:00.897   754   754 I MotionRecognitionService: Plugged
06-30 14:18:00.897   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:18:00.897   754  1343 D BatteryService: stay LED for fully charged
,06-30 14:18:00.907  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:18:00.907  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:18:00.907  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:18:00.907  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:18:00.907  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:18:00.907  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:18:00.907  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:18:00.907  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:18:01.857   302   302 E SMD     : DCD ON
,06-30 14:18:03.007   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:18:04.277   754  1320 E Watchdog: !@Sync 55
,06-30 14:18:04.857   302   302 E SMD     : DCD ON
,06-30 14:18:05.037   754  1050 I PowerManagerService: [PWL] Off : 1625s ago
,06-30 14:18:07.017   754  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:18:07.867   302   302 E SMD     : DCD ON
,06-30 14:18:08.477   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:18:10.867   302   302 E SMD     : DCD ON
,06-30 14:18:10.947   754  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:18:10.957   754  1584 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:18:10.957   754  1584 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:18:10.957   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:18:10.967  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:18:10.967   754   754 I MotionRecognitionService: Plugged
,06-30 14:18:10.967  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:18:10.967   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:18:10.977   754  1584 D BatteryService: stay LED for fully charged
,06-30 14:18:10.977  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:18:10.977  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:18:10.977  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:18:10.977  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:18:10.987  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:18:10.987  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:18:11.007   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:18:13.867   302   302 E SMD     : DCD ON
,06-30 14:18:15.017   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:18:16.867   302   302 E SMD     : DCD ON
,06-30 14:18:18.527   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:18:19.027   754   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:18:19.877   302   302 E SMD     : DCD ON
,06-30 14:18:21.007   754  1357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:18:21.017   754  1357 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 14:18:21.017   754  1357 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,06-30 14:18:21.017   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:18:21.027  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:18:21.027  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:18:21.027   754   754 I MotionRecognitionService: Plugged
,06-30 14:18:21.027   754   754 I MotionRecognitionService: setPowerConnected  = true
,06-30 14:18:21.027   754  1357 D BatteryService: stay LED for fully charged
,06-30 14:18:21.037  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 14:18:21.037  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 14:18:21.037  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
,06-30 14:18:21.037  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:18:21.057  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:18:21.057  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:18:22.867   302   302 E SMD     : DCD ON
,06-30 14:18:23.027   754  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:18:25.877   302   302 E SMD     : DCD ON
,06-30 14:18:27.027   754  1571 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:18:28.577   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:18:28.877   302   302 E SMD     : DCD ON
,06-30 14:18:31.047   754  1378 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:18:31.077   754  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:18:31.877   302   302 E SMD     : DCD ON
,06-30 14:18:34.277   754  1320 E Watchdog: !@Sync 56
,06-30 14:18:34.867   302   302 E SMD     : DCD ON
,06-30 14:18:35.047   754  1544 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:18:37.877   302   302 E SMD     : DCD ON
,06-30 14:18:38.627   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:18:39.047   754  1421 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:18:40.877   302   302 E SMD     : DCD ON
,06-30 14:18:41.127   754  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:18:43.047   754  1246 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:18:43.867   302   302 E SMD     : DCD ON
,06-30 14:18:46.867   302   302 E SMD     : DCD ON
,06-30 14:18:47.057   754  1343 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 14:18:48.677   754  3297 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,06-30 14:18:49.887   302   302 E SMD     : DCD ON
,TIME-OUT KILL (timeout was 1400000ms),06-30 14:18:50.577  8265  8265 D AndroidRuntime: 
06-30 14:18:50.577  8265  8265 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 14:18:50.587  8265  8265 D AndroidRuntime: CheckJNI is OFF
06-30 14:18:50.587  8265  8265 D AndroidRuntime: readGMSProperty: start
06-30 14:18:50.587  8265  8265 D AndroidRuntime: readGMSProperty: already setted!!
06-30 14:18:50.587  8265  8265 D AndroidRuntime: readGMSProperty: end
06-30 14:18:50.587  8265  8265 D AndroidRuntime: addProductProperty: start
06-30 14:18:50.717  8265  8265 E AffinityControl: AffinityControl: registerfunction enter
06-30 14:18:50.737  8265  8265 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 14:18:50.747   754  1697 D PackageManager: START PACKAGE DELETE: observer{306335991}
06-30 14:18:50.747   754  1697 D PackageManager: pkg{<packageName>}
06-30 14:18:50.747   754  1697 D PackageManager: user{0}
06-30 14:18:50.747   754  1697 D PackageManager: caller{2000}
06-30 14:18:50.747   754  1697 D PackageManager: flags{2}
06-30 14:18:50.747   754  1697 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
06-30 14:18:50.747   754  1697 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-30 14:18:50.747   754  1697 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-30 14:18:50.747   754  1697 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 14:18:50.747   754  1697 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 14:18:50.747   754  1065 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-30 14:18:50.747   754  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
06-30 14:18:50.747   754  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
06-30 14:18:50.747   754  1065 D ApplicationPolicy: getApplicationUninstallationEnabled
06-30 14:18:50.747   754  1065 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
06-30 14:18:50.747   754  1065 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
06-30 14:18:50.747   754  1007 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
06-30 14:18:50.747   754  1007 I ActivityManager: Killing 7447:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
06-30 14:18:50.757   754  1007 I ActivityManager:   Force finishing activity ActivityRecord{804c7a1 u0 com.test.thalitest/.MainActivity t23}
06-30 14:18:50.757   754  1007 D FocusedStackFrame: Set to : 0
06-30 14:18:50.767   266   407 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
06-30 14:18:50.767   266   950 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
06-30 14:18:50.887   754  3297 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 14:18:50.897   754  3297 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 14:18:50.897   754  1065 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
06-30 14:18:50.937  5372  5372 I art     : Explicit concurrent mark sweep GC freed 35559(1946KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 15MB/26MB, paused 423us total 27.902ms
06-30 14:18:50.947  1490  1490 I art     : Explicit concurrent mark sweep GC freed 2400(201KB) AllocSpace objects, 2(40KB) LOS objects, 40% free, 20MB/33MB, paused 422us total 26.107ms
06-30 14:18:50.957  5780  5780 I art     : Explicit concurrent mark sweep GC freed 1832(108KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/21MB, paused 311us total 39.179ms
06-30 14:18:50.957  5287  5287 I art     : Explicit concurrent mark sweep GC freed 693(39KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 320us total 32.899ms
06-30 14:18:50.957  6454  6454 I art     : Explicit concurrent mark sweep GC freed 20067(2MB) AllocSpace objects, 2(40KB) LOS objects, 31% free, 17MB/25MB, paused 465us total 34.246ms
06-30 14:18:50.957   754  1045 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
06-30 14:18:50.967   754  1122 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-30 14:18:50.967  1757  1757 E SamsungIME: mOCRHelper is null
06-30 14:18:50.967  1449  1449 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
06-30 14:18:50.967  1449  1449 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 14:18:50.967  1449  1449 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
06-30 14:18:50.967  1997  2317 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-30 14:18:50.967  1449  1449 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
06-30 14:18:50.977  1449  1449 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 14:18:50.977  1449  1449 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 14:18:50.977  1449  1449 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
06-30 14:18:50.977  1449  1449 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
06-30 14:18:50.987  1449  1449 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 14:18:50.987  1449  1449 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
06-30 14:18:50.987  1411  1411 D RegisteredServicesCache: empty dynamic service
06-30 14:18:50.987   754  1146 V NetworkStats: removeUidsLocked() for UIDs [10079]
06-30 14:18:50.987   754  1146 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 14:18:50.987   754  1146 V NetworkStats: performPollLocked(flags=0x3)
06-30 14:18:50.987   754  1146 D NetworkStatsFactory: UpdateStatsForKnox
06-30 14:18:50.987   754  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 14:18:50.987  2602  2602 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
06-30 14:18:50.987   754  1146 V NetworkStats: performPollLocked() took 5ms
06-30 14:18:50.987   754  1146 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 14:18:50.987   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 14:18:50.987   754  1147 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 14:18:51.017  2602  2602 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1467289131019
06-30 14:18:51.027  2602  2602 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
06-30 14:18:51.027  2602  2602 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
06-30 14:18:51.037   754  3190 E libprocessgroup: failed to kill 1 processes for processgroup 7447
06-30 14:18:51.057   754  1697 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 14:18:51.067   754   754 I art     : Explicit concurrent mark sweep GC freed 36907(3MB) AllocSpace objects, 66(1056KB) LOS objects, 30% free, 36MB/52MB, paused 1.605ms total 139.962ms
06-30 14:18:51.077   754   754 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
06-30 14:18:51.077   754  1065 I art     : WaitForGcToComplete blocked for 86.441ms for cause Explicit
06-30 14:18:51.097   754   754 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
06-30 14:18:51.107   754   754 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
06-30 14:18:51.107   754  1421 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
06-30 14:18:51.107   754  1421 D SecContentProvider2: mCursor = null
06-30 14:18:51.117   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
06-30 14:18:51.117   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
06-30 14:18:51.127   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
06-30 14:18:51.127   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
06-30 14:18:51.127   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
06-30 14:18:51.137   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
06-30 14:18:51.147   754   754 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
06-30 14:18:51.157  2602  2602 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
06-30 14:18:51.157   754   754 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
06-30 14:18:51.157   754   754 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
06-30 14:18:51.167  2602  2602 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
06-30 14:18:51.167   754  1553 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
06-30 14:18:51.167   754  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.167   754  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.167   754  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.167   754  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.177   754   754 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
06-30 14:18:51.177   754  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:18:51.177   754  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 14:18:51.177   754  1343 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
06-30 14:18:51.177   754  1343 D BatteryService: stay LED for fully charged
06-30 14:18:51.177   754   754 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
06-30 14:18:51.177   754   754 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
06-30 14:18:51.177   754   754 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
06-30 14:18:51.177   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
06-30 14:18:51.187   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
06-30 14:18:51.187   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
06-30 14:18:51.197   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
06-30 14:18:51.197   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
06-30 14:18:51.197   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
06-30 14:18:51.207   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
06-30 14:18:51.207   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
06-30 14:18:51.207  8293  8293 E Zygote  : MountEmulatedStorage()
06-30 14:18:51.207  8293  8293 E Zygote  : v2
06-30 14:18:51.207  8293  8293 I libpersona: KNOX_SDCARD checking this for 10116
06-30 14:18:51.207  8293  8293 I libpersona: KNOX_SDCARD not a persona
06-30 14:18:51.207   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
06-30 14:18:51.217   754  1553 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8293 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
06-30 14:18:51.217   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
06-30 14:18:51.227   754   754 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
06-30 14:18:51.227  8293  8293 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 14:18:51.227  8293  8293 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 14:18:51.227  8293  8293 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 14:18:51.227   754   754 D RCPManagerService: PackageReceiver onReceive()
06-30 14:18:51.227   754   754 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
06-30 14:18:51.227   754   754 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
06-30 14:18:51.227   754   754 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 14:18:51.227   754   754 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-30 14:18:51.227   754   754 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
06-30 14:18:51.227   754   754 V EnterpriseBillingPolicy: uID is 10079
06-30 14:18:51.227   754   754 V EnterpriseBillingPolicy: Removed Packageuid is0
06-30 14:18:51.227   754   754 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
06-30 14:18:51.227   754   754 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
06-30 14:18:51.227   754   754 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-30 14:18:51.227   754   754 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-30 14:18:51.227   754   754 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
06-30 14:18:51.237   754   754 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
06-30 14:18:51.237   754   754 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
06-30 14:18:51.237   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:18:51.237   754  1179 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
06-30 14:18:51.237  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:18:51.237  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 14:18:51.237  3234  3234 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 14:18:51.237  3234  7978 D HeadsetStateMachine: Disconnected process message: 10
06-30 14:18:51.237  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
06-30 14:18:51.237  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:18:51.247  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:18:51.247  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:18:51.257  8293  8293 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 14:18:51.257  8293  8293 D ActivityThread: Added TimaKeyStore provider
06-30 14:18:51.287  8293  8293 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
06-30 14:18:51.287  1449  1449 D SurfaceWidgetView: destroyHardwareResources():573337542
06-30 14:18:51.287   754  3297 I SQLiteConnectionPool: exportDB...
06-30 14:18:51.297   754   754 I MotionRecognitionService: Plugged
06-30 14:18:51.297  1449  1449 D Launcher: onRestart, Launcher: 614775439
06-30 14:18:51.297   754   754 I MotionRecognitionService: setPowerConnected  = true
06-30 14:18:51.297  1449  1449 D Launcher: onStart, Launcher: 614775439
06-30 14:18:51.297  1449  1449 D Launcher.HomeView: onStart
06-30 14:18:51.297  1449  1449 V ActivityThread: updateVisibility : ActivityRecord{1f158be6 token=android.os.BinderProxy@8e4051d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
06-30 14:18:51.297  1792  2134 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
06-30 14:18:51.297  1792  2098 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
06-30 14:18:51.297  1792  2098 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
06-30 14:18:51.297   754  1065 I art     : Explicit concurrent mark sweep GC freed 11415(631KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 36MB/52MB, paused 3.986ms total 227.603ms
06-30 14:18:51.307  8293  8293 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
06-30 14:18:51.307  8293  8293 D elm:14491: ELMEngine.ELMEngine( context ).
06-30 14:18:51.307  8293  8293 D elm:14491: MDMBridge.setEnterpriseBridge()
06-30 14:18:51.307   754  1378 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
06-30 14:18:51.307   754  1378 D ActivityManager: caller:android.app.ApplicationThreadProxy@b281bec, r.packageName :com.sec.esdk.elm
06-30 14:18:51.307   266   266 I SurfaceFlinger: id=15 createSurf (1080x1920),1 flag=4, Mauncher
06-30 14:18:51.327  8293  8293 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
06-30 14:18:51.327  3849  3849 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
06-30 14:18:51.327  3849  3849 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 14:18:51.327  3849  3849 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
06-30 14:18:51.327  3849  3849 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
06-30 14:18:51.327  3849  3849 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
06-30 14:18:51.327  3849  3849 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
06-30 14:18:51.327  3849  3849 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
06-30 14:18:51.327  3849  3849 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:18:51.327  3849  3849 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 14:18:51.327  3849  3849 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 14:18:51.327  3849  3849 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 14:18:51.327  3849  3849 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 14:18:51.327  3849  3849 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 14:18:51.327  3849  3849 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 14:18:51.337  8293  8293 D elm:14491: ElmAgentService : onCreate()
06-30 14:18:51.337  8293  8312 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
06-30 14:18:51.337  8293  8312 D elm:14491: MainReceiver.listeningToPackageRemoved()
06-30 14:18:51.337  8293  8312 D elm:14491: MDMBridge.getInstance()
06-30 14:18:51.337  8293  8312 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
06-30 14:18:51.337  8293  8312 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
06-30 14:18:51.347  1627  1627 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
06-30 14:18:51.347  1627  1627 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
06-30 14:18:51.347   754   781 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 14:18:51.347   754  1116 V AlarmManager: waitForAlarm result :4
06-30 14:18:51.357   754  3297 I SQLiteConnectionPool: ...exportDB
06-30 14:18:51.367  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 14:18:51.367   754  3297 D SSRM:aY : MSG_TYPE_APP_REMOVED::
06-30 14:18:51.367  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:18:51.367  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
06-30 14:18:51.367  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
06-30 14:18:51.377   754   781 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 14:18:51.377   754   781 D ActivityManager: caller:android.app.ApplicationThreadProxy@1c57fc84, r.packageName :com.google.android.gms
06-30 14:18:51.377  8293  8293 D elm:14491: ElmAgentService : onDestroy().
06-30 14:18:51.377  2217  8316 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
06-30 14:18:51.377  2217  8316 D AccountUtils: Clearing selected account for com.test.thalitest
06-30 14:18:51.387  2217  2217 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
06-30 14:18:51.387  2217  2217 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
06-30 14:18:51.387  2217  2217 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-30 14:18:51.387  2217  2217 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
06-30 14:18:51.387   754  1584 D ActivityManager: caller:android.app.ApplicationThreadProxy@356210a2, r.packageName :com.google.android.gms
06-30 14:18:51.397   754  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3432e399 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t20} time:1716121
06-30 14:18:51.397   754  1045 D MultiWindowConverter: MultiWindow Gesture is not supported with launcher
06-30 14:18:51.397   754  1553 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 14:18:51.397   754  1553 D ActivityManager: caller:android.app.ApplicationThreadProxy@19a5cf0, r.packageName :com.google.android.gms
06-30 14:18:51.397   754  1544 D ActivityManager: caller:android.app.ApplicationThreadProxy@7f494ee, r.packageName :com.google.android.gms
06-30 14:18:51.407  2217  8316 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
06-30 14:18:51.407   754  1476 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
06-30 14:18:51.407   754  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@208303ab, r.packageName :com.google.android.gms
06-30 14:18:51.417   754  1652 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 14:18:51.417   754  1652 D ActivityManager: caller:android.app.ApplicationThreadProxy@220375a1, r.packageName :com.google.android.gms
06-30 14:18:51.417   754  1652 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.417   754  1652 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.417   754  1652 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.417   754  1652 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.417  2217  2217 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
06-30 14:18:51.417  2217  2217 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
06-30 14:18:51.417  2217  2217 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-30 14:18:51.417  2217  2217 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
06-30 14:18:51.427  2217  8319 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
06-30 14:18:51.427  2217  8319 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
06-30 14:18:51.427  2217  8319 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
06-30 14:18:51.427  2217  8319 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
06-30 14:18:51.437  2217  8319 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
06-30 14:18:51.437  2217  8319 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
06-30 14:18:51.437  2217  8319 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
06-30 14:18:51.437  2217  8319 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
06-30 14:18:51.437  2217  8319 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
06-30 14:18:51.447  2217  8319 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
06-30 14:18:51.457   754  1065 D PackageManager: delete codoeFile: 
06-30 14:18:51.457  8321  8321 E Zygote  : MountEmulatedStorage()
06-30 14:18:51.457  8321  8321 I libpersona: KNOX_SDCARD checking this for 10015
06-30 14:18:51.457  8321  8321 E Zygote  : v2
06-30 14:18:51.457  8321  8321 I libpersona: KNOX_SDCARD not a persona
06-30 14:18:51.457   754  1652 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=8321 uid=10015 gids={50015, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
06-30 14:18:51.467   754  1065 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
06-30 14:18:51.467   754  1065 I AASA_removePackage: UID=10079 Target=com.test.thalitest
06-30 14:18:51.467   754  1065 D PackageManager: result of delete: 1{306335991}
06-30 14:18:51.487  8321  8321 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 14:18:51.487  8321  8321 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 14:18:51.487  8321  8321 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
06-30 14:18:51.487  8265  8265 D AndroidRuntime: Shutting down VM
06-30 14:18:51.497   754  1652 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.service.health, hostingType: broadcast
06-30 14:18:51.497   754  1652 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.497   754  1652 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.497   754  1652 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.497   754  1652 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.517  8321  8321 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 14:18:51.517  8321  8321 D ActivityThread: Added TimaKeyStore provider
06-30 14:18:51.537  8337  8337 E Zygote  : MountEmulatedStorage()
06-30 14:18:51.537  8337  8337 E Zygote  : v2
06-30 14:18:51.537  8337  8337 I libpersona: KNOX_SDCARD checking this for 10021
06-30 14:18:51.537  8337  8337 I libpersona: KNOX_SDCARD not a persona
06-30 14:18:51.547   754  1652 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8337 uid=10021 gids={50021, 9997} abi=armeabi-v7a
06-30 14:18:51.547  8337  8337 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 14:18:51.547  8337  8337 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 14:18:51.547  8337  8337 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 14:18:51.557  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
06-30 14:18:51.567  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
06-30 14:18:51.567  8337  8337 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 14:18:51.567  8337  8337 D ActivityThread: Added TimaKeyStore provider
06-30 14:18:51.567  8321  8321 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
06-30 14:18:51.577  8321  8321 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 14:18:51.577  8321  8321 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-30 14:18:51.587   754  1357 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 14:18:51.587   754  1357 D ActivityManager: caller:android.app.ApplicationThreadProxy@3fc0cadd, r.packageName :com.google.android.gms
06-30 14:18:51.587  8337  8337 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
06-30 14:18:51.587  1627  1627 I ConfigService: onCreate
06-30 14:18:51.587  1627  1627 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-30 14:18:51.587   754  1144 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 14:18:51.597   754  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@2ba6159e, r.packageName :com.google.android.gms
06-30 14:18:51.597  2217  2217 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
06-30 14:18:51.597   754  1697 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 14:18:51.597   754  1697 D ActivityManager: caller:android.app.ApplicationThreadProxy@6d9edaa, r.packageName :com.google.android.gms
06-30 14:18:51.597  1627  1627 I ConfigService: onBind returning update interface
06-30 14:18:51.607  2217  8347 E SQLiteLog: (539) recovered 2 pages from /data/data/com.google.android.gms/databases/DocList.db-journal
06-30 14:18:51.607   754  1144 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 14:18:51.607  1627  1627 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-30 14:18:51.607  1627  1627 I ConfigService: onBind returning service broker
06-30 14:18:51.607   754  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@35cad538, r.packageName :com.google.android.gms
06-30 14:18:51.617   754  1421 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 14:18:51.617   754  1421 D ActivityManager: caller:android.app.ApplicationThreadProxy@5c13a76, r.packageName :com.google.android.gms
06-30 14:18:51.617  2217  8355 I PeopleContactsSync: CP2 sync disabled
06-30 14:18:51.617  2217  4393 I Icing   : doRemovePackageData com.test.thalitest
06-30 14:18:51.627  8337  8337 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
06-30 14:18:51.627  8337  8337 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
06-30 14:18:51.627  8337  8337 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
06-30 14:18:51.627   754  1144 D ActivityManager: startProcessLocked calleePkgName: sstream.app, hostingType: broadcast
06-30 14:18:51.627   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.627   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.627   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.627   754  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 14:18:51.637  8321  8321 I MultiDex: VM with version 2.1.0 has multidex support
06-30 14:18:51.637  8321  8321 I MultiDex: install
06-30 14:18:51.637  8321  8321 I MultiDex: VM has multidex support, MultiDex support library is disabled.
06-30 14:18:51.667  8358  8358 E Zygote  : MountEmulatedStorage()
06-30 14:18:51.667  8358  8358 E Zygote  : v2
06-30 14:18:51.667  8358  8358 I libpersona: KNOX_SDCARD checking this for 10025
06-30 14:18:51.667  8358  8358 I libpersona: KNOX_SDCARD not a persona
06-30 14:18:51.677   754  1144 I ActivityManager: Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=8358 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
06-30 14:18:51.677   754  1144 I ActivityManager: Killing 6255:com.android.mms/u0a55 (adj 15): emptyCount ##41
06-30 14:18:51.697  2217  8347 W FieldDefinition: Ignoring isIndexed constraint as field also has uniqueness constraint (on just this field, and therefore SQLite will have to create an index on that. For field: com.google.android.gms.drive.database.model.ax@3afb7cdc
06-30 14:18:51.707  8358  8358 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 14:18:51.707  8358  8358 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 14:18:51.707  8358  8358 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 14:18:51.707  2217  8344 W BaseAppContext: Using Auth Proxy for data requests.
06-30 14:18:51.707  8321  8321 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
06-30 14:18:51.717  2217  8344 W BaseAppContext: Using Auth Proxy for data requests.

```
