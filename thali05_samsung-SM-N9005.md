#### Test 6136236661fd38c_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
D/AndroidRuntime( 7237): 
D/AndroidRuntime( 7237): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7237): CheckJNI is OFF
D/AndroidRuntime( 7237): readGMSProperty: start
D/AndroidRuntime( 7237): readGMSProperty: already setted!!
D/AndroidRuntime( 7237): readGMSProperty: end
D/AndroidRuntime( 7237): addProductProperty: start
E/AffinityControl( 7237): AffinityControl: registerfunction enter
D/AndroidRuntime( 7237): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  908): inState():  stateMachine is null !!
I/PersonaManagerService(  908): PersonaId don't exist
I/ActivityManager(  908): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  908): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  908): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  908): mDVFSHelper.acquire()
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  908): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7253 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7253): MountEmulatedStorage()
E/Zygote  ( 7253): v2
I/libpersona( 7253): KNOX_SDCARD checking this for 10079
I/libpersona( 7253): KNOX_SDCARD not a persona
D/PointerIcon(  908): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  908): setMouseCustomIcon IconType is same.101
D/PointerIcon(  908): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  908): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7237): Shutting down VM
I/SELinux ( 7253): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7253): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7253): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7253): TimaSignature is unavailable
D/ActivityThread( 7253): Added TimaKeyStore provider
I/SurfaceFlinger(  268): id=10 Removed YUIInstallC (5/8)
I/SurfaceFlinger(  268): id=10 Removed YUIInstallC (-2/8)
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/ActivityThread( 3441): updateVisibility : ActivityRecord{125b47c8 token=android.os.BinderProxy@a9b9fdd {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/ResourcesManager( 7253): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/WebViewFactory( 7253): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
D/ResourcesManager( 7253): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
E/SMD     (  307): DCD ON
I/LibraryLoader( 7253): Time to load native libraries: 3 ms (timestamps 6303-6306)
I/LibraryLoader( 7253): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7253): Binding Chromium to main looper Looper (main, tid 1) {1eb7a988}
I/LibraryLoader( 7253): Expected native library version number "",actual native library version number ""
I/chromium( 7253): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7253): Initializing chromium process, singleProcess=true
W/art     ( 7253): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7253): ApplicationContext is null in ApplicationStatus
W/chromium( 7253): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 7253): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 7253): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
I/Adreno-EGL( 7253): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7253): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7253): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7253): Local Branch: mybranch5813579
I/Adreno-EGL( 7253): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7253): Local Patches: NONE
I/Adreno-EGL( 7253): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
W/ActivityManager(  908): Activity pause timeout for ActivityRecord{30f3a702 u0 com.test.thalitest/.MainActivity t10}
W/chromium( 7253): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
W/art     ( 7253): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7253): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7253): CordovaWebView is running on device made by: samsung
W/art     ( 7253): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7253): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 7253): performCreate Call secproduct feature valuefalse
D/Activity( 7253): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7253): Render dirty regions requested: true
D/ActivityManager(  908): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  908): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  908): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler(  908): handleActiveUserChange for user 0
D/PersonaManagerService(  908): getPersonasForUser(): returning null!
V/ActivityThread( 7253): updateVisibility : ActivityRecord{9e6bb82 token=android.os.BinderProxy@ec13464 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger(  268): id=13 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  908): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  908): setMouseCustomIcon IconType is same.101
D/PointerIcon(  908): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  908): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 7253): Initialized EGL, version 1.4
I/OpenGLRenderer( 7253): HWUI protection enabled for context ,  &this =0xa054b060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7253): Enabling debug mode 0
,D/InputMethodManagerService(  908): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager(  908): mDVFSHelper.release()
I/Timeline(  908): Timeline: Activity_windows_visible id: ActivityRecord{30f3a702 u0 com.test.thalitest/.MainActivity t10} time:136978
W/IInputConnectionWrapper( 7253): showStatusIcon on inactive InputConnection
I/Timeline( 7253): Timeline: Activity_idle id: android.os.BinderProxy@ec13464 time:136994
W/BindingManager( 7253): Cannot call determinedVisibility() - never saw a connection for the pid: 7253
D/JsMessageQueue( 7253): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7253): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258383360
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7253): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7253):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7253):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7253):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7253):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7253): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d125683 added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7253): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7253):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7253):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7253):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7253):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7253):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7253):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7253):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7253):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7253):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7253): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a7a867e added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7253): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7253): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7253): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7253): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 7253): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7253): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7253): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7253): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7253): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7253): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7253): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7253): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7253): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7253): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7253): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7253): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 7253): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7253): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7253): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e99d7df added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7253): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7253): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cc10c2c added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7253): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7253): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7253): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7253): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 7253): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7253): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7253): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7253): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7253): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7253): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7253): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7253): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7253): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7253): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7253): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7253): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/Watchdog(  908): !@Sync 4
,E/SMD     (  307): DCD ON
D/SSRM:n  (  908): SIOP:: AP = 330, PST = 359, CUR = 450
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,I/chromium( 7253): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 7253): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  908): waitForAlarm result :8
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 320, PST = 349, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  908): Plugged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  908): stay LED for fully charged
,I/PowerManagerService(  908): [PWL] Off : 75s ago
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 310, PST = 344, CUR = 450
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10,
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 5
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 310, PST = 338, CUR = 450
,I/ClearcutLoggerApiImpl( 1851): disconnect managed GoogleApiClient
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 310, PST = 332, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/PowerManagerService(  908): [PWL] Off : 105s ago
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/SSRM:n  (  908): SIOP:: AP = 310, PST = 323, CUR = 450
,E/SMD     (  307): DCD ON
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 6
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 310, PST = 318, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,V/AlarmManager(  908): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 315, CUR = 450
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1851): Vacuum at: now=1457013664035 tag=VacuumService
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhenotypeConfigurator( 1851): Scheduling Phenotype for one-off execution 12503 seconds from now (1457013664435)
,I/PhenotypeFlagCommitter( 1851): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1851): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1851): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1851): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1851): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 1851, getuid(): 10015
,I/qtaguid ( 1851): Tagging socket 89 with tag 1000120100000000{268440065,0} uid -1, pid: 1851, getuid(): 10015
,E/SMD     (  307): DCD ON
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1851): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1851): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 1851, getuid(): 10015
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1851): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1851): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1851): Tagging socket 84 with tag 1000040100000000{268436481,0} uid 10015, pid: 1851, getuid(): 10015
,I/qtaguid ( 1851): Tagging socket 92 with tag 1000040100000000{268436481,0} uid 10015, pid: 1851, getuid(): 10015
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1851): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1851): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 1851, getuid(): 10015
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1851): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1851): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 1851, getuid(): 10015
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1851): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1851): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 1851, getuid(): 10015
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1851): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1851): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 1851, getuid(): 10015
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1851): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1851): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 1851, getuid(): 10015
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1851): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1851): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 1851, getuid(): 10015
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/Atfwd_Sendcmd(  348): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  348): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  307): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 140s ago
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  908): SIOP:: AP = 310, PST = 313, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/Watchdog(  908): !@Sync 7
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 311, CUR = 450
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 308, CUR = 450
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 306, CUR = 450
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 8
,I/PowerManagerService(  908): [PWL] Off : 180s ago
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 305, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,V/AlarmManager(  908): waitForAlarm result :8
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 304, CUR = 450
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 303, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 9
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 302, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 301, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,E/SMD     (  307): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 225s ago
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 301, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  908): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  908): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  908): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  908): initializing...
,I/TLC_TIMA_PKM_initialize(  908): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize(  908): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  908): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  908): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  908): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  908): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  908): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  908): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: (  908): App is not loaded in QSEE
,D/QSEECOMAPI: (  908): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  908): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  908): Trustlet response is completed
,E/SMD     (  307): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  908): !@Sync 10
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 300, CUR = 450
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,I/Atfwd_Sendcmd(  348): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  348): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,V/AlarmManager(  908): waitForAlarm result :4
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,E/Zygote  ( 7365): MountEmulatedStorage()
I/libpersona( 7365): KNOX_SDCARD checking this for 10096
E/Zygote  ( 7365): v2
I/libpersona( 7365): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7365 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/SELinux ( 7365): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7365): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7365): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,D/TimaKeyStoreProvider( 7365): TimaSignature is unavailable
,D/ActivityThread( 7365): Added TimaKeyStore provider
,D/ResourcesManager( 7365): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager(  908): Killing 6599:com.sec.android.fotaclient/u0a14 (adj 15): bgCount ##41
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 300, CUR = 450
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  908): !@Sync 11
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/SSRM:n  (  908): SIOP:: AP = 300, PST = 300, CUR = 450
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/PowerManagerService(  908): [PWL] Off : 275s ago
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 299, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 298, CUR = 450
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  908): !@Sync 12
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 297, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,V/AlarmManager(  908): waitForAlarm result :8
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 296, CUR = 450
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/Watchdog(  908): !@Sync 13
,I/PowerManagerService(  908): [PWL] Off : 330s ago
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/Watchdog(  908): !@Sync 14
,E/SMD     (  307): DCD ON
,I/Atfwd_Sendcmd(  348): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  348): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 15
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,I/PowerManagerService(  908): [PWL] Off : 390s ago
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/bootchecker(  342): bootchecker wake up!!
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 16
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 17
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,I/PowerManagerService(  908): [PWL] Off : 455s ago
,I/ServiceManager(  348): Waiting for service AtCmdFwd...
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  348): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 18
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,I/Atfwd_Sendcmd(  348): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  348): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,I/Atfwd_Daemon(  348): Stop the daemon....
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 19
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,I/PowerManagerService(  908): [PWL] Off : 525s ago
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  908): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  908): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  908): TimaServiceHandler.handleMessage what =1
,E/SMD     (  307): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  908): !@Sync 20
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 21
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  307): DCD ON
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 22
,I/PowerManagerService(  908): [PWL] Off : 600s ago
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  908): stay LED for fully charged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 23
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 24
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 680s ago
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 25
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,V/AlarmManager(  908): waitForAlarm result :8
,E/Watchdog(  908): !@Sync 26
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,V/AlarmManager(  908): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,D/LightsService(  908): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  908): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/SensorManager(  908): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  307): DCD ON
,D/LightsService(  908): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  908): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  908): unregisterListener ::   
,D/LightsService(  908): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/AlarmManager(  908): waitForAlarm result :8
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 27
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 765s ago
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 28
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 29
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/TimaService(  908): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  908): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  908): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  908): !@Sync 30
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 855s ago
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 31
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 32
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/Watchdog(  908): !@Sync 33
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 950s ago
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/Watchdog(  908): !@Sync 34
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/Watchdog(  908): !@Sync 35
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/Watchdog(  908): !@Sync 36
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  908): !@Sync 37
,I/PowerManagerService(  908): [PWL] Off : 1050s ago
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  908): !@Sync 38
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  908): !@Sync 39
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/TimaService(  908): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  908): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  908): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  908): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  908): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  908): Updating Usage Statistics in DB @ 1457014670429
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
E/SMD     (  307): DCD ON
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsage(  908): Done Updating Usage Statistics in DB @ 1457014670616
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  908): !@Sync 40
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 1155s ago
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/Watchdog(  908): !@Sync 41
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/Watchdog(  908): !@Sync 42
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/Watchdog(  908): !@Sync 43
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 289, CUR = 450
,E/Watchdog(  908): !@Sync 44
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 1265s ago
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 287, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 286, CUR = 450
,E/Watchdog(  908): !@Sync 45
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 284, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 283, CUR = 450
,E/Watchdog(  908): !@Sync 46
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,V/AlarmManager(  908): waitForAlarm result :8
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 282, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 47
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 48
,I/PowerManagerService(  908): [PWL] Off : 1380s ago
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 49
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  307): DCD ON
,D/TimaService(  908): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  908): TimaServiceHandler.handleMessage what =1
,D/TimaService(  908): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  307): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  908): !@Sync 50
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 281, CUR = 450
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 282, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,D/SSRM:n  (  908): SIOP:: AP = 290, PST = 283, CUR = 450
,E/SMD     (  307): DCD ON
,D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2944): Disconnected process message: 10
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,E/SMD     (  307): DCD ON
,E/SMD     (  307): DCD ON
,E/Watchdog(  908): !@Sync 51
,E/SMD     (  307): DCD ON
,TIME-OUT KILL (timeout was 1400000ms),D/SSRM:n  (  908): SIOP:: AP = 280, PST = 283, CUR = 450
D/BatteryService(  908): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2944): Disconnected process message: 10
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
D/AndroidRuntime( 7474): 
D/AndroidRuntime( 7474): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7474): CheckJNI is OFF
D/AndroidRuntime( 7474): readGMSProperty: start
D/AndroidRuntime( 7474): readGMSProperty: already setted!!
D/AndroidRuntime( 7474): readGMSProperty: end
D/AndroidRuntime( 7474): addProductProperty: start
E/AffinityControl( 7474): AffinityControl: registerfunction enter
D/AndroidRuntime( 7474): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  908): START PACKAGE DELETE: observer{631842242}
D/PackageManager(  908): pkg{<packageName>}
D/PackageManager(  908): user{0}
D/PackageManager(  908): caller{2000}
D/PackageManager(  908): flags{3}
D/PersonaManagerService(  908): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  908): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  908): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  908): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  908): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  908): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  908): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  908): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  908): getApplicationUninstallationEnabled
D/ApplicationPolicy(  908): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  908): !@killApplicatoin: 10079, uninstall pkg
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
I/ActivityManager(  908): Killing 7253:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest
W/PackageSettings(  908): Skipping PackageSetting{28e6fc7b com.example.hello/10078} due to missing metadata
I/WindowState(  908): WIN DEATH: Window{43ca698 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  268): id=13 Removed NainActivit (5/8)
I/SurfaceFlinger(  268): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger(  268): id=13 Removed NainActivit (-2/8)
D/PointerIcon(  908): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  908): setMouseCustomIcon IconType is same.101
D/PointerIcon(  908): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  908): setHoveringSpenCustomIcon IconType is same.1
E/SMD     (  307): DCD ON
I/ActivityManager(  908):   Force finishing activity ActivityRecord{30f3a702 u0 com.test.thalitest/.MainActivity t10}
W/ActivityManager(  908): mDVFSHelper.acquire()
W/ActivityManager(  908): Spurious death for ProcessRecord{8925fd3 7253:com.test.thalitest/u0a79}, curProc for 7253: null
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10079 user=0: pkg removed
I/ActivityManager(  908):   Force finishing activity ActivityRecord{30f3a702 u0 com.test.thalitest/.MainActivity t10 f}
W/ActivityManager(  908): Duplicate finish request for ActivityRecord{30f3a702 u0 com.test.thalitest/.MainActivity t10 f}
I/art     ( 7000): Explicit concurrent mark sweep GC freed 7750(365KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 443us total 30.929ms
I/art     ( 1609): Explicit concurrent mark sweep GC freed 27226(1558KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 20MB/26MB, paused 607us total 95.992ms
I/art     ( 7071): Explicit concurrent mark sweep GC freed 4099(313KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 16MB/21MB, paused 1.038ms total 89.301ms
I/art     ( 6009): Explicit concurrent mark sweep GC freed 13606(628KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 415us total 37.222ms
I/DBG_DM  ( 3441): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3441): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 0
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/art     ( 4538): Explicit concurrent mark sweep GC freed 4454(249KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 15MB/26MB, paused 499us total 27.475ms
I/InputReader(  908): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1689): mOCRHelper is null
W/GeofencerStateMachine( 1851): Ignoring removeGeofence because network location is disabled.
I/art     ( 2201): Explicit concurrent mark sweep GC freed 34524(2MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 22MB/30MB, paused 1.047ms total 118.203ms
I/DBG_DM  ( 3441): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/KLMS-2.4.511: ( 6621): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/DBG_DM  ( 3441): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3441): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 0
D/RegisteredServicesCache( 1411): empty dynamic service
I/DBG_DM  ( 3441): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
W/SQLiteConnectionPool( 2201): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/KLMS-2.4.511: ( 6621): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1457015006896
I/KLMS-2.4.511: ( 6621): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 6621): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
I/DBG_DM  ( 3441): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/DBG_DM  ( 3441): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/SecContentProvider2(  908): uri = 14 selection = getSealedState
D/SecContentProvider2(  908): mCursor = null
D/ApplicationPolicy(  908): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  908): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/DBG_DM  ( 3441): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 0
I/art     (  908): Explicit concurrent mark sweep GC freed 39818(3MB) AllocSpace objects, 94(1505KB) LOS objects, 30% free, 37MB/53MB, paused 1.514ms total 141.214ms
I/art     (  908): WaitForGcToComplete blocked for 100.277ms for cause Explicit
D/ResourcesManager(  908): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/DBG_DM  ( 3441): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 3441): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3441): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3441): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3441): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager(  908): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  908): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  908): postActiveUserChange, showWhenLocked: false
I/DBG_DM  ( 3441): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
I/SurfaceFlinger(  268): id=14 createSurf (1080x1920),2 flag=404, YUIInstallC
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  908): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  908): setMouseCustomIcon IconType is same.101
D/PointerIcon(  908): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  908): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 3441): updateVisibility : ActivityRecord{125b47c8 token=android.os.BinderProxy@a9b9fdd {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/InputMethodManagerService(  908): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/SecContentProvider2(  908): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  908): mCursor = null
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/InputMethodManagerService(  908): Got RemoteException sending setActive(false) notification to pid 7253 uid 10079
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/Timeline( 3441): Timeline: Activity_idle id: android.os.BinderProxy@a9b9fdd time:1553215
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/ActivityManager(  908): mDVFSHelper.release()
I/Timeline(  908): Timeline: Activity_windows_visible id: ActivityRecord{368cc6d1 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t8} time:1553236
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/elm:14491( 6724): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/elm:14491( 6724): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/elm:14491( 6724): ElmAgentService : onCreate()
D/elm:14491( 6724): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 6724): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6724): MDMBridge.getInstance()
D/elm:14491( 6724): MDMBridge.getAllLicenseInfoFromSDK()
D/AASAservice-UpdateReceiver( 3753): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/System.err( 3753): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
D/elm:14491( 6724): MDMBridge.getAllLicenseInfoFromSDK()
W/System.err( 3753): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
W/System.err( 3753): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 3753): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
W/System.err( 3753): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
W/System.err( 3753): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 3753): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3753): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3753): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
W/System.err( 3753): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3753): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3753): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
W/System.err( 3753): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/elm:14491( 6724): ElmAgentService : onDestroy().
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6830): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6830): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6830): onReceive() : package name is not s health. Return !!!
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/PCWCLIENTTRACE_PushUtil( 6845): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6845): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6845): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6845): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/RCPManagerService(  908): PackageReceiver onReceive()
I/HarmonyEASService(  908): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  908): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  908): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  908): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  908): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  908): uID is 10079
V/EnterpriseBillingPolicy(  908): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  908): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  908): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  908): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  908): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  908): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  908): getBillingProfileForVpnEngine - end - null
D/SSRM:aV (  908): MSG_TYPE_APP_REMOVED::
D/KnoxTimeoutHandler(  908): handleActiveUserChange for user 0
D/PersonaManagerService(  908): getPersonasForUser(): returning null!
V/AlarmManagerEXT(  908): com.test.thalitest(10079) is removed.
D/TaskPersister(  908): removeObsoleteFile: deleting file=10_task.xml
D/TaskPersister(  908): removeObsoleteFile: deleting file=8_task.xml
D/StatusBar( 1187): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
D/PersonaManager( 1187): isKioskContainerExistOnDevice
D/PersonaManager( 1187): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1187): Icon Only
I/StatusBar( 1187): Icon Only
D/PanelView( 1187): There is/are notification(s) 
D/PanelView( 1187): There is/are notification(s) 
I/art     (  908): Explicit concurrent mark sweep GC freed 14065(913KB) AllocSpace objects, 5(80KB) LOS objects, 30% free, 36MB/52MB, paused 2.175ms total 300.549ms
E/Zygote  ( 7506): MountEmulatedStorage()
E/Zygote  ( 7506): v2
I/libpersona( 7506): KNOX_SDCARD checking this for 10043
I/libpersona( 7506): KNOX_SDCARD not a persona
I/ActivityManager(  908): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7506 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7506): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7506): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7506): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/PackageManager(  908): delete codoeFile: 
D/TimaKeyStoreProvider( 7506): TimaSignature is unavailable
D/ActivityThread( 7506): Added TimaKeyStore provider
D/AASAuninstall(  908): userId = 0, info.removedAppID = -1, info.uid = 10079, packageName = com.test.thalitest
I/AASA_removePackage(  908): UID=10079 Target=com.test.thalitest
D/PackageManager(  908): result of delete: 1{631842242}
D/AndroidRuntime( 7474): Shutting down VM
D/ResourcesManager( 7506): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService( 7506): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7506): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 7506): PushLog.txt file is not deleted.
D/SPPClientService( 7506): PushLog.txt file is not deleted.
D/SPPClientService( 7506): ============PushLog. stop!
I/SA      ( 6667): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOI6 PSS = 5.701607447389803  ]
I/SA      ( 6667): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager(  908): Killing 6651:com.sec.android.soagent/u0a42 (adj 13): bgCount ##41
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7524): MountEmulatedStorage()
E/Zygote  ( 7524): v2
I/libpersona( 7524): KNOX_SDCARD checking this for 10024
I/libpersona( 7524): KNOX_SDCARD not a persona
I/SELinux ( 7524): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7524): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
I/ActivityManager(  908): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7524 uid=10024 gids={50024, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
E/SELinux ( 7524): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7524): TimaSignature is unavailable
D/ActivityThread( 7524): Added TimaKeyStore provider
D/Mms/FreeMessageReceiver( 5571): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5571): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5571): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist(  908): enable value -1
I/TactileAssist(  908): internal enable value -1
I/TactileAssist(  908): intensity value -1
I/TactileAssist(  908): saveAppList value true
I/TactileAssist(  908): List of disabled apps :
D/ResourcesManager( 7524): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
D/SettingsProvider(  908): name = reading_mode_app_list
D/Compatibility( 6906): onReceive() it will make start service
D/Compatibility( 6906): onHandleIntent()
D/Compatibility( 6906): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10079, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 6906): found: 2
D/Compatibility( 6906): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6906): skipping ResolveInfo{6c6e507 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6906): considering ResolveInfo{26e1d634 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6906): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6906): enabling receiver ResolveInfo{3da43c5d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6906): enabling receiver ResolveInfo{164039d2 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6906): enabling receiver ResolveInfo{1562caa3 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/UpdateIcingCorporaServi( 1609): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 6906): enabling receiver ResolveInfo{11e021a0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/SQLiteLog( 6009): (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
D/Compatibility( 6906): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/SQLiteDatabase( 6009): Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
E/SQLiteDatabase( 6009): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6009): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6009): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6009): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6009): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6009): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6009): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6009): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6009): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6009): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6009): 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
E/SQLiteDatabase( 6009): 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
E/SQLiteDatabase( 6009): 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
E/SQLiteDatabase( 6009): 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
E/SQLiteDatabase( 6009): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
E/SQLiteDatabase( 6009): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 6009): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 6009): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6009): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6009): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/SQLiteDatabase( 6009): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6009): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6009): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/SQLiteDatabase( 6009): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/AndroidRuntime( 6009): Shutting down VM
E/AndroidRuntime( 6009): FATAL EXCEPTION: main
E/AndroidRuntime( 6009): Process: com.samsung.android.sm, PID: 6009
E/AndroidRuntime( 6009): java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6009): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2996)
E/AndroidRuntime( 6009): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/AndroidRuntime( 6009): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/AndroidRuntime( 6009): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6009): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6009): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/AndroidRuntime( 6009): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6009): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6009): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/AndroidRuntime( 6009): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
E/AndroidRuntime( 6009): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6009): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6009): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6009): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime( 6009): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime( 6009): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6009): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/AndroidRuntime( 6009): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6009): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6009): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6009): 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
E/AndroidRuntime( 6009): 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
E/AndroidRuntime( 6009): 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
E/AndroidRuntime( 6009): 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
E/AndroidRuntime( 6009): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
E/AndroidRuntime( 6009): 	... 9 more
V/ApplicationPolicy(  908): isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
E/SQLiteLog( 7524): (28) failed to open "/data/user/0/com.sec.android.provider.logsprovider/databases/logs.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 7524): Failed to open database '/data/user/0/com.sec.android.provider.logsprovider/databases/logs.db'.
E/SQLiteDatabase( 7524): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7524): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7524): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7524): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7524): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7524): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7524): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7524): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7524): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7524): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7524): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7524): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7524): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7524): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7524): 	at com.sec.android.provider.logsprovider.LogsProvider.onCreate(LogsProvider.java:1864)
E/SQLiteDatabase( 7524): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1716)
E/SQLiteDatabase( 7524): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1685)
E/SQLiteDatabase( 7524): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5555)
E/SQLiteDatabase( 7524): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
E/SQLiteDatabase( 7524): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
E/SQLiteDatabase( 7524): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/SQLiteDatabase( 7524): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/SQLiteDatabase( 7524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7524): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7524): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/SQLiteDatabase( 7524): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7524): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7524): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/SQLiteDatabase( 7524): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/AndroidRuntime( 7524): Shutting down VM
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop184.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:15135)
E/DropBoxManagerService(  908): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  908): 	... 5 more
E/AndroidRuntime( 7524): FATAL EXCEPTION: main
E/AndroidRuntime( 7524): Process: com.sec.android.provider.logsprovider, PID: 7524
E/AndroidRuntime( 7524): java.lang.RuntimeException: Unable to get provider com.sec.android.provider.logsprovider.LogsProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7524): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5558)
E/AndroidRuntime( 7524): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
E/AndroidRuntime( 7524): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
E/AndroidRuntime( 7524): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 7524): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 7524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7524): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 7524): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/AndroidRuntime( 7524): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7524): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7524): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/AndroidRuntime( 7524): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
E/AndroidRuntime( 7524): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7524): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7524): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 7524): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 7524): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7524): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7524): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7524): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime( 7524): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime( 7524): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 7524): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/AndroidRuntime( 7524): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 7524): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7524): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7524): 	at com.sec.android.provider.logsprovider.LogsProvider.onCreate(LogsProvider.java:1864)
E/AndroidRuntime( 7524): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1716)
E/AndroidRuntime( 7524): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1685)
E/AndroidRuntime( 7524): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5555)
E/AndroidRuntime( 7524): 	... 11 more
I/EventHub(  908): Removing device '/dev/input/event6' due to inotify event
I/Process ( 6009): Sending signal. PID: 6009 SIG: 9
V/ApplicationPolicy(  908): isApplicationStateBlocked userId 0 pkgname com.sec.android.provider.logsprovider
I/Process ( 7524): Sending signal. PID: 7524 SIG: 9
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop185.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:15135)
E/DropBoxManagerService(  908): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  908): 	... 5 more
E/SQLiteLog( 1609): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 1609): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/chromium( 1609): ### WebView Version 43.0.2357.121 (code 2357121)
F/libc    ( 1609): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa020fe20 in tid 7543 (IntentService[U)
I/EventHub(  908): Removing device '/dev/input/event7' due to inotify event
I/ActivityManager(  908): Process com.samsung.android.sm (pid 6009)(adj 0) has died(324,1526)
I/EventHub(  908): Removing device '/dev/input/event8' due to inotify event
I/EventHub(  908): Removing device '/dev/input/event9' due to inotify event
I/DEBUG   (  302): failed to create /data/tombstones: Read-only file system
I/DEBUG   (  302): failed to open /data/tombstones: No such file or directory
E/        (  302): ro.product_ship = true
E/        (  302): ro.debug_level = 0x4f4c
E/audit_log( 1827): File locking failed. error= Bad file number
I/ActivityManager(  908): Process com.sec.android.provider.logsprovider (pid 7524)(adj 5) has died(326,1527)
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0

```
