#### Test 613623661dfc74c_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  304): DCD ON
,D/AndroidRuntime( 7495): 
D/AndroidRuntime( 7495): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7495): CheckJNI is OFF
D/AndroidRuntime( 7495): readGMSProperty: start
D/AndroidRuntime( 7495): readGMSProperty: already setted!!
D/AndroidRuntime( 7495): readGMSProperty: end
D/AndroidRuntime( 7495): addProductProperty: start
E/AffinityControl( 7495): AffinityControl: registerfunction enter
D/AndroidRuntime( 7495): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  934): inState():  stateMachine is null !!
I/PersonaManagerService(  934): PersonaId don't exist
I/ActivityManager(  934): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  934): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/ResourcesManager(  934): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
--------- beginning of system
I/ActivityManager(  934): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  934): mDVFSHelper.acquire()
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  934): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7509 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7495): Shutting down VM
E/Zygote  ( 7509): MountEmulatedStorage()
I/libpersona( 7509): KNOX_SDCARD checking this for 10079
E/Zygote  ( 7509): v2
I/libpersona( 7509): KNOX_SDCARD not a persona
D/PointerIcon(  934): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/SELinux ( 7509): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7509): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7509): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon(  934): setMouseCustomIcon IconType is same.101
D/PointerIcon(  934): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  934): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider( 7509): TimaSignature is unavailable
D/ActivityThread( 7509): Added TimaKeyStore provider
D/ConnectivityService(  934): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7509): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  266): id=10 Removed YUIInstallC (5/8)
I/SurfaceFlinger(  266): id=10 Removed YUIInstallC (-2/8)
V/ActivityThread( 3618): updateVisibility : ActivityRecord{3169c2a5 token=android.os.BinderProxy@3721bdc2 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory( 7509): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/ResourcesManager( 7509): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7509): Time to load native libraries: 2 ms (timestamps 4643-4645)
I/LibraryLoader( 7509): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7509): Binding Chromium to main looper Looper (main, tid 1) {3b82651}
I/LibraryLoader( 7509): Expected native library version number "",actual native library version number ""
I/chromium( 7509): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7509): Initializing chromium process, singleProcess=true
W/art     ( 7509): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7509): ApplicationContext is null in ApplicationStatus
W/chromium( 7509): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 7509): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 7509): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
I/Adreno-EGL( 7509): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7509): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7509): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7509): Local Branch: mybranch5813579
I/Adreno-EGL( 7509): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7509): Local Patches: NONE
I/Adreno-EGL( 7509): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
W/ActivityManager(  934): Activity pause timeout for ActivityRecord{2eadb83d u0 com.test.thalitest/.MainActivity t10}
W/chromium( 7509): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
W/art     ( 7509): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7509): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7509): CordovaWebView is running on device made by: samsung
W/art     ( 7509): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7509): Attempt to remove local handle scope entry from IRT, ignoring
D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  934): stay LED for fully charged
I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/Activity( 7509): performCreate Call secproduct feature valuefalse
D/Activity( 7509): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7509): Render dirty regions requested: true
,D/ActivityManager(  934): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  934): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  934): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler(  934): handleActiveUserChange for user 0
D/PersonaManagerService(  934): getPersonasForUser(): returning null!
,V/ActivityThread( 7509): updateVisibility : ActivityRecord{5018c43 token=android.os.BinderProxy@31687cfd {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  266): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  934): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  934): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  934): setMouseCustomIcon IconType is same.101
D/PointerIcon(  934): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,I/OpenGLRenderer( 7509): Initialized EGL, version 1.4
D/PointerIcon(  934): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 7509): HWUI protection enabled for context ,  &this =0xb3bbec68 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7509): Enabling debug mode 0
,D/InputMethodManagerService(  934): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  934): mDVFSHelper.release()
,I/Timeline(  934): Timeline: Activity_windows_visible id: ActivityRecord{2eadb83d u0 com.test.thalitest/.MainActivity t10} time:135381
,W/IInputConnectionWrapper( 7509): showStatusIcon on inactive InputConnection
,I/Timeline( 7509): Timeline: Activity_idle id: android.os.BinderProxy@31687cfd time:135389
,W/BindingManager( 7509): Cannot call determinedVisibility() - never saw a connection for the pid: 7509
D/JsMessageQueue( 7509): Set native->JS mode to OnlineEventsBridgeMode
W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/jxcore_app_log( 7509): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1360697472
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7509): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7509):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7509):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7509):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7509):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7509): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2324ebf0 added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7509): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7509):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7509):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7509):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7509):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7509):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7509):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7509):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7509):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7509):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7509): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1193388f added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7509): addListener: New listener added - the number of listeners is now 1
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7509): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7509): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7509): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7509): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:84)
W/System.err( 7509): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7509): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7509): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7509): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7509): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7509): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7509): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7509): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7509): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7509): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7509): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7509): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 7509): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7509): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7509): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c24f25 added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7509): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7509): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7728fa added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7509): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7509): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7509): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7509): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:84)
W/System.err( 7509): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7509): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7509): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7509): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7509): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7509): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7509): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7509): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7509): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7509): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7509): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7509): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 4
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  934): SIOP:: AP = 310, PST = 353, CUR = 450
,I/chromium( 7509): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 7509): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 310, PST = 343, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  934): [PWL] Off : 75s ago
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  934): SIOP:: AP = 300, PST = 337, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 4
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 5
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 300, PST = 329, CUR = 450
,I/ClearcutLoggerApiImpl( 1805): disconnect managed GoogleApiClient
,E/SMD     (  304): DCD ON
,V/AlarmManager(  934): waitForAlarm result :8
,E/SMD     (  304): DCD ON
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 300, PST = 321, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  934): [PWL] Off : 105s ago
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  934): SIOP:: AP = 300, PST = 312, CUR = 450
,E/SMD     (  304): DCD ON
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  934): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryService(  934): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 6
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 300, PST = 308, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,V/AlarmManager(  934): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1195): handleTimeUpdate
,D/KeyguardEffectViewController( 1195): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1195): *** don't update sliding image ***
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 300, PST = 306, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/Atfwd_Sendcmd(  359): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  359): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,I/PowerManagerService(  934): [PWL] Off : 140s ago
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 302, CUR = 450
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/Watchdog(  934): !@Sync 7
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 300, CUR = 450
,E/SMD     (  304): DCD ON
,V/AlarmManager(  934): waitForAlarm result :8
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 298, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 296, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  934): !@Sync 8
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  934): [PWL] Off : 180s ago
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 294, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,E/Watchdog(  934): !@Sync 9
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  934): Plugged
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
I/MotionRecognitionService(  934): setPowerConnected  = true
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  934): [PWL] Off : 225s ago
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  934): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  934): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  934): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  934): initializing...
,I/TLC_TIMA_PKM_initialize(  934): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize(  934): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  934): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  934): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  934): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  934): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  934): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  934): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  934): App is not loaded in QSEE
,D/QSEECOMAPI: (  934): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  934): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  934): Trustlet response is completed
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/TLC_TIMA_PKM_measure_kernel(  934): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  934): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  934): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  934): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  934): !@Sync 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/Atfwd_Sendcmd(  359): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  359): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,V/AlarmManager(  934): waitForAlarm result :4
,E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): stay LED for fully charged
,E/Zygote  ( 7598): MountEmulatedStorage()
,I/ActivityManager(  934): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7598 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
E/Zygote  ( 7598): v2
I/libpersona( 7598): KNOX_SDCARD checking this for 10096
I/libpersona( 7598): KNOX_SDCARD not a persona
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,I/SELinux ( 7598): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7598): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7598): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.TIME_TICK
V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleTimeUpdate
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardEffectViewController( 1195): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1195): *** don't update sliding image ***
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 7598): TimaSignature is unavailable
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/ActivityThread( 7598): Added TimaKeyStore provider
,D/ResourcesManager( 7598): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  934): Killing 5037:com.android.calendar/u0a172 (adj 15): bgCount ##41
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 11
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,V/AlarmManager(  934): waitForAlarm result :8
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/PowerManagerService(  934): [PWL] Off : 275s ago
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 12
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 13
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  934): [PWL] Off : 330s ago
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  934): Plugged
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryService(  934): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  304): DCD ON
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 14
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  359): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  359): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  304): DCD ON
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 284, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 15
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  934): [PWL] Off : 390s ago
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 283, CUR = 450
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryService(  934): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/bootchecker(  355): bootchecker wake up!!
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  304): DCD ON
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 16
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 4
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 17
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,V/AlarmManager(  934): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1195): handleTimeUpdate
,D/KeyguardEffectViewController( 1195): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1195): *** don't update sliding image ***
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  934): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,V/AlarmManager(  934): waitForAlarm result :8
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/ServiceManager(  359): Waiting for service AtCmdFwd...
,I/PowerManagerService(  934): [PWL] Off : 455s ago
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  359): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 18
,E/SMD     (  304): DCD ON
,I/Atfwd_Sendcmd(  359): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  359): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  934): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  934): stay LED for fully charged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,I/Atfwd_Daemon(  359): Stop the daemon....
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 19
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  934): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryService(  934): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  934): [PWL] Off : 525s ago
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  934): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  934): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  934): TimaServiceHandler.handleMessage what =1
,E/SMD     (  304): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  934): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  934): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  934): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  934): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  934): !@Sync 20
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  934): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  934): stay LED for fully charged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 21
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryService(  934): stay LED for fully charged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  934): Plugged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryService(  934): stay LED for fully charged
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 22
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  934): [PWL] Off : 600s ago
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 23
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 24
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  934): [PWL] Off : 680s ago
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  934): Plugged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 25
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  934): Plugged
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,V/AlarmManager(  934): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1195): handleTimeUpdate
,D/LightsService(  934): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/KeyguardEffectViewController( 1195): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1195): *** don't update sliding image ***
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/LightSensor(  934): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  934): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1195): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2142): Aggregate from 1456919101764 (log), 1456919101764 (data)
,E/Watchdog(  934): !@Sync 26
,D/LightsService(  934): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  934): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  934): unregisterListener ::   
,D/LightsService(  934): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  934): Plugged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  934): setPowerConnected  = true
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 27
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
I/MotionRecognitionService(  934): Plugged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  934): setPowerConnected  = true
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,V/AlarmManager(  934): waitForAlarm result :8
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  934): [PWL] Off : 765s ago
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 28
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 29
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  934): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  934): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  934): TimaServiceHandler.handleMessage what =1
,E/SMD     (  304): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  934): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  934): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  934): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  934): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  934): !@Sync 30
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryService(  934): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true,
,D/BatteryService(  934): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  934): [PWL] Off : 855s ago
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryService(  934): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 31
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryService(  934): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryService(  934): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 32
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  934): !@Sync 33
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  934): Plugged
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  934): [PWL] Off : 950s ago
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  934): !@Sync 34
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  934): !@Sync 35
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  934): !@Sync 36
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  934): Plugged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  934): !@Sync 37
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  934): [PWL] Off : 1050s ago
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  934): !@Sync 38
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  934): Plugged
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  934): !@Sync 39
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryService(  934): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/TimaService(  934): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  934): TimaServiceHandler.handleMessage what =1
,D/TimaService(  934): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  304): DCD ON
,I/UsageStatsService(  934): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  934): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  934): Updating Usage Statistics in DB @ 1456921343023
,I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
,W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
,W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
,W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
,W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
,W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  934): ::getAppControlDB: Exception to create DB
W/System.err(  934): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  934): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  934): Done Updating Usage Statistics in DB @ 1456921343198
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  934): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  934): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  934): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  934): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  934): !@Sync 40
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  934): [PWL] Off : 1155s ago
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  934): !@Sync 41
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryService(  934): stay LED for fully charged
,E/SMD     (  304): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  934): Plugged
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/BatteryService(  934): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  934): !@Sync 42
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  934): !@Sync 43
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
,D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
I/MotionRecognitionService(  934): Plugged
I/MotionRecognitionService(  934): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  934): stay LED for fully charged
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  934): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  934): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  934): stay LED for fully charged
D/BatteryService(  934): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  934): Plugged
,I/MotionRecognitionService(  934): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1195): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1195):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1195): handleBatteryUpdate
D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1195): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/Watchdog(  934): !@Sync 44
,D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  934): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  934): [PWL] Off : 1265s ago
,E/SMD     (  304): DCD ON
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  304): DCD ON
D/SSRM:n  (  934): SIOP:: AP = 280, PST = 280, CUR = 450
D/AndroidRuntime( 7707): 
D/AndroidRuntime( 7707): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7707): CheckJNI is OFF
D/AndroidRuntime( 7707): readGMSProperty: start
D/AndroidRuntime( 7707): readGMSProperty: already setted!!
D/AndroidRuntime( 7707): readGMSProperty: end
D/AndroidRuntime( 7707): addProductProperty: start
E/AffinityControl( 7707): AffinityControl: registerfunction enter
D/AndroidRuntime( 7707): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  934): START PACKAGE DELETE: observer{777070914}
D/PackageManager(  934): pkg{<packageName>}
D/PackageManager(  934): user{0}
D/PackageManager(  934): caller{2000}
D/PackageManager(  934): flags{3}
D/PersonaManagerService(  934): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  934): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  934): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  934): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  934): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  934): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  934): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  934): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  934): getApplicationUninstallationEnabled
D/ApplicationPolicy(  934): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  934): !@killApplicatoin: 10079, uninstall pkg
I/ActivityManager(  934): Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
I/ActivityManager(  934): Killing 7509:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest
W/PackageSettings(  934): Skipping PackageSetting{23ea5246 com.example.hello/10078} due to missing metadata
I/WindowState(  934): WIN DEATH: Window{bfad3eb u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  266): id=13 Removed NainActivit (5/8)
I/SurfaceFlinger(  266): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger(  266): id=13 Removed NainActivit (-2/8)
D/PointerIcon(  934): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  934): setMouseCustomIcon IconType is same.101
D/PointerIcon(  934): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  934): setHoveringSpenCustomIcon IconType is same.1
E/libprocessgroup(  934): failed to kill 1 processes for processgroup 7509
I/ActivityManager(  934):   Force finishing activity ActivityRecord{2eadb83d u0 com.test.thalitest/.MainActivity t10}
W/ActivityManager(  934): mDVFSHelper.acquire()
I/ActivityManager(  934): Force stopping com.test.thalitest appid=10079 user=0: pkg removed
I/ActivityManager(  934):   Force finishing activity ActivityRecord{2eadb83d u0 com.test.thalitest/.MainActivity t10 f}
W/ActivityManager(  934): Duplicate finish request for ActivityRecord{2eadb83d u0 com.test.thalitest/.MainActivity t10 f}
I/art     ( 1589): Explicit concurrent mark sweep GC freed 33325(1834KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 20MB/26MB, paused 616us total 46.281ms
I/art     ( 6389): Explicit concurrent mark sweep GC freed 9727(464KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 464us total 61.078ms
I/art     ( 7216): Explicit concurrent mark sweep GC freed 5331(263KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 462us total 37.555ms
I/art     ( 7270): Explicit concurrent mark sweep GC freed 9657(550KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 467us total 60.660ms
W/ActivityManager(  934): Spurious death for ProcessRecord{1e2cdd53 7509:com.test.thalitest/u0a79}, curProc for 7509: null
I/art     ( 2142): Explicit concurrent mark sweep GC freed 35952(2MB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 22MB/30MB, paused 1.398ms total 92.905ms
I/DBG_DM  ( 3618): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
D/ConnectivityService(  934): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager(  934): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/DBG_DM  ( 3618): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 0
I/InputReader(  934): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1805): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1728): mOCRHelper is null
I/DBG_DM  ( 3618): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/DBG_DM  ( 3618): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3618): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 0
I/DBG_DM  ( 3618): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3618): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
D/ResourcesManager( 1439): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
I/art     ( 6272): Explicit concurrent mark sweep GC freed 36281(1965KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 15MB/26MB, paused 18.439ms total 79.487ms
W/ResourcesManager( 1439): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1439): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1439): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
E/Zygote  ( 7735): MountEmulatedStorage()
E/Zygote  ( 7735): v2
I/libpersona( 7735): KNOX_SDCARD checking this for 10023
I/libpersona( 7735): KNOX_SDCARD not a persona
W/ResourcesManager( 1439): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1439): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1439): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
W/SQLiteConnectionPool( 2142): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/ActivityManager(  934): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7735 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
I/DBG_DM  ( 3618): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/art     (  934): Explicit concurrent mark sweep GC freed 26963(2MB) AllocSpace objects, 44(704KB) LOS objects, 30% free, 36MB/52MB, paused 1.585ms total 143.058ms
I/art     (  934): WaitForGcToComplete blocked for 20.809ms for cause Explicit
D/ResourcesManager(  934): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/SELinux ( 7735): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7735): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7735): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 1439): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
D/RegisteredServicesCache( 1407): empty dynamic service
W/ResourcesManager( 1439): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1439): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/SecContentProvider2(  934): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  934): mCursor = null
D/SecContentProvider2(  934): uri = 14 selection = getSealedState
D/SecContentProvider2(  934): mCursor = null
D/ApplicationPolicy(  934): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  934): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/ResourcesManager(  934): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  934): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
I/DBG_DM  ( 3618): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 0
I/DBG_DM  ( 3618): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/TimaKeyStoreProvider( 7735): TimaSignature is unavailable
D/ActivityThread( 7735): Added TimaKeyStore provider
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/DBG_DM  ( 3618): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/DBG_DM  ( 3618): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3618): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3618): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ActivityManager(  934): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  934): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  934): postActiveUserChange, showWhenLocked: false
I/DBG_DM  ( 3618): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
I/SurfaceFlinger(  266): id=14 createSurf (1080x1920),2 flag=404, YUIInstallC
D/StatusBarManagerService(  934): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager(  934): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager( 7735): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  934): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/PointerIcon(  934): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  934): setMouseCustomIcon IconType is same.101
D/PointerIcon(  934): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  934): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 3618): updateVisibility : ActivityRecord{3169c2a5 token=android.os.BinderProxy@3721bdc2 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/InputMethodManagerService(  934): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  934): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/InputMethodManagerService(  934): Got RemoteException sending setActive(false) notification to pid 7509 uid 10079
W/ContextImpl(  934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  934): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  934): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  934): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  934): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/Timeline( 3618): Timeline: Activity_idle id: android.os.BinderProxy@3721bdc2 time:1350078
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/ActivityManager(  934): mDVFSHelper.release()
I/Timeline(  934): Timeline: Activity_windows_visible id: ActivityRecord{10ed90a6 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t8} time:1350093
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/KLMS-2.4.511: ( 7735): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/KLMS-2.4.511: ( 7735): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1456921476624
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/KLMS-2.4.511: ( 7735): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 7735): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  934): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/RCPManagerService(  934): PackageReceiver onReceive()
I/HarmonyEASService(  934): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  934): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  934): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  934): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  934): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  934): uID is 10079
V/EnterpriseBillingPolicy(  934): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  934): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  934): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  934): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  934): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  934): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  934): getBillingProfileForVpnEngine - end - null
D/SSRM:aV (  934): MSG_TYPE_APP_REMOVED::
D/TaskPersister(  934): removeObsoleteFile: deleting file=10_task.xml
D/TaskPersister(  934): removeObsoleteFile: deleting file=8_task.xml
D/KnoxTimeoutHandler(  934): handleActiveUserChange for user 0
D/PersonaManagerService(  934): getPersonasForUser(): returning null!
V/AlarmManagerEXT(  934): com.test.thalitest(10079) is removed.
D/StatusBar( 1195): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1195): isKioskContainerExistOnDevice
D/PersonaManager( 1195): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1195): Icon Only
I/StatusBar( 1195): Icon Only
D/PanelView( 1195): There is/are notification(s) 
D/PanelView( 1195): There is/are notification(s) 
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7754): MountEmulatedStorage()
E/Zygote  ( 7754): v2
I/libpersona( 7754): KNOX_SDCARD checking this for 10116
I/libpersona( 7754): KNOX_SDCARD not a persona
I/SELinux ( 7754): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7754): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
I/ActivityManager(  934): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7754 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 7754): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  934): Killing 6167:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
D/TimaKeyStoreProvider( 7754): TimaSignature is unavailable
D/ActivityThread( 7754): Added TimaKeyStore provider
I/art     (  934): Explicit concurrent mark sweep GC freed 13630(813KB) AllocSpace objects, 5(80KB) LOS objects, 30% free, 36MB/52MB, paused 1.997ms total 326.342ms
D/ResourcesManager( 7754): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/elm:14491( 7754): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 7754): ELMEngine.ELMEngine( context ).
D/elm:14491( 7754): MDMBridge.setEnterpriseBridge()
D/elm:14491( 7754): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14491( 7754): ElmAgentService : onCreate()
D/elm:14491( 7754): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/AASAservice-UpdateReceiver( 3869): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 3869): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
D/elm:14491( 7754): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 7754): MDMBridge.getInstance()
D/elm:14491( 7754): MDMBridge.getAllLicenseInfoFromSDK()
W/System.err( 3869): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
W/System.err( 3869): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 3869): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
W/System.err( 3869): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
W/System.err( 3869): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 3869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3869): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3869): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
W/System.err( 3869): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3869): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3869): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
W/System.err( 3869): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/elm:14491( 7754): MDMBridge.getAllLicenseInfoFromSDK()
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6024): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6024): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6024): onReceive() : package name is not s health. Return !!!
D/elm:14491( 7754): ElmAgentService : onDestroy().
I/PCWCLIENTTRACE_PushUtil( 7000): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7000): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7000): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7000): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
D/PackageManager(  934): delete codoeFile: 
D/AASAuninstall(  934): userId = 0, info.removedAppID = -1, info.uid = 10079, packageName = com.test.thalitest
I/AASA_removePackage(  934): UID=10079 Target=com.test.thalitest
D/PackageManager(  934): result of delete: 1{777070914}
D/AndroidRuntime( 7707): Shutting down VM
E/Zygote  ( 7772): MountEmulatedStorage()
E/Zygote  ( 7772): v2
I/libpersona( 7772): KNOX_SDCARD checking this for 10043
I/libpersona( 7772): KNOX_SDCARD not a persona
I/ActivityManager(  934): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7772 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  934): Killing 6294:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
I/SELinux ( 7772): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7772): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7772): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7772): TimaSignature is unavailable
D/ActivityThread( 7772): Added TimaKeyStore provider
D/ResourcesManager( 7772): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService( 7772): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7772): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 7772): PushLog.txt file is not deleted.
D/SPPClientService( 7772): PushLog.txt file is not deleted.
D/SPPClientService( 7772): ============PushLog. stop!
I/SA      ( 7066): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOI6 PSS = 5.701607447389803  ]
I/SA      ( 7066): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager(  934): Killing 6333:com.sec.android.app.myfiles/u0a56 (adj 13): bgCount ##41
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  934): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7792): MountEmulatedStorage()
E/Zygote  ( 7792): v2
I/libpersona( 7792): KNOX_SDCARD checking this for 10024
I/libpersona( 7792): KNOX_SDCARD not a persona
I/ActivityManager(  934): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7792 uid=10024 gids={50024, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
I/SELinux ( 7792): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7792): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7792): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/Mms/FreeMessageReceiver( 7087): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/TimaKeyStoreProvider( 7792): TimaSignature is unavailable
D/ActivityThread( 7792): Added TimaKeyStore provider
I/EventHub(  934): Removing device '/dev/input/event6' due to inotify event
D/Mms/FreeMessageReceiverService( 7087): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 7087): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist(  934): enable value -1
I/TactileAssist(  934): internal enable value -1
I/TactileAssist(  934): intensity value -1
I/TactileAssist(  934): saveAppList value true
I/TactileAssist(  934): List of disabled apps :
E/SharedPreferencesImpl(  934): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
D/SettingsProvider(  934): name = reading_mode_app_list
D/Compatibility( 7127): onReceive() it will make start service
D/ResourcesManager( 7792): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
W/ContextImpl( 7792): Unable to create files subdir /data/user/0/com.sec.android.provider.logsprovider/cache
E/ActivityThread( 7792): Unable to setupGraphicsSupport due to missing cache directory
D/Compatibility( 7127): onHandleIntent()
D/Compatibility( 7127): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10079, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AndroidRuntime( 7792): Shutting down VM
E/AndroidRuntime( 7792): FATAL EXCEPTION: main
E/AndroidRuntime( 7792): Process: com.sec.android.provider.logsprovider, PID: 7792
E/AndroidRuntime( 7792): java.lang.RuntimeException: Unable to get provider com.sec.android.provider.logsprovider.LogsProvider: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.provider.logsprovider.LogsProvider" on path: DexPathList[[zip file "/system/priv-app/LogsProvider/LogsProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 7792): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5558)
E/AndroidRuntime( 7792): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
E/AndroidRuntime( 7792): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
E/AndroidRuntime( 7792): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 7792): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 7792): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7792): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 7792): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/AndroidRuntime( 7792): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7792): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7792): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/AndroidRuntime( 7792): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
E/AndroidRuntime( 7792): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.provider.logsprovider.LogsProvider" on path: DexPathList[[zip file "/system/priv-app/LogsProvider/LogsProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 7792): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 7792): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 7792): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 7792): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5543)
E/AndroidRuntime( 7792): 	... 11 more
E/AndroidRuntime( 7792): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/LogsProvider/LogsProvider.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 7792): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 7792): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 7792): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 7792): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 7792): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 7792): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 7792): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 7792): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 7792): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 7792): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
E/AndroidRuntime( 7792): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7792): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7792): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
E/AndroidRuntime( 7792): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
E/AndroidRuntime( 7792): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
E/AndroidRuntime( 7792): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 7792): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 7792): 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
E/AndroidRuntime( 7792): 		... 9 more
E/AndroidRuntime( 7792): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/LogsProvider/LogsProvider.apk'
E/AndroidRuntime( 7792): 		... 27 more
E/AndroidRuntime( 7792): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/LogsProvider/arm/LogsProvider.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 7792): 		... 27 more
E/AndroidRuntime( 7792): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 7792): 		... 27 more
E/AndroidRuntime( 7792): 	Suppressed: java.lang.ClassNotFoundException: com.sec.android.provider.logsprovider.LogsProvider
E/AndroidRuntime( 7792): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 7792): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 7792): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 7792): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 7792): 		... 13 more
E/AndroidRuntime( 7792): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
D/Compatibility( 7127): found: 2
D/Compatibility( 7127): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7127): skipping ResolveInfo{39e7bb24 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7127): considering ResolveInfo{2487d68d com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7127): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7127): enabling receiver ResolveInfo{2f438042 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
V/ApplicationPolicy(  934): isApplicationStateBlocked userId 0 pkgname com.sec.android.provider.logsprovider
D/Compatibility( 7127): enabling receiver ResolveInfo{25dde853 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/AndroidRuntime(  934): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  934): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  934): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  934): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  934): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  934): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  934): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  934): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:15135)
E/AndroidRuntime(  934): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  934): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  934): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  934): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  934): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  934): 	... 5 more
I/UpdateIcingCorporaServi( 1589): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/SQLiteLog( 6389): (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteLog( 6389): (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6389): (14) cannot open file at line 32509 of [b3bb660af9]
E/SQLiteLog( 6389): (14) os_unix.c:32509: (2) open(/data/data/com.samsung.android.sm/databases/history.db) - 
E/SQLiteDatabase( 6389): Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
E/SQLiteDatabase( 6389): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6389): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6389): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6389): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6389): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6389): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6389): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6389): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6389): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6389): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6389): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6389): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6389): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6389): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6389): 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
E/SQLiteDatabase( 6389): 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
E/SQLiteDatabase( 6389): 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
E/SQLiteDatabase( 6389): 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
E/SQLiteDatabase( 6389): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
E/SQLiteDatabase( 6389): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 6389): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 6389): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6389): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6389): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/SQLiteDatabase( 6389): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6389): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6389): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/SQLiteDatabase( 6389): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
I/Process ( 7792): Sending signal. PID: 7792 SIG: 9
D/AndroidRuntime( 6389): Shutting down VM
E/AndroidRuntime( 6389): FATAL EXCEPTION: main
E/AndroidRuntime( 6389): Process: com.samsung.android.sm, PID: 6389
E/AndroidRuntime( 6389): java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/AndroidRuntime( 6389): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2996)
E/AndroidRuntime( 6389): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/AndroidRuntime( 6389): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/AndroidRuntime( 6389): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6389): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6389): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/AndroidRuntime( 6389): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6389): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6389): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/AndroidRuntime( 6389): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
E/AndroidRuntime( 6389): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/AndroidRuntime( 6389): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6389): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6389): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6389): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6389): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6389): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6389): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime( 6389): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime( 6389): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6389): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/AndroidRuntime( 6389): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6389): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6389): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6389): 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
E/AndroidRuntime( 6389): 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
E/AndroidRuntime( 6389): 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
E/AndroidRuntime( 6389): 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
E/AndroidRuntime( 6389): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
E/AndroidRuntime( 6389): 	... 9 more
E/android.os.Debug(  934): ro.product_ship = true
E/android.os.Debug(  934): ro.debug_level = 0x4f4c
I/EventHub(  934): Removing device '/dev/input/event7' due to inotify event
E/AndroidRuntime(  934): Error reporting crash
E/AndroidRuntime(  934): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  934): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  934): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  934): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  934): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  934): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  934): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:15135)
E/AndroidRuntime(  934): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15142)
E/AndroidRuntime(  934): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14730)
E/AndroidRuntime(  934): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14714)
E/AndroidRuntime(  934): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime(  934): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime(  934): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/AndroidRuntime(  934): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  934): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  934): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  934): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  934): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  934): 	... 11 more
I/Process (  934): Sending signal. PID: 934 SIG: 9
D/Compatibility( 7127): enabling receiver ResolveInfo{3f776590 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/JavaBinder( 6389): !!! FAILED BINDER TRANSACTION !!!
E/AndroidRuntime( 6389): Error reporting crash
E/AndroidRuntime( 6389): android.os.TransactionTooLargeException
E/AndroidRuntime( 6389): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6389): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6389): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4650)
E/AndroidRuntime( 6389): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6389): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6389): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 6389): Sending signal. PID: 6389 SIG: 9
E/installd(  316): eof
E/installd(  316): failed to read size
I/installd(  316): closing connection

```
