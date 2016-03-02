#### Test 61432979123161a_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 98026622759; DSPS: 3353025; Offset : -4313260646
D/AndroidRuntime( 6563): 
D/AndroidRuntime( 6563): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6563): CheckJNI is OFF
D/AndroidRuntime( 6563): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1047): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1955): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1047): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1047): setTaskToReturnTo : TaskRecord{3d75d59a #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1047): setTaskToReturnTo : TaskRecord{3d75d59a #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1047): AppWindowTokenEx init.. 
E/GBMv2   (  345): DFP En is all cleared set to be enabled
I/ActivityManager( 1047): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6583 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/InputDispatcher( 1047): Focus left window: Window{263e33ca u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 2076): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/AndroidRuntime( 6563): Shutting down VM
V/ActivityManager( 1047): Display changed displayId=0
D/DSDPConnection( 1859): Display #0 changed.
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{30381470 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{1cbb03e9 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6583): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/WebViewFactory( 6583): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6583): Loading: webviewchromium
,I/LibraryLoader( 6583): Time to load native libraries: 3 ms (timestamps 8756-8759)
I/LibraryLoader( 6583): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6583): Binding Chromium to main looper Looper (main, tid 1) {af49dd9}
,I/LibraryLoader( 6583): Expected native library version number "",actual native library version number ""
I/chromium( 6583): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6583): Initializing chromium process, renderers=0
W/art     ( 6583): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  320): registerClient() client 0xb14fd600, uid 10311
,D/BluetoothManagerService( 1047): Message: 20
D/BluetoothManagerService( 1047): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13ab3554:true
W/chromium( 6583): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6583): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6583): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,I/Adreno-EGL( 6583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6583): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6583): Build Date: 12/12/14 금
I/Adreno-EGL( 6583): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6583): Remote Branch: 
I/Adreno-EGL( 6583): Local Patches: 
I/Adreno-EGL( 6583): Reconstruct Branch: 
,W/chromium( 6583): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6583): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6583): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6583): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 6583): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 6583): [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 6583): [setNavigationBarColor2] color=0x fff5f5f5
,D/SystemWebViewEngine( 6583): CordovaWebView is running on device made by: LGE
,W/art     ( 6583): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6583): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1047): Activity pause timeout for ActivityRecord{215d0ecb u0 com.test.thalitest/.MainActivity t4}
,D/LgDataFeature( 6583): LgDataFeature() Constructor: none
,D/LgDataFeature( 6583): LgDataFeature() Constructor Done, null
I/art     ( 1047): Explicit concurrent mark sweep GC freed 19510(854KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 2.280ms total 144.917ms
,D/OpenGLRenderer( 6583): Render dirty regions requested: true
I/OpenGLRenderer( 6583): Initialized EGL, version 1.4
D/OpenGLRenderer( 6583): Enabling debug mode 0
D/Atlas   ( 6583): Validating map...
,D/SplitWindow( 1047): check instance of lgWin Window{3e303bee u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WindowManager( 1047): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
,I/[SystemUI]NavigationThemeResource( 1458): notify navigation bar color(0xfff5f5f5)
I/[SystemUI]NavigationThemeResource( 1458): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1458):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1458): , Keyguard show=false, IME shown=false, Panel expanded=false
I/SystemUI[Framework]( 1047): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
W/PhoneWindowManagerEx( 1047): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1047): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1047): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@302c33f9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher( 1047): Focus entered window: Window{3e303bee u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputMethodManagerService( 1047): setImestate : 0
,I/ActivityManager( 1047): Displayed com.test.thalitest/.MainActivity: +693ms (total +805ms)
,I/Timeline( 1047): Timeline: Activity_windows_visible id: ActivityRecord{215d0ecb u0 com.test.thalitest/.MainActivity t4} time:99291
W/IInputConnectionWrapper( 6583): showStatusIcon on inactive InputConnection
W/IInputConnectionWrapper( 6583): getTextBeforeCursor on inactive InputConnection
E/b       ( 1692): Unable to connect to the editor to retrieve text... will retry later
I/Timeline( 6583): Timeline: Activity_idle id: android.os.BinderProxy@25c5b27c time:99311
,W/IInputConnectionWrapper( 6583): getTextAfterCursor on inactive InputConnection
D/JsMessageQueue( 6583): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6583): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6583): 
,D/jxcore_app_log( 6583): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435209856
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6583): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6583):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6583):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6583):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6583):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6583): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35c1fcb9 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6583): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6583):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6583):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6583):     - Bluetooth MAC address: 58:3F:54:73:64:C0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6583):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6583):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6583):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6583):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6583):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6583):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6583): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@518b2ac added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6583): addListener: New listener added - the number of listeners is now 1
D/WifiService( 1047): New client listening to asynchronous messages
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6583): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,W/System.err( 6583): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 6583): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 6583): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 6583): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 6583): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 6583): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 6583): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 6583): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 6583): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 6583): 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 6583): 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
W/System.err( 6583): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6583): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6583): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 6583): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6583): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6583): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efcab75 added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6583): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6583): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f50d70a added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6583): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6583): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 6583): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 6583): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 6583): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 6583): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 6583): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 6583): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 6583): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 6583): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 6583): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 6583): 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 6583): 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
W/System.err( 6583): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6583): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6583): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/chromium( 6583): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6583): 
,E/GBMv2   (  345): DFP En is all cleared set to be enabled
E/GBMv2   (  345): Set value is all cleared set the max
I/GBMv2   (  345): DFP Enabled. Ignore VFP set
,I/rmt_storage(  306): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  306): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  306): wakelock acquired: 1, error no: 42
,I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  306): 
,I/rmt_storage(  306): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  906): [IMS_FATAL]| 3347 | 920 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
I/chromium( 6583): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 6583): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{1ab1ceab type 2 when 104539 android} when 104539
,I/ActivityManager( 1047): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6658 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  356): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 433us total 33.913ms
,I/art     (  356): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 406us total 29.885ms
,I/art     (  356): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 363us total 31.700ms
,I/ReaderUtils( 6658): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 6658): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6658): Created application version: 3.2.35 (30235)
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksSync( 6658): Starting books sync
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2127): innerSync failed
D/ContactsSyncAdapter( 2127): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2127): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2127): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2127): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2127): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2127): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2127): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2127): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2127): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2127): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2127): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/SyncManager( 1047): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 89844, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1047): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 169681, reason: 10019
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/BooksSync( 6658): started syncMyEbooks
,I/art     ( 2127): Explicit concurrent mark sweep GC freed 17726(991KB) AllocSpace objects, 3(432KB) LOS objects, 51% free, 30MB/62MB, paused 1.456ms total 39.887ms
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6658): Authentication error
E/BooksAccountManager( 6658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6658): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6658): null auth token
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
,D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6658): Error response from books API: {
W/ApiaryClient( 6658):  "error": {
W/ApiaryClient( 6658):   "errors": [
W/ApiaryClient( 6658):    {
W/ApiaryClient( 6658):     "domain": "global",
W/ApiaryClient( 6658):     "reason": "required",
W/ApiaryClient( 6658):     "message": "Login Required",
W/ApiaryClient( 6658):     "locationType": "header",
W/ApiaryClient( 6658):     "location": "Authorization"
W/ApiaryClient( 6658):    }
W/ApiaryClient( 6658):   ],
W/ApiaryClient( 6658):   "code": 401,
W/ApiaryClient( 6658):   "message": "Login Required"
W/ApiaryClient( 6658):  }
W/ApiaryClient( 6658): }
W/ApiaryClient( 6658): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6916478291192112822&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6658): Headers:
W/ApiaryClient( 6658): accept-encoding: [gzip]
W/ApiaryClient( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6658): gdata-version: 2
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6658): Authentication error
E/BooksAccountManager( 6658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6658): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6658): null auth token
,I/MusicWidget( 2697): mDelayedStopHandler : unbind
,I/MusicBrowser( 2205): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2205): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2205): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2205): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2205): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2205): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2205): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2205): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,I/MediaFocusControl( 1047):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@21eae56fcom.lge.music.MediaPlaybackService$5@25c5b27c
D/MusicBrowser( 2205): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2205): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2205): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2205): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2205): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@2ed23baa
I/MusicBrowser( 2205): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2205): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2205): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2205): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2205): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2205): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2205): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2205): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2205): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2205): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2205): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2205): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2205): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2205): reset
W/ApiaryClient( 6658): Error response from books API: {
W/ApiaryClient( 6658):  "error": {
W/ApiaryClient( 6658):   "errors": [
W/ApiaryClient( 6658):    {
W/ApiaryClient( 6658):     "domain": "global",
W/ApiaryClient( 6658):     "reason": "required",
W/ApiaryClient( 6658):     "message": "Login Required",
W/ApiaryClient( 6658):     "locationType": "header",
W/ApiaryClient( 6658):     "location": "Authorization"
W/ApiaryClient( 6658):    }
W/ApiaryClient( 6658):   ],
W/ApiaryClient( 6658):   "code": 401,
W/ApiaryClient( 6658):   "message": "Login Required"
W/ApiaryClient( 6658):  }
W/ApiaryClient( 6658): }
,W/ApiaryClient( 6658): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6916478291192112822&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6658): Headers:
W/ApiaryClient( 6658): accept-encoding: [gzip]
W/ApiaryClient( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6658): gdata-version: 2
V/MediaPlayer[Native]( 2205): setListener
V/MediaPlayer[Native]( 2205): disconnect
V/MediaPlayer[Native]( 2205): destructor
V/AudioFlinger(  320): releasing 13 from 2205 for -1
,V/AudioFlinger(  320):  decremented refcount to 0
V/AudioFlinger(  320): purging stale effects
V/MediaPlayer[Native]( 2205): disconnect
D/MusicBrowser( 2205): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2205): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2205): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2205): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2205): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2205): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2205): [SmartShareManagerClient] unregisterListener: 427226885
W/SmartShareClient( 2205): [SmartShareManagerClient] unregisterListener invalid listener: 427226885
I/SmartShareClient( 2205): [SmartShareManagerClient] terminate service: 2205/MediaPlaybackService/733028384
E/HomeCloudIF( 2205): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2205): [SmartShareManagerClient] unbindService context:android.app.Application@29c8e35a
,V/CloudHub( 2205): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2205): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2205): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2205): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/CloudHub( 2205): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29998
,I/ActivityManager( 1047): Killing 6229:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1047): failed to open /acct/uid_1000/pid_6229/cgroup.procs: No such file or directory
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6658): Authentication error
E/BooksAccountManager( 6658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6658): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6658): null auth token
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6658): Error response from books API: {
W/ApiaryClient( 6658):  "error": {
W/ApiaryClient( 6658):   "errors": [
W/ApiaryClient( 6658):    {
W/ApiaryClient( 6658):     "domain": "global",
W/ApiaryClient( 6658):     "reason": "required",
W/ApiaryClient( 6658):     "message": "Login Required",
W/ApiaryClient( 6658):     "locationType": "header",
W/ApiaryClient( 6658):     "location": "Authorization"
W/ApiaryClient( 6658):    }
W/ApiaryClient( 6658):   ],
W/ApiaryClient( 6658):   "code": 401,
W/ApiaryClient( 6658):   "message": "Login Required"
W/ApiaryClient( 6658):  }
W/ApiaryClient( 6658): }
W/ApiaryClient( 6658): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6916478291192112822&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6658): Headers:
W/ApiaryClient( 6658): accept-encoding: [gzip]
W/ApiaryClient( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6658): gdata-version: 2
,E/BooksSync( 6658): Soft error: 
E/BooksSync( 6658): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6916478291192112822&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6658): Headers:
E/BooksSync( 6658): accept-encoding: [gzip]
E/BooksSync( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6658): gdata-version: 2
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6658): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6658): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6658): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6658): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6658): {
E/BooksSync( 6658):  "error": {
E/BooksSync( 6658):   "errors": [
E/BooksSync( 6658):    {
E/BooksSync( 6658):     "domain": "global",
E/BooksSync( 6658):     "reason": "required",
E/BooksSync( 6658):     "message": "Login Required",
E/BooksSync( 6658):     "locationType": "header",
E/BooksSync( 6658):     "location": "Authorization"
E/BooksSync( 6658):    }
E/BooksSync( 6658):   ],
E/BooksSync( 6658):   "code": 401,
E/BooksSync( 6658):   "message": "Login Required"
E/BooksSync( 6658):  }
E/BooksSync( 6658): }
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6658): 	... 8 more
E/BooksSync( 6658): Sync error
E/BooksSync( 6658): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6916478291192112822&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6658): Headers:
E/BooksSync( 6658): accept-encoding: [gzip]
E/BooksSync( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6658): gdata-version: 2
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6658): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.NetworkTaskQ,ueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6658): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6658): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6658): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6658): {
E/BooksSync( 6658):  "error": {
E/BooksSync( 6658):   "errors": [
E/BooksSync( 6658):    {
E/BooksSync( 6658):     "domain": "global",
E/BooksSync( 6658):     "reason": "required",
E/BooksSync( 6658):     "message": "Login Required",
E/BooksSync( 6658):     "locationType": "header",
E/BooksSync( 6658):     "location": "Authorization"
E/BooksSync( 6658):    }
E/BooksSync( 6658):   ],
E/BooksSync( 6658):   "code": 401,
E/BooksSync( 6658):   "message": "Login Required"
E/BooksSync( 6658):  }
E/BooksSync( 6658): }
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6658): 	... 8 more
I/BooksSync( 6658): Finished books sync
,I/ActivityManager( 1047): Killing 6330:com.lge.bnr/1000 (adj 15): empty #17
,D/SyncManager( 1047): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 78880, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1047): failed to open /acct/uid_1000/pid_6330/cgroup.procs: No such file or directory
I/GAV2    ( 6658): Thread[GAThread,5,main]: No campaign data found.
,I/CloudHub( 2205): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19988
,V/AlarmManager( 1047): RTC_WAKEUP set : Alarm{3a8b2c12 type 0 when 1456940242076 com.android.vending} when 1456940242076
,W/ContextImpl( 4561): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6251): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6251): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6251): [1] 5.onFinished: Scheduling replication attempt 2.
D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 118028040271; DSPS: 4008432; Offset : -4313275377
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1458): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1458): onReceive = android.intent.action.BATTERY_CHANGED
,D/WifiController( 1047): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1458): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1955): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1955): Battery Level Remaining: 100%
D/LEDHandler( 1955): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3859): Disconnected process message: 10, size: 0
D/LGDMClient( 4377): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4377): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{1c3e5ca4 type 2 when 134728 android} when 134728
,I/CloudHub( 2205): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2205): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 138029820806; DSPS: 4663850; Offset : -4313266815
,V/AlarmManager( 1047): RTC_WAKEUP set : Alarm{14f2bdc2 type 0 when 1456940269458 com.android.vending} when 1456940269458
,V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6251): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6251): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6251): [1] 5.onFinished: Scheduling replication attempt 3.
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 158032173072; DSPS: 5319287; Offset : -4313264715
,D/PowerManagerServiceEx( 1047): acquireWakeLockInternal: lock=430882898, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1047
,V/AlarmManager( 1047): RTC_WAKEUP set : Alarm{bb8207d type 0 when 1456940300017 com.android.vending} when 1456940300017
,D/[Concierge]Service( 2594): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1047): releaseWakeLockInternal: lock=430882898 [*alarm*], flags=0x0
,V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6251): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6251): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6251): [1] 5.onFinished: Scheduling replication attempt 4.
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{6fe2517 type 2 when 172014 android} when 172014
,I/art     ( 1047): Explicit concurrent mark sweep GC freed 26212(1174KB) AllocSpace objects, 7(630KB) LOS objects, 33% free, 44MB/66MB, paused 2.974ms total 145.213ms
,I/BooksSync( 6658): Starting books sync
,D/BooksSync( 6658): started syncMyEbooks
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6658): Authentication error
E/BooksAccountManager( 6658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6658): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6658): null auth token
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6658): Error response from books API: {
W/ApiaryClient( 6658):  "error": {
W/ApiaryClient( 6658):   "errors": [
W/ApiaryClient( 6658):    {
W/ApiaryClient( 6658):     "domain": "global",
W/ApiaryClient( 6658):     "reason": "required",
W/ApiaryClient( 6658):     "message": "Login Required",
W/ApiaryClient( 6658):     "locationType": "header",
W/ApiaryClient( 6658):     "location": "Authorization"
W/ApiaryClient( 6658):    }
W/ApiaryClient( 6658):   ],
W/ApiaryClient( 6658):   "code": 401,
W/ApiaryClient( 6658):   "message": "Login Required"
W/ApiaryClient( 6658):  }
W/ApiaryClient( 6658): }
W/ApiaryClient( 6658): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5986827755555110354&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6658): Headers:
W/ApiaryClient( 6658): accept-encoding: [gzip]
W/ApiaryClient( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6658): gdata-version: 2
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6658): Authentication error
E/BooksAccountManager( 6658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6658): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6658): null auth token
,D/QuickStatusbarLayout( 1405): Notification difference=198
,D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6658): Error response from books API: {
W/ApiaryClient( 6658):  "error": {
W/ApiaryClient( 6658):   "errors": [
W/ApiaryClient( 6658):    {
W/ApiaryClient( 6658):     "domain": "global",
W/ApiaryClient( 6658):     "reason": "required",
W/ApiaryClient( 6658):     "message": "Login Required",
W/ApiaryClient( 6658):     "locationType": "header",
W/ApiaryClient( 6658):     "location": "Authorization"
W/ApiaryClient( 6658):    }
W/ApiaryClient( 6658):   ],
W/ApiaryClient( 6658):   "code": 401,
W/ApiaryClient( 6658):   "message": "Login Required"
W/ApiaryClient( 6658):  }
W/ApiaryClient( 6658): }
W/ApiaryClient( 6658): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5986827755555110354&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6658): Headers:
W/ApiaryClient( 6658): accept-encoding: [gzip]
W/ApiaryClient( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6658): gdata-version: 2
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6658): Authentication error
E/BooksAccountManager( 6658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6658): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6658): null auth token
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6658): Error response from books API: {
W/ApiaryClient( 6658):  "error": {
W/ApiaryClient( 6658):   "errors": [
W/ApiaryClient( 6658):    {
W/ApiaryClient( 6658):     "domain": "global",
W/ApiaryClient( 6658):     "reason": "required",
W/ApiaryClient( 6658):     "message": "Login Required",
W/ApiaryClient( 6658):     "locationType": "header",
W/ApiaryClient( 6658):     "location": "Authorization"
W/ApiaryClient( 6658):    }
W/ApiaryClient( 6658):   ],
W/ApiaryClient( 6658):   "code": 401,
W/ApiaryClient( 6658):   "message": "Login Required"
W/ApiaryClient( 6658):  }
W/ApiaryClient( 6658): }
W/ApiaryClient( 6658): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5986827755555110354&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6658): Headers:
W/ApiaryClient( 6658): accept-encoding: [gzip]
W/ApiaryClient( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6658): gdata-version: 2
,E/BooksSync( 6658): Soft error: 
E/BooksSync( 6658): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5986827755555110354&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6658): Headers:
E/BooksSync( 6658): accept-encoding: [gzip]
E/BooksSync( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6658): gdata-version: 2
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6658): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6658): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6658): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6658): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6658): {
E/BooksSync( 6658):  "error": {
E/BooksSync( 6658):   "errors": [
E/BooksSync( 6658):    {
E/BooksSync( 6658):     "domain": "global",
E/BooksSync( 6658):     "reason": "required",
E/BooksSync( 6658):     "message": "Login Required",
E/BooksSync( 6658):     "locationType": "header",
E/BooksSync( 6658):     "location": "Authorization"
E/BooksSync( 6658):    }
E/BooksSync( 6658):   ],
E/BooksSync( 6658):   "code": 401,
E/BooksSync( 6658):   "message": "Login Required"
E/BooksSync( 6658):  }
E/BooksSync( 6658): }
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6658): 	... 8 more
,E/BooksSync( 6658): Sync error
E/BooksSync( 6658): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5986827755555110354&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6658): Headers:
E/BooksSync( 6658): accept-encoding: [gzip]
E/BooksSync( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6658): gdata-version: 2
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6658): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6658): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6658): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6658): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6658): {
E/BooksSync( 6658):  "error": {
E/BooksSync( 6658):   "errors": [
E/BooksSync( 6658):    {
E/BooksSync( 6658):     "domain": "global",
E/BooksSync( 6658):     "reason": "required",
E/BooksSync( 6658):     "message": "Login Required",
E/BooksSync( 6658):     "locationType": "header",
E/BooksSync( 6658):     "location": "Authorization"
E/BooksSync( 6658):    }
E/BooksSync( 6658):   ],
E/BooksSync( 6658):   "code": 401,
E/BooksSync( 6658):   "message": "Login Required"
E/BooksSync( 6658):  }
E/BooksSync( 6658): }
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6658): 	... 8 more
I/BooksSync( 6658): Finished books sync
,D/SyncManager( 1047): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 172014, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 178033826860; DSPS: 5974701; Offset : -4313258512
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1458): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1458): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1955): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1955): Battery Level Remaining: 100%
D/LEDHandler( 1955): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/WifiController( 1047): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1458): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3859): Disconnected process message: 10, size: 0
D/LGDMClient( 4377): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4377): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,V/AlarmManager( 1047): RTC_WAKEUP set : Alarm{4334f93 type 0 when 1456940320757 com.android.vending} when 1456940320757
,V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6251): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6251): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6251): [1] 5.onFinished: Scheduling replication attempt 5.
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 198035498537; DSPS: 6630116; Offset : -4313265405
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{841123d type 2 when 202205 android} when 202205
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 218037185687; DSPS: 7285531; Offset : -4313257061
,D/PowerManagerServiceEx( 1047): acquireWakeLockInternal: lock=430882898, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1047
,V/AlarmManager( 1047): RTC_WAKEUP set : Alarm{201f4383 type 0 when 1456940342374 com.android.vending} when 1456940342374
,D/[Concierge]Service( 2594): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1047): releaseWakeLockInternal: lock=430882898 [*alarm*], flags=0x0
,V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6251): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6251): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6251): [1] 5.onFinished: Giving up after 6 failures.
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{2f8004ad type 2 when 186156 com.google.android.gms} when 186156
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{5bce3e2 type 2 when 187767 android} when 187767
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2127): Vacuum at: now=1456940362986 tag=VacuumService
,I/GoogleURLConnFactory( 2127): Using platform SSLCertificateSocketFactory
,W/Uploader( 2127): No account for auth token provided
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  315): res_queryN name = play.googleapis.com succeed
,W/Uploader( 2127): No account for auth token provided
,W/Uploader( 2127): No account for auth token provided
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{7bcbf63 type 2 when 232231 android} when 232231
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
E/Uploader( 2127): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 2127): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 2127): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 2127): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 2127): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 2127): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 2127): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 2127): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 2127): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 2127): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/Uploader( 2127): No account for auth token provided
,W/Uploader( 2127):  no longer exists, so no auth token.
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 238038861938; DSPS: 7940946; Offset : -4313259094
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 258040951313; DSPS: 8596375; Offset : -4313275250
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 278042608106; DSPS: 9251789; Offset : -4313266510
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 298044223686; DSPS: 9907202; Offset : -4313268674
,D/PowerManagerServiceEx( 1047): acquireWakeLockInternal: lock=430882898, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1047
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{331eebf type 2 when 301443 android} when 301443
D/[Concierge]Service( 2594): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1047): releaseWakeLockInternal: lock=430882898 [*alarm*], flags=0x0
,I/BooksSync( 6658): Starting books sync
,D/BooksSync( 6658): started syncMyEbooks
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6658): Authentication error
E/BooksAccountManager( 6658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6658): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6658): null auth token
,D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6658): Error response from books API: {
W/ApiaryClient( 6658):  "error": {
W/ApiaryClient( 6658):   "errors": [
W/ApiaryClient( 6658):    {
W/ApiaryClient( 6658):     "domain": "global",
W/ApiaryClient( 6658):     "reason": "required",
W/ApiaryClient( 6658):     "message": "Login Required",
W/ApiaryClient( 6658):     "locationType": "header",
W/ApiaryClient( 6658):     "location": "Authorization"
W/ApiaryClient( 6658):    }
W/ApiaryClient( 6658):   ],
W/ApiaryClient( 6658):   "code": 401,
W/ApiaryClient( 6658):   "message": "Login Required"
W/ApiaryClient( 6658):  }
W/ApiaryClient( 6658): }
,W/ApiaryClient( 6658): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6142678977534770804&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6658): Headers:
W/ApiaryClient( 6658): accept-encoding: [gzip]
W/ApiaryClient( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6658): gdata-version: 2
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6658): Authentication error
E/BooksAccountManager( 6658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6658): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6658): null auth token
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6658): Error response from books API: {
W/ApiaryClient( 6658):  "error": {
W/ApiaryClient( 6658):   "errors": [
W/ApiaryClient( 6658):    {
W/ApiaryClient( 6658):     "domain": "global",
W/ApiaryClient( 6658):     "reason": "required",
W/ApiaryClient( 6658):     "message": "Login Required",
W/ApiaryClient( 6658):     "locationType": "header",
W/ApiaryClient( 6658):     "location": "Authorization"
W/ApiaryClient( 6658):    }
W/ApiaryClient( 6658):   ],
W/ApiaryClient( 6658):   "code": 401,
W/ApiaryClient( 6658):   "message": "Login Required"
W/ApiaryClient( 6658):  }
W/ApiaryClient( 6658): }
W/ApiaryClient( 6658): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6142678977534770804&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6658): Headers:
W/ApiaryClient( 6658): accept-encoding: [gzip]
W/ApiaryClient( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6658): gdata-version: 2
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2127): Explicit concurrent mark sweep GC freed 48220(2MB) AllocSpace objects, 21(2MB) LOS objects, 51% free, 30MB/62MB, paused 2.135ms total 62.600ms
,I/art     ( 1047): Explicit concurrent mark sweep GC freed 26657(1150KB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/66MB, paused 2.251ms total 134.844ms
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6658): Authentication error
E/BooksAccountManager( 6658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6658): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6658): null auth token
,D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6658): Error response from books API: {
W/ApiaryClient( 6658):  "error": {
W/ApiaryClient( 6658):   "errors": [
W/ApiaryClient( 6658):    {
W/ApiaryClient( 6658):     "domain": "global",
W/ApiaryClient( 6658):     "reason": "required",
W/ApiaryClient( 6658):     "message": "Login Required",
W/ApiaryClient( 6658):     "locationType": "header",
W/ApiaryClient( 6658):     "location": "Authorization"
W/ApiaryClient( 6658):    }
W/ApiaryClient( 6658):   ],
W/ApiaryClient( 6658):   "code": 401,
W/ApiaryClient( 6658):   "message": "Login Required"
W/ApiaryClient( 6658):  }
W/ApiaryClient( 6658): }
W/ApiaryClient( 6658): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6142678977534770804&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6658): Headers:
W/ApiaryClient( 6658): accept-encoding: [gzip]
W/ApiaryClient( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6658): gdata-version: 2
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1047): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1458): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1458): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1955): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1955): Battery Level Remaining: 100%
D/LEDHandler( 1955): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3859): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1458): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4377): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4377): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,E/BooksSync( 6658): Soft error: 
E/BooksSync( 6658): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6142678977534770804&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6658): Headers:
E/BooksSync( 6658): accept-encoding: [gzip]
E/BooksSync( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6658): gdata-version: 2
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6658): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6658): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6658): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6658): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6658): {
E/BooksSync( 6658):  "error": {
E/BooksSync( 6658):   "errors": [
E/BooksSync( 6658):    {
E/BooksSync( 6658):     "domain": "global",
E/BooksSync( 6658):     "reason": "required",
E/BooksSync( 6658):     "message": "Login Required",
E/BooksSync( 6658):     "locationType": "header",
E/BooksSync( 6658):     "location": "Authorization"
E/BooksSync( 6658):    }
E/BooksSync( 6658):   ],
E/BooksSync( 6658):   "code": 401,
E/BooksSync( 6658):   "message": "Login Required"
E/BooksSync( 6658):  }
E/BooksSync( 6658): }
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6658): 	... 8 more
,E/BooksSync( 6658): Sync error
E/BooksSync( 6658): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6142678977534770804&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6658): Headers:
E/BooksSync( 6658): accept-encoding: [gzip]
E/BooksSync( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6658): gdata-version: 2
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6658): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6658): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6658): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6658): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6658): {
E/BooksSync( 6658):  "error": {
E/BooksSync( 6658):   "errors": [
E/BooksSync( 6658):    {
E/BooksSync( 6658):     "domain": "global",
E/BooksSync( 6658):     "reason": "required",
E/BooksSync( 6658):     "message": "Login Required",
E/BooksSync( 6658):     "locationType": "header",
E/BooksSync( 6658):     "location": "Authorization"
E/BooksSync( 6658):    }
E/BooksSync( 6658):   ],
E/BooksSync( 6658):   "code": 401,
E/BooksSync( 6658):   "message": "Login Required"
E/BooksSync( 6658):  }
E/BooksSync( 6658): }
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6658): 	... 8 more
I/BooksSync( 6658): Finished books sync
,D/SyncManager( 1047): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 301443, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 318045879921; DSPS: 10562616; Offset : -4313260389
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/PowerManagerServiceEx( 1047): acquireWakeLockInternal: lock=430882898, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1047
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{1f19b831 type 2 when 331580 android} when 331580
D/[Concierge]Service( 2594): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1047): releaseWakeLockInternal: lock=430882898 [*alarm*], flags=0x0
,I/LocationManagerService( 1047): remove 11f2edb7
D/LocationManagerService( 1047): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService( 1047): getAllProviders()=[passive, gps, network]
D/LocationManagerService( 1047): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService( 1047): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService( 1047): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 338047531697; DSPS: 11218030; Offset : -4313256093
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 358049152040; DSPS: 11873443; Offset : -4313253104
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ResourcesManager( 1405): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1405): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/PlayEventLogger( 6251): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6251): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6251): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6251): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6251): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6251): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6251): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
W/ResourcesManager( 1405): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
,W/ResourcesManager( 1405): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6251): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com succeed
D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 378050803189; DSPS: 12528857; Offset : -4313250165
,D/PowerManagerServiceEx( 1047): acquireWakeLockInternal: lock=430882898, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1047
,D/[Concierge]Service( 2594): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/PowerManagerServiceEx( 1047): releaseWakeLockInternal: lock=430882898 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 398052483304; DSPS: 13184273; Offset : -4313278982
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 418054098252; DSPS: 13839685; Offset : -4313251260
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 438055574452; DSPS: 14495094; Offset : -4313269953
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 458057231180; DSPS: 15150508; Offset : -4313261590
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 478058756121; DSPS: 15805918; Offset : -4313262346
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 498061077688; DSPS: 16461354; Offset : -4313259934
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 518062710781; DSPS: 17116768; Offset : -4313274893
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 538064234571; DSPS: 17772178; Offset : -4313277347
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1047): battery changed pluggedType: 2
D/LEDHandler( 1955): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1955): Battery Level Remaining: 100%
D/LEDHandler( 1955): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3859): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1458): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1458): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1458): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4377): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4377): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/PowerManagerServiceEx( 1047): acquireWakeLockInternal: lock=430882898, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1047
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{32db8dab type 2 when 556514 android} when 556514
D/[Concierge]Service( 2594): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1047): releaseWakeLockInternal: lock=430882898 [*alarm*], flags=0x0
,I/BooksSync( 6658): Starting books sync
,D/BooksSync( 6658): started syncMyEbooks
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6658): Authentication error
E/BooksAccountManager( 6658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6658): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6658): null auth token
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6658): Error response from books API: {
W/ApiaryClient( 6658):  "error": {
W/ApiaryClient( 6658):   "errors": [
W/ApiaryClient( 6658):    {
W/ApiaryClient( 6658):     "domain": "global",
W/ApiaryClient( 6658):     "reason": "required",
W/ApiaryClient( 6658):     "message": "Login Required",
W/ApiaryClient( 6658):     "locationType": "header",
W/ApiaryClient( 6658):     "location": "Authorization"
W/ApiaryClient( 6658):    }
W/ApiaryClient( 6658):   ],
W/ApiaryClient( 6658):   "code": 401,
W/ApiaryClient( 6658):   "message": "Login Required"
W/ApiaryClient( 6658):  }
W/ApiaryClient( 6658): }
W/ApiaryClient( 6658): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2299369094591158067&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6658): Headers:
W/ApiaryClient( 6658): accept-encoding: [gzip]
W/ApiaryClient( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6658): gdata-version: 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 558065858387; DSPS: 18427591; Offset : -4313270806
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6658): Authentication error
E/BooksAccountManager( 6658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6658): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6658): null auth token
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6658): Error response from books API: {
W/ApiaryClient( 6658):  "error": {
W/ApiaryClient( 6658):   "errors": [
W/ApiaryClient( 6658):    {
W/ApiaryClient( 6658):     "domain": "global",
W/ApiaryClient( 6658):     "reason": "required",
W/ApiaryClient( 6658):     "message": "Login Required",
W/ApiaryClient( 6658):     "locationType": "header",
W/ApiaryClient( 6658):     "location": "Authorization"
W/ApiaryClient( 6658):    }
W/ApiaryClient( 6658):   ],
W/ApiaryClient( 6658):   "code": 401,
W/ApiaryClient( 6658):   "message": "Login Required"
W/ApiaryClient( 6658):  }
W/ApiaryClient( 6658): }
,W/ApiaryClient( 6658): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2299369094591158067&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6658): Headers:
W/ApiaryClient( 6658): accept-encoding: [gzip]
W/ApiaryClient( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6658): gdata-version: 2
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6658): Authentication error
E/BooksAccountManager( 6658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6658): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6658): null auth token
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6658): Error response from books API: {
W/ApiaryClient( 6658):  "error": {
W/ApiaryClient( 6658):   "errors": [
W/ApiaryClient( 6658):    {
W/ApiaryClient( 6658):     "domain": "global",
W/ApiaryClient( 6658):     "reason": "required",
W/ApiaryClient( 6658):     "message": "Login Required",
W/ApiaryClient( 6658):     "locationType": "header",
W/ApiaryClient( 6658):     "location": "Authorization"
W/ApiaryClient( 6658):    }
W/ApiaryClient( 6658):   ],
W/ApiaryClient( 6658):   "code": 401,
W/ApiaryClient( 6658):   "message": "Login Required"
W/ApiaryClient( 6658):  }
W/ApiaryClient( 6658): }
W/ApiaryClient( 6658): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2299369094591158067&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6658): Headers:
W/ApiaryClient( 6658): accept-encoding: [gzip]
W/ApiaryClient( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6658): gdata-version: 2
,E/BooksSync( 6658): Soft error: 
E/BooksSync( 6658): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2299369094591158067&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6658): Headers:
E/BooksSync( 6658): accept-encoding: [gzip]
E/BooksSync( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6658): gdata-version: 2
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6658): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6658): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6658): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6658): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6658): {
E/BooksSync( 6658):  "error": {
E/BooksSync( 6658):   "errors": [
E/BooksSync( 6658):    {
E/BooksSync( 6658):     "domain": "global",
E/BooksSync( 6658):     "reason": "required",
E/BooksSync( 6658):     "message": "Login Required",
E/BooksSync( 6658):     "locationType": "header",
E/BooksSync( 6658):     "location": "Authorization"
E/BooksSync( 6658):    }
E/BooksSync( 6658):   ],
E/BooksSync( 6658):   "code": 401,
E/BooksSync( 6658):   "message": "Login Required"
E/BooksSync( 6658):  }
E/BooksSync( 6658): }
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6658): 	... 8 more
,E/BooksSync( 6658): Sync error
E/BooksSync( 6658): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2299369094591158067&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6658): Headers:
E/BooksSync( 6658): accept-encoding: [gzip]
E/BooksSync( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6658): gdata-version: 2
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6658): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6658): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6658): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6658): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6658): {
E/BooksSync( 6658):  "error": {
E/BooksSync( 6658):   "errors": [
E/BooksSync( 6658):    {
E/BooksSync( 6658):     "domain": "global",
E/BooksSync( 6658):     "reason": "required",
E/BooksSync( 6658):     "message": "Login Required",
E/BooksSync( 6658):     "locationType": "header",
E/BooksSync( 6658):     "location": "Authorization"
E/BooksSync( 6658):    }
E/BooksSync( 6658):   ],
E/BooksSync( 6658):   "code": 401,
E/BooksSync( 6658):   "message": "Login Required"
E/BooksSync( 6658):  }
E/BooksSync( 6658): }
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6658): 	... 8 more
I/BooksSync( 6658): Finished books sync
,D/SyncManager( 1047): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 556514, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/PowerManagerServiceEx( 1047): acquireWakeLockInternal: lock=430882898, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1047
,I/ActivityManager( 1047): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6976 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2594): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 6976): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6976): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@8f6b323
,D/PowerManagerServiceEx( 1047): releaseWakeLockInternal: lock=430882898 [*alarm*], flags=0x0
I/ActivityManager( 1047): Killing 6402:com.google.android.talk/u0a72 (adj 15): empty #17
,W/libprocessgroup( 1047): failed to open /acct/uid_10072/pid_6402/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 578067558751; DSPS: 19083007; Offset : -4313279322
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{108a35bd type 2 when 586682 android} when 586682
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 598069186313; DSPS: 19738420; Offset : -4313269244
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 618070694252; DSPS: 20393830; Offset : -4313287132
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 638072301880; DSPS: 21049242; Offset : -4313266236
,D/PowerManagerServiceEx( 1047): acquireWakeLockInternal: lock=430882898, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1047
,D/[Concierge]Service( 2594): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1047): releaseWakeLockInternal: lock=430882898 [*alarm*], flags=0x0
,I/ActivityManager( 1047): Killing 6058:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1047): failed to open /acct/uid_10011/pid_6058/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 658073925203; DSPS: 21704655; Offset : -4313260500
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1047): battery changed pluggedType: 2
D/HeadsetStateMachine( 3859): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1458): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1458): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1955): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1955): Battery Level Remaining: 100%
D/LEDHandler( 1955): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1458): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4377): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4377): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 678075477732; DSPS: 22360066; Offset : -4313264212
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 698077067185; DSPS: 23015478; Offset : -4313261934
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 718078732058; DSPS: 23670893; Offset : -4313275579
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 738080902108; DSPS: 24326324; Offset : -4313271991
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 758082544547; DSPS: 24981738; Offset : -4313277475
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 778084103931; DSPS: 25637149; Offset : -4313274878
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 798085582564; DSPS: 26292557; Offset : -4313260932
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 818087252843; DSPS: 26947972; Offset : -4313268834
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 838088751357; DSPS: 27603381; Offset : -4313266098
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 858090872907; DSPS: 28258811; Offset : -4313280362
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 878092545741; DSPS: 28914225; Offset : -4313255478
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 898094081081; DSPS: 29569636; Offset : -4313276897
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 918095607149; DSPS: 30225046; Offset : -4313276474
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 938097313312; DSPS: 30880462; Offset : -4313279479
,D/PowerManagerServiceEx( 1047): acquireWakeLockInternal: lock=430882898, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1047
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{3466a7b2 type 2 when 943613 com.android.bluetooth} when 943613
,W/bt-smp  ( 3859): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3859): Plain text(LSB ~ MSB) = 65 c8 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3859): Encrypted text(LSB ~ MSB) = f4 df 77 02 46 1d 2e 53 ef 46 51 d4 5e 50 4e 18 
W/bt-btm  ( 3859): Stopping oneshot timer
D/[Concierge]Service( 2594): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1047): releaseWakeLockInternal: lock=430882898 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 958099013824; DSPS: 31535877; Offset : -4313257459
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 978101218843; DSPS: 32191310; Offset : -4313279833
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 998102857115; DSPS: 32846723; Offset : -4313259304
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 1018104386930; DSPS: 33502134; Offset : -4313285965
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 1038105863135; DSPS: 34157542; Offset : -4313274472
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 1058107470752; DSPS: 34812954; Offset : -4313253822
,D/PowerManagerServiceEx( 1047): acquireWakeLockInternal: lock=430882898, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1047
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{3c79d303 type 2 when 1062546 android} when 1062546
D/[Concierge]Service( 2594): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1047): releaseWakeLockInternal: lock=430882898 [*alarm*], flags=0x0
,I/BooksSync( 6658): Starting books sync
,D/BooksSync( 6658): started syncMyEbooks
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6658): Authentication error
E/BooksAccountManager( 6658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6658): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6658): null auth token
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6658): Error response from books API: {
W/ApiaryClient( 6658):  "error": {
W/ApiaryClient( 6658):   "errors": [
W/ApiaryClient( 6658):    {
W/ApiaryClient( 6658):     "domain": "global",
W/ApiaryClient( 6658):     "reason": "required",
W/ApiaryClient( 6658):     "message": "Login Required",
W/ApiaryClient( 6658):     "locationType": "header",
W/ApiaryClient( 6658):     "location": "Authorization"
W/ApiaryClient( 6658):    }
W/ApiaryClient( 6658):   ],
W/ApiaryClient( 6658):   "code": 401,
W/ApiaryClient( 6658):   "message": "Login Required"
W/ApiaryClient( 6658):  }
W/ApiaryClient( 6658): }
W/ApiaryClient( 6658): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2379147651991772046&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6658): Headers:
W/ApiaryClient( 6658): accept-encoding: [gzip]
W/ApiaryClient( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6658): gdata-version: 2
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6658): Authentication error
E/BooksAccountManager( 6658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6658): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6658): null auth token
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6658): Error response from books API: {
W/ApiaryClient( 6658):  "error": {
W/ApiaryClient( 6658):   "errors": [
W/ApiaryClient( 6658):    {
W/ApiaryClient( 6658):     "domain": "global",
W/ApiaryClient( 6658):     "reason": "required",
W/ApiaryClient( 6658):     "message": "Login Required",
W/ApiaryClient( 6658):     "locationType": "header",
W/ApiaryClient( 6658):     "location": "Authorization"
W/ApiaryClient( 6658):    }
W/ApiaryClient( 6658):   ],
W/ApiaryClient( 6658):   "code": 401,
W/ApiaryClient( 6658):   "message": "Login Required"
W/ApiaryClient( 6658):  }
W/ApiaryClient( 6658): }
W/ApiaryClient( 6658): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2379147651991772046&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6658): Headers:
W/ApiaryClient( 6658): accept-encoding: [gzip]
W/ApiaryClient( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6658): gdata-version: 2
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6658): Authentication error
E/BooksAccountManager( 6658): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6658): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6658): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6658): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6658): null auth token
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{22ade486 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6658): Error response from books API: {
W/ApiaryClient( 6658):  "error": {
W/ApiaryClient( 6658):   "errors": [
W/ApiaryClient( 6658):    {
W/ApiaryClient( 6658):     "domain": "global",
W/ApiaryClient( 6658):     "reason": "required",
W/ApiaryClient( 6658):     "message": "Login Required",
W/ApiaryClient( 6658):     "locationType": "header",
W/ApiaryClient( 6658):     "location": "Authorization"
W/ApiaryClient( 6658):    }
W/ApiaryClient( 6658):   ],
W/ApiaryClient( 6658):   "code": 401,
W/ApiaryClient( 6658):   "message": "Login Required"
W/ApiaryClient( 6658):  }
W/ApiaryClient( 6658): }
W/ApiaryClient( 6658): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2379147651991772046&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6658): Headers:
W/ApiaryClient( 6658): accept-encoding: [gzip]
W/ApiaryClient( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6658): gdata-version: 2
,E/BooksSync( 6658): Soft error: 
E/BooksSync( 6658): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2379147651991772046&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6658): Headers:
E/BooksSync( 6658): accept-encoding: [gzip]
E/BooksSync( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6658): gdata-version: 2
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6658): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6658): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6658): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6658): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6658): {
E/BooksSync( 6658):  "error": {
E/BooksSync( 6658):   "errors": [
E/BooksSync( 6658):    {
E/BooksSync( 6658):     "domain": "global",
E/BooksSync( 6658):     "reason": "required",
E/BooksSync( 6658):     "message": "Login Required",
E/BooksSync( 6658):     "locationType": "header",
E/BooksSync( 6658):     "location": "Authorization"
E/BooksSync( 6658):    }
E/BooksSync( 6658):   ],
E/BooksSync( 6658):   "code": 401,
E/BooksSync( 6658):   "message": "Login Required"
E/BooksSync( 6658):  }
E/BooksSync( 6658): }
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6658): 	... 8 more
,E/BooksSync( 6658): Sync error
E/BooksSync( 6658): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6658): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2379147651991772046&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6658): Headers:
E/BooksSync( 6658): accept-encoding: [gzip]
,E/BooksSync( 6658): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6658): gdata-version: 2
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224),
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6658): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6658): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6658): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6658): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6658): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6658): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6658): {
E/BooksSync( 6658):  "error": {
E/BooksSync( 6658):   "errors": [
E/BooksSync( 6658):    {
E/BooksSync( 6658):     "domain": "global",
E/BooksSync( 6658):     "reason": "required",
E/BooksSync( 6658):     "message": "Login Required",
E/BooksSync( 6658):     "locationType": "header",
E/BooksSync( 6658):     "location": "Authorization"
E/BooksSync( 6658):    }
E/BooksSync( 6658):   ],
E/BooksSync( 6658):   "code": 401,
E/BooksSync( 6658):   "message": "Login Required"
E/BooksSync( 6658):  }
E/BooksSync( 6658): }
E/BooksSync( 6658): 
E/BooksSync( 6658): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6658): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6658): 	... 8 more
,I/BooksSync( 6658): Finished books sync
,D/SyncManager( 1047): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1062546, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 1078109070785; DSPS: 35468367; Offset : -4313271377
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{243dbc55 type 2 when 1093300 android} when 1093300
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 1098111375367; DSPS: 36123802; Offset : -4313255223
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 1118113057135; DSPS: 36779218; Offset : -4313282674
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 1138114608797; DSPS: 37434628; Offset : -4313256812
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 1158116087299; DSPS: 38090036; Offset : -4313243232
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated(),
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 1178117667237; DSPS: 38745448; Offset : -4313250130
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 1198119261903; DSPS: 39400861; Offset : -4313273026
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 1218120993938; DSPS: 40056278; Offset : -4313280545
,I/UsageStatsService( 1047): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
,I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 1238122926890; DSPS: 40711701; Offset : -4313269758
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 1258124641642; DSPS: 41367117; Offset : -4313264328
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 1278126670385; DSPS: 42022544; Offset : -4313279977
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 1298128595837; DSPS: 42677967; Offset : -4313277392
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 7126): 
D/AndroidRuntime( 7126): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7126): CheckJNI is OFF
D/AndroidRuntime( 7126): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1047): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1047): Killing 6583:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1047): WIN DEATH: Window{3e303bee u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1047): Client connection lost with reason: 4
W/PackageSettings( 1047): Skipping PackageSetting{15bcea57 com.example.hello/10319} due to missing metadata
D/InputDispatcher( 1047): Focus left window: Window{3e303bee u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher( 1047): Window went away: Window{3e303bee u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1047):   Force finishing activity ActivityRecord{215d0ecb u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  345): DFP En is all cleared set to be enabled
W/ActivityManager( 1047): Spurious death for ProcessRecord{3c69466a 6583:com.test.thalitest/u0a311}, curProc for 6583: null
I/ActivityManager( 1047): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1047):   Force finishing activity ActivityRecord{215d0ecb u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1047): Duplicate finish request for ActivityRecord{215d0ecb u0 com.test.thalitest/.MainActivity t4 f}
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{2607d86e co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2076): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2076): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2076): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{285cdb0f co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]Launcher.Model( 2076): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/ActionManagerService( 1910): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3804): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2076): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2076): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2076): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2076): [Launcher.java:1114:onPause()]onPause
I/[LGHome]GBoardWebView( 2076): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1910): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3804): handleMessage: what(1000) actionID(0x1000004)
D/KeyguardModel( 1458): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1047): Reconfiguring input devices.  changes=0x00000010
E/LGBluetoothAvrcpQcomAdapter( 3859): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3859): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2022): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3804): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/GeofencerStateMachine( 1824): Ignoring removeGeofence because network location is disabled.
W/System.err( 4561): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4561): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4561): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4561): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4561): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4561): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4561): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4561): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4561): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4561): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4561): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4561): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1047): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7156 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/KeyguardModel( 1458): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1458): createShortcutInfo...
I/[SystemUI]QSlideListController( 1458): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1458): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1458): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1458): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1458): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/SplitUIManager( 1876): split_name #11 / not available #0
D/SplitUIService( 1876): removed split : 
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1458): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1458): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1458): createShortcutInfo...
V/SIM_STK ( 1047): Menu title from STK is T-Mobile
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1458): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1458): createShortcutInfo...
D/KeyguardModel( 1458): handleShortcutListChanged...
D/SplitUIManager( 1876): split_name #11 / not available #0
I/SplitUIService( 1876): split app #11
D/KeyguardModel( 1458): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1458): createShortcutInfo...
D/KeyguardModel( 1458): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1458): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1458): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1458): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1458): createShortcutInfo...
D/KeyguardModel( 1458): handleShortcutListChanged...
I/art     ( 4610): Explicit concurrent mark sweep GC freed 16614(950KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 308us total 230.777ms
I/art     ( 1047): Explicit concurrent mark sweep GC freed 43539(2MB) AllocSpace objects, 17(1296KB) LOS objects, 33% free, 44MB/66MB, paused 2.015ms total 228.885ms
I/art     ( 1047): WaitForGcToComplete blocked for 199.723ms for cause Explicit
W/ResourcesManager( 7156): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/SIM_STK ( 1047): Menu title from STK is T-Mobile
V/SIM_STK ( 1047): Menu title from STK is T-Mobile
D/PluginManager( 7156): init()
I/art     ( 1047): Explicit concurrent mark sweep GC freed 1436(57KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.696ms total 78.309ms
D/administrator( 1047): Handling package changes for user 0
I/art     ( 1047): WaitForGcToComplete blocked for 303.000ms for cause Explicit
V/BoardContentProvider( 3804): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/SIM_STK ( 1047): Menu title from STK is T-Mobile
W/ActivityManager( 1047): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3859): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3859): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3859): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3859): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3859): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3859): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3859): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3859): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3859): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3859): [BTUI]          playState: 2 (PAUSED)
I/GBoardWebViewUtils( 2076): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2076): , create_time: 1430558575574
I/GBoardWebViewUtils( 2076): , expire_time: 0
I/GBoardWebViewUtils( 2076): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2076): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2076): , display: false
I/GBoardWebViewUtils( 2076): , animation: false }
D/LGBluetoothAvrcpQcomAdapter( 3859): [BTUI] [-] updateMediaPlayerInfo
I/GBoardWebViewUtils( 2076): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2076): , create_time: 1430558575600
I/GBoardWebViewUtils( 2076): , expire_time: 0
I/GBoardWebViewUtils( 2076): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2076): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2076): , display: false
I/GBoardWebViewUtils( 2076): , animation: false }
I/GBoardWebViewUtils( 2076): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1455195784986
I/GBoardWebViewUtils( 2076): , create_time: 1455195785688
I/GBoardWebViewUtils( 2076): , expire_time: 0
I/GBoardWebViewUtils( 2076): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2076): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2076): , display: false
I/GBoardWebViewUtils( 2076): , animation: false }
D/WallpaperManager( 2076): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/WindowManager( 1047): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
I/SystemUI[Framework]( 1047): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
I/[SystemUI]NavigationThemeResource( 1458): notify navigation bar color(0x0)
I/[SystemUI]NavigationThemeResource( 1458): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1458):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1458): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1047): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1047): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1047): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@302c33f9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher( 1047): Focus entered window: Window{263e33ca u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]GBoardWebView( 2076): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/NotificationService( 1047): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1047): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1047): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2076): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/TaskPersister( 1047): removeObsoleteFile: deleting file=4_task.xml
I/[LGHome]EVENT( 2076): [Launcher.java:5349:onStop()]onStop
I/[LGHome]EVENT( 2076): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 2076): [setNavigationBarColor] color=0x 0
D/[Concierge]WidgetView( 2076): notifyExtViewAvailable
D/InputMethodManagerService( 1047): setImestate : 0
W/InputMethodManagerService( 1047): Got RemoteException sending setActive(false) notification to pid 6583 uid 10311
I/art     ( 1047): Explicit concurrent mark sweep GC freed 5931(423KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.430ms total 129.132ms
I/ThermalEngine(  339): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3207): Thermal-Lib-Client: Client request sent
I/[LGHome]Launcher.Model( 2076): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/IInputConnectionWrapper( 2076): getTextBeforeCursor on inactive InputConnection
I/Timeline( 1047): Timeline: Activity_windows_visible id: ActivityRecord{8698d6e u0 com.lge.launcher2/.Launcher t3} time:1309956
E/b       ( 1692): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]Launcher.Model( 2076): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2076): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2076): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/AndroidRuntime( 7126): Shutting down VM
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 2076): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 2076): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2076): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2594): onStartCommand(). Type : 8
D/[Concierge]Service( 2594): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2594): Update widget ID : 11
D/[Concierge]WidgetView( 2076): change position of spinner
D/[Concierge]Service( 2594): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2076): initWebView(). Time : 1456941441597
I/[Concierge]WebView( 2076): Return exist ConciergeWebView. Reuse : 807195424
D/[Concierge]WidgetView( 2076): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2076): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2076): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1828a228
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2076): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2076): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2076): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2076): Widget kill message received. Destory myself. My : 1456940159852, New one : 1456941441597
D/[Concierge]WidgetView( 2076): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2076): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ExternalStrings( 7156): load override strings
W/ExternalStrings( 7156): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7156): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7156): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7156): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7156): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7156): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7156): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7156): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7156): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7156): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7156): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7156): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7156): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7156): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7156): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7156): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7156): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7156): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 7156): onCreate
W/ResourcesManager( 1047): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1047): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LgeWidgetLib]LgeAppWidgetHostView( 2076): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2076): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 2076): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
V/Signer  ( 7156): override build config not found
D/Signer  ( 7156): value of property debug is false
I/Timeline( 2076): Timeline: Activity_idle id: android.os.BinderProxy@16eb22d3 time:1310123
D/LGMDMWrapper( 7156): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7156): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7156): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7156): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7156): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7156): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7156): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7156): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7156): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7156): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7156): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7156): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7156): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 7156): Create singleton instance
D/LGMDMWrapper( 7156): LG MDM library v4.0.0 is available on this device.
D/PostponalbeReceiver( 7156): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/ContextImpl( 7156): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/ActivityManager( 1047): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7188 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager( 1047): Killing 6075:com.android.contacts/u0a19 (adj 15): empty #17
I/chromium( 2076): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
W/ActivityThread( 7156): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/GBoardtInterface( 2076): onReloaded()
I/GBoardWebViewClient( 2076): onPageFinished url:file:///android_asset/www/main.html
W/libprocessgroup( 1047): failed to open /acct/uid_10019/pid_6075/cgroup.procs: No such file or directory
V/BoardContentProvider( 3804): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3804): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1910): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3804): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3804): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1910): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3804): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3804): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3804): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3804): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3804): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2076): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2076): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2076): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2076): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2076): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2076): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
E/SQLiteDatabase( 7156): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7156): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7156): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7156): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.ConfigManager.ab(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.fw.ws.WSLicenseService.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.g.b.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7156): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7156): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7156): 	at com.mcafee.d.c.run(Unknown Source)
I/AppUp4:AppBoxCP( 7188): onCreate
W/AppUp4:DB( 7188):  [AppBoxDatabaseHelper] construct
E/SQLiteDatabase( 7188): Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
E/SQLiteDatabase( 7188): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7188): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7188): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7188): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7188): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7188): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7188): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7188): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7188): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7188): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7188): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/SQLiteDatabase( 7188): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7188): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7188): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7188): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7188): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7188): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7188): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7188): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7188): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7188): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7188): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7188): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7188): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7188): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/AndroidRuntime( 7188): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 7188): FATAL EXCEPTION: main
E/AndroidRuntime( 7188): Process: com.lge.appbox.client, PID: 7188
E/AndroidRuntime( 7188): java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7188): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
E/AndroidRuntime( 7188): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/AndroidRuntime( 7188): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/AndroidRuntime( 7188): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/AndroidRuntime( 7188): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/AndroidRuntime( 7188): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7188): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7188): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/AndroidRuntime( 7188): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7188): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7188): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/AndroidRuntime( 7188): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/AndroidRuntime( 7188): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7188): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 7188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 7188): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7188): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/AndroidRuntime( 7188): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/AndroidRuntime( 7188): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 7188): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/AndroidRuntime( 7188): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7188): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7188): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7188): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/AndroidRuntime( 7188): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 7188): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 7188): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/AndroidRuntime( 7188): 	... 11 more
I/Process ( 7188): Sending signal. PID: 7188 SIG: 9
E/DropBoxManagerService( 1047): Can't write: system_app_crash
E/DropBoxManagerService( 1047): java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1047): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1047): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1047): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1047): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1047): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1047): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1047): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1047): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1047): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1047): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1047): 	... 5 more
E/SQLiteDatabase( 7156): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
E/SQLiteDatabase( 7156): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7156): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7156): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7156): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7156): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7156): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7156): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteOpenHelper( 7156): Couldn't open lockedapplications for writing (will try read-only):
E/SQLiteOpenHelper( 7156): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7156): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 7156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 7156): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7156): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 7156): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 7156): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 7156): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 7156): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7156): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7156): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 7156): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteOpenHelper( 7156): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 7156): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 7156): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 7156): 	at com.mcafee.d.c.run(Unknown Source)
W/SQLiteOpenHelper( 7156): Opened lockedapplications in read-only mode
I/ActivityManager( 1047): Process com.lge.appbox.client (pid 7188) has died
E/SQLiteDatabase( 7156): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7156): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7156): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7156): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.notificationtray.e.<init>(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.notificationtray.e.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.notificationtray.NotificationComponent.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7156): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7156): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7156): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7156): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7156): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7156): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7156): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7156): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7156): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7156): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7156): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7156): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7156): 	at com.mcafee.d.c.run(Unknown Source)

```
