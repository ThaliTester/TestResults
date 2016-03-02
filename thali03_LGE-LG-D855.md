#### Test 61362366121daa0_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/AlertService( 6568): Beginning updateAlertNotification
,D/AlertService( 6568): No fired or scheduled alerts
D/AlertService( 6568): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 6568): No events found starting within 1 week.
--------- beginning of system
I/ActivityManager( 1039): Killing 6216:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10061/pid_6216/cgroup.procs: No such file or directory
D/AndroidRuntime( 6614): 
D/AndroidRuntime( 6614): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6614): CheckJNI is OFF
D/AndroidRuntime( 6614): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1039): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1983): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1039): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{277959d5 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{277959d5 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1039): AppWindowTokenEx init.. 
E/GBMv2   (  349): DFP En is all cleared set to be enabled
I/ActivityManager( 1039): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6643 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/InputDispatcher( 1039): Focus left window: Window{1591f4cd u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 2096): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=167951953, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{1ccde6b6 type 0 when 1456925744066 com.lge.ia.task.mrgdblogger} when 1456925744066
V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{2c453324 type 0 when 1456925771994 com.android.vending} when 1456925771994
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{20e3ee8d type 2 when 92961 com.google.android.gms} when 92961
D/LIA_MrGDBLogger_MrGIntentReceiverDBCleaning( 3793): [dreamwood]onReceive
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{1c9b842 type 2 when 95649 com.android.providers.calendar} when 95649
D/AndroidRuntime( 6614): Shutting down VM
D/LIA_MrGDBLogger_MrGDBCleaner( 3793): [dreamwood]onReceive
D/LIA_MrGDBLogger_MrGDBManager( 3793): [dreamwood]dbFileSize : 57344
D/LIA_MrGDBLogger_DBCleanerUtil( 3793): [dreamwood]cleanOldRecord : APP_USAGE
D/LIA_MrGDBLogger_DBCleanerUtil( 3793): [dreamwood]LimitedDate : 2016-02-01 14:36:19, count : 0
D/LIA_MrGDBLogger_DBCleanerUtil( 3793): [dreamwood]cleanOldRecord : CONCIERGE_BOARD
D/LIA_MrGDBLogger_DBCleanerUtil( 3793): [dreamwood]LimitedDate : 2016-02-01 14:36:19, count : 0
D/LIA_MrGDBLogger_DBCleanerUtil( 3793): [dreamwood]cleanOldRecord : INFORMANT_FEATURE_STATUS_INFO
D/LIA_MrGDBLogger_DBCleanerUtil( 3793): [dreamwood]LimitedDate : 2016-02-01 14:36:19, count : 0
D/LIA_MrGDBLogger_MrGDBManager( 3793): [dreamwood]dbFileSize : 57344
D/CalendarProviderBroadcastReceiver( 6540): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/[Concierge]Service( 2648): onStartCommand(). Type : 9
D/CalendarProviderBroadcastReceiver( 6540): [IntentService] WakeLock acquire, start IntentSerivce
V/ActivityManager( 1039): Display changed displayId=0
D/DSDPConnection( 1878): Display #0 changed.
D/CalendarProvider2( 6540): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6540): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6540): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 6540): (284) automatic index on view_events(_id)
D/SplitWindowPolicy( 1983): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1983): topRunningActivity=ActivityInfo{367330f co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1983): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1983): topRunningActivity=ActivityInfo{31197f9c co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=167951953 [*alarm*], flags=0x0
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
D/CalendarProvider2( 6540): [IntentService] Release Lock
D/CalendarProvider2( 6540): CalendarProviderIntentService.onDestroy()
D/ContextHelper( 6643): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 97899607986; DSPS: 3348802; Offset : -4308827735
I/WebViewFactory( 6643): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6643): Loading: webviewchromium
I/LibraryLoader( 6643): Time to load native libraries: 3 ms (timestamps 7986-7989)
I/LibraryLoader( 6643): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6643): Binding Chromium to main looper Looper (main, tid 1) {1b6d964c}
,I/LibraryLoader( 6643): Expected native library version number "",actual native library version number ""
I/chromium( 6643): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6643): Initializing chromium process, renderers=0
W/art     ( 6643): Attempt to remove local handle scope entry from IRT, ignoring
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AudioPolicyService(  332): registerClient() client 0xb1427580, uid 10311
D/BluetoothManagerService( 1039): Message: 20
D/BluetoothManagerService( 1039): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@201eddc1:true
,W/chromium( 6643): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6643): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6643): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6643): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6643): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6643): Build Date: 12/12/14 금
I/Adreno-EGL( 6643): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6643): Remote Branch: 
I/Adreno-EGL( 6643): Local Patches: 
I/Adreno-EGL( 6643): Reconstruct Branch: 
,I/art     ( 2147): Explicit concurrent mark sweep GC freed 20850(1192KB) AllocSpace objects, 3(432KB) LOS objects, 51% free, 30MB/62MB, paused 3.099ms total 56.148ms
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/chromium( 6643): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/chromium( 6643): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/Finsky  ( 6358): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6358): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6358): [1] 5.onFinished: Scheduling replication attempt 1.
,W/art     ( 6643): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6643): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 6643): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 6643): [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 6643): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 6643): CordovaWebView is running on device made by: LGE
,W/art     ( 6643): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6643): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6643): Render dirty regions requested: true
I/OpenGLRenderer( 6643): Initialized EGL, version 1.4
D/OpenGLRenderer( 6643): Enabling debug mode 0
,D/Atlas   ( 6643): Validating map...
,D/SplitWindow( 1039): check instance of lgWin Window{3bf56725 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WindowManager( 1039): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework]( 1039): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
,I/[SystemUI]NavigationThemeResource( 1468): notify navigation bar color(0xfff5f5f5)
I/[SystemUI]NavigationThemeResource( 1468): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1468):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1468): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1039): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1039): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1039): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@71a8be4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher( 1039): Focus entered window: Window{3bf56725 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6643): LgDataFeature() Constructor: none
,D/LgDataFeature( 6643): LgDataFeature() Constructor Done, null
D/InputMethodManagerService( 1039): setImestate : 0
,D/InputMethodManagerService( 1039): setImestate : 0
,I/ActivityManager( 1039): Displayed com.test.thalitest/.MainActivity: +522ms (total +622ms)
W/IInputConnectionWrapper( 6643): showStatusIcon on inactive InputConnection
I/Timeline( 1039): Timeline: Activity_windows_visible id: ActivityRecord{17c855ea u0 com.test.thalitest/.MainActivity t4} time:98365
I/Timeline( 6643): Timeline: Activity_idle id: android.os.BinderProxy@285e418b time:98366
W/IInputConnectionWrapper( 6643): getTextBeforeCursor on inactive InputConnection
E/b       ( 1712): Unable to connect to the editor to retrieve text... will retry later
,W/IInputConnectionWrapper( 6643): getTextAfterCursor on inactive InputConnection
,D/JsMessageQueue( 6643): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6643): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6643): 
,I/chromium( 6643): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6643): 
,D/jxcore_app_log( 6643): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435226752
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6643): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6643):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6643):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6643):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6643):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6643): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bca2aac added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6643): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6643):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6643):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6643):     - Bluetooth MAC address: 58:3F:54:73:64:C0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6643):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6643):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6643):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6643):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6643):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6643):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6643): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a46a37b added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6643): addListener: New listener added - the number of listeners is now 1
D/WifiService( 1039): New client listening to asynchronous messages
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6643): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,W/System.err( 6643): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 6643): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 6643): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 6643): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 6643): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 6643): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 6643): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 6643): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 6643): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 6643): 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 6643): 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
W/System.err( 6643): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6643): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6643): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 6643): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6643): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6643): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12054598 added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6643): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6643): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@330321f1 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6643): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6643): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 6643): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 6643): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 6643): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 6643): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 6643): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 6643): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 6643): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 6643): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 6643): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 6643): 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 6643): 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
W/System.err( 6643): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 6643): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6643): ,	at android.os.HandlerThread.run(HandlerThread.java:61)
E/GBMv2   (  349): DFP En is all cleared set to be enabled
,E/GBMv2   (  349): Set value is all cleared set the max
,I/GBMv2   (  349): DFP Enabled. Ignore VFP set
,I/rmt_storage(  320): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  320): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
,I/rmt_storage(  320): wakelock acquired: 1, error no: 42
,I/rmt_storage(  320): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/rmt_storage(  320): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  320): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  320): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  320): 
,I/rmt_storage(  320): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,E/Diag_Lib(  869): [IMS_FATAL]| 3347 | 883 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
I/chromium( 6643): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 6643): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3af8b74c type 2 when 108025 android} when 108025
,I/ActivityManager( 1039): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6746 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 6746): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 6746): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksApp( 6746): Created application version: 3.2.35 (30235)
I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,I/BooksSync( 6746): Starting books sync
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/ContactsSyncAdapter( 2147): innerSync failed
D/ContactsSyncAdapter( 2147): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2147): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2147): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2147): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2147): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2147): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2147): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2147): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2147): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2147): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2147): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 80911, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1039): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 169824, reason: 10019
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 15884(774KB) AllocSpace objects, 3(182KB) LOS objects, 33% free, 44MB/66MB, paused 1.886ms total 123.928ms
,D/BooksSync( 6746): started syncMyEbooks
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
,D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
E/BooksAccountManager( 6746): Authentication error
E/BooksAccountManager( 6746): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6746): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6746): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6746): null auth token
D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  328): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  328): res_queryN name = www.googleapis.com succeed
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6746): Error response from books API: {
W/ApiaryClient( 6746):  "error": {
W/ApiaryClient( 6746):   "errors": [
W/ApiaryClient( 6746):    {
W/ApiaryClient( 6746):     "domain": "global",
W/ApiaryClient( 6746):     "reason": "required",
W/ApiaryClient( 6746):     "message": "Login Required",
W/ApiaryClient( 6746):     "locationType": "header",
W/ApiaryClient( 6746):     "location": "Authorization"
W/ApiaryClient( 6746):    }
W/ApiaryClient( 6746):   ],
W/ApiaryClient( 6746):   "code": 401,
W/ApiaryClient( 6746):   "message": "Login Required"
W/ApiaryClient( 6746):  }
W/ApiaryClient( 6746): }
,W/ApiaryClient( 6746): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6147316813236258125&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6746): Headers:
W/ApiaryClient( 6746): accept-encoding: [gzip]
W/ApiaryClient( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6746): gdata-version: 2
V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
,W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6746): Authentication error
E/BooksAccountManager( 6746): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6746): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6746): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6746): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6746): Error response from books API: {
W/ApiaryClient( 6746):  "error": {
W/ApiaryClient( 6746):   "errors": [
W/ApiaryClient( 6746):    {
W/ApiaryClient( 6746):     "domain": "global",
W/ApiaryClient( 6746):     "reason": "required",
W/ApiaryClient( 6746):     "message": "Login Required",
W/ApiaryClient( 6746):     "locationType": "header",
W/ApiaryClient( 6746):     "location": "Authorization"
W/ApiaryClient( 6746):    }
W/ApiaryClient( 6746):   ],
W/ApiaryClient( 6746):   "code": 401,
W/ApiaryClient( 6746):   "message": "Login Required"
W/ApiaryClient( 6746):  }
W/ApiaryClient( 6746): }
W/ApiaryClient( 6746): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6147316813236258125&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6746): Headers:
W/ApiaryClient( 6746): accept-encoding: [gzip]
W/ApiaryClient( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6746): gdata-version: 2
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6746): Authentication error
E/BooksAccountManager( 6746): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6746): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6746): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6746): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6746): Error response from books API: {
W/ApiaryClient( 6746):  "error": {
W/ApiaryClient( 6746):   "errors": [
W/ApiaryClient( 6746):    {
W/ApiaryClient( 6746):     "domain": "global",
W/ApiaryClient( 6746):     "reason": "required",
W/ApiaryClient( 6746):     "message": "Login Required",
W/ApiaryClient( 6746):     "locationType": "header",
W/ApiaryClient( 6746):     "location": "Authorization"
W/ApiaryClient( 6746):    }
W/ApiaryClient( 6746):   ],
W/ApiaryClient( 6746):   "code": 401,
W/ApiaryClient( 6746):   "message": "Login Required"
W/ApiaryClient( 6746):  }
W/ApiaryClient( 6746): }
,W/ApiaryClient( 6746): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6147316813236258125&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6746): Headers:
W/ApiaryClient( 6746): accept-encoding: [gzip]
W/ApiaryClient( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6746): gdata-version: 2
,I/MusicWidget( 2716): mDelayedStopHandler : unbind
,I/MusicBrowser( 2223): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2223): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2223): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2223): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2223): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2223): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,I/MusicBrowser( 2223): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2223): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1039):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@7451b5acom.lge.music.MediaPlaybackService$5@285e418b
D/MusicBrowser( 2223): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2223): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2223): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2223): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2223): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@32d8c711
I/MusicBrowser( 2223): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2223): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2223): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2223): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2223): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2223): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2223): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2223): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2223): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2223): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2223): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2223): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2223): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2223): reset
V/MediaPlayer[Native]( 2223): setListener
V/MediaPlayer[Native]( 2223): disconnect
V/MediaPlayer[Native]( 2223): destructor
,V/AudioFlinger(  332): releasing 13 from 2223 for -1
V/AudioFlinger(  332):  decremented refcount to 0
V/AudioFlinger(  332): purging stale effects
V/MediaPlayer[Native]( 2223): disconnect
D/MusicBrowser( 2223): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2223): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2223): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2223): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2223): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2223): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2223): [SmartShareManagerClient] unregisterListener: 614232680
W/SmartShareClient( 2223): [SmartShareManagerClient] unregisterListener invalid listener: 614232680
E/BooksSync( 6746): Soft error: 
E/BooksSync( 6746): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6147316813236258125&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6746): Headers:
E/BooksSync( 6746): accept-encoding: [gzip]
E/BooksSync( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6746): gdata-version: 2
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6746): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6746): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6746): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6746): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6746): {
E/BooksSync( 6746):  "error": {
E/BooksSync( 6746):   "errors": [
E/BooksSync( 6746):    {
E/BooksSync( 6746):     "domain": "global",
E/BooksSync( 6746):     "reason": "required",
E/BooksSync( 6746):     "message": "Login Required",
E/BooksSync( 6746):     "locationType": "header",
E/BooksSync( 6746):     "location": "Authorization"
E/BooksSync( 6746):    }
E/BooksSync( 6746):   ],
E/BooksSync( 6746):   "code": 401,
E/BooksSync( 6746):   "message": "Login Required"
E/BooksSync( 6746):  }
E/BooksSync( 6746): }
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6746): 	... 8 more
E/BooksSync( 6746): Sync error
E/BooksSync( 6746): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6147316813236258125&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&sourc,e=ge-android-app
E/BooksSync( 6746): Headers:
E/BooksSync( 6746): accept-encoding: [gzip]
E/BooksSync( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6746): gdata-version: 2
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6746): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6746): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6746): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6746): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6746): {
E/BooksSync( 6746):  "error": {
E/BooksSync( 6746):   "errors": [
E/BooksSync( 6746):    {
E/BooksSync( 6746):     "domain": "global",
E/BooksSync( 6746):     "reason": "required",
E/BooksSync( 6746):     "message": "Login Required",
E/BooksSync( 6746):     "locationType": "header",
E/BooksSync( 6746):     "location": "Authorization"
E/BooksSync( 6746):    }
E/BooksSync( 6746):   ],
E/BooksSync( 6746):   "code": 401,
E/BooksSync( 6746):   "message": "Login Required"
E/BooksSync( 6746):  }
E/BooksSync( 6746): }
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6746): 	... 8 more
I/BooksSync( 6746): Finished books sync
,I/SmartShareClient( 2223): [SmartShareManagerClient] terminate service: 2223/MediaPlaybackService/748140159
E/HomeCloudIF( 2223): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2223): [SmartShareManagerClient] unbindService context:android.app.Application@25e89681
V/CloudHub( 2223): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2223): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2223): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2223): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
,I/ActivityManager( 1039): Killing 6336:com.lge.eula/1000 (adj 15): empty #17
I/CloudHub( 2223): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29990
W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6336/cgroup.procs: No such file or directory
,I/ActivityManager( 1039): Killing 6432:com.lge.bnr/1000 (adj 15): empty #17
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 87433, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6432/cgroup.procs: No such file or directory
,I/GAV2    ( 6746): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 117901503084; DSPS: 4004224; Offset : -4308825535
,I/CloudHub( 2223): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19979
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{1f5c900c type 0 when 1456925799871 com.android.vending} when 1456925799871
,W/ContextImpl( 4924): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6358): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6358): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6358): [1] 5.onFinished: Scheduling replication attempt 2.
,I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
,D/WifiController( 1039): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1983): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1983): Battery Level Remaining: 100%
D/LEDHandler( 1983): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 4194): Disconnected process message: 10, size: 0
,D/LGDMClient( 4762): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4762): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 137903293219; DSPS: 4659643; Offset : -4308835806
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{2cf3ac0e type 2 when 138097 android} when 138097
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
I/CloudHub( 2223): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2223): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=167951953, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{162a143c type 0 when 1456925825620 com.android.vending} when 1456925825620
,D/[Concierge]Service( 2648): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=167951953 [*alarm*], flags=0x0
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6358): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6358): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6358): [1] 5.onFinished: Scheduling replication attempt 3.
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 157904974279; DSPS: 5315058; Offset : -4308833343
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{311891f type 0 when 1456925852573 com.android.vending} when 1456925852573
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6358): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6358): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6358): [1] 5.onFinished: Scheduling replication attempt 4.
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{36cc98e9 type 2 when 176934 android} when 176934
,I/BooksSync( 6746): Starting books sync
,D/BooksSync( 6746): started syncMyEbooks
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6746): Authentication error
E/BooksAccountManager( 6746): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6746): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6746): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6746): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6746): Error response from books API: {
W/ApiaryClient( 6746):  "error": {
W/ApiaryClient( 6746):   "errors": [
W/ApiaryClient( 6746):    {
W/ApiaryClient( 6746):     "domain": "global",
W/ApiaryClient( 6746):     "reason": "required",
W/ApiaryClient( 6746):     "message": "Login Required",
W/ApiaryClient( 6746):     "locationType": "header",
W/ApiaryClient( 6746):     "location": "Authorization"
W/ApiaryClient( 6746):    }
W/ApiaryClient( 6746):   ],
W/ApiaryClient( 6746):   "code": 401,
W/ApiaryClient( 6746):   "message": "Login Required"
W/ApiaryClient( 6746):  }
W/ApiaryClient( 6746): }
,W/ApiaryClient( 6746): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4347023008039872392&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6746): Headers:
W/ApiaryClient( 6746): accept-encoding: [gzip]
W/ApiaryClient( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6746): gdata-version: 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 177906593702; DSPS: 5970471; Offset : -4308831456
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6746): Authentication error
E/BooksAccountManager( 6746): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6746): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6746): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6746): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6746): Error response from books API: {
W/ApiaryClient( 6746):  "error": {
W/ApiaryClient( 6746):   "errors": [
W/ApiaryClient( 6746):    {
W/ApiaryClient( 6746):     "domain": "global",
W/ApiaryClient( 6746):     "reason": "required",
W/ApiaryClient( 6746):     "message": "Login Required",
W/ApiaryClient( 6746):     "locationType": "header",
W/ApiaryClient( 6746):     "location": "Authorization"
W/ApiaryClient( 6746):    }
W/ApiaryClient( 6746):   ],
W/ApiaryClient( 6746):   "code": 401,
W/ApiaryClient( 6746):   "message": "Login Required"
W/ApiaryClient( 6746):  }
W/ApiaryClient( 6746): }
W/ApiaryClient( 6746): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4347023008039872392&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6746): Headers:
W/ApiaryClient( 6746): accept-encoding: [gzip]
W/ApiaryClient( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6746): gdata-version: 2
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6746): Authentication error
E/BooksAccountManager( 6746): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6746): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6746): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6746): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6746): Error response from books API: {
W/ApiaryClient( 6746):  "error": {
W/ApiaryClient( 6746):   "errors": [
W/ApiaryClient( 6746):    {
W/ApiaryClient( 6746):     "domain": "global",
W/ApiaryClient( 6746):     "reason": "required",
W/ApiaryClient( 6746):     "message": "Login Required",
W/ApiaryClient( 6746):     "locationType": "header",
W/ApiaryClient( 6746):     "location": "Authorization"
W/ApiaryClient( 6746):    }
W/ApiaryClient( 6746):   ],
W/ApiaryClient( 6746):   "code": 401,
W/ApiaryClient( 6746):   "message": "Login Required"
W/ApiaryClient( 6746):  }
W/ApiaryClient( 6746): }
W/ApiaryClient( 6746): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4347023008039872392&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6746): Headers:
W/ApiaryClient( 6746): accept-encoding: [gzip]
W/ApiaryClient( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6746): gdata-version: 2
,E/BooksSync( 6746): Soft error: 
E/BooksSync( 6746): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4347023008039872392&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6746): Headers:
E/BooksSync( 6746): accept-encoding: [gzip]
E/BooksSync( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6746): gdata-version: 2
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6746): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6746): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6746): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6746): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6746): {
E/BooksSync( 6746):  "error": {
E/BooksSync( 6746):   "errors": [
E/BooksSync( 6746):    {
E/BooksSync( 6746):     "domain": "global",
E/BooksSync( 6746):     "reason": "required",
E/BooksSync( 6746):     "message": "Login Required",
E/BooksSync( 6746):     "locationType": "header",
E/BooksSync( 6746):     "location": "Authorization"
E/BooksSync( 6746):    }
E/BooksSync( 6746):   ],
E/BooksSync( 6746):   "code": 401,
E/BooksSync( 6746):   "message": "Login Required"
E/BooksSync( 6746):  }
E/BooksSync( 6746): }
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6746): 	... 8 more
,E/BooksSync( 6746): Sync error
E/BooksSync( 6746): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4347023008039872392&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6746): Headers:
E/BooksSync( 6746): accept-encoding: [gzip]
E/BooksSync( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6746): gdata-version: 2
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6746): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6746): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6746): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6746): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6746): {
E/BooksSync( 6746):  "error": {
E/BooksSync( 6746):   "errors": [
E/BooksSync( 6746):    {
E/BooksSync( 6746):     "domain": "global",
E/BooksSync( 6746):     "reason": "required",
E/BooksSync( 6746):     "message": "Login Required",
E/BooksSync( 6746):     "locationType": "header",
E/BooksSync( 6746):     "location": "Authorization"
E/BooksSync( 6746):    }
E/BooksSync( 6746):   ],
E/BooksSync( 6746):   "code": 401,
E/BooksSync( 6746):   "message": "Login Required"
E/BooksSync( 6746):  }
E/BooksSync( 6746): }
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6746): 	... 8 more
I/BooksSync( 6746): Finished books sync
,D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 176934, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1039): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1983): ACTION_BATTERY_CHANGED : plugged type=2
D/HeadsetStateMachine( 4194): Disconnected process message: 10, size: 0
D/LEDHandler( 1983): Battery Level Remaining: 100%
D/LEDHandler( 1983): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4762): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4762): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{19a08f85 type 0 when 1456925877450 com.android.vending} when 1456925877450
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2147): Explicit concurrent mark sweep GC freed 30177(1777KB) AllocSpace objects, 16(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.432ms total 33.215ms
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1039): Explicit concurrent mark sweep GC freed 26471(1140KB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/66MB, paused 1.656ms total 88.493ms
,D/Finsky  ( 6358): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6358): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6358): [1] 5.onFinished: Scheduling replication attempt 5.
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 197908298364; DSPS: 6625887; Offset : -4308835309
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=167951953, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{1784ecdf type 2 when 206980 android} when 206980
D/[Concierge]Service( 2648): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=167951953 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 217909943751; DSPS: 7281301; Offset : -4308838002
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{12fd63f5 type 0 when 1456925899022 com.android.vending} when 1456925899022
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6358): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6358): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6358): [1] 5.onFinished: Giving up after 6 failures.
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3428cbcf type 2 when 187337 com.google.android.gms} when 187337
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{1492095c type 2 when 189143 android} when 189143
V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2147): Vacuum at: now=1456925915245 tag=VacuumService
,I/GoogleURLConnFactory( 2147): Using platform SSLCertificateSocketFactory
,W/Uploader( 2147): No account for auth token provided
,D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  328): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  328): res_queryN name = play.googleapis.com succeed
,W/Uploader( 2147): No account for auth token provided
,W/Uploader( 2147): No account for auth token provided
,W/Uploader( 2147):  no longer exists, so no auth token.
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 237911574175; DSPS: 7936715; Offset : -4308855814
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{1def9763 type 2 when 257255 android} when 257255
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 257913242706; DSPS: 8592129; Offset : -4308834971
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 277914833471; DSPS: 9247542; Offset : -4308861768
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 297916457658; DSPS: 9902955; Offset : -4308855064
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=167951953, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{38b5cf60 type 2 when 308883 android} when 308883
D/[Concierge]Service( 2648): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=167951953 [*alarm*], flags=0x0
,I/BooksSync( 6746): Starting books sync
,D/BooksSync( 6746): started syncMyEbooks
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6746): Authentication error
E/BooksAccountManager( 6746): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6746): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6746): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6746): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6746): Error response from books API: {
W/ApiaryClient( 6746):  "error": {
W/ApiaryClient( 6746):   "errors": [
W/ApiaryClient( 6746):    {
W/ApiaryClient( 6746):     "domain": "global",
W/ApiaryClient( 6746):     "reason": "required",
W/ApiaryClient( 6746):     "message": "Login Required",
W/ApiaryClient( 6746):     "locationType": "header",
W/ApiaryClient( 6746):     "location": "Authorization"
W/ApiaryClient( 6746):    }
W/ApiaryClient( 6746):   ],
W/ApiaryClient( 6746):   "code": 401,
W/ApiaryClient( 6746):   "message": "Login Required"
W/ApiaryClient( 6746):  }
W/ApiaryClient( 6746): }
W/ApiaryClient( 6746): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4841788010831689817&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6746): Headers:
W/ApiaryClient( 6746): accept-encoding: [gzip]
W/ApiaryClient( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6746): gdata-version: 2
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6746): Authentication error
E/BooksAccountManager( 6746): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6746): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6746): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6746): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6746): Error response from books API: {
W/ApiaryClient( 6746):  "error": {
W/ApiaryClient( 6746):   "errors": [
W/ApiaryClient( 6746):    {
W/ApiaryClient( 6746):     "domain": "global",
W/ApiaryClient( 6746):     "reason": "required",
W/ApiaryClient( 6746):     "message": "Login Required",
W/ApiaryClient( 6746):     "locationType": "header",
W/ApiaryClient( 6746):     "location": "Authorization"
W/ApiaryClient( 6746):    }
W/ApiaryClient( 6746):   ],
W/ApiaryClient( 6746):   "code": 401,
W/ApiaryClient( 6746):   "message": "Login Required"
W/ApiaryClient( 6746):  }
W/ApiaryClient( 6746): }
W/ApiaryClient( 6746): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4841788010831689817&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6746): Headers:
W/ApiaryClient( 6746): accept-encoding: [gzip]
W/ApiaryClient( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6746): gdata-version: 2
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6746): Authentication error
E/BooksAccountManager( 6746): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6746): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6746): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6746): null auth token
,D/QuickStatusbarLayout( 1418): Notification difference=198
,D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6746): Error response from books API: {
W/ApiaryClient( 6746):  "error": {
W/ApiaryClient( 6746):   "errors": [
W/ApiaryClient( 6746):    {
W/ApiaryClient( 6746):     "domain": "global",
W/ApiaryClient( 6746):     "reason": "required",
W/ApiaryClient( 6746):     "message": "Login Required",
W/ApiaryClient( 6746):     "locationType": "header",
W/ApiaryClient( 6746):     "location": "Authorization"
W/ApiaryClient( 6746):    }
W/ApiaryClient( 6746):   ],
W/ApiaryClient( 6746):   "code": 401,
W/ApiaryClient( 6746):   "message": "Login Required"
W/ApiaryClient( 6746):  }
W/ApiaryClient( 6746): }
W/ApiaryClient( 6746): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4841788010831689817&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6746): Headers:
W/ApiaryClient( 6746): accept-encoding: [gzip]
W/ApiaryClient( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6746): gdata-version: 2
,E/BooksSync( 6746): Soft error: ,
E/BooksSync( 6746): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4841788010831689817&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6746): Headers:
E/BooksSync( 6746): accept-encoding: [gzip]
E/BooksSync( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6746): gdata-version: 2
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6746): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6746): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6746): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6746): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6746): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6746): {,
E/BooksSync( 6746):  "error": {
E/BooksSync( 6746):   "errors": [
E/BooksSync( 6746):    {
E/BooksSync( 6746):     "domain": "global",
E/BooksSync( 6746):     "reason": "required",
E/BooksSync( 6746):     "message": "Login Required",,
E/BooksSync( 6746):     "locationType": "header",
E/BooksSync( 6746):     "location": "Authorization"
E/BooksSync( 6746):    }
E/BooksSync( 6746):   ],
E/BooksSync( 6746):   "code": 401,
E/BooksSync( 6746):   "message": "Login Required"
E/BooksSync( 6746):  }
E/BooksSync( 6746): }
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6746): 	... 8 more
,E/BooksSync( 6746): Sync error,
E/BooksSync( 6746): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4841788010831689817&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6746): Headers:
E/BooksSync( 6746): accept-encoding: [gzip]
E/BooksSync( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/],
E/BooksSync( 6746): gdata-version: 2
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211),
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6746): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6746): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6746): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6746): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6746): {
E/BooksSync( 6746):  "error": {
,E/BooksSync( 6746):   "errors": [
E/BooksSync( 6746):    {
E/BooksSync( 6746):     "domain": "global",
E/BooksSync( 6746):     "reason": "required",
E/BooksSync( 6746):     "message": "Login Required",
E/BooksSync( 6746):     "locationType": "header",
E/BooksSync( 6746):     "location": "Authorization"
E/BooksSync( 6746):    }
E/BooksSync( 6746):   ],
E/BooksSync( 6746):   "code": 401,
E/BooksSync( 6746):   "message": "Login Required"
E/BooksSync( 6746):  }
E/BooksSync( 6746): }
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6746): 	... 8 more
I/BooksSync( 6746): Finished books sync
,D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 308883, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 317918118410; DSPS: 10558368; Offset : -4308811614
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
I/LocationManagerService( 1039): remove 2ad85dbf
D/LocationManagerService( 1039): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService( 1039): getAllProviders()=[passive, gps, network]
D/LocationManagerService( 1039): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService( 1039): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService( 1039): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 337921626951; DSPS: 11213844; Offset : -4308843164
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=167951953, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{33b1ac4a type 2 when 339019 android} when 339019
D/[Concierge]Service( 2648): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=167951953 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 357924593480; DSPS: 11869301; Offset : -4308836814
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ResourcesManager( 1418): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/PlayEventLogger( 6358): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6358): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6358): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6358): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6358): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6358): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6358): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6358): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  328): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  328): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 377926267052; DSPS: 12524716; Offset : -4308841736
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=167951953, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,D/[Concierge]Service( 2648): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=167951953 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 397927843180; DSPS: 13180127; Offset : -4308821874
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 417929426321; DSPS: 13835539; Offset : -4308825828
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 437931594259; DSPS: 14490970; Offset : -4308824744
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
,D/LEDHandler( 1983): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1983): Battery Level Remaining: 100%
D/LEDHandler( 1983): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
,D/WifiController( 1039): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 4194): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4762): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4762): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 457933178436; DSPS: 15146381; Offset : -4308796546
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 477934722602; DSPS: 15801793; Offset : -4308839554
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 497936260287; DSPS: 16457204; Offset : -4308858292
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 517937834649; DSPS: 17112613; Offset : -4308778874
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 537939407409; DSPS: 17768027; Offset : -4308854611
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 557941610408; DSPS: 18423458; Offset : -4308818125
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=167951953, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3b9e721c type 2 when 569072 android} when 569072
D/[Concierge]Service( 2648): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=167951953 [*alarm*], flags=0x0
,I/BooksSync( 6746): Starting books sync
,D/BooksSync( 6746): started syncMyEbooks
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6746): Authentication error
E/BooksAccountManager( 6746): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6746): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6746): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6746): null auth token
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  328): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  328): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6746): Error response from books API: {
W/ApiaryClient( 6746):  "error": {
W/ApiaryClient( 6746):   "errors": [
W/ApiaryClient( 6746):    {
W/ApiaryClient( 6746):     "domain": "global",
W/ApiaryClient( 6746):     "reason": "required",
W/ApiaryClient( 6746):     "message": "Login Required",
W/ApiaryClient( 6746):     "locationType": "header",
W/ApiaryClient( 6746):     "location": "Authorization"
W/ApiaryClient( 6746):    }
W/ApiaryClient( 6746):   ],
W/ApiaryClient( 6746):   "code": 401,
W/ApiaryClient( 6746):   "message": "Login Required"
W/ApiaryClient( 6746):  }
W/ApiaryClient( 6746): }
W/ApiaryClient( 6746): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2207563183315918258&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6746): Headers:
W/ApiaryClient( 6746): accept-encoding: [gzip]
W/ApiaryClient( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6746): gdata-version: 2
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 29101(1256KB) AllocSpace objects, 7(752KB) LOS objects, 33% free, 44MB/66MB, paused 2.374ms total 136.856ms
,V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6746): Authentication error
E/BooksAccountManager( 6746): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6746): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6746): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6746): null auth token
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6746): Error response from books API: {
W/ApiaryClient( 6746):  "error": {
W/ApiaryClient( 6746):   "errors": [
W/ApiaryClient( 6746):    {
W/ApiaryClient( 6746):     "domain": "global",
W/ApiaryClient( 6746):     "reason": "required",
W/ApiaryClient( 6746):     "message": "Login Required",
W/ApiaryClient( 6746):     "locationType": "header",
W/ApiaryClient( 6746):     "location": "Authorization"
W/ApiaryClient( 6746):    }
W/ApiaryClient( 6746):   ],
W/ApiaryClient( 6746):   "code": 401,
W/ApiaryClient( 6746):   "message": "Login Required"
W/ApiaryClient( 6746):  }
W/ApiaryClient( 6746): }
W/ApiaryClient( 6746): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2207563183315918258&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6746): Headers:
W/ApiaryClient( 6746): accept-encoding: [gzip]
W/ApiaryClient( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6746): gdata-version: 2
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6746): Authentication error
E/BooksAccountManager( 6746): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6746): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6746): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6746): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6746): Error response from books API: {
W/ApiaryClient( 6746):  "error": {
W/ApiaryClient( 6746):   "errors": [
W/ApiaryClient( 6746):    {
W/ApiaryClient( 6746):     "domain": "global",
W/ApiaryClient( 6746):     "reason": "required",
W/ApiaryClient( 6746):     "message": "Login Required",
W/ApiaryClient( 6746):     "locationType": "header",
W/ApiaryClient( 6746):     "location": "Authorization"
W/ApiaryClient( 6746):    }
W/ApiaryClient( 6746):   ],
W/ApiaryClient( 6746):   "code": 401,
W/ApiaryClient( 6746):   "message": "Login Required"
W/ApiaryClient( 6746):  }
W/ApiaryClient( 6746): }
W/ApiaryClient( 6746): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2207563183315918258&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6746): Headers:
W/ApiaryClient( 6746): accept-encoding: [gzip]
W/ApiaryClient( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6746): gdata-version: 2
,E/BooksSync( 6746): Soft error: 
E/BooksSync( 6746): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2207563183315918258&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6746): Headers:
E/BooksSync( 6746): accept-encoding: [gzip]
E/BooksSync( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6746): gdata-version: 2
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6746): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6746): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6746): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6746): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6746): {
E/BooksSync( 6746):  "error": {
E/BooksSync( 6746):   "errors": [
E/BooksSync( 6746):    {
E/BooksSync( 6746):     "domain": "global",
E/BooksSync( 6746):     "reason": "required",
E/BooksSync( 6746):     "message": "Login Required",
E/BooksSync( 6746):     "locationType": "header",
E/BooksSync( 6746):     "location": "Authorization"
E/BooksSync( 6746):    }
E/BooksSync( 6746):   ],
E/BooksSync( 6746):   "code": 401,
E/BooksSync( 6746):   "message": "Login Required"
E/BooksSync( 6746):  }
E/BooksSync( 6746): }
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6746): 	... 8 more
,E/BooksSync( 6746): Sync error
E/BooksSync( 6746): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2207563183315918258&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6746): Headers:
E/BooksSync( 6746): accept-encoding: [gzip]
E/BooksSync( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6746): gdata-version: 2
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6746): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6746): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6746): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6746): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6746): {
E/BooksSync( 6746):  "error": {
E/BooksSync( 6746):   "errors": [
E/BooksSync( 6746):    {
E/BooksSync( 6746):     "domain": "global",
E/BooksSync( 6746):     "reason": "required",
E/BooksSync( 6746):     "message": "Login Required",
E/BooksSync( 6746):     "locationType": "header",
E/BooksSync( 6746):     "location": "Authorization"
E/BooksSync( 6746):    }
E/BooksSync( 6746):   ],
E/BooksSync( 6746):   "code": 401,
E/BooksSync( 6746):   "message": "Login Required"
E/BooksSync( 6746):  }
E/BooksSync( 6746): }
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6746): 	... 8 more
I/BooksSync( 6746): Finished books sync
,D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 569072, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 577943301561; DSPS: 19078874; Offset : -4308835775
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 597944852724; DSPS: 19734283; Offset : -4308780364
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{df57726 type 2 when 599259 android} when 599259
,I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
,D/WifiController( 1039): battery changed pluggedType: 2
,D/LEDHandler( 1983): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1983): Battery Level Remaining: 100%
D/LEDHandler( 1983): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 4194): Disconnected process message: 10, size: 0
,D/LGDMClient( 4762): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4762): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 617946558547; DSPS: 20389701; Offset : -4308844429
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=167951953, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,I/ActivityManager( 1039): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7054 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2648): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7054): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7054): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@ca03b9e
,I/ActivityManager( 1039): Killing 6461:com.google.android.talk/u0a72 (adj 15): empty #17
D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=167951953 [*alarm*], flags=0x0
W/libprocessgroup( 1039): failed to open /acct/uid_10072/pid_6461/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 637948250381; DSPS: 21045116; Offset : -4308830854
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 657949909792; DSPS: 21700529; Offset : -4308789213
,I/ActivityManager( 1039): Killing 6129:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10011/pid_6129/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 677952207092; DSPS: 22355966; Offset : -4308841792
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 697953776782; DSPS: 23011377; Offset : -4308828161
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 717955413358; DSPS: 23666791; Offset : -4308839873
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 737956926580; DSPS: 24322200; Offset : -4308822012
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 757958477369; DSPS: 24977610; Offset : -4308796867
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 777959975210; DSPS: 25633019; Offset : -4308794701
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 797961447716; DSPS: 26288428; Offset : -4308817400
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=167951953, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,D/Finsky  ( 6358): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{2942d114 type 0 when 1456926304593 com.android.vending} when 1456926304593
D/[Concierge]Service( 2648): onStartCommand(). Type : 9
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=167951953 [*alarm*], flags=0x0
I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6358): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6358): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6358): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6358): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 6358): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6358): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
D/DeviceConnectionService( 1843): client connected with version: 7571000
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 817964541045; DSPS: 26943890; Offset : -4308836759
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{3fef1736 type 0 when 1456926504297 com.android.vending} when 1456926504297
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6358): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6358): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6358): [1] 5.onFinished: Scheduling replication attempt 1.
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 837965910161; DSPS: 27599295; Offset : -4308840336
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{362a2041 type 0 when 1456926534662 com.android.vending} when 1456926534662
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 857967299042; DSPS: 28254700; Offset : -4308823938
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2147): Explicit concurrent mark sweep GC freed 43866(2MB) AllocSpace objects, 16(2MB) LOS objects, 51% free, 30MB/62MB, paused 2.080ms total 61.212ms
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6358): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6358): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6358): [1] 5.onFinished: Scheduling replication attempt 2.
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 877969089132; DSPS: 28910120; Offset : -4308866022
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=167951953, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{154b8e58 type 0 when 1456926559948 com.android.vending} when 1456926559948
,D/[Concierge]Service( 2648): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=167951953 [*alarm*], flags=0x0
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6358): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6358): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6358): [1] 5.onFinished: Scheduling replication attempt 3.
,I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
,D/WifiController( 1039): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1983): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1983): Battery Level Remaining: 100%
D/LEDHandler( 1983): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 4194): Disconnected process message: 10, size: 0
,D/LGDMClient( 4762): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4762): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 897971781094; DSPS: 29565567; Offset : -4308829507
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{2e6e8907 type 0 when 1456926585398 com.android.vending} when 1456926585398
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6358): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6358): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6358): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 917973476994; DSPS: 30220983; Offset : -4308842591
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=167951953, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{210bc691 type 2 when 930051 com.google.android.gms} when 930051
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{e5c1f7 type 0 when 1456926613854 com.android.vending} when 1456926613854
D/[Concierge]Service( 2648): onStartCommand(). Type : 9
,D/GCM     ( 2147): Message class com.google.f.a.a.i
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=167951953 [*alarm*], flags=0x0
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6358): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6358): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6358): [1] 5.onFinished: Scheduling replication attempt 5.
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 937975185582; DSPS: 30876399; Offset : -4308842701
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{c9a7601 type 2 when 948868 com.android.bluetooth} when 948868
,W/bt-smp  ( 4194): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
,W/bt-smp  ( 4194): Plain text(LSB ~ MSB) = d9 ef 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 4194): Encrypted text(LSB ~ MSB) = 08 82 96 58 f3 6d 4e a2 4f 2a 89 8a 71 80 c7 45 
W/bt-btm  ( 4194): Stopping oneshot timer
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 957976885038; DSPS: 31531814; Offset : -4308821893
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{18d516e7 type 0 when 1456926635312 com.android.vending} when 1456926635312
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 27521(1147KB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 2.120ms total 108.820ms
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6358): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6358): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6358): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 977978427924; DSPS: 32187225; Offset : -4308835509
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 997980668887; DSPS: 32842658; Offset : -4308822225
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1017982227828; DSPS: 33498070; Offset : -4308849885
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1037983811019; DSPS: 34153482; Offset : -4308853946
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1057985337557; DSPS: 34808891; Offset : -4308822562
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1077986911124; DSPS: 35464303; Offset : -4308836013
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=167951953, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{1fabe171 type 2 when 1085936 android} when 1085936
D/[Concierge]Service( 2648): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=167951953 [*alarm*], flags=0x0
,I/BooksSync( 6746): Starting books sync
,D/BooksSync( 6746): started syncMyEbooks
V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6746): Authentication error
E/BooksAccountManager( 6746): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6746): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6746): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6746): null auth token
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  328): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  328): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6746): Error response from books API: {
W/ApiaryClient( 6746):  "error": {
W/ApiaryClient( 6746):   "errors": [
W/ApiaryClient( 6746):    {
W/ApiaryClient( 6746):     "domain": "global",
W/ApiaryClient( 6746):     "reason": "required",
W/ApiaryClient( 6746):     "message": "Login Required",
W/ApiaryClient( 6746):     "locationType": "header",
W/ApiaryClient( 6746):     "location": "Authorization"
W/ApiaryClient( 6746):    }
W/ApiaryClient( 6746):   ],
W/ApiaryClient( 6746):   "code": 401,
W/ApiaryClient( 6746):   "message": "Login Required"
W/ApiaryClient( 6746):  }
W/ApiaryClient( 6746): }
,W/ApiaryClient( 6746): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1588356315236262631&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6746): Headers:
W/ApiaryClient( 6746): accept-encoding: [gzip]
W/ApiaryClient( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6746): gdata-version: 2
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6746): Authentication error
E/BooksAccountManager( 6746): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6746): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6746): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6746): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6746): Error response from books API: {
W/ApiaryClient( 6746):  "error": {
W/ApiaryClient( 6746):   "errors": [
W/ApiaryClient( 6746):    {
W/ApiaryClient( 6746):     "domain": "global",
W/ApiaryClient( 6746):     "reason": "required",
W/ApiaryClient( 6746):     "message": "Login Required",
W/ApiaryClient( 6746):     "locationType": "header",
W/ApiaryClient( 6746):     "location": "Authorization"
W/ApiaryClient( 6746):    }
W/ApiaryClient( 6746):   ],
W/ApiaryClient( 6746):   "code": 401,
W/ApiaryClient( 6746):   "message": "Login Required"
W/ApiaryClient( 6746):  }
W/ApiaryClient( 6746): }
W/ApiaryClient( 6746): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1588356315236262631&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6746): Headers:
W/ApiaryClient( 6746): accept-encoding: [gzip]
W/ApiaryClient( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6746): gdata-version: 2
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2147): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2147): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2147): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2147): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2147): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2147): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2147): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2147): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2147): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2147): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6746): Authentication error
E/BooksAccountManager( 6746): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6746): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6746): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6746): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6746): null auth token
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{27383a9d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6746): Error response from books API: {
W/ApiaryClient( 6746):  "error": {
W/ApiaryClient( 6746):   "errors": [
W/ApiaryClient( 6746):    {
W/ApiaryClient( 6746):     "domain": "global",
W/ApiaryClient( 6746):     "reason": "required",
W/ApiaryClient( 6746):     "message": "Login Required",
W/ApiaryClient( 6746):     "locationType": "header",
W/ApiaryClient( 6746):     "location": "Authorization"
W/ApiaryClient( 6746):    }
W/ApiaryClient( 6746):   ],
W/ApiaryClient( 6746):   "code": 401,
W/ApiaryClient( 6746):   "message": "Login Required"
W/ApiaryClient( 6746):  }
W/ApiaryClient( 6746): }
W/ApiaryClient( 6746): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1588356315236262631&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6746): Headers:
W/ApiaryClient( 6746): accept-encoding: [gzip]
W/ApiaryClient( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6746): gdata-version: 2
,E/BooksSync( 6746): Soft error: 
E/BooksSync( 6746): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1588356315236262631&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6746): Headers:
E/BooksSync( 6746): accept-encoding: [gzip]
E/BooksSync( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6746): gdata-version: 2
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6746): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6746): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6746): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6746): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6746): {
E/BooksSync( 6746):  "error": {
E/BooksSync( 6746):   "errors": [
E/BooksSync( 6746):    {
E/BooksSync( 6746):     "domain": "global",
E/BooksSync( 6746):     "reason": "required",
E/BooksSync( 6746):     "message": "Login Required",
E/BooksSync( 6746):     "locationType": "header",
E/BooksSync( 6746):     "location": "Authorization"
E/BooksSync( 6746):    }
E/BooksSync( 6746):   ],
E/BooksSync( 6746):   "code": 401,
E/BooksSync( 6746):   "message": "Login Required"
E/BooksSync( 6746):  }
E/BooksSync( 6746): }
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6746): 	... 8 more
,E/BooksSync( 6746): Sync error
E/BooksSync( 6746): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6746): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1588356315236262631&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6746): Headers:
E/BooksSync( 6746): accept-encoding: [gzip]
E/BooksSync( 6746): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6746): gdata-version: 2
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6746): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6746): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6746): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6746): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6746): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6746): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6746): {
E/BooksSync( 6746):  "error": {
E/BooksSync( 6746):   "errors": [
E/BooksSync( 6746):    {
E/BooksSync( 6746):     "domain": "global",
E/BooksSync( 6746):     "reason": "required",
E/BooksSync( 6746):     "message": "Login Required",
E/BooksSync( 6746):     "locationType": "header",
E/BooksSync( 6746):     "location": "Authorization"
E/BooksSync( 6746):    }
E/BooksSync( 6746):   ],
E/BooksSync( 6746):   "code": 401,
E/BooksSync( 6746):   "message": "Login Required"
E/BooksSync( 6746):  }
E/BooksSync( 6746): }
E/BooksSync( 6746): 
E/BooksSync( 6746): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6746): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6746): 	... 8 more
I/BooksSync( 6746): Finished books sync
,D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1085936, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1097988592351; DSPS: 36119718; Offset : -4308833122
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=167951953, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{1b127e53 type 2 when 1116607 android} when 1116607
D/[Concierge]Service( 2648): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=167951953 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1117990921631; DSPS: 36775154; Offset : -4308823257
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1137992515881; DSPS: 37430567; Offset : -4308846412
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1157994172825; DSPS: 38085980; Offset : -4308807030
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1177995709866; DSPS: 38741391; Offset : -4308826282
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1197997153451; DSPS: 39396798; Offset : -4308817152
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1217998659994; DSPS: 40052208; Offset : -4308836489
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated(),
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,I/UsageStatsService( 1039): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1238000853656; DSPS: 40707640; Offset : -4308839988
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1258002388581; DSPS: 41363049; Offset : -4308800268
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1273003902350; DSPS: 41854620; Offset : -4308843104
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1293005466620; DSPS: 42510031; Offset : -4308835387
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1313007026999; DSPS: 43165443; Offset : -4308861583
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1333008584694; DSPS: 43820853; Offset : -4308830002
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1353010778975; DSPS: 44476285; Offset : -4308832725
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1373012332675; DSPS: 45131696; Offset : -4308835552
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1393013864459; DSPS: 45787106; Offset : -4308829829
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1413015434032; DSPS: 46442517; Offset : -4308816731
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1433016961425; DSPS: 47097927; Offset : -4308814880
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1453018516286; DSPS: 47753339; Offset : -4308846880
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1473020732323; DSPS: 48408771; Offset : -4308828108
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1493022296911; DSPS: 49064183; Offset : -4308850616
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 7270): 
D/AndroidRuntime( 7270): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7270): CheckJNI is OFF
D/AndroidRuntime( 7270): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1039): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1039): Killing 6643:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1039): WIN DEATH: Window{3bf56725 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1039): Client connection lost with reason: 4
D/InputDispatcher( 1039): Focus left window: Window{3bf56725 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher( 1039): Window went away: Window{3bf56725 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1039): Skipping PackageSetting{29f1f362 com.example.hello/10319} due to missing metadata
I/ActivityManager( 1039):   Force finishing activity ActivityRecord{17c855ea u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  349): DFP En is all cleared set to be enabled
W/ActivityManager( 1039): Spurious death for ProcessRecord{308f4390 6643:com.test.thalitest/u0a311}, curProc for 6643: null
I/ActivityManager( 1039): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1039):   Force finishing activity ActivityRecord{17c855ea u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1039): Duplicate finish request for ActivityRecord{17c855ea u0 com.test.thalitest/.MainActivity t4 f}
D/SplitWindowPolicy( 1983): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1983): topRunningActivity=ActivityInfo{3b650da5 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1983): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1983): topRunningActivity=ActivityInfo{6cd457a co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2096): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2096): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2096): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2096): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1936): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2096): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 3793): handleMessage: what(1000) actionID(0x1000003)
D/KeyguardModel( 1468): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1039): Reconfiguring input devices.  changes=0x00000010
E/LGBluetoothAvrcpQcomAdapter( 4194): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 4194): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2055): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3793): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/GeofencerStateMachine( 1843): Ignoring removeGeofence because network location is disabled.
I/ActivityManager( 1039): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7299 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/[LGHome]LGActivityUtil( 2096): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[SystemUI]QSlideListController( 1468): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2096): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2096): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1936): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3793): handleMessage: what(1000) actionID(0x1000004)
D/KeyguardModel( 1468): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1468): createShortcutInfo...
D/KeyguardModel( 1468): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1468): createShortcutInfo...
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1468): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1468): createShortcutInfo...
I/[LGHome]GBoardWebView( 2096): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 3793): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/GBoardWebViewUtils( 2096): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2096): , create_time: 1430558575574
I/GBoardWebViewUtils( 2096): , expire_time: 0
I/GBoardWebViewUtils( 2096): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2096): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2096): , display: false
I/GBoardWebViewUtils( 2096): , animation: false }
I/GBoardWebViewUtils( 2096): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2096): , create_time: 1430558575600
I/GBoardWebViewUtils( 2096): , expire_time: 0
I/GBoardWebViewUtils( 2096): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2096): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2096): , display: false
I/GBoardWebViewUtils( 2096): , animation: false }
I/GBoardWebViewUtils( 2096): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1455195784986
I/GBoardWebViewUtils( 2096): , create_time: 1455195785688
I/GBoardWebViewUtils( 2096): , expire_time: 0
I/GBoardWebViewUtils( 2096): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2096): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2096): , display: false
I/GBoardWebViewUtils( 2096): , animation: false }
D/WindowManager( 1039): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
I/SystemUI[Framework]( 1039): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx( 1039): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1039): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1039): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@71a8be4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher( 1039): Focus entered window: Window{1591f4cd u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1468): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1468): createShortcutInfo...
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
I/[LGHome]GBoardWebView( 2096): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/System.err( 4924): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4924): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4924): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4924): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4924): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4924): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4924): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4924): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4924): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4924): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4924): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4924): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/SplitUIManager( 1896): split_name #11 / not available #0
D/SplitUIService( 1896): removed split : 
D/KeyguardModel( 1468): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1468): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1468): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1468): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[SystemUI]NavigationThemeResource( 1468): notify navigation bar color(0x0)
I/[SystemUI]NavigationThemeResource( 1468): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1468):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1468): , Keyguard show=false, IME shown=false, Panel expanded=false
D/WallpaperManager( 2096): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
W/ActivityManager( 1039): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 4194): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 4194): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 4194): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 4194): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 4194): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 4194): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 4194): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 4194): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 4194): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 4194): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 4194): [BTUI] [-] updateMediaPlayerInfo
I/art     ( 1039): Explicit concurrent mark sweep GC freed 27797(1803KB) AllocSpace objects, 10(544KB) LOS objects, 33% free, 44MB/66MB, paused 8.195ms total 213.626ms
I/art     ( 1039): WaitForGcToComplete blocked for 45.510ms for cause Explicit
D/KeyguardModel( 1468): handleShortcutListChanged...
D/KeyguardModel( 1468): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1468): createShortcutInfo...
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
D/KeyguardModel( 1468): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1468): createShortcutInfo...
I/[LGHome]EVENT( 2096): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 2096): [Launcher.java:5349:onStop()]onStop
I/[LGHome]EVENT( 2096): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/KeyguardModel( 1468): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1468): createShortcutInfo...
I/PhoneWindow( 2096): [setNavigationBarColor] color=0x 0
D/[Concierge]WidgetView( 2096): notifyExtViewAvailable
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/art     ( 4975): Explicit concurrent mark sweep GC freed 16618(950KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 293us total 205.147ms
D/InputMethodManagerService( 1039): setImestate : 0
D/administrator( 1039): Handling package changes for user 0
W/InputMethodManagerService( 1039): Got RemoteException sending setActive(false) notification to pid 6643 uid 10311
D/SplitUIManager( 1896): split_name #11 / not available #0
I/SplitUIService( 1896): split app #11
D/KeyguardModel( 1468): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1468): createShortcutInfo...
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1468): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1468): createShortcutInfo...
W/ResourcesManager( 7299): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/KeyguardModel( 1468): handleShortcutListChanged...
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
D/PluginManager( 7299): init()
I/[LGHome]Launcher.Model( 2096): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/NotificationService( 1039): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1039): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1039): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1039): removeObsoleteFile: deleting file=4_task.xml
I/[LGHome]Launcher( 2096): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ThermalEngine(  342): Thermal-Server: Thermal received msg from  override
I/[LGHome]EVENT( 2096): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/Thermal-Lib( 3251): Thermal-Lib-Client: Client request sent
I/[LGHome]EVENT( 2096): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2096): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2096): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline( 1039): Timeline: Activity_windows_visible id: ActivityRecord{290606a5 u0 com.lge.launcher2/.Launcher t3} time:1509017
W/IInputConnectionWrapper( 2096): getTextBeforeCursor on inactive InputConnection
E/b       ( 1712): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]Launcher.Model( 2096): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2096): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2096): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2096): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2096): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2096): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2096): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2096): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/[Concierge]Service( 2648): onStartCommand(). Type : 8
D/[Concierge]Service( 2648): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2648): Update widget ID : 11
D/[Concierge]WidgetView( 2096): change position of spinner
I/[Concierge]WidgetView( 2096): initWebView(). Time : 1456927190796
D/[Concierge]Service( 2648): onStartCommand(). Type : 0
I/[Concierge]WebView( 2096): Return exist ConciergeWebView. Reuse : 784059772
D/[Concierge]WidgetView( 2096): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2096): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2096): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@182d8627
I/[LGHome]EVENT( 2096): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2096): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2096): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     ( 1039): Explicit concurrent mark sweep GC freed 6158(321KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.384ms total 183.749ms
I/[LGHome]EVENT( 2096): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 2096): getTextAfterCursor on inactive InputConnection
D/[Concierge]WidgetView( 2096): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2096): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2096): Widget kill message received. Destory myself. My : 1456925710250, New one : 1456927190796
D/[Concierge]WidgetView( 2096): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2096): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2096): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2096): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2096): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2096): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2096): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2096): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2096): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2096): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2096): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2096): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2096): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2096): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2096): Timeline: Activity_idle id: android.os.BinderProxy@1cfe730e time:1509172
D/AndroidRuntime( 7270): Shutting down VM
W/ExternalStrings( 7299): load override strings
W/ExternalStrings( 7299): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7299): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7299): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7299): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7299): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7299): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7299): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7299): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7299): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7299): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7299): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7299): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7299): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7299): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7299): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7299): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7299): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7299): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 7299): onCreate
W/ResourcesManager( 1039): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/Signer  ( 7299): override build config not found
D/Signer  ( 7299): value of property debug is false
W/ResourceType( 1039): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2096): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/LGMDMWrapper( 7299): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7299): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7299): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7299): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7299): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7299): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7299): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7299): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7299): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7299): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7299): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7299): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7299): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
I/chromium( 2096): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
V/LGMDMManager( 7299): Create singleton instance
I/GBoardtInterface( 2096): onReloaded()
I/GBoardWebViewClient( 2096): onPageFinished url:file:///android_asset/www/main.html
D/LGMDMWrapper( 7299): LG MDM library v4.0.0 is available on this device.
V/BoardContentProvider( 3793): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3793): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1936): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3793): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3793): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1936): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3793): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3793): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3793): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3793): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3793): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2096): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2096): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2096): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2096): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2096): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2096): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/PostponalbeReceiver( 7299): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/ContextImpl( 7299): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/ActivityManager( 1039): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7330 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6149:com.android.contacts/u0a19 (adj 15): empty #17
W/ActivityThread( 7299): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/libprocessgroup( 1039): failed to open /acct/uid_10019/pid_6149/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7330): onCreate
W/AppUp4:DB( 7330):  [AppBoxDatabaseHelper] construct
E/SQLiteDatabase( 7299): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7299): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7299): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7299): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7299): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.wsstorage.ConfigManager.ab(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.fw.ws.WSLicenseService.a(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.g.b.a(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7299): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7299): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7299): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7299): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7299): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7299): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7299): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7330): Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
E/SQLiteDatabase( 7330): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7330): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7330): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7330): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7330): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7330): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7330): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7330): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7330): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7330): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7330): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7330): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7330): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7330): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7330): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/SQLiteDatabase( 7330): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7330): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7330): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7330): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7330): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7330): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7330): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7330): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7330): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7330): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7330): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7330): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7330): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7330): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/AndroidRuntime( 7330): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 7330): FATAL EXCEPTION: main
E/AndroidRuntime( 7330): Process: com.lge.appbox.client, PID: 7330
E/AndroidRuntime( 7330): java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7330): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
E/AndroidRuntime( 7330): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/AndroidRuntime( 7330): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/AndroidRuntime( 7330): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/AndroidRuntime( 7330): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/AndroidRuntime( 7330): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7330): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7330): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/AndroidRuntime( 7330): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7330): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7330): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/AndroidRuntime( 7330): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/AndroidRuntime( 7330): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7330): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7330): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 7330): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 7330): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7330): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7330): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7330): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/AndroidRuntime( 7330): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/AndroidRuntime( 7330): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 7330): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/AndroidRuntime( 7330): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7330): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7330): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7330): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/AndroidRuntime( 7330): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 7330): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 7330): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/AndroidRuntime( 7330): 	... 11 more
I/Process ( 7330): Sending signal. PID: 7330 SIG: 9
E/DropBoxManagerService( 1039): Can't write: system_app_crash
E/DropBoxManagerService( 1039): java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1039): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1039): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1039): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1039): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1039): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1039): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1039): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1039): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1039): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1039): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1039): 	... 5 more
E/SQLiteDatabase( 7299): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
E/SQLiteDatabase( 7299): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7299): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7299): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7299): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7299): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7299): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7299): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7299): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7299): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7299): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7299): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7299): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7299): 	at com.mcafee.d.c.run(Unknown Source)

```
