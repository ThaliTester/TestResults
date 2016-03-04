#### Test 614329799926788_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
I/ServiceManager(  354): Waiting for service AtCmdFwd...
,--------- beginning of system
W/ProcessCpuTracker(  762): Skipping unknown process pid 7399
W/ProcessCpuTracker(  762): Skipping unknown process pid 7400
W/ProcessCpuTracker(  762): Skipping unknown process pid 7407
W/ProcessCpuTracker(  762): Skipping unknown process pid 7413
D/AndroidRuntime( 7416): 
D/AndroidRuntime( 7416): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7416): CheckJNI is OFF
D/AndroidRuntime( 7416): readGMSProperty: start
D/AndroidRuntime( 7416): readGMSProperty: already setted!!
D/AndroidRuntime( 7416): readGMSProperty: end
D/AndroidRuntime( 7416): addProductProperty: start
D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): stay LED for fully charged
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
E/AffinityControl( 7416): AffinityControl: registerfunction enter
D/AndroidRuntime( 7416): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  762): inState():  stateMachine is null !!
I/PersonaManagerService(  762): PersonaId don't exist
I/ActivityManager(  762): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  762): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  762): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  762): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  762): mDVFSHelper.acquire()
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
D/SSRM:n  (  762): SIOP:: AP = 330, PST = 386, CUR = 450
E/Zygote  ( 7432): MountEmulatedStorage()
E/Zygote  ( 7432): v2
I/ActivityManager(  762): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7432 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/libpersona( 7432): KNOX_SDCARD checking this for 10079
I/libpersona( 7432): KNOX_SDCARD not a persona
I/SELinux ( 7432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7432): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7432): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon(  762): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  762): setMouseCustomIcon IconType is same.101
D/PointerIcon(  762): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  762): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7416): Shutting down VM
D/TimaKeyStoreProvider( 7432): TimaSignature is unavailable
D/ActivityThread( 7432): Added TimaKeyStore provider
V/ActivityManager(  762): Display changed displayId=0
I/SurfaceFlinger(  266): id=10 Removed YUIInstallC (5/8)
I/SurfaceFlinger(  266): id=10 Removed YUIInstallC (-2/8)
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/ActivityThread( 3652): updateVisibility : ActivityRecord{21da9004 token=android.os.BinderProxy@2e38a29 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/ResourcesManager( 7432): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/WebViewFactory( 7432): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
D/ResourcesManager( 7432): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7432): Time to load native libraries: 3 ms (timestamps 405-408)
I/LibraryLoader( 7432): Expected native library version number "",actual native library version number ""
W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 1
V/WebViewChromiumFactoryProvider( 7432): Binding Chromium to main looper Looper (main, tid 1) {3d1dc4}
I/LibraryLoader( 7432): Expected native library version number "",actual native library version number ""
I/chromium( 7432): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7432): Initializing chromium process, singleProcess=true
W/art     ( 7432): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7432): ApplicationContext is null in ApplicationStatus
W/chromium( 7432): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 7432): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 7432): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
I/Adreno-EGL( 7432): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7432): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7432): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7432): Local Branch: mybranch5813579
I/Adreno-EGL( 7432): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7432): Local Patches: NONE
I/Adreno-EGL( 7432): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
W/chromium( 7432): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
W/art     ( 7432): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager(  762): Activity pause timeout for ActivityRecord{3810d40a u0 com.test.thalitest/.MainActivity t9}
W/AwContents( 7432): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7432): CordovaWebView is running on device made by: samsung
W/art     ( 7432): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7432): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 7432): performCreate Call secproduct feature valuefalse
D/Activity( 7432): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7432): Render dirty regions requested: true
D/ActivityManager(  762): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  762): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  762): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler(  762): handleActiveUserChange for user 0
D/PersonaManagerService(  762): getPersonasForUser(): returning null!
V/ActivityThread( 7432): updateVisibility : ActivityRecord{3a247cde token=android.os.BinderProxy@774a760 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger(  266): id=13 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  762): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  762): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  762): setMouseCustomIcon IconType is same.101
D/PointerIcon(  762): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  762): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 7432): Initialized EGL, version 1.4
I/OpenGLRenderer( 7432): HWUI protection enabled for context ,  &this =0xa044b060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7432): Enabling debug mode 0
D/InputMethodManagerService(  762): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager(  762): mDVFSHelper.release()
I/Timeline(  762): Timeline: Activity_windows_visible id: ActivityRecord{3810d40a u0 com.test.thalitest/.MainActivity t9} time:121008
W/IInputConnectionWrapper( 7432): showStatusIcon on inactive InputConnection
I/Timeline( 7432): Timeline: Activity_idle id: android.os.BinderProxy@774a760 time:121018
W/BindingManager( 7432): Cannot call determinedVisibility() - never saw a connection for the pid: 7432
D/JsMessageQueue( 7432): Set native->JS mode to OnlineEventsBridgeMode
E/SMD     (  304): DCD ON
D/jxcore_app_log( 7432): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357922560
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@298515af added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@147c009a added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7432): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7432): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7432): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 7432): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7432): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7432): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7432): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7432): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7432): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7432): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7432): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7432): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7432): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7432): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7432): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/FactoryTest( 6424): Not factory mode
D/FactoryTest( 6424): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 6424): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6424): still no open session command from host, so toast
W/ContextImpl( 6424): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1583 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 6424): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.app.ContextImpl.startActivity:1584 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 
I/Timeline( 6424): Timeline: Activity_launch_request id:com.android.settings time:121357
E/PersonaManagerService(  762): inState():  stateMachine is null !!
I/PersonaManagerService(  762): PersonaId don't exist
I/ActivityManager(  762): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  762): isApplicationStateBlocked userId 0 pkgname com.android.settings
I/ActivityManager(  762): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
W/ActivityManager(  762): mDVFSHelper.acquire()
D/JX-Cordova( 7432): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12175dcb added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2888f9a8 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7432): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7432): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7432): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 7432): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7432): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7432): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7432): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7432): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7432): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7432): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7432): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7432): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7432): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7432): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7432): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PointerIcon(  762): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  762): setMouseCustomIcon IconType is same.101
D/PointerIcon(  762): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  762): setHoveringSpenCustomIcon IconType is same.1
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/MTPRx   ( 6424): started activity for popup
D/ResourcesManager( 6424): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager( 6424): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6424): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6424): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6424): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6424): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6424): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/SettingsReceiverActivity( 6424): PREF_DONT_ASK_AGAIN : true
D/PointerIcon(  762): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  762): setMouseCustomIcon IconType is same.101
D/PointerIcon(  762): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  762): setHoveringSpenCustomIcon IconType is same.1
D/InputMethodManagerService(  762): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  762): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@301dbcf8 attribute=null, token = android.os.BinderProxy@220d3e3
D/SettingsReceiverActivity( 6424): dev.kiessupport is : TRUE
D/Activity( 6424): performCreate Call secproduct feature valuefalse
D/Activity( 6424): performCreate Call debug elastic valuetrue
D/ActivityManager(  762): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  762): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  762): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler(  762): handleActiveUserChange for user 0
D/PersonaManagerService(  762): getPersonasForUser(): returning null!
V/ActivityThread( 7432): updateVisibility : ActivityRecord{3a247cde token=android.os.BinderProxy@774a760 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/Timeline( 7432): Timeline: Activity_idle id: android.os.BinderProxy@774a760 time:121579
D/JX-Cordova( 7432): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e53acc1 added. We now have 3 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26898c66 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7432): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7432): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7432): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 7432): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7432): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7432): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7432): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7432): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7432): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7432): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7432): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7432): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7432): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7432): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7432): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 7432): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3c0ba7 added. We now have 4 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5480854 added. We now have 4 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7432): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7432): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7432): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 7432): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7432): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7432): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7432): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7432): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7432): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7432): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7432): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7432): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7432): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7432): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7432): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  304): DCD ON
,W/ActivityManager(  762): mDVFSHelper.release()
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/chromium( 7432): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 7432): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/PowerManagerService(  762): [PWL] Off : 50s ago
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): stay LED for fully charged
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,D/SSRM:n  (  762): SIOP:: AP = 320, PST = 375, CUR = 450
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  762): !@Sync 4
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/SSRM:n  (  762): SIOP:: AP = 320, PST = 365, CUR = 450
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): stay LED for fully charged
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  762): SIOP:: AP = 310, PST = 354, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 75s ago
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/SSRM:n  (  762): SIOP:: AP = 310, PST = 345, CUR = 450
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,V/AlarmManager(  762): waitForAlarm result :8
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 5
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  762): SIOP:: AP = 310, PST = 335, CUR = 450
,I/ClearcutLoggerApiImpl( 1886): disconnect managed GoogleApiClient
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  762): SIOP:: AP = 310, PST = 325, CUR = 450
,E/SMD     (  304): DCD ON
,D/InputReader(  762): Input event: value=1
,D/InputReader(  762): !@notifyKey(172), action=0
D/InputManager-JNI(  762): !@interceptKeyBeforeQueueing(172), action=0
,D/CustomFrequencyManagerService(  762): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 762  pkgName : WAKEUP_BOOSTER@32
,E/SamsungWindowManager(  762): mCoreNumLockHelper.acquire
,D/PowerManagerService(  762): [api] [s] wakeUpWithReason (uid: 1000 pid: 762) eventTime = 182790 event = 1
,I/PowerManagerService(  762): !@[ps] Screen__On  - 1 :  wakeUpWithReason: 1 (uid: 1000 pid: 762)
I/PowerManagerService(  762): Waking up from sleep (uid 1000)...
,D/PowerManagerService(  762): [PWL] sb acquire: PowerManagerService.Broadcasts
V/KeyguardServiceDelegate(  762): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@1daae1e4)
,D/KeyguardViewMediator( 1191): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1191): notifyScreenOnLocked
,D/KeyguardViewMediator( 1191): handleNotifyScreenOn
D/StatusBarKeyguardViewManager( 1191): onScreenTurnedOn()
V/KeyguardServiceDelegate(  762): **** SHOWN CALLED ****
,D/StatusBarKeyguardViewManager( 1191): callback.onShown()
D/PowerManagerService(  762): [s] UserActivityState : 0 -> 1
,I/DisplayPowerController(  762): Blocking screen on until initial contents have been drawn.
D/PowerManagerService(  762): [PWL] sb acquire: PowerManagerService.Display
D/InputManager-JNI(  762): !@handleInterceptActions(172), action=0, wmActions=0
D/InputManager-JNI(  762): Disable repeat for home key when device wake up
D/SContextService(  762): 	.registerCallback : 1, client=
W/CAE     (  762): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
I/CAE     (  762): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
I/CAE     (  762): setCAProperty(ContextAwareService.java:469) - result : true
W/CAE     (  762): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  762): sendAttribute() : service = Auto Rotation
W/CAE     (  762): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
V/CAE     (  762): start(ContextProvider.java:126)
V/CAE     (  762): clear(AutoRotationRunner.java:182)
D/DisplayPowerController(  762): getFinalBrightness : 162 -> 162
D/DisplayPowerController(  762): animation target = 162, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
V/CAE     (  762): enable(AutoRotationRunner.java:158)
,I/CAE     (  762): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager(  762): SendSensorHubData: send data = -79, 7, 0, 0
,D/Sensorhubs(  321): sendContextData: -79, 7, 0, 0
,D/PowerManagerService(  762): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
,D/MISC PowerHAL(  762): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL(  762): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
I/QCOM PowerHAL(  762): Got set_interactive hint
,D/SurfaceFlinger(  266): Set power mode=2, type=0 flinger=0xb6a62000
I/DisplayManagerService(  762): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/qdhwcomposer(  266): hwc_blank: Unblanking display: 0
V/ActivityManager(  762): Display changed displayId=0
,D/CAE     (  762): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  762): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/StatusBar.NetworkController( 1191): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/CAE     (  762): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
I/CAE     (  762): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
D/CAE     (  762): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
I/CAE     (  762): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@21de5e0d, Service : AUTO_ROTATION(1)
W/CAE     (  762): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  762): addSContextService() : service = Auto Rotation
D/SContextService(  762): ===== SContext Service List =====
D/SContextService(  762): Listener : android.hardware.scontext.SContextService$Listener@376431c2, Service : Auto Rotation
D/SContextManager(  762):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@cedd64d, service=Auto Rotation
D/DisplayPowerController(  762): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
I/DisplayPowerController(  762): Unblocked screen on after 72 ms
D/DisplayPowerState(  762): !@ ColorFade exit
I/SurfaceFlinger(  266): id=12 Removed DolorFade (8/8)
I/SurfaceFlinger(  266): id=12 Removed DolorFade (-2/8)
E/libEGL  (  762): call to OpenGL ES API with no current context (logged once per thread)
,D/DisplayPowerController(  762): getFinalBrightness : 162 -> 162
D/DisplayPowerController(  762): animation target = 162, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  (  762): lcd : 115 +
D/lights  (  762): lcd : 115 -
D/lights  (  762): lcd : 148 +
D/lights  (  762): lcd : 148 -
D/DisplayPowerController(  762): getFinalBrightness : 162 -> 162
D/DisplayPowerController(  762): animation target = 162, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService(  762): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  762): SecHardwareInterface.setBatteryADC : true
D/PowerManagerService(  762): [input device light] setInputDeviceLightOn is called : 1
D/PowerManagerService(  762): [input device light] handleInputDeviceLightOn
D/lights  (  762): button : 1 +
D/lights  (  762): button : 1 -
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/PalmMotion(  762): 2013 - SURFACE_MOTION_ENGINE: 1 SURFACE_PALM_TOUCH: 1
D/PalmMotion(  762): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService(  762):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService(  762): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 762) 
D/LightsService(  762): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
E/LightSensor(  762): Light old sensor_state 0, new sensor_state : 512 en : 1
D/DisplayPowerController(  762): getFinalBrightness : 162 -> 162
D/DisplayPowerController(  762): animation target = 162, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  (  762): lcd : 162 +
D/lights  (  762): lcd : 162 -
D/DisplayPowerController(  762): getFinalBrightness : 162 -> 162
D/DisplayPowerController(  762): animation target = 162, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1191): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/NativeNfcManager( 1413): power state=4
D/BrcmNfcJni( 1413): PowerSwitch::com_android_nfc_NativeNfcManager_doSetPowerMode: mode=0x4; screen on unlocked
D/InputManager-JNI(  762): setDeviceInteractive: 1
D/SamsungIME( 1683): showDlgMsgBox : false true true
D/InputManager-JNI(  762): sysfs_write +: /sys/class/input/event3/device/enabled: 1
D/InputManager-JNI(  762): sysfs_write -: /sys/class/input/event3/device/enabled: 1
D/InputManager-JNI(  762): sysfs_write +: /sys/class/input/event4/device/enabled: 1
V/UserPresentBroadcastReceiver( 1886): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/InputManager-JNI(  762): sysfs_write +: /sys/class/input/event2/device/enabled: 1
D/SensorManager(  762): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
D/NfcService( 1413): call the applyRouting
D/SSRM:a  (  762): DeviceInfo:: 000000100000
I/rmt_storage(  295): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
D/SSRM:a  (  762): SettingsAirViewInfo:: 010100000
I/rmt_storage(  295): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  295): wakelock acquired: 1, error no: 42
I/rmt_storage(  295): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,D/InputReader(  762): Input event: value=0
D/InputReader(  762): !@notifyKey(172), action=1
D/InputManager-JNI(  762): !@interceptKeyBeforeQueueing(172), action=1
D/InputManager-JNI(  762): !@handleInterceptActions(172), action=1, wmActions=0
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,I/rmt_storage(  295): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  295): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  295): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 0
I/rmt_storage(  295): 
,I/rmt_storage(  295): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,D/JX-Cordova( 7432): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9208f2 added. We now have 5 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): load: Already loaded
D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a13bb43 added. We now have 5 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7432): addListener: New listener added - the number of listeners is now 1
,D/ActivityManager(  762): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  762): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  762): postActiveUserChange, showWhenLocked: false
,D/LightsService(  762): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 762) 
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
D/LightsService(  762): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
W/System.err( 7432): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
D/BatteryService(  762): turn off LED
D/KnoxTimeoutHandler(  762): handleActiveUserChange for user 0
D/PersonaManagerService(  762): getPersonasForUser(): returning null!
W/System.err( 7432): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 7432): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7432): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7432): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7432): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7432): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7432): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7432): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
D/LightsService(  762): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
W/System.err( 7432): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7432): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7432): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7432): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7432): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/LightSensor(  762): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  762): unregisterListener ::   
,D/lights  (  762): led_pattern : 0 +
D/lights  (  762): led_pattern : 0 -
,D/LightsService(  762): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  762): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  762): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     (  762): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  762): SendSensorHubData: send data = -76, 13, -47, 0
D/Sensorhubs(  321): sendContextData: -76, 13, -47, 0
,D/InputManager-JNI(  762): sysfs_write -: /sys/class/input/event4/device/enabled: 1
,D/InputMethodManagerService(  762): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService(  762):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService(  762):  handler : SCREEN_ON end
,I/Timeline( 7432): Timeline: Activity_idle id: android.os.BinderProxy@774a760 time:183048
,D/NotificationService(  762): ACTION_SCREEN_ON
D/LightsService(  762): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 762) 
D/LightsService(  762): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  762): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  762): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/native  (  762): do suspend false
,D/audio_hw_primary(  309): adev_set_parameters: enter: screen_state=on
V/voice   (  309): voice_set_parameters: enter: screen_state=on
V/voice   (  309): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  309): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  309): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  309): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  309): adev_set_parameters: exit
,I/wpa_supplicant( 1282): reset timer : RESET_TIMER 1
I/wpa_supplicant( 1282): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1282): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 1282): Scan requested (ret=0) - scan timeout 30 seconds
,I/SecExternalDisplayIntents_Java(  762): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/qdexternal(  266): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
I/qdhwcomposer(  266): handle_blank_event: dpy:0 panel power state: 1
,D/qdhwcomposer(  266): hwc_blank: Done unblanking display: 0
D/SurfaceControl(  762): Excessive delay in setPowerMode(): 264ms
D/PowerManagerService(  762): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 267ms
,D/IpRemoteDisplayController(  762): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  762): Bridge Server is not available
,D/InputManager-JNI(  762): sysfs_write -: /sys/class/input/event2/device/enabled: 1
,D/GpsLocationProvider(  762): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService(  762): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler(  762): MSG_ACTION_SCREEN_ON called
,I/NfcService( 1413): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1413): call the applyRouting
,D/accuweather( 1848): [Accuweather J]>>> SWW:67 [0:0] =============== BR act = androidintentactionSCREEN_ON
,D/accuweather( 1848): [Accuweather J]>>> SWW:70 [0:0] =============== androidintentactionSCREEN_ON instance : [0]1
,I/SamsungIME( 1683): getNextShiftState() cursorCapsMode : 0
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.samsung.app( 2876): [MSC]>>>News_Daemon(E) DR:43 [0:0] onReceive() action : androidintentactionSCREEN_ON
,E/com.samsung.app( 2876): [MSC]>>>News_Daemon(E) DR:71 [0:0] [NameNotFoundException] process restart With Widget !!!!!
,W/com.samsung.app( 2876): [MSC]>>>News_Daemon(E) U:95 [0:0]  ::::::::: Available Internal MemorySize ::::::::: = 25315952k
,D/com.samsung.app( 2876): [MSC]>>>News_Daemon(E) DR:104 [0:0] checkPackageNameList is Empty
,I/com.samsung.app( 2876): [MSC]>>>News_Daemon(E) DR:110 [0:0] serviceStatus = 0 checkPackageNameList = 0
D/com.samsung.app( 2876): [MSC]>>>News_Daemon(E) DR:145 [0:0] [CARS][AUTOREFRESHKEY] --> 0
D/com.samsung.app( 2876): [MSC]>>>News_Daemon(E) DR:146 [0:0] [CARS][NRT] = 0
D/com.samsung.app( 2876): [MSC]>>>News_Daemon(E) DR:147 [0:0] [CARS][DT] = 1457077280483
,D/PowerManagerService(  762): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  (  762): SIOP:: AP = 310, PST = 320, CUR = 450
,D/daemonapp( 2876): [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 2876): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 2876): [MSC_Accu_Daemon]>>> daemonapp [Version : 150820735400 ] [ 1 ] 
D/comsamsunglog( 2876): [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 2876): [MSC_Accu_Daemon]>>> ====================================================================================================================
,D/daemonapp( 2876): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 2876): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/daemonapp( 2876): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 2876): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 2876): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 2876): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 2876): [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,D/daemonapp( 2876): [MSC_Accu_Daemon]>>> AWDS:616 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 2876): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 2876): [MSC_Accu_Daemon]>>> AWDS:618 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 2876): [MSC_Accu_Daemon]>>> AWDS:619 [0:0] [ASO][NUT] = 03/04/2016 02:38 PM
,D/daemonapp( 2876): [MSC_Accu_Daemon]>>> AWDS:620 [0:0] [ASO][CT] = 03/04/2016 08:41 AM
D/daemonapp( 2876): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 2876): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,I/BatteryStatsDumper(  762): In refreshStats isReason Screen ON/OFF: true
,D/NetworkStatsFactory(  762): UpdateStatsForKnox
,D/NetworkStatsFactory(  762): UpdateStatsForKnox
,I/BatteryStatsDumper(  762): Screen bin #0: time=17 power=1.0766666666666668E-4
,I/BatteryStatsDumper(  762): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper(  762): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper(  762): Screen bin #3: time=12093 power=0.536123
I/BatteryStatsDumper(  762): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper(  762): Previous Battery Level: 100 Current Level: 100 Delta: 0
,I/BatteryStatsDumper(  762): Writing to database completed
,D/CustomFrequencyManagerService(  762): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 762  tag : WAKEUP_BOOSTER@32
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,E/SMD     (  304): DCD ON
,D/SSRM:a  (  762): DeviceInfo:: 000000100000
,D/SSRM:a  (  762): SettingsAirViewInfo:: 010100000
,D/PowerManagerService(  762): [input device light] handleInputDeviceLightOff
,D/lights  (  762): button : 0 +
,D/lights  (  762): button : 0 -
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1282): nl80211: Received scan results (17 BSSes)
,D/WifiP2pService(  762): InactiveState{ what=147461 }
,D/WifiP2pService(  762): P2pEnabledState{ what=147461 }
,D/WifiP2pService(  762): DefaultState{ what=147461 }
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 5
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 310, PST = 317, CUR = 450
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,E/SMD     (  304): DCD ON
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  762): !@Sync 6
,E/SMD     (  304): DCD ON
,V/AlarmManager(  762): waitForAlarm result :4
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,E/SMD     (  304): DCD ON
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/SSRM:n  (  762): SIOP:: AP = 310, PST = 314, CUR = 450
,E/SMD     (  304): DCD ON
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/PowerManagerService(  762): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  762): getFinalBrightness : 20 -> 20
,D/DisplayPowerController(  762): animation target = 20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService(  762): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  762): lcd : 140 +
,D/lights  (  762): lcd : 140 -
,D/lights  (  762): lcd : 106 +
,D/lights  (  762): lcd : 106 -
,D/lights  (  762): lcd : 73 +
,D/lights  (  762): lcd : 73 -
,D/lights  (  762): lcd : 40 +
,D/DisplayPowerController(  762): getFinalBrightness : 20 -> 20
,D/DisplayPowerController(  762): animation target = 20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  (  762): lcd : 40 -
D/lights  (  762): lcd : 20 +
,D/lights  (  762): lcd : 20 -
,D/DisplayPowerController(  762): getFinalBrightness : 20 -> 20
D/DisplayPowerController(  762): animation target = 20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/SMD     (  304): DCD ON
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/PowerManagerService(  762): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  762): !@[ps] Screen__Off - 1 : timeout (0x4) (2)
,I/PowerManagerService(  762): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService(  762): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/InputManager-JNI(  762): setDeviceInteractive: 0,
,D/PowerManagerService(  762): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService(  762): handleSandman : startDream()
,E/PowerManagerService(  762): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  762): Sleeping (uid 1000)...
D/PowerManagerService(  762): [s] UserActivityState : 4 -> 0
,D/PowerManagerService(  762): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  762): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  266): id=14 createSurf (1080x1920),2 flag=404, DolorFade
,D/InputManager-JNI(  762): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  762): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/InputManager-JNI(  762): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/InputManager-JNI(  762): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  762): sysfs_write +: /sys/class/input/event4/device/enabled: 0
,D/InputManager-JNI(  762): sysfs_write -: /sys/class/input/event4/device/enabled: 0
,D/SContextService(  762): 	.unregisterCallback : 1, client=
D/SContextService(  762): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@376431c2, Service = Auto Rotation, used = 1
,W/CAE     (  762): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  762): stop(ContextProvider.java:149)
,V/CAE     (  762): clear(AutoRotationRunner.java:182)
,V/CAE     (  762): disable(AutoRotationRunner.java:171)
,I/CAE     (  762): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  762): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  321): sendContextData: -78, 7, 0, 0
,D/CAE     (  762): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  762): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/DisplayPowerController(  762): ColorFade: onAnimationStart
,D/DisplayPowerController(  762): getFinalBrightness : 162 -> 0
,D/DisplayPowerController(  762): animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/RampAnimator(  762): mAnimationCallback timeDelta calculate error!! -0.0034508968
,D/CAE     (  762): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  762): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  762): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  762): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  762): removeSContextService() : service = Auto Rotation
D/SContextService(  762): ===== SContext Service List =====
D/SContextManager(  762):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@cedd64d, service=Auto Rotation
,D/KeyguardViewMediator( 1191): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1191): *** KeyguardEffectView getInstanceIfExists ***
,D/KeyguardEffectViewController( 1191): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1191): notifyScreenOffLocked
,D/KeyguardViewMediator( 1191): timeout : 5000
,D/JX-Cordova( 7432): jxcore cordova android initializing
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7432): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@364755c0 added. We now have 6 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): load: Already loaded
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b0032f9 added. We now have 6 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7432): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7432): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,W/System.err( 7432): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7432): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
,W/System.err( 7432): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7432): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7432): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7432): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7432): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7432): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
,W/System.err( 7432): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7432): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7432): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7432): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7432): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7432): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/lights  (  762): lcd : 0 +
,D/DisplayPowerController(  762): getFinalBrightness : 162 -> 0
D/DisplayPowerController(  762): animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  (  762): lcd : 0 -
,D/KeyguardViewMediator( 1191): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1191): handleNotifyScreenOff
V/ActivityThread( 7432): updateVisibility : ActivityRecord{3a247cde token=android.os.BinderProxy@774a760 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/LightsService(  762): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 762) 
,D/LightsService(  762): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
E/LightSensor(  762): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  762): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  762): turn on LED for fully charged
,I/CAE     (  762): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  762): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  762): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  762): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  321): sendContextData: -76, 13, -46, 0
,I/CAE     (  762): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 7, 41, 50,
,D/SensorHubManager(  762): SendSensorHubData: send data = -63, 14, 7, 41, 50
D/Sensorhubs(  321): sendContextData: -63, 14, 7, 41, 50
,D/MotionRecognitionService(  762):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  762):  handler : SCREEN_OFF end 
,D/NotificationService(  762): ACTION_SCREEN_OFF
D/LightsService(  762): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 762) 
D/LightsService(  762): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/audio_hw_primary(  309): adev_set_parameters: enter: screen_state=off
,V/voice   (  309): voice_set_parameters: enter: screen_state=off
V/voice   (  309): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  309): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  309): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  309): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  309): adev_set_parameters: exit
,E/native  (  762): do suspend true
,I/SecExternalDisplayIntents_Java(  762): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,I/BackgroundCompactionService(  762): Schedule Type1 BGCompaction
,D/DisplayPowerState(  762): !@ ColorFade entry
,D/DisplayPowerController(  762): ColorFade: onAnimationEnd
,D/DisplayPowerController(  762): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  762): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController(  762): getFinalBrightness : 0 -> 0
D/DisplayPowerController(  762): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController(  762): getFinalBrightness : 0 -> 0
D/IpRemoteDisplayController(  762): intent received android.intent.action.SCREEN_OFF
D/DisplayPowerController(  762): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/SurfaceFlinger(  266): Set power mode=0, type=0 flinger=0xb6a62000
D/PowerManagerService(  762): [s] DisplayPowerCallbacks : onStateChanged()
D/qdhwcomposer(  266): hwc_blank: Blanking display: 0
D/PowerManagerService(  762): [PWL] sb release: PowerManagerService.Display
,D/IpRemoteDisplayController(  762): Bridge Server is not available
,I/DisplayManagerService(  762): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/VolumePanel.013b4145( 1191): forceTimeout delay=0 callers=com.android.systemui.volume.VolumePanel.postDismiss:2103 com.android.systemui.volume.VolumePanel$8.onReceive:1167 android.app.LoadedApk$ReceiverDispatcher$Args.run:923 
,V/ActivityManager(  762): Display changed displayId=0
,D/VolumePanel( 1191): mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/VolumePanel( 1191): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1191): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1191): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1191): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/GpsLocationProvider(  762): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/PersonaManagerService(  762): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  762): MSG_ACTION_SCREEN_OFF called
,D/NativeNfcManager( 1413): power state=2
D/BrcmNfcJni( 1413): PowerSwitch::com_android_nfc_NativeNfcManager_doSetPowerMode: mode=0x2; screen off
,D/StatusBar.NetworkController( 1191): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/NfcService( 1413): call the applyRouting
,D/STATUSBAR-PhoneStatusBar( 1191):      ACTION_SCREEN_OFF is finished!!!! 
,D/accuweather( 1848): [Accuweather J]>>> SWW:81 [0:0] =============== BR act = androidintentactionSCREEN_OFF
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  762): getTasks: caller 10102 does not hold GET_TASKS; limiting output
,W/ActivityManager(  762): getTasks: caller 10102 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  762): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  (  762): SIOP:: AP = 310, PST = 312, CUR = 450
,I/BatteryStatsDumper(  762): In refreshStats isReason Screen ON/OFF: true
,D/NetworkStatsFactory(  762): UpdateStatsForKnox
,I/qdhwcomposer(  266): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  266): hwc_blank: Done blanking display: 0
D/SurfaceControl(  762): Excessive delay in setPowerMode(): 262ms
,D/NetworkStatsFactory(  762): UpdateStatsForKnox
,D/PowerManagerService(  762): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  762): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  762): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL(  762): Got set_interactive hint
,I/PowerManagerService(  762): [PWL] Off : 0s ago
,I/PowerManagerService(  762): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  762): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  762): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=762, ws=null) (elapsedTime=86)
D/PowerManagerService(  762): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 293ms
,D/LightsService(  762): [SvcLED]  onSensorChanged::light value = 32,
E/LightSensor(  762): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  762): unregisterListener ::   
D/lights  (  762): led_pattern : 5 +
D/lights  (  762): led_pattern : 5 -
D/LightsService(  762): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/BatteryStatsDumper(  762): Screen bin #0: time=17 power=1.0766666666666668E-4
I/BatteryStatsDumper(  762): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper(  762): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper(  762): Screen bin #3: time=12093 power=0.536123
I/BatteryStatsDumper(  762): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper(  762): Previous Battery Level: 100 Current Level: 100 Delta: 0
,I/BatteryStatsDumper(  762): Writing to database completed,
,E/SMD     (  304): DCD ON
,I/Atfwd_Sendcmd(  354): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  354): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,V/AlarmManager(  762): waitForAlarm result :4
,D/KeyguardViewMediator( 1191): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1191): isKioskContainerExistOnDevice
,D/KeyguardViewMediator( 1191): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  762): [PWL] Off : 5s ago
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,V/AlarmManager(  762): waitForAlarm result :8
,V/AlarmManager(  762): waitForAlarm result :8
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 310, PST = 311, CUR = 450
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,V/AlarmManager(  762): waitForAlarm result :8
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/PowerManagerService(  762): [PWL] Off : 15s ago
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/Watchdog(  762): !@Sync 7
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 309, CUR = 450
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  304): DCD ON
,V/AlarmManager(  762): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): stay LED for fully charged
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,I/BackgroundCompactionService(  762): onStart. jobID=801
,I/BackgroundCompactionService(  762): onStart done. jobID=801
,I/BackgroundCompactionService(  762): Execute BGCompaction (type1). (1 times)
,I/BackgroundCompactionService(  762): compact_memory command done
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PowerManagerService(  762): [PWL] Off : 30s ago
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 308, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 307, CUR = 450
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  304): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  762): !@Sync 8
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 50s ago
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 306, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 305, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,V/AlarmManager(  762): waitForAlarm result :8
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 304, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 75s ago
,E/Watchdog(  762): !@Sync 9
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 303, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  304): DCD ON
,I/ClearcutLoggerApiImpl( 1886): disconnect managed GoogleApiClient
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 302, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 301, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService(  762): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  762): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  762): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  762): initializing...
,I/TLC_TIMA_PKM_initialize(  762): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  762): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  762): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  762): process = tima_pkm, process_strlen = 8,
I/TZ: qc_tlc_communication(  762): aligned max_sendmsg_size = 262208 = 0x40040,
,I/TZ: qc_tlc_communication(  762): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  762): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  762): QSEECom_get_handle sb_length = 0x80080,
,D/QSEECOMAPI: (  762): App is not loaded in QSEE,
,D/QSEECOMAPI: (  762): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  762): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  762): Trustlet response is completed
,E/SMD     (  304): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  762): [PWL] Off : 105s ago
,I/PowerManagerService(  762): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  762): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  762): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=762, ws=null) (elapsedTime=2366),
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  762): !@Sync 10
,D/TimaService(  762): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  304): DCD ON
,I/Atfwd_Sendcmd(  354): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  354): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,V/AlarmManager(  762): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 300, CUR = 450
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,V/AlarmManager(  762): waitForAlarm result :4
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0,
,I/ActivityManager(  762): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7595 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7595): MountEmulatedStorage()
,E/Zygote  ( 7595): v2
I/libpersona( 7595): KNOX_SDCARD checking this for 10096
I/libpersona( 7595): KNOX_SDCARD not a persona
,I/SELinux ( 7595): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7595): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7595): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7595): TimaSignature is unavailable
,D/ActivityThread( 7595): Added TimaKeyStore provider
,D/ResourcesManager( 7595): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  762): Killing 6130:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,V/AlarmManager(  762): waitForAlarm result :8
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 300, CUR = 450
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 11
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  762): [PWL] Off : 140s ago
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 300, CUR = 450
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 299, CUR = 450
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 298, CUR = 450
,E/SMD     (  304): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  762): !@Sync 12
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 297, CUR = 450
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 180s ago
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 296, CUR = 450
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 13
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 293, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 292, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  762): [PWL] Off : 225s ago
,E/Watchdog(  762): !@Sync 14
,E/SMD     (  304): DCD ON
,I/Atfwd_Sendcmd(  354): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  354): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 291, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 15
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/bootchecker(  350): bootchecker wake up!!
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/PowerManagerService(  762): [PWL] Off : 275s ago
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  762): !@Sync 16
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,V/AlarmManager(  762): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 17
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,I/ServiceManager(  354): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  354): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 330s ago
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  762): !@Sync 18
,E/SMD     (  304): DCD ON
,I/Atfwd_Sendcmd(  354): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  354): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,V/AlarmManager(  762): waitForAlarm result :8
,E/SMD     (  304): DCD ON
,I/Atfwd_Daemon(  354): Stop the daemon....
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  304): DCD ON
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/Watchdog(  762): !@Sync 19
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 390s ago
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/TimaService(  762): TIMA: TimaService scheduler is intialized. 
D/TimaService(  762): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  762): TimaServiceHandler.handleMessage what =1,
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  762): !@Sync 20
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/Watchdog(  762): !@Sync 21
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 455s ago
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/Watchdog(  762): !@Sync 22
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,E/SMD     (  304): DCD ON
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/Watchdog(  762): !@Sync 23
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  762): [PWL] Off : 525s ago
,E/Watchdog(  762): !@Sync 24
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  762): !@Sync 25
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/Watchdog(  762): !@Sync 26
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 600s ago
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/Watchdog(  762): !@Sync 27
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/Watchdog(  762): !@Sync 28
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 29
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 680s ago
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  762): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/TimaService(  762): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  762): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  762): TimaServiceHandler.handleMessage what =1
,E/SMD     (  304): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  762): !@Sync 30
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/art     (  762): Background sticky concurrent mark sweep GC freed 122086(9MB) AllocSpace objects, 258(4MB) LOS objects, 17% free, 38MB/46MB, paused 2.001ms total 124.194ms
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 31
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 765s ago
,E/Watchdog(  762): !@Sync 32
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 33
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,V/AlarmManager(  762): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): stay LED for fully charged
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/LightsService(  762): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  762): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SensorManager(  762): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,E/SMD     (  304): DCD ON
,I/EventLogService( 2207): Aggregate from 1457076318095 (log), 1457076318095 (data)
,D/LightsService(  762): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  762): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  762): unregisterListener ::   
,D/lights  (  762): led_pattern : 5 +
,D/lights  (  762): led_pattern : 5 -
,D/LightsService(  762): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 34
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,V/AlarmManager(  762): waitForAlarm result :8
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 855s ago
,E/Watchdog(  762): !@Sync 35
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 36
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 37
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 38
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 950s ago
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 39
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/TimaService(  762): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  762): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  762): TimaServiceHandler.handleMessage what =1
,E/SMD     (  304): DCD ON
,I/UsageStatsService(  762): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  762): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  762): Updating Usage Statistics in DB @ 1457078313618
,I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
,W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
,W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
,W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
,W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
,W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
,W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  762): Done Updating Usage Statistics in DB @ 1457078313828
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  762): !@Sync 40
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 281, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 282, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 41
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): stay LED for fully charged
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 1050s ago
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 42
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/Watchdog(  762): !@Sync 43
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 7675): 
D/AndroidRuntime( 7675): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7675): CheckJNI is OFF
D/AndroidRuntime( 7675): readGMSProperty: start
D/AndroidRuntime( 7675): readGMSProperty: already setted!!
D/AndroidRuntime( 7675): readGMSProperty: end
D/AndroidRuntime( 7675): addProductProperty: start
E/AffinityControl( 7675): AffinityControl: registerfunction enter
D/AndroidRuntime( 7675): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  762): START PACKAGE DELETE: observer{331613861}
D/PackageManager(  762): pkg{<packageName>}
D/PackageManager(  762): user{0}
D/PackageManager(  762): caller{2000}
D/PackageManager(  762): flags{3}
D/PersonaManagerService(  762): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  762): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  762): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  762): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  762): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  762): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  762): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  762): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  762): getApplicationUninstallationEnabled
D/ApplicationPolicy(  762): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  762): !@killApplicatoin: 10079, uninstall pkg
I/ActivityManager(  762): Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
I/ActivityManager(  762): Killing 7432:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest
E/SMD     (  304): DCD ON
I/WindowState(  762): WIN DEATH: Window{2d1b91e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  266): id=13 Removed NainActivit (5/8)
I/SurfaceFlinger(  266): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger(  266): id=13 Removed NainActivit (-2/8)
D/PointerIcon(  762): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  762): setMouseCustomIcon IconType is same.101
D/PointerIcon(  762): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  762): setHoveringSpenCustomIcon IconType is same.1
W/PackageSettings(  762): Skipping PackageSetting{16319241 com.example.hello/10078} due to missing metadata
I/ActivityManager(  762):   Force finishing activity ActivityRecord{3810d40a u0 com.test.thalitest/.MainActivity t9}
W/ActivityManager(  762): mDVFSHelper.acquire()
W/ActivityManager(  762): Spurious death for ProcessRecord{2d1b4a7a 7432:com.test.thalitest/u0a79}, curProc for 7432: null
I/ActivityManager(  762): Force stopping com.test.thalitest appid=10079 user=0: pkg removed
I/ActivityManager(  762):   Force finishing activity ActivityRecord{3810d40a u0 com.test.thalitest/.MainActivity t9 f}
W/ActivityManager(  762): Duplicate finish request for ActivityRecord{3810d40a u0 com.test.thalitest/.MainActivity t9 f}
I/art     ( 6953): Explicit concurrent mark sweep GC freed 2170(128KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 448us total 36.044ms
I/art     ( 4615): Explicit concurrent mark sweep GC freed 5587(309KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 15MB/26MB, paused 478us total 37.282ms
I/art     ( 6605): Explicit concurrent mark sweep GC freed 16218(860KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 2.141ms total 128.513ms
I/art     ( 1596): Explicit concurrent mark sweep GC freed 44211(2MB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/26MB, paused 595us total 147.666ms
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3652): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/DBG_DM  ( 3652): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 0
W/GeofencerStateMachine( 1886): Ignoring removeGeofence because network location is disabled.
I/InputReader(  762): Reconfiguring input devices.  changes=0x00000010
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/SamsungIME( 1683): mOCRHelper is null
I/DBG_DM  ( 3652): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/DBG_DM  ( 3652): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3652): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 0
I/DBG_DM  ( 3652): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/ActivityManager(  762): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7702 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 7702): MountEmulatedStorage()
E/Zygote  ( 7702): v2
I/libpersona( 7702): KNOX_SDCARD checking this for 10023
I/libpersona( 7702): KNOX_SDCARD not a persona
D/RegisteredServicesCache( 1413): empty dynamic service
I/art     ( 2207): Explicit concurrent mark sweep GC freed 12481(727KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 22MB/30MB, paused 3.811ms total 209.255ms
I/art     ( 7026): Explicit concurrent mark sweep GC freed 7386(454KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 580us total 117.132ms
I/DBG_DM  ( 3652): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/SELinux ( 7702): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7702): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7702): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 1437): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
I/DBG_DM  ( 3652): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
W/ResourcesManager( 1437): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1437): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1437): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
D/SecContentProvider2(  762): uri = 14 selection = getSealedState
D/SecContentProvider2(  762): mCursor = null
W/ResourcesManager( 1437): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1437): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1437): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ApplicationPolicy(  762): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  762): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/TimaKeyStoreProvider( 7702): TimaSignature is unavailable
D/ActivityThread( 7702): Added TimaKeyStore provider
D/ResourcesManager( 1437): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
I/art     (  762): Explicit concurrent mark sweep GC freed 82723(6MB) AllocSpace objects, 126(2017KB) LOS objects, 30% free, 37MB/53MB, paused 2.173ms total 217.658ms
W/ResourcesManager( 1437): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1437): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/DBG_DM  ( 3652): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 0
D/ResourcesManager(  762): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  762): WaitForGcToComplete blocked for 81.378ms for cause Explicit
I/DBG_DM  ( 3652): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/DBG_DM  ( 3652): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3652): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3652): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3652): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager(  762): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  762): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  762): postActiveUserChange, showWhenLocked: false
I/SurfaceFlinger(  266): id=15 createSurf (1080x1920),2 flag=404, YUIInstallC
D/ResourcesManager( 7702): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/StatusBarManagerService(  762): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/PointerIcon(  762): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  762): setMouseCustomIcon IconType is same.101
D/PointerIcon(  762): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  762): setHoveringSpenCustomIcon IconType is same.1
I/DBG_DM  ( 3652): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
D/InputMethodManagerService(  762): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  762): Got RemoteException sending setActive(false) notification to pid 7432 uid 10079
W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/SecContentProvider2(  762): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  762): mCursor = null
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
V/ActivityThread( 3652): updateVisibility : ActivityRecord{21da9004 token=android.os.BinderProxy@2e38a29 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/Timeline( 3652): Timeline: Activity_idle id: android.os.BinderProxy@2e38a29 time:1334176
W/ActivityManager(  762): mDVFSHelper.release()
I/Timeline(  762): Timeline: Activity_windows_visible id: ActivityRecord{23ea35cd u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t8} time:1334196
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/KLMS-2.4.511: ( 7702): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/KLMS-2.4.511: ( 7702): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1457078431181
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/KLMS-2.4.511: ( 7702): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 7702): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/RCPManagerService(  762): PackageReceiver onReceive()
I/HarmonyEASService(  762): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  762): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  762): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  762): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  762): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  762): uID is 10079
V/EnterpriseBillingPolicy(  762): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  762): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  762): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  762): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  762): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  762): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  762): getBillingProfileForVpnEngine - end - null
E/Zygote  ( 7725): MountEmulatedStorage()
E/Zygote  ( 7725): v2
I/libpersona( 7725): KNOX_SDCARD checking this for 10116
I/libpersona( 7725): KNOX_SDCARD not a persona
I/ActivityManager(  762): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7725 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  762): Killing 6038:com.google.android.music:main/u0a144 (adj 15): bgCount ##41
D/SSRM:aV (  762): MSG_TYPE_APP_REMOVED::
D/TaskPersister(  762): removeObsoleteFile: deleting file=9_task.xml
D/KnoxTimeoutHandler(  762): handleActiveUserChange for user 0
D/TaskPersister(  762): removeObsoleteFile: deleting file=8_task.xml
D/PersonaManagerService(  762): getPersonasForUser(): returning null!
V/AlarmManagerEXT(  762): com.test.thalitest(10079) is removed.
I/art     (  762): Explicit concurrent mark sweep GC freed 11746(584KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 37MB/53MB, paused 1.794ms total 248.836ms
I/SELinux ( 7725): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7725): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7725): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBar( 1191): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1191): isKioskContainerExistOnDevice
D/PersonaManager( 1191): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1191): Icon Only
I/StatusBar( 1191): Icon Only
D/PanelView( 1191): There is/are notification(s) 
D/PanelView( 1191): There is/are notification(s) 
D/TimaKeyStoreProvider( 7725): TimaSignature is unavailable
D/ActivityThread( 7725): Added TimaKeyStore provider
D/ResourcesManager( 7725): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/elm:14491( 7725): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 7725): ELMEngine.ELMEngine( context ).
D/elm:14491( 7725): MDMBridge.setEnterpriseBridge()
D/elm:14491( 7725): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/AASAservice-UpdateReceiver( 3876): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 3876): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3876): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
W/System.err( 3876): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 3876): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
W/System.err( 3876): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
W/System.err( 3876): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 3876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3876): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3876): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
W/System.err( 3876): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3876): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3876): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
W/System.err( 3876): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/elm:14491( 7725): ElmAgentService : onCreate()
D/elm:14491( 7725): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6704): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6704): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6704): onReceive() : package name is not s health. Return !!!
D/elm:14491( 7725): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 7725): MDMBridge.getInstance()
D/elm:14491( 7725): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 7725): MDMBridge.getAllLicenseInfoFromSDK()
I/PCWCLIENTTRACE_PushUtil( 6721): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6721): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6721): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6721): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/elm:14491( 7725): ElmAgentService : onDestroy().
D/PackageManager(  762): delete codoeFile: 
D/AASAuninstall(  762): userId = 0, info.removedAppID = -1, info.uid = 10079, packageName = com.test.thalitest
I/AASA_removePackage(  762): UID=10079 Target=com.test.thalitest
D/PackageManager(  762): result of delete: 1{331613861}
D/AndroidRuntime( 7675): Shutting down VM
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7743): MountEmulatedStorage()
E/Zygote  ( 7743): v2
I/libpersona( 7743): KNOX_SDCARD checking this for 10043
I/libpersona( 7743): KNOX_SDCARD not a persona
I/ActivityManager(  762): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7743 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7743): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7743): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7743): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager(  762): Killing 5490:com.google.android.talk/u0a131 (adj 15): bgCount ##41
D/TimaKeyStoreProvider( 7743): TimaSignature is unavailable
D/ActivityThread( 7743): Added TimaKeyStore provider
D/ResourcesManager( 7743): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService( 7743): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7743): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 7743): PushLog.txt file is not deleted.
D/SPPClientService( 7743): PushLog.txt file is not deleted.
D/SPPClientService( 7743): ============PushLog. stop!
I/SA      ( 6790): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOI6 PSS = 5.701607447389803  ]
I/SA      ( 6790): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager(  762): Killing 6669:com.google.android.partnersetup/u0a19 (adj 13): bgCount ##41
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7761): MountEmulatedStorage()
E/Zygote  ( 7761): v2
I/libpersona( 7761): KNOX_SDCARD checking this for 10024
I/libpersona( 7761): KNOX_SDCARD not a persona
I/ActivityManager(  762): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7761 uid=10024 gids={50024, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
I/SELinux ( 7761): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7761): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7761): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/Mms/FreeMessageReceiver( 6811): onReceive, action : android.intent.action.PACKAGE_REMOVED
I/TactileAssist(  762): enable value -1
I/TactileAssist(  762): internal enable value -1
I/TactileAssist(  762): intensity value -1
I/TactileAssist(  762): saveAppList value true
I/TactileAssist(  762): List of disabled apps :
D/TimaKeyStoreProvider( 7761): TimaSignature is unavailable
D/ActivityThread( 7761): Added TimaKeyStore provider
D/Mms/FreeMessageReceiverService( 6811): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 6811): onHandleIntent: ACTION_PACKAGE_REMOVED
D/SettingsProvider(  762): name = reading_mode_app_list
D/Compatibility( 6855): onReceive() it will make start service
D/ResourcesManager( 7761): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
D/Compatibility( 6855): onHandleIntent()
D/Compatibility( 6855): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10079, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 6855): found: 2
D/Compatibility( 6855): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6855): skipping ResolveInfo{3cca2373 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6855): considering ResolveInfo{16d05230 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6855): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6855): enabling receiver ResolveInfo{30ddcea9 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/EventHub(  762): Removing device '/dev/input/event6' due to inotify event
D/Compatibility( 6855): enabling receiver ResolveInfo{231eac2e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/UpdateIcingCorporaServi( 1596): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 6855): enabling receiver ResolveInfo{261983cf com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6855): enabling receiver ResolveInfo{20615c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/EventHub(  762): Removing device '/dev/input/event7' due to inotify event
E/SharedPreferencesImpl( 6855): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
E/SharedPreferencesImpl( 6855): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
D/Compatibility( 6855): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/SQLiteLog( 6605): (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteLog( 6605): (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6605): (14) cannot open file at line 32509 of [b3bb660af9]
E/SQLiteLog( 6605): (14) os_unix.c:32509: (2) open(/data/data/com.samsung.android.sm/databases/history.db) - 
E/SQLiteDatabase( 6605): Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
E/SQLiteDatabase( 6605): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6605): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6605): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6605): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6605): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6605): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6605): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6605): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6605): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6605): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6605): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6605): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6605): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6605): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6605): 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
E/SQLiteDatabase( 6605): 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
E/SQLiteDatabase( 6605): 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
E/SQLiteDatabase( 6605): 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
E/SQLiteDatabase( 6605): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
E/SQLiteDatabase( 6605): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 6605): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 6605): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6605): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6605): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/SQLiteDatabase( 6605): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6605): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6605): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/SQLiteDatabase( 6605): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/AndroidRuntime( 6605): Shutting down VM
E/AndroidRuntime( 6605): FATAL EXCEPTION: main
E/AndroidRuntime( 6605): Process: com.samsung.android.sm, PID: 6605
E/AndroidRuntime( 6605): java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/AndroidRuntime( 6605): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2996)
E/AndroidRuntime( 6605): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/AndroidRuntime( 6605): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/AndroidRuntime( 6605): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6605): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6605): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/AndroidRuntime( 6605): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6605): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6605): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/AndroidRuntime( 6605): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
E/AndroidRuntime( 6605): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/AndroidRuntime( 6605): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6605): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6605): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6605): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6605): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6605): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6605): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime( 6605): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime( 6605): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6605): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/AndroidRuntime( 6605): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6605): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6605): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6605): 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
E/AndroidRuntime( 6605): 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
E/AndroidRuntime( 6605): 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
E/AndroidRuntime( 6605): 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
E/AndroidRuntime( 6605): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
E/AndroidRuntime( 6605): 	... 9 more
V/ApplicationPolicy(  762): isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
E/AndroidRuntime(  762): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  762): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  762): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  762): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  762): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  762): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  762): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  762): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:15135)
E/AndroidRuntime(  762): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  762): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  762): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  762): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  762): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  762): 	... 5 more
I/Process ( 6605): Sending signal. PID: 6605 SIG: 9
I/EventHub(  762): Removing device '/dev/input/event8' due to inotify event
E/android.os.Debug(  762): ro.product_ship = true
E/android.os.Debug(  762): ro.debug_level = 0x4f4c
E/AndroidRuntime(  762): Error reporting crash
E/AndroidRuntime(  762): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  762): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  762): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  762): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  762): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  762): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  762): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:15135)
E/AndroidRuntime(  762): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15142)
E/AndroidRuntime(  762): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14730)
E/AndroidRuntime(  762): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14714)
E/AndroidRuntime(  762): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime(  762): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime(  762): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/AndroidRuntime(  762): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  762): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  762): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  762): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  762): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  762): 	... 11 more
I/Process (  762): Sending signal. PID: 762 SIG: 9
E/SQLiteLog( 7761): (28) failed to open "/data/user/0/com.sec.android.provider.logsprovider/databases/logs.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteLog( 7761): (28) failed to open "/data/user/0/com.sec.android.provider.logsprovider/databases/logs.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 7761): (14) cannot open file at line 32509 of [b3bb660af9]
E/SQLiteLog( 7761): (14) os_unix.c:32509: (2) open(/data/user/0/com.sec.android.provider.logsprovider/databases/logs.db) - 
E/SQLiteDatabase( 7761): Failed to open database '/data/user/0/com.sec.android.provider.logsprovider/databases/logs.db'.
E/SQLiteDatabase( 7761): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 7761): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7761): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7761): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7761): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7761): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7761): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7761): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7761): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7761): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7761): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7761): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7761): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7761): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7761): 	at com.sec.android.provider.logsprovider.LogsProvider.onCreate(LogsProvider.java:1864)
E/SQLiteDatabase( 7761): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1716)
E/SQLiteDatabase( 7761): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1685)
E/SQLiteDatabase( 7761): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5555)
E/SQLiteDatabase( 7761): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
E/SQLiteDatabase( 7761): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
E/SQLiteDatabase( 7761): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/SQLiteDatabase( 7761): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/SQLiteDatabase( 7761): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7761): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7761): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/SQLiteDatabase( 7761): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7761): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7761): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/SQLiteDatabase( 7761): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)

```
