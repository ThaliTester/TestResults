#### Test 61362366121daa0_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
,E/Watchdog(  763): !@Sync 8
--------- beginning of main
E/SMD     (  302): DCD ON
D/AndroidRuntime( 7334): 
D/AndroidRuntime( 7334): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7334): CheckJNI is OFF
D/AndroidRuntime( 7334): readGMSProperty: start
D/AndroidRuntime( 7334): readGMSProperty: already setted!!
D/AndroidRuntime( 7334): readGMSProperty: end
D/AndroidRuntime( 7334): addProductProperty: start
E/AffinityControl( 7334): AffinityControl: registerfunction enter
D/AndroidRuntime( 7334): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  763): inState():  stateMachine is null !!
I/PersonaManagerService(  763): PersonaId don't exist
I/ActivityManager(  763): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  763): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  763): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  763): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  763): mDVFSHelper.acquire()
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7349): MountEmulatedStorage()
E/Zygote  ( 7349): v2
I/libpersona( 7349): KNOX_SDCARD checking this for 10079
I/libpersona( 7349): KNOX_SDCARD not a persona
I/ActivityManager(  763): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7349 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7334): Shutting down VM
D/PointerIcon(  763): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  763): setMouseCustomIcon IconType is same.101
D/PointerIcon(  763): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  763): setHoveringSpenCustomIcon IconType is same.1
I/SELinux ( 7349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7349): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7349): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7349): TimaSignature is unavailable
D/ActivityThread( 7349): Added TimaKeyStore provider
D/ConnectivityService(  763): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7349): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  266): id=10 Removed YUIInstallC (5/8)
I/SurfaceFlinger(  266): id=10 Removed YUIInstallC (-2/8)
V/ActivityThread( 3686): updateVisibility : ActivityRecord{23584aba token=android.os.BinderProxy@1ef4a987 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/PowerManagerService(  763): [PWL] Off : 180s ago
I/WebViewFactory( 7349): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
D/ResourcesManager( 7349): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7349): Time to load native libraries: 3 ms (timestamps 9774-9777)
I/LibraryLoader( 7349): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7349): Binding Chromium to main looper Looper (main, tid 1) {3580e67a}
I/LibraryLoader( 7349): Expected native library version number "",actual native library version number ""
I/chromium( 7349): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7349): Initializing chromium process, singleProcess=true
W/art     ( 7349): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7349): ApplicationContext is null in ApplicationStatus
W/chromium( 7349): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 7349): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 7349): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
I/Adreno-EGL( 7349): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7349): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7349): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7349): Local Branch: mybranch5813579
I/Adreno-EGL( 7349): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7349): Local Patches: NONE
I/Adreno-EGL( 7349): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
W/chromium( 7349): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
W/art     ( 7349): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7349): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7349): CordovaWebView is running on device made by: samsung
W/ActivityManager(  763): Activity pause timeout for ActivityRecord{39dabf6f u0 com.test.thalitest/.MainActivity t10}
W/art     ( 7349): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7349): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 7349): performCreate Call secproduct feature valuefalse
D/Activity( 7349): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7349): Render dirty regions requested: true
D/ActivityManager(  763): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  763): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  763): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler(  763): handleActiveUserChange for user 0
D/PersonaManagerService(  763): getPersonasForUser(): returning null!
V/ActivityThread( 7349): updateVisibility : ActivityRecord{2e165d64 token=android.os.BinderProxy@37b1f6f6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger(  266): id=13 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  763): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  763): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  763): setMouseCustomIcon IconType is same.101
D/PointerIcon(  763): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  763): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 7349): Initialized EGL, version 1.4
I/OpenGLRenderer( 7349): HWUI protection enabled for context ,  &this =0xa054b060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7349): Enabling debug mode 0
D/InputMethodManagerService(  763): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager(  763): mDVFSHelper.release()
I/Timeline(  763): Timeline: Activity_windows_visible id: ActivityRecord{39dabf6f u0 com.test.thalitest/.MainActivity t10} time:260266
W/IInputConnectionWrapper( 7349): showStatusIcon on inactive InputConnection
I/Timeline( 7349): Timeline: Activity_idle id: android.os.BinderProxy@37b1f6f6 time:260273
W/BindingManager( 7349): Cannot call determinedVisibility() - never saw a connection for the pid: 7349
D/JsMessageQueue( 7349): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7349): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258383360
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7349): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7349):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7349):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7349):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7349):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7349): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa2e23d added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7349): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7349):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7349):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7349):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7349):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7349):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7349):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7349):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7349):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7349):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7349): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1be900 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7349): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7349): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7349): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7349): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 7349): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7349): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7349): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7349): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7349): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7349): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7349): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7349): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7349): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7349): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7349): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7349): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 7349): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7349): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7349): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31e06539 added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7349): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7349): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e78a77e added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7349): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7349): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7349): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7349): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 7349): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7349): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7349): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7349): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7349): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7349): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7349): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7349): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7349): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7349): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7349): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7349): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/SSRM:n  (  763): SIOP:: AP = 310, PST = 301, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,I/chromium( 7349): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 7349): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/SSRM:n  (  763): SIOP:: AP = 300, PST = 301, CUR = 450
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  763): Plugged,
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 300, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/Watchdog(  763): !@Sync 9
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 299, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 298, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,I/PowerManagerService(  763): [PWL] Off : 225s ago
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 297, CUR = 450
,E/SMD     (  302): DCD ON
,D/TimaService(  763): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  763): TimaServiceHandler.handleMessage what =1
,D/TimaService(  763): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  763): initializing...
,I/TLC_TIMA_PKM_initialize(  763): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize(  763): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  763): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  763): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  763): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  763): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  763): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  763): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: (  763): App is not loaded in QSEE
,E/SMD     (  302): DCD ON
,D/QSEECOMAPI: (  763): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  763): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  763): Trustlet response is completed
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  763): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  763): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  763): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  763): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  763): !@Sync 10
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 300, PST = 297, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,I/Atfwd_Sendcmd(  362): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  362): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 296, CUR = 450
,E/SMD     (  302): DCD ON
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD ON
,V/AlarmManager(  763): waitForAlarm result :4
,E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
,E/SMD     (  302): DCD ON
D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/Zygote  ( 7405): MountEmulatedStorage()
I/libpersona( 7405): KNOX_SDCARD checking this for 10096
E/Zygote  ( 7405): v2
I/libpersona( 7405): KNOX_SDCARD not a persona
,I/ActivityManager(  763): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7405 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7405): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7405): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7405): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 7405): TimaSignature is unavailable
,D/ActivityThread( 7405): Added TimaKeyStore provider
D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ResourcesManager( 7405): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ActivityManager(  763): Killing 4850:com.android.calendar/u0a172 (adj 15): bgCount ##41
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 295, CUR = 450
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 11
,E/SMD     (  302): DCD ON
,V/AlarmManager(  763): waitForAlarm result :8
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/PowerManagerService(  763): [PWL] Off : 275s ago
,E/SMD     (  302): DCD ON
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD ON
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  763): !@Sync 12
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 4
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  302): DCD ON
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 13
,E/SMD     (  302): DCD ON
,I/PowerManagerService(  763): [PWL] Off : 330s ago
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD ON
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  763): !@Sync 14
,E/SMD     (  302): DCD ON
,I/Atfwd_Sendcmd(  362): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  362): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  302): DCD ON
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 15
,E/SMD     (  302): DCD ON
,I/PowerManagerService(  763): [PWL] Off : 390s ago
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD ON
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/bootchecker(  357): bootchecker wake up!!
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD ON
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  763): !@Sync 16
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  302): DCD ON
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 17
,E/SMD     (  302): DCD ON
,V/AlarmManager(  763): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/PowerManagerService(  763): [PWL] Off : 455s ago
,E/SMD     (  302): DCD ON
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  763): !@Sync 18
,E/SMD     (  302): DCD ON
,I/Atfwd_Sendcmd(  362): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  362): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  302): DCD ON
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  302): DCD ON
,I/Atfwd_Daemon(  362): Stop the daemon....
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 19
,E/SMD     (  302): DCD ON
,V/AlarmManager(  763): waitForAlarm result :8
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  302): DCD ON
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  302): DCD ON
,I/PowerManagerService(  763): [PWL] Off : 525s ago
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  302): DCD ON
,D/TimaService(  763): TIMA: TimaService scheduler is intialized. 
D/TimaService(  763): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  763): TimaServiceHandler.handleMessage what =1,
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  763): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  763): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  763): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  763): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  763): !@Sync 20
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 287, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 287, CUR = 450
,E/SMD     (  302): DCD ON
,W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 21
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 22
,E/SMD     (  302): DCD ON
,I/PowerManagerService(  763): [PWL] Off : 600s ago
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 23
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): setPowerConnected  = true
,E/SMD     (  302): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 24
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,I/PowerManagerService(  763): [PWL] Off : 680s ago
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 25
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  763): Plugged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,V/AlarmManager(  763): waitForAlarm result :8
,E/Watchdog(  763): !@Sync 26
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 27
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,I/PowerManagerService(  763): [PWL] Off : 765s ago
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 28
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 29
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  763): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  763): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  763): TimaServiceHandler.handleMessage what =1
,E/SMD     (  302): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  763): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  763): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  763): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  763): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  763): !@Sync 30
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 290, PST = 281, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 281, CUR = 450
,I/PowerManagerService(  763): [PWL] Off : 855s ago
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 31
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 32
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 33
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,I/PowerManagerService(  763): [PWL] Off : 951s ago
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 34
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 35
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 36
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 37
,E/SMD     (  302): DCD ON
,I/PowerManagerService(  763): [PWL] Off : 1051s ago
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 38
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 39
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/TimaService(  763): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  763): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  763): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,I/UsageStatsService(  763): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  763): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  763): Updating Usage Statistics in DB @ 1456926927149
,I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
,W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
,W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
,W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
,W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
,W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  763): ::getAppControlDB: Exception to create DB
W/System.err(  763): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  763): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  763): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsage(  763): Done Updating Usage Statistics in DB @ 1456926927329
,I/TLC_TIMA_PKM_measure_kernel(  763): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  763): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  763): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  763): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  763): !@Sync 40
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,I/PowerManagerService(  763): [PWL] Off : 1156s ago
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  763): !@Sync 41
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  763): !@Sync 42
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  763): !@Sync 43
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  763): !@Sync 44
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,I/PowerManagerService(  763): [PWL] Off : 1266s ago
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  763): !@Sync 45
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  763): !@Sync 46
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  763): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  763): !@Sync 47
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  763): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  763): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  763): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/Watchdog(  763): !@Sync 48
,E/SMD     (  302): DCD ON
,I/PowerManagerService(  763): [PWL] Off : 1381s ago
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/Watchdog(  763): !@Sync 49
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/TimaService(  763): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  763): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  763): TimaServiceHandler.handleMessage what =1
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  763): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  763): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  763): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  763): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  763): !@Sync 50
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  763): !@Sync 51
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  763): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 52
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD ON
,I/PowerManagerService(  763): [PWL] Off : 1501s ago
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  763): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 53
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 54
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): stay LED for fully charged
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  763): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  763): Plugged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryService(  763): stay LED for fully charged
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 55
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): stay LED for fully charged
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3155): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/BatteryService(  763): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 56
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD ON
,I/PowerManagerService(  763): [PWL] Off : 1626s ago
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  763): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  763): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  763): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  763): Plugged
,I/MotionRecognitionService(  763): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3155): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3155): Disconnected process message: 10
D/BatteryService(  763): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  302): DCD ON
,E/SMD     (  302): DCD ON
,V/AlarmManager(  763): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/LightsService(  763): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  763): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  763): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
,D/ConnectivityService(  763): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  763): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  763): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  763): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  763): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LightsService(  763): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  763): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  763): unregisterListener ::   
D/LightsService(  763): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  302): DCD ON
,E/Watchdog(  763): !@Sync 57
,V/AlarmManager(  763): waitForAlarm result :8
,E/SMD     (  302): DCD ON
,TIME-OUT KILL (timeout was 1400000ms),D/SSRM:n  (  763): SIOP:: AP = 280, PST = 280, CUR = 450
E/SMD     (  302): DCD ON
D/AndroidRuntime( 7536): 
D/AndroidRuntime( 7536): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7536): CheckJNI is OFF
D/AndroidRuntime( 7536): readGMSProperty: start
D/AndroidRuntime( 7536): readGMSProperty: already setted!!
D/AndroidRuntime( 7536): readGMSProperty: end
D/AndroidRuntime( 7536): addProductProperty: start
E/AffinityControl( 7536): AffinityControl: registerfunction enter
D/AndroidRuntime( 7536): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService(  763): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  763): START PACKAGE DELETE: observer{649423687}
D/PackageManager(  763): pkg{<packageName>}
D/PackageManager(  763): user{0}
D/PackageManager(  763): caller{2000}
D/PackageManager(  763): flags{3}
D/PersonaManagerService(  763): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  763): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  763): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  763): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  763): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  763): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  763): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  763): getApplicationUninstallationEnabled
D/ApplicationPolicy(  763): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  763): !@killApplicatoin: 10079, uninstall pkg
I/ActivityManager(  763): Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
I/ActivityManager(  763): Killing 7349:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest
W/PackageSettings(  763): Skipping PackageSetting{5cd47f1 com.example.hello/10078} due to missing metadata
I/WindowState(  763): WIN DEATH: Window{33b1fe2d u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  266): id=13 Removed NainActivit (5/8)
I/SurfaceFlinger(  266): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger(  266): id=13 Removed NainActivit (-2/8)
D/PointerIcon(  763): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  763): setMouseCustomIcon IconType is same.101
D/PointerIcon(  763): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  763): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager(  763):   Force finishing activity ActivityRecord{39dabf6f u0 com.test.thalitest/.MainActivity t10}
W/ActivityManager(  763): mDVFSHelper.acquire()
D/ConnectivityService(  763): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ActivityManager(  763): Spurious death for ProcessRecord{1d87f74 7349:com.test.thalitest/u0a79}, curProc for 7349: null
I/DBG_DM  ( 3686): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
I/ActivityManager(  763): Force stopping com.test.thalitest appid=10079 user=0: pkg removed
I/ActivityManager(  763):   Force finishing activity ActivityRecord{39dabf6f u0 com.test.thalitest/.MainActivity t10 f}
W/ActivityManager(  763): Duplicate finish request for ActivityRecord{39dabf6f u0 com.test.thalitest/.MainActivity t10 f}
I/DBG_DM  ( 3686): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 0
I/DBG_DM  ( 3686): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/DBG_DM  ( 3686): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3686): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 0
I/DBG_DM  ( 3686): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/DBG_DM  ( 3686): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
D/BatteryService(  763): !@BatteryListener : batteryPropertiesChanged!
I/art     ( 7104): Explicit concurrent mark sweep GC freed 6481(415KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 459us total 58.252ms
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
E/SamsungIME( 1686): mOCRHelper is null
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
W/GeofencerStateMachine( 1883): Ignoring removeGeofence because network location is disabled.
I/InputReader(  763): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
I/art     ( 6042): Explicit concurrent mark sweep GC freed 32333(1797KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 15MB/26MB, paused 541us total 54.111ms
E/Zygote  ( 7563): MountEmulatedStorage()
E/Zygote  ( 7563): v2
I/libpersona( 7563): KNOX_SDCARD checking this for 10023
I/libpersona( 7563): KNOX_SDCARD not a persona
I/ActivityManager(  763): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7563 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
I/DBG_DM  ( 3686): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/art     ( 1613): Explicit concurrent mark sweep GC freed 25056(1491KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 20MB/26MB, paused 778us total 173.618ms
I/art     ( 6153): Explicit concurrent mark sweep GC freed 7366(334KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 312us total 110.225ms
I/art     ( 7045): Explicit concurrent mark sweep GC freed 2163(128KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 392us total 120.612ms
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/art     ( 2232): Explicit concurrent mark sweep GC freed 34550(2MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 22MB/30MB, paused 560us total 193.639ms
I/SELinux ( 7563): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7563): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7563): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/RegisteredServicesCache( 1409): empty dynamic service
D/SecContentProvider2(  763): uri = 14 selection = getSealedState
D/SecContentProvider2(  763): mCursor = null
D/ApplicationPolicy(  763): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  763): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/EnterpriseDeviceManagerService(  763): Package has changed for user 0
D/EnterpriseDeviceManagerService(  763): Admin package name: com.google.android.gms
I/DBG_DM  ( 3686): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 0
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/DBG_DM  ( 3686): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/TimaKeyStoreProvider( 7563): TimaSignature is unavailable
D/ActivityThread( 7563): Added TimaKeyStore provider
I/DBG_DM  ( 3686): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3686): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3686): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3686): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
I/art     (  763): Explicit concurrent mark sweep GC freed 49674(4MB) AllocSpace objects, 137(2MB) LOS objects, 30% free, 37MB/53MB, paused 5.388ms total 190.641ms
D/ResourcesManager(  763): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  763): WaitForGcToComplete blocked for 96.786ms for cause Explicit
D/ActivityManager(  763): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  763): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  763): postActiveUserChange, showWhenLocked: false
I/DBG_DM  ( 3686): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
I/SurfaceFlinger(  266): id=14 createSurf (1080x1920),2 flag=404, YUIInstallC
D/StatusBarManagerService(  763): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  763): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  763): setMouseCustomIcon IconType is same.101
D/PointerIcon(  763): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  763): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 3686): updateVisibility : ActivityRecord{23584aba token=android.os.BinderProxy@1ef4a987 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/SecContentProvider2(  763): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  763): mCursor = null
D/InputMethodManagerService(  763): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
W/InputMethodManagerService(  763): Got RemoteException sending setActive(false) notification to pid 7349 uid 10079
D/ResourcesManager( 7563): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/Timeline( 3686): Timeline: Activity_idle id: android.os.BinderProxy@1ef4a987 time:1734273
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/ActivityManager(  763): mDVFSHelper.release()
I/Timeline(  763): Timeline: Activity_windows_visible id: ActivityRecord{1c2aa8e6 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t8} time:1734295
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
I/KLMS-2.4.511: ( 7563): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/KLMS-2.4.511: ( 7563): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1456927444776
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/KLMS-2.4.511: ( 7563): MainReciver(): PACKAGE_REMOVED
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/KLMS-2.4.511: ( 7563): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/Videos/Videos.apk
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/RCPManagerService(  763): PackageReceiver onReceive()
I/HarmonyEASService(  763): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  763): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/BackupManagerService(  763): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  763): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  763): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  763): uID is 10079
V/EnterpriseBillingPolicy(  763): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  763): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  763): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  763): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  763): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  763): getBillingProfileForVpnEngine - start - com.test.thalitest
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
V/EnterpriseBillingPolicyStorage(  763): getBillingProfileForVpnEngine - end - null
D/SSRM:aV (  763): MSG_TYPE_APP_REMOVED::
D/KnoxTimeoutHandler(  763): handleActiveUserChange for user 0
D/PersonaManagerService(  763): getPersonasForUser(): returning null!
V/AlarmManagerEXT(  763): com.test.thalitest(10079) is removed.
D/TaskPersister(  763): removeObsoleteFile: deleting file=10_task.xml
D/TaskPersister(  763): removeObsoleteFile: deleting file=8_task.xml
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/StatusBar( 1191): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/art     (  763): Explicit concurrent mark sweep GC freed 11347(604KB) AllocSpace objects, 2(32KB) LOS objects, 29% free, 37MB/53MB, paused 3.069ms total 191.671ms
D/PersonaManager( 1191): isKioskContainerExistOnDevice
D/PersonaManager( 1191): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1191): Icon Only
I/StatusBar( 1191): Icon Only
D/PanelView( 1191): There is/are notification(s) 
D/PanelView( 1191): There is/are notification(s) 
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
E/Zygote  ( 7586): MountEmulatedStorage()
E/Zygote  ( 7586): v2
I/libpersona( 7586): KNOX_SDCARD checking this for 10116
I/libpersona( 7586): KNOX_SDCARD not a persona
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
I/ActivityManager(  763): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7586 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  763): Killing 5907:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/PackageManager(  763): delete codoeFile: 
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
I/art     (  337): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 308us total 14.016ms
W/ResourcesManager(  763): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  763): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  763): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  763): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/AASAuninstall(  763): userId = 0, info.removedAppID = -1, info.uid = 10079, packageName = com.test.thalitest
I/AASA_removePackage(  763): UID=10079 Target=com.test.thalitest
D/PackageManager(  763): result of delete: 1{649423687}
D/ResourcesManager(  763): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 267us total 11.758ms
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 333us total 10.141ms
I/SELinux ( 7586): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7586): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7586): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/AndroidRuntime( 7536): Shutting down VM
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
D/TimaKeyStoreProvider( 7586): TimaSignature is unavailable
D/ActivityThread( 7586): Added TimaKeyStore provider
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  763): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  763): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager(  763): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  763): onPackageRemoved : com.test.thalitest
D/ResourcesManager( 7586): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/elm:14491( 7586): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 7586): ELMEngine.ELMEngine( context ).
D/elm:14491( 7586): MDMBridge.setEnterpriseBridge()
D/elm:14491( 7586): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/AASAservice-UpdateReceiver( 3857): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 3857): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3857): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
W/System.err( 3857): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 3857): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
W/System.err( 3857): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
W/System.err( 3857): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 3857): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3857): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3857): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
W/System.err( 3857): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3857): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3857): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
W/System.err( 3857): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/elm:14491( 7586): ElmAgentService : onCreate()
D/elm:14491( 7586): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 7586): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 7586): MDMBridge.getInstance()
D/elm:14491( 7586): MDMBridge.getAllLicenseInfoFromSDK()
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6820): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6820): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6820): onReceive() : package name is not s health. Return !!!
D/elm:14491( 7586): MDMBridge.getAllLicenseInfoFromSDK()
I/PCWCLIENTTRACE_PushUtil( 6835): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6835): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6835): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6835): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/elm:14491( 7586): ElmAgentService : onDestroy().
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7604): MountEmulatedStorage()
E/Zygote  ( 7604): v2
I/libpersona( 7604): KNOX_SDCARD checking this for 10043
I/libpersona( 7604): KNOX_SDCARD not a persona
I/ActivityManager(  763): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7604 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  763): Killing 6444:flipboard.app/u0a125 (adj 15): bgCount ##41
I/SELinux ( 7604): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7604): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7604): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7604): TimaSignature is unavailable
D/ActivityThread( 7604): Added TimaKeyStore provider
D/ResourcesManager( 7604): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService( 7604): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7604): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 7604): PushLog.txt file is not deleted.
D/SPPClientService( 7604): PushLog.txt file is not deleted.
D/SPPClientService( 7604): ============PushLog. stop!
I/SA      ( 6897): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOI6 PSS = 5.701607447389803  ]
I/SA      ( 6897): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager(  763): Killing 5808:com.google.android.gm/u0a128 (adj 13): bgCount ##41
D/Mms/FreeMessageReceiver( 6921): onReceive, action : android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  763): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7623): MountEmulatedStorage()
E/Zygote  ( 7623): v2
I/libpersona( 7623): KNOX_SDCARD checking this for 10024
I/libpersona( 7623): KNOX_SDCARD not a persona
I/ActivityManager(  763): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7623 uid=10024 gids={50024, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
I/SELinux ( 7623): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7623): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7623): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/Mms/FreeMessageReceiverService( 6921): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 6921): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist(  763): enable value -1
I/TactileAssist(  763): internal enable value -1
I/TactileAssist(  763): intensity value -1
I/TactileAssist(  763): saveAppList value true
I/TactileAssist(  763): List of disabled apps :
I/EventHub(  763): Removing device '/dev/input/event6' due to inotify event
D/SettingsProvider(  763): name = reading_mode_app_list
D/Compatibility( 6961): onReceive() it will make start service
D/TimaKeyStoreProvider( 7623): TimaSignature is unavailable
D/Compatibility( 6961): onHandleIntent()
D/ActivityThread( 7623): Added TimaKeyStore provider
D/Compatibility( 6961): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10079, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 6961): found: 2
D/Compatibility( 6961): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6961): skipping ResolveInfo{2dfab421 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6961): considering ResolveInfo{2926f046 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6961): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6961): enabling receiver ResolveInfo{3eedd207 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6961): enabling receiver ResolveInfo{39aabf34 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6961): enabling receiver ResolveInfo{2a2d715d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}

```
