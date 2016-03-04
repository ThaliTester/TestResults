#### Test 61432979f791f6f_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
V/AlarmManager(  920): waitForAlarm result :8
,--------- beginning of main
D/AndroidRuntime( 7178): 
D/AndroidRuntime( 7178): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7178): CheckJNI is OFF
D/AndroidRuntime( 7178): readGMSProperty: start
D/AndroidRuntime( 7178): readGMSProperty: already setted!!
D/AndroidRuntime( 7178): readGMSProperty: end
D/AndroidRuntime( 7178): addProductProperty: start
E/AffinityControl( 7178): AffinityControl: registerfunction enter
D/AndroidRuntime( 7178): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  920): inState():  stateMachine is null !!
I/PersonaManagerService(  920): PersonaId don't exist
I/ActivityManager(  920): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  920): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  920): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  920): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  920): mDVFSHelper.acquire()
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7193): MountEmulatedStorage()
E/Zygote  ( 7193): v2
I/libpersona( 7193): KNOX_SDCARD checking this for 10079
I/libpersona( 7193): KNOX_SDCARD not a persona
I/ActivityManager(  920): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7193 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PointerIcon(  920): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  920): setMouseCustomIcon IconType is same.101
D/PointerIcon(  920): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  920): setHoveringSpenCustomIcon IconType is same.1
I/art     (  348): Explicit concurrent mark sweep GC freed 8745(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 7.221ms total 22.495ms
I/SELinux ( 7193): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7193): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7193): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 268us total 9.467ms
D/AndroidRuntime( 7178): Shutting down VM
I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 261us total 10.893ms
D/TimaKeyStoreProvider( 7193): TimaSignature is unavailable
D/ActivityThread( 7193): Added TimaKeyStore provider
V/ActivityManager(  920): Display changed displayId=0
D/ConnectivityService(  920): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7193): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  266): id=10 Removed YUIInstallC (5/8)
I/SurfaceFlinger(  266): id=10 Removed YUIInstallC (-2/8)
V/ActivityThread( 3692): updateVisibility : ActivityRecord{2e902a00 token=android.os.BinderProxy@31894121 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
E/SMD     (  301): DCD ON
I/WebViewFactory( 7193): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
D/ResourcesManager( 7193): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7193): Time to load native libraries: 2 ms (timestamps 3175-3177)
I/LibraryLoader( 7193): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7193): Binding Chromium to main looper Looper (main, tid 1) {25dd781c}
I/LibraryLoader( 7193): Expected native library version number "",actual native library version number ""
I/chromium( 7193): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7193): Initializing chromium process, singleProcess=true
W/art     ( 7193): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7193): ApplicationContext is null in ApplicationStatus
,W/chromium( 7193): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 7193): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 7193): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 7193): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7193): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7193): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7193): Local Branch: mybranch5813579
I/Adreno-EGL( 7193): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7193): Local Patches: NONE
I/Adreno-EGL( 7193): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/chromium( 7193): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/art     ( 7193): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7193): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7193): CordovaWebView is running on device made by: samsung
,W/art     ( 7193): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 7193): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7193): performCreate Call secproduct feature valuefalse
,D/Activity( 7193): performCreate Call debug elastic valuetrue
,W/ActivityManager(  920): Activity pause timeout for ActivityRecord{9e2eef4 u0 com.test.thalitest/.MainActivity t9}
,D/OpenGLRenderer( 7193): Render dirty regions requested: true
,D/ActivityManager(  920): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler(  920): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  920): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler(  920): handleActiveUserChange for user 0
,D/PersonaManagerService(  920): getPersonasForUser(): returning null!
,V/ActivityThread( 7193): updateVisibility : ActivityRecord{249d5a76 token=android.os.BinderProxy@3d01f538 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  266): id=13 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  920): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  920): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  920): setMouseCustomIcon IconType is same.101
D/PointerIcon(  920): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
I/OpenGLRenderer( 7193): Initialized EGL, version 1.4
D/PointerIcon(  920): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 7193): HWUI protection enabled for context ,  &this =0xa074b060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7193): Enabling debug mode 0
,D/InputMethodManagerService(  920): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  920): mDVFSHelper.release()
I/Timeline(  920): Timeline: Activity_windows_visible id: ActivityRecord{9e2eef4 u0 com.test.thalitest/.MainActivity t9} time:103645
,W/IInputConnectionWrapper( 7193): showStatusIcon on inactive InputConnection
,I/Timeline( 7193): Timeline: Activity_idle id: android.os.BinderProxy@3d01f538 time:103652
,W/BindingManager( 7193): Cannot call determinedVisibility() - never saw a connection for the pid: 7193
,D/JsMessageQueue( 7193): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7193): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259435136
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7193): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7193):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7193):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7193):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7193):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7193): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a499d67 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17f315b2 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7193): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,W/System.err( 7193): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7193): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 7193): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7193): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7193): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7193): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7193): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
,W/System.err( 7193): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7193): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7193): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7193): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7193): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7193): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 7193): jxcore cordova android initializing
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7193): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7193): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cc8a903 added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@411080 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7193): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7193): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 7193): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
,W/System.err( 7193): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7193): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7193): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7193): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7193): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7193): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7193): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7193): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7193): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 7193): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7193): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SMD     (  301): DCD ON
,D/PackageManager(  920): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  920): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  920): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/RegisteredServicesCache( 1412): empty dynamic service
,D/AASAservice-UpdateReceiver( 3843): AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.sec.enterprise.knox.cloudmdm.smdms, uid = -1
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/SecContentProvider2(  920): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  920): mCursor = null
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/UpdateIcingCorporaServi( 1487): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/BackupManagerService(  920): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,E/Zygote  ( 7280): MountEmulatedStorage()
E/Zygote  ( 7280): v2
I/libpersona( 7280): KNOX_SDCARD checking this for 10088
I/libpersona( 7280): KNOX_SDCARD not a persona
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,I/ActivityManager(  920): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7280 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/UpdateIcingCorporaServi( 1487): UpdateCorporaTask done [took 77 ms] updated apps [took 77 ms] 
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 7280): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7280): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7280): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  920): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager(  920): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  920): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  920): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  920): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/TimaKeyStoreProvider( 7280): TimaSignature is unavailable
,D/ActivityThread( 7280): Added TimaKeyStore provider
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
D/ResourcesManager( 7280): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/FileShare-Server( 7280): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7297): MountEmulatedStorage()
E/Zygote  ( 7297): v2
I/libpersona( 7297): KNOX_SDCARD checking this for 1000
I/libpersona( 7297): KNOX_SDCARD not a persona
,I/ActivityManager(  920): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7297 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  920): Killing 6016:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7297): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7297): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7297): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7297): TimaSignature is unavailable
,D/ActivityThread( 7297): Added TimaKeyStore provider
,D/ResourcesManager( 7297): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7297): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7312): MountEmulatedStorage()
E/Zygote  ( 7312): v2
I/libpersona( 7312): KNOX_SDCARD checking this for 1000
I/libpersona( 7312): KNOX_SDCARD not a persona
,I/SELinux ( 7312): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  920): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=7312 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7312): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
I/ActivityManager(  920): Killing 6496:flipboard.app/u0a125 (adj 15): bgCount ##41
E/SELinux ( 7312): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7312): TimaSignature is unavailable
D/ActivityThread( 7312): Added TimaKeyStore provider
,D/ResourcesManager( 7312): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,D/ShortcutReceiver( 7312):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  920): Killing 5851:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,D/PackageBroadcastService( 2242): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,I/Icing   ( 2242): Indexing F944DC6DBF38E5B5A54FB3560A7505412CF0FFB9 from com.google.android.gms
,I/Icing   ( 2242): Indexing done F944DC6DBF38E5B5A54FB3560A7505412CF0FFB9
,E/Watchdog(  920): !@Sync 3
,I/chromium( 7193): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 7193): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,E/SMD     (  301): DCD ON
,V/AlarmManager(  920): waitForAlarm result :4
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  920): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT(  920): <AppSync3 Whitelist>
,V/AlarmManagerEXT(  920): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1200): handleTimeUpdate
,D/KeyguardEffectViewController( 1200): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1200): *** don't update sliding image ***
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/PowerManagerService(  920): [PWL] Off : 30s ago
,I/PowerManagerService(  920): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  920): [PWL]     mWakeLockSummary : 0x1
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  (  920): SIOP:: AP = 360, PST = 413, CUR = 450
,I/Atfwd_Sendcmd(  369): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  369): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  301): DCD ON
,V/AlarmManager(  920): waitForAlarm result :4,
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1829): Vacuum at: now=1457078771995 tag=VacuumService
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  920): Explicit concurrent mark sweep GC freed 80886(4MB) AllocSpace objects, 22(602KB) LOS objects, 29% free, 37MB/53MB, paused 1.295ms total 112.630ms
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhenotypeConfigurator( 1829): Scheduling Phenotype for one-off execution 6182 seconds from now (1457078772524)
,I/PhenotypeFlagCommitter( 1829): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1829): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  920): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SMD     (  301): DCD ON
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1829): (HTTPLog)-Static: isShipBuild true
I/System.out( 1829): (HTTPLog)-Thread-251-797960215: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1829): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1829): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 1829, getuid(): 10015
,I/qtaguid ( 1829): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 1829, getuid(): 10015
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LocationManagerService(  920): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1829): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 1829, getuid(): 10015
,D/LocationManagerService(  920): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1829): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 1829, getuid(): 10015
,D/LocationManagerService(  920): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1829): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 1829, getuid(): 10015
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/LocationManagerService(  920): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1829): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 1829, getuid(): 10015
,D/LocationManagerService(  920): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1829): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 1829, getuid(): 10015
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  920): stay LED for fully charged
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/SSRM:n  (  920): SIOP:: AP = 350, PST = 405, CUR = 450
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  301): DCD ON
,D/FactoryTest( 6448): Not factory mode
,D/FactoryTest( 6448): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6448): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6448): still no open session command from host, so toast
,W/ContextImpl( 6448): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1583 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6448): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.app.ContextImpl.startActivity:1584 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 
,I/Timeline( 6448): Timeline: Activity_launch_request id:com.android.settings time:121636
,E/PersonaManagerService(  920): inState():  stateMachine is null !!
,I/PersonaManagerService(  920): PersonaId don't exist
I/ActivityManager(  920): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy(  920): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  920): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  920): mDVFSHelper.acquire()
,D/PointerIcon(  920): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  920): setMouseCustomIcon IconType is same.101
D/PointerIcon(  920): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  920): setHoveringSpenCustomIcon IconType is same.1
,D/ConnectivityService(  920): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/MTPRx   ( 6448): started activity for popup
,D/ResourcesManager( 6448): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6448): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6448): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6448): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6448): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6448): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6448): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6448): PREF_DONT_ASK_AGAIN : true
,D/PointerIcon(  920): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/InputMethodManagerService(  920): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  920): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3838de21 attribute=null, token = android.os.BinderProxy@1929a445
D/PointerIcon(  920): setMouseCustomIcon IconType is same.101
D/PointerIcon(  920): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  920): setHoveringSpenCustomIcon IconType is same.1
,D/SettingsReceiverActivity( 6448): dev.kiessupport is : TRUE
,D/Activity( 6448): performCreate Call secproduct feature valuefalse
,D/Activity( 6448): performCreate Call debug elastic valuetrue
,D/ActivityManager(  920): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  920): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  920): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler(  920): handleActiveUserChange for user 0
D/PersonaManagerService(  920): getPersonasForUser(): returning null!
,D/JX-Cordova( 7193): jxcore cordova android initializing
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7193): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7193): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31bb36b9 added. We now have 3 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193): load: Already loaded
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@378dafe added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7193): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,W/System.err( 7193): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 7193): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 7193): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
,W/System.err( 7193): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
,W/System.err( 7193): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7193): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7193): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7193): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7193): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7193): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7193): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7193): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7193): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/ActivityThread( 7193): updateVisibility : ActivityRecord{249d5a76 token=android.os.BinderProxy@3d01f538 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 7193): Timeline: Activity_idle id: android.os.BinderProxy@3d01f538 time:121888
,D/JX-Cordova( 7193): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7193): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 7193): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ba2d25f added. We now have 4 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193): load: Already loaded
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e6b4ac added. We now have 4 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 7193): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7193): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 7193): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 7193): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 7193): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 7193): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 7193): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 7193): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 7193): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 7193): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 7193): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 7193): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 7193): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 7193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7193): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7193): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ConnectivityService(  920): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  301): DCD ON
,W/ActivityManager(  920): mDVFSHelper.release()
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/PowerManagerService(  920): [PWL] Off : 50s ago
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/SSRM:n  (  920): SIOP:: AP = 340, PST = 394, CUR = 450
,E/SMD     (  301): DCD ON
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  301): DCD ON
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 4
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 330, PST = 383, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  920): stay LED for fully charged
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 330, PST = 372, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  920): [PWL] Off : 75s ago
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 330, PST = 362, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,V/AlarmManager(  920): waitForAlarm result :8
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 5
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 330, PST = 352, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,I/ClearcutLoggerApiImpl( 1829): disconnect managed GoogleApiClient
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 320, PST = 342, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  920): [PWL] Off : 105s ago
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/SSRM:n  (  920): SIOP:: AP = 320, PST = 337, CUR = 450
,E/SMD     (  301): DCD ON
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  301): DCD ON
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 6
,V/AlarmManager(  920): waitForAlarm result :4
,E/SMD     (  301): DCD ON
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1200): handleTimeUpdate
,D/KeyguardEffectViewController( 1200): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1200): *** don't update sliding image ***
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): stay LED for fully charged
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  (  920): SIOP:: AP = 320, PST = 333, CUR = 450
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  920): Plugged
I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/SSRM:n  (  920): SIOP:: AP = 320, PST = 329, CUR = 450
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/Atfwd_Sendcmd(  369): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  369): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  920): [PWL] Off : 140s ago
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  920): Plugged
I/MotionRecognitionService(  920): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
D/BatteryService(  920): stay LED for fully charged
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 320, PST = 326, CUR = 450
,V/AlarmManager(  920): waitForAlarm result :8
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/Watchdog(  920): !@Sync 7
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/SSRM:n  (  920): SIOP:: AP = 320, PST = 324, CUR = 450
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  920): Plugged
I/MotionRecognitionService(  920): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/SSRM:n  (  920): SIOP:: AP = 310, PST = 322, CUR = 450
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  920): SIOP:: AP = 310, PST = 320, CUR = 450
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 8
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  920): [PWL] Off : 180s ago
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  920): SIOP:: AP = 310, PST = 318, CUR = 450
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/SSRM:n  (  920): SIOP:: AP = 310, PST = 316, CUR = 450
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  920): SIOP:: AP = 310, PST = 315, CUR = 450
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 9
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): stay LED for fully charged
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  920): Plugged
I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  920): SIOP:: AP = 310, PST = 314, CUR = 450
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  920): Plugged
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  920): SIOP:: AP = 310, PST = 313, CUR = 450
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  920): [PWL] Off : 225s ago
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  920): Plugged
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  920): SIOP:: AP = 310, PST = 312, CUR = 450
,E/SMD     (  301): DCD ON
,D/TimaService(  920): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  920): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  920): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  920): initializing...
,I/TLC_TIMA_PKM_initialize(  920): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  920): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  920): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  920): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  920): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  920): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  920): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  920): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  920): App is not loaded in QSEE
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/QSEECOMAPI: (  920): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  920): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  920): Trustlet response is completed
,E/SMD     (  301): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  920): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  920): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  920): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  920): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  920): !@Sync 10
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/SSRM:n  (  920): SIOP:: AP = 310, PST = 311, CUR = 450
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/Atfwd_Sendcmd(  369): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  369): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 310, PST = 310, CUR = 450
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,V/AlarmManager(  920): waitForAlarm result :4
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,E/Zygote  ( 7397): MountEmulatedStorage()
,E/Zygote  ( 7397): v2
I/ActivityManager(  920): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7397 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 7397): KNOX_SDCARD checking this for 10096
I/libpersona( 7397): KNOX_SDCARD not a persona
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1200): handleTimeUpdate
,D/KeyguardEffectViewController( 1200): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1200): *** don't update sliding image ***
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,I/SELinux ( 7397): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7397): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SELinux ( 7397): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 7397): TimaSignature is unavailable
,D/ActivityThread( 7397): Added TimaKeyStore provider
,D/ResourcesManager( 7397): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  920): Killing 6105:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/SSRM:n  (  920): SIOP:: AP = 310, PST = 310, CUR = 450
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,V/AlarmManager(  920): waitForAlarm result :8
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 11
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  920): Plugged
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  920): stay LED for fully charged
D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/SSRM:n  (  920): SIOP:: AP = 310, PST = 310, CUR = 450
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/PowerManagerService(  920): [PWL] Off : 275s ago
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 309, CUR = 450
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): stay LED for fully charged
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  301): DCD ON
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 308, CUR = 450
,E/SMD     (  301): DCD ON
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 12
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 307, CUR = 450
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 306, CUR = 450
,E/SMD     (  301): DCD ON
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,V/AlarmManager(  920): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1200): handleTimeUpdate
,D/KeyguardEffectViewController( 1200): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1200): *** don't update sliding image ***
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 305, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PeopleSync( 2242): onPerformSync() [5005f081]
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PeopleSync( 2242): Setting subscription: result=true [5005f081]
,I/PeopleSync( 2242): Starting sync, feed=null [5005f081]
,W/BaseAppContext( 2242): Using Auth Proxy for data requests.
,W/BaseAppContext( 2242): Using Auth Proxy for data requests.
,W/BaseAppContext( 2242): Using Auth Proxy for data requests.
,I/PeopleSync( 2242): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1829): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1829): Tagging socket 55 with tag 1000040100000000{268436481,0} uid 10015, pid: 1829, getuid(): 10015
,V/AlarmManager(  920): waitForAlarm result :8
,I/qtaguid ( 1829): Tagging socket 72 with tag 1000040100000000{268436481,0} uid 10015, pid: 1829, getuid(): 10015
,I/System.out( 2242): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 2242): (HTTPLog)-Static: isShipBuild true
I/System.out( 2242): (HTTPLog)-Thread-230-725850190: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 2242): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 2242): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 2242): Tagging socket 109 with tag 1000150000000000{268440832,0} uid 10015, pid: 2242, getuid(): 10015
,I/qtaguid ( 2242): Tagging socket 113 with tag 1000150000000000{268440832,0} uid 10015, pid: 2242, getuid(): 10015
,E/SMD     (  301): DCD ON
,I/qtaguid ( 2242): Untagging socket 109
,I/System.out( 2242): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 2242): Tagging socket 109 with tag 1000190000000000{268441856,0} uid 10015, pid: 2242, getuid(): 10015
,I/qtaguid ( 2242): Untagging socket 109
,I/System.out( 2242): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 2242): Tagging socket 109 with tag 1000150000000000{268440832,0} uid 10015, pid: 2242, getuid(): 10015
,I/qtaguid ( 2242): Untagging socket 109
,I/PeopleSync( 2242): Sync finished, successful=true, took 2109ms
,I/PeopleContactsSync( 2242): CP2 sync start [5005f081]
,I/PeopleContactsSync( 2242): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 2242): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 2242): CP2 cleanup done, kept= duration=45 ms
,I/PeopleContactsSync( 2242): ===CP2 sync finished, success=true, time=57,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,I/PeopleSync( 2242): ***Sync finished***, duration: 2655 [5005f081]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=7482 uid=10129 gids={50129, 9997, 3003} abi=armeabi-v7a
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7482): MountEmulatedStorage()
E/Zygote  ( 7482): v2
,I/libpersona( 7482): KNOX_SDCARD checking this for 10129
I/libpersona( 7482): KNOX_SDCARD not a persona
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7482): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7482): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7482): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/GoogleURLConnFactory( 2242): Using platform SSLCertificateSocketFactory
,D/TimaKeyStoreProvider( 7482): TimaSignature is unavailable
,D/ActivityThread( 7482): Added TimaKeyStore provider
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 7482): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,I/System.out( 2242): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 2242): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 2242): Tagging socket 114 with tag 1000210100000000{268443905,0} uid -1, pid: 2242, getuid(): 10015
,I/qtaguid ( 2242): Tagging socket 117 with tag 1000210100000000{268443905,0} uid -1, pid: 2242, getuid(): 10015
,W/AbstractGoogleClient( 7482): Application name is not set. Call Builder#setApplicationName.
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7501 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7501): MountEmulatedStorage()
,E/Zygote  ( 7501): v2
,I/libpersona( 7501): KNOX_SDCARD checking this for 10051
I/libpersona( 7501): KNOX_SDCARD not a persona
,I/SELinux ( 7501): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7501): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7501): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7501): TimaSignature is unavailable
,D/ActivityThread( 7501): Added TimaKeyStore provider
,D/ResourcesManager( 7501): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 7501): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 7501): CalendarProvider2.onCreate() called
,I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1829): Tagging socket 55 with tag 1000040100000000{268436481,0} uid 10015, pid: 1829, getuid(): 10015
,I/System.out( 7482): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 7482): (HTTPLog)-Static: isShipBuild true
I/System.out( 7482): (HTTPLog)-Thread-1241-1012232488: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7482): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 7482): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 7482): Tagging socket 28 with tag 1100000000000000{285212672,0} uid -1, pid: 7482, getuid(): 10129
,I/CalendarProvider2( 7501): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 7524): MountEmulatedStorage()
,E/Zygote  ( 7524): v2
,I/libpersona( 7524): KNOX_SDCARD checking this for 10171
I/libpersona( 7524): KNOX_SDCARD not a persona
,I/ActivityManager(  920): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7524 uid=10171 gids={50171, 9997} abi=armeabi-v7a
,I/SELinux ( 7524): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7524): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7524): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/qtaguid ( 2242): Untagging socket 114
,D/TimaKeyStoreProvider( 7524): TimaSignature is unavailable
,D/ActivityThread( 7524): Added TimaKeyStore provider
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7524): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 7524): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7524): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/SMD     (  301): DCD ON
,E/Zygote  ( 7557): MountEmulatedStorage()
E/Zygote  ( 7557): v2
I/libpersona( 7557): KNOX_SDCARD checking this for 10172
I/libpersona( 7557): KNOX_SDCARD not a persona
,I/SELinux ( 7557): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7557): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7557): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  920): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7557 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  920): Killing 6142:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7557): TimaSignature is unavailable
,D/ActivityThread( 7557): Added TimaKeyStore provider
,D/ResourcesManager( 7557): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager( 7557): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7557): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7557): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/qtaguid ( 7482): Untagging socket 28
,W/BaseAppContext( 1829): Using Auth Proxy for data requests.
,E/BaseAppContext( 1829): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/ActivityManager(  920): Killing 6033:com.google.android.music:main/u0a144 (adj 15): bgCount ##41
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1829): Tagging socket 55 with tag 1000040100000000{268436481,0} uid 10015, pid: 1829, getuid(): 10015
,D/CalendarSyncAdapter( 7482): Found 0 events marked dirty & lastSynced
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  920): Killing 6674:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,I/ActivityManager(  920): Killing 6692:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1829): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1829): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1829): Tagging socket 73 with tag 1000060200000000{268436994,0} uid 10015, pid: 1829, getuid(): 10015
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/qtaguid ( 1829): Tagging socket 76 with tag 1000060200000000{268436994,0} uid 10015, pid: 1829, getuid(): 10015
,E/Zygote  ( 7595): MountEmulatedStorage()
I/libpersona( 7595): KNOX_SDCARD checking this for 10128
E/Zygote  ( 7595): v2
I/libpersona( 7595): KNOX_SDCARD not a persona
,I/ActivityManager(  920): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=7595 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7595): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7595): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7595): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7595): TimaSignature is unavailable
,D/ActivityThread( 7595): Added TimaKeyStore provider
,D/ResourcesManager( 7595): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/ActivityManager(  920): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7595): getAccountsCursor
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 7595): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  920): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 7595): Observing account changes for notifications
,W/ActivityManager(  920): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  920): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/Gmail   ( 7595): Sync started for account: account:61035162
,E/Gmail   ( 7595): Error finding the version of the Email provider.....
E/Gmail   ( 7595): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7595): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
E/Gmail   ( 7595): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 7595): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 7595): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7595): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7595): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 7595): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7595): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7595): getAccountsCursor
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1829): Untagging socket 73
,E/SQLiteLog( 7595): (283) recovered 31 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/GCoreUlr( 1829): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1829): DispatchingService.onCreate()
,E/File    ( 7595): fail readDirectory() errno=2
D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Gmail   ( 7595): notifyAccountChanged
,I/Gmail   ( 7595): getAccountsCursor
,I/Gmail   ( 7595): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7595): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Gmail   ( 7595): notifyAccountChanged
,I/Gmail   ( 7595): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7595): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/GCoreUlr( 1829): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1829): Unbound from all location providers
I/GCoreUlr( 1829): Place inference reporting - stopped
,I/GCoreUlr( 1829): DispatchingService.onDestroy()
,I/GCoreUlr( 1829): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1829): Unbound from all location providers
,I/GCoreUlr( 1829): Place inference reporting - stopped
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Gmail   ( 7595): getAccountsCursor
,I/Gmail   ( 7595): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 17963, normalSync: true
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 7595): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7595): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7595): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7595): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityThread( 7595): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7595): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1a62c479: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7595): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1635): Thread-127(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 1635): Thread-127(ApacheHTTPLog):isShipBuild true
,I/System.out( 1635): Thread-127(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1635): Tagging socket 36 with tag 1244000400000000{306446340,0} uid -1, pid: 1635, getuid(): 10015
,I/System.out( 7595): Thread-1274(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7595): Thread-1274(ApacheHTTPLog):isShipBuild true
,I/System.out( 7595): Thread-1274(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 7595): Tagging socket 59 with tag 1010000000000000{269484032,0} uid -1, pid: 7595, getuid(): 10128
,I/qtaguid ( 1635): Tagging socket 41 with tag 1244000400000000{306446340,0} uid -1, pid: 1635, getuid(): 10015
,I/qtaguid ( 7595): Tagging socket 63 with tag 1010000000000000{269484032,0} uid -1, pid: 7595, getuid(): 10128
,E/Watchdog(  920): !@Sync 13
,I/qtaguid ( 1635): Untagging socket 36
,I/System.out( 1635): GDataFeedFetcher calls detatch()
,D/Mms/Contact( 6803): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 6803): performUpdate:widgetCount=0
,I/qtaguid ( 1635): Tagging socket 36 with tag 1144000400000000{289669124,0} uid -1, pid: 1635, getuid(): 10015
,E/SMD     (  301): DCD ON
,I/art     (  920): Explicit concurrent mark sweep GC freed 87449(5MB) AllocSpace objects, 110(1761KB) LOS objects, 30% free, 37MB/53MB, paused 1.909ms total 149.001ms
,D/ContactProvider( 6120): getAllContactInfoList Start
,D/ContactProvider( 6120): getAllContactInfoList End
,I/qtaguid ( 1635): Untagging socket 36
,I/System.out( 1635): GDataFeedFetcher calls detatch()
,D/Mms/Contact( 6803): sContactsObserver.onChange(),selfUpdate=false
,D/ContactProvider( 6120): getAllContactInfoList Start
,E/SQLiteLog( 1697): (284) automatic index on sqlite_sq_B3A18AB0(STAT_DATA_ID)
,I/PowerManagerService(  920): [PWL] Off : 330s ago
I/PowerManagerService(  920): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  920): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  920): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/gmail-ls/com.google/eM_ADDR' (uid=1000, pid=920, ws=WorkSource{10128}) (elapsedTime=2266)
I/PowerManagerService(  920): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.android.contacts/com.google/eM_ADDR' (uid=1000, pid=920, ws=WorkSource{10015}) (elapsedTime=1115)
,E/SQLiteLog( 1697): (284) automatic index on sqlite_sq_B3A18C90(STAT_DATA_ID)
,D/ContactProvider( 6120): getAllContactInfoList End
,E/SQLiteLog( 1697): (284) automatic index on sqlite_sq_B3A383D0(STAT_DATA_ID)
,E/SQLiteLog( 1697): (284) automatic index on sqlite_sq_B3A18880(STAT_DATA_ID)
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 7595): Untagging socket 59
I/System.out( 7595): SyncAdapterThread-1 calls detatch()
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7691): MountEmulatedStorage()
,E/Zygote  ( 7691): v2
I/libpersona( 7691): KNOX_SDCARD checking this for 10146
,I/libpersona( 7691): KNOX_SDCARD not a persona
,I/ActivityManager(  920): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=7691 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7691): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7691): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7691): TimaSignature is unavailable
,D/ActivityThread( 7691): Added TimaKeyStore provider
,D/ResourcesManager( 7691): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/ContextImpl( 7691): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 7691): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7691): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7691): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/art     ( 7595): Explicit concurrent mark sweep GC freed 5378(253KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 441us total 53.483ms
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Gmail   ( 7595): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 18015, normalSync: true
,I/Gmail   ( 7595): lowestBackward conversation id 0
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/Gmail   ( 7595): notifyAccountChanged
,I/Gmail   ( 7595): getAccountsCursor
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7595): notifyAccountChanged
,W/Gmail   ( 7595): Sync complete for account: account:61035162
,I/Gmail   ( 7595): getAccountsCursor
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 2242): Using Auth Proxy for data requests.
,W/BaseAppContext( 2242): Using Auth Proxy for data requests.
,W/BaseAppContext( 2242): Using Auth Proxy for data requests.
,W/BaseAppContext( 2242): Using Auth Proxy for data requests.
,I/WebViewFactory( 7691): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/ResourcesManager( 7691): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
W/BaseAppContext( 2242): Using Auth Proxy for data requests.
,W/BaseAppContext( 2242): Using Auth Proxy for data requests.
,I/LibraryLoader( 7691): Time to load native libraries: 3 ms (timestamps 673-676)
,I/LibraryLoader( 7691): Expected native library version number "",actual native library version number ""
,W/BaseAppContext( 2242): Using Auth Proxy for data requests.
,V/WebViewChromiumFactoryProvider( 7691): Binding Chromium to main looper Looper (main, tid 1) {911db47}
,I/LibraryLoader( 7691): Expected native library version number "",actual native library version number ""
,I/chromium( 7691): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BrowserStartupController( 7691): Initializing chromium process, singleProcess=true
,W/art     ( 7691): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7691): ApplicationContext is null in ApplicationStatus
,W/chromium( 7691): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 7691): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
I/chromium( 7691): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Adreno-EGL( 7691): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7691): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7691): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7691): Local Branch: mybranch5813579
I/Adreno-EGL( 7691): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7691): Local Patches: NONE
I/Adreno-EGL( 7691): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PicasaService( 6120): start picasa sync
D/PicasaService( 6120): end picasa sync
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7750): MountEmulatedStorage()
E/Zygote  ( 7750): v2
I/libpersona( 7750): KNOX_SDCARD checking this for 10144
I/libpersona( 7750): KNOX_SDCARD not a persona
,I/SELinux ( 7750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7750): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7750): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  920): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=7750 uid=10144 gids={50144, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioManagerAndroid( 7691): Requires BLUETOOTH permission
,I/art     (  348): Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 325us total 13.438ms
,I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 273us total 9.839ms
,I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 346us total 9.344ms
,I/NSApplication( 7691): Starting up...
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7750): TimaSignature is unavailable
,D/ActivityThread( 7750): Added TimaKeyStore provider
,I/SyncAdapterService( 7691): Ignoring sync request for non-current account
,D/ResourcesManager( 7750): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  920): Killing 6710:com.sec.android.service.health/u0a21 (adj 15): bgCount ##41
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/MusicStore( 7750): Database version: 108
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Mms/Contact( 6803): performUpdate:widgetCount=0
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7750): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7750): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7750): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Auth.Api.Credentials( 2242): [CredentialSyncAdapter] Unknown sync event.
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/JNIHelp ( 7750): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityThread( 7750): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7750): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39f999b0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7750): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7750): GMSCore installation verified
,I/ConfigStore( 7750): Config Database version: 1
,I/System.out( 7482): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 7482): Tagging socket 28 with tag 1000000400000000{268435460,0} uid -1, pid: 7482, getuid(): 10129
,I/qtaguid ( 7482): Tagging socket 32 with tag 1000000400000000{268435460,0} uid -1, pid: 7482, getuid(): 10129
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7750): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7750): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7750): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,I/Icing   ( 2242): Indexing E78F5CBEB57D2B0FC1D839F8E1139AA0E96FD1EC from com.google.android.gm
,D/SSRM:n  (  920): SIOP:: AP = 330, PST = 307, CUR = 450
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/WifiDisplayAdapter(  920): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  920): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService(  920): getStreamVolume 3 index 0
,I/MediaRouter( 7750): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/art     ( 2242): Explicit concurrent mark sweep GC freed 35982(2MB) AllocSpace objects, 35(871KB) LOS objects, 24% free, 23MB/31MB, paused 979us total 62.515ms
,I/GHttpClientFactory( 7750): Using the GMSCore's GoogleHttpClient
,I/Icing   ( 2242): Indexing done E78F5CBEB57D2B0FC1D839F8E1139AA0E96FD1EC
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7750): type=WIFI subType= reason=null isConnected=true
,V/CalendarSyncAdapter( 7482): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2017-03-25T00:00:00.000Z, updatedMin=2016-02-15T23:58:22.671Z}
,I/qtaguid ( 7482): Untagging socket 28
,D/WifiDisplayAdapter(  920): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7750): type=WIFI subType= reason=null isConnected=true
,W/SQLiteConnectionPool( 2242): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/GHttpClientFactory( 7750): Using the GMSCore's GoogleHttpClient
,D/CalendarSyncAdapter( 7482): Found 0 events marked dirty & lastSynced
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  920): Killing 6725:com.sec.pcw.device/1000 (adj 15): bgCount ##41
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 7750): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7750): (HTTPLog)-Static: isShipBuild true
I/System.out( 7750): (HTTPLog)-Thread-1281-209024737: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7750): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 7750): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/art     (  920): Explicit concurrent mark sweep GC freed 41041(1948KB) AllocSpace objects, 6(96KB) LOS objects, 30% free, 37MB/53MB, paused 3.450ms total 133.540ms
,I/GAV2    ( 7595): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 1829): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 7750): (HTTPLog)-Static: isSBSettingEnabled false
,W/MusicApiClient( 7750): No content in 'data' field in GET sync response for Track
,I/MusicSyncAdapter( 7750): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
,I/MusicSyncAdapter( 7750): Periodic update
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7750): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
E/File    ( 7750): fail readDirectory() errno=2
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7750): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/ContextImpl( 7750): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,I/MusicLeanback( 7750): Conditions not met for autocaching.
I/MusicLeanback( 7750): Stop autocaching.
,D/WearableService( 1829): callingUid 10015, callindPid: 1829
,E/GmsUtils( 7750): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 7750): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/ActivityManager(  920): Killing 5135:com.sec.spp.push/u0a43 (adj 15): bgCount ##41
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/GAV4    ( 7691): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/GmsUtils( 7750): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/MusicLeanback( 7750): Conditions not met for autocaching.
I/MusicLeanback( 7750): Stop autocaching.
,I/art     ( 1829): Explicit concurrent mark sweep GC freed 124072(7MB) AllocSpace objects, 81(3MB) LOS objects, 40% free, 22MB/38MB, paused 981us total 87.963ms
,E/GmsUtils( 7750): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 310, PST = 307, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,V/AlarmManager(  920): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1200): handleTimeUpdate
,D/KeyguardEffectViewController( 1200): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1200): *** don't update sliding image ***
,D/ConnectivityService(  920): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1200): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  (  920): SIOP:: AP = 310, PST = 307, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 14
,W/IcingInternalCorpora( 2242): getNumBytesRead when not calculated.
,E/SMD     (  301): DCD ON
,I/Atfwd_Sendcmd(  369): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  369): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 306, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  920): stay LED for fully charged
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 305, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 305, CUR = 450
,V/AlarmManager(  920): waitForAlarm result :8
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 15
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  920): [PWL] Off : 390s ago
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 305, CUR = 450
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 305, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/bootchecker(  365): bootchecker wake up!!
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 305, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 16
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 305, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): stay LED for fully charged
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 302, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  920): Plugged
I/MotionRecognitionService(  920): setPowerConnected  = true
,E/SMD     (  301): DCD ON
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 301, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,I/ClearcutLoggerApiImpl( 2242): disconnect managed GoogleApiClient
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 17
,E/SMD     (  301): DCD ON
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 300, CUR = 450
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  920): Plugged
I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,I/PowerManagerService(  920): [PWL] Off : 455s ago
,I/ServiceManager(  369): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,W/Atfwd_Sendcmd(  369): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 300, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  920): Plugged
I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 300, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 18
,E/SMD     (  301): DCD ON
,I/Atfwd_Sendcmd(  369): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  369): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 300, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): stay LED for fully charged
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  920): Plugged
I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 300, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): stay LED for fully charged
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,E/SMD     (  301): DCD ON
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Daemon(  369): Stop the daemon....
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 19
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 300, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): stay LED for fully charged
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  920): Plugged
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 300, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  920): [PWL] Off : 525s ago
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  920): Plugged
I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/TimaService(  920): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  920): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  920): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  920): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  920): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  920): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  920): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  920): !@Sync 20
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 300, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 300, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  920): Plugged
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 21
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 299, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 298, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 297, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  920): Plugged
I/MotionRecognitionService(  920): setPowerConnected  = true
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 22
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  920): [PWL] Off : 600s ago
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 296, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 295, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 294, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  920): Plugged
I/MotionRecognitionService(  920): setPowerConnected  = true
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 23
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 293, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 292, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 291, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 24
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  920): Plugged
I/MotionRecognitionService(  920): setPowerConnected  = true
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  920): [PWL] Off : 680s ago
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 25
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,E/SMD     (  301): DCD ON
,V/AlarmManager(  920): waitForAlarm result :8
,E/Watchdog(  920): !@Sync 26
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 27
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  920): [PWL] Off : 765s ago
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 28
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  920): stay LED for fully charged
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 29
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  920): stay LED for fully charged
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/TimaService(  920): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  920): TimaServiceHandler.handleMessage what =1
,D/TimaService(  920): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  301): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  920): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  920): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  920): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  920): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  920): !@Sync 30
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  920): [PWL] Off : 855s ago
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  920): stay LED for fully charged
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): stay LED for fully charged
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 31
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  920): stay LED for fully charged
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): stay LED for fully charged
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 32
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  920): stay LED for fully charged
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,E/SMD     (  301): DCD ON
,E/Watchdog(  920): !@Sync 33
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  920): [PWL] Off : 950s ago
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  920): !@Sync 34
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,D/BatteryService(  920): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  920): setPowerConnected  = true
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/Watchdog(  920): !@Sync 35
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  920): Plugged
I/MotionRecognitionService(  920): setPowerConnected  = true
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  920): Plugged
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
D/BatteryService(  920): stay LED for fully charged
,E/Watchdog(  920): !@Sync 36
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  920): stay LED for fully charged
D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  920): !@Sync 37
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  920): [PWL] Off : 1050s ago
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): stay LED for fully charged
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  920): !@Sync 38
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): stay LED for fully charged
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,E/Watchdog(  920): !@Sync 39
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  920): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3167): Disconnected process message: 10
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/TimaService(  920): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  920): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  920): TimaServiceHandler.handleMessage what =1
,E/SMD     (  301): DCD ON
,I/UsageStatsService(  920): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  920): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  920): Updating Usage Statistics in DB @ 1457079874265
,I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
,W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
,W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  920): ::getAppControlDB: Exception to create DB
W/System.err(  920): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  920): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  920): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  920): Done Updating Usage Statistics in DB @ 1457079874438
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  920): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  920): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  920): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  920): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  920): !@Sync 40
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  920): [PWL] Off : 1155s ago
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,E/Watchdog(  920): !@Sync 41
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,E/Watchdog(  920): !@Sync 42
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): stay LED for fully charged
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  920): setPowerConnected  = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  920): SIOP:: AP = 290, PST = 290, CUR = 450
,E/Watchdog(  920): !@Sync 43
,D/BatteryService(  920): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  920): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  920): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  920): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1200): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1200): handleBatteryUpdate
,I/MotionRecognitionService(  920): Plugged
,I/MotionRecognitionService(  920): setPowerConnected  = true
D/BatteryService(  920): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1200):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1200): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3167): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3167): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  301): DCD ON
D/AndroidRuntime( 7930): 
D/AndroidRuntime( 7930): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7930): CheckJNI is OFF
D/AndroidRuntime( 7930): readGMSProperty: start
D/AndroidRuntime( 7930): readGMSProperty: already setted!!
D/AndroidRuntime( 7930): readGMSProperty: end
D/AndroidRuntime( 7930): addProductProperty: start
E/AffinityControl( 7930): AffinityControl: registerfunction enter
D/AndroidRuntime( 7930): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  920): START PACKAGE DELETE: observer{924774028}
D/PackageManager(  920): pkg{<packageName>}
D/PackageManager(  920): user{0}
D/PackageManager(  920): caller{2000}
D/PackageManager(  920): flags{3}
D/PersonaManagerService(  920): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  920): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  920): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  920): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  920): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  920): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  920): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  920): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  920): getApplicationUninstallationEnabled
D/ApplicationPolicy(  920): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  920): !@killApplicatoin: 10079, uninstall pkg
I/ActivityManager(  920): Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
I/ActivityManager(  920): Killing 7193:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest
W/PackageSettings(  920): Skipping PackageSetting{32dfc971 com.example.hello/10078} due to missing metadata
I/WindowState(  920): WIN DEATH: Window{3926279a u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  266): id=13 Removed NainActivit (5/8)
I/SurfaceFlinger(  266): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger(  266): id=13 Removed NainActivit (-2/8)
D/PointerIcon(  920): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  920): setMouseCustomIcon IconType is same.101
D/PointerIcon(  920): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  920): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager(  920):   Force finishing activity ActivityRecord{9e2eef4 u0 com.test.thalitest/.MainActivity t9}
W/ActivityManager(  920): mDVFSHelper.acquire()
I/ActivityManager(  920): Force stopping com.test.thalitest appid=10079 user=0: pkg removed
I/ActivityManager(  920):   Force finishing activity ActivityRecord{9e2eef4 u0 com.test.thalitest/.MainActivity t9 f}
W/ActivityManager(  920): Duplicate finish request for ActivityRecord{9e2eef4 u0 com.test.thalitest/.MainActivity t9 f}
I/art     ( 2242): Explicit concurrent mark sweep GC freed 3984(189KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 23MB/31MB, paused 815us total 79.890ms
I/art     ( 6918): Explicit concurrent mark sweep GC freed 3752(195KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 440us total 64ms
I/art     ( 6969): Explicit concurrent mark sweep GC freed 8155(487KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 16MB/21MB, paused 460us total 63.437ms
W/ActivityManager(  920): Spurious death for ProcessRecord{312269d5 7193:com.test.thalitest/u0a79}, curProc for 7193: null
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/ConnectivityService(  920): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3692): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
I/InputReader(  920): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager( 1438): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
E/SamsungIME( 1741): mOCRHelper is null
I/DBG_DM  ( 3692): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
I/art     ( 6083): Explicit concurrent mark sweep GC freed 34962(1921KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 15MB/26MB, paused 868us total 41.316ms
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
W/GeofencerStateMachine( 1829): Ignoring removeGeofence because network location is disabled.
I/DBG_DM  ( 3692): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
W/ResourcesManager( 1438): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1438): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1438): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
W/ResourcesManager( 1438): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1438): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1438): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/DBG_DM  ( 3692): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3692): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 0
I/art     ( 6422): Explicit concurrent mark sweep GC freed 23036(1176KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 639us total 124.436ms
I/DBG_DM  ( 3692): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
E/Zygote  ( 7956): MountEmulatedStorage()
I/ActivityManager(  920): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7956 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 7956): v2
I/libpersona( 7956): KNOX_SDCARD checking this for 10023
I/libpersona( 7956): KNOX_SDCARD not a persona
I/DBG_DM  ( 3692): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
D/ResourcesManager( 1438): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/ResourcesManager( 1438): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1438): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/SELinux ( 7956): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/RegisteredServicesCache( 1412): empty dynamic service
I/SELinux ( 7956): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7956): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  920): Explicit concurrent mark sweep GC freed 80685(8MB) AllocSpace objects, 275(4MB) LOS objects, 30% free, 37MB/53MB, paused 1.468ms total 145.830ms
D/ResourcesManager(  920): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  920): WaitForGcToComplete blocked for 47.226ms for cause Explicit
I/DBG_DM  ( 3692): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/art     ( 1487): Explicit concurrent mark sweep GC freed 57925(3MB) AllocSpace objects, 1(39KB) LOS objects, 25% free, 19MB/26MB, paused 2.150ms total 176.849ms
D/SecContentProvider2(  920): uri = 14 selection = getSealedState
D/SecContentProvider2(  920): mCursor = null
D/TimaKeyStoreProvider( 7956): TimaSignature is unavailable
D/ActivityThread( 7956): Added TimaKeyStore provider
D/ApplicationPolicy(  920): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  920): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
I/DBG_DM  ( 3692): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 0
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
I/DBG_DM  ( 3692): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/DBG_DM  ( 3692): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/DBG_DM  ( 3692): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3692): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3692): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ActivityManager(  920): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  920): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  920): postActiveUserChange, showWhenLocked: false
I/DBG_DM  ( 3692): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
I/SurfaceFlinger(  266): id=14 createSurf (1080x1920),2 flag=404, YUIInstallC
D/StatusBarManagerService(  920): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/SecContentProvider2(  920): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  920): mCursor = null
D/PointerIcon(  920): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  920): setMouseCustomIcon IconType is same.101
D/PointerIcon(  920): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  920): setHoveringSpenCustomIcon IconType is same.1
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager( 7956): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/InputMethodManagerService(  920): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  920): Got RemoteException sending setActive(false) notification to pid 7193 uid 10079
V/ActivityThread( 3692): updateVisibility : ActivityRecord{2e902a00 token=android.os.BinderProxy@31894121 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
W/ContextImpl(  920): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager(  920): mDVFSHelper.release()
I/Timeline(  920): Timeline: Activity_windows_visible id: ActivityRecord{2e9a27db u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t8} time:1317142
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
I/Timeline( 3692): Timeline: Activity_idle id: android.os.BinderProxy@31894121 time:1317143
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/KLMS-2.4.511: ( 7956): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
I/KLMS-2.4.511: ( 7956): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1457079974786
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/KLMS-2.4.511: ( 7956): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 7956): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/RCPManagerService(  920): PackageReceiver onReceive()
I/HarmonyEASService(  920): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  920): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  920): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy(  920): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService(  920): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  920): uID is 10079
V/EnterpriseBillingPolicy(  920): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  920): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  920): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  920): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  920): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  920): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  920): getBillingProfileForVpnEngine - end - null
D/SSRM:aV (  920): MSG_TYPE_APP_REMOVED::
D/KnoxTimeoutHandler(  920): handleActiveUserChange for user 0
D/PersonaManagerService(  920): getPersonasForUser(): returning null!
V/AlarmManagerEXT(  920): com.test.thalitest(10079) is removed.
D/TaskPersister(  920): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  920): removeObsoleteFile: deleting file=8_task.xml
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
D/StatusBar( 1200): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1200): isKioskContainerExistOnDevice
D/PersonaManager( 1200): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1200): Icon Only
I/StatusBar( 1200): Icon Only
D/PanelView( 1200): There is/are notification(s) 
D/PanelView( 1200): There is/are notification(s) 
E/Zygote  ( 7977): MountEmulatedStorage()
E/Zygote  ( 7977): v2
I/libpersona( 7977): KNOX_SDCARD checking this for 10116
I/libpersona( 7977): KNOX_SDCARD not a persona
I/ActivityManager(  920): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7977 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  920): Killing 6756:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
I/art     (  920): Explicit concurrent mark sweep GC freed 17074(911KB) AllocSpace objects, 4(64KB) LOS objects, 30% free, 37MB/53MB, paused 1.463ms total 318.658ms
I/SELinux ( 7977): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7977): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7977): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7977): TimaSignature is unavailable
D/ActivityThread( 7977): Added TimaKeyStore provider
D/ResourcesManager( 7977): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/elm:14491( 7977): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/PackageManager(  920): delete codoeFile: 
D/elm:14491( 7977): ELMEngine.ELMEngine( context ).
D/elm:14491( 7977): MDMBridge.setEnterpriseBridge()
D/AASAuninstall(  920): userId = 0, info.removedAppID = -1, info.uid = 10079, packageName = com.test.thalitest
I/AASA_removePackage(  920): UID=10079 Target=com.test.thalitest
D/PackageManager(  920): result of delete: 1{924774028}
D/elm:14491( 7977): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/AASAservice-UpdateReceiver( 3843): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 3843): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3843): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
W/System.err( 3843): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 3843): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
W/System.err( 3843): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
W/System.err( 3843): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 3843): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3843): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3843): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
W/System.err( 3843): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3843): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3843): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
W/System.err( 3843): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 7930): Shutting down VM
D/elm:14491( 7977): ElmAgentService : onCreate()
D/elm:14491( 7977): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 7977): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 7977): MDMBridge.getInstance()
D/elm:14491( 7977): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 7977): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 7994): MountEmulatedStorage()
E/Zygote  ( 7994): v2
I/libpersona( 7994): KNOX_SDCARD checking this for 10021
I/libpersona( 7994): KNOX_SDCARD not a persona
I/ActivityManager(  920): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7994 uid=10021 gids={50021, 9997} abi=armeabi-v7a
I/SELinux ( 7994): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/elm:14491( 7977): ElmAgentService : onDestroy().
I/SELinux ( 7994): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
I/ActivityManager(  920): Killing 6782:com.osp.app.signin/u0a50 (adj 15): bgCount ##41
E/SELinux ( 7994): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7994): TimaSignature is unavailable
D/ActivityThread( 7994): Added TimaKeyStore provider
D/ResourcesManager( 7994): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7994): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 7994): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7994): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8009): MountEmulatedStorage()
E/Zygote  ( 8009): v2
I/libpersona( 8009): KNOX_SDCARD checking this for 1000
I/libpersona( 8009): KNOX_SDCARD not a persona
I/ActivityManager(  920): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8009 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  920): Killing 6573:com.android.defcontainer/u0a7 (adj 13): bgCount ##41
I/SELinux ( 8009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 8009): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 8009): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8009): TimaSignature is unavailable
D/ActivityThread( 8009): Added TimaKeyStore provider
D/ResourcesManager( 8009): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
I/PCWCLIENTTRACE_LOG( 8009): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8009): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8009): new DMDBOpenHelper instance
I/PCWCLIENTTRACE_PushUtil( 8009): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 8009): sales region : global
I/PCWCLIENTTRACE_PushUtil( 8009): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 8009): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  920): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=8029 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 8029): MountEmulatedStorage()
E/Zygote  ( 8029): v2
I/libpersona( 8029): KNOX_SDCARD checking this for 10043
I/libpersona( 8029): KNOX_SDCARD not a persona
I/SELinux ( 8029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 8029): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 8029): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager(  920): Killing 6803:com.android.mms/u0a55 (adj 13): bgCount ##41
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/TimaKeyStoreProvider( 8029): TimaSignature is unavailable
D/ActivityThread( 8029): Added TimaKeyStore provider
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/ResourcesManager( 8029): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
D/EnterpriseDeviceManagerService(  920): Package has changed for user 0
D/EnterpriseDeviceManagerService(  920): Admin package name: com.google.android.gms
W/ContextImpl( 8029): Unable to create files subdir /data/data/com.sec.spp.push/cache
E/ActivityThread( 8029): Unable to setupGraphicsSupport due to missing cache directory
I/EventHub(  920): Removing device '/dev/input/event6' due to inotify event
E/SharedPreferencesImpl( 6230): Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
W/        ( 8029): Zip: inflate read failed (7420 vs 32768)
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/AndroidRuntime( 8029): Shutting down VM
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
E/AndroidRuntime( 8029): FATAL EXCEPTION: main
E/AndroidRuntime( 8029): Process: com.sec.spp.push, PID: 8029
E/AndroidRuntime( 8029): java.lang.RuntimeException: Unable to instantiate application com.sec.spp.push.PushClientApplication: java.lang.ClassNotFoundException: Didn't find class "com.sec.spp.push.PushClientApplication" on path: DexPathList[[zip file "/system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8029): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
E/AndroidRuntime( 8029): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
E/AndroidRuntime( 8029): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 8029): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 8029): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8029): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8029): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/AndroidRuntime( 8029): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8029): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8029): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/AndroidRuntime( 8029): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
E/AndroidRuntime( 8029): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.spp.push.PushClientApplication" on path: DexPathList[[zip file "/system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8029): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 8029): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 8029): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 8029): 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
E/AndroidRuntime( 8029): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
E/AndroidRuntime( 8029): 	... 10 more
E/AndroidRuntime( 8029): 	Suppressed: java.io.IOException: Failed to extract 'classes.dex' from '/system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk': I/O Error
E/AndroidRuntime( 8029): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 8029): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 8029): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 8029): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 8029): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 8029): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 8029): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 8029): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 8029): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 8029): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
E/AndroidRuntime( 8029): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8029): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8029): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
E/AndroidRuntime( 8029): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
E/AndroidRuntime( 8029): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
E/AndroidRuntime( 8029): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 8029): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 8029): 		... 10 more
E/AndroidRuntime( 8029): 	Caused by: java.io.IOException: Failed to open file '/data/dalvik-cache/arm/system@priv-app@SPPPushClient_Prod@SPPPushClient_Prod.apk@classes.dex': Read-only file system
E/AndroidRuntime( 8029): 		... 27 more
E/AndroidRuntime( 8029): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk'
E/AndroidRuntime( 8029): 		... 27 more
E/AndroidRuntime( 8029): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/SPPPushClient_Prod/arm/SPPPushClient_Prod.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 8029): 		... 27 more
E/AndroidRuntime( 8029): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 8029): 		... 27 more
E/AndroidRuntime( 8029): 	Suppressed: java.lang.ClassNotFoundException: com.sec.spp.push.PushClientApplication
E/AndroidRuntime( 8029): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 8029): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 8029): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 8029): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 8029): 		... 13 more
E/AndroidRuntime( 8029): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
V/ApplicationPolicy(  920): isApplicationStateBlocked userId 0 pkgname com.sec.spp.push
D/CountryDetector(  920): No listener is left
W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
E/AndroidRuntime(  920): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  920): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  920): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  920): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  920): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  920): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  920): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  920): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:15135)
E/AndroidRuntime(  920): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  920): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  920): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  920): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  920): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  920): 	... 5 more
W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  920): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  920): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
E/android.os.Debug(  920): ro.product_ship = true
E/android.os.Debug(  920): ro.debug_level = 0x4f4c
D/ResourcesManager(  920): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
E/AndroidRuntime(  920): Error reporting crash
E/AndroidRuntime(  920): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  920): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  920): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  920): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  920): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  920): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  920): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:15135)
E/AndroidRuntime(  920): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15142)
E/AndroidRuntime(  920): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14730)
E/AndroidRuntime(  920): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14714)
E/AndroidRuntime(  920): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime(  920): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime(  920): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/AndroidRuntime(  920): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  920): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  920): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  920): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  920): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  920): 	... 11 more
I/Process (  920): Sending signal. PID: 920 SIG: 9
W/AudioFlinger(  313): power manager service died !!!
I/SurfaceFlinger(  266): restart the boot-animation @ binderDied
W/Sensors ( 1438): sensorservice died [0xaedf4200]
D/SurfaceFlinger(  266): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  266): hwc_blank: Unblanking display: 0
I/ServiceManager(  264): service 'sec_analytics' died
I/ServiceManager(  264): service 'wifi_policy' died
I/ServiceManager(  264): service 'phone_restriction_policy' died
I/ServiceManager(  264): service 'remoteinjection' died
I/ServiceManager(  264): service 'mum_container_policy' died
I/ServiceManager(  264): service 'enterprise_billing_policy' died
I/ServiceManager(  264): service 'knox_timakeystore_policy' died
I/ServiceManager(  264): service 'backup' died
I/ServiceManager(  264): service 'appwidget' died
I/ServiceManager(  264): service 'voiceinteraction' died
I/ServiceManager(  264): service 'SecExternalDisplayService' died
I/ServiceManager(  264): service 'diskstats' died
I/ServiceManager(  264): service 'mDNIe' died
I/ServiceManager(  264): service 'netpolicy' died
I/ServiceManager(  264): service 'wifip2p' died
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
I/ServiceManager(  264): service 'media_projection' died
I/ServiceManager(  264): service 'imms' died
I/ServiceManager(  264): service 'wifi' died
I/ServiceManager(  264): service 'msapwifi' died
I/ServiceManager(  264): service 'wifiscanner' died
I/ServiceManager(  264): service 'rttmanager' died
I/ServiceManager(  264): service 'audio' died
I/ServiceManager(  264): service 'DockObserver' died
I/ServiceManager(  264): service 'usb' died
I/ServiceManager(  264): service 'serial' died
I/ServiceManager(  264): service 'uimode' died
I/ServiceManager(  264): service 'tactileassist' died
I/ServiceManager(  264): service 'bluetooth_manager' died
I/ServiceManager(  264): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  264): service 'motion_recognition' died
I/ServiceManager(  264): service 'cover' died
I/ServiceManager(  264): service 'mount' died
I/ServiceManager(  264): service 'lock_settings' died
I/ServiceManager(  264): service 'device_policy' died
I/ServiceManager(  264): service 'harmony_eas_service' died
I/ServiceManager(  264): service 'sdp' died
I/ServiceManager(  264): service 'connectivity' died
I/ServiceManager(  264): service 'sb_service' died
I/ServiceManager(  264): service 'servicediscovery' died
I/ServiceManager(  264): service 'updatelock' died
I/ServiceManager(  264): service 'notification' died
I/ServiceManager(  264): service 'devicestoragemonitor' died
I/ServiceManager(  264): service 'location' died
I/ServiceManager(  264): service 'country_detector' died
I/ServiceManager(  264): service 'search' died
I/ServiceManager(  264): service 'dropbox' died
I/ServiceManager(  264): service 'wallpaper' died
I/ServiceManager(  264): service 'log_manager_service' died
I/ServiceManager(  264): service 'accessibility' died
I/ServiceManager(  264): service 'rcp' died
I/ServiceManager(  264): service 'input_method' died
I/ServiceManager(  264): service 'jobscheduler' died
I/ServiceManager(  264): service 'gfxinfo' died
I/ServiceManager(  264): service 'activity' died
I/ServiceManager(  264): service 'hardware' died
I/ServiceManager(  264): service 'sedenial' died
I/ServiceManager(  264): service 'vibrator' died
I/ServiceManager(  264): service 'tima' died
I/ServiceManager(  264): service 'cepproxyks' died
I/ServiceManager(  264): service 'CustomFrequencyManagerService' died
I/ServiceManager(  264): service 'samsung.smartfaceservice' died
I/ServiceManager(  264): service 'consumer_ir' died
I/ServiceManager(  264): service 'enterprise_policy' died

```
