#### Test 757892681403989_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
07-05 12:00:09.618   917   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 12:00:09.618   917   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 12:00:09.618   917   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:00:09.618   917   935 D BatteryService: stay LED for fully charged
07-05 12:00:09.618   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
07-05 12:00:09.628  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:00:09.628  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:00:09.628  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:00:09.628  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:00:09.628  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 12:00:09.628   917   917 I MotionRecognitionService: Plugged
07-05 12:00:09.628   917   917 I MotionRecognitionService: setPowerConnected  = true
07-05 12:00:09.648  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:00:09.648  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:00:09.648  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:00:10.038  7325  7325 D AndroidRuntime: 
07-05 12:00:10.038  7325  7325 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 12:00:10.048  7325  7325 D AndroidRuntime: CheckJNI is OFF
07-05 12:00:10.048  7325  7325 D AndroidRuntime: readGMSProperty: start
07-05 12:00:10.048  7325  7325 D AndroidRuntime: readGMSProperty: already setted!!
07-05 12:00:10.048  7325  7325 D AndroidRuntime: readGMSProperty: end
07-05 12:00:10.048  7325  7325 D AndroidRuntime: addProductProperty: start
07-05 12:00:10.058   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-05 12:00:10.218  7325  7325 E AffinityControl: AffinityControl: registerfunction enter
07-05 12:00:10.238  7325  7325 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 12:00:10.248   917  1372 E PersonaManagerService: inState():  stateMachine is null !!
07-05 12:00:10.248   917  1372 I PersonaManagerService: PersonaId don't exist
07-05 12:00:10.248   917  1372 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-05 12:00:10.248   917  1372 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 12:00:10.248   917  1372 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 12:00:10.248   917  1372 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-05 12:00:10.258   917  1372 W ActivityManager: mDVFSHelper.acquire()
07-05 12:00:10.258   917  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:00:10.258   917  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:00:10.258   917  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:00:10.258   917  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:00:10.318   917  1372 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7340 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 12:00:10.318  7325  7325 D AndroidRuntime: Shutting down VM
07-05 12:00:10.328  7340  7340 E Zygote  : MountEmulatedStorage()
07-05 12:00:10.328  7340  7340 E Zygote  : v2
07-05 12:00:10.328  7340  7340 I libpersona: KNOX_SDCARD checking this for 10079
07-05 12:00:10.328  7340  7340 I libpersona: KNOX_SDCARD not a persona
07-05 12:00:10.348  7340  7340 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 12:00:10.348  7340  7340 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 12:00:10.348  7340  7340 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-05 12:00:10.378  7340  7340 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:00:10.378  7340  7340 D ActivityThread: Added TimaKeyStore provider
07-05 12:00:10.378  1454  1454 V ActivityThread: updateVisibility : ActivityRecord{377200b5 token=android.os.BinderProxy@2ac6f0c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-05 12:00:10.388  1846  1871 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
07-05 12:00:10.398   917  3316 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 12:00:10.408  7340  7340 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-05 12:00:10.418   917  3316 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 12:00:10.418  1454  1454 D SurfaceWidgetView: destroyHardwareResources():570534421
07-05 12:00:10.468   266   414 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
07-05 12:00:10.468   266  1856 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
07-05 12:00:10.468  1454  1454 D Launcher: onTrimMemory. Level: 20
07-05 12:00:10.498  7340  7340 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-05 12:00:10.498  7340  7340 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
07-05 12:00:10.518  7340  7340 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6630-6632)
07-05 12:00:10.518  7340  7340 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 12:00:10.538  7340  7340 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1b27c607}
07-05 12:00:10.538  7340  7340 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:00:10.538  7340  7340 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 12:00:10.568  7340  7340 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 12:00:10.568  7340  7340 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:00:10.568  7340  7340 E SysUtils: ApplicationContext is null in ApplicationStatus
07-05 12:00:10.588  7340  7340 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-05 12:00:10.588  7340  7340 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-05 12:00:10.588  7340  7340 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
07-05 12:00:10.598  7340  7340 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-05 12:00:10.598  7340  7340 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-05 12:00:10.598  7340  7340 I Adreno-EGL: Build Date: 11/19/14 Wed
07-05 12:00:10.598  7340  7340 I Adreno-EGL: Local Branch: mybranch5813579
07-05 12:00:10.598  7340  7340 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-05 12:00:10.598  7340  7340 I Adreno-EGL: Local Patches: NONE
07-05 12:00:10.598  7340  7340 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
07-05 12:00:10.708  7340  7377 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
07-05 12:00:10.748  7340  7340 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:00:10.748  7340  7340 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 12:00:10.768  7340  7340 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-05 12:00:10.768  7340  7340 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:00:10.768  7340  7340 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:00:10.818  7340  7340 D Activity: performCreate Call secproduct feature valuefalse
07-05 12:00:10.818  7340  7340 D Activity: performCreate Call debug elastic valuetrue
07-05 12:00:10.828  7340  7396 D OpenGLRenderer: Render dirty regions requested: true
07-05 12:00:10.828   917  1332 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-05 12:00:10.828   917  1332 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-05 12:00:10.828   917  1332 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-05 12:00:10.828   917   917 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-05 12:00:10.828   917   917 D PersonaManagerService: getPersonasForUser(): returning null!
07-05 12:00:10.848   266   266 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
07-05 12:00:10.858  7340  7396 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 12:00:10.868  7340  7396 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3c8e100 ,&mEglDisplay = 1 , &mEglConfig = 8 
07-05 12:00:10.868  7340  7396 D OpenGLRenderer: Enabling debug mode 0
07-05 12:00:10.888  7340  7340 V ActivityThread: updateVisibility : ActivityRecord{12ae4bc9 token=android.os.BinderProxy@8d7d393 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-05 12:00:10.908  7340  7340 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8d7d393 time:157029
07-05 12:00:10.928   917  1050 W ActivityManager: mDVFSHelper.release()
07-05 12:00:10.928   917  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{114a8e17 u0 com.test.thalitest/.MainActivity t23} time:157048
07-05 12:00:10.938   917  1050 D MultiWindowConverter: This application or window do not support multiwindow
07-05 12:00:10.978  7340  7340 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7340
07-05 12:00:11.058  7340  7340 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-05 12:00:11.098  7340  7340 I chromium: [INFO:CONSOLE(90)] "Uncaught SyntaxError: Unexpected token function", source: file:///android_asset/www/js/thali_main.js (90)
,07-05 12:00:11.148  7340  7400 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357929472
,07-05 12:00:11.158  7340  7400 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 12:00:11.158  7340  7400 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 12:00:11.158  7340  7400 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 12:00:11.158  7340  7400 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 12:00:11.158  7340  7400 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 12:00:11.158  7340  7400 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e4b939 added. We now have 1 listener(s)
,07-05 12:00:11.158  7340  7400 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:2A:28:2D
,07-05 12:00:11.158  7340  7400 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,07-05 12:00:11.168  7340  7400 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-05 12:00:11.168  7340  7400 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-05 12:00:11.168  7340  7400 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 12:00:11.168  7340  7400 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 12:00:11.168  7340  7400 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 12:00:11.168  7340  7400 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:2A:28:2D
07-05 12:00:11.168  7340  7400 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 12:00:11.168  7340  7400 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 12:00:11.168  7340  7400 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 12:00:11.168  7340  7400 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 12:00:11.168  7340  7400 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 12:00:11.168  7340  7400 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 12:00:11.168  7340  7400 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-05 12:00:11.168  7340  7400 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2095f92c added. We now have 1 listener(s)
07-05 12:00:11.168  7340  7400 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-05 12:00:11.178  7340  7400 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,07-05 12:00:11.178  7340  7400 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-05 12:00:11.178  7340  7400 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-05 12:00:11.178  7340  7400 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 12:00:11.188  7340  7400 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:2A:28:2D
,07-05 12:00:11.188   917   934 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 12:00:11.188   301   301 E SMD     : DCD ON
,07-05 12:00:11.188  7340  7400 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 12:00:11.188  7340  7400 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:00:11.188  7340  7400 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 12:00:11.188  7340  7400 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 12:00:11.188  7340  7400 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 12:00:11.188  7340  7400 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 12:00:11.188  7340  7400 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 12:00:11.188  7340  7400 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 12:00:11.188  7340  7400 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 12:00:11.188  7340  7400 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-05 12:00:11.198  7340  7400 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-05 12:00:11.198   917  1589 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 12:00:11.198  7340  7340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 12:00:11.198   917  1508 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 12:00:11.198  7340  7340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 12:00:11.208  7340  7340 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 12:00:11.978  7340  7406 W jxcore-log: Initializing JXcore engine
,07-05 12:00:11.978  7340  7406 W jxcore-log: JXcore engine is ready
,07-05 12:00:12.018  1987  1987 E auditd  : In denial and Property audit_ondenial is set to 1 
,07-05 12:00:12.018  1987  1987 E audit   : type=1400 msg=audit(1467712812.018:203): avc:  denied  { ioctl } for  pid=7406 comm="Thread-1264" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-05 12:00:12.018  1987  1987 E audit   :  SEPF_SM-N9005_5.0-1_0032
07-05 12:00:12.018  1987  1987 E audit   : 
,07-05 12:00:12.028  1987  1987 E audit   : type=1300 msg=audit(1467712812.018:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=98ee08d8 items=0 ppid=325 ppcomm=main pid=7406 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1264" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-05 12:00:12.028  1987  1987 E audit   : type=1320 msg=audit(1467712812.018:203): 
07-05 12:00:12.028   917  1040 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
,07-05 12:00:12.028   917  1040 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,07-05 12:00:12.028   917  1008 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,07-05 12:00:12.028   917  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:00:12.028   917  1040 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
07-05 12:00:12.028   917  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:00:12.028   917  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:00:12.028   917  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:00:12.038  7340  7406 W jxcore-log: Starting JXcore engine
,07-05 12:00:12.058   917  1008 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7407 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-05 12:00:12.068  7407  7407 E Zygote  : MountEmulatedStorage()
07-05 12:00:12.068  7407  7407 E Zygote  : v2
07-05 12:00:12.068  7407  7407 I libpersona: KNOX_SDCARD checking this for 1000
07-05 12:00:12.068  7407  7407 I libpersona: KNOX_SDCARD not a persona
,07-05 12:00:12.098  7407  7407 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-05 12:00:12.098  7407  7407 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 12:00:12.098  7407  7407 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 12:00:12.118  7407  7407 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 12:00:12.118  7407  7407 D ActivityThread: Added TimaKeyStore provider
,07-05 12:00:12.138  7340  7406 W jxcore-log: Platform android
07-05 12:00:12.138  7340  7406 W jxcore-log: 
07-05 12:00:12.138  7340  7406 W jxcore-log: Process ARCH arm
07-05 12:00:12.138  7340  7406 W jxcore-log: 
,07-05 12:00:12.138  7407  7407 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,07-05 12:00:12.148  7407  7407 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-05 12:00:12.148  7407  7407 D SecurityLogAgent:  SeDenialReceiver : File path = null
,07-05 12:00:12.158   917  1665 I ActivityManager: Killing 6179:com.google.android.gm/u0a128 (adj 15): emptyCount ##41
,07-05 12:00:12.338  7340  7406 I jxcore-log: JXcore Cordova bridge is ready!
07-05 12:00:12.338  7340  7406 I jxcore-log: 
,07-05 12:00:12.338  7340  7406 W jxcore-log: JXcore engine is started
,07-05 12:00:14.198   301   301 E SMD     : DCD ON
,07-05 12:00:14.358   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:15.358   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:16.358   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:17.188   301   301 E SMD     : DCD ON
,07-05 12:00:17.358   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:18.368   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:18.438   917  3316 D SSRM:n  : SIOP:: AP = 340, PST = 358, CUR = 450
,07-05 12:00:19.358   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:00:20.198   301   301 E SMD     : DCD ON
,07-05 12:00:20.268   917  1064 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-05 12:00:22.428   917  1323 E Watchdog: !@Sync 5
,07-05 12:00:23.198   301   301 E SMD     : DCD ON
,07-05 12:00:26.198   301   301 E SMD     : DCD ON
,07-05 12:00:26.228   917  1112 V AlarmManager: waitForAlarm result :4
,07-05 12:00:26.248   917  1712 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 12:00:26.258  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 12:00:26.258  1199  1199 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 12:00:26.268  1199  1199 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 12:00:26.268  1199  1199 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 12:00:26.278   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:00:26.278   917  2696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 12:00:26.278   917  2696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:00:26.278   917  2696 D BatteryService: stay LED for fully charged
07-05 12:00:26.278   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:00:26.278   917   917 I MotionRecognitionService: Plugged
,07-05 12:00:26.278   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:00:26.288  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:00:26.288  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:00:26.298  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:00:26.298  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:00:26.298  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:00:26.298  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:00:26.298  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:00:26.298  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:00:26.308   917  1565 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-05 12:00:26.308   917  1565 D ActivityManager: caller:android.app.ApplicationThreadProxy@28f1c8c9, r.packageName :com.google.android.gms
,07-05 12:00:26.368  1199  1199 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:00:26.368  1199  1199 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:00:28.488   917  3316 D SSRM:n  : SIOP:: AP = 340, PST = 354, CUR = 450,
,07-05 12:00:29.198   301   301 E SMD     : DCD ON
,07-05 12:00:30.058   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:00:32.198   301   301 E SMD     : DCD ON
,07-05 12:00:35.198   301   301 E SMD     : DCD ON
,07-05 12:00:36.338   917  1531 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:00:37.738   917  1060 I PowerManagerService: [PWL] Off : 140s ago
,07-05 12:00:38.208   301   301 E SMD     : DCD ON
,07-05 12:00:38.538   917  3316 D SSRM:n  : SIOP:: AP = 330, PST = 351, CUR = 450
,07-05 12:00:39.368   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:40.368   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:41.198   301   301 E SMD     : DCD ON
,07-05 12:00:41.368   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:42.368   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:43.368   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:44.198   301   301 E SMD     : DCD ON
,07-05 12:00:44.368   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 12:00:46.398   917  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:00:46.398   917  1508 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:00:46.408   917  1508 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:00:46.408   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:00:46.418   917   917 I MotionRecognitionService: Plugged
,07-05 12:00:46.418   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:00:46.418  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:00:46.418  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:00:46.418  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:00:46.418  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:00:46.418  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:00:46.428  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:00:46.428  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:00:46.428   917  1508 D BatteryService: stay LED for fully charged
07-05 12:00:46.428  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:00:47.198   301   301 E SMD     : DCD ON
,07-05 12:00:48.588   917  3316 D SSRM:n  : SIOP:: AP = 330, PST = 349, CUR = 450
,07-05 12:00:50.058   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:00:50.198   301   301 E SMD     : DCD ON
,07-05 12:00:52.428   917  1323 E Watchdog: !@Sync 6
,07-05 12:00:53.208   301   301 E SMD     : DCD ON
,07-05 12:00:56.208   301   301 E SMD     : DCD ON
,07-05 12:00:56.458   917   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:00:56.458   917   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:00:56.468   917   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:00:56.468   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:00:56.468  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:00:56.468  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:00:56.468  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:00:56.478   917   917 I MotionRecognitionService: Plugged
,07-05 12:00:56.478  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:00:56.478   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:00:56.478  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:00:56.478  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:00:56.478  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:00:56.478  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:00:56.478   917   935 D BatteryService: stay LED for fully charged
,07-05 12:00:58.638   917  3316 D SSRM:n  : SIOP:: AP = 330, PST = 348, CUR = 450
,07-05 12:00:59.208   301   301 E SMD     : DCD ON
,07-05 12:00:59.988   917  1112 V AlarmManager: waitForAlarm result :8
,07-05 12:01:02.208   301   301 E SMD     : DCD ON
,07-05 12:01:05.208   301   301 E SMD     : DCD ON
,07-05 12:01:06.518   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:01:06.518   917  2696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:01:06.528   917  2696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:01:06.528   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:01:06.528  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:01:06.528  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:01:06.528  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:01:06.538  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:01:06.538   917   917 I MotionRecognitionService: Plugged
07-05 12:01:06.538   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:01:06.538  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:01:06.538  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:01:06.538  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:01:06.538  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:01:06.538   917  2696 D BatteryService: stay LED for fully charged
,07-05 12:01:08.208   301   301 E SMD     : DCD ON
,07-05 12:01:08.688   917  3316 D SSRM:n  : SIOP:: AP = 320, PST = 346, CUR = 450
,07-05 12:01:09.368   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 12:01:09.368   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 12:01:10.068   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:01:11.208   301   301 E SMD     : DCD ON
,07-05 12:01:14.208   301   301 E SMD     : DCD ON
,07-05 12:01:16.578   917  1565 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:01:16.578   917  1565 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:01:16.588   917  1565 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:01:16.588   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:01:16.588  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:01:16.588  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:01:16.588  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:01:16.598  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:01:16.598   917   917 I MotionRecognitionService: Plugged
,07-05 12:01:16.598  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:01:16.598   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:01:16.598  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:01:16.598  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:01:16.598   917  1565 D BatteryService: stay LED for fully charged
,07-05 12:01:16.598  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:01:17.208   301   301 E SMD     : DCD ON
,07-05 12:01:17.738   917  1060 I PowerManagerService: [PWL] Off : 180s ago
,07-05 12:01:18.738   917  3316 D SSRM:n  : SIOP:: AP = 320, PST = 341, CUR = 450
,07-05 12:01:19.368   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:20.208   301   301 E SMD     : DCD ON
,07-05 12:01:20.378   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:21.378   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:22.378   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:22.428   917  1323 E Watchdog: !@Sync 7
,07-05 12:01:23.208   301   301 E SMD     : DCD ON
,07-05 12:01:23.378   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:24.378   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 12:01:26.208   301   301 E SMD     : DCD ON
,07-05 12:01:26.638   917  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:01:26.638   917  1508 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:01:26.638   917  1508 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:01:26.648   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:01:26.648  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:01:26.658  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:01:26.658  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:01:26.658  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:01:26.658   917   917 I MotionRecognitionService: Plugged
07-05 12:01:26.658   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:01:26.658  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:01:26.658  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:01:26.658  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:01:26.658  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:01:26.658   917  1508 D BatteryService: stay LED for fully charged
,07-05 12:01:28.778   917  3316 D SSRM:n  : SIOP:: AP = 320, PST = 332, CUR = 450
,07-05 12:01:29.218   301   301 E SMD     : DCD ON
,07-05 12:01:29.378   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:30.068   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:01:30.378   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:31.378   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:32.218   301   301 E SMD     : DCD ON
,07-05 12:01:32.378   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:33.388   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:34.388   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 12:01:35.218   301   301 E SMD     : DCD ON
,07-05 12:01:38.218   301   301 E SMD     : DCD ON
,07-05 12:01:38.828   917  3316 D SSRM:n  : SIOP:: AP = 320, PST = 329, CUR = 450
,07-05 12:01:41.218   301   301 E SMD     : DCD ON
,07-05 12:01:44.218   301   301 E SMD     : DCD ON
,07-05 12:01:44.388   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:45.388   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:46.228   917  1112 V AlarmManager: waitForAlarm result :4
,07-05 12:01:46.258  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 12:01:46.258  1199  1199 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 12:01:46.268  1199  1199 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 12:01:46.268  1199  1199 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 12:01:46.278   917  1665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:01:46.308   917   935 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 12:01:46.308   917   935 D ActivityManager: caller:android.app.ApplicationThreadProxy@3843b70b, r.packageName :com.google.android.gms
,07-05 12:01:46.338  1199  1199 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:01:46.348  1199  1199 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:01:46.368  1651  1676 I art     : Explicit concurrent mark sweep GC freed 15014(851KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 18MB/31MB, paused 477us total 24.562ms
,07-05 12:01:46.368  2308  7477 I EventLogService: Aggregate from 1467711085231 (log), 1467711085231 (data)
,07-05 12:01:46.388   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:47.218   301   301 E SMD     : DCD ON
,07-05 12:01:47.388   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:48.388   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:48.878   917  3316 D SSRM:n  : SIOP:: AP = 320, PST = 327, CUR = 450
,07-05 12:01:49.388   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 12:01:50.068   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:01:50.218   301   301 E SMD     : DCD ON
,07-05 12:01:52.438   917  1323 E Watchdog: !@Sync 8
,07-05 12:01:53.218   301   301 E SMD     : DCD ON
,07-05 12:01:56.218   301   301 E SMD     : DCD ON
,07-05 12:01:56.338   917  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:01:58.928   917  3316 D SSRM:n  : SIOP:: AP = 320, PST = 325, CUR = 450
,07-05 12:01:59.218   301   301 E SMD     : DCD ON
,07-05 12:01:59.988   917  1112 V AlarmManager: waitForAlarm result :8
,07-05 12:02:02.218   301   301 E SMD     : DCD ON
,07-05 12:02:02.748   917  1060 I PowerManagerService: [PWL] Off : 225s ago
,07-05 12:02:04.388   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:05.228   301   301 E SMD     : DCD ON
,07-05 12:02:05.388   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:06.398   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:06.398   917  1357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:02:06.408   917  1357 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:02:06.408   917  1357 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:02:06.408   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:02:06.408  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:02:06.408  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:02:06.408   917   917 I MotionRecognitionService: Plugged
07-05 12:02:06.408   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:02:06.418  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:02:06.418   917  1357 D BatteryService: stay LED for fully charged
,07-05 12:02:06.418  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:02:06.418  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:02:06.418  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:02:06.418  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:02:06.418  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:02:07.398   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:08.228   301   301 E SMD     : DCD ON
,07-05 12:02:08.408   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:08.978   917  3316 D SSRM:n  : SIOP:: AP = 320, PST = 323, CUR = 450
,07-05 12:02:09.408   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:02:10.078   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:02:11.228   301   301 E SMD     : DCD ON
,07-05 12:02:14.228   301   301 E SMD     : DCD ON
,07-05 12:02:16.458   917  1372 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:02:16.458   917  1372 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:02:16.458   917  1372 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:02:16.458   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:02:16.468  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:02:16.468  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:02:16.468   917   917 I MotionRecognitionService: Plugged
,07-05 12:02:16.468  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:02:16.468   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:02:16.478  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:02:16.478  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:02:16.478   917  1372 D BatteryService: stay LED for fully charged
,07-05 12:02:16.488  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:02:16.488  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:02:16.488  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:02:17.228   301   301 E SMD     : DCD ON
,07-05 12:02:19.018   917  3316 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 450
,07-05 12:02:20.228   301   301 E SMD     : DCD ON
,07-05 12:02:22.438   917  1323 E Watchdog: !@Sync 9
,07-05 12:02:23.228   301   301 E SMD     : DCD ON
,07-05 12:02:26.228   301   301 E SMD     : DCD ON
,07-05 12:02:26.518   917  1357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:02:29.068   917  3316 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 450
,07-05 12:02:29.228   301   301 E SMD     : DCD ON
,07-05 12:02:29.408   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:30.078   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:02:30.408   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:31.408   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:32.228   301   301 E SMD     : DCD ON
,07-05 12:02:32.408   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:33.408   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:34.408   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 12:02:35.228   301   301 E SMD     : DCD ON
,07-05 12:02:36.578   917  1332 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:02:36.588   917  1332 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:02:36.588   917  1332 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:02:36.588   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:02:36.588   917   917 I MotionRecognitionService: Plugged
07-05 12:02:36.588   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:02:36.588  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:02:36.598  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:02:36.598  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:02:36.598  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:02:36.598  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:02:36.598  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:02:36.598  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:02:36.598   917  1332 D BatteryService: stay LED for fully charged
07-05 12:02:36.598  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:02:38.228   301   301 E SMD     : DCD ON
,07-05 12:02:39.118   917  3316 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-05 12:02:41.228   301   301 E SMD     : DCD ON
,07-05 12:02:44.238   301   301 E SMD     : DCD ON
,07-05 12:02:46.638   917  1249 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:02:46.648   917  1249 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:02:46.648   917  1249 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:02:46.648   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:02:46.648   917   917 I MotionRecognitionService: Plugged
,07-05 12:02:46.648   917   917 I MotionRecognitionService: setPowerConnected  = true
07-05 12:02:46.648  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:02:46.648  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:02:46.658  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:02:46.658  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:02:46.658  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 12:02:46.658  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:02:46.658   917  1249 D BatteryService: stay LED for fully charged
07-05 12:02:46.658  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:02:46.658  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:02:47.238   301   301 E SMD     : DCD ON
,07-05 12:02:49.168   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 450
,07-05 12:02:49.728   917  1101 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 12:02:49.738   917  1101 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 12:02:49.738   917  1100 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 12:02:49.748   917  1101 I TLC_TIMA_PKM_initialize: initializing...
,07-05 12:02:49.748   917  1101 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,07-05 12:02:49.758   917  1101 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,07-05 12:02:49.758   917  1101 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,07-05 12:02:49.758   917  1101 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,07-05 12:02:49.758   917  1101 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-05 12:02:49.758   917  1101 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040,
,07-05 12:02:49.758   917  1101 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080,
,07-05 12:02:49.768   917  1101 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-05 12:02:49.768   917  1101 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 12:02:49.778   917  1101 D QSEECOMAPI: : Loaded image: APP id = 2
,07-05 12:02:49.788   917  1101 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-05 12:02:49.788   917  1101 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-05 12:02:50.078   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:02:50.238   301   301 E SMD     : DCD ON
,07-05 12:02:51.968   917  1101 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 12:02:51.978   917  1101 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 12:02:51.978   917  1101 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:02:51.988   917  1101 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:02:52.448   917  1323 E Watchdog: !@Sync 10
,07-05 12:02:52.748   917  1060 I PowerManagerService: [PWL] Off : 275s ago
,07-05 12:02:53.238   301   301 E SMD     : DCD ON
,07-05 12:02:56.238   301   301 E SMD     : DCD ON
,07-05 12:02:56.698   917  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:02:59.218   917  3316 D SSRM:n  : SIOP:: AP = 320, PST = 319, CUR = 450
,07-05 12:02:59.238   301   301 E SMD     : DCD ON
,07-05 12:02:59.408   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 12:02:59.408   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 12:03:02.238   301   301 E SMD     : DCD ON
,07-05 12:03:05.238   301   301 E SMD     : DCD ON
,07-05 12:03:08.238   301   301 E SMD     : DCD ON
,07-05 12:03:09.258   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 318, CUR = 450
,07-05 12:03:09.628   917  1112 V AlarmManager: waitForAlarm result :4
,07-05 12:03:09.648   917  1008 D ActivityManager: startProcessLocked calleePkgName: com.blurb.checkout, hostingType: broadcast
,07-05 12:03:09.648   917  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:03:09.648   917  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:03:09.648   917  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:03:09.648   917  1008 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:03:09.678   917  1531 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:03:09.708   917  1008 I ActivityManager: Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7508 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 12:03:09.708  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 12:03:09.708  1199  1199 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 12:03:09.708  1199  1199 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 12:03:09.708  7508  7508 E Zygote  : MountEmulatedStorage()
07-05 12:03:09.708  7508  7508 E Zygote  : v2
07-05 12:03:09.708  7508  7508 I libpersona: KNOX_SDCARD checking this for 10096
07-05 12:03:09.708  7508  7508 I libpersona: KNOX_SDCARD not a persona
,07-05 12:03:09.708  1199  1199 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 12:03:09.728  7508  7508 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-05 12:03:09.728  7508  7508 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-05 12:03:09.738  7508  7508 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-05 12:03:09.778  7508  7508 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 12:03:09.778  7508  7508 D ActivityThread: Added TimaKeyStore provider
,07-05 12:03:09.788  7508  7508 D ResourcesManager: creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,07-05 12:03:09.788  1199  1199 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:03:09.798  1199  1199 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:03:09.808   917  1508 D ActivityManager: startService callerProcessName:com.blurb.checkout, calleePkgName: com.blurb.checkout
,07-05 12:03:09.808   917  1508 D ActivityManager: caller:android.app.ApplicationThreadProxy@1a9f8732, r.packageName :com.blurb.checkout
,07-05 12:03:09.838   917   935 I ActivityManager: Killing 5942:com.sec.android.app.music:service/u0a49 (adj 15): emptyCount ##41
,07-05 12:03:10.088   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:03:11.238   301   301 E SMD     : DCD ON
,07-05 12:03:14.238   301   301 E SMD     : DCD ON
,07-05 12:03:14.408   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:15.408   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:16.418   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:17.238   301   301 E SMD     : DCD ON
,07-05 12:03:17.418   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:18.418   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:19.308   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 450
,07-05 12:03:19.418   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 12:03:19.738   917  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:03:19.738   917  1142 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:03:19.748   917  1142 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:03:19.748   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:03:19.748  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:03:19.748  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:03:19.748   917   917 I MotionRecognitionService: Plugged
,07-05 12:03:19.748   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:03:19.758  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:03:19.758  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:03:19.758  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:03:19.758  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:03:19.758  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:03:19.758  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:03:19.758   917  1142 D BatteryService: stay LED for fully charged
,07-05 12:03:20.248   301   301 E SMD     : DCD ON
,07-05 12:03:22.448   917  1323 E Watchdog: !@Sync 11
,07-05 12:03:23.248   301   301 E SMD     : DCD ON
,07-05 12:03:24.418   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:25.418   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:26.248   301   301 E SMD     : DCD ON
,07-05 12:03:26.418   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:27.418   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:28.418   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:29.248   301   301 E SMD     : DCD ON
,07-05 12:03:29.358   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 450
,07-05 12:03:29.428   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 12:03:29.798   917  1531 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:03:29.798   917  1531 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:03:29.808   917  1531 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:03:29.808   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:03:29.808  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:03:29.808  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:03:29.808   917   917 I MotionRecognitionService: Plugged
,07-05 12:03:29.808   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:03:29.818  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:03:29.818  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:03:29.818  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:03:29.818  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:03:29.818  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:03:29.818   917  1531 D BatteryService: stay LED for fully charged
07-05 12:03:29.818  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:03:30.088   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:03:32.248   301   301 E SMD     : DCD ON
,07-05 12:03:35.248   301   301 E SMD     : DCD ON
,07-05 12:03:38.248   301   301 E SMD     : DCD ON
,07-05 12:03:39.408   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 450
,07-05 12:03:39.428   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:39.858   917  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:03:39.858   917  1589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:03:39.858   917  1589 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:03:39.868   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:03:39.868  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:03:39.868  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:03:39.868  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:03:39.878   917   917 I MotionRecognitionService: Plugged
,07-05 12:03:39.878  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:03:39.878   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:03:39.878  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:03:39.878  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:03:39.878  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:03:39.878   917  1589 D BatteryService: stay LED for fully charged
,07-05 12:03:39.878  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:03:40.428   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:41.248   301   301 E SMD     : DCD ON
,07-05 12:03:41.428   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:42.428   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:43.428   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:44.248   301   301 E SMD     : DCD ON
,07-05 12:03:44.428   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 12:03:47.248   301   301 E SMD     : DCD ON
,07-05 12:03:47.748   917  1060 I PowerManagerService: [PWL] Off : 330s ago
,07-05 12:03:49.458   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 450
,07-05 12:03:49.918   917  1565 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:03:50.088   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:03:50.248   301   301 E SMD     : DCD ON
,07-05 12:03:52.448   917  1323 E Watchdog: !@Sync 12
,07-05 12:03:53.248   301   301 E SMD     : DCD ON
,07-05 12:03:56.258   301   301 E SMD     : DCD ON
,07-05 12:03:59.258   301   301 E SMD     : DCD ON
,07-05 12:03:59.438   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:59.498   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 450
,07-05 12:03:59.988   917  1112 V AlarmManager: waitForAlarm result :8
,07-05 12:04:00.038   917  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:04:00.038   917  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 12:04:00.038   917  1648 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:04:00.038   917  1648 D BatteryService: stay LED for fully charged
07-05 12:04:00.038   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:04:00.038  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:04:00.048  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:04:00.048   917   917 I MotionRecognitionService: Plugged
07-05 12:04:00.048   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:04:00.048  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:04:00.048  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:04:00.048  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:04:00.048  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:04:00.058  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:04:00.058  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:04:00.428   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:01.428   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:02.258   301   301 E SMD     : DCD ON
,07-05 12:04:02.428   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:03.438   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:04.438   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:04:05.258   301   301 E SMD     : DCD ON
,07-05 12:04:08.258   301   301 E SMD     : DCD ON
,07-05 12:04:09.548   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 450
,07-05 12:04:10.098   917   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:04:10.098   917   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 12:04:10.098   917   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:04:10.098   917   935 D BatteryService: stay LED for fully charged
07-05 12:04:10.098   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:04:10.098   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:04:10.098  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:04:10.098   917   917 I MotionRecognitionService: Plugged
,07-05 12:04:10.098   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:04:10.098  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:04:10.108  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:04:10.108  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:04:10.108  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:04:10.108  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:04:10.108  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:04:10.108  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:04:11.258   301   301 E SMD     : DCD ON
,07-05 12:04:14.268   301   301 E SMD     : DCD ON
,07-05 12:04:17.258   301   301 E SMD     : DCD ON
,07-05 12:04:19.608   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,07-05 12:04:20.158   917  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:04:20.258   301   301 E SMD     : DCD ON
,07-05 12:04:22.448   917  1323 E Watchdog: !@Sync 13
,07-05 12:04:23.258   301   301 E SMD     : DCD ON
,07-05 12:04:24.438   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:25.438   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:26.258   301   301 E SMD     : DCD ON
,07-05 12:04:26.438   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:27.448   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:28.438   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:29.268   301   301 E SMD     : DCD ON
,07-05 12:04:29.438   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 12:04:29.658   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,07-05 12:04:30.108   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:04:30.218   917  1372 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:04:32.258   301   301 E SMD     : DCD ON
,07-05 12:04:35.268   301   301 E SMD     : DCD ON
,07-05 12:04:38.268   301   301 E SMD     : DCD ON
,07-05 12:04:39.708   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:04:40.278   917   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:04:41.268   301   301 E SMD     : DCD ON
,07-05 12:04:44.268   301   301 E SMD     : DCD ON
,07-05 12:04:47.268   301   301 E SMD     : DCD ON
,07-05 12:04:47.788   917  1060 I PowerManagerService: [PWL] Off : 390s ago
,07-05 12:04:49.768   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:04:50.108   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:04:50.268   301   301 E SMD     : DCD ON
,07-05 12:04:50.338   917  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:04:52.458   917  1323 E Watchdog: !@Sync 14
,07-05 12:04:53.268   301   301 E SMD     : DCD ON
,07-05 12:04:54.438   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 12:04:54.438   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 12:04:56.268   301   301 E SMD     : DCD ON
,07-05 12:04:59.268   301   301 E SMD     : DCD ON
,07-05 12:04:59.818   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:05:00.398   917   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:05:00.408   917   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:05:00.408   917   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:05:00.408   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:05:00.418  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:05:00.418   917   917 I MotionRecognitionService: Plugged
,07-05 12:05:00.418  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:05:00.418   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:05:00.418   917   935 D BatteryService: stay LED for fully charged
,07-05 12:05:00.428  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:05:00.428  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:05:00.428  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:05:00.428  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:05:00.428  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:05:00.438  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:05:02.268   301   301 E SMD     : DCD ON
,07-05 12:05:05.268   301   301 E SMD     : DCD ON
,07-05 12:05:08.268   301   301 E SMD     : DCD ON
,07-05 12:05:09.868   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:05:10.118   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:05:10.468   917  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:05:10.468   917  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 12:05:10.468   917  1648 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:05:10.468   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:05:10.478  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:05:10.478   917   917 I MotionRecognitionService: Plugged
,07-05 12:05:10.478   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:05:10.478  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:05:10.488   917  1648 D BatteryService: stay LED for fully charged
,07-05 12:05:10.488  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:05:10.488  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:05:10.488  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:05:10.488  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:05:10.508  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:05:10.508  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:05:11.268   301   301 E SMD     : DCD ON
,07-05 12:05:14.278   301   301 E SMD     : DCD ON
,07-05 12:05:14.438   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:15.448   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:16.448   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:17.278   301   301 E SMD     : DCD ON
,07-05 12:05:17.448   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:18.448   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:19.448   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 12:05:19.918   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:05:20.278   301   301 E SMD     : DCD ON
,07-05 12:05:20.518   917   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:05:22.458   917  1323 E Watchdog: !@Sync 15
,07-05 12:05:23.278   301   301 E SMD     : DCD ON
,07-05 12:05:24.448   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:25.448   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:26.278   301   301 E SMD     : DCD ON
,07-05 12:05:26.448   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:27.448   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:28.448   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:29.278   301   301 E SMD     : DCD ON
,07-05 12:05:29.458   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 12:05:29.978   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:05:30.118   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:05:30.578   917  1665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:05:30.578   917  1665 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:05:30.578   917  1665 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:05:30.588   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:05:30.588  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:05:30.588  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:05:30.588  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:05:30.598   917   917 I MotionRecognitionService: Plugged
,07-05 12:05:30.598   917   917 I MotionRecognitionService: setPowerConnected  = true
07-05 12:05:30.598  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:05:30.598  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:05:30.598  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:05:30.598   917  1665 D BatteryService: stay LED for fully charged
,07-05 12:05:30.598  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:05:30.598  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:05:32.278   301   301 E SMD     : DCD ON
,07-05 12:05:35.278   301   301 E SMD     : DCD ON
,07-05 12:05:38.278   301   301 E SMD     : DCD ON
,07-05 12:05:39.458   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:40.028   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:05:40.458   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:40.558   328   328 I bootchecker: bootchecker wake up!!
,07-05 12:05:40.638   917  1372 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:05:41.288   301   301 E SMD     : DCD ON
,07-05 12:05:41.458   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:42.458   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:43.458   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:44.278   301   301 E SMD     : DCD ON
,07-05 12:05:44.458   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 12:05:47.278   301   301 E SMD     : DCD ON
,07-05 12:05:50.078   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:05:50.128   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:05:50.278   301   301 E SMD     : DCD ON
,07-05 12:05:50.698   917   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:05:52.458   917  1323 E Watchdog: !@Sync 16
,07-05 12:05:52.788   917  1060 I PowerManagerService: [PWL] Off : 455s ago
,07-05 12:05:53.288   301   301 E SMD     : DCD ON
,07-05 12:05:56.288   301   301 E SMD     : DCD ON
,07-05 12:05:59.288   301   301 E SMD     : DCD ON
,07-05 12:05:59.458   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:00.138   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:06:00.458   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:00.758   917  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:06:01.458   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:02.288   301   301 E SMD     : DCD ON
,07-05 12:06:02.468   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:03.468   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:04.468   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:06:05.288   301   301 E SMD     : DCD ON
,07-05 12:06:08.288   301   301 E SMD     : DCD ON
,07-05 12:06:10.128   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:06:10.188   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:06:10.818   917   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:06:11.288   301   301 E SMD     : DCD ON
,07-05 12:06:14.288   301   301 E SMD     : DCD ON
,07-05 12:06:17.298   301   301 E SMD     : DCD ON
,07-05 12:06:20.248   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:06:20.288   301   301 E SMD     : DCD ON
,07-05 12:06:20.878   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:06:20.878   917  2696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:06:20.878   917  2696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:06:20.888   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:06:20.888   917   917 I MotionRecognitionService: Plugged
,07-05 12:06:20.888   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:06:20.888  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:06:20.888  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:06:20.888  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:06:20.898  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:06:20.898  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:06:20.898  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:06:20.898   917  2696 D BatteryService: stay LED for fully charged
07-05 12:06:20.898  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:06:20.898  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:06:22.468   917  1323 E Watchdog: !@Sync 17
,07-05 12:06:23.288   301   301 E SMD     : DCD ON
,07-05 12:06:24.468   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:25.468   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:26.288   301   301 E SMD     : DCD ON
,07-05 12:06:26.478   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:27.468   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:28.468   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:29.298   301   301 E SMD     : DCD ON
,07-05 12:06:29.468   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 12:06:30.128   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:06:30.298   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-05 12:06:30.938   917  1372 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:06:32.298   301   301 E SMD     : DCD ON
,07-05 12:06:35.298   301   301 E SMD     : DCD ON
,07-05 12:06:38.298   301   301 E SMD     : DCD ON
,07-05 12:06:40.358   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450
,07-05 12:06:40.998   917   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:06:41.008   917   934 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:06:41.008   917   934 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:06:41.008   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:06:41.008   917   917 I MotionRecognitionService: Plugged
,07-05 12:06:41.008   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:06:41.008  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:06:41.008  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:06:41.018  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:06:41.018  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:06:41.018  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:06:41.018  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:06:41.018   917   934 D BatteryService: stay LED for fully charged
,07-05 12:06:41.018  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:06:41.018  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:06:41.298   301   301 E SMD     : DCD ON
,07-05 12:06:44.298   301   301 E SMD     : DCD ON
,07-05 12:06:47.298   301   301 E SMD     : DCD ON
,07-05 12:06:50.138   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:06:50.298   301   301 E SMD     : DCD ON
,07-05 12:06:50.418   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450
,07-05 12:06:51.058   917  1332 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:06:51.068   917  1332 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:06:51.068   917  1332 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:06:51.068   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:06:51.078  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:06:51.078  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:06:51.078   917   917 I MotionRecognitionService: Plugged
,07-05 12:06:51.078   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:06:51.078   917  1332 D BatteryService: stay LED for fully charged
,07-05 12:06:51.088  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:06:51.088  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:06:51.088  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:06:51.088  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:06:51.088  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:06:51.098  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:06:52.468   917  1323 E Watchdog: !@Sync 18
,07-05 12:06:53.298   301   301 E SMD     : DCD ON
,07-05 12:06:54.468   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 12:06:54.468   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 12:06:56.298   301   301 E SMD     : DCD ON
,07-05 12:06:59.298   301   301 E SMD     : DCD ON
,07-05 12:07:00.478   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450
,07-05 12:07:01.118   917  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:07:02.298   301   301 E SMD     : DCD ON
,07-05 12:07:02.798   917  1060 I PowerManagerService: [PWL] Off : 525s ago
,07-05 12:07:05.298   301   301 E SMD     : DCD ON
,07-05 12:07:08.308   301   301 E SMD     : DCD ON
,07-05 12:07:10.138   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:07:10.528   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450
,07-05 12:07:11.178   917  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:07:11.308   301   301 E SMD     : DCD ON
,07-05 12:07:14.308   301   301 E SMD     : DCD ON
,07-05 12:07:17.308   301   301 E SMD     : DCD ON
,07-05 12:07:19.488   333   333 I Atfwd_Daemon: Stop the daemon....
,07-05 12:07:20.308   301   301 E SMD     : DCD ON
,07-05 12:07:20.588   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450
,07-05 12:07:21.238   917   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:07:21.238   917   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:07:21.238   917   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:07:21.248   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:07:21.248   917   917 I MotionRecognitionService: Plugged
07-05 12:07:21.248   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:07:21.248  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:07:21.248  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:07:21.248  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:07:21.258  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:07:21.258  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:07:21.258  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:07:21.258   917   935 D BatteryService: stay LED for fully charged
,07-05 12:07:21.258  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:07:21.258  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:07:22.468   917  1323 E Watchdog: !@Sync 19
,07-05 12:07:23.308   301   301 E SMD     : DCD ON
,07-05 12:07:26.308   301   301 E SMD     : DCD ON
,07-05 12:07:29.308   301   301 E SMD     : DCD ON
,07-05 12:07:30.148   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:07:30.638   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450
,07-05 12:07:31.298   917  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:07:31.298   917  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:07:31.298   917  1648 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:07:31.308   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:07:31.308  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:07:31.308  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:07:31.308  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:07:31.318  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 12:07:31.318   917   917 I MotionRecognitionService: Plugged
07-05 12:07:31.318   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:07:31.318  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:07:31.318   917  1648 D BatteryService: stay LED for fully charged
,07-05 12:07:31.318  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:07:31.318  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:07:31.318  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:07:32.308   301   301 E SMD     : DCD ON
,07-05 12:07:35.308   301   301 E SMD     : DCD ON
,07-05 12:07:38.308   301   301 E SMD     : DCD ON
,07-05 12:07:40.688   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,07-05 12:07:41.308   301   301 E SMD     : DCD ON
,07-05 12:07:41.358   917  1249 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:07:41.368   917  1249 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 12:07:41.368   917  1249 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:07:41.368   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:07:41.368   917   917 I MotionRecognitionService: Plugged
07-05 12:07:41.368   917   917 I MotionRecognitionService: setPowerConnected  = true
07-05 12:07:41.368  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:07:41.378  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:07:41.378  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:07:41.378  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:07:41.378  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:07:41.378  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:07:41.378   917  1249 D BatteryService: stay LED for fully charged
,07-05 12:07:41.378  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:07:41.378  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:07:44.308   301   301 E SMD     : DCD ON
,07-05 12:07:47.318   301   301 E SMD     : DCD ON
,07-05 12:07:49.728   917  1101 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 12:07:49.738   917  1100 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 12:07:49.738   917  1101 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 12:07:50.148   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:07:50.318   301   301 E SMD     : DCD ON
,07-05 12:07:50.748   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-05 12:07:51.418   917  1357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:07:51.418   917  1357 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:07:51.418   917  1357 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:07:51.418   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:07:51.418   917   917 I MotionRecognitionService: Plugged
,07-05 12:07:51.428   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:07:51.428   917  1357 D BatteryService: stay LED for fully charged
,07-05 12:07:51.428  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:07:51.428  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:07:51.428  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:07:51.428  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:07:51.428  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:07:51.428  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:07:51.438  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:07:51.438  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:07:51.988   917  1101 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 12:07:51.988   917  1101 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 12:07:51.988   917  1101 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:07:51.998   917  1101 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:07:52.478   917  1323 E Watchdog: !@Sync 20
,07-05 12:07:53.318   301   301 E SMD     : DCD ON
,07-05 12:07:56.318   301   301 E SMD     : DCD ON
,07-05 12:07:59.318   301   301 E SMD     : DCD ON
,07-05 12:08:00.788   917  3316 D SSRM:n  : SIOP:: AP = 310, PST = 302, CUR = 450
,07-05 12:08:01.478   917   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:08:01.478   917   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:08:01.478   917   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:08:01.488   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:08:01.488  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:08:01.488  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:08:01.498  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:08:01.498   917   917 I MotionRecognitionService: Plugged
,07-05 12:08:01.498  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:08:01.498   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:08:01.498  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:08:01.498  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:08:01.498   917   935 D BatteryService: stay LED for fully charged
,07-05 12:08:01.498  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:08:01.498  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:08:02.318   301   301 E SMD     : DCD ON
,07-05 12:08:05.318   301   301 E SMD     : DCD ON
,07-05 12:08:08.318   301   301 E SMD     : DCD ON
,07-05 12:08:10.148   917  3330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:08:10.838   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:08:11.318   301   301 E SMD     : DCD ON
,07-05 12:08:11.538   917  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:08:11.538   917  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:08:11.548   917  1648 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:08:11.548   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:08:11.548   917   917 I MotionRecognitionService: Plugged
,07-05 12:08:11.548  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:08:11.548  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:08:11.548  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:08:11.558  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:08:11.558   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:08:11.558  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:08:11.558  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:08:11.558  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:08:11.558   917  1648 D BatteryService: stay LED for fully charged
07-05 12:08:11.558  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:08:14.318   301   301 E SMD     : DCD ON
,07-05 12:08:17.318   301   301 E SMD     : DCD ON
,07-05 12:08:17.798   917  1060 I PowerManagerService: [PWL] Off : 600s ago
,07-05 12:08:20.318   301   301 E SMD     : DCD ON
,07-05 12:08:20.888   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:08:21.598   917  1249 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:08:21.598   917  1249 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:08:21.608   917  1249 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:08:21.608   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:08:21.608   917   917 I MotionRecognitionService: Plugged
,07-05 12:08:21.608   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:08:21.608  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:08:21.608  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:08:21.618  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:08:21.618  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:08:21.618  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:08:21.618  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:08:21.618  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:08:21.618   917  1249 D BatteryService: stay LED for fully charged
,07-05 12:08:21.618  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:08:22.478   917  1323 E Watchdog: !@Sync 21
,07-05 12:08:23.318   301   301 E SMD     : DCD ON
,07-05 12:08:26.328   301   301 E SMD     : DCD ON
,07-05 12:08:29.328   301   301 E SMD     : DCD ON
,07-05 12:08:30.938   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:08:31.658   917  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:08:31.658   917  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:08:31.668   917  1648 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:08:31.668   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:08:31.668   917   917 I MotionRecognitionService: Plugged
,07-05 12:08:31.668  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:08:31.668  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:08:31.668  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:08:31.678  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:08:31.678   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:08:31.678  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:08:31.678  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:08:31.678   917  1648 D BatteryService: stay LED for fully charged
,07-05 12:08:31.678  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:08:31.678  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:08:32.328   301   301 E SMD     : DCD ON
,07-05 12:08:35.328   301   301 E SMD     : DCD ON
,07-05 12:08:38.328   301   301 E SMD     : DCD ON
,07-05 12:08:40.988   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:08:41.328   301   301 E SMD     : DCD ON
,07-05 12:08:41.718   917  1249 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:08:44.328   301   301 E SMD     : DCD ON
,07-05 12:08:47.328   301   301 E SMD     : DCD ON
,07-05 12:08:50.328   301   301 E SMD     : DCD ON
,07-05 12:08:51.038   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:08:51.778   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:08:52.488   917  1323 E Watchdog: !@Sync 22
,07-05 12:08:53.328   301   301 E SMD     : DCD ON
,07-05 12:08:56.328   301   301 E SMD     : DCD ON
,07-05 12:08:59.328   301   301 E SMD     : DCD ON
,07-05 12:09:01.098   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:09:01.838   917  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:09:01.848   917  1712 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:09:01.848   917  1712 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:09:01.848   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:09:01.848   917   917 I MotionRecognitionService: Plugged
07-05 12:09:01.848  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:09:01.848  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:09:01.858  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:09:01.858   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:09:01.858  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:09:01.858  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:09:01.858  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:09:01.858  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:09:01.858   917  1712 D BatteryService: stay LED for fully charged
,07-05 12:09:01.858  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:09:02.328   301   301 E SMD     : DCD ON
,07-05 12:09:05.338   301   301 E SMD     : DCD ON
,07-05 12:09:08.338   301   301 E SMD     : DCD ON
,07-05 12:09:11.158   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:09:11.338   301   301 E SMD     : DCD ON
,07-05 12:09:11.898   917   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:09:14.338   301   301 E SMD     : DCD ON
,07-05 12:09:17.348   301   301 E SMD     : DCD ON
,07-05 12:09:20.338   301   301 E SMD     : DCD ON
,07-05 12:09:21.208   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:09:21.958   917  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:09:21.958   917  1589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:09:21.968   917  1589 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:09:21.968   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:09:21.968  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:09:21.968  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:09:21.978  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:09:21.978   917   917 I MotionRecognitionService: Plugged
,07-05 12:09:21.978   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:09:21.978  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:09:21.978  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:09:21.978  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:09:21.978  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:09:21.978  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:09:21.978   917  1589 D BatteryService: stay LED for fully charged
,07-05 12:09:22.488   917  1323 E Watchdog: !@Sync 23
,07-05 12:09:23.348   301   301 E SMD     : DCD ON
,07-05 12:09:26.338   301   301 E SMD     : DCD ON
,07-05 12:09:29.338   301   301 E SMD     : DCD ON
,07-05 12:09:31.268   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-05 12:09:32.018   917  1531 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:09:32.018   917  1531 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:09:32.028   917  1531 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:09:32.028   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:09:32.028   917   917 I MotionRecognitionService: Plugged
07-05 12:09:32.028  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:09:32.028  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:09:32.038  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:09:32.038   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:09:32.038  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:09:32.038  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:09:32.038  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:09:32.038   917  1531 D BatteryService: stay LED for fully charged
07-05 12:09:32.038  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:09:32.038  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:09:32.338   301   301 E SMD     : DCD ON
,07-05 12:09:35.338   301   301 E SMD     : DCD ON
,07-05 12:09:37.798   917  1060 I PowerManagerService: [PWL] Off : 680s ago
,07-05 12:09:38.338   301   301 E SMD     : DCD ON
,07-05 12:09:41.308   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:09:41.348   301   301 E SMD     : DCD ON
,07-05 12:09:42.078   917  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:09:44.348   301   301 E SMD     : DCD ON
,07-05 12:09:47.348   301   301 E SMD     : DCD ON
,07-05 12:09:50.348   301   301 E SMD     : DCD ON
,07-05 12:09:51.358   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:09:52.118   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:09:52.128   917  2696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 12:09:52.128   917  2696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:09:52.128   917  2696 D BatteryService: stay LED for fully charged
07-05 12:09:52.128   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:09:52.128  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:09:52.128  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:09:52.128   917   917 I MotionRecognitionService: Plugged
07-05 12:09:52.128   917   917 I MotionRecognitionService: setPowerConnected  = true
07-05 12:09:52.128  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:09:52.128  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:09:52.138  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:09:52.138  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:09:52.138  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:09:52.148  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:09:52.488   917  1323 E Watchdog: !@Sync 24
,07-05 12:09:53.348   301   301 E SMD     : DCD ON
,07-05 12:09:56.348   301   301 E SMD     : DCD ON
,07-05 12:09:59.348   301   301 E SMD     : DCD ON
,07-05 12:10:01.408   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:10:02.188   917  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:10:02.188   917  1482 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:10:02.188   917  1482 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:10:02.188   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:10:02.198  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:10:02.198  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:10:02.198   917   917 I MotionRecognitionService: Plugged
,07-05 12:10:02.208   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:10:02.208   917  1482 D BatteryService: stay LED for fully charged
,07-05 12:10:02.208  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:10:02.208  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:02.208  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:02.208  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:02.218  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:10:02.218  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:10:02.348   301   301 E SMD     : DCD ON
,07-05 12:10:05.348   301   301 E SMD     : DCD ON
,07-05 12:10:08.348   301   301 E SMD     : DCD ON
,07-05 12:10:11.348   301   301 E SMD     : DCD ON
,07-05 12:10:11.458   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:10:12.248   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:10:12.248   917  2696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:10:12.248   917  2696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:10:12.248   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:10:12.258   917   917 I MotionRecognitionService: Plugged
,07-05 12:10:12.258  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:10:12.258  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:10:12.258   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:10:12.268   917  2696 D BatteryService: stay LED for fully charged
,07-05 12:10:12.268  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:10:12.268  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:10:12.268  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:10:12.288  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:12.288  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:12.288  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:14.348   301   301 E SMD     : DCD ON
,07-05 12:10:17.348   301   301 E SMD     : DCD ON
,07-05 12:10:20.358   301   301 E SMD     : DCD ON
,07-05 12:10:21.518   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:10:22.308   917  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:10:22.498   917  1323 E Watchdog: !@Sync 25
,07-05 12:10:23.358   301   301 E SMD     : DCD ON
,07-05 12:10:26.358   301   301 E SMD     : DCD ON
,07-05 12:10:29.358   301   301 E SMD     : DCD ON
,07-05 12:10:31.578   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:10:32.358   301   301 E SMD     : DCD ON
,07-05 12:10:32.358   917   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:10:32.368   917   934 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:10:32.368   917   934 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:10:32.368   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:10:32.378  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:10:32.378  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:10:32.378   917   917 I MotionRecognitionService: Plugged
,07-05 12:10:32.378   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:10:32.378   917   934 D BatteryService: stay LED for fully charged
,07-05 12:10:32.388  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:32.388  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:10:32.388  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:10:32.388  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:10:32.388  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:32.388  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:35.358   301   301 E SMD     : DCD ON
,07-05 12:10:38.358   301   301 E SMD     : DCD ON
,07-05 12:10:41.368   301   301 E SMD     : DCD ON
,07-05 12:10:41.628   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:10:42.418   917  1372 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:10:42.428   917  1372 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:10:42.428   917  1372 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:10:42.428   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:10:42.438  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:10:42.438  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:10:42.438   917   917 I MotionRecognitionService: Plugged
,07-05 12:10:42.438   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:10:42.438   917  1372 D BatteryService: stay LED for fully charged
,07-05 12:10:42.448  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:10:42.448  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:42.448  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:42.448  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:10:42.448  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:10:42.458  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:44.358   301   301 E SMD     : DCD ON
,07-05 12:10:47.358   301   301 E SMD     : DCD ON
,07-05 12:10:50.358   301   301 E SMD     : DCD ON
,07-05 12:10:51.688   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:10:52.238   917  1112 V AlarmManager: waitForAlarm result :8
,07-05 12:10:52.478   917   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:10:52.478   917   934 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:10:52.488   917   934 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:10:52.488   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:10:52.488   917   917 I MotionRecognitionService: Plugged
,07-05 12:10:52.488   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:10:52.488  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:10:52.488  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:10:52.488  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:10:52.498  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:10:52.498  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:52.498   917   934 D BatteryService: stay LED for fully charged
07-05 12:10:52.498   917  1323 E Watchdog: !@Sync 26
,07-05 12:10:52.498  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:52.498  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:10:52.498  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:53.358   301   301 E SMD     : DCD ON
,07-05 12:10:56.358   301   301 E SMD     : DCD ON
,07-05 12:10:59.358   301   301 E SMD     : DCD ON
,07-05 12:11:01.738   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:11:02.368   301   301 E SMD     : DCD ON
,07-05 12:11:02.538   917  1372 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:11:02.538   917  1372 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:11:02.538   917  1372 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450,
,07-05 12:11:02.548   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:11:02.548   917   917 I MotionRecognitionService: Plugged
,07-05 12:11:02.548   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:11:02.548  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:11:02.548  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:11:02.548  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:11:02.558  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:11:02.558  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:11:02.558  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:02.558   917  1372 D BatteryService: stay LED for fully charged
,07-05 12:11:02.558  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:11:02.558  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:02.808   917  1060 I PowerManagerService: [PWL] Off : 765s ago
,07-05 12:11:05.368   301   301 E SMD     : DCD ON
,07-05 12:11:08.368   301   301 E SMD     : DCD ON
,07-05 12:11:11.378   301   301 E SMD     : DCD ON
,07-05 12:11:11.788   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:11:12.598   917  1665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:11:12.608   917  1665 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:11:12.608   917  1665 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:11:12.608   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:11:12.608   917   917 I MotionRecognitionService: Plugged
,07-05 12:11:12.608   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:11:12.608  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:11:12.608  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:11:12.618  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:11:12.618   917  1665 D BatteryService: stay LED for fully charged
,07-05 12:11:12.618  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:11:12.618  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:11:12.618  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:12.618  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:12.618  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:14.368   301   301 E SMD     : DCD ON
,07-05 12:11:17.368   301   301 E SMD     : DCD ON
,07-05 12:11:20.368   301   301 E SMD     : DCD ON
,07-05 12:11:21.858   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:11:22.498   917  1323 E Watchdog: !@Sync 27
,07-05 12:11:22.658   917  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:11:22.668   917  1712 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:11:22.668   917  1712 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:11:22.668   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:11:22.678  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:11:22.678  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:11:22.678   917   917 I MotionRecognitionService: Plugged
,07-05 12:11:22.678   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:11:22.678   917  1712 D BatteryService: stay LED for fully charged
,07-05 12:11:22.688  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:11:22.688  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:11:22.688  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:11:22.688  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:22.688  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:11:22.698  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:23.368   301   301 E SMD     : DCD ON
,07-05 12:11:26.368   301   301 E SMD     : DCD ON
,07-05 12:11:29.368   301   301 E SMD     : DCD ON
,07-05 12:11:31.918   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:11:32.368   301   301 E SMD     : DCD ON
,07-05 12:11:32.718   917  1665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:11:32.718   917  1665 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:11:32.728   917  1665 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:11:32.728   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:11:32.728  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:11:32.728  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:11:32.728  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:11:32.728  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:11:32.738   917   917 I MotionRecognitionService: Plugged
,07-05 12:11:32.738   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:11:32.738  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:11:32.738  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:32.738   917  1665 D BatteryService: stay LED for fully charged
,07-05 12:11:32.738  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:32.738  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:35.368   301   301 E SMD     : DCD ON
,07-05 12:11:38.378   301   301 E SMD     : DCD ON
,07-05 12:11:41.378   301   301 E SMD     : DCD ON
,07-05 12:11:41.988   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:11:42.778   917  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:11:44.378   301   301 E SMD     : DCD ON
,07-05 12:11:47.378   301   301 E SMD     : DCD ON
,07-05 12:11:50.388   301   301 E SMD     : DCD ON
,07-05 12:11:52.048   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:11:52.498   917  1323 E Watchdog: !@Sync 28
,07-05 12:11:52.838   917  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:11:52.838   917  1508 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:11:52.838   917  1508 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:11:52.848   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:11:52.848   917   917 I MotionRecognitionService: Plugged
,07-05 12:11:52.848  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:11:52.848  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:11:52.848  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:11:52.858  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:11:52.858   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:11:52.858  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:11:52.858  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:52.858   917  1508 D BatteryService: stay LED for fully charged
,07-05 12:11:52.858  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:11:52.858  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:53.378   301   301 E SMD     : DCD ON
,07-05 12:11:56.378   301   301 E SMD     : DCD ON
,07-05 12:11:59.388   301   301 E SMD     : DCD ON
,07-05 12:12:02.088   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:12:02.378   301   301 E SMD     : DCD ON
,07-05 12:12:02.898   917  1332 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:12:02.908   917  1332 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:12:02.908   917  1332 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:12:02.908   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:12:02.908  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:12:02.908  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:12:02.908   917   917 I MotionRecognitionService: Plugged
,07-05 12:12:02.908   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:12:02.918  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:12:02.918   917  1332 D BatteryService: stay LED for fully charged
,07-05 12:12:02.918  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:02.918  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:02.918  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:12:02.918  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:12:02.918  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:05.378   301   301 E SMD     : DCD ON
,07-05 12:12:08.378   301   301 E SMD     : DCD ON
,07-05 12:12:11.378   301   301 E SMD     : DCD ON
,07-05 12:12:12.138   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:12:12.958   917  1531 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:12:12.958   917  1531 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:12:12.958   917  1531 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:12:12.968   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:12:12.968   917   917 I MotionRecognitionService: Plugged
,07-05 12:12:12.968   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:12:12.968  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:12:12.968  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:12:12.978  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:12:12.978  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:12:12.978  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:12.978   917  1531 D BatteryService: stay LED for fully charged
,07-05 12:12:12.978  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:12.978  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:12:12.978  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:12:14.378   301   301 E SMD     : DCD ON
,07-05 12:12:17.388   301   301 E SMD     : DCD ON
,07-05 12:12:20.388   301   301 E SMD     : DCD ON
,07-05 12:12:22.188   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:12:22.508   917  1323 E Watchdog: !@Sync 29
,07-05 12:12:23.018   917  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:12:23.028   917  1589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:12:23.028   917  1589 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:12:23.028   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:12:23.028   917   917 I MotionRecognitionService: Plugged
07-05 12:12:23.028   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:12:23.028  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:12:23.038  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:12:23.038  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:12:23.038  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:12:23.038  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:12:23.038  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:23.038   917  1589 D BatteryService: stay LED for fully charged
,07-05 12:12:23.038  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:23.038  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:23.388   301   301 E SMD     : DCD ON
,07-05 12:12:26.388   301   301 E SMD     : DCD ON
,07-05 12:12:29.388   301   301 E SMD     : DCD ON
,07-05 12:12:32.238   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:12:32.388   301   301 E SMD     : DCD ON
,07-05 12:12:32.808   917  1060 I PowerManagerService: [PWL] Off : 855s ago
,07-05 12:12:33.078   917  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:12:33.088   917  1508 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:12:33.088   917  1508 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:12:33.088   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:12:33.088   917   917 I MotionRecognitionService: Plugged
,07-05 12:12:33.088   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:12:33.088  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:12:33.088  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:12:33.098  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:12:33.098  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:12:33.098  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:12:33.098   917  1508 D BatteryService: stay LED for fully charged
07-05 12:12:33.098  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:33.098  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:33.098  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:35.388   301   301 E SMD     : DCD ON
,07-05 12:12:38.388   301   301 E SMD     : DCD ON
,07-05 12:12:41.388   301   301 E SMD     : DCD ON
,07-05 12:12:42.288   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:12:43.138   917  1332 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:12:43.148   917  1332 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:12:43.148   917  1332 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:12:43.148   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:12:43.158  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:12:43.158  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:12:43.158   917   917 I MotionRecognitionService: Plugged
,07-05 12:12:43.158   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:12:43.158   917  1332 D BatteryService: stay LED for fully charged
,07-05 12:12:43.168  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:12:43.168  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:43.168  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:43.168  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:43.168  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:12:43.168  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:12:44.388   301   301 E SMD     : DCD ON
,07-05 12:12:47.388   301   301 E SMD     : DCD ON
,07-05 12:12:49.738   917  1101 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 12:12:49.738   917  1100 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 12:12:49.738   917  1101 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 12:12:50.388   301   301 E SMD     : DCD ON
,07-05 12:12:52.148   917  1101 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 12:12:52.148   917  1101 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 12:12:52.158   917  1101 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:12:52.168   917  1101 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:12:52.338   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:12:52.508   917  1323 E Watchdog: !@Sync 30
,07-05 12:12:53.198   917  1531 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:12:53.198   917  1531 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:12:53.208   917  1531 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:12:53.208   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:12:53.208   917   917 I MotionRecognitionService: Plugged
,07-05 12:12:53.208  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:12:53.208  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:12:53.208   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:12:53.218  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:12:53.218   917  1531 D BatteryService: stay LED for fully charged
,07-05 12:12:53.218  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:53.218  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:53.218  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:12:53.218  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:12:53.218  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:53.388   301   301 E SMD     : DCD ON
,07-05 12:12:56.398   301   301 E SMD     : DCD ON
,07-05 12:12:59.398   301   301 E SMD     : DCD ON
,07-05 12:13:02.388   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:13:02.398   301   301 E SMD     : DCD ON
,07-05 12:13:05.398   301   301 E SMD     : DCD ON
,07-05 12:13:08.398   301   301 E SMD     : DCD ON
,07-05 12:13:11.398   301   301 E SMD     : DCD ON
,07-05 12:13:11.918   917  1112 V AlarmManager: waitForAlarm result :4
,07-05 12:13:11.928   917   917 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-05 12:13:11.938  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 12:13:11.938  1199  1199 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 12:13:11.938  1199  1199 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-05 12:13:11.938  1199  1199 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 12:13:11.948   917   917 E LightSensor: Light old sensor_state 8192, new sensor_state : 8704 en : 1
,07-05 12:13:11.958   917   917 D SensorManager: registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,07-05 12:13:11.968   917  1665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:13:11.968   917  1665 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 12:13:11.968   917  1665 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:13:11.968   917  1665 D BatteryService: stay LED for fully charged
,07-05 12:13:11.998   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:13:11.998  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:13:11.998  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:13:12.008  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:13:12.008  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:13:12.008  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:13:12.008  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:13:12.008  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:13:12.008   917   917 I MotionRecognitionService: Plugged
07-05 12:13:12.008   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:13:12.018  1199  1199 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:13:12.018  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:13:12.018  1199  1199 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:13:12.138  1651  4298 D GCM     : Message class com.google.f.a.a.i
,07-05 12:13:12.148   917  1648 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 12:13:12.148   917  1665 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 12:13:12.318   917  1092 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,07-05 12:13:12.318   917  1092 E LightSensor: Light old sensor_state 8704, new sensor_state : 8192 en : 0
,07-05 12:13:12.318   917  1092 D SensorManager: unregisterListener ::   
,07-05 12:13:12.318   917  1092 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-05 12:13:12.438   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:13:14.398   301   301 E SMD     : DCD ON
,07-05 12:13:17.398   301   301 E SMD     : DCD ON
,07-05 12:13:20.398   301   301 E SMD     : DCD ON
,07-05 12:13:22.018   917  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:13:22.018   917  1508 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:13:22.028   917  1508 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:13:22.028   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:13:22.038  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:13:22.038   917   917 I MotionRecognitionService: Plugged
,07-05 12:13:22.038   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:13:22.038   917  1508 D BatteryService: stay LED for fully charged
,07-05 12:13:22.038  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:13:22.048  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:13:22.048  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:13:22.048  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:13:22.048  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:13:22.048  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:13:22.048  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:13:22.488   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:13:22.508   917  1323 E Watchdog: !@Sync 31
,07-05 12:13:23.398   301   301 E SMD     : DCD ON
,07-05 12:13:26.398   301   301 E SMD     : DCD ON
,07-05 12:13:29.398   301   301 E SMD     : DCD ON
,07-05 12:13:32.078   917  1332 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:13:32.078   917  1332 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:13:32.088   917  1332 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:13:32.088   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:13:32.088  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:13:32.088  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:13:32.088   917   917 I MotionRecognitionService: Plugged
,07-05 12:13:32.088  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:13:32.088   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:13:32.098   917  1332 D BatteryService: stay LED for fully charged
,07-05 12:13:32.098  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:13:32.098  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:13:32.098  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:13:32.098  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:13:32.108  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:13:32.398   301   301 E SMD     : DCD ON
,07-05 12:13:32.538   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:13:35.408   301   301 E SMD     : DCD ON
,07-05 12:13:38.408   301   301 E SMD     : DCD ON
,07-05 12:13:41.408   301   301 E SMD     : DCD ON
,07-05 12:13:42.138   917  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:13:42.138   917  1508 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:13:42.138   917  1508 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:13:42.148   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:13:42.148   917   917 I MotionRecognitionService: Plugged
,07-05 12:13:42.148   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:13:42.148  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:13:42.148  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:13:42.148  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:13:42.148  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:13:42.158  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:13:42.158  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:13:42.158   917  1508 D BatteryService: stay LED for fully charged
07-05 12:13:42.158  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:13:42.158  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:13:42.598   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:13:44.408   301   301 E SMD     : DCD ON
,07-05 12:13:47.408   301   301 E SMD     : DCD ON
,07-05 12:13:50.408   301   301 E SMD     : DCD ON
,07-05 12:13:52.198   917  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:13:52.198   917  1589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:13:52.198   917  1589 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:13:52.198   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:13:52.208  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:13:52.208  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:13:52.208   917   917 I MotionRecognitionService: Plugged
,07-05 12:13:52.208   917   917 I MotionRecognitionService: setPowerConnected  = true
07-05 12:13:52.208   917  1589 D BatteryService: stay LED for fully charged
,07-05 12:13:52.208  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:13:52.218  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:13:52.218  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:13:52.218  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:13:52.218  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:13:52.228  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:13:52.518   917  1323 E Watchdog: !@Sync 32
,07-05 12:13:52.648   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:13:53.408   301   301 E SMD     : DCD ON
,07-05 12:13:56.408   301   301 E SMD     : DCD ON
,07-05 12:13:59.408   301   301 E SMD     : DCD ON
,07-05 12:13:59.998   917  1112 V AlarmManager: waitForAlarm result :8
,07-05 12:14:02.258   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:14:02.258   917  2696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:14:02.258   917  2696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:14:02.268   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:14:02.268  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:14:02.268  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:14:02.278  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:14:02.278   917   917 I MotionRecognitionService: Plugged
,07-05 12:14:02.278   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:14:02.278  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:14:02.278  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:14:02.278   917  2696 D BatteryService: stay LED for fully charged
07-05 12:14:02.278  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:14:02.278  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:14:02.278  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:14:02.408   301   301 E SMD     : DCD ON
,07-05 12:14:02.688   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:14:05.418   301   301 E SMD     : DCD ON
,07-05 12:14:07.808   917  1060 I PowerManagerService: [PWL] Off : 950s ago
,07-05 12:14:08.408   301   301 E SMD     : DCD ON
,07-05 12:14:11.408   301   301 E SMD     : DCD ON
,07-05 12:14:12.318   917  1332 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:14:12.738   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:14:14.418   301   301 E SMD     : DCD ON
,07-05 12:14:17.418   301   301 E SMD     : DCD ON
,07-05 12:14:20.418   301   301 E SMD     : DCD ON
,07-05 12:14:22.378   917  1357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:14:22.528   917  1323 E Watchdog: !@Sync 33
,07-05 12:14:22.788   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:14:23.418   301   301 E SMD     : DCD ON
,07-05 12:14:26.418   301   301 E SMD     : DCD ON
,07-05 12:14:29.428   301   301 E SMD     : DCD ON
,07-05 12:14:32.418   301   301 E SMD     : DCD ON
,07-05 12:14:32.438   917  1665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:14:32.448   917  1665 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:14:32.448   917  1665 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:14:32.448   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:14:32.448   917   917 I MotionRecognitionService: Plugged
,07-05 12:14:32.448   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:14:32.448  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:14:32.458  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:14:32.458  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:14:32.458  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:14:32.458  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:14:32.458   917  1665 D BatteryService: stay LED for fully charged
,07-05 12:14:32.458  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:14:32.458  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:14:32.458  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:14:32.838   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:14:35.428   301   301 E SMD     : DCD ON
,07-05 12:14:38.418   301   301 E SMD     : DCD ON
,07-05 12:14:41.428   301   301 E SMD     : DCD ON
,07-05 12:14:42.498   917  1249 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:14:42.888   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:14:44.418   301   301 E SMD     : DCD ON
,07-05 12:14:47.418   301   301 E SMD     : DCD ON
,07-05 12:14:50.418   301   301 E SMD     : DCD ON
,07-05 12:14:52.518   917  1323 E Watchdog: !@Sync 34
,07-05 12:14:52.568   917   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:14:52.568   917   934 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:14:52.568   917   934 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:14:52.568   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:14:52.578  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:14:52.578   917   917 I MotionRecognitionService: Plugged
,07-05 12:14:52.578  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:14:52.578   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:14:52.588   917   934 D BatteryService: stay LED for fully charged
,07-05 12:14:52.588  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:14:52.588  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:14:52.588  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:14:52.608  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:14:52.608  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:14:52.608  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:14:52.938   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:14:53.428   301   301 E SMD     : DCD ON
,07-05 12:14:56.428   301   301 E SMD     : DCD ON
,07-05 12:14:59.428   301   301 E SMD     : DCD ON
,07-05 12:15:02.428   301   301 E SMD     : DCD ON
,07-05 12:15:02.628   917  1565 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:15:02.628   917  1565 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:15:02.628   917  1565 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:15:02.628   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:15:02.638  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:15:02.638  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:15:02.638   917   917 I MotionRecognitionService: Plugged
,07-05 12:15:02.638   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:15:02.648   917  1565 D BatteryService: stay LED for fully charged
,07-05 12:15:02.648  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:15:02.648  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:15:02.648  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:15:02.668  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:15:02.668  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:15:02.668  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:15:02.988   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:15:05.428   301   301 E SMD     : DCD ON
,07-05 12:15:08.428   301   301 E SMD     : DCD ON
,07-05 12:15:11.428   301   301 E SMD     : DCD ON
,07-05 12:15:12.688   917   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:15:13.038   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:15:14.428   301   301 E SMD     : DCD ON
,07-05 12:15:17.428   301   301 E SMD     : DCD ON
,07-05 12:15:20.428   301   301 E SMD     : DCD ON
,07-05 12:15:22.518   917  1323 E Watchdog: !@Sync 35
,07-05 12:15:22.748   917  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:15:22.748   917  1589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:15:22.748   917  1589 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:15:22.748   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:15:22.758  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:15:22.758  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:15:22.758   917   917 I MotionRecognitionService: Plugged
07-05 12:15:22.758   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:15:22.768   917  1589 D BatteryService: stay LED for fully charged
,07-05 12:15:22.768  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:15:22.768  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:15:22.768  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:15:22.788  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:15:22.788  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:15:22.788  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:15:23.088   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:15:23.428   301   301 E SMD     : DCD ON
,07-05 12:15:26.428   301   301 E SMD     : DCD ON
,07-05 12:15:29.428   301   301 E SMD     : DCD ON
,07-05 12:15:32.438   301   301 E SMD     : DCD ON
,07-05 12:15:32.808   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:15:32.808   917  2696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:15:32.808   917  2696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:15:32.808   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:15:32.818   917   917 I MotionRecognitionService: Plugged
,07-05 12:15:32.818   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:15:32.818   917  2696 D BatteryService: stay LED for fully charged
,07-05 12:15:32.818  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:15:32.818  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:15:32.828  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:15:32.828  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:15:32.828  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:15:32.828  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:15:32.848  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:15:32.848  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:15:33.138   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:15:35.438   301   301 E SMD     : DCD ON
,07-05 12:15:38.438   301   301 E SMD     : DCD ON
,07-05 12:15:41.438   301   301 E SMD     : DCD ON
,07-05 12:15:42.868   917  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:15:42.868   917  1589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 12:15:42.868   917  1589 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:15:42.868   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:15:42.878  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:15:42.878  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:15:42.878   917   917 I MotionRecognitionService: Plugged
,07-05 12:15:42.878   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:15:42.878   917  1589 D BatteryService: stay LED for fully charged
,07-05 12:15:42.888  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:15:42.888  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:15:42.888  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:15:42.888  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:15:42.888  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:15:42.908  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:15:43.188   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:15:44.438   301   301 E SMD     : DCD ON
,07-05 12:15:47.438   301   301 E SMD     : DCD ON
,07-05 12:15:47.818   917  1060 I PowerManagerService: [PWL] Off : 1050s ago
,07-05 12:15:50.438   301   301 E SMD     : DCD ON
,07-05 12:15:52.528   917  1323 E Watchdog: !@Sync 36
,07-05 12:15:52.918   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:15:52.918   917  2696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:15:52.928   917  2696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:15:52.928   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:15:52.928  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:15:52.938  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:15:52.938   917   917 I MotionRecognitionService: Plugged
,07-05 12:15:52.938   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:15:52.938   917  2696 D BatteryService: stay LED for fully charged
,07-05 12:15:52.948  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:15:52.948  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:15:52.948  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:15:52.948  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:15:52.968  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:15:52.968  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:15:53.248   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:15:53.438   301   301 E SMD     : DCD ON
,07-05 12:15:56.438   301   301 E SMD     : DCD ON
,07-05 12:15:59.438   301   301 E SMD     : DCD ON
,07-05 12:16:02.438   301   301 E SMD     : DCD ON
,07-05 12:16:02.978   917  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:16:02.978   917  1589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:16:02.988   917  1589 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:16:02.988   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:16:02.988  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:16:02.998   917   917 I MotionRecognitionService: Plugged
,07-05 12:16:02.998  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:16:02.998   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:16:03.008   917  1589 D BatteryService: stay LED for fully charged
,07-05 12:16:03.008  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:16:03.008  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:16:03.008  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:16:03.008  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:16:03.028  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:16:03.028  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:16:03.298   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:16:05.438   301   301 E SMD     : DCD ON
,07-05 12:16:08.438   301   301 E SMD     : DCD ON
,07-05 12:16:11.448   301   301 E SMD     : DCD ON
,07-05 12:16:13.038   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:16:13.038   917  2696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:16:13.048   917  2696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:16:13.048   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:16:13.048  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:16:13.058  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:16:13.058   917   917 I MotionRecognitionService: Plugged
,07-05 12:16:13.058  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:16:13.058   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:16:13.068   917  2696 D BatteryService: stay LED for fully charged
,07-05 12:16:13.068  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:16:13.068  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:16:13.068  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:16:13.068  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:16:13.068  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:16:13.348   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:16:14.448   301   301 E SMD     : DCD ON
,07-05 12:16:17.448   301   301 E SMD     : DCD ON
,07-05 12:16:20.448   301   301 E SMD     : DCD ON
,07-05 12:16:22.528   917  1323 E Watchdog: !@Sync 37
,07-05 12:16:23.098   917  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:16:23.098   917  1589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:16:23.108   917  1589 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:16:23.108   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:16:23.108  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:16:23.108  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:16:23.108   917   917 I MotionRecognitionService: Plugged
,07-05 12:16:23.108   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:16:23.118  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:16:23.118   917  1589 D BatteryService: stay LED for fully charged
,07-05 12:16:23.118  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:16:23.118  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:16:23.118  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:16:23.118  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:16:23.118  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:16:23.388   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:16:23.448   301   301 E SMD     : DCD ON
,07-05 12:16:26.448   301   301 E SMD     : DCD ON
,07-05 12:16:29.448   301   301 E SMD     : DCD ON
,07-05 12:16:32.448   301   301 E SMD     : DCD ON
,07-05 12:16:33.158   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:16:33.438   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:16:35.448   301   301 E SMD     : DCD ON
,07-05 12:16:38.448   301   301 E SMD     : DCD ON
,07-05 12:16:41.448   301   301 E SMD     : DCD ON
,07-05 12:16:43.218   917   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:16:43.528   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:16:44.448   301   301 E SMD     : DCD ON
,07-05 12:16:47.458   301   301 E SMD     : DCD ON
,07-05 12:16:50.458   301   301 E SMD     : DCD ON
,07-05 12:16:52.528   917  1323 E Watchdog: !@Sync 38
,07-05 12:16:53.278   917  1249 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:16:53.288   917  1249 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:16:53.288   917  1249 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:16:53.288   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:16:53.288  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:16:53.288  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:16:53.288   917   917 I MotionRecognitionService: Plugged
,07-05 12:16:53.288   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:16:53.298  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:16:53.298  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:16:53.298  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:16:53.298   917  1249 D BatteryService: stay LED for fully charged
,07-05 12:16:53.298  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:16:53.298  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:16:53.298  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:16:53.458   301   301 E SMD     : DCD ON
,07-05 12:16:53.578   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:16:56.458   301   301 E SMD     : DCD ON
,07-05 12:16:59.458   301   301 E SMD     : DCD ON
,07-05 12:17:02.458   301   301 E SMD     : DCD ON
,07-05 12:17:03.338   917  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:17:03.618   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:17:05.458   301   301 E SMD     : DCD ON
,07-05 12:17:08.458   301   301 E SMD     : DCD ON
,07-05 12:17:11.458   301   301 E SMD     : DCD ON
,07-05 12:17:13.418   917  1565 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:17:13.668   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:17:14.458   301   301 E SMD     : DCD ON
,07-05 12:17:17.458   301   301 E SMD     : DCD ON
,07-05 12:17:20.458   301   301 E SMD     : DCD ON
,07-05 12:17:22.528   917  1323 E Watchdog: !@Sync 39
,07-05 12:17:23.458   301   301 E SMD     : DCD ON
,07-05 12:17:23.478   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:17:23.718   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:17:26.458   301   301 E SMD     : DCD ON
,07-05 12:17:29.458   301   301 E SMD     : DCD ON
,07-05 12:17:32.468   301   301 E SMD     : DCD ON
,07-05 12:17:32.818   917  1060 I PowerManagerService: [PWL] Off : 1155s ago
,07-05 12:17:33.538   917   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:17:33.538   917   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:17:33.548   917   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:17:33.548   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:17:33.548   917   917 I MotionRecognitionService: Plugged
,07-05 12:17:33.548  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:17:33.548  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:17:33.548  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:17:33.558   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:17:33.558  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:17:33.558  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:17:33.558  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:17:33.558  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:17:33.558   917   935 D BatteryService: stay LED for fully charged
07-05 12:17:33.558  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:17:33.768   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:17:35.468   301   301 E SMD     : DCD ON
,07-05 12:17:38.468   301   301 E SMD     : DCD ON
,07-05 12:17:41.468   301   301 E SMD     : DCD ON
,07-05 12:17:43.598   917  1372 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:17:43.598   917  1372 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:17:43.608   917  1372 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:17:43.608   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:17:43.608   917   917 I MotionRecognitionService: Plugged
,07-05 12:17:43.608   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:17:43.608  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:17:43.608  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:17:43.618  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:17:43.618  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:17:43.618  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:17:43.618  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:17:43.618  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:17:43.618   917  1372 D BatteryService: stay LED for fully charged
07-05 12:17:43.618  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:17:43.818   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:17:44.478   301   301 E SMD     : DCD ON
,07-05 12:17:47.468   301   301 E SMD     : DCD ON
,07-05 12:17:49.738   917  1101 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 12:17:49.738   917  1100 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 12:17:49.738   917  1101 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 12:17:50.388   917  1004 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 12:17:50.428   917  1124 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,07-05 12:17:50.428   917  1124 I ApplicationUsage: Updating Usage Statistics in DB @ 1467713870442
,07-05 12:17:50.428   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 12:17:50.438   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 12:17:50.438   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 12:17:50.438   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-05 12:17:50.438   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
07-05 12:17:50.438   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,07-05 12:17:50.438   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.438   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.438   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 12:17:50.438   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.438   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 12:17:50.438   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 12:17:50.438   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.438   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,07-05 12:17:50.438   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
07-05 12:17:50.438   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
07-05 12:17:50.438   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 12:17:50.438   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.438   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.438   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 12:17:50.438   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.438   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 12:17:50.438   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.438   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 12:17:50.448   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.448   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.448   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 12:17:50.448   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.448   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 12:17:50.448   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.448   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.448   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 12:17:50.448   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.448   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 12:17:50.448   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.448   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.448   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 12:17:50.448   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 12:17:50.448   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.448   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.458   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.458   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.458   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 12:17:50.458   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.458   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 12:17:50.458   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.458   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.458   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 12:17:50.458   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.458   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 12:17:50.458   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 12:17:50.458   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.458   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.458   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 12:17:50.458   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.458   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 12:17:50.458   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.458   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.458   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 12:17:50.458   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.458   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.458   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 12:17:50.458   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.458   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.468   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 12:17:50.468   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 12:17:50.468   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.468   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.468   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 12:17:50.468   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.468   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 12:17:50.468   301   301 E SMD     : DCD ON
07-05 12:17:50.468   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.468   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 12:17:50.468   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.468   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.468   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 12:17:50.468   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.468   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.468   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 12:17:50.468   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.468   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.468   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 12:17:50.478   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.478   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.478   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 12:17:50.478   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.478   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.478   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.478   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.478   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 12:17:50.478   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 12:17:50.478   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.478   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.478   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 12:17:50.478   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.478   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.478   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.478   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.478   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.478   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 12:17:50.478   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.478   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.478   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 12:17:50.488   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 12:17:50.488   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.488   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.488   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 12:17:50.488   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.488   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 12:17:50.488   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.488   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.488   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.488   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.488   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.488   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.488   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.488   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.488   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.488   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.488   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.488   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.488   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.488   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.488   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.498   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.498   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.498   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.498   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.498   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.498   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.498   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.498   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.498   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.498   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.498   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.498   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.498   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.498   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.498   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.498   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.498   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.498   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.508   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.508   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.508   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.508   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.508   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.508   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.508   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.508   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.508   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.508   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.508   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.508   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.508   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.508   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.508   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.508   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.508   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.508   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.508   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.518   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.518   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.518   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.518   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.518   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.518   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.518   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.518   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 12:17:50.518   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.518   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.518   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.518   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.518   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.518   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.518   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.518   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.518   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.518   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.518   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.518   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.518   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.528   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.528   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.528   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.528   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.528   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.528   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.528   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.528   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.528   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.528   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.528   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.528   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.528   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.528   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.528   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.528   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.528   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.528   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.528   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.528   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.528   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.538   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.538   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.538   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.538   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.538   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.538   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.538   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.538   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.538   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.538   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.538   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.538   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.538   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.538   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.538   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.538   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.538   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.538   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.538   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.548   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.548   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.548   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.548   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.548   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.548   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.548   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.548   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.548   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.548   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.548   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.548   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.548   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.548   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.548   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.548   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.548   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.548   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.548   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.548   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.548   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.548   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.548   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.548   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.548   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.548   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.548   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.548   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.558   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.558   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.558   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.558   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.558   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.558   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.558   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.558   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.558   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.558   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.558   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.558   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.558   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 12:17:50.558   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.558   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.558   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.558   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.558   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.558   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.558   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.558   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.558   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.558   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.558   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.558   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.558   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.558   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.558   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.558   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.558   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.558   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.558   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.558   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.568   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.568   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.568   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.568   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.568   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.568   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.568   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.568   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.568   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.568   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.568   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.568   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.568   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.568   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.568   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.568   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.568   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.568   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.568   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.568   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.578   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.578   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.578   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.578   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.578   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.578   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.578   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.578   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.578   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.578   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.578   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.578   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.578   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.578   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.578   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.578   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.578   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.578   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.578   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.578   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.578   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.578   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.578   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.578   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.578   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.578   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.578   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.578   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.578   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.578   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.578   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.578   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.588   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.588   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.588   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.588   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.588   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.588   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.588   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.588   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.588   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.588   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.588   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.588   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.588   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.588   917  1124 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 12:17:50.588   917  1124 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 12:17:50.588   917  1124 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 12:17:50.598   917  1124 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:17:50.598   917  1124 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:17:50.598   917  1124 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:17:50.598   917  1124 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1467713870607
,07-05 12:17:51.888   917  1101 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 12:17:51.888   917  1101 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 12:17:51.898   917  1101 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:17:51.898   917  1101 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:17:52.548   917  1323 E Watchdog: !@Sync 40
,07-05 12:17:53.468   301   301 E SMD     : DCD ON
,07-05 12:17:53.658   917  1332 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:17:53.658   917  1332 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:17:53.658   917  1332 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:17:53.668   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:17:53.668  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:17:53.668  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:17:53.668  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:17:53.678  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:17:53.678   917   917 I MotionRecognitionService: Plugged
07-05 12:17:53.678   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:17:53.678  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:17:53.678  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:17:53.678  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:17:53.678  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:17:53.678   917  1332 D BatteryService: stay LED for fully charged
,07-05 12:17:53.858   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:17:56.468   301   301 E SMD     : DCD ON
,07-05 12:17:59.468   301   301 E SMD     : DCD ON
,07-05 12:18:02.468   301   301 E SMD     : DCD ON
,07-05 12:18:03.718   917  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:18:03.718   917  1508 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:18:03.718   917  1508 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:18:03.728   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:18:03.728  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:18:03.728  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:18:03.728  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:18:03.738   917   917 I MotionRecognitionService: Plugged
,07-05 12:18:03.738   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:18:03.738  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:18:03.738  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:18:03.738  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:18:03.738  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:18:03.738  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:18:03.738   917  1508 D BatteryService: stay LED for fully charged
,07-05 12:18:03.898   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:18:05.468   301   301 E SMD     : DCD ON
,07-05 12:18:08.468   301   301 E SMD     : DCD ON
,07-05 12:18:11.468   301   301 E SMD     : DCD ON
,07-05 12:18:13.778   917   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:18:13.778   917   935 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:18:13.778   917   935 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:18:13.788   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:18:13.788  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:18:13.788  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:18:13.788  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:18:13.798  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:18:13.798   917   917 I MotionRecognitionService: Plugged
07-05 12:18:13.798   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:18:13.798  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:18:13.798  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:18:13.798  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:18:13.798  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:18:13.798   917   935 D BatteryService: stay LED for fully charged
,07-05 12:18:13.938   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:18:14.478   301   301 E SMD     : DCD ON
,07-05 12:18:17.478   301   301 E SMD     : DCD ON
,07-05 12:18:20.478   301   301 E SMD     : DCD ON
,07-05 12:18:22.538   917  1323 E Watchdog: !@Sync 41
,07-05 12:18:23.478   301   301 E SMD     : DCD ON
,07-05 12:18:23.838   917  1372 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:18:23.838   917  1372 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:18:23.838   917  1372 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:18:23.848   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:18:23.848  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:18:23.848  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:18:23.848  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:18:23.858   917   917 I MotionRecognitionService: Plugged
,07-05 12:18:23.858   917   917 I MotionRecognitionService: setPowerConnected  = true
07-05 12:18:23.858  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:18:23.858  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:18:23.858  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:18:23.858  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:18:23.858  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:18:23.858   917  1372 D BatteryService: stay LED for fully charged
,07-05 12:18:23.978   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:18:26.478   301   301 E SMD     : DCD ON
,07-05 12:18:29.478   301   301 E SMD     : DCD ON
,07-05 12:18:32.488   301   301 E SMD     : DCD ON
,07-05 12:18:33.898   917  1332 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:18:34.048   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:18:35.478   301   301 E SMD     : DCD ON
,07-05 12:18:38.478   301   301 E SMD     : DCD ON
,07-05 12:18:41.478   301   301 E SMD     : DCD ON
,07-05 12:18:43.958   917  1249 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:18:43.958   917  1249 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:18:43.968   917  1249 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:18:43.968   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:18:43.968   917   917 I MotionRecognitionService: Plugged
,07-05 12:18:43.968  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:18:43.968  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:18:43.978  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:18:43.978   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:18:43.978  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:18:43.978  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:18:43.978  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:18:43.978  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:18:43.978   917  1249 D BatteryService: stay LED for fully charged
,07-05 12:18:43.978  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:18:44.088   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:18:44.478   301   301 E SMD     : DCD ON
,07-05 12:18:47.478   301   301 E SMD     : DCD ON
,07-05 12:18:50.478   301   301 E SMD     : DCD ON
,07-05 12:18:52.538   917  1323 E Watchdog: !@Sync 42
,07-05 12:18:53.478   301   301 E SMD     : DCD ON
,07-05 12:18:54.018   917  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:18:54.168   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:18:56.488   301   301 E SMD     : DCD ON
,07-05 12:18:59.488   301   301 E SMD     : DCD ON
,07-05 12:19:02.488   301   301 E SMD     : DCD ON
,07-05 12:19:04.078   917  1565 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:19:04.078   917  1565 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:19:04.088   917  1565 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:19:04.088   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:19:04.088  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:19:04.088  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:19:04.088  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:19:04.098   917   917 I MotionRecognitionService: Plugged
,07-05 12:19:04.098   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:19:04.098  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:19:04.098  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:19:04.098  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:19:04.098  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:19:04.098   917  1565 D BatteryService: stay LED for fully charged
,07-05 12:19:04.098  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:19:04.208   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:19:05.488   301   301 E SMD     : DCD ON
,07-05 12:19:08.488   301   301 E SMD     : DCD ON
,07-05 12:19:11.488   301   301 E SMD     : DCD ON
,07-05 12:19:14.138   917   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:19:14.148   917   934 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:19:14.148   917   934 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:19:14.148   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:19:14.148  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:19:14.148  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:19:14.148   917   917 I MotionRecognitionService: Plugged
07-05 12:19:14.148   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:19:14.158  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:19:14.158  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:19:14.158   917   934 D BatteryService: stay LED for fully charged
,07-05 12:19:14.158  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:19:14.158  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:19:14.158  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:19:14.158  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:19:14.238   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:19:14.488   301   301 E SMD     : DCD ON
,07-05 12:19:17.488   301   301 E SMD     : DCD ON
,07-05 12:19:20.488   301   301 E SMD     : DCD ON
,07-05 12:19:22.548   917  1323 E Watchdog: !@Sync 43
,07-05 12:19:22.828   917  1060 I PowerManagerService: [PWL] Off : 1265s ago
,07-05 12:19:23.488   301   301 E SMD     : DCD ON
,07-05 12:19:24.198   917  1531 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:19:24.198   917  1531 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:19:24.198   917  1531 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:19:24.208   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:19:24.208  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:19:24.208  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:19:24.208  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:19:24.218   917   917 I MotionRecognitionService: Plugged
,07-05 12:19:24.218   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:19:24.218  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:19:24.218  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:19:24.218  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:19:24.218   917  1531 D BatteryService: stay LED for fully charged
07-05 12:19:24.218  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:19:24.218  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:19:24.278   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:19:26.488   301   301 E SMD     : DCD ON
,07-05 12:19:29.488   301   301 E SMD     : DCD ON
,07-05 12:19:32.498   301   301 E SMD     : DCD ON
,07-05 12:19:34.258   917  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:19:34.338   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:19:35.498   301   301 E SMD     : DCD ON
,07-05 12:19:38.498   301   301 E SMD     : DCD ON
,07-05 12:19:41.498   301   301 E SMD     : DCD ON
,07-05 12:19:44.318   917  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:19:44.318   917  1482 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:19:44.328   917  1482 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:19:44.328   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:19:44.328  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:19:44.328  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:19:44.328   917   917 I MotionRecognitionService: Plugged
,07-05 12:19:44.328   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:19:44.338  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:19:44.338  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:19:44.338  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:19:44.338  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:19:44.338   917  1482 D BatteryService: stay LED for fully charged
07-05 12:19:44.338  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:19:44.338  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:19:44.378   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:19:44.498   301   301 E SMD     : DCD ON
,07-05 12:19:47.498   301   301 E SMD     : DCD ON
,07-05 12:19:50.498   301   301 E SMD     : DCD ON
,07-05 12:19:52.548   917  1323 E Watchdog: !@Sync 44
,07-05 12:19:53.508   301   301 E SMD     : DCD ON
,07-05 12:19:54.378   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:19:54.378   917  2696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:19:54.378   917  2696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:19:54.388   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:19:54.388  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:19:54.388  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:19:54.388  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:19:54.398   917   917 I MotionRecognitionService: Plugged
,07-05 12:19:54.398   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:19:54.398  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:19:54.398  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:19:54.398  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:19:54.398  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:19:54.398  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:19:54.398   917  2696 D BatteryService: stay LED for fully charged
,07-05 12:19:54.448   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:19:56.498   301   301 E SMD     : DCD ON
,07-05 12:19:59.498   301   301 E SMD     : DCD ON
,07-05 12:20:02.498   301   301 E SMD     : DCD ON
,07-05 12:20:04.438   917  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:20:04.438   917  1589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:20:04.448   917  1589 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:20:04.448   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:20:04.448  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:20:04.448  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:20:04.448  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:20:04.458   917   917 I MotionRecognitionService: Plugged
,07-05 12:20:04.458  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:20:04.458   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:20:04.458  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:20:04.458  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:20:04.458  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:20:04.458  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:20:04.458   917  1589 D BatteryService: stay LED for fully charged
,07-05 12:20:04.508   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:20:05.498   301   301 E SMD     : DCD ON
,07-05 12:20:08.498   301   301 E SMD     : DCD ON
,07-05 12:20:11.498   301   301 E SMD     : DCD ON
,07-05 12:20:14.498   917  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:20:14.498   917  1142 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:20:14.498   917  1142 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:20:14.508   301   301 E SMD     : DCD ON
,07-05 12:20:14.508   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:20:14.508  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:20:14.508  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:20:14.508  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:20:14.518  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:20:14.518   917   917 I MotionRecognitionService: Plugged
07-05 12:20:14.518  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:20:14.518   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:20:14.518  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:20:14.518  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:20:14.518  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:20:14.518   917  1142 D BatteryService: stay LED for fully charged
,07-05 12:20:14.568   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:20:17.508   301   301 E SMD     : DCD ON
,07-05 12:20:20.508   301   301 E SMD     : DCD ON
,07-05 12:20:22.548   917  1323 E Watchdog: !@Sync 45
,07-05 12:20:23.508   301   301 E SMD     : DCD ON
,07-05 12:20:24.558   917  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:20:24.628   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:20:26.508   301   301 E SMD     : DCD ON
,07-05 12:20:29.508   301   301 E SMD     : DCD ON
,07-05 12:20:32.508   301   301 E SMD     : DCD ON
,07-05 12:20:34.618   917  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:20:34.698   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:20:35.508   301   301 E SMD     : DCD ON
,07-05 12:20:38.508   301   301 E SMD     : DCD ON
,07-05 12:20:41.508   301   301 E SMD     : DCD ON
,07-05 12:20:44.508   301   301 E SMD     : DCD ON
,07-05 12:20:44.678   917  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:20:44.688   917  1712 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:20:44.688   917  1712 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:20:44.688   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:20:44.688  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:20:44.688  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:20:44.688   917   917 I MotionRecognitionService: Plugged
,07-05 12:20:44.688   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:20:44.698  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:20:44.698  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:20:44.698  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:20:44.698  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:20:44.698  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:20:44.698   917  1712 D BatteryService: stay LED for fully charged
07-05 12:20:44.698  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:20:44.728   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:20:47.508   301   301 E SMD     : DCD ON
,07-05 12:20:50.518   301   301 E SMD     : DCD ON
,07-05 12:20:52.558   917  1323 E Watchdog: !@Sync 46
,07-05 12:20:53.518   301   301 E SMD     : DCD ON
,07-05 12:20:54.738   917  1357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:20:54.748   917  1357 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:20:54.748   917  1357 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:20:54.748   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:20:54.748  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:20:54.748  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:20:54.748   917   917 I MotionRecognitionService: Plugged
,07-05 12:20:54.748   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:20:54.758  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:20:54.758  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:20:54.758  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:20:54.758  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:20:54.758  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:20:54.758  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:20:54.758   917  1357 D BatteryService: stay LED for fully charged
,07-05 12:20:54.798   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:20:56.518   301   301 E SMD     : DCD ON
,07-05 12:20:59.518   301   301 E SMD     : DCD ON
,07-05 12:21:02.518   301   301 E SMD     : DCD ON
,07-05 12:21:04.798   917  1665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:21:04.848   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:21:05.518   301   301 E SMD     : DCD ON
,07-05 12:21:08.518   301   301 E SMD     : DCD ON
,07-05 12:21:11.518   301   301 E SMD     : DCD ON
,07-05 12:21:14.518   301   301 E SMD     : DCD ON
,07-05 12:21:14.858   917  1565 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:21:14.918   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:21:17.518   301   301 E SMD     : DCD ON
,07-05 12:21:17.828   917  1060 I PowerManagerService: [PWL] Off : 1380s ago
,07-05 12:21:20.528   301   301 E SMD     : DCD ON
,07-05 12:21:22.568   917  1323 E Watchdog: !@Sync 47
,07-05 12:21:23.518   301   301 E SMD     : DCD ON
,07-05 12:21:24.918   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:21:24.918   917  2696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:21:24.918   917  2696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:21:24.928   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:21:24.928  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:21:24.928  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:21:24.928  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:21:24.938   917   917 I MotionRecognitionService: Plugged
,07-05 12:21:24.938  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:21:24.938   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:21:24.938  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:21:24.938  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:21:24.938  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:21:24.938   917  2696 D BatteryService: stay LED for fully charged
07-05 12:21:24.938  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:21:24.988   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:21:26.518   301   301 E SMD     : DCD ON
,07-05 12:21:29.528   301   301 E SMD     : DCD ON
,07-05 12:21:32.528   301   301 E SMD     : DCD ON
,07-05 12:21:34.978   917  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:21:34.978   917  1589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 12:21:34.978   917  1589 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-05 12:21:34.978   917  1589 D BatteryService: stay LED for fully charged
07-05 12:21:34.978   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:21:34.978  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:21:34.988  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:21:34.988   917   917 I MotionRecognitionService: Plugged
07-05 12:21:34.988   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:21:34.988  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:21:34.988  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:21:34.988  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:21:34.988  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:21:34.988  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:21:34.998  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:21:35.028   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:21:35.528   301   301 E SMD     : DCD ON
,07-05 12:21:38.528   301   301 E SMD     : DCD ON
,07-05 12:21:41.528   301   301 E SMD     : DCD ON
,07-05 12:21:44.528   301   301 E SMD     : DCD ON
,07-05 12:21:45.038   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:21:45.098   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:21:47.528   301   301 E SMD     : DCD ON
,07-05 12:21:50.538   301   301 E SMD     : DCD ON
,07-05 12:21:52.558   917  1323 E Watchdog: !@Sync 48
,07-05 12:21:53.528   301   301 E SMD     : DCD ON
,07-05 12:21:55.098   917   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:21:55.158   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:21:56.528   301   301 E SMD     : DCD ON
,07-05 12:21:59.528   301   301 E SMD     : DCD ON
,07-05 12:22:02.538   301   301 E SMD     : DCD ON
,07-05 12:22:05.158   917  1357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:22:05.158   917  1357 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:22:05.168   917  1357 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:22:05.168   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:22:05.168   917   917 I MotionRecognitionService: Plugged
,07-05 12:22:05.168   917   917 I MotionRecognitionService: setPowerConnected  = true
07-05 12:22:05.168  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:22:05.168  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:22:05.168  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:22:05.178  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:22:05.178  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:22:05.178  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:22:05.178   917  1357 D BatteryService: stay LED for fully charged
,07-05 12:22:05.178  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:22:05.178  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:22:05.208   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:22:05.538   301   301 E SMD     : DCD ON
,07-05 12:22:08.538   301   301 E SMD     : DCD ON
,07-05 12:22:11.538   301   301 E SMD     : DCD ON
,07-05 12:22:14.538   301   301 E SMD     : DCD ON
,07-05 12:22:15.218   917  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:22:15.218   917  1712 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:22:15.218   917  1712 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:22:15.228   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:22:15.228   917   917 I MotionRecognitionService: Plugged
,07-05 12:22:15.228   917   917 I MotionRecognitionService: setPowerConnected  = true
07-05 12:22:15.228  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:22:15.228  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:22:15.228  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:22:15.238  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:22:15.238  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:22:15.238   917  1712 D BatteryService: stay LED for fully charged
07-05 12:22:15.238  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:22:15.238  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:22:15.238  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:22:15.278   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:22:17.538   301   301 E SMD     : DCD ON
,07-05 12:22:20.538   301   301 E SMD     : DCD ON
,07-05 12:22:22.568   917  1323 E Watchdog: !@Sync 49
,07-05 12:22:23.548   301   301 E SMD     : DCD ON
,07-05 12:22:25.278   917  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:22:25.338   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:22:26.538   301   301 E SMD     : DCD ON
,07-05 12:22:29.538   301   301 E SMD     : DCD ON
,07-05 12:22:32.538   301   301 E SMD     : DCD ON
,07-05 12:22:35.338   917   934 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:22:35.378   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:22:35.538   301   301 E SMD     : DCD ON
,07-05 12:22:38.538   301   301 E SMD     : DCD ON
,07-05 12:22:41.548   301   301 E SMD     : DCD ON
,07-05 12:22:44.548   301   301 E SMD     : DCD ON
,07-05 12:22:45.398   917  1589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:22:45.398   917  1589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:22:45.408   917  1589 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:22:45.408   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:22:45.408  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:22:45.408  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:22:45.408  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:22:45.418   917   917 I MotionRecognitionService: Plugged
,07-05 12:22:45.418   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:22:45.418  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:22:45.418  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:22:45.418   917  1589 D BatteryService: stay LED for fully charged
,07-05 12:22:45.418  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:22:45.418  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:22:45.418  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:22:45.448   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:22:47.548   301   301 E SMD     : DCD ON
,07-05 12:22:49.738   917  1101 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 12:22:49.738   917  1100 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 12:22:49.738   917  1101 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 12:22:50.548   301   301 E SMD     : DCD ON
,07-05 12:22:51.998   917  1101 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 12:22:51.998   917  1101 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 12:22:52.008   917  1101 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:22:52.008   917  1101 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:22:52.568   917  1323 E Watchdog: !@Sync 50
,07-05 12:22:53.548   301   301 E SMD     : DCD ON
,07-05 12:22:55.458   917  2696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:22:55.458   917  2696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:22:55.458   917  2696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:22:55.468   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:22:55.468   917   917 I MotionRecognitionService: Plugged
,07-05 12:22:55.468   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:22:55.468  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:22:55.468  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:22:55.468  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:22:55.478  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:22:55.478  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:22:55.478  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:22:55.478   917  2696 D BatteryService: stay LED for fully charged
,07-05 12:22:55.478  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:22:55.478  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:22:55.518   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:22:56.548   301   301 E SMD     : DCD ON
,07-05 12:22:59.548   301   301 E SMD     : DCD ON
,07-05 12:23:02.548   301   301 E SMD     : DCD ON
,07-05 12:23:05.518   917  1565 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:23:05.548   301   301 E SMD     : DCD ON
,07-05 12:23:05.558   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:23:08.548   301   301 E SMD     : DCD ON
,07-05 12:23:11.548   301   301 E SMD     : DCD ON
,07-05 12:23:12.328   917  1112 V AlarmManager: waitForAlarm result :8
,07-05 12:23:14.548   301   301 E SMD     : DCD ON
,07-05 12:23:15.578   917  1372 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:23:15.578   917  1372 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:23:15.578   917  1372 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:23:15.588   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:23:15.588   917   917 I MotionRecognitionService: Plugged
,07-05 12:23:15.588  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:23:15.588  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:23:15.588  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:23:15.598  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:23:15.598   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:23:15.598  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:23:15.598   917  1372 D BatteryService: stay LED for fully charged
,07-05 12:23:15.598  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:23:15.598  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:23:15.598  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:23:15.628   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:23:17.548   301   301 E SMD     : DCD ON
,07-05 12:23:17.828   917  1060 I PowerManagerService: [PWL] Off : 1500s ago
,07-05 12:23:20.548   301   301 E SMD     : DCD ON
,07-05 12:23:22.578   917  1323 E Watchdog: !@Sync 51
,07-05 12:23:23.548   301   301 E SMD     : DCD ON
,07-05 12:23:25.638   917   935 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:23:25.698   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:23:26.558   301   301 E SMD     : DCD ON
,07-05 12:23:29.558   301   301 E SMD     : DCD ON
,07-05 12:23:32.558   301   301 E SMD     : DCD ON
,07-05 12:23:35.558   301   301 E SMD     : DCD ON
,07-05 12:23:35.698   917  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:23:35.698   917  1508 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 12:23:35.708   917  1508 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-05 12:23:35.708   917   917 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:23:35.708   917   917 I MotionRecognitionService: Plugged
,07-05 12:23:35.708   917   917 I MotionRecognitionService: setPowerConnected  = true
,07-05 12:23:35.708  3255  3255 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:23:35.708  1199  1199 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:23:35.708  3255  3470 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:23:35.718  1199  1199 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:23:35.718  1199  1199 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 12:23:35.718  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:23:35.718   917  1508 D BatteryService: stay LED for fully charged
,07-05 12:23:35.718  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:23:35.718  1199  1199 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:23:35.748   917  3316 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-05 12:23:38.558   301   301 E SMD     : DCD ON
,07-05 12:23:41.558   301   301 E SMD     : DCD ON
,TIME-OUT KILL (timeout was 1401000ms),07-05 12:23:42.398  7618  7618 D AndroidRuntime: 
07-05 12:23:42.398  7618  7618 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 12:23:42.408  7618  7618 D AndroidRuntime: CheckJNI is OFF
07-05 12:23:42.408  7618  7618 D AndroidRuntime: readGMSProperty: start
07-05 12:23:42.408  7618  7618 D AndroidRuntime: readGMSProperty: already setted!!
07-05 12:23:42.408  7618  7618 D AndroidRuntime: readGMSProperty: end
07-05 12:23:42.408  7618  7618 D AndroidRuntime: addProductProperty: start
07-05 12:23:42.548  7618  7618 E AffinityControl: AffinityControl: registerfunction enter
07-05 12:23:42.568  7618  7618 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-05 12:23:42.578   917  1665 D PackageManager: START PACKAGE DELETE: observer{1073364213}
07-05 12:23:42.578   917  1665 D PackageManager: pkg{<packageName>}
07-05 12:23:42.578   917  1665 D PackageManager: user{0}
07-05 12:23:42.578   917  1665 D PackageManager: caller{2000}
07-05 12:23:42.578   917  1665 D PackageManager: flags{2}
07-05 12:23:42.578   917  1665 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-05 12:23:42.578   917  1665 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-05 12:23:42.578   917  1665 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-05 12:23:42.578   917  1665 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 12:23:42.578   917  1665 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 12:23:42.578   917  1064 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-05 12:23:42.578   917  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-05 12:23:42.578   917  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-05 12:23:42.578   917  1064 D ApplicationPolicy: getApplicationUninstallationEnabled
07-05 12:23:42.578   917  1064 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-05 12:23:42.578   917  1064 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
07-05 12:23:42.578   917  1008 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
07-05 12:23:42.578   917  1008 I ActivityManager: Killing 7340:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
07-05 12:23:42.578   917  1008 I ActivityManager:   Force finishing activity ActivityRecord{114a8e17 u0 com.test.thalitest/.MainActivity t23}
07-05 12:23:42.588   917  1008 D FocusedStackFrame: Set to : 0
07-05 12:23:42.588   266   981 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
07-05 12:23:42.588   266   411 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
07-05 12:23:42.608   917  3316 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 12:23:42.618   917  3316 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 12:23:42.718   917  1064 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
07-05 12:23:42.738  5115  5115 I art     : Explicit concurrent mark sweep GC freed 1017(72KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 15MB/20MB, paused 329us total 19.966ms
07-05 12:23:42.748  5193  5193 I art     : Explicit concurrent mark sweep GC freed 4553(254KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 15MB/26MB, paused 394us total 20.442ms
07-05 12:23:42.758   917  1050 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
07-05 12:23:42.758  1493  1493 I art     : Explicit concurrent mark sweep GC freed 560(34KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/32MB, paused 384us total 26.923ms
07-05 12:23:42.768  1454  1454 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
07-05 12:23:42.768  1454  1454 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 12:23:42.768  1454  1454 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-05 12:23:42.768  2025  2420 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-05 12:23:42.768  1454  1454 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
07-05 12:23:42.768   917  1118 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-05 12:23:42.768  1454  1454 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 12:23:42.768  1454  1454 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 12:23:42.768  1454  1454 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-05 12:23:42.768  1754  1754 E SamsungIME: mOCRHelper is null
07-05 12:23:42.768  7220  7220 I art     : Explicit concurrent mark sweep GC freed 4214(320KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 308us total 39.960ms
07-05 12:23:42.778  1454  1454 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
07-05 12:23:42.778  1418  1418 D RegisteredServicesCache: empty dynamic service
07-05 12:23:42.778   917  1145 V NetworkStats: removeUidsLocked() for UIDs [10079]
07-05 12:23:42.778   917  1145 V NetworkStats: performPollLocked(flags=0x3)
07-05 12:23:42.778   917  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 12:23:42.778   917  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-05 12:23:42.778   917  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 12:23:42.778  1454  1454 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 12:23:42.778  1454  1454 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-05 12:23:42.778   917  1145 V NetworkStats: performPollLocked() took 5ms
07-05 12:23:42.778   917  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 12:23:42.798  2598  2598 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-05 12:23:42.818   917  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 12:23:42.818   917  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 12:23:42.828  2598  2598 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1467714222828
07-05 12:23:42.828  2598  2598 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
07-05 12:23:42.848  2598  2598 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
07-05 12:23:42.848  6282  6282 I art     : Explicit concurrent mark sweep GC freed 20502(2MB) AllocSpace objects, 2(40KB) LOS objects, 31% free, 17MB/25MB, paused 488us total 74.929ms
07-05 12:23:42.868   917   917 I art     : Explicit concurrent mark sweep GC freed 40688(3MB) AllocSpace objects, 85(1360KB) LOS objects, 30% free, 36MB/52MB, paused 1.747ms total 137.517ms
07-05 12:23:42.878   917  1064 I art     : WaitForGcToComplete blocked for 102.537ms for cause Explicit
07-05 12:23:42.878   917   917 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
07-05 12:23:42.888   917   917 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
07-05 12:23:42.898   917   917 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
07-05 12:23:42.898   917  1357 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-05 12:23:42.898   917  1357 D SecContentProvider2: mCursor = null
07-05 12:23:42.908   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
07-05 12:23:42.908   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
07-05 12:23:42.908   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
07-05 12:23:42.928   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
07-05 12:23:42.928   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
07-05 12:23:42.938   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
07-05 12:23:42.958   917   917 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
07-05 12:23:42.968   917   917 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
07-05 12:23:42.968   917   917 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
07-05 12:23:42.978  2598  2598 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
07-05 12:23:42.978   917   917 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
07-05 12:23:42.978   917   917 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
07-05 12:23:42.978   917   917 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
07-05 12:23:42.988  2598  2598 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
07-05 12:23:42.988   917   917 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
07-05 12:23:42.988   917  1142 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
07-05 12:23:42.988   917  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:42.988   917  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:42.988   917  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:42.988   917  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:42.988   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
07-05 12:23:42.988   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
07-05 12:23:42.998   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
07-05 12:23:42.998   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
07-05 12:23:42.998   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
07-05 12:23:43.008   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
07-05 12:23:43.008   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
07-05 12:23:43.008   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
07-05 12:23:43.018   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
07-05 12:23:43.018   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
07-05 12:23:43.028   917   917 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
07-05 12:23:43.028   917   917 D RCPManagerService: PackageReceiver onReceive()
07-05 12:23:43.028   917   917 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
07-05 12:23:43.028  7647  7647 E Zygote  : MountEmulatedStorage()
07-05 12:23:43.028  7647  7647 E Zygote  : v2
07-05 12:23:43.028  7647  7647 I libpersona: KNOX_SDCARD checking this for 10116
07-05 12:23:43.028  7647  7647 I libpersona: KNOX_SDCARD not a persona
07-05 12:23:43.028   917   917 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-05 12:23:43.028   917   917 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 12:23:43.028   917   917 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-05 12:23:43.028   917   917 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-05 12:23:43.028   917   917 V EnterpriseBillingPolicy: uID is 10079
07-05 12:23:43.038   917   917 V EnterpriseBillingPolicy: Removed Packageuid is0
07-05 12:23:43.038   917   917 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-05 12:23:43.038   917   917 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
07-05 12:23:43.038   917   917 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-05 12:23:43.038   917   917 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-05 12:23:43.038   917   917 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-05 12:23:43.038   917   917 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-05 12:23:43.038   917  1142 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7647 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
07-05 12:23:43.048   917   917 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
07-05 12:23:43.048   917  1180 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
07-05 12:23:43.058   917  1064 I art     : Explicit concurrent mark sweep GC freed 11163(636KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 3.130ms total 177.051ms
07-05 12:23:43.058  7647  7647 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 12:23:43.058  7647  7647 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 12:23:43.058  7647  7647 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 12:23:43.088  7647  7647 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:23:43.088  7647  7647 D ActivityThread: Added TimaKeyStore provider
07-05 12:23:43.098   917  3316 I SQLiteConnectionPool: exportDB...
07-05 12:23:43.108  7647  7647 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
07-05 12:23:43.118  1454  1454 D SurfaceWidgetView: destroyHardwareResources():570534421
07-05 12:23:43.118  1454  1454 D Launcher: onRestart, Launcher: 16469714
07-05 12:23:43.118  1454  1454 D Launcher: onStart, Launcher: 16469714
07-05 12:23:43.118  1454  1454 D Launcher.HomeView: onStart
07-05 12:23:43.118  1454  1454 V ActivityThread: updateVisibility : ActivityRecord{377200b5 token=android.os.BinderProxy@2ac6f0c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-05 12:23:43.118  1846  1871 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
07-05 12:23:43.118  1846  2050 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
07-05 12:23:43.118  1846  2050 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
07-05 12:23:43.138   266   266 I SurfaceFlinger: id=14 createSurf (1080x1920),1 flag=4, Mauncher
07-05 12:23:43.138  7647  7647 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
07-05 12:23:43.138  7647  7647 D elm:14491: ELMEngine.ELMEngine( context ).
07-05 12:23:43.138  7647  7647 D elm:14491: MDMBridge.setEnterpriseBridge()
07-05 12:23:43.148   917  1142 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-05 12:23:43.148   917  1142 D ActivityManager: caller:android.app.ApplicationThreadProxy@7ee2920, r.packageName :com.sec.esdk.elm
07-05 12:23:43.148   917  1064 D PackageManager: delete codoeFile: 
07-05 12:23:43.148  7647  7647 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
07-05 12:23:43.148  3814  3814 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
07-05 12:23:43.148  3814  3814 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 12:23:43.158  3814  3814 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
07-05 12:23:43.158  3814  3814 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-05 12:23:43.158  3814  3814 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-05 12:23:43.158  3814  3814 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-05 12:23:43.158  3814  3814 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-05 12:23:43.158  3814  3814 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:23:43.158  3814  3814 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:23:43.158  3814  3814 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-05 12:23:43.158  3814  3814 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:23:43.158  3814  3814 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:23:43.158  3814  3814 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-05 12:23:43.158  3814  3814 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-05 12:23:43.158  7647  7647 D elm:14491: ElmAgentService : onCreate()
07-05 12:23:43.158  7647  7664 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-05 12:23:43.158  7647  7664 D elm:14491: MainReceiver.listeningToPackageRemoved()
07-05 12:23:43.158  7647  7664 D elm:14491: MDMBridge.getInstance()
07-05 12:23:43.158  7647  7664 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
07-05 12:23:43.158  7647  7664 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
07-05 12:23:43.158   917  1064 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
07-05 12:23:43.158   917  1064 I AASA_removePackage: UID=10079 Target=com.test.thalitest
07-05 12:23:43.158   917  1064 D PackageManager: result of delete: 1{1073364213}
07-05 12:23:43.168  7618  7618 D AndroidRuntime: Shutting down VM
07-05 12:23:43.178  7647  7647 D elm:14491: ElmAgentService : onDestroy().
07-05 12:23:43.178  1651  1651 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-05 12:23:43.178  1651  1651 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
07-05 12:23:43.178   917  1565 I ActivityManager: Killing 5983:com.sec.android.app.myfiles/u0a56 (adj 15): emptyCount ##41
07-05 12:23:43.188   917  1482 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 12:23:43.188   917  3316 I SQLiteConnectionPool: ...exportDB
07-05 12:23:43.198   917  3316 D SSRM:aY : MSG_TYPE_APP_REMOVED::
07-05 12:23:43.198   917  1712 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-05 12:23:43.198   917  1712 D ActivityManager: caller:android.app.ApplicationThreadProxy@1f88349e, r.packageName :com.google.android.gms
07-05 12:23:43.208  2308  2308 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
07-05 12:23:43.208  2308  7667 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-05 12:23:43.208  2308  2308 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
07-05 12:23:43.208  2308  2308 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-05 12:23:43.208  2308  2308 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-05 12:23:43.208  2308  7667 D AccountUtils: Clearing selected account for com.test.thalitest
07-05 12:23:43.208   917  1648 D ActivityManager: caller:android.app.ApplicationThreadProxy@3a5cb74c, r.packageName :com.google.android.gms
07-05 12:23:43.208   917  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{28e2f0a7 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t20} time:1569324
07-05 12:23:43.208  2308  2308 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
07-05 12:23:43.208  2308  2308 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
07-05 12:23:43.208  2308  2308 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-05 12:23:43.208  2308  2308 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-05 12:23:43.208   917  1050 D MultiWindowConverter: MultiWindow Gesture is not supported with launcher
07-05 12:23:43.218   917  1712 D ActivityManager: caller:android.app.ApplicationThreadProxy@203efcaa, r.packageName :com.google.android.gms
07-05 12:23:43.218   917  1565 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 12:23:43.218   917  1565 D ActivityManager: caller:android.app.ApplicationThreadProxy@2943fc38, r.packageName :com.google.android.gms
07-05 12:23:43.218  2308  7667 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
07-05 12:23:43.218   917  1357 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
07-05 12:23:43.228   917  1665 D ActivityManager: caller:android.app.ApplicationThreadProxy@375f7813, r.packageName :com.google.android.gms
07-05 12:23:43.228   917  2696 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 12:23:43.228   917  2696 D ActivityManager: caller:android.app.ApplicationThreadProxy@1a45c449, r.packageName :com.google.android.gms
07-05 12:23:43.238  6942  6942 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
07-05 12:23:43.238  6942  6942 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
07-05 12:23:43.238  6942  6942 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
07-05 12:23:43.248  6957  6957 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-05 12:23:43.248  6957  6957 I PCWCLIENTTRACE_PushUtil: sales region : global
07-05 12:23:43.248  6957  6957 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-05 12:23:43.248  6957  6957 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
07-05 12:23:43.258   917  1357 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 12:23:43.258   917  1357 D ActivityManager: caller:android.app.ApplicationThreadProxy@1abf826f, r.packageName :com.google.android.gms
07-05 12:23:43.268   917  1357 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 12:23:43.268   917  1357 D ActivityManager: caller:android.app.ApplicationThreadProxy@291d5c05, r.packageName :com.google.android.gms
07-05 12:23:43.268  2308  7673 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
07-05 12:23:43.268  2308  7673 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
07-05 12:23:43.278  2308  7673 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
07-05 12:23:43.278  2308  7673 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
07-05 12:23:43.278  1651  1651 I ConfigService: onCreate
07-05 12:23:43.278  1651  1651 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-05 12:23:43.278   917  1249 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 12:23:43.278   917  1249 D ActivityManager: caller:android.app.ApplicationThreadProxy@11afec26, r.packageName :com.google.android.gms
07-05 12:23:43.278  2308  7673 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
07-05 12:23:43.278  2308  7673 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
07-05 12:23:43.278  2308  7673 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
07-05 12:23:43.278   917  1508 D ActivityManager: startService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.sec.android.app.shealth
07-05 12:23:43.278   917  1508 D ActivityManager: caller:android.app.ApplicationThreadProxy@251ece14, r.packageName :com.sec.android.app.shealth
07-05 12:23:43.288  2308  2308 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-05 12:23:43.288   917  1357 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 12:23:43.288   917  1357 D ActivityManager: caller:android.app.ApplicationThreadProxy@224b780, r.packageName :com.google.android.gms
07-05 12:23:43.288  1651  1651 I ConfigService: onBind returning update interface
07-05 12:23:43.288  2308  7673 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
07-05 12:23:43.288  2308  7673 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
07-05 12:23:43.288  2308  7673 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
07-05 12:23:43.298  1651  1651 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-05 12:23:43.298  1651  1651 I ConfigService: onBind returning service broker
07-05 12:23:43.308   917  1648 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 12:23:43.308   917  1648 D ActivityManager: caller:android.app.ApplicationThreadProxy@2a4e59fe, r.packageName :com.google.android.gms
07-05 12:23:43.308  2308  7678 I PeopleContactsSync: CP2 sync disabled
07-05 12:23:43.308  2308  2308 I ConfigFetchService: service connected
07-05 12:23:43.308  2308  4320 I Icing   : doRemovePackageData com.test.thalitest
07-05 12:23:43.318  2308  7674 W BaseAppContext: Using Auth Proxy for data requests.
07-05 12:23:43.318  2308  7674 W BaseAppContext: Using Auth Proxy for data requests.
07-05 12:23:43.328   917  1712 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
07-05 12:23:43.328   917  1712 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:43.328   917  1712 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:43.328   917  1712 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:43.328   917  1712 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:43.368  7679  7679 E Zygote  : MountEmulatedStorage()
07-05 12:23:43.368  7679  7679 E Zygote  : v2
07-05 12:23:43.368  7679  7679 I libpersona: KNOX_SDCARD checking this for 10043
07-05 12:23:43.368  7679  7679 I libpersona: KNOX_SDCARD not a persona
07-05 12:23:43.378   917  1712 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7679 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 12:23:43.398  7679  7679 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 12:23:43.398  7679  7679 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 12:23:43.398  7679  7679 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-05 12:23:43.398   917  1064 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-05 12:23:43.398   917  1064 D PackageManager: userId{-1}
07-05 12:23:43.398   917  1064 D PackageManager: andCode{true}
07-05 12:23:43.398   917  1064 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
07-05 12:23:43.398   917   934 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
07-05 12:23:43.408   917   934 D ActivityManager: caller:android.app.ApplicationThreadProxy@3eddcbac, r.packageName :com.samsung.android.app.galaxyfinder
07-05 12:23:43.418  7679  7679 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:23:43.428  7679  7679 D ActivityThread: Added TimaKeyStore provider
07-05 12:23:43.438  7679  7679 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
07-05 12:23:43.478  7679  7679 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
07-05 12:23:43.478  7679  7679 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
07-05 12:23:43.488  7679  7679 D SPPClientService: PushLog.txt file is not deleted.
07-05 12:23:43.488  7679  7679 D SPPClientService: PushLog.txt file is not deleted.
07-05 12:23:43.488  7679  7679 D SPPClientService: ============PushLog. stop!
07-05 12:23:43.488  7679  7679 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.l.b(Unknown Source)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.l.a(Unknown Source)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.onReceive(Unknown Source)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-05 12:23:43.498  7679  7679 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-05 12:23:43.498  7679  7679 E LNoti   : [b] open fail. SQLException occured
07-05 12:23:43.508  7038  7038 I SA      : [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
07-05 12:23:43.508  7038  7038 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
07-05 12:23:43.508   917  1372 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
07-05 12:23:43.508   917  1372 D ActivityManager: caller:android.app.ApplicationThreadProxy@b865075, r.packageName :com.android.providers.contacts
07-05 12:23:43.518  5958  5958 E SharedPreferencesImpl: Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
07-05 12:23:43.528  7059  7059 D Mms/FreeMessageReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
07-05 12:23:43.528   917  1142 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
07-05 12:23:43.528   917  1142 D ActivityManager: caller:android.app.ApplicationThreadProxy@2e63787b, r.packageName :com.android.mms
07-05 12:23:43.538   917  1712 I TactileAssist: enable value -1
07-05 12:23:43.538   917  1712 I TactileAssist: internal enable value -1
07-05 12:23:43.538   917  1712 I TactileAssist: intensity value -1
07-05 12:23:43.538   917  1712 I TactileAssist: saveAppList value true
07-05 12:23:43.538  7059  7699 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
07-05 12:23:43.538  7059  7699 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
07-05 12:23:43.538   917  1712 I TactileAssist: List of disabled apps :
07-05 12:23:43.548   917  1508 D SettingsProvider: name = reading_mode_app_list

```
