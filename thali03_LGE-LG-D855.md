#### Test 613623661dfc74c_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/AlertService( 6461): Beginning updateAlertNotification
D/AlertService( 6461): No fired or scheduled alerts
D/AlertService( 6461): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 6461): No events found starting within 1 week.
--------- beginning of system
I/ActivityManager( 1039): Killing 6136:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10061/pid_6136/cgroup.procs: No such file or directory
,E/ThermalEngine(  325): out low battery limit. 
D/AndroidRuntime( 6532): 
D/AndroidRuntime( 6532): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6532): CheckJNI is OFF
D/AndroidRuntime( 6532): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1039): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1952): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1039): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{d4f810e #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{d4f810e #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1039): AppWindowTokenEx init.. 
E/GBMv2   (  339): DFP En is all cleared set to be enabled
I/ActivityManager( 1039): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6547 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/InputDispatcher( 1039): Focus left window: Window{fd3884 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 2075): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/AndroidRuntime( 6532): Shutting down VM
I/art     (  343): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 269us total 32.513ms
I/art     (  343): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 253us total 14.483ms
I/art     (  343): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 434us total 31.782ms
V/ActivityManager( 1039): Display changed displayId=0
D/DSDPConnection( 1864): Display #0 changed.
D/SplitWindowPolicy( 1952): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1952): topRunningActivity=ActivityInfo{6217a3f co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3406a01a type 2 when 92329 com.google.android.gms} when 92329
D/SplitWindowPolicy( 1952): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1952): topRunningActivity=ActivityInfo{1b3a6f0c co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6547): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,I/WebViewFactory( 6547): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6547): Loading: webviewchromium
I/LibraryLoader( 6547): Time to load native libraries: 4 ms (timestamps 2487-2491)
I/LibraryLoader( 6547): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6547): Binding Chromium to main looper Looper (main, tid 1) {acf61bc}
,I/LibraryLoader( 6547): Expected native library version number "",actual native library version number ""
I/chromium( 6547): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6547): Initializing chromium process, renderers=0
W/art     ( 6547): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  316): registerClient() client 0xb558a2a0, uid 10311
,W/chromium( 6547): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6547): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6547): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1039): Message: 20
D/BluetoothManagerService( 1039): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39f87241:true
I/Adreno-EGL( 6547): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6547): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6547): Build Date: 12/12/14 금
I/Adreno-EGL( 6547): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6547): Remote Branch: 
I/Adreno-EGL( 6547): Local Patches: 
I/Adreno-EGL( 6547): Reconstruct Branch: 
,W/chromium( 6547): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6547): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6547): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6547): onDetachedFromWindow called when already detached. Ignoring
I/PhoneWindow( 6547): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 6547): [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 6547): [setNavigationBarColor2] color=0x fff5f5f5
,D/SystemWebViewEngine( 6547): CordovaWebView is running on device made by: LGE
,W/art     ( 6547): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6547): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6547): Render dirty regions requested: true
I/OpenGLRenderer( 6547): Initialized EGL, version 1.4
D/OpenGLRenderer( 6547): Enabling debug mode 0
,D/Atlas   ( 6547): Validating map...
D/SplitWindow( 1039): check instance of lgWin Window{3585f4b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6547): LgDataFeature() Constructor: none
D/LgDataFeature( 6547): LgDataFeature() Constructor Done, null
,D/WindowManager( 1039): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework]( 1039): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
I/[SystemUI]NavigationThemeResource( 1450): notify navigation bar color(0xfff5f5f5)
I/[SystemUI]NavigationThemeResource( 1450): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1450):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1450): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1039): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1039): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1039): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1b43af32,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher( 1039): Focus entered window: Window{3585f4b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputMethodManagerService( 1039): setImestate : 0
,I/ActivityManager( 1039): Displayed com.test.thalitest/.MainActivity: +540ms (total +686ms)
,I/Timeline( 1039): Timeline: Activity_windows_visible id: ActivityRecord{300672f u0 com.test.thalitest/.MainActivity t4} time:92885
,W/IInputConnectionWrapper( 6547): showStatusIcon on inactive InputConnection
,W/IInputConnectionWrapper( 6547): getTextBeforeCursor on inactive InputConnection
I/Timeline( 6547): Timeline: Activity_idle id: android.os.BinderProxy@3d6343bb time:92897
E/b       ( 1717): Unable to connect to the editor to retrieve text... will retry later
W/IInputConnectionWrapper( 6547): getTextAfterCursor on inactive InputConnection
,D/JsMessageQueue( 6547): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6547): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6547): 
,D/jxcore_app_log( 6547): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435200640
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6547): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6547):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6547):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6547):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6547):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6547): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e166e1c added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6547): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6547):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6547):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6547):     - Bluetooth MAC address: 58:3F:54:73:64:C0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6547):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6547):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6547):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6547):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6547):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6547):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6547): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@396891ab added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6547): addListener: New listener added - the number of listeners is now 1
D/WifiService( 1039): New client listening to asynchronous messages
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6547): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6547): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 6547): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 6547): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:84)
W/System.err( 6547): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 6547): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 6547): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 6547): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 6547): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 6547): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 6547): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 6547): 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 6547): 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
W/System.err( 6547): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6547): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6547): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 6547): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6547): load: Already loaded
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6547): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96b3a1 added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6547): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6547): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296bb9c6 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6547): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6547): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 6547): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 6547): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:84)
W/System.err( 6547): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 6547): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 6547): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 6547): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 6547): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 6547): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 6547): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 6547): 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 6547): 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
W/System.err( 6547): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6547): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6547): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/chromium( 6547): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6547): 
,E/GBMv2   (  339): DFP En is all cleared set to be enabled
,E/GBMv2   (  339): Set value is all cleared set the max
I/GBMv2   (  339): DFP Enabled. Ignore VFP set
,I/chromium( 6547): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 6547): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
I/rmt_storage(  308): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  308): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  308): wakelock acquired: 1, error no: 42
,I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  308): 
,I/rmt_storage(  308): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,E/Diag_Lib(  905): [IMS_FATAL]| 3347 | 918 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{b64cfa0 type 2 when 103499 android} when 103499
,I/ActivityManager( 1039): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6652 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 6652): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 6652): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6652): Created application version: 3.2.35 (30235)
,I/BooksSync( 6652): Starting books sync
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2118): innerSync failed
D/ContactsSyncAdapter( 2118): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2118): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2118): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2118): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2118): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2118): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2118): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2118): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2118): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2118): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2118): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 75672, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1039): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 167756, reason: 10019
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/BooksSync( 6652): started syncMyEbooks
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
E/HttpHelper( 6652): null auth token
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  312): res_queryN name = www.googleapis.com succeed
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
W/ApiaryClient( 6652): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7303880401112558243&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,I/MusicWidget( 2681): mDelayedStopHandler : unbind
,I/MusicBrowser( 2207): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2207): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2207): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2207): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2207): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2207): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,I/MusicBrowser( 2207): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2207): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1039):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3d6343bbcom.lge.music.MediaPlaybackService$5@3f8900d8
D/MusicBrowser( 2207): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2207): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2207): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2207): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2207): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@3fcdc0c1
I/MusicBrowser( 2207): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2207): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2207): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2207): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2207): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2207): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2207): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2207): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2207): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2207): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2207): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2207): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2207): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2207): reset
V/MediaPlayer[Native]( 2207): setListener
V/MediaPlayer[Native]( 2207): disconnect
V/MediaPlayer[Native]( 2207): destructor
,V/AudioFlinger(  316): releasing 13 from 2207 for -1
V/AudioFlinger(  316):  decremented refcount to 0
V/AudioFlinger(  316): purging stale effects
V/MediaPlayer[Native]( 2207): disconnect
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/MusicBrowser( 2207): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2207): [SmartShareManagerClient] smartshare client supported version code: 305000
,I/SmartShareClient( 2207): [SmartShareManagerClient] smartshare client enabled
,I/art     ( 2118): Explicit concurrent mark sweep GC freed 21323(1259KB) AllocSpace objects, 8(1152KB) LOS objects, 51% free, 30MB/62MB, paused 2.193ms total 53.481ms
I/MusicBrowser( 2207): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2207): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
,V/MusicBrowser( 2207): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2207): [SmartShareManagerClient] unregisterListener: 178740273
W/SmartShareClient( 2207): [SmartShareManagerClient] unregisterListener invalid listener: 178740273
I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SmartShareClient( 2207): [SmartShareManagerClient] terminate service: 2207/MediaPlaybackService/131910063
,E/HomeCloudIF( 2207): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2207): [SmartShareManagerClient] unbindService context:android.app.Application@63f5f16
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
,W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
V/CloudHub( 2207): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2207): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
I/CloudHub( 2207): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2207): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
I/ActivityManager( 1039): Killing 6242:com.lge.eula/1000 (adj 15): empty #17
I/CloudHub( 2207): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
,D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6242/cgroup.procs: No such file or directory
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
W/ApiaryClient( 6652): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7303880401112558243&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 18742(893KB) AllocSpace objects, 5(470KB) LOS objects, 33% free, 43MB/65MB, paused 2.843ms total 145.634ms
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
W/ApiaryClient( 6652): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7303880401112558243&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 107972581478; DSPS: 3678693; Offset : -4303676082
,E/BooksSync( 6652): Soft error: 
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7303880401112558243&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
E/BooksSync( 6652): Sync error
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7303880401112558243&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTas,kQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
I/BooksSync( 6652): Finished books sync
,I/ActivityManager( 1039): Killing 6336:com.lge.bnr/1000 (adj 15): empty #17
,D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 78485, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6336/cgroup.procs: No such file or directory
,I/GAV2    ( 6652): Thread[GAThread,5,main]: No campaign data found.
,I/CloudHub( 2207): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19982
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{25ad9e8c type 0 when 1456920208180 com.android.vending} when 1456920208180
,W/ContextImpl( 4536): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6265): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6265): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6265): [1] 5.onFinished: Scheduling replication attempt 2.
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 127974143407; DSPS: 4334104; Offset : -4303670835
,I/[SystemUI]LGPowerUI( 1450): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1450): On Skip Timer : true
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1039): battery changed pluggedType: 2
D/HeadsetStateMachine( 3849): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1450): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1450): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1952): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1952): Battery Level Remaining: 100%
D/LEDHandler( 1952): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1450): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4351): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4351): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{f61168e type 2 when 133620 android} when 133620
,I/CloudHub( 2207): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2207): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{2c1bc2bc type 0 when 1456920235485 com.android.vending} when 1456920235485
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6265): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6265): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6265): [1] 5.onFinished: Scheduling replication attempt 3.
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 147975599046; DSPS: 4989512; Offset : -4303679832
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=767640288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{3c62019f type 0 when 1456920260314 com.android.vending} when 1456920260314
,D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=767640288 [*alarm*], flags=0x0
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6265): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6265): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6265): [1] 5.onFinished: Scheduling replication attempt 4.
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 167976958584; DSPS: 5644916; Offset : -4303663042
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{1bd75d69 type 2 when 170690 android} when 170690
,I/BooksSync( 6652): Starting books sync
,D/BooksSync( 6652): started syncMyEbooks
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
W/ApiaryClient( 6652): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5700069068088048944&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5700069068088048944&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
,W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5700069068088048944&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,E/BooksSync( 6652): Soft error: 
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5700069068088048944&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
,E/BooksSync( 6652): Sync error
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5700069068088048944&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
I/BooksSync( 6652): Finished books sync
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 170690, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 187978464834; DSPS: 6300326; Offset : -4303682696
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{d135c05 type 0 when 1456920286007 com.android.vending} when 1456920286007
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6265): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6265): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6265): [1] 5.onFinished: Scheduling replication attempt 5.
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{1241e55f type 2 when 200754 android} when 200754
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
,I/[SystemUI]Clock( 1450): called onTimeUpdated()
I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 207979967274; DSPS: 6955735; Offset : -4303675670
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=767640288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{18fc5075 type 0 when 1456920307970 com.android.vending} when 1456920307970
,D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=767640288 [*alarm*], flags=0x0
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6265): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6265): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6265): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 227981451216; DSPS: 7611143; Offset : -4303656676
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 247982807203; DSPS: 8266548; Offset : -4303673590
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{2e54e44f type 2 when 185666 com.google.android.gms} when 185666
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3bcf77dc type 2 when 187655 android} when 187655
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2118): Vacuum at: now=1456920353196 tag=VacuumService
,I/GoogleURLConnFactory( 2118): Using platform SSLCertificateSocketFactory
,W/Uploader( 2118): No account for auth token provided
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  312): res_queryN name = play.googleapis.com succeed
,W/Uploader( 2118): No account for auth token provided
,W/Uploader( 2118): No account for auth token provided
,W/Uploader( 2118): No account for auth token provided
,W/Uploader( 2118):  no longer exists, so no auth token.
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
,I/[SystemUI]Clock( 1450): called onTimeUpdated()
I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 267984298882; DSPS: 8921957; Offset : -4303677532
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 287985726814; DSPS: 9577364; Offset : -4303683952
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=767640288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{267847e3 type 2 when 298568 android} when 298568
D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=767640288 [*alarm*], flags=0x0
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 32237(1357KB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 3.081ms total 142.469ms
,I/BooksSync( 6652): Starting books sync
,D/BooksSync( 6652): started syncMyEbooks
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1333666362636065366&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
W/ApiaryClient( 6652): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1333666362636065366&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
W/ApiaryClient( 6652): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1333666362636065366&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,E/BooksSync( 6652): Soft error: ,
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1333666362636065366&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
,E/BooksSync( 6652): Headers:,
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
,E/BooksSync( 6652): Sync error
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1333666362636065366&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
,E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054),
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
I/BooksSync( 6652): Finished books sync
,D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 298568, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 307987196456; DSPS: 10232772; Offset : -4303679050
,I/[SystemUI]LGPowerUI( 1450): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1450): On Skip Timer : true
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1039): battery changed pluggedType: 2
D/HeadsetStateMachine( 3849): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1450): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1450): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1952): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1952): Battery Level Remaining: 100%
D/LEDHandler( 1952): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1450): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4351): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4351): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 327988683070; DSPS: 10888181; Offset : -4303687980
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=767640288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{1d31fa35 type 2 when 328798 android} when 328798
D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=767640288 [*alarm*], flags=0x0
,I/LocationManagerService( 1039): remove 33b32c39
D/LocationManagerService( 1039): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService( 1039): getAllProviders()=[passive, gps, network]
D/LocationManagerService( 1039): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService( 1039): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService( 1039): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 347990918927; DSPS: 11543614; Offset : -4303679671
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 367992323585; DSPS: 12199020; Offset : -4303678822
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/ResourcesManager( 1404): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1404): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/PlayEventLogger( 6265): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6265): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6265): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6265): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6265): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6265): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6265): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,W/ResourcesManager( 1404): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1404): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6265): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  312): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  312): res_queryN name = play.googleapis.com succeed
I/[SystemUI]LGPowerUI( 1450): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1450): On Skip Timer : true
,D/WifiController( 1039): battery changed pluggedType: 2
,D/LEDHandler( 1952): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1952): Battery Level Remaining: 100%
D/LEDHandler( 1952): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1450): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/[SystemUI]LGPowerUI( 1450): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1450): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3849): Disconnected process message: 10, size: 0
,D/LGDMClient( 4351): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4351): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=767640288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=767640288 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 387993820145; DSPS: 12854429; Offset : -4303677910
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 407995261954; DSPS: 13509836; Offset : -4303670244
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 427996567608; DSPS: 14165239; Offset : -4303676741
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 447997994593; DSPS: 14820646; Offset : -4303684213
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 467999299070; DSPS: 15476048; Offset : -4303661346
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 488000594041; DSPS: 16131450; Offset : -4303648268
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 508002026336; DSPS: 16786858; Offset : -4303680895
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 528003336522; DSPS: 17442261; Offset : -4303682861
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 548004778297; DSPS: 18097668; Offset : -4303675386
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=767640288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{32ef80f type 2 when 550649 android} when 550649
D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=767640288 [*alarm*], flags=0x0
,I/BooksSync( 6652): Starting books sync
,D/BooksSync( 6652): started syncMyEbooks
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2118): Explicit concurrent mark sweep GC freed 51714(2MB) AllocSpace objects, 22(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.346ms total 41.016ms
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  312): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  312): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
W/ApiaryClient( 6652): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7993443819866631141&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
,D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
W/ApiaryClient( 6652): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7993443819866631141&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
W/ApiaryClient( 6652): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7993443819866631141&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,E/BooksSync( 6652): Soft error: 
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7993443819866631141&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],,
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
,E/BooksSync( 6652): Sync error
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7993443819866631141&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
,E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
,E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): ,	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
,I/BooksSync( 6652): Finished books sync
,D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 550649, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 568006299593; DSPS: 18753078; Offset : -4303679969
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=767640288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{2d899f01 type 2 when 580823 android} when 580823
D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=767640288 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 588007762372; DSPS: 19408486; Offset : -4303682085
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 608009137556; DSPS: 20063891; Offset : -4303680114
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 628011325653; DSPS: 20719322; Offset : -4303658766
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=767640288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=767640288 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 648012814727; DSPS: 21374731; Offset : -4303665262
,I/ActivityManager( 1039): Killing 5875:com.google.android.gm/u0a64 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10064/pid_5875/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 668014224342; DSPS: 22030138; Offset : -4303689868
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
,I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1450): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1450): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1450): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 264
I/[SystemUI]LGPowerUI( 1450): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1952): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1952): Battery Level Remaining: 100%
,D/LEDHandler( 1952): Battery Temp: 264, mChargingStatus=5, mChargingStop=false
D/WifiController( 1039): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1450): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3849): Disconnected process message: 10, size: 0
,D/LGDMClient( 4351): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED,
D/LGDMClient( 4351): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction,
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 688015696618; DSPS: 22685546; Offset : -4303682332
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 708017082910; DSPS: 23340951; Offset : -4303669410
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 728018479569; DSPS: 23996358; Offset : -4303707077
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 748019965829; DSPS: 24651766; Offset : -4303685609
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 768021371977; DSPS: 25307172; Offset : -4303683320
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 788022716787; DSPS: 25962576; Offset : -4303681467
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=767640288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,I/ActivityManager( 1039): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6960 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 6960): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6960): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@352ddd8e
D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=767640288 [*alarm*], flags=0x0
,I/ActivityManager( 1039): Killing 6371:com.google.android.talk/u0a72 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10072/pid_6371/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 808024265944; DSPS: 26617986; Offset : -4303658188
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 828025650422; DSPS: 27273392; Offset : -4303677232
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 848027008321; DSPS: 27928796; Offset : -4303662263
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 868028463051; DSPS: 28584204; Offset : -4303672376
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 888029787157; DSPS: 29239608; Offset : -4303691149
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 908031884549; DSPS: 29895036; Offset : -4303668821
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 928033340443; DSPS: 30550444; Offset : -4303677745
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=767640288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{dd131a6 type 2 when 943133 com.android.bluetooth} when 943133
,W/bt-smp  ( 3849): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3849): Plain text(LSB ~ MSB) = 94 81 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3849): Encrypted text(LSB ~ MSB) = 54 f8 b7 06 ab 29 b8 fb cc 24 d7 7c e4 1a aa bb 
W/bt-btm  ( 3849): Stopping oneshot timer
D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=767640288 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 948034738916; DSPS: 31205850; Offset : -4303683315
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 968036437159; DSPS: 31861266; Offset : -4303693562
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 988038155954; DSPS: 32516682; Offset : -4303684063
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1008040670598; DSPS: 33172125; Offset : -4303702456
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1028042508036; DSPS: 33827544; Offset : -4303665477
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=767640288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{2b96e7e7 type 2 when 962637 com.google.android.gms} when 962637
D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=767640288 [*alarm*], flags=0x0
,D/GCM     ( 2118): Message class com.google.f.a.a.i
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 30654(1359KB) AllocSpace objects, 9(1040KB) LOS objects, 33% free, 44MB/66MB, paused 1.920ms total 99.226ms
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
,I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1048043995247; DSPS: 34482953; Offset : -4303673680
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=767640288, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{a702a3d type 2 when 1050701 android} when 1050701
D/[Concierge]Service( 2597): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=767640288 [*alarm*], flags=0x0
,I/BooksSync( 6652): Starting books sync
,D/BooksSync( 6652): started syncMyEbooks
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  312): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1404): Notification difference=198
,D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  312): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
W/ApiaryClient( 6652): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3012893917786625379&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
W/ApiaryClient( 6652): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3012893917786625379&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{93bc34d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3012893917786625379&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,E/BooksSync( 6652): Soft error: 
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3012893917786625379&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
E/BooksSync( 6652): Sync error
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3012893917786625379&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	,at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): ,	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
,E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [,
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
,E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
,E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization",
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
,E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
,I/BooksSync( 6652): Finished books sync
,D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1050701, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1068045474401; DSPS: 35138362; Offset : -4303689835
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{e3446bf type 2 when 1080915 android} when 1080915
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1088046967768; DSPS: 35793770; Offset : -4303661390
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1108048455543; DSPS: 36449179; Offset : -4303668950
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1128049836773; DSPS: 37104584; Offset : -4303660725
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1148051834821; DSPS: 37760010; Offset : -4303676811
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,I/[SystemUI]DateView( 1450): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1168053228070; DSPS: 38415416; Offset : -4303687605
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1188054540701; DSPS: 39070819; Offset : -4303687152
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1208055905855; DSPS: 39726225; Offset : -4303725885
,I/UsageStatsService( 1039): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1228057398901; DSPS: 40381632; Offset : -4303667270
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1248058745313; DSPS: 41037036; Offset : -4303663474
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1268060717199; DSPS: 41692461; Offset : -4303675179
,I/[SystemUI]TimeTickManager( 1450): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1450): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1450): called onTimeUpdated()
I/[SystemUI]Clock( 1450): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
I/[SystemUI]DateView( 1450): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1450): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1288062186062; DSPS: 42347869; Offset : -4303671393
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 7094): 
D/AndroidRuntime( 7094): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7094): CheckJNI is OFF
D/AndroidRuntime( 7094): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1039): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1039): Killing 6547:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1039): WIN DEATH: Window{3585f4b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1039): Client connection lost with reason: 4
D/InputDispatcher( 1039): Focus left window: Window{3585f4b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher( 1039): Window went away: Window{3585f4b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1039):   Force finishing activity ActivityRecord{300672f u0 com.test.thalitest/.MainActivity t4}
W/PackageSettings( 1039): Skipping PackageSetting{e72aa52 com.example.hello/10319} due to missing metadata
E/GBMv2   (  339): DFP En is all cleared set to be enabled
W/ActivityManager( 1039): Spurious death for ProcessRecord{308a818c 6547:com.test.thalitest/u0a311}, curProc for 6547: null
I/ActivityManager( 1039): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
D/SplitWindowPolicy( 1952): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1952): topRunningActivity=ActivityInfo{14ff2055 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1952): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1952): topRunningActivity=ActivityInfo{338da6a co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/ActivityManager( 1039):   Force finishing activity ActivityRecord{300672f u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1039): Duplicate finish request for ActivityRecord{300672f u0 com.test.thalitest/.MainActivity t4 f}
I/[LGHome]EVENT( 2075): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2075): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2075): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1450): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1039): Reconfiguring input devices.  changes=0x00000010
D/LIA_Service_RemotePackageHandler( 2026): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 3849): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3849): [BTUI] [+] updateMediaPlayerInfo
D/LIA_MrGDBLogger_PackageInfoDetector( 3779): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/GeofencerStateMachine( 1820): Ignoring removeGeofence because network location is disabled.
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
W/System.err( 4536): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4536): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4536): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4536): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4536): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4536): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4536): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4536): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4536): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4536): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4536): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4536): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1039): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7124 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/[LGHome]GBoardWebView( 2075): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2075): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2075): [Launcher.java:1056:onResume()]onResume end
D/ActionManagerService( 1915): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3779): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]EVENT( 2075): [Launcher.java:1114:onPause()]onPause
D/KeyguardModel( 1450): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1450): createShortcutInfo...
D/KeyguardModel( 1450): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1450): createShortcutInfo...
D/ActionManagerService( 1915): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3779): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2075): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 3779): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
W/ResourcesManager( 1450): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/GBoardWebViewUtils( 2075): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2075): , create_time: 1430558575574
I/GBoardWebViewUtils( 2075): , expire_time: 0
I/GBoardWebViewUtils( 2075): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2075): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2075): , display: false
I/GBoardWebViewUtils( 2075): , animation: false }
I/GBoardWebViewUtils( 2075): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2075): , create_time: 1430558575600
I/GBoardWebViewUtils( 2075): , expire_time: 0
I/GBoardWebViewUtils( 2075): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2075): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2075): , display: false
I/GBoardWebViewUtils( 2075): , animation: false }
I/GBoardWebViewUtils( 2075): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1455195784986
I/GBoardWebViewUtils( 2075): , create_time: 1455195785688
I/GBoardWebViewUtils( 2075): , expire_time: 0
I/GBoardWebViewUtils( 2075): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2075): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2075): , display: false
I/GBoardWebViewUtils( 2075): , animation: false }
I/[SystemUI]QSlideListController( 1450): onReceive = android.intent.action.PACKAGE_REMOVED
W/ResourceType( 1450): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1450): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/WindowManager( 1039): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
I/SystemUI[Framework]( 1039): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
D/KeyguardModel( 1450): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1450): createShortcutInfo...
D/WallpaperManager( 2075): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
W/PhoneWindowManagerEx( 1039): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1039): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1039): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1b43af32,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 1450): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1450): No package identifier when getting value for resource number 0x00000000
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1450): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1450): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[SystemUI]NavigationThemeResource( 1450): notify navigation bar color(0x0)
I/[SystemUI]NavigationThemeResource( 1450): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1450):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1450): , Keyguard show=false, IME shown=false, Panel expanded=false
D/InputDispatcher( 1039): Focus entered window: Window{fd3884 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/SplitUIManager( 1881): split_name #11 / not available #0
D/SplitUIService( 1881): removed split : 
W/PackageManager( 1450): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1450): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1450): createShortcutInfo...
W/ResourcesManager( 1450): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2075): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2075): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourceType( 1450): No package identifier when getting value for resource number 0x00000000
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
W/PackageManager( 1450): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1450): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1450): createShortcutInfo...
D/SplitUIManager( 1881): split_name #11 / not available #0
I/SplitUIService( 1881): split app #11
D/KeyguardModel( 1450): handleShortcutListChanged...
I/art     ( 1039): Explicit concurrent mark sweep GC freed 21772(1411KB) AllocSpace objects, 10(544KB) LOS objects, 33% free, 44MB/66MB, paused 1.789ms total 197.965ms
D/KeyguardModel( 1450): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1450): createShortcutInfo...
D/KeyguardModel( 1450): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1450): createShortcutInfo...
W/ResourceType( 1450): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1450): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/art     ( 1039): WaitForGcToComplete blocked for 102.304ms for cause Explicit
D/KeyguardModel( 1450): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1450): createShortcutInfo...
W/ResourceType( 1450): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1450): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1450): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1450): createShortcutInfo...
W/ResourceType( 1450): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1450): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1450): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1450): createShortcutInfo...
D/KeyguardModel( 1450): handleShortcutListChanged...
W/ActivityManager( 1039): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3849): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3849): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3849): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3849): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3849): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3849): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3849): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3849): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3849): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3849): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3849): [BTUI] [-] updateMediaPlayerInfo
D/administrator( 1039): Handling package changes for user 0
I/art     ( 4585): Explicit concurrent mark sweep GC freed 16631(949KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 334us total 252.811ms
I/[LGHome]EVENT( 2075): [Launcher.java:5349:onStop()]onStop
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
W/ResourcesManager( 7124): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/PluginManager( 7124): init()
I/ThermalEngine(  325): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3205): Thermal-Lib-Client: Client request sent
I/NotificationService( 1039): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1039): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1039): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1039): removeObsoleteFile: deleting file=4_task.xml
I/[LGHome]EVENT( 2075): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 2075): [setNavigationBarColor] color=0x 0
D/[Concierge]WidgetView( 2075): notifyExtViewAvailable
D/InputMethodManagerService( 1039): setImestate : 0
W/InputMethodManagerService( 1039): Got RemoteException sending setActive(false) notification to pid 6547 uid 10311
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline( 1039): Timeline: Activity_windows_visible id: ActivityRecord{def5955 u0 com.lge.launcher2/.Launcher t3} time:1303633
W/IInputConnectionWrapper( 2075): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
E/b       ( 1717): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2075): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2075): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 2075): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2075): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2597): onStartCommand(). Type : 8
D/[Concierge]Service( 2597): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2597): Update widget ID : 11
D/[Concierge]WidgetView( 2075): change position of spinner
I/art     ( 1039): Explicit concurrent mark sweep GC freed 5844(346KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.725ms total 194.385ms
I/[Concierge]WidgetView( 2075): initWebView(). Time : 1456921401873
D/[Concierge]Service( 2597): onStartCommand(). Type : 0
I/[Concierge]WebView( 2075): Return exist ConciergeWebView. Reuse : 404659046
D/[Concierge]WidgetView( 2075): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2075): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2075): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@116beb57
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2075): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2075): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2075): Widget kill message received. Destory myself. My : 1456920126122, New one : 1456921401873
D/[Concierge]WidgetView( 2075): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2075): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2075): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2075): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 7094): Shutting down VM
I/Timeline( 2075): Timeline: Activity_idle id: android.os.BinderProxy@2717e0fe time:1303799
W/ResourcesManager( 1039): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1039): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2075): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ExternalStrings( 7124): load override strings
W/ExternalStrings( 7124): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7124): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7124): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7124): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7124): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7124): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7124): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7124): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7124): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7124): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7124): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7124): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7124): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7124): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7124): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7124): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7124): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7124): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 7124): onCreate
I/chromium( 2075): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
V/Signer  ( 7124): override build config not found
D/Signer  ( 7124): value of property debug is false
D/LGMDMWrapper( 7124): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7124): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7124): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7124): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7124): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7124): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7124): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7124): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7124): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7124): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7124): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7124): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7124): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
I/GBoardtInterface( 2075): onReloaded()
I/GBoardWebViewClient( 2075): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3779): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3779): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/LGMDMManager( 7124): Create singleton instance
D/ActionManagerService( 1915): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3779): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3779): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1915): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3779): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3779): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3779): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3779): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3779): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2075): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2075): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2075): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2075): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2075): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2075): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/LGMDMWrapper( 7124): LG MDM library v4.0.0 is available on this device.
D/PostponalbeReceiver( 7124): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/ContextImpl( 7124): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/AppUp4:PreloadHelper( 6061): added Exclude : com.test.thalitest
I/ActivityManager( 1039): Killing 6106:com.android.gallery3d/u0a27 (adj 15): empty #17
W/ActivityThread( 7124): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/libprocessgroup( 1039): failed to open /acct/uid_10027/pid_6106/cgroup.procs: No such file or directory
D/VoicemailCleanupService( 2234): Cleaning up data for package: com.test.thalitest
E/SQLiteLog( 2234): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/ContactsProvider2ForLG( 2234): performBackgroundTask SQLiteDiskIOException during query
D/ContactsProvider2ForLG( 2234): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
D/ContactsProvider2ForLG( 2234): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
D/ContactsProvider2ForLG( 2234): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
D/ContactsProvider2ForLG( 2234): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
D/ContactsProvider2ForLG( 2234): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
D/ContactsProvider2ForLG( 2234): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
D/ContactsProvider2ForLG( 2234): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
D/ContactsProvider2ForLG( 2234): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
D/ContactsProvider2ForLG( 2234): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
D/ContactsProvider2ForLG( 2234): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
D/ContactsProvider2ForLG( 2234): 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
D/ContactsProvider2ForLG( 2234): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
D/ContactsProvider2ForLG( 2234): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/ContactsProvider2ForLG( 2234): 	at android.os.Looper.loop(Looper.java:135)
D/ContactsProvider2ForLG( 2234): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 2234): (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 2234): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 2234): Process: android.process.acore, PID: 2234
E/AndroidRuntime( 2234): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2234): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2234): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
E/AndroidRuntime( 2234): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 2234): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2234): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
E/AndroidRuntime( 2234): 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
E/AndroidRuntime( 2234): 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
E/AndroidRuntime( 2234): 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
E/AndroidRuntime( 2234): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 2234): 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
E/AndroidRuntime( 2234): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 2234): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 2234): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2234): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2234): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2234): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
