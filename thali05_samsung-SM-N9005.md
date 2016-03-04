#### Test 61699762a45f11c_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 340, PST = 394, CUR = 450
--------- beginning of main
D/AndroidRuntime( 7313): 
D/AndroidRuntime( 7313): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7313): CheckJNI is OFF
D/AndroidRuntime( 7313): readGMSProperty: start
D/AndroidRuntime( 7313): readGMSProperty: already setted!!
D/AndroidRuntime( 7313): readGMSProperty: end
D/AndroidRuntime( 7313): addProductProperty: start
E/AffinityControl( 7313): AffinityControl: registerfunction enter
D/AndroidRuntime( 7313): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  738): inState():  stateMachine is null !!
I/PersonaManagerService(  738): PersonaId don't exist
I/ActivityManager(  738): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  738): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/ResourcesManager(  738): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/ActivityManager(  738): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  738): mDVFSHelper.acquire()
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7329): MountEmulatedStorage()
E/Zygote  ( 7329): v2
I/libpersona( 7329): KNOX_SDCARD checking this for 10079
I/libpersona( 7329): KNOX_SDCARD not a persona
I/ActivityManager(  738): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7329 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7329): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7329): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7329): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon(  738): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  738): setMouseCustomIcon IconType is same.101
D/PointerIcon(  738): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  738): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7313): Shutting down VM
W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 1
D/TimaKeyStoreProvider( 7329): TimaSignature is unavailable
D/ActivityThread( 7329): Added TimaKeyStore provider
V/ActivityManager(  738): Display changed displayId=0
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SurfaceFlinger(  267): id=10 Removed YUIInstallC (5/8)
I/SurfaceFlinger(  267): id=10 Removed YUIInstallC (-2/8)
D/ResourcesManager( 7329): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 3680): updateVisibility : ActivityRecord{3dd38b2 token=android.os.BinderProxy@144c2aab {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,I/WebViewFactory( 7329): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
D/ResourcesManager( 7329): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7329): Time to load native libraries: 4 ms (timestamps 624-628)
I/LibraryLoader( 7329): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7329): Binding Chromium to main looper Looper (main, tid 1) {1fcb726e}
,I/LibraryLoader( 7329): Expected native library version number "",actual native library version number ""
,I/chromium( 7329): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7329): Initializing chromium process, singleProcess=true
,W/art     ( 7329): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7329): ApplicationContext is null in ApplicationStatus
,W/chromium( 7329): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 7329): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 7329): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 7329): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7329): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7329): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7329): Local Branch: mybranch5813579
I/Adreno-EGL( 7329): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7329): Local Patches: NONE
I/Adreno-EGL( 7329): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/ActivityManager(  738): Activity pause timeout for ActivityRecord{13b13a31 u0 com.test.thalitest/.MainActivity t9}
,W/chromium( 7329): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/art     ( 7329): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7329): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7329): CordovaWebView is running on device made by: samsung
,W/art     ( 7329): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7329): Attempt to remove local handle scope entry from IRT, ignoring
,E/SMD     (  304): DCD ON
,D/Activity( 7329): performCreate Call secproduct feature valuefalse
D/Activity( 7329): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7329): Render dirty regions requested: true
,D/ActivityManager(  738): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  738): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  738): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler(  738): handleActiveUserChange for user 0
D/PersonaManagerService(  738): getPersonasForUser(): returning null!
,V/ActivityThread( 7329): updateVisibility : ActivityRecord{4ae26b8 token=android.os.BinderProxy@15f9832a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  267): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  738): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  738): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  738): setMouseCustomIcon IconType is same.101
D/PointerIcon(  738): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  738): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 7329): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7329): HWUI protection enabled for context ,  &this =0xa054b060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7329): Enabling debug mode 0
,D/InputMethodManagerService(  738): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  738): mDVFSHelper.release()
,I/Timeline(  738): Timeline: Activity_windows_visible id: ActivityRecord{13b13a31 u0 com.test.thalitest/.MainActivity t9} time:121284
,W/IInputConnectionWrapper( 7329): showStatusIcon on inactive InputConnection
I/Timeline( 7329): Timeline: Activity_idle id: android.os.BinderProxy@15f9832a time:121294
,W/BindingManager( 7329): Cannot call determinedVisibility() - never saw a connection for the pid: 7329
,D/JsMessageQueue( 7329): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7329): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358599680
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7329): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7329):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7329):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7329):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7329):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7329): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127aec01 added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39bac094 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7329): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7329): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7329): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 7329): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7329): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7329): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7329): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7329): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7329): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7329): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7329): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7329): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7329): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7329): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7329): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 7329): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7329): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7329): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a9473d added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ef61b32 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7329): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7329): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7329): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 7329): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7329): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7329): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7329): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7329): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7329): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7329): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7329): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7329): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7329): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7329): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7329): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/FactoryTest( 6494): Not factory mode
D/FactoryTest( 6494): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 6494): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6494): still no open session command from host, so toast
W/ContextImpl( 6494): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1583 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 6494): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.app.ContextImpl.startActivity:1584 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 
I/Timeline( 6494): Timeline: Activity_launch_request id:com.android.settings time:122521
E/PersonaManagerService(  738): inState():  stateMachine is null !!
I/PersonaManagerService(  738): PersonaId don't exist
I/ActivityManager(  738): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  738): isApplicationStateBlocked userId 0 pkgname com.android.settings
I/ActivityManager(  738): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
W/ActivityManager(  738): mDVFSHelper.acquire()
D/PointerIcon(  738): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  738): setMouseCustomIcon IconType is same.101
D/PointerIcon(  738): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  738): setHoveringSpenCustomIcon IconType is same.1
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/MTPRx   ( 6494): started activity for popup
D/ResourcesManager( 6494): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager( 6494): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6494): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6494): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6494): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6494): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6494): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/SettingsReceiverActivity( 6494): PREF_DONT_ASK_AGAIN : true
D/PointerIcon(  738): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  738): setMouseCustomIcon IconType is same.101
D/PointerIcon(  738): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/InputMethodManagerService(  738): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/PointerIcon(  738): setHoveringSpenCustomIcon IconType is same.1
W/InputMethodManagerService(  738): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@ab90477 attribute=null, token = android.os.BinderProxy@a62019e
D/SettingsReceiverActivity( 6494): dev.kiessupport is : TRUE
D/Activity( 6494): performCreate Call secproduct feature valuefalse
D/Activity( 6494): performCreate Call debug elastic valuetrue
D/ActivityManager(  738): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  738): postActiveUserChange for user 0
D/PersonaManagerService(  738): getPersonasForUser(): returning null!
I/KnoxTimeoutHandler(  738): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler(  738): handleActiveUserChange for user 0
D/JX-Cordova( 7329): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7329): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7329): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25bf0083 added. We now have 3 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ccd5200 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7329): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7329): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7329): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 7329): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7329): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7329): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7329): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7329): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7329): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7329): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7329): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7329): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7329): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7329): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7329): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/ActivityThread( 7329): updateVisibility : ActivityRecord{4ae26b8 token=android.os.BinderProxy@15f9832a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/Timeline( 7329): Timeline: Activity_idle id: android.os.BinderProxy@15f9832a time:122771
D/JX-Cordova( 7329): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7329): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7329): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e681a39 added. We now have 4 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b66b87e added. We now have 4 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7329): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7329): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7329): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7329): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 7329): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7329): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7329): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7329): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7329): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7329): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7329): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7329): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7329): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7329): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7329): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7329): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,W/ActivityManager(  738): mDVFSHelper.release()
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/chromium( 7329): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 7329): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,I/PowerManagerService(  738): [PWL] Off : 50s ago
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 330, PST = 383, CUR = 450
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  738): !@Sync 4
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 320, PST = 372, CUR = 450
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 320, PST = 361, CUR = 450
,E/SMD     (  304): DCD ON
,I/art     (  738): Explicit concurrent mark sweep GC freed 97989(5MB) AllocSpace objects, 34(801KB) LOS objects, 29% free, 37MB/53MB, paused 1.333ms total 157.351ms
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 75s ago
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 320, PST = 352, CUR = 450
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 5
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 310, PST = 341, CUR = 450
,I/ClearcutLoggerApiImpl( 1865): disconnect managed GoogleApiClient
,E/SMD     (  304): DCD ON
,V/AlarmManager(  738): waitForAlarm result :8
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 310, PST = 330, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 105s ago
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 310, PST = 325, CUR = 450
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  738): !@Sync 6
,E/SMD     (  304): DCD ON
,V/AlarmManager(  738): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1200): handleTimeUpdate
,D/KeyguardEffectViewController( 1200): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1200): *** don't update sliding image ***
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  (  738): SIOP:: AP = 310, PST = 321, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 310, PST = 318, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/Atfwd_Sendcmd(  365): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  365): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 140s ago
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,E/SMD     (  304): DCD ON
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/SSRM:n  (  738): SIOP:: AP = 310, PST = 315, CUR = 450
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/Watchdog(  738): !@Sync 7
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  (  738): SIOP:: AP = 310, PST = 313, CUR = 450
,E/SMD     (  304): DCD ON
,V/AlarmManager(  738): waitForAlarm result :8
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  (  738): SIOP:: AP = 310, PST = 312, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 310, CUR = 450
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  738): !@Sync 8
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 180s ago
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 308, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 307, CUR = 450
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 306, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 9
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 305, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 304, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 225s ago
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 303, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  738): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  738): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  738): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  738): initializing...
,I/TLC_TIMA_PKM_initialize(  738): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize(  738): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  738): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  738): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  738): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  738): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  738): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  738): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: (  738): App is not loaded in QSEE
,D/QSEECOMAPI: (  738): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  738): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  738): Trustlet response is completed
,E/Watchdog(  738): !@Sync 10
,E/SMD     (  304): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  738): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  738): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  738): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  738): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 302, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/Atfwd_Sendcmd(  365): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  365): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 301, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,V/AlarmManager(  738): waitForAlarm result :4
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ActivityManager(  738): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7432 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1200): handleTimeUpdate
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 7432): MountEmulatedStorage()
,E/Zygote  ( 7432): v2
,I/libpersona( 7432): KNOX_SDCARD checking this for 10096
I/libpersona( 7432): KNOX_SDCARD not a persona
,D/KeyguardEffectViewController( 1200): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1200): *** don't update sliding image ***
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,I/SELinux ( 7432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7432): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7432): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 7432): TimaSignature is unavailable
,D/ActivityThread( 7432): Added TimaKeyStore provider
,D/ResourcesManager( 7432): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  738): Killing 6177:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 300, CUR = 450,
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 11
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  738): Plugged
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 300, CUR = 450
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,V/AlarmManager(  738): waitForAlarm result :8
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/PowerManagerService(  738): [PWL] Off : 275s ago
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  738): !@Sync 12
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 4
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 13
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 330s ago
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 299, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 298, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  738): !@Sync 14
,E/SMD     (  304): DCD ON
,I/Atfwd_Sendcmd(  365): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  365): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryService(  738): stay LED for fully charged
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 297, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 296, CUR = 450
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 295, CUR = 450
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 15
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 390s ago
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/bootchecker(  358): bootchecker wake up!!
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  738): !@Sync 16
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,I/MotionRecognitionService(  738): Plugged
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 17
,E/SMD     (  304): DCD ON
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,V/AlarmManager(  738): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1200): handleTimeUpdate
,D/KeyguardEffectViewController( 1200): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1200): *** don't update sliding image ***
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  365): Waiting for service AtCmdFwd...
,I/PowerManagerService(  738): [PWL] Off : 455s ago
,E/SMD     (  304): DCD ON
,W/Atfwd_Sendcmd(  365): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  738): !@Sync 18
,E/SMD     (  304): DCD ON
,I/Atfwd_Sendcmd(  365): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  365): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,I/Atfwd_Daemon(  365): Stop the daemon....
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 19
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,V/AlarmManager(  738): waitForAlarm result :8
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 525s ago
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  738): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  738): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  738): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  738): !@Sync 20
,E/SMD     (  304): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  738): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  738): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  738): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  738): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 291, CUR = 450
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 21
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 291, CUR = 450
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 22
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 600s ago
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 291, CUR = 450
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  738): Plugged
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 291, CUR = 450
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 23
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 291, CUR = 450
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 24
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 680s ago
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 25
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,V/AlarmManager(  738): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1200): handleTimeUpdate
,D/LightsService(  738): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/KeyguardEffectViewController( 1200): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1200): *** don't update sliding image ***
,E/LightSensor(  738): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SensorManager(  738): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2222): Aggregate from 1457091068550 (log), 1457091068550 (data)
,E/Watchdog(  738): !@Sync 26
,D/LightsService(  738): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  738): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  738): unregisterListener ::   
,D/LightsService(  738): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  304): DCD ON,
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 27
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,V/AlarmManager(  738): waitForAlarm result :8
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,I/PowerManagerService(  738): [PWL] Off : 765s ago
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 28
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 29
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,D/TimaService(  738): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  738): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  738): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  738): !@Sync 30
,E/SMD     (  304): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  738): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  738): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  738): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  738): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  738): stay LED for fully charged
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  738): Plugged
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 855s ago
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 31
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  738): Plugged
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 32
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate,
I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 33
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  738): stay LED for fully charged
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 950s ago
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  738): Plugged
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 34
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 35
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,V/AlarmManager(  738): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1200): handleTimeUpdate
,D/KeyguardEffectViewController( 1200): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1200): *** don't update sliding image ***
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  738): waitForAlarm result :8
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 36
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 37
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 1050s ago
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/Watchdog(  738): !@Sync 38
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryService(  738): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/Watchdog(  738): !@Sync 39
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,I/UsageStatsService(  738): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  738): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  738): Updating Usage Statistics in DB @ 1457093602880
,I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
,W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
,W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
,W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): ,	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
,W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145),
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350),
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145),
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134),
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): ,	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/TimaService(  738): TIMA: TimaService scheduler is intialized. 
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
D/TimaService(  738): TIMA: checkEvent, operation: 50000 subject: 10000
W/System.err(  738): ,	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
,D/TimaService(  738): TimaServiceHandler.handleMessage what =1
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): ,	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	,at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
,W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  738): ,	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB,
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128),
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB,
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): ,	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  738): ,	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350),
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	,at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): ,	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128),
,W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145),
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
,W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
,W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  738): ::getAppControlDB: Exception to create DB
W/System.err(  738): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  738): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  738): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  738): Done Updating Usage Statistics in DB @ 1457093603057
,E/Watchdog(  738): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  738): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  738): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  738): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  738): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  738): Plugged
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,I/PowerManagerService(  738): [PWL] Off : 1155s ago
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/Watchdog(  738): !@Sync 41
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/Watchdog(  738): !@Sync 42
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/Watchdog(  738): !@Sync 43
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  304): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,E/Watchdog(  738): !@Sync 44
,E/SMD     (  304): DCD ON
,E/SMD     (  304): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 1265s ago
,E/SMD     (  304): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3170): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3170): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 290, PST = 290, CUR = 450
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  304): DCD ON
D/AndroidRuntime( 7540): 
D/AndroidRuntime( 7540): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7540): CheckJNI is OFF
D/AndroidRuntime( 7540): readGMSProperty: start
D/AndroidRuntime( 7540): readGMSProperty: already setted!!
D/AndroidRuntime( 7540): readGMSProperty: end
D/AndroidRuntime( 7540): addProductProperty: start
E/AffinityControl( 7540): AffinityControl: registerfunction enter
D/AndroidRuntime( 7540): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  738): START PACKAGE DELETE: observer{777714816}
D/PackageManager(  738): pkg{<packageName>}
D/PackageManager(  738): user{0}
D/PackageManager(  738): caller{2000}
D/PackageManager(  738): flags{3}
D/PersonaManagerService(  738): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  738): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  738): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  738): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  738): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  738): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  738): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  738): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  738): getApplicationUninstallationEnabled
D/ApplicationPolicy(  738): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  738): !@killApplicatoin: 10079, uninstall pkg
I/ActivityManager(  738): Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
I/ActivityManager(  738): Killing 7329:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest
W/PackageSettings(  738): Skipping PackageSetting{d40735f com.example.hello/10078} due to missing metadata
I/WindowState(  738): WIN DEATH: Window{266d047f u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  267): id=13 Removed NainActivit (5/8)
I/SurfaceFlinger(  267): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger(  267): id=13 Removed NainActivit (-2/8)
D/PointerIcon(  738): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  738): setMouseCustomIcon IconType is same.101
D/PointerIcon(  738): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  738): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager(  738):   Force finishing activity ActivityRecord{13b13a31 u0 com.test.thalitest/.MainActivity t9}
W/ActivityManager(  738): mDVFSHelper.acquire()
I/ActivityManager(  738): Force stopping com.test.thalitest appid=10079 user=0: pkg removed
I/ActivityManager(  738):   Force finishing activity ActivityRecord{13b13a31 u0 com.test.thalitest/.MainActivity t9 f}
W/ActivityManager(  738): Duplicate finish request for ActivityRecord{13b13a31 u0 com.test.thalitest/.MainActivity t9 f}
I/art     ( 1498): Explicit concurrent mark sweep GC freed 54100(2MB) AllocSpace objects, 0(0B) LOS objects, 25% free, 20MB/26MB, paused 640us total 75.302ms
I/art     ( 6118): Explicit concurrent mark sweep GC freed 34969(1922KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 15MB/26MB, paused 525us total 49.244ms
I/art     ( 7015): Explicit concurrent mark sweep GC freed 8157(487KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 524us total 99.872ms
W/ActivityManager(  738): Spurious death for ProcessRecord{acb2b9 7329:com.test.thalitest/u0a79}, curProc for 7329: null
I/DBG_DM  ( 3680): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
E/SamsungIME( 1741): mOCRHelper is null
I/DBG_DM  ( 3680): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 1445): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
W/GeofencerStateMachine( 1865): Ignoring removeGeofence because network location is disabled.
W/ResourcesManager( 1445): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/DBG_DM  ( 3680): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/InputReader(  738): Reconfiguring input devices.  changes=0x00000010
I/DBG_DM  ( 3680): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
W/ResourcesManager( 1445): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1445): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
I/DBG_DM  ( 3680): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 0
I/art     ( 6965): Explicit concurrent mark sweep GC freed 3752(195KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 442us total 160.764ms
I/DBG_DM  ( 3680): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
E/Zygote  ( 7568): MountEmulatedStorage()
E/Zygote  ( 7568): v2
I/libpersona( 7568): KNOX_SDCARD checking this for 10023
I/libpersona( 7568): KNOX_SDCARD not a persona
I/ActivityManager(  738): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7568 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
I/art     ( 6463): Explicit concurrent mark sweep GC freed 23193(1185KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 483us total 187.979ms
I/DBG_DM  ( 3680): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
W/ResourcesManager( 1445): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/art     ( 2222): Explicit concurrent mark sweep GC freed 12543(732KB) AllocSpace objects, 4(64KB) LOS objects, 25% free, 22MB/30MB, paused 880us total 222.122ms
I/SELinux ( 7568): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7568): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
D/RegisteredServicesCache( 1419): empty dynamic service
E/SELinux ( 7568): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 1445): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
I/DBG_DM  ( 3680): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
W/ResourcesManager( 1445): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/SecContentProvider2(  738): uri = 14 selection = getSealedState
D/SecContentProvider2(  738): mCursor = null
D/ApplicationPolicy(  738): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  738): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/TimaKeyStoreProvider( 7568): TimaSignature is unavailable
D/ActivityThread( 7568): Added TimaKeyStore provider
I/DBG_DM  ( 3680): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 0
I/DBG_DM  ( 3680): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 3680): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3680): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3680): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3680): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager(  738): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  738): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  738): postActiveUserChange, showWhenLocked: false
I/DBG_DM  ( 3680): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
I/SurfaceFlinger(  267): id=14 createSurf (1080x1920),2 flag=404, YUIInstallC
D/StatusBarManagerService(  738): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  738): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  738): setMouseCustomIcon IconType is same.101
D/PointerIcon(  738): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  738): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 3680): updateVisibility : ActivityRecord{3dd38b2 token=android.os.BinderProxy@144c2aab {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/InputMethodManagerService(  738): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  738): Got RemoteException sending setActive(false) notification to pid 7329 uid 10079
D/ResourcesManager( 7568): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/art     (  738): Explicit concurrent mark sweep GC freed 104614(10MB) AllocSpace objects, 367(5MB) LOS objects, 29% free, 37MB/53MB, paused 1.816ms total 273.064ms
D/ResourcesManager(  738): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  738): WaitForGcToComplete blocked for 153.905ms for cause Background
I/art     (  738): WaitForGcToComplete blocked for 230.708ms for cause Explicit
I/Timeline( 3680): Timeline: Activity_idle id: android.os.BinderProxy@144c2aab time:1349644
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/SecContentProvider2(  738): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  738): mCursor = null
I/KLMS-2.4.511: ( 7568): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 7568): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1457093735788
W/ActivityManager(  738): mDVFSHelper.release()
I/Timeline(  738): Timeline: Activity_windows_visible id: ActivityRecord{90a99e6 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t8} time:1349666
I/KLMS-2.4.511: ( 7568): MainReciver(): PACKAGE_REMOVED
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
I/KLMS-2.4.511: ( 7568): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/RCPManagerService(  738): PackageReceiver onReceive()
I/HarmonyEASService(  738): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  738): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  738): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy(  738): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService(  738): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  738): uID is 10079
V/EnterpriseBillingPolicy(  738): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  738): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  738): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  738): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  738): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  738): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  738): getBillingProfileForVpnEngine - end - null
E/Zygote  ( 7588): MountEmulatedStorage()
E/Zygote  ( 7588): v2
I/libpersona( 7588): KNOX_SDCARD checking this for 10116
I/libpersona( 7588): KNOX_SDCARD not a persona
I/ActivityManager(  738): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7588 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  738): Killing 6068:com.google.android.music:main/u0a144 (adj 15): bgCount ##41
D/KnoxTimeoutHandler(  738): handleActiveUserChange for user 0
D/SSRM:aV (  738): MSG_TYPE_APP_REMOVED::
D/PersonaManagerService(  738): getPersonasForUser(): returning null!
V/AlarmManagerEXT(  738): com.test.thalitest(10079) is removed.
D/TaskPersister(  738): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  738): removeObsoleteFile: deleting file=8_task.xml
I/SELinux ( 7588): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7588): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7588): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBar( 1200): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1200): isKioskContainerExistOnDevice
D/PersonaManager( 1200): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1200): Icon Only
I/StatusBar( 1200): Icon Only
D/PanelView( 1200): There is/are notification(s) 
D/PanelView( 1200): There is/are notification(s) 
D/TimaKeyStoreProvider( 7588): TimaSignature is unavailable
D/ActivityThread( 7588): Added TimaKeyStore provider
I/art     (  738): Explicit concurrent mark sweep GC freed 15359(897KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 37MB/53MB, paused 1.679ms total 257.043ms
D/ResourcesManager( 7588): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/elm:14491( 7588): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 7588): ELMEngine.ELMEngine( context ).
D/elm:14491( 7588): MDMBridge.setEnterpriseBridge()
D/elm:14491( 7588): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14491( 7588): ElmAgentService : onCreate()
D/elm:14491( 7588): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 7588): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 7588): MDMBridge.getInstance()
D/AASAservice-UpdateReceiver( 3824): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
D/elm:14491( 7588): MDMBridge.getAllLicenseInfoFromSDK()
W/System.err( 3824): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3824): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
W/System.err( 3824): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 3824): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
W/System.err( 3824): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
W/System.err( 3824): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
D/elm:14491( 7588): MDMBridge.getAllLicenseInfoFromSDK()
W/System.err( 3824): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3824): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3824): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
W/System.err( 3824): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3824): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3824): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
W/System.err( 3824): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6756): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6756): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6756): onReceive() : package name is not s health. Return !!!
D/elm:14491( 7588): ElmAgentService : onDestroy().
I/PCWCLIENTTRACE_PushUtil( 6774): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6774): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6774): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6774): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
D/PackageManager(  738): delete codoeFile: 
D/AASAuninstall(  738): userId = 0, info.removedAppID = -1, info.uid = 10079, packageName = com.test.thalitest
I/AASA_removePackage(  738): UID=10079 Target=com.test.thalitest
D/PackageManager(  738): result of delete: 1{777714816}
D/AndroidRuntime( 7540): Shutting down VM
E/Zygote  ( 7607): MountEmulatedStorage()
E/Zygote  ( 7607): v2
I/libpersona( 7607): KNOX_SDCARD checking this for 10043
I/libpersona( 7607): KNOX_SDCARD not a persona
I/ActivityManager(  738): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7607 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  738): Killing 5884:com.google.android.gm/u0a128 (adj 15): bgCount ##41
I/SELinux ( 7607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7607): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7607): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7607): TimaSignature is unavailable
D/ActivityThread( 7607): Added TimaKeyStore provider
D/ResourcesManager( 7607): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService( 7607): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7607): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 7607): PushLog.txt file is not deleted.
D/SPPClientService( 7607): PushLog.txt file is not deleted.
D/SPPClientService( 7607): ============PushLog. stop!
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/SA      ( 6830): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOI6 PSS = 5.701607447389803  ]
I/SA      ( 6830): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager(  738): Killing 6722:com.google.android.partnersetup/u0a19 (adj 13): bgCount ##41
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/EnterpriseDeviceManagerService(  738): Package has changed for user 0
D/EnterpriseDeviceManagerService(  738): Admin package name: com.google.android.gms
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
W/ResourcesManager(  738): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  738): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  738): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  738): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
E/Zygote  ( 7627): MountEmulatedStorage()
E/Zygote  ( 7627): v2
I/libpersona( 7627): KNOX_SDCARD checking this for 10024
I/libpersona( 7627): KNOX_SDCARD not a persona
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
I/ActivityManager(  738): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7627 uid=10024 gids={50024, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  738): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  738): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/EventHub(  738): Removing device '/dev/input/event6' due to inotify event
I/SELinux ( 7627): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
I/EventHub(  738): Removing device '/dev/input/event7' due to inotify event
E/SELinux ( 7627): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/EventHub(  738): Removing device '/dev/input/event8' due to inotify event
D/TimaKeyStoreProvider( 7627): TimaSignature is unavailable
D/ActivityThread( 7627): Added TimaKeyStore provider
D/Mms/FreeMessageReceiver( 6850): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/UsbSettingsManager(  738): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  738): onPackageRemoved : com.test.thalitest
I/EventHub(  738): Removing device '/dev/input/event9' due to inotify event
D/Mms/FreeMessageReceiverService( 6850): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 6850): onHandleIntent: ACTION_PACKAGE_REMOVED
D/ResourcesManager( 7627): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk

```
