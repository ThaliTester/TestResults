#### Test 61432979123161a_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
D/SSRM:n  (  915): SIOP:: AP = 290, PST = 299, CUR = 450
D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService(  915): Plugged
--------- beginning of main
D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): setPowerConnected  = true
D/BatteryService(  915): stay LED for fully charged
D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
E/SMD     (  298): DCD ON
,D/AndroidRuntime( 7274): 
D/AndroidRuntime( 7274): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7274): CheckJNI is OFF
D/AndroidRuntime( 7274): readGMSProperty: start
D/AndroidRuntime( 7274): readGMSProperty: already setted!!
D/AndroidRuntime( 7274): readGMSProperty: end
D/AndroidRuntime( 7274): addProductProperty: start
E/AffinityControl( 7274): AffinityControl: registerfunction enter
D/AndroidRuntime( 7274): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  915): inState():  stateMachine is null !!
I/PersonaManagerService(  915): PersonaId don't exist
I/ActivityManager(  915): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  915): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  915): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  915): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  915): mDVFSHelper.acquire()
E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  915): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7288 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PointerIcon(  915): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  915): setMouseCustomIcon IconType is same.101
D/PointerIcon(  915): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  915): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7274): Shutting down VM
E/Zygote  ( 7288): MountEmulatedStorage()
E/Zygote  ( 7288): v2
I/libpersona( 7288): KNOX_SDCARD checking this for 10079
I/libpersona( 7288): KNOX_SDCARD not a persona
I/SELinux ( 7288): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7288): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7288): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7288): TimaSignature is unavailable
D/ActivityThread( 7288): Added TimaKeyStore provider
D/ConnectivityService(  915): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7288): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  266): id=10 Removed YUIInstallC (5/8)
I/SurfaceFlinger(  266): id=10 Removed YUIInstallC (-2/8)
V/ActivityThread( 3461): updateVisibility : ActivityRecord{23b19d5c token=android.os.BinderProxy@2117c021 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,I/WebViewFactory( 7288): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/ResourcesManager( 7288): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7288): Time to load native libraries: 3 ms (timestamps 1769-1772)
,I/LibraryLoader( 7288): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7288): Binding Chromium to main looper Looper (main, tid 1) {5b8e31c}
,I/LibraryLoader( 7288): Expected native library version number "",actual native library version number ""
,I/chromium( 7288): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7288): Initializing chromium process, singleProcess=true
,W/art     ( 7288): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7288): ApplicationContext is null in ApplicationStatus
,W/chromium( 7288): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 7288): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 7288): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 7288): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU (),
I/Adreno-EGL( 7288): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7288): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7288): Local Branch: mybranch5813579
I/Adreno-EGL( 7288): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7288): Local Patches: NONE
I/Adreno-EGL( 7288): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/ActivityManager(  915): Activity pause timeout for ActivityRecord{25a0aefc u0 com.test.thalitest/.MainActivity t10}
,W/chromium( 7288): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/art     ( 7288): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7288): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7288): CordovaWebView is running on device made by: samsung
,W/art     ( 7288): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7288): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7288): performCreate Call secproduct feature valuefalse
,D/Activity( 7288): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7288): Render dirty regions requested: true
,D/ActivityManager(  915): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler(  915): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  915): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler(  915): handleActiveUserChange for user 0
D/PersonaManagerService(  915): getPersonasForUser(): returning null!
,V/ActivityThread( 7288): updateVisibility : ActivityRecord{e102d76 token=android.os.BinderProxy@3825d038 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  266): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  915): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  915): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  915): setMouseCustomIcon IconType is same.101
D/PointerIcon(  915): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  915): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 7288): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7288): HWUI protection enabled for context ,  &this =0xa064b060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7288): Enabling debug mode 0
,D/InputMethodManagerService(  915): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7288): showStatusIcon on inactive InputConnection
,W/ActivityManager(  915): mDVFSHelper.release()
I/Timeline(  915): Timeline: Activity_windows_visible id: ActivityRecord{25a0aefc u0 com.test.thalitest/.MainActivity t10} time:282441
,I/Timeline( 7288): Timeline: Activity_idle id: android.os.BinderProxy@3825d038 time:282443
,W/BindingManager( 7288): Cannot call determinedVisibility() - never saw a connection for the pid: 7288
,D/JsMessageQueue( 7288): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7288): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258383360
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7288): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7288):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7288):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7288):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7288):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7288): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d1b3467 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7288): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7288):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7288):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7288):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7288):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7288):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7288):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7288):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7288):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7288):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7288): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c06d8b2 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7288): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7288): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,W/System.err( 7288): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 7288): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 7288): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
,W/System.err( 7288): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7288): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7288): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7288): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
,W/System.err( 7288): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7288): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7288): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
,W/System.err( 7288): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7288): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 7288): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7288): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 7288): jxcore cordova android initializing
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7288): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7288): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cb003 added. We now have 2 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7288): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7288): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25aa0b80 added. We now have 2 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7288): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7288): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,W/System.err( 7288): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 7288): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 7288): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
,W/System.err( 7288): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7288): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
,W/System.err( 7288): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
,W/System.err( 7288): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7288): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7288): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
,W/System.err( 7288): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7288): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7288): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 7288): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7288): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,I/chromium( 7288): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 7288): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,E/Watchdog(  915): !@Sync 9
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 300, PST = 299, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryService(  915): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,E/SMD     (  298): DCD ON
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,V/AlarmManager(  915): waitForAlarm result :8
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 298, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  298): DCD ON
,I/PowerManagerService(  915): [PWL] Off : 225s ago
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 297, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  915): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  915): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  915): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  915): initializing...
,I/TLC_TIMA_PKM_initialize(  915): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  915): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  915): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  915): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  915): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  915): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  915): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  915): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  915): App is not loaded in QSEE
,D/QSEECOMAPI: (  915): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  915): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  915): Trustlet response is completed
,E/SMD     (  298): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  915): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  915): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  915): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  915): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  915): !@Sync 10
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 300, PST = 297, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,I/Atfwd_Sendcmd(  333): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  333): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 296, CUR = 450
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,V/AlarmManager(  915): waitForAlarm result :4
,E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,E/Zygote  ( 7345): MountEmulatedStorage()
I/libpersona( 7345): KNOX_SDCARD checking this for 10096
E/Zygote  ( 7345): v2
I/libpersona( 7345): KNOX_SDCARD not a persona
,I/ActivityManager(  915): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7345 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/SELinux ( 7345): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7345): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7345): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1195): handleTimeUpdate
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/TimaKeyStoreProvider( 7345): TimaSignature is unavailable
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardEffectViewController( 1195): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1195): *** don't update sliding image ***
D/ActivityThread( 7345): Added TimaKeyStore provider
,D/ResourcesManager( 7345): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager(  915): Killing 6508:com.sec.android.fotaclient/u0a14 (adj 15): bgCount ##41
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 295, CUR = 450
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 11
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 294, CUR = 450
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/PowerManagerService(  915): [PWL] Off : 275s ago
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  298): DCD ON
,V/AlarmManager(  915): waitForAlarm result :8
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  298): DCD ON
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 12
,E/SMD     (  298): DCD ON
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/BatteryService(  915): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/BatteryService(  915): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 13
,I/PowerManagerService(  915): [PWL] Off : 330s ago
,E/SMD     (  298): DCD ON
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  298): DCD ON
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  298): DCD ON
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 14
,E/SMD     (  298): DCD ON
,I/Atfwd_Sendcmd(  333): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  333): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryService(  915): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 15
,I/PowerManagerService(  915): [PWL] Off : 390s ago
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/BatteryService(  915): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/bootchecker(  329): bootchecker wake up!!
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD ON
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 16
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 17
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/PowerManagerService(  915): [PWL] Off : 455s ago
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  298): DCD ON
,V/AlarmManager(  915): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1195): handleTimeUpdate
,D/KeyguardEffectViewController( 1195): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1195): *** don't update sliding image ***
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): stay LED for fully charged
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 18
,E/SMD     (  298): DCD ON
,I/Atfwd_Sendcmd(  333): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  333): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,E/SMD     (  298): DCD ON
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): stay LED for fully charged
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,E/SMD     (  298): DCD ON
,I/Atfwd_Daemon(  333): Stop the daemon....
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 19
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): stay LED for fully charged
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,V/AlarmManager(  915): waitForAlarm result :8
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  915): [PWL] Off : 525s ago
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,E/SMD     (  298): DCD ON
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  915): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  915): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  915): TimaServiceHandler.handleMessage what =1
,E/SMD     (  298): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  915): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  915): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  915): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  915): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  915): !@Sync 20
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  298): DCD ON
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,E/SMD     (  298): DCD ON
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 21
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 289, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): stay LED for fully charged
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 22
,I/PowerManagerService(  915): [PWL] Off : 600s ago
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 288, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 287, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): stay LED for fully charged
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 286, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 23
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 285, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 284, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/BatteryService(  915): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 283, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 24
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 282, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  915): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  915): stay LED for fully charged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,I/PowerManagerService(  915): [PWL] Off : 680s ago
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
D/BatteryService(  915): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 25
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,V/AlarmManager(  915): waitForAlarm result :8
,E/Watchdog(  915): !@Sync 26
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 27
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  915): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  915): [PWL] Off : 765s ago
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 28
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  298): DCD ON
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  915): Plugged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  915): stay LED for fully charged
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  915): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 29
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryService(  915): stay LED for fully charged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryService(  915): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService(  915): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  915): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  915): TimaServiceHandler.handleMessage what =1
,E/SMD     (  298): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  915): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  915): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  915): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  915): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  915): !@Sync 30
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 290, PST = 281, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryService(  915): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,I/PowerManagerService(  915): [PWL] Off : 855s ago
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 31
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
D/BatteryService(  915): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  915): stay LED for fully charged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 32
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
D/BatteryService(  915): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 33
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  915): stay LED for fully charged
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,E/SMD     (  298): DCD ON
,I/PowerManagerService(  915): [PWL] Off : 950s ago
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  915): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 34
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): stay LED for fully charged
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  915): stay LED for fully charged
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 35
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  915): stay LED for fully charged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/BatteryService(  915): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  915): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 36
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  915): !@Sync 37
,I/PowerManagerService(  915): [PWL] Off : 1050s ago
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  915): stay LED for fully charged
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  915): stay LED for fully charged
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/Watchdog(  915): !@Sync 38
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  915): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  915): stay LED for fully charged
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryService(  915): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  915): !@Sync 39
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryService(  915): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryService(  915): stay LED for fully charged
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/TimaService(  915): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  915): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  915): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  915): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  915): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  915): Updating Usage Statistics in DB @ 1456941376897
,I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
,W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
,W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
,W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
,W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
,W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
,W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
,W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,E/SMD     (  298): DCD ON
,W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
,W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  915): ::getAppControlDB: Exception to create DB
W/System.err(  915): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  915): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  915): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  915): Done Updating Usage Statistics in DB @ 1456941377142
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,I/TLC_TIMA_PKM_measure_kernel(  915): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  915): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  915): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  915): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  915): !@Sync 40
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,I/PowerManagerService(  915): [PWL] Off : 1155s ago
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryService(  915): stay LED for fully charged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  915): !@Sync 41
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  915): !@Sync 42
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  915): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/Watchdog(  915): !@Sync 43
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
D/BatteryService(  915): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryService(  915): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/Watchdog(  915): !@Sync 44
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,I/PowerManagerService(  915): [PWL] Off : 1265s ago
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
D/BatteryService(  915): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 45
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  915): stay LED for fully charged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 46
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  915): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): stay LED for fully charged
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 47
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  915): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  915): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 48
,I/PowerManagerService(  915): [PWL] Off : 1380s ago
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  298): DCD ON
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  915): stay LED for fully charged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/Watchdog(  915): !@Sync 49
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  915): Plugged
,I/MotionRecognitionService(  915): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  915): stay LED for fully charged
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/TimaService(  915): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  915): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  915): TimaServiceHandler.handleMessage what =1
,E/SMD     (  298): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  915): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  915): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  915): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  915): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  915): !@Sync 50
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450,
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  915): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2930): Disconnected process message: 10
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,E/SMD     (  298): DCD ON
,D/SSRM:n  (  915): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  915): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  915): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  915): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  915): stay LED for fully charged
D/BatteryService(  915): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  915): Plugged
I/MotionRecognitionService(  915): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2930): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2930): Disconnected process message: 10
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  298): DCD ON
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  298): DCD ON
D/AndroidRuntime( 7448): 
D/AndroidRuntime( 7448): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7448): CheckJNI is OFF
D/AndroidRuntime( 7448): readGMSProperty: start
D/AndroidRuntime( 7448): readGMSProperty: already setted!!
D/AndroidRuntime( 7448): readGMSProperty: end
D/AndroidRuntime( 7448): addProductProperty: start
E/AffinityControl( 7448): AffinityControl: registerfunction enter
D/AndroidRuntime( 7448): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  915): START PACKAGE DELETE: observer{193679339}
D/PackageManager(  915): pkg{<packageName>}
D/PackageManager(  915): user{0}
D/PackageManager(  915): caller{2000}
D/PackageManager(  915): flags{3}
D/PersonaManagerService(  915): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  915): isFromApprovedUnInstaller: isApproved : true
D/PackageManager(  915): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService(  915): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  915): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  915): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  915): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  915): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  915): getApplicationUninstallationEnabled
D/PackageManager(  915): !@killApplicatoin: 10079, uninstall pkg
D/ApplicationPolicy(  915): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager(  915): Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
I/ActivityManager(  915): Killing 7288:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest
W/PackageSettings(  915): Skipping PackageSetting{2d7f8871 com.example.hello/10078} due to missing metadata
I/WindowState(  915): WIN DEATH: Window{12ee7de2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  266): id=13 Removed NainActivit (5/8)
I/SurfaceFlinger(  266): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger(  266): id=13 Removed NainActivit (-2/8)
D/PointerIcon(  915): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  915): setMouseCustomIcon IconType is same.101
D/PointerIcon(  915): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  915): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager(  915):   Force finishing activity ActivityRecord{25a0aefc u0 com.test.thalitest/.MainActivity t10}
W/ActivityManager(  915): mDVFSHelper.acquire()
I/ActivityManager(  915): Force stopping com.test.thalitest appid=10079 user=0: pkg removed
I/ActivityManager(  915):   Force finishing activity ActivityRecord{25a0aefc u0 com.test.thalitest/.MainActivity t10 f}
W/ActivityManager(  915): Duplicate finish request for ActivityRecord{25a0aefc u0 com.test.thalitest/.MainActivity t10 f}
I/art     ( 2233): Explicit concurrent mark sweep GC freed 35685(2MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 22MB/30MB, paused 834us total 67.872ms
I/art     ( 6006): Explicit concurrent mark sweep GC freed 7443(338KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 19.084ms total 70.828ms
I/art     ( 1492): Explicit concurrent mark sweep GC freed 25222(1499KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 20MB/26MB, paused 631us total 103.106ms
I/art     ( 7154): Explicit concurrent mark sweep GC freed 4963(351KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 439us total 86.897ms
W/ActivityManager(  915): Spurious death for ProcessRecord{176cd148 7288:com.test.thalitest/u0a79}, curProc for 7288: null
D/ConnectivityService(  915): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager(  915): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
W/GeofencerStateMachine( 1874): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1739): mOCRHelper is null
I/InputReader(  915): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4441): Explicit concurrent mark sweep GC freed 4304(240KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 15MB/26MB, paused 472us total 36.278ms
I/KLMS-2.4.511: ( 6542): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 6542): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1456941696656
I/DBG_DM  ( 3461): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
I/KLMS-2.4.511: ( 6542): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 6542): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/RegisteredServicesCache( 1412): empty dynamic service
I/DBG_DM  ( 3461): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 0
I/DBG_DM  ( 3461): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/DBG_DM  ( 3461): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3461): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 0
I/DBG_DM  ( 3461): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/DBG_DM  ( 3461): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
D/SecContentProvider2(  915): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  915): mCursor = null
I/DBG_DM  ( 3461): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/SecContentProvider2(  915): uri = 14 selection = getSealedState
D/SecContentProvider2(  915): mCursor = null
D/ApplicationPolicy(  915): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  915): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/DBG_DM  ( 3461): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 0
I/DBG_DM  ( 3461): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/art     (  915): Explicit concurrent mark sweep GC freed 204730(14MB) AllocSpace objects, 103(6MB) LOS objects, 30% free, 37MB/53MB, paused 1.954ms total 193.411ms
D/ResourcesManager(  915): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  915): WaitForGcToComplete blocked for 151.520ms for cause Explicit
I/DBG_DM  ( 3461): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3461): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3461): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3461): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager(  915): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  915): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  915): postActiveUserChange, showWhenLocked: false
I/DBG_DM  ( 3461): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
D/ResourcesManager(  915): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/SurfaceFlinger(  266): id=14 createSurf (1080x1920),2 flag=404, YUIInstallC
D/StatusBarManagerService(  915): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  915): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  915): setMouseCustomIcon IconType is same.101
D/PointerIcon(  915): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  915): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 3461): updateVisibility : ActivityRecord{23b19d5c token=android.os.BinderProxy@2117c021 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/ResourcesManager(  915): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/InputMethodManagerService(  915): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  915): Got RemoteException sending setActive(false) notification to pid 7288 uid 10079
W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/Timeline( 3461): Timeline: Activity_idle id: android.os.BinderProxy@2117c021 time:1536451
W/ActivityManager(  915): mDVFSHelper.release()
I/Timeline(  915): Timeline: Activity_windows_visible id: ActivityRecord{7fe94c7 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t8} time:1536453
D/ResourcesManager(  915): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  915): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  915): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  915): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/elm:14491( 6688): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/ResourcesManager(  915): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  915): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  915): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/elm:14491( 6688): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/Books/Books.apk
D/AASAservice-UpdateReceiver( 3651): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 3651): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3651): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
W/System.err( 3651): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 3651): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
W/System.err( 3651): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
W/System.err( 3651): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 3651): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3651): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3651): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
W/System.err( 3651): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3651): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3651): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
W/System.err( 3651): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6933): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6933): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6933): onReceive() : package name is not s health. Return !!!
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/PCWCLIENTTRACE_PushUtil( 6950): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6950): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6950): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6950): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/elm:14491( 6688): ElmAgentService : onCreate()
D/elm:14491( 6688): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/elm:14491( 6688): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6688): MDMBridge.getInstance()
D/elm:14491( 6688): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/elm:14491( 6688): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  915): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/elm:14491( 6688): ElmAgentService : onDestroy().
D/RCPManagerService(  915): PackageReceiver onReceive()
I/HarmonyEASService(  915): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  915): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  915): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  915): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  915): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  915): uID is 10079
V/EnterpriseBillingPolicy(  915): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  915): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  915): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  915): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  915): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  915): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  915): getBillingProfileForVpnEngine - end - null
D/SSRM:aV (  915): MSG_TYPE_APP_REMOVED::
D/KnoxTimeoutHandler(  915): handleActiveUserChange for user 0
D/PersonaManagerService(  915): getPersonasForUser(): returning null!
V/AlarmManagerEXT(  915): com.test.thalitest(10079) is removed.
E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
D/StatusBar( 1195): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1195): isKioskContainerExistOnDevice
D/PersonaManager( 1195): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1195): Icon Only
I/StatusBar( 1195): Icon Only
D/PanelView( 1195): There is/are notification(s) 
D/PanelView( 1195): There is/are notification(s) 
E/Zygote  ( 7480): MountEmulatedStorage()
E/Zygote  ( 7480): v2
I/libpersona( 7480): KNOX_SDCARD checking this for 10043
I/art     (  915): Explicit concurrent mark sweep GC freed 14295(924KB) AllocSpace objects, 5(80KB) LOS objects, 30% free, 37MB/53MB, paused 1.751ms total 242.391ms
I/libpersona( 7480): KNOX_SDCARD not a persona
I/ActivityManager(  915): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7480 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  915): removeObsoleteFile: deleting file=10_task.xml
D/TaskPersister(  915): removeObsoleteFile: deleting file=8_task.xml
D/PackageManager(  915): delete codoeFile: 
D/AASAuninstall(  915): userId = 0, info.removedAppID = -1, info.uid = 10079, packageName = com.test.thalitest
I/AASA_removePackage(  915): UID=10079 Target=com.test.thalitest
D/PackageManager(  915): result of delete: 1{193679339}
I/SELinux ( 7480): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7480): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7480): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 7448): Shutting down VM
D/TimaKeyStoreProvider( 7480): TimaSignature is unavailable
D/ActivityThread( 7480): Added TimaKeyStore provider
D/ResourcesManager( 7480): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService( 7480): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7480): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 7480): PushLog.txt file is not deleted.
D/SPPClientService( 7480): PushLog.txt file is not deleted.
D/SPPClientService( 7480): ============PushLog. stop!
I/SA      ( 6625): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOI6 PSS = 5.701607447389803  ]
I/SA      ( 6625): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager(  915): Killing 6597:com.sec.android.soagent/u0a42 (adj 13): bgCount ##41
E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  915): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7499): MountEmulatedStorage()
E/Zygote  ( 7499): v2
I/libpersona( 7499): KNOX_SDCARD checking this for 10024
I/libpersona( 7499): KNOX_SDCARD not a persona
I/SELinux ( 7499): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7499): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7499): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager(  915): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7499 uid=10024 gids={50024, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
D/Mms/FreeMessageReceiver( 5569): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/TimaKeyStoreProvider( 7499): TimaSignature is unavailable
D/ActivityThread( 7499): Added TimaKeyStore provider
I/TactileAssist(  915): enable value -1
I/TactileAssist(  915): internal enable value -1
I/TactileAssist(  915): intensity value -1
I/TactileAssist(  915): saveAppList value true
D/Mms/FreeMessageReceiverService( 5569): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
I/TactileAssist(  915): List of disabled apps :
D/Mms/FreeMessageReceiverService( 5569): onHandleIntent: ACTION_PACKAGE_REMOVED
I/EventHub(  915): Removing device '/dev/input/event6' due to inotify event
E/SharedPreferencesImpl(  915): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
D/SettingsProvider(  915): name = reading_mode_app_list
D/ResourcesManager( 7499): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
D/Compatibility( 7010): onReceive() it will make start service
W/ContextImpl( 7499): Unable to create files subdir /data/user/0/com.sec.android.provider.logsprovider/cache
E/ActivityThread( 7499): Unable to setupGraphicsSupport due to missing cache directory
I/EventHub(  915): Removing device '/dev/input/event7' due to inotify event
D/Compatibility( 7010): onHandleIntent()
D/Compatibility( 7010): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10079, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 7010): found: 2
D/Compatibility( 7010): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7010): skipping ResolveInfo{1e314aab com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7010): considering ResolveInfo{aff1508 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7010): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7010): enabling receiver ResolveInfo{333494a1 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7010): enabling receiver ResolveInfo{283286c6 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/AndroidRuntime( 7499): Shutting down VM
D/Compatibility( 7010): enabling receiver ResolveInfo{5b7e687 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7010): enabling receiver ResolveInfo{af479b4 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/AndroidRuntime( 7499): FATAL EXCEPTION: main
E/AndroidRuntime( 7499): Process: com.sec.android.provider.logsprovider, PID: 7499
E/AndroidRuntime( 7499): java.lang.RuntimeException: Unable to get provider com.sec.android.provider.logsprovider.LogsProvider: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.provider.logsprovider.LogsProvider" on path: DexPathList[[zip file "/system/priv-app/LogsProvider/LogsProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 7499): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5558)
E/AndroidRuntime( 7499): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
E/AndroidRuntime( 7499): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
E/AndroidRuntime( 7499): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 7499): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 7499): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7499): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 7499): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/AndroidRuntime( 7499): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7499): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7499): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/AndroidRuntime( 7499): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
E/AndroidRuntime( 7499): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.provider.logsprovider.LogsProvider" on path: DexPathList[[zip file "/system/priv-app/LogsProvider/LogsProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 7499): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 7499): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 7499): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 7499): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5543)
E/AndroidRuntime( 7499): 	... 11 more
E/AndroidRuntime( 7499): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/LogsProvider/LogsProvider.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 7499): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 7499): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 7499): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 7499): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 7499): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 7499): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 7499): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 7499): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 7499): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 7499): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
E/AndroidRuntime( 7499): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7499): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7499): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
E/AndroidRuntime( 7499): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
E/AndroidRuntime( 7499): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
E/AndroidRuntime( 7499): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 7499): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 7499): 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
E/AndroidRuntime( 7499): 		... 9 more
E/AndroidRuntime( 7499): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/LogsProvider/LogsProvider.apk'
E/AndroidRuntime( 7499): 		... 27 more
E/AndroidRuntime( 7499): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/LogsProvider/arm/LogsProvider.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 7499): 		... 27 more
E/AndroidRuntime( 7499): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 7499): 		... 27 more
E/AndroidRuntime( 7499): 	Suppressed: java.lang.ClassNotFoundException: com.sec.android.provider.logsprovider.LogsProvider
E/AndroidRuntime( 7499): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 7499): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 7499): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 7499): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 7499): 		... 13 more
E/AndroidRuntime( 7499): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
V/ApplicationPolicy(  915): isApplicationStateBlocked userId 0 pkgname com.sec.android.provider.logsprovider
E/SharedPreferencesImpl( 7010): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
E/SharedPreferencesImpl( 7010): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
D/Compatibility( 7010): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/AndroidRuntime(  915): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  915): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  915): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  915): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  915): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  915): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  915): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  915): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:15135)
E/AndroidRuntime(  915): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  915): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  915): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  915): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  915): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  915): 	... 5 more
I/UpdateIcingCorporaServi( 1492): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/android.os.Debug(  915): ro.product_ship = true
E/android.os.Debug(  915): ro.debug_level = 0x4f4c
E/SQLiteLog( 6006): (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteLog( 6006): (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6006): (14) cannot open file at line 32509 of [b3bb660af9]
E/AndroidRuntime(  915): Error reporting crash
E/AndroidRuntime(  915): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  915): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  915): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  915): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  915): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  915): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  915): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:15135)
E/AndroidRuntime(  915): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15142)
E/AndroidRuntime(  915): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14730)
E/AndroidRuntime(  915): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14714)
E/AndroidRuntime(  915): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime(  915): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime(  915): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/AndroidRuntime(  915): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  915): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  915): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  915): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  915): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  915): 	... 11 more
I/Process (  915): Sending signal. PID: 915 SIG: 9
E/SQLiteLog( 6006): (14) os_unix.c:32509: (2) open(/data/data/com.samsung.android.sm/databases/history.db) - 
E/SQLiteDatabase( 6006): Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
E/SQLiteDatabase( 6006): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6006): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6006): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6006): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6006): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6006): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6006): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6006): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6006): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6006): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6006): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6006): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6006): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6006): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6006): 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
E/SQLiteDatabase( 6006): 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
E/SQLiteDatabase( 6006): 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
E/SQLiteDatabase( 6006): 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
E/SQLiteDatabase( 6006): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
E/SQLiteDatabase( 6006): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 6006): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 6006): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6006): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6006): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/SQLiteDatabase( 6006): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6006): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6006): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/SQLiteDatabase( 6006): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
I/Process ( 7499): Sending signal. PID: 7499 SIG: 9
D/AndroidRuntime( 6006): Shutting down VM
E/AndroidRuntime( 6006): FATAL EXCEPTION: main
E/AndroidRuntime( 6006): Process: com.samsung.android.sm, PID: 6006
E/AndroidRuntime( 6006): java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/AndroidRuntime( 6006): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2996)
E/AndroidRuntime( 6006): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/AndroidRuntime( 6006): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/AndroidRuntime( 6006): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6006): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6006): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/AndroidRuntime( 6006): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6006): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6006): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/AndroidRuntime( 6006): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
E/AndroidRuntime( 6006): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/AndroidRuntime( 6006): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6006): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6006): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6006): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6006): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6006): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6006): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime( 6006): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime( 6006): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6006): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/AndroidRuntime( 6006): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6006): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6006): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6006): 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
E/AndroidRuntime( 6006): 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
E/AndroidRuntime( 6006): 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
E/AndroidRuntime( 6006): 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
E/AndroidRuntime( 6006): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
E/AndroidRuntime( 6006): 	... 9 more
E/JavaBinder( 6006): !!! FAILED BINDER TRANSACTION !!!
E/AndroidRuntime( 6006): Error reporting crash
E/AndroidRuntime( 6006): android.os.TransactionTooLargeException
E/AndroidRuntime( 6006): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6006): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6006): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4650)
E/AndroidRuntime( 6006): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6006): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6006): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 6006): Sending signal. PID: 6006 SIG: 9
W/AudioFlinger(  306): power manager service died !!!
W/AudioCache(  306): clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
I/ServiceManager(  264): service 'backup' died
I/ServiceManager(  264): service 'appwidget' died
I/ServiceManager(  264): service 'voiceinteraction' died
I/ServiceManager(  264): service 'SecExternalDisplayService' died
I/ServiceManager(  264): service 'diskstats' died
E/ActivityThread( 1631): Failed to find provider info for logs
I/ServiceManager(  264): service 'mDNIe' died
I/ServiceManager(  264): service 'spengestureservice' died
I/ServiceManager(  264): service 'quickconnect' died
I/ServiceManager(  264): service 'samplingprofiler' died
I/ServiceManager(  264): service 'commontime_management' died
I/ServiceManager(  264): service 'dreams' died
I/ServiceManager(  264): service 'print' died
I/ServiceManager(  264): service 'restrictions' died
I/ServiceManager(  264): service 'media_session' died
I/ServiceManager(  264): service 'media_router' died
I/ServiceManager(  264): service 'trust' died
I/ServiceManager(  264): service 'fingerprint' died
I/ServiceManager(  264): service 'launcherapps' died
I/ServiceManager(  264): service 'voip' died
I/ServiceManager(  264): service 'sec_analytics' died
I/ServiceManager(  264): service 'ABTPersistenceService' died
I/ServiceManager(  264): service 'textservices' died
I/ServiceManager(  264): service 'network_score' died
I/ServiceManager(  264): service 'netstats' died
I/ServiceManager(  264): service 'netpolicy' died
I/ServiceManager(  264): service 'wifi' died
I/ServiceManager(  264): service 'msapwifi' died
I/ServiceManager(  264): service 'wifiscanner' died
I/ServiceManager(  264): service 'rttmanager' died
I/ServiceManager(  264): service 'mum_container_policy' died
I/ServiceManager(  264): service 'enterprise_billing_policy' died
I/ServiceManager(  264): service 'knox_timakeystore_policy' died
I/ServiceManager(  264): service 'enterprise_policy' died
I/ServiceManager(  264): service 'statusbar' died
I/ServiceManager(  264): service 'clipboard' died
I/ServiceManager(  264): service 'clipboardEx' died
I/ServiceManager(  264): service 'network_management' died
I/ServiceManager(  264): service 'wifip2p' died
I/ServiceManager(  264): service 'connectivity' died
I/ServiceManager(  264): service 'sb_service' died
I/ServiceManager(  264): service 'servicediscovery' died
I/ServiceManager(  264): service 'updatelock' died
I/ServiceManager(  264): service 'media_projection' died
I/ServiceManager(  264): service 'imms' died
I/ServiceManager(  264): service 'notification' died
I/ServiceManager(  264): service 'devicestoragemonitor' died
I/ServiceManager(  264): service 'location' died
I/ServiceManager(  264): service 'country_detector' died
I/ServiceManager(  264): service 'search' died
I/ServiceManager(  264): service 'dropbox' died
I/ServiceManager(  264): service 'wallpaper' died
I/ServiceManager(  264): service 'audio' died
I/ServiceManager(  264): service 'DockObserver' died
I/ServiceManager(  264): service 'usb' died
I/ServiceManager(  264): service 'serial' died
I/ServiceManager(  264): service 'tactileassist' died
I/ServiceManager(  264): service 'bluetooth_manager' died
I/ServiceManager(  264): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  264): service 'rcp' died
I/ServiceManager(  264): service 'input_method' died
I/ServiceManager(  264): service 'motion_recognition' died
I/ServiceManager(  264): service 'cover' died
I/ServiceManager(  264): service 'mount' died
I/ServiceManager(  264): service 'lock_settings' died
I/ServiceManager(  264): service 'device_policy' died
I/ServiceManager(  264): service 'harmony_eas_service' died
I/ServiceManager(  264): service 'sdp' died
I/ServiceManager(  264): service 'log_manager_service' died
I/ServiceManager(  264): service 'accessibility' died
I/ServiceManager(  264): service 'hardware' died
I/ServiceManager(  264): service 'battery' died
I/ServiceManager(  264): service 'sedenial' died
I/ServiceManager(  264): service 'vibrator' died
I/ServiceManager(  264): service 'tima' died
I/ServiceManager(  264): service 'cepproxyks' died
I/ServiceManager(  264): service 'CustomFrequencyManagerService' died
I/ServiceManager(  264): service 'enterprise_license_policy' died
I/ServiceManager(  264): service 'application_policy' died
I/ServiceManager(  264): service 'wifi_policy' died
I/ServiceManager(  264): service 'phone_restriction_policy' died
I/ServiceManager(  264): service 'remoteinjection' died
I/ServiceManager(  264): service 'context_aware' died
I/ServiceManager(  264): service 'scontext' died
I/ServiceManager(  264): service 'barbeam' died
I/ServiceManager(  264): service 'multiwindow_facade' died
I/ServiceManager(  264): service 'window' died
I/ServiceManager(  264): service 'input' died
I/ServiceManager(  264): service 'uimode' died
I/ServiceManager(  264): service 'jobscheduler' died
I/ServiceManager(  264): service 'telephony.registry' died
I/ServiceManager(  264): service 'account' died
I/ServiceManager(  264): service 'content' died
I/ServiceManager(  264): service 'DirEncryptService' died
I/ServiceManager(  264): service 'ReactiveService' died
I/ServiceManager(  264): service 'entropy' died
I/ServiceManager(  264): service 'SEAMService' died
I/ServiceManager(  264): service 'persona' died
I/ServiceManager(  264): service 'persona_policy' died
I/ServiceManager(  264): service 'samsung.smartfaceservice' died
I/ServiceManager(  264): service 'consumer_ir' died
I/ServiceManager(  264): service 'alarm' died
I/ServiceManager(  264): service 'scheduling_policy' died
I/ServiceManager(  264): service 'activity' died
I/ServiceManager(  264): service 'user' died
I/ServiceManager(  264): service 'usagestats' died
I/ServiceManager(  264): service 'edmnativehelper' died
I/ServiceManager(  264): service 'procstats' died
I/ServiceManager(  264): service 'gfxinfo' died
I/ServiceManager(  264): service 'dbinfo' died
I/ServiceManager(  264): service 'permission' died
I/ServiceManager(  264): service 'mdm.remotedesktop' died
I/ServiceManager(  264): service 'sensorservice' died
I/ServiceManager(  264): service 'batterystats' died
I/ServiceManager(  264): service 'appops' died
I/ServiceManager(  264): service 'power' died
I/ServiceManager(  264): service 'display' died
I/ServiceManager(  264): service 'package' died
I/ServiceManager(  264): service 'meminfo' died
I/ServiceManager(  264): service 'cpuinfo' died
I/ServiceManager(  264): service 'webviewupdate' died
E/AndroidRuntime( 1631): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 1631): Process: android.process.acore, PID: 1631
E/AndroidRuntime( 1631): java.lang.IllegalArgumentException: Unknown URL content://logs/from_vvm
E/AndroidRuntime( 1631): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1631): 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:476)
E/AndroidRuntime( 1631): 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
E/AndroidRuntime( 1631): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:314)
E/AndroidRuntime( 1631): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/AndroidRuntime( 1631): 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 1631): 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 1631): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1631): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1631): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 1631): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SurfaceFlinger(  266): restart the boot-animation @ binderDied
D/SurfaceFlinger(  266): Set power mode=2, type=0 flinger=0xb6962000
D/qdhwcomposer(  266): hwc_blank: Unblanking display: 0
E/AndroidRuntime( 1631): Error reporting crash
E/AndroidRuntime( 1631): android.os.DeadObjectException
E/AndroidRuntime( 1631): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 1631): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 1631): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4650)
E/AndroidRuntime( 1631): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 1631): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 1631): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 1631): Sending signal. PID: 1631 SIG: 9
E/AndroidRuntime( 4441): FATAL EXCEPTION: AppProvider
E/AndroidRuntime( 4441): Process: com.samsung.android.app.galaxyfinder:tagService, PID: 4441
E/AndroidRuntime( 4441): java.lang.RuntimeException: Package manager has died
E/AndroidRuntime( 4441): 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:608)
E/AndroidRuntime( 4441): 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:590)
E/AndroidRuntime( 4441): 	at com.samsung.android.app.galaxyfinder.applicationprovider.AppProvider.updateApplicationsList(AppProvider.java:461)
E/AndroidRuntime( 4441): 	at com.samsung.android.app.galaxyfinder.applicationprovider.AppProvider.access$300(AppProvider.java:56)
E/AndroidRuntime( 4441): 	at com.samsung.android.app.galaxyfinder.applicationprovider.AppProvider$UpdateHandler.handleMessage(AppProvider.java:203)
E/AndroidRuntime( 4441): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4441): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4441): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 4441): Caused by: android.os.DeadObjectException
E/AndroidRuntime( 4441): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 4441): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 4441): 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3168)
E/AndroidRuntime( 4441): 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:598)
E/AndroidRuntime( 4441): 	... 7 more
E/AndroidRuntime( 4441): Error reporting crash
E/AndroidRuntime( 4441): android.os.DeadObjectException
E/AndroidRuntime( 4441): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 4441): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 4441): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4650)
E/AndroidRuntime( 4441): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 4441): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 4441): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 4441): Sending signal. PID: 4441 SIG: 9
E/WifiManager( 1312): Channel connection lost
W/Sensors ( 1874): sensorservice died [0xaf071e40]
E/WifiManager( 1485): Channel connection lost
E/WifiManager( 1874): Channel connection lost
W/Sensors ( 1424): sensorservice died [0xafa17180]
E/WifiManager( 1492): Channel connection lost
E/WifiManager( 1424): Channel connection lost
W/Sensors ( 1404): sensorservice died [0xaf0fe900]
I/SurfaceFlinger(  266): id=2 Removed GocusedStac (4/8)
I/SurfaceFlinger(  266): id=3 Removed EimLayer (0/7)
I/SurfaceFlinger(  266): id=4 Removed EimLayer (0/6)
I/SurfaceFlinger(  266): id=5 Removed EimLayer (0/5)
I/SurfaceFlinger(  266): id=6 Removed EimLayer (2/4)
I/SurfaceFlinger(  266): id=2 Removed GocusedStac (-2/4)
I/SurfaceFlinger(  266): id=3 Removed EimLayer (-2/4)
I/SurfaceFlinger(  266): id=4 Removed EimLayer (-2/4)
E/WifiManager( 1195): Channel connection lost
W/Sensors ( 1447): sensorservice died [0xaf0ee240]
W/Sensors ( 1889): sensorservice died [0xaf0fea00]
W/Sensors ( 1195): sensorservice died [0xaf0e9240]
W/Sensors ( 1791): sensorservice died [0xaf0b7300]
I/SurfaceFlinger(  266): id=5 Removed EimLayer (-2/4)
I/SurfaceFlinger(  266): id=6 Removed EimLayer (-2/4)
E/chromium( 1492): ### WebView Version 43.0.2357.121 (code 2357121)
I/SurfaceFlinger(  266): id=7 Removed JmageWallpa (0/3)
I/SurfaceFlinger(  266): id=7 Removed JmageWallpa (-2/3)
I/SurfaceFlinger(  266): id=9 Removed TtatusBar (1/2)
I/SurfaceFlinger(  266): id=9 Removed TtatusBar (-2/2)
I/SurfaceFlinger(  266): id=14 Removed YUIInstallC (0/1)
I/SurfaceFlinger(  266): id=14 Removed YUIInstallC (-2/1)
I/SurfaceFlinger(  266): id=12 Removed DolorFade (0/0)
I/SurfaceFlinger(  266): id=12 Removed DolorFade (-2/0)
F/libc    ( 1492): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa0348d88 in tid 7518 (IntentService[U)
E/installd(  310): eof
E/installd(  310): failed to read size
I/installd(  310): closing connection
I/DEBUG   (  293): failed to create /data/tombstones: Read-only file system
I/DEBUG   (  293): failed to open /data/tombstones: No such file or directory
E/        (  293): ro.product_ship = true
E/        (  293): ro.debug_level = 0x4f4c
E/audit_log( 1854): File locking failed. error= Bad file number
I/qdhwcomposer(  266): handle_blank_event: dpy:0 panel power state: 1
E/qdexternal(  266): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  266): hwc_blank: Done unblanking display: 0
E/SMD     (  298): DCD ON
I/qdhwcomposer(  266): handle_blank_event: dpy:0 panel power state: 0
I/SurfaceFlinger(  266): Disp[0] Orientation 0=>0

```
