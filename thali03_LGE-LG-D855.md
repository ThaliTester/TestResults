#### Test 61248225a3bd1fe_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
,D/DocsApplication( 6067): Installing DEX configuration.
D/DexInstaller( 6067): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 6067): Provided clientMode=RELEASE, packageInfo=PackageInfo{18e21244 com.google.android.apps.docs}
D/TAG     ( 6067): onCreate()
D/CrossAppStateProvider( 6067): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/AndroidRuntime( 6093): 
D/AndroidRuntime( 6093): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6093): CheckJNI is OFF
D/AndroidRuntime( 6093): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1033): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1975): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1033): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1033): setTaskToReturnTo : TaskRecord{3b3f353b #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1033): setTaskToReturnTo : TaskRecord{3b3f353b #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1033): AppWindowTokenEx init.. 
E/GBMv2   (  343): DFP En is all cleared set to be enabled
I/ActivityManager( 1033): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6119 uid=10319 gids={50319, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/InputDispatcher( 1033): Focus left window: Window{ecb37a7 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 2086): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[SystemUI]QPairHandler( 1452): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/AndroidRuntime( 6093): Shutting down VM
I/InputReader( 1033): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1452): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1452): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/administrator( 1033): Handling package changes for user 0
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/DSDPConnection( 1857): Display #0 changed.
D/SplitWindowPolicy( 1975): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1975): topRunningActivity=ActivityInfo{28695f00 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1975): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1975): topRunningActivity=ActivityInfo{9cfa339 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6119): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/NotificationService( 1033): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1033): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1033): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService( 1033): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/ActivityManager( 1033): Display changed displayId=0
V/BackupManagerService( 1033): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService( 1033): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@105c5156
W/ResourcesManager( 1033): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1033): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/Icing   ( 2344): Indexing 006D8E3EE7EAD3D24732771C6193DFFED0C57687 from com.google.android.googlequicksearchbox
I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
V/GmsNetworkLocationProvi( 1822): DISABLE
I/GCoreNlp( 1822): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/WebViewFactory( 6119): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/Icing   ( 2344): Loaded CLD2 Version V2.0 - 20141016
I/art     ( 1033): Explicit concurrent mark sweep GC freed 19924(973KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.519ms total 84.588ms
I/ActivityManager( 1033): Waited long enough for: ServiceRecord{236b6bb u0 com.lge.springcleaning/.service.AppCleanupService}
I/LibraryLoader( 6119): Loading: webviewchromium
I/LibraryLoader( 6119): Time to load native libraries: 10 ms (timestamps 6082-6092)
I/LibraryLoader( 6119): Expected native library version number "",actual native library version number ""
I/Icing   ( 2344): Indexing done 006D8E3EE7EAD3D24732771C6193DFFED0C57687
V/WebViewChromiumFactoryProvider( 6119): Binding Chromium to main looper Looper (main, tid 1) {a100eb0}
D/LocationProviderProxy( 1033): applying state to connected service
I/LibraryLoader( 6119): Expected native library version number "",actual native library version number ""
I/chromium( 6119): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6119): Initializing chromium process, renderers=0
W/art     ( 6119): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  315): registerClient() client 0xb14fdb20, uid 10319
W/chromium( 6119): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6119): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6119): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{38486289 type 2 when 66135 com.android.systemui} when 66135
D/BluetoothManagerService( 1033): Message: 20
D/BluetoothManagerService( 1033): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2184eaaf:true
I/Adreno-EGL( 6119): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6119): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6119): Build Date: 12/12/14 금
I/Adreno-EGL( 6119): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6119): Remote Branch: 
I/Adreno-EGL( 6119): Local Patches: 
I/Adreno-EGL( 6119): Reconstruct Branch: 
W/chromium( 6119): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6119): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6119): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6119): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6119): CordovaWebView is running on device made by: LGE
W/art     ( 6119): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6119): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6119): Render dirty regions requested: true
I/OpenGLRenderer( 6119): Initialized EGL, version 1.4
D/OpenGLRenderer( 6119): Enabling debug mode 0
D/Atlas   ( 6119): Validating map...
D/SplitWindow( 1033): check instance of lgWin Window{cdeb531 u0 com.example.hello/com.example.hello.MainActivity}
W/ActivityManager( 1033): Activity pause timeout for ActivityRecord{22c3d458 u0 com.example.hello/.MainActivity t4}
D/LgDataFeature( 6119): LgDataFeature() Constructor: none
D/LgDataFeature( 6119): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1033): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.example.hello
D/PhoneStatusBar( 1452): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
W/PhoneWindowManagerEx( 1033): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1033): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1033): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@55e7ac9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework]( 1033): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
D/PhoneStatusBar( 1452): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1452): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1452):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1452): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1033): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1033): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1033): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@55e7ac9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher( 1033): Focus entered window: Window{cdeb531 u0 com.example.hello/com.example.hello.MainActivity}
D/InputMethodManagerService( 1033): setImestate : 0
I/ActivityManager( 1033): Displayed com.example.hello/.MainActivity: +605ms (total +712ms)
I/Timeline( 1033): Timeline: Activity_windows_visible id: ActivityRecord{22c3d458 u0 com.example.hello/.MainActivity t4} time:66452
W/IInputConnectionWrapper( 6119): showStatusIcon on inactive InputConnection
W/IInputConnectionWrapper( 6119): getTextBeforeCursor on inactive InputConnection
I/Timeline( 6119): Timeline: Activity_idle id: android.os.BinderProxy@125c83e0 time:66466
E/b       ( 1686): Unable to connect to the editor to retrieve text... will retry later
W/IInputConnectionWrapper( 6119): getTextAfterCursor on inactive InputConnection
I/chromium( 6119): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 6119): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 6119): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6119): 
D/JsMessageQueue( 6119): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6119): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6119): 
D/jxcore_app_log( 6119): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435115264
D/JX-Cordova( 6119): jxcore cordova android initializing
W/jxcore-log( 6119): Initializing JXcore engine
W/jxcore-log( 6119): JXcore engine is ready
W/jxcore-log( 6119): Starting JXcore engine
D/LgDataFeature( 6067): LgDataFeature() Constructor: none
D/LgDataFeature( 6067): LgDataFeature() Constructor Done, null
W/m.example.hello( 6119): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7461]" dev="sockfs" ino=7461 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 6119): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 6119): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8474]" dev="sockfs" ino=8474 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 6119): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/m.example.hello( 6119): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30252]" dev="sockfs" ino=30252 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6119): Platform android
W/jxcore-log( 6119): 
W/jxcore-log( 6119): Process ARCH arm
W/jxcore-log( 6119): 
,W/GAV2    ( 6067): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/UEI.SmartControl( 5786): Internal timer expired: 1
,D/UEI.SmartControl( 5786): unbind internal service
I/jxcore-log( 6119): JXcore Cordova bridge is ready!
I/jxcore-log( 6119): 
W/jxcore-log( 6119): JXcore engine is started
I/ActivityManager( 1033): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6183 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,D/serial_port( 5786): close(fd = 25)
,I/UEI.SmartControl( 5786): Serial port is closed.
E/jxcore-log( 6119): >> LGE-LG-D855
E/jxcore-log( 6119): 
I/LockScreenSettings( 6183): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
I/jxcore-log( 6119): Total memory 2995761152
I/jxcore-log( 6119): 
I/jxcore-log( 6119): Free memory 551018496
I/jxcore-log( 6119): 
I/jxcore-log( 6119): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6119): 
I/jxcore-log( 6119): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6119): 
,I/jxcore-log( 6119): userPath [ 'www', 'www' ]
I/jxcore-log( 6119): 
I/jxcore-log( 6119): Size 1440 2392
I/jxcore-log( 6119): 
I/LockScreenSettings( 6183): New app installed broadcast received ..
I/jxcore-log( 6119): Screen Brightness 50
I/jxcore-log( 6119): 
E/jxcore-log( 6119): Dummy Error Log.
E/jxcore-log( 6119): 
I/LockScreenSettings( 6183): Number of installed packages  1
I/ActivityManager( 1033): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6207 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1033): Killing 5764:com.qualcomm.timeservice/1000 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_5764/cgroup.procs: No such file or directory
,W/ResourcesManager( 6207): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/GAV2    ( 6067): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager( 1033): Killing 5826:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_5826/cgroup.procs: No such file or directory
,E/GBMv2   (  343): DFP En is all cleared set to be enabled
E/GBMv2   (  343): Set value is all cleared set the max
I/GBMv2   (  343): DFP Enabled. Ignore VFP set
,I/jxcore-log( 6119): getBuffer is called!!!!
I/jxcore-log( 6119): 
,V/SIM_STK ( 1033): Menu title from STK is T-Mobile
I/GLSActivity( 2129): [ac] getting account id
,I/ActivityManager( 1033): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6237 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/art     (  347): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 469us total 29.071ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 20.316ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 20.144ms
,I/GLSUser ( 2129): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/EulaProviderUpdateObserver( 6237): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 6237): uri : package:com.example.hello
,I/ActivityManager( 1033): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6263 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1033): Killing 5847:com.android.settings/1000 (adj 15): empty #17
,E/WifiStateMachine( 1033):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1033):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,I/[SystemUI]LGPowerUI( 1452): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1452): On Skip Timer : true
D/KeyguardUpdateMonitor( 1452): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1452): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1975): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1975): Battery Level Remaining: 100%
D/LEDHandler( 1975): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]BatterySaverHandler( 1452): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 3839): Disconnected process message: 10, size: 0
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_5847/cgroup.procs: No such file or directory
D/LGDMClient( 4352): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4352): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/MainApplication( 5903): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController( 1033): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1452): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1452): On Skip Timer : true
I/GAV2    ( 5930): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 6263): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 6263): LgDataFeature() Constructor: none
,D/LgDataFeature( 6263): LgDataFeature() Constructor Done, null
,D/Finsky  ( 6263): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1033): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6310 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/ActivityManager( 1033): Waited long enough for: ServiceRecord{2b49b462 u0 com.android.calendar/.alerts.InitAlarmsService}
,W/Settings( 6263): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6263): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/DownloadManager( 3444): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3444): created cursor android.database.sqlite.SQLiteCursor@12d6ace6 on behalf of 6263
W/ResourcesManager( 6310): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6310): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager( 1033): Killing 5786:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/MultiDex( 6310): VM with version 2.1.0 has multidex support
I/MultiDex( 6310): install
I/MultiDex( 6310): VM has multidex support, MultiDex support library is disabled.
,I/QRemote ( 5487): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 5487): android.os.DeadObjectException
W/System.err( 5487): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5487): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5487): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5487): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 5487): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5487): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5487): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5487): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5487): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5487): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5487): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5487): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5487): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5487): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5487): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5487): android.os.DeadObjectException
W/System.err( 5487): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5487): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5487): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5487): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 5487): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5487): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5487): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5487): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5487): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5487): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5487): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5487): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5487): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5487): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5487): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 5487): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
D/Finsky  ( 6263): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_5786/cgroup.procs: No such file or directory
W/ActivityManager( 1033): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/Finsky  ( 6263): [1] 2.run: Finished loading 1 libraries.
D/QRemote ( 5487): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,I/QRemote ( 5487): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/Finsky  ( 6263): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager( 1033): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6338 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 5487): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/PackageBroadcastService( 2344): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 2344): Loading module com.google.android.gms.games from APK com.google.android.gms
V/JNIHelp ( 6310): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 6263): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1033): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=6358 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/ChimeraCfgMgr( 2344): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 2344): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 2344): Failed to find package metadata for com.example.hello
D/Vision  ( 2344): No vision deps
I/ConfigFetchService( 2344): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 2344): launchTask
D/[BNRAppListMgrReceiver]( 5903): android.intent.action.PACKAGE_ADDED : com.example.hello
I/PeopleContactsSync( 2344): CP2 sync disabled
V/ConfigFetchTask( 2344): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VPhRfDQm5srjPREIyYt44KKwTmXfqnunlYelK5WavhrhpUpAhWO4Azjy6YmAnluxpDmKZub62RbBlTk5JdBYo_l_nQIT7wj6NIxI9YBVJ5pZktAB6WzoZkifoCiyofkfvEqXUHzORaKzOVYsvJUoN99JUoT_WJv_YzxDVuitm4JEW09Y_0jeteNTQ9mo7RltcIS2B9iMfU_GbNEe5kKQL5XALBLhCicNaXbXqKrh7RpsRXCuo
,I/GoogleURLConnFactory( 2344): Using platform SSLCertificateSocketFactory
,W/ActivityThread( 6310): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6310): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@36ad5e3b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6310): Installed default security provider GmsCore_OpenSSL
D/UEI.SmartControl( 6338): Quickset Services start...
I/UEI.SmartControl( 6338): Manufacture = LGE
D/UEI.SmartControl( 6338): Id = LGNevo
D/UEI.SmartControl( 6338): File observer start...
,E/UEI.SmartControl( 6338): IR Port is disabled: false
D/UEI.SmartControl( 6338): Starting file observer...
D/UEI.SmartControl( 6338): Extracting JNI libs...
D/UEI.SmartControl( 6338): --- this system supports 32-bit or 64-bit only
W/ResourcesManager( 6358): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6358): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = android.clients.google.com, class = 1, type = 1
I/ActivityManager( 1033): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6389 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/MultiDex( 6358): VM with version 2.1.0 has multidex support
I/MultiDex( 6358): install
I/MultiDex( 6358): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6358): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/NotifUtils( 5930): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
D/UEI.SmartControl( 6338): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6338): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6338): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,W/ResourcesManager( 6389): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/libc-netbsd(  311): res_queryN name = android.clients.google.com succeed
I/UEI.SmartControl( 6338): --- Selecting new region: 6
I/UEI.SmartControl( 6338): Model = LG-D855
W/ActivityThread( 6358): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6358): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@36ad5e3b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6358): Installed default security provider GmsCore_OpenSSL
D/UEI.SmartControl( 6338): QS Service created
,I/NotifUtils( 5930): validateNotifications - cancelling account 61035162 / folder -317575340
I/UEI.SmartControl( 6338): Service initServices...
,W/NativeLibraryUtils( 6358): Install did not work
W/NativeLibraryUtils( 6358): java.io.IOException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 6358): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
W/NativeLibraryUtils( 6358): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
W/NativeLibraryUtils( 6358): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
W/NativeLibraryUtils( 6358): 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
W/NativeLibraryUtils( 6358): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 6358): Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 6358): 	at libcore.io.Posix.fcntlFlock(Native Method)
W/NativeLibraryUtils( 6358): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
W/NativeLibraryUtils( 6358): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
W/NativeLibraryUtils( 6358): 	... 4 more
D/UEI.SmartControl( 6338): QS start get config
I/ActivityManager( 1033): Killing 5487:com.lge.qremote/u0a112 (adj 15): empty #17
D/UEI.SmartControl( 6338): Loading JNI Libs...
,W/libprocessgroup( 1033): failed to open /acct/uid_10112/pid_5487/cgroup.procs: No such file or directory
,D/LgDataFeature( 6389): LgDataFeature() Constructor: none
,D/LgDataFeature( 6389): LgDataFeature() Constructor Done, null
I/ActivityManager( 1033): Killing 5868:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_10037/pid_5868/cgroup.procs: No such file or directory
,V/AlarmManager( 1033): RTC_WAKEUP set : Alarm{719fa14 type 0 when 1456842808365 com.android.vending} when 1456842808365
,D/Finsky  ( 6263): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/Finsky  ( 6263): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/UEI.SmartControl( 6338): Supports setup maps: true
D/UEI.SmartControl( 6338): QS start statue = true Error code = 0
I/UEI.SmartControl( 6338): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6338): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6338): ### init IR Blaster...
D/serial_port( 6338): Configuring serial port
,E/UEI.SmartControl( 6338): UEIBLaster setting for 616
I/UEI.SmartControl( 6338): Setting serial record hearder size = 2
I/UEI.SmartControl( 6338): configuring settings for MAXQ616
I/UEI.SmartControl( 6338): Get version...
I/Babel   ( 6389): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6389): MmsConfig.loadMmsSettings
D/UEI.SmartControl( 6338): serial port data available: 21
,D/UEI.SmartControl( 6338): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6338): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 6338): QS saving settings...
D/UEI.SmartControl( 6338): IR Blaster version: 25672567
W/AudioCapabilities( 6389): Unsupported mime audio/evrc
W/AudioCapabilities( 6389): Unsupported mime audio/qcelp
W/VideoCapabilities( 6389): Unrecognized profile 2130706433 for video/avc
D/UEI.SmartControl( 6338): serial port data available: 4
,W/AudioCapabilities( 6389): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6389): Unsupported mime audio/qcelp
W/AudioCapabilities( 6389): Unsupported mime audio/evrc
W/VideoCapabilities( 6389): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6389): Unsupported mime video/divx
W/VideoCapabilities( 6389): Unsupported mime video/divx311
W/VideoCapabilities( 6389): Unsupported mime video/divx4
W/VideoCapabilities( 6389): Unsupported mime video/mp4v-esdp
,I/UEI.SmartControl( 6338): Device manager: loading config....
D/UEI.SmartControl( 6338): ----------- loading internal config...
W/ContextImpl( 6338): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6338): Loading SETTINGS...
,I/VideoCapabilities( 6389): Unsupported profile 4 for video/mp4v-es
D/UEI.SmartControl( 6338): -- Open brand translation xml: brands_translations_ko
W/AudioCapabilities( 6389): Unsupported mime audio/eac3
W/AudioCapabilities( 6389): Unsupported mime audio/ac3
I/art     ( 1033): Explicit concurrent mark sweep GC freed 19643(946KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 43MB/65MB, paused 2.337ms total 134.778ms
W/AudioCapabilities( 6389): Unsupported mime audio/g726
I/Babel   ( 6389): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6389): MmsConfig.loadFromDatabase
I/UEI.SmartControl( 6338): Notify AllClients services are ready: 0
,E/UEI.SmartControl( 6338): Services init done
,D/UEI.SmartControl( 6338): -----service ready thread exits
D/UEI.SmartControl( 6338): QS Service init finished
D/UEI.SmartControl( 6338): QS Service version name: 2.1.91
D/UEI.SmartControl( 6338): QS Service version code: 201091
D/UEI.SmartControl( 6338): Service requested: Control
D/UEI.SmartControl( 6338): Service.onUnbind: IControl
D/UEI.SmartControl( 6338): unbind internal service
D/UEI.SmartControl( 6338): Service.onDestroy
D/UEI.SmartControl( 6338): Lock is in USE false
,D/UEI.SmartControl( 6338): unbind internal service
D/serial_port( 6338): close(fd = 25)
W/AudioCapabilities( 6389): Unsupported mime audio/wma-voice
I/UEI.SmartControl( 6338): Serial port is closed.
W/AudioCapabilities( 6389): Unsupported mime audio/x-ms-wma
I/UEI.SmartControl( 6338): Serial port is closed.
D/UEI.SmartControl( 6338): Blaster closed
D/UEI.SmartControl( 6338): Shut down QS...
D/UEI.SmartControl( 6338): Stopping QS lib
D/UEI.SmartControl( 6338): QS lib stop result = true
D/UEI.SmartControl( 6338): Stopped QS lib
D/UEI.SmartControl( 6338): Stopped file observer...
D/UEI.SmartControl( 6338): QS shutdown complete
,W/Settings( 6389): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UEI.SmartControl( 6338): QS Service created
E/Babel   ( 6389): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6389): MmsConfig.loadFromResources
W/AudioCapabilities( 6389): Unsupported mime audio/adpcm
E/Babel   ( 6389): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6389): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/VideoCapabilities( 6389): Unsupported mime video/theora
,W/VideoCapabilities( 6389): Unsupported mime video/mjpg
W/Finsky  ( 6263): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/UEI.SmartControl( 6338): Service initServices...
D/UEI.SmartControl( 6338): QS start get config
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CalendarWeatherReceiver( 5210): Get action=com.lge.calendar.action.WEATHER_SERVICE_START
,D/AlertReceiver( 5210): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/AgendaWidgetManager( 5210): [updateWidgets] 
D/AlertService( 5210): 0 Action = android.intent.action.PROVIDER_CHANGED
D/MonthWidgetProvider( 5210): [onReceive]
D/CalendarWidgetProvider( 5210): [onReceive]
D/CalendarWidgetProvider( 5210): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,W/Finsky  ( 6263): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/CalendarTypeController( 5210): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 5210): [onReceive]
,D/CalendarWidgetProvider( 5210): [onReceive]
D/CalendarWidgetProvider( 5210): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 5210): [onCreate] mContext.getPackageName() = com.android.calendar
D/GCM     ( 2129): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2129): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2344): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WearableService( 6358): callingUid 10005, callindPid: 6358
,D/LocationInitializer( 2344): Restart initialization of location
E/MDM     ( 1822): [100] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/SIM_STK ( 1033): Menu title from STK is T-Mobile
,E/SQLiteLog( 6389): (284) automatic index on conversation_participants_view(conversation_id)
,V/DownloadManager( 3444): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='197' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3444): created cursor android.database.sqlite.SQLiteCursor@df9e227 on behalf of 2344
E/SQLiteLog( 6389): (284) automatic index on conversation_participants_view(conversation_id)
D/GCM     ( 2129): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/SQLiteLog( 6389): (284) automatic index on conversation_participants_view(conversation_id)
I/ConfigFetchService( 2344): fetch service done; releasing wakelock
I/ConfigFetchService( 2344): stopping self
D/ChimeraCfgMgr( 2344): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2344): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
E/SQLiteLog( 6389): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 6389): (284) automatic index on conversation_participants_view(conversation_id)
V/DownloadManager( 3444): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3444): created cursor android.database.sqlite.SQLiteCursor@27775cd4 on behalf of 2344
V/DownloadManager( 3444): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3444): created cursor android.database.sqlite.SQLiteCursor@c134e7d on behalf of 2344
,I/art     ( 3444): Explicit concurrent mark sweep GC freed 4029(282KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 27MB/59MB, paused 944us total 25.922ms
,W/ResourcesManager( 6389): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6389): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6389): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/UEI.SmartControl( 6338): Supports setup maps: true
,D/UEI.SmartControl( 6338): QS start statue = true Error code = 0
I/UEI.SmartControl( 6338): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6338): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6338): ### init IR Blaster...
D/serial_port( 6338): Configuring serial port
E/UEI.SmartControl( 6338): UEIBLaster setting for 616
I/UEI.SmartControl( 6338): Setting serial record hearder size = 2
I/UEI.SmartControl( 6338): configuring settings for MAXQ616
I/UEI.SmartControl( 6338): Get version...
I/ActivityManager( 1033): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6456 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/UEI.SmartControl( 6338): serial port data available: 21
,W/System  ( 6389): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6389): Installed default security provider GmsCore_OpenSSL
D/UEI.SmartControl( 6338): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6338): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6338): QS saving settings...
D/UEI.SmartControl( 6338): IR Blaster version: 25672567
D/UEI.SmartControl( 6338): serial port data available: 4
,W/ResourcesManager( 6456): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/QRemote ( 6456): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,W/ContextImpl( 6338): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6338): Services init done
D/UEI.SmartControl( 6338): QS Service init finished
D/UEI.SmartControl( 6338): QS Service version name: 2.1.91
D/UEI.SmartControl( 6338): QS Service version code: 201091
I/UEI.SmartControl( 6338): Device manager: loading config....
D/UEI.SmartControl( 6338): Service requested: Control
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 6338): ----------- loading internal config...
E/UEI.SmartControl( 6338): Loading SETTINGS...
D/UEI.SmartControl( 6338): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6338): -- Open brand translation xml: brands_translations_ko
E/ActivityThread( 6338): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@2ffb35ba that was originally bound here
E/ActivityThread( 6338): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@2ffb35ba that was originally bound here
E/ActivityThread( 6338): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
E/ActivityThread( 6338): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
E/ActivityThread( 6338): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
E/ActivityThread( 6338): 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
E/ActivityThread( 6338): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6338): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6338): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6338): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6338): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
E/ActivityThread( 6338): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 6338): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 6338): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6338): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6338): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/ActivityThread( 6338): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6338): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6338): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/ActivityThread( 6338): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/UEI.SmartControl( 6338): Internal service binding...
I/UEI.SmartControl( 6338): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6338): -----service ready thread exits
,D/QRemote ( 6456): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6456): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6456): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6456): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6456): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6456): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QRemote ( 6456): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
V/QRemote ( 6456): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6456): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6456): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
W/Finsky  ( 6263): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 6263): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6263): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6263): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
D/DeviceConnectionService( 1822): client connected with version: 7571000
,D/LgDataFeature( 6456): LgDataFeature() Constructor: none
D/LgDataFeature( 6456): LgDataFeature() Constructor Done, null
V/SoundPool( 6456): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
E/Babel   ( 6389): UserRecoverableAuthException.
E/Babel   ( 6389): cfq: BadAuthentication
E/Babel   ( 6389): 	at cfn.a(Unknown Source)
E/Babel   ( 6389): 	at f.a(PG:191)
E/Babel   ( 6389): 	at ava.a(PG:88)
E/Babel   ( 6389): 	at ava.a(PG:128)
E/Babel   ( 6389): 	at bjs.a(PG:255)
E/Babel   ( 6389): 	at bep.a(PG:602)
E/Babel   ( 6389): 	at bep.a(PG:469)
E/Babel   ( 6389): 	at bpo.run(PG:1141)
,E/Babel   ( 6389): Error getting auth token
E/Babel   ( 6389): bxl
E/Babel   ( 6389): 	at f.a(PG:201)
E/Babel   ( 6389): 	at ava.a(PG:88)
E/Babel   ( 6389): 	at ava.a(PG:128)
E/Babel   ( 6389): 	at bjs.a(PG:255)
E/Babel   ( 6389): 	at bep.a(PG:602)
E/Babel   ( 6389): 	at bep.a(PG:469)
E/Babel   ( 6389): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6389): error sending REQ[fc:0; creat:1456842809178; type:bev-473516339]; took 83 ms (error code == 100)
E/Babel   ( 6389): Account registration failedRedacted-21
V/SoundPool( 6456): load: fd=27, offset=10857164, length=17813, priority=1
E/Babel   ( 6389): bph: null -- null
E/Babel   ( 6389): 	at ava.a(PG:120)
E/Babel   ( 6389): 	at ava.a(PG:128)
E/Babel   ( 6389): 	at bjs.a(PG:255)
E/Babel   ( 6389): 	at bep.a(PG:602)
E/Babel   ( 6389): 	at bep.a(PG:469)
E/Babel   ( 6389): 	at bpo.run(PG:1141)
V/SoundPool( 6456): create sampleID=1, fd=28, offset=17813 length=10857164
V/SoundPool( 6456): doLoad: loading sample sampleID=1
I/Babel   ( 6389): Account setup failed with error state:106 account:Redacted-21
V/SoundPool( 6456): Start decode
V/MediaPlayer[Native]( 6456): decode(28, 10857164, 17813)
I/Babel   ( 6389): Account sign in complete with state 106account: Redacted-21
V/MediaPlayerService(  315): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  315): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  315): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  315): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  315): player type = 3
V/AwesomePlayer(  315): AwesomePlayer create()
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): setAudioSink() 
V/AwesomePlayer(  315): reset_l() 
I/QRemote ( 6456): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/AudioCache(  315): notify(0xb5474940, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/Utils   (  315): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  315): setDataSource_l dataSource
V/LGParserOSAL(  315): SniffLGParser start
V/LGParserOSAL(  315): MainType:5, SubType=0
V/LGParserOSAL(  315): #### check Mime : application/ogg
V/LGParserOSAL(  315): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  315): Use LGExtractor :application/ogg 
I/art     ( 6389): Note: end time exceeds epoch: 
D/QRemote ( 6456): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6456): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGMDMManager( 6456): Create singleton instance
V/LGParserOSAL(  315): supported mime: application/ogg
V/AwesomePlayer(  315): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  315): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  315): mBitrate = -1 bits/sec
V/AwesomePlayer(  315): AudioTrack Setting
V/AwesomePlayer(  315): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  315): setAudioSource() 
V/MediaPlayerService(  315): prepare
V/AwesomePlayer(  315): prepareAsync_l() 
V/MediaPlayerService(  315): wait for prepare
V/AwesomePlayer(  315): onPrepareAsyncEvent() 
V/AwesomePlayer(  315): initAudioDecoder() 
W/Utils   (  315): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  315): isOffloadSupported()
V/AudioPolicyManager(  315): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  315): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  315): isAudioPlaybackHookOn() false
,V/AwesomePlayer(  315): getUseOffload() = 0 
V/OMXCodec(  315): OMXCodec::Create
V/OMXCodec(  315): findMatchingCodecs()
,V/OMXCodec(  315): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  315): matchingCodecs.size()=1
V/OMXCodec(  315): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  315): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  315): LG Codec Adapter start
V/OMXCodec(  315): OMXCodec Createtor
V/OMXCodec(  315): setComponentRole
V/OMXCodec(  315): configureCodec protected=0
V/LGCodecAdapter(  315): called getLGCodecSpecificData
V/LGCodecOSAL(  315): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  315): Called LGconfigureCodecMETA
V/LGCodecOSAL(  315): Called LGconfigureCodecMSG
V/LGCodecOSAL(  315): Not support LGCodec
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  315): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  315): Could not offload audio decode, try pcm offload
W/Utils   (  315): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  315): isOffloadSupported()
V/AudioPolicyManager(  315): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  315): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  315): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  315): init()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  315): allocateBuffers
V/OMXCodec(  315): allocateBuffersOnPort portIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb1434240 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca60 on output port
V/OMXCodec(  315): init() mAsyncCompletion wait!!! 
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  315): init() mAsyncCompletion wait!!! 
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  315): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  315): finishAsyncPrepare_l() 
V/AudioCache(  315): notify(0xb5474940, 5, 0, 0)
V/AudioCache(  315): ignored
V/AudioCache(  315): notify(0xb5474940, 1, 0, 0)
V/AudioCache(  315): prepared
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): start
V/AwesomePlayer(  315): play_l() 
V/AwesomePlayer(  315): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  315): createAudioPlayer_l
V/AwesomePlayer(  315): seekAudioIfNecessary_l() 
V/AwesomePlayer(  315): startAudioPlayer_l() 
D/AudioPlayer(  315): start of Playback, useOffload 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V,/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
I/art     ( 2129): Explicit concurrent mark sweep GC freed 18878(1062KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 959us total 32.024ms
V/OMXCodec(  315): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  315): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795904
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796144
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796384
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  315): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb17ad380 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  315): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  315): notify(0xb5474940, 6, 0, 0)
V/AudioCache(  315): ignored
V/MediaPlayerService(  315): wait for playback complete
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae504000, 0xb57ee000, 4096)
I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae505000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae506000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae507000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae508000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae509000, 0xb57ee000, 4096)
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae50a000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae50b000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae50c000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae50d000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae50e000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae50f000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae510000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae511000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae512000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae513000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae514000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae515000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae516000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae517000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae518000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae519000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae51a000, 0xb57ee000, 4096)
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae51b000, 0xb57ee000, 4096)
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae51c000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae51d000, 0xb57ee000, 4096)
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5036
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae51e000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae51f000, 0xb57ee000, 4096)
W/ResourcesManager( 2129): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae520000, 0xb57ee000, 4096)
D/QRemote ( 6456): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae521000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae522000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae523000, 0xb57ee000, 4096)
D/QRemote ( 6456): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae524000, 0xb57ee000, 4096)
I/QRemote ( 6456): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae525000, 0xb57ee000, 4096)
I/UEI.SmartControl( 6338): ------ IControl API: 11
D/UEI.SmartControl( 6338): File observer start...
E/UEI.SmartControl( 6338): IR Port is disabled: false
D/UEI.SmartControl( 6338): Starting file observer...
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae526000, 0xb57ee000, 4096)
I/UEI.SmartControl( 6338): Registering callback...
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae527000, 0xb57ee000, 4096)
I/UEI.SmartControl( 6338): ------ IControl API: 19
V/AudioCache(  315): write(0xb57ee000, 4096)
I/UEI.SmartControl( 6338): Registering Services Ready callback...
V/AudioCache(  315): memcpy(0xae528000, 0xb57ee000, 4096)
I/UEI.SmartControl( 6338): Notify client services are ready...
I/QRemote ( 6456): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae529000, 0xb57ee000, 4096)
D/QRemote ( 6456): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6456): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6456): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae52a000, 0xb57ee000, 4096)
D/QRemote ( 6456): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6338): ------ IControl API: 8
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae52b000, 0xb57ee000, 4096)
D/QRemote ( 6456): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6456): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae52c000, 0xb57ee000, 4096)
D/QRemote ( 6456): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6456): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae52d000, 0xb57ee000, 4096)
D/QRemote ( 6456): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6456): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae52e000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae52f000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae530000, 0xb57ee000, 4096)
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae531000, 0xb57ee000, 4096)
,V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae532000, 0xb57ee000, 4096)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] No more output data.
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae533000, 0xb57ee000, 4096)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae534000, 0xb57ee000, 4096)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AudioCache(  315): write(0xb57ee000, 4096)
V/AudioCache(  315): memcpy(0xae535000, 0xb57ee000, 4096)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/OMXCodec(  315): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  315): postAudioEOS() 
V/AudioCache(  315): write(0xb57ee000, 280)
V/AudioCache(  315): memcpy(0xae536000, 0xb57ee000, 280)
V/AwesomePlayer(  315): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  315): onStreamDone
V/AwesomePlayer(  315): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  315): notify(0xb5474940, 2, 0, 0)
V/AudioCache(  315): playback complete
V/AwesomePlayer(  315): pause_l() 
V/AudioCache(  315): wait - success
V/AudioCache(  315): notify(0xb5474940, 7, 0, 0)
V/MediaPlayerService(  315): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/AudioPlayer(  315): Pause Playback at 1068125
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb5474940, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/AudioPlayer(  315): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb1434240 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb17ad380 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  315): AudioPlayer releasing audio source
D/AudioPlayer(  315): AudioPlayer done releasing audio source
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): ~AwesomePlayer call
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/SoundPool( 6456): close(28)
V/SoundPool( 6456): pointer = 0xa002b000, size = 205080, sampleRate = 48000, numChannels = 2
I/ActivityManager( 1033): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6491 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
D/QRemote ( 6456): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
D/QRemote ( 6456): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1033): Killing 5741:com.lge.clock/u0a10 (adj 15): empty #17
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
W/libprocessgroup( 1033): failed to open /acct/uid_10010/pid_5741/cgroup.procs: No such file or directory
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/Babel   ( 6389): Unexpected exception while authenticating.
E/Babel   ( 6389): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6389): 	at cfn.b(Unknown Source)
E/Babel   ( 6389): 	at cfn.a(Unknown Source)
E/Babel   ( 6389): 	at f.a(PG:188)
E/Babel   ( 6389): 	at ava.b(PG:143)
E/Babel   ( 6389): 	at bnr.run(PG:5415)
E/Babel   ( 6389): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6389): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6389): 	at java.lang.Thread.run(Thread.java:818)
,D/LgeQuickCoverNLService( 1402): onNotificationPosted
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
W/ResourcesManager( 6491): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{239a1b96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/CalendarProvider2( 6491): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@18e21244
,D/CalendarProvider2( 6491): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6491): Created com.android.providers.calendar.CalendarAlarmManager@39701129(com.android.providers.calendar.CalendarProvider2@18e21244)
D/CalendarProviderBroadcastReceiver( 6491): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6491): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6491): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6491): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6491): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 6491): (284) automatic index on view_events(_id)
I/ActivityManager( 1033): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6510 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/CalendarProvider2( 6491): [IntentService] Release Lock
D/CalendarProvider2( 6491): CalendarProviderIntentService.onDestroy()
I/ActivityManager( 1033): Killing 5510:com.google.android.music:main/u0a92 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_10092/pid_5510/cgroup.procs: No such file or directory
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{2b816c1b type 2 when 71040 android} when 71040
,I/DigitalAppWidgetProvider( 6510): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 5043): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 15:33:29
D/Weather.Utils( 5043): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 5043): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 5043): 2 : This is isUpdating : false
D/Weather_cast( 5043): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 5043): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 15:33:29
V/QRemote ( 6456): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6456): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6456): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6456): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1456842809913]
V/QRemote ( 6456): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6456): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6456): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6456): [RemoteAppWidgetManager.java:36:startLoading()] oooooo 140518:startLoading:sWidgetHandler has [3] at [1456842809925]. skip
D/QRemote ( 6456): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,I/ActivityManager( 1033): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=6531 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1033): Killing 5968:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10008/pid_5968/cgroup.procs: No such file or directory
I/MusicStore( 6531): Database version: 100
,D/LgDataFeature( 6531): LgDataFeature() Constructor: none
D/LgDataFeature( 6531): LgDataFeature() Constructor Done, null
,I/ConfigStore( 6531): Config Database version: 1
,I/art     ( 1033): Explicit concurrent mark sweep GC freed 13617(604KB) AllocSpace objects, 1(144KB) LOS objects, 33% free, 44MB/66MB, paused 2.588ms total 155.923ms
,E/PlayEventLogger( 6531): Invalid device id bea67b7c50ddc6a9
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6531): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6531): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6531): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/MediaRouter( 6531): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/NetworkMonitor( 6531): type=WIFI subType= reason=null isConnected=true
,I/GAV2    ( 6067): Thread[GAThread,5,main]: No campaign data found.
,I/NetworkMonitor( 6531): type=WIFI subType= reason=null isConnected=true
,I/AppUp4:CustModeStarterReceiver( 5990): onReceive
I/MusicLeanback( 6531): Stop autocaching.
I/MusicLeanback( 6531): Stop autocaching.
I/GoogleHttpClient( 6531): Falling back to old http client 0 java.lang.NoSuchMethodException: <init> [class android.content.Context, class java.lang.String, boolean, boolean]
,I/MusicLeanback( 6531): Stop autocaching.
I/MusicLeanback( 6531): Stop autocaching.
,D/LgDataFeature( 5990): LgDataFeature() Constructor: none
D/LgDataFeature( 5990): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 5990): Context : android.app.ReceiverRestrictedContext@2f7901f3
D/AppUp4:CustFacade( 5990): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5990): isPhone : true
D/AppUp4:CustModeStarterReceiver( 5990): begin check event
I/AppUp4:CustModeStarterReceiver( 5990): Event For Nothing, skip.
D/WearableClient( 6531): WearableClientImpl.onPostInitHandler: done
,I/MusicLeanback( 6531): Conditions not met for autocaching.
D/WearableClient( 6531): WearableClientImpl.onPostInitHandler: done
D/WearableClient( 6531): WearableClientImpl.onPostInitHandler: done
,I/MusicLeanback( 6531): Stop autocaching.
E/GmsUtils( 6531): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
E/GmsUtils( 6531): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
I/UpdateIcingCorporaServi( 4606): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/BluetoothManagerService( 1033): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1033): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3e8153f4 mBinding = false
,D/LockScreenSettings( 6183): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6183): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6183): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6183): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6183): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 6183): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
D/BluetoothManagerService( 1033): Message: 2
D/LocationManagerService( 1033): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1033): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1033): JNI:system_update. Event-4
,D/BluetoothManagerService( 1033): Sending off request.
D/LGBluetoothServiceAdapter( 3839): [BTUI] Precleanup
D/BluetoothAdapterState( 3839): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3839): Setting state to 13
I/BluetoothAdapterState( 3839): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3839): onBluetoothDisable()
I/BluetoothAdapterState( 3839): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/WifiService( 1033): New client listening to asynchronous messages
D/BluetoothManagerService( 1033): Message: 60
D/BluetoothManagerService( 1033): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1033): Bluetooth State Change Intent: 12 -> 13
D/WifiServiceImplEx( 1033): setWifiEnabled: false pid=6119, uid=10319, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1033): setWifiEnabled: false pid=6119, uid=10319
E/WifiService( 1033): Invoking mWifiStateMachine.setWifiEnabled
,I/[SystemUI]BluetoothHandler( 1452): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1975): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/BluetoothMapService( 3839): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3839): STATE_TURNING_OFF
V/BluetoothMapService( 3839): Handler(): got msg=4
D/BluetoothMapService( 3839): MAP Service closeService in
D/BluetoothMapMasInstance( 3839): MAP Service shutdown
D/BluetoothAdapterProperties( 3839): Scan Mode:20
V/BluetoothMapMasInstance( 3839): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3839): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3839): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3839): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3839): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3839): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3839): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3839): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/BluetoothAdapterState( 3839): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BluetoothSapService( 3839): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 3839): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x000f
D/LGBluetoothMapAdapter( 3839): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3839): MAP Service closeService out
V/BtOppService( 3839): Receiver DISABLED_ACTION 
W/bt-btif ( 3839): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
V/BluetoothFtpService:RfcommSocketAcceptThread( 3839): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothPbapService( 3839): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 3839): stopping Accept Thread
V/BtOppRfcommListener( 3839): close mBtServerSocket
E/BtOppRfcommListener( 3839): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BtOppRfcommListener( 3839): waiting for thread to terminate
I/BtOppRfcommListener( 3839): BluetoothSocket listen thread finished
,W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3839): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3839): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x001b
,W/bt-l2cap( 3839): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3839): bta_gattc_deregister Deregister Failedm unknown client cif
V/BtOppRfcommListener( 3839): done waiting for thread to terminate
,D/LocationManagerService( 1033): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1033): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1033): JNI:system_update. Event-4
E/WifiStateMachine( 1033):  ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
I/jxcore-log( 6119): ****TEST TOOK:  5098  ms ****
I/jxcore-log( 6119): 
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1033): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1033): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1033): doBoolean: SET_NETWORK 0 bssid any
I/jxcore-log( 6119): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6119): 
D/WifiNative-wlan0( 1033): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1033): doBoolean: SAVE_CONFIG
I/ActivityManager( 1033): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6597 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BtOppService( 3839): onDestroy
D/LGBluetoothOppAdapter( 3839): [BTUI] LGBluetoothOppAdapter cleanup
I/ActivityManager( 1033): Killing 5582:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10023/pid_5582/cgroup.procs: No such file or directory
,D/KeyguardViewMediator( 1452): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/WifiNative-wlan0( 1033): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1033): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1033): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1033): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET ps 1
D/WifiNative-wlan0( 1033): SET ps 1: returned true
D/DhcpStateMachine( 1033): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  311): Clearing all IP addresses on wlan0
D/KeyguardUpdateMonitor( 1452): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1452): doKeyguard: not showing because lockscreen is off
V/NativeCrypto( 2129): Read error: ssl=0xaa6d9c00: I/O error during system call, Connection timed out
V/NativeCrypto( 2129): SSL shutdown failed: ssl=0xaa6d9c00: I/O error during system call, Broken pipe
,D/PackageBroadcastService( 2344): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 2344): Null package name or gms related package.  Ignoreing.
,D/ConnectivityService( 1033): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Checking http://clients3.google.com/generate_204 on "NG700"
W/ResourcesManager( 6597): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/GCM     ( 2129): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ConnectivityService( 1033): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1033): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1033):  WaitForP2pDisableState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1033):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1033):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1033): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1033):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
D/DSQN    ( 1033): Dns fail occured do internet check.
D/LGWifiP2pService( 1033): InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1033): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3baccb7d
D/LGWifiP2pService( 1033): P2pDisablingState
D/LGWifiP2pService( 1033): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): p2p socket connection lost
D/LGWifiP2pService( 1033): P2pDisabledState
D/WifiHS20( 1033): hidePasspointNotification off =false
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1033): hidePasspointNotification off =false
E/WifiStateMachine( 1033):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService( 1033): SCAN_AVAILABLE : 1
D/RttService( 1033): SCAN_AVAILABLE : 1
D/DSQN    ( 1033): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1033): try Internet connection check
E/WifiStateMachine( 1033):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1033): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiScanningService( 1033): DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1033): EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
V/WfdStateTracker( 1975): handleWifiStateChangedEvent: 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/LGWifiP2pService( 1033): P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1975): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1975): WifiP2pState is changed : false
,D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WfdsService( 1975): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1975): Set the WFDS Monitor: false
D/WfdsMonitor( 1975): WFDS Monitor is stopped
D/WfdsService( 1975): STATE : WfdsDisabledState - enter
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/CtrlSupplicant( 1975): Received on exit socket, terminate
E/CtrlSupplicant( 1975): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
W/WfdsSession:Controller( 1975): DefaultState - msg [9441355] is not handled
D/WfdsMonitor( 1975): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1975): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1975): DefaultState - msg [9445378] is not handled
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1033): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET ps 1
D/WifiNative-wlan0( 1033): SET ps 1: returned true
,W/ResourcesManager( 6597): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6597): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6597): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6597): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6597): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/AuthorizationBluetoothService( 2129): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2344): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/CommandListener(  311): Clearing all IP addresses on wlan0
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1033): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1033): disableDataServiceNotify
D/DSQN    ( 1033): stop dsqn bin
D/DSQN    ( 1033): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/DSQN    ( 1033): ThreadTCPConnectionCheck DNS fail internet is not possible
D/DSQN    ( 1033): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1033): InternetcheckProgress is not set don't send DS quality intent
D/WifiNative-p2p0( 1033): doBoolean: TERMINATE
D/WifiHS20( 1033): hidePasspointNotification off =false
D/WifiNative-p2p0( 1033): TERMINATE: returned true
E/WifiStateMachine( 1033): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1033): useWiFiOffloading() : false
E/WifiStateMachine( 1033): CONFIG_LGE_WLAN_PATH : true
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1033):  SupplicantStoppingState CMD_SET_COUNTRY_CODE 1 0 cz
V/WfdStateTracker( 1975): WfdStateTracker handleDirectStateChangedEvent: 6
,D/ConnectivityService( 1033): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/WifiServerServiceExt( 1033): WIFI_STATE_CHANGED_ACTION [0]
,D/WifiServerServiceExt( 1033): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): setSupplicantStateDISCONNECTED
D/ConnectivityService( 1033): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1033): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1452): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1033): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1033): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1033): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1033): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1033): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1033): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1033): ignore wifi update if we are not in OPENING or CLOSING
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1033): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/MDM     ( 1822): [82] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1033): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1033): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1033): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy( 1033): [LG_RESTRICTED] !!!isConnected  type  :1
,D/LocSvc_java( 1033): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1033): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1033): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1033): ignore wifi update if we are not in OPENING or CLOSING
D/TelephonyNetworkFactory-1( 1857): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1857):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1033): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1033):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService( 1033): Removing idletimer
W/Settings( 1033): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService( 1033): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/LocationInitializer( 2344): Restart initialization of location
I/Icing   ( 2344): updateResources: need to parse f{com.google.android.gms}
D/GCM     ( 2129): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2129): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/TelephonyIcons( 1452): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
V/GmsCoreStatsServiceLauncher( 2344): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1822): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/DhcpStateMachine( 1033): StoppedState
D/DhcpStateMachine( 1033): StoppedState{ when=-145ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyIcons( 1452): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1033):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_ON_QUIT 0 0
D/LocationInitializer( 2344): Restart initialization of location
D/AndroidRuntime( 6615): 
D/AndroidRuntime( 6615): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2682): monitor socket send errors count : 1
I/wpa_supplicant( 2682): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1975-2\x00 that cannot receive messages
D/WifiMonitor( 1033): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1033): Dropping event because (p2p0) is stopped
,D/AndroidRuntime( 6615): CheckJNI is OFF
W/ContextImpl( 6597): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/BluetoothPbapReceiver( 3839): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3839): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3839): ***********state = 13
V/BluetoothPbapReceiver( 3839): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3839): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3839): state: 13
V/BluetoothPbapService( 3839): Pbap Service closeService in
D/BluetoothManagerService( 1033): Message: 20
D/BluetoothManagerService( 1033): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@97e5989:true
,I/wpa_supplicant( 2682): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
W/wpa_supplicant( 2682): USIM:  scard_deinit function
,D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
E/WifiMonitor( 1033): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
D/Tethering( 1033): InitialState.processMessage what=4
E/WifiMonitor( 1033): WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
E/WifiStateMachine( 1033):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=72723
E/WifiStateMachine( 1033):  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=72723
E/WifiStateMachine( 1033):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=72724  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1033):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=72724  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
I/ActivityManager( 1033): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6630 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,V/BluetoothPbapService( 3839): successfully stopped pbap service
V/BluetoothPbapService( 3839): Pbap Service closeService out
V/BluetoothPbapService( 3839): Pbap Service onDestroy
V/BluetoothPbapService( 3839): Pbap Service closeService in
V/BluetoothPbapService( 3839): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3839): [BTUI] cleanup
D/Tethering( 1033): sendTetherStateChangedBroadcast 0, 0, 0
,D/BluetoothManagerService( 1033): Message: 30
E/WifiStateMachine( 1033):  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
V/QRemote ( 6456): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3503
I/art     (  347): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 477us total 23.965ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 411us total 18.673ms
,D/BluetoothManagerService( 1033): Message: 30
D/LocalBluetoothProfileManager( 6597): Adding local MAP profile
D/BluetoothMap( 6597): Create BluetoothMap proxy object
D/BluetoothManagerService( 1033): Message: 30
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 418us total 18.386ms
D/BluetoothManagerService( 1033): Message: 30
D/LocalBluetoothProfileManager( 6597): LocalBluetoothProfileManager construction complete
,D/LGBluetoothFeatureConfig( 6597):  get() - isFeatureLoaded : false
V/QRemote ( 6456): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6456): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 6456): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6456): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1456842811584]
D/LGBluetoothUserBindClient( 6597): [BTUI] initUserBindClient
V/QRemote ( 6456): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
W/ContextImpl( 6597): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
E/QRemote ( 6456): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6456): [RemoteAppWidgetManager.java:36:startLoading()] oooooo 140518:startLoading:sWidgetHandler has [3] at [1456842811592]. skip
V/QRemote ( 6456): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6456): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/DockEventReceiver( 6597): finishStartingService: stopping service
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/BluetoothInputDevice( 6597): Proxy object connected
D/HidProfile( 6597): Bluetooth service connected
D/BluetoothPan( 6597): BluetoothPAN Proxy object connected
D/PanProfile( 6597): Bluetooth service connected
D/BluetoothMap( 6597): Proxy object connected
D/MapProfile( 6597): Bluetooth service connected
D/BluetoothMap( 6597): getConnectedDevices()
D/BluetoothMap( 6597): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 6597): [BTUI] onServiceConnected
D/QRemote ( 6456): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,D/QRemote ( 6456): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
I/ActivityManager( 1033): Killing 3738:com.wsandroid.suite.lge/1000 (adj 15): empty #17
D/AndroidRuntime( 6615): Calling main entry com.android.commands.pm.Pm
I/wpa_supplicant( 2682): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1033): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1033):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 16 0
W/PackageSettings( 1033): Skipping PackageSetting{2611aad4 com.test.thalitest/10311} due to missing metadata
,E/ActivityThread( 6630): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6630): No ProfileInfo entries
I/LG Account v2.2( 6630): isEnabled: false
I/Feature ( 6630): [Lifetracker]ver: 4.21.112(40211120)
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_3738/cgroup.procs: No such file or directory
I/Feature ( 6630): [Lifetracker]Country: EU
I/Feature ( 6630): [Lifetracker]Operator: OPEN
I/Feature ( 6630): [Lifetracker]Ranking support: false
I/Feature ( 6630): [Lifetracker]Comfort support: false
I/Feature ( 6630): [Lifetracker]Accessory: true
I/Feature ( 6630): [Lifetracker]Health device: true
I/Feature ( 6630): [Lifetracker]Extra Pedometer: false
I/Feature ( 6630): [Lifetracker]Blood glucose device: false
I/Feature ( 6630): [Lifetracker]Device Number: 3
,I/ActivityManager( 1033): Force stopping com.example.hello appid=10319 user=-1: uninstall pkg
I/ActivityManager( 1033): Killing 6119:com.example.hello/u0a319 (adj 0): stop com.example.hello
I/WindowState( 1033): WIN DEATH: Window{cdeb531 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1033): Client connection lost with reason: 4
D/InputDispatcher( 1033): Focus left window: Window{cdeb531 u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher( 1033): Window went away: Window{cdeb531 u0 com.example.hello/com.example.hello.MainActivity}
I/ActivityManager( 1033):   Force finishing activity ActivityRecord{22c3d458 u0 com.example.hello/.MainActivity t4}
,E/GBMv2   (  343): DFP En is all cleared set to be enabled
I/ActivityManager( 1033): Force stopping com.example.hello appid=10319 user=0: pkg removed
,I/ActivityManager( 1033):   Force finishing activity ActivityRecord{22c3d458 u0 com.example.hello/.MainActivity t4 f}
W/ActivityManager( 1033): Duplicate finish request for ActivityRecord{22c3d458 u0 com.example.hello/.MainActivity t4 f}
D/KeyguardModel( 1452): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,E/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2036): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
W/GeofencerStateMachine( 1822): Ignoring removeGeofence because network location is disabled.
D/LIA_MrGDBLogger_PackageInfoDetector( 3697): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
I/InputReader( 1033): Reconfiguring input devices.  changes=0x00000010
,V/SIM_STK ( 1033): Menu title from STK is T-Mobile
W/ActivityManager( 1033): Spurious death for ProcessRecord{28678a25 6119:com.example.hello/u0a319}, curProc for 6119: null
,W/System.err( 4552): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 4552): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4552): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4552): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4552): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4552): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4552): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4552): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4552): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4552): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4552): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4552): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/[LGHome]EVENT( 2086): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2086): [Launcher.java:903:onResume()]onResume
D/administrator( 1033): Handling package changes for user 0
,D/WifiOffDelayIfNotUsed( 1033): stopMonitoring
E/WifiStateMachine( 1033): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1033): useWiFiOffloading() : false
E/WifiStateMachine( 1033): CONFIG_LGE_WLAN_PATH : true
I/[LGHome]EVENT( 2086): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[SystemUI]QSlideListController( 1452): onReceive = android.intent.action.PACKAGE_REMOVED
D/ActionManagerService( 1917): notifyUserLog: 1000003
D/SplitWindowPolicy( 1975): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1975): topRunningActivity=ActivityInfo{283a0d7e co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,W/Settings( 6389): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WfdsService( 1975): Supplicant Connection state is changed : false
D/WfdsService( 1975): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1975): Set the WFDS Monitor: false
D/WfdsMonitor( 1975): WFDS Monitor is stopped
D/LIA_Informant_ActionManagerMessageHandler( 3697): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2086): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/SplitWindowPolicy( 1975): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1975): topRunningActivity=ActivityInfo{3e4852df co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
V/WfdStateTracker( 1975): WfdStateTracker handleDirectStateChangedEvent: 0
,W/Settings( 1822): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[LGHome]LGActivityUtil( 2086): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2086): [Launcher.java:1056:onResume()]onResume end
D/LGBluetoothAuthorization( 6597): [BTUI] cancel All Notification
I/[LGHome]EVENT( 2086): [Launcher.java:1114:onPause()]onPause
,W/bt-btif ( 3839): ag scb idx 1 not allocated
D/bt_hci_bdroid( 3839): cleanup
E/bt-btif ( 3839): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3839): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3839): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3839): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3839): L2CAP - PSM: 0x0019 not found for deregistration
I/bt_userial_mct( 3839): exiting userial_read_thread
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x0017
D/bt_userial_mct( 3839): Leaving userial_evt_read_thread()
W/bt-l2cap( 3839): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3839): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3839): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3839): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3839): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3839): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3839): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_userial_mct( 3839): userial_close_reader Joined userial reader thread: 0
,I/bt_lpm  ( 3839): LPM is already off!!!
I/bt_vendor( 3839): hw_epilog_process
D/bt_hci_bdroid( 3839): cleanup Finalizing cleanup
D/bt_userial_mct( 3839): userial_close
E/bt_userial_mct( 3839): pthread_join() FAILED result:3
I/bt_vendor( 3839): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
I/ActivityManager( 1033): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6669 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/[LGHome]GBoardWebView( 2086): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,D/ActionManagerService( 1917): notifyUserLog: 1000004
D/KeyguardModel( 1452): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1452): createShortcutInfo...
D/LIA_Informant_ActionManagerMessageHandler( 3697): handleMessage: what(1000) actionID(0x1000004)
D/KeyguardModel( 1452): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1452): createShortcutInfo...
,W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.android.mms: Resource ID #0x0
V/BoardContentProvider( 3697): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/BluetoothPermissionRequest( 6597): onReceive
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
I/GBoardWebViewUtils( 2086): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2086): , create_time: 1430558575574
I/GBoardWebViewUtils( 2086): , expire_time: 0
I/GBoardWebViewUtils( 2086): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2086): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2086): , display: false
I/GBoardWebViewUtils( 2086): , animation: false }
I/GBoardWebViewUtils( 2086): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2086): , create_time: 1430558575600
I/GBoardWebViewUtils( 2086): , expire_time: 0
I/GBoardWebViewUtils( 2086): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2086): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2086): , display: false
I/GBoardWebViewUtils( 2086): , animation: false }
I/GBoardWebViewUtils( 2086): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1455195784986
I/GBoardWebViewUtils( 2086): , create_time: 1455195785688
I/GBoardWebViewUtils( 2086): , expire_time: 0
I/GBoardWebViewUtils( 2086): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2086): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2086): , display: false
I/GBoardWebViewUtils( 2086): , animation: false }
,V/SIM_STK ( 1033): Menu title from STK is T-Mobile
I/SystemUI[Framework]( 1033): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx( 1033): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1033): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1033): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@55e7ac9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,D/KeyguardModel( 1452): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1452): createShortcutInfo...
D/WallpaperManager( 2086): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1452): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
I/SystemUI[Framework]( 1033): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
D/KeyguardModel( 1452): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/InputDispatcher( 1033): Focus entered window: Window{ecb37a7 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,D/LGBluetoothAuthorization( 6597): [BTUI] cancel All Notification
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/PhoneWindowManagerEx( 1033): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1033): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1033): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@55e7ac9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2086): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/NotificationService( 1033): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1033): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/KeyguardModel( 1452): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1452): createShortcutInfo...
,D/JobSchedulerService( 1033): Receieved: android.intent.action.PACKAGE_REMOVED
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1452): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1452): createShortcutInfo...
,I/WifiServerServiceExt( 1033): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1033): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1033): batteryPsActivateMsgHandler : this is not treated
D/PhoneStatusBar( 1452): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/TaskPersister( 1033): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1452): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1452): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1452):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1452): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LGBluetoothResetSettingReceiver( 6597): return without doing reset settings.
W/ActivityManager( 1033): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI] [-] updateMediaPlayerInfo
,I/ActivityManager( 1033): Killing 6067:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/SplitUIManager( 1874): split_name #11 / not available #0
D/SplitUIService( 1874): removed split : 
E/WifiStateMachine( 1033):  InitialState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1033):  DefaultState CMD_SET_COUNTRY_CODE 1 0 cz
W/ResourcesManager( 6669): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/bt_hci_bdroid( 3839): set_power 0
I/bt_vendor( 3839): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3839): bluetooth satus is on
I/bt_vendor( 3839): bt-vendor : resetting BT status
I/bt_vendor( 3839): Starting hciattach daemon
I/bt_vendor( 3839): try to set false
I/bt_vendor( 3839): Starting hciattach daemon
I/bt_vendor( 3839): try to set false
I/bt_vendor( 3839): cleanup
I/GKI_LINUX( 3839): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 3839): GKI_exit_task 0 done
I/GKI_LINUX( 3839): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3839): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
D/SplitUIManager( 1874): split_name #11 / not available #0
I/SplitUIService( 1874): split app #11
D/PluginManager( 6669): init()
,I/UpdateIcingCorporaServi( 4606): UpdateCorporaTask done [took 1251 ms] updated apps [took 1251 ms] 
,D/DSQN    ( 1033): EVENT_INTERNET_CHECK_ENABLE received
W/ResourcesManager( 1033): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1033): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
V/BluetoothOppReceiver( 3839): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 3839): [BTUI] cancel opp incoming file confirm notification
,W/libprocessgroup( 1033): failed to open /acct/uid_10061/pid_6067/cgroup.procs: No such file or directory
D/BluetoothOppNotification( 3839): [BTUI] cancel opp active transfer file notification
D/KeyguardModel( 1452): handleShortcutListChanged...
I/[LGHome]EVENT( 2086): [Launcher.java:5349:onStop()]onStop
D/KeyguardModel( 1452): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1452): createShortcutInfo...
D/HeadsetService( 3839): Received stop request...Stopping profile...
D/KeyguardModel( 1452): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1452): createShortcutInfo...
I/LGBluetoothHfpAdapter( 3839): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3839): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3839): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b17ca4f
D/HeadsetStateMachine( 3839): Exit Disconnected: -1
D/BluetoothHeadset( 1033): Proxy object disconnected
D/BluetoothAdapterState( 3839): Stopping profile services that were post enabled
D/AudioService( 1033): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1857): Proxy object disconnected
D/BluetoothHeadset( 1857): Proxy object disconnected
D/BluetoothHeadset( 1857): Proxy object disconnected
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/A2dpService( 3839): Received stop request...Stopping profile...
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI] cleanup
D/A2dpStateMachine( 3839): Exit Disconnected: -1
D/KeyguardModel( 1452): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1452): createShortcutInfo...
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1452): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1452): createShortcutInfo...
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
D/LGBluetoothA2dpAdapter( 3839): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3839): Cleaning up Bluetooth Handsfree callback object
W/PackageManager( 1452): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/BluetoothAdapterService( 3839): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b17ca4f
D/BluetoothA2dp( 1033): Proxy object disconnected
D/AudioService( 1033): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 3839): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3839): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b17ca4f
D/KeyguardModel( 1452): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1452): createShortcutInfo...
D/HealthService( 3839): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3839): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b17ca4f
D/BluetoothInputDevice( 6597): Proxy object disconnected
D/HidProfile( 6597): Bluetooth service disconnected
D/PanService( 3839): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3839): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b17ca4f
D/BtGatt.DebugUtils( 3839): handleDebugAction() action=null
D/BtGatt.GattService( 3839): Received stop request...Stopping profile...
D/BtGatt.GattService( 3839): stop()
D/BtGatt.AdvertiseManager( 3839): advertise clients cleared
D/BluetoothAdapterService( 3839): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b17ca4f
D/BluetoothMapService( 3839): Received stop request...Stopping profile...
D/BluetoothMapService( 3839),: stop()
D/BluetoothPan( 6597): BluetoothPAN Proxy object disconnected
D/PanProfile( 6597): Bluetooth service disconnected
D/BluetoothMapEmailAppObserver( 3839): deinitObservers()
D/BluetoothMapEmailAppObserver( 3839): removeReceiver()
I/ActivityManager( 1033): Killing 6237:com.lge.eula/1000 (adj 15): empty #17
,I/art     ( 1033): Explicit concurrent mark sweep GC freed 53339(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 4.204ms total 244.718ms
,I/[LGHome]EVENT( 2086): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 2086): [setNavigationBarColor] color=0x 0
D/[Concierge]WidgetView( 2086): notifyExtViewAvailable
D/InputMethodManagerService( 1033): setImestate : 0
W/InputMethodManagerService( 1033): Got RemoteException sending setActive(false) notification to pid 6119 uid 10319
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/AndroidRuntime( 6615): Shutting down VM
,I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_6237/cgroup.procs: No such file or directory
D/KeyguardModel( 1452): handleShortcutListChanged...
W/IInputConnectionWrapper( 2086): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,E/b       ( 1686): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2086): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2086): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/Timeline( 1033): Timeline: Activity_windows_visible id: ActivityRecord{5f5827e u0 com.lge.launcher2/.Launcher t3} time:73737
D/BluetoothAdapterService( 3839): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b17ca4f
D/HeadsetStateMachine( 3839): Unbinding service...
D/HeadsetPhoneState( 3839): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3839): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3839): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3839): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3839): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3839): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3839): [BTUI] LGBluetoothHfpAdapter cleanup
V/BluetoothFtpReceiver( 3839): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3839): BluetoothFtpReceiver Start Service
I/BluetoothA2dpServiceJni( 3839): cleanupNative
I/GKI_LINUX( 3839): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3839): GKI_exit_task 2 done
I/GKI_LINUX( 3839): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3839): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3839): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3839): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3839): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3839): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3839): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3839): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 3839): Handler(): got msg=4
D/BluetoothMapService( 3839): MAP Service closeService in
D/LGBluetoothMapAdapter( 3839): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3839): MAP Service closeService out
D/BluetoothMapService( 3839): cleanup()
D/BluetoothMapService( 3839): MAP Service closeService in
D/LGBluetoothMapAdapter( 3839): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3839): MAP Service closeService out
D/BluetoothAdapterState( 3839): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
V/BluetoothFtpService( 3839): Ftp Service onStartCommand
V/BluetoothFtpService( 3839): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterProperties( 3839): Setting state to 10
I/BluetoothAdapterState( 3839): Bluetooth adapter state changed: 13-> 10
V/BluetoothFtpService( 3839): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3839): Shutdown
D/BluetoothManagerService( 1033): Message: 60
D/BluetoothManagerService( 1033): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1033): Broadcasting onBluetoothStateChange(false) to 9 receivers.
V/BluetoothFtpService( 3839): successfully stopped ftp service
V/BluetoothSapReceiver( 3839): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3839): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3839): SapReceiver onReceive 
V/BluetoothSapReceiver( 3839): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3839):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3839): Calling SAP service start service with action = null
D/BluetoothPan( 6597): onBluetoothStateChange on: false
I/BluetoothAdapterState( 3839): Entering OffState
D/BluetoothMap( 6597): Proxy object disconnected
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
V/BluetoothFtpService( 3839): Ftp Service onDestroy
V/BluetoothFtpService( 3839): Ftp Service closeService
D/BluetoothMap( 6597): onBluetoothStateChange: up=false
D/MapProfile( 6597): Bluetooth service disconnected
W/IInputConnectionWrapper( 2086): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2086): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,I/ActivityManager( 1033): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6693 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/BluetoothInputDevice( 6597): onBluetoothStateChange: up=false
D/[Concierge]Service( 2629): onStartCommand(). Type : 8
D/[Concierge]Service( 2629): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
V/BluetoothSapService( 3839): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3839): state: 13
V/BluetoothSapService( 3839): Stopping SAP server process
D/BluetoothHeadset( 1857): onBluetoothStateChange: up=false
D/[Concierge]Service( 2629): Update widget ID : 11
V/BluetoothSapService( 3839): Sap Service closeSapService in
V/BluetoothSapService( 3839): Close listen Socket : 
V/BluetoothSapService( 3839): Close rfcomm Socket : 
D/BluetoothHeadset( 1857): onBluetoothStateChange: up=false
V/BluetoothSapService( 3839): Close sapd  Socket : 
D/BluetoothPbap( 6597): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1857): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1033): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1033): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1033): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1033): Broadcasting onBluetoothServiceDown() to 7 receivers.
V/BluetoothSapService( 3839): Sap Service closeSapService out
V/BluetoothSapService( 3839): Sap Service onDestroy
V/BluetoothSapService( 3839): Sap Service closeSapService in
V/BluetoothSapService( 3839): Close listen Socket : 
V/BluetoothSapService( 3839): Close rfcomm Socket : 
V/BluetoothSapService( 3839): Close sapd  Socket : 
V/BluetoothSapService( 3839): Sap Service closeSapService out
D/BluetoothManagerService( 1033): Calling onQBluetoothServiceDown callbacks
,D/BluetoothManagerService( 1033): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1033): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3e8153f4 mBinding = false
D/BluetoothManagerService( 1033): Sending unbind request.
D/[Concierge]WidgetView( 2086): change position of spinner
I/GKI_LINUX( 3839): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3839): GKI_exit_task 1 done
I/GKI_LINUX( 3839): GKI_shutdown(): task [BTIF] terminated
D/BluetoothManagerService( 1033): Bluetooth State Change Intent: 13 -> 10
,I/BluetoothServiceJni( 3839): cleanupNative: return from cleanup
I/art     ( 3839): --- WEIRD: removing null entry 246
,W/art     ( 3839): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3839): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 3839): [BTUI] unregister observer for LG device name DB
D/LGBluetoothAPIService( 1975): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1975): Message: 2
D/LGBluetoothAPIService( 1975): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@5856b2c mBinding = false
D/LGBluetoothAPIService( 1975): Sending unbind request.
I/[SystemUI]BluetoothHandler( 1452): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothAdapter( 1452): 372293345: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1452): 372293345: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothFeatureConfig( 6597): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 6597): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 6597): [BTUI] clear device connection state
I/art     ( 3839): System.exit called, status: 0
I/AndroidRuntime( 3839): VM exiting with result code 0, cleanup skipped.
I/[Concierge]WidgetView( 2086): initWebView(). Time : 1456842812576
D/[Concierge]Service( 2629): onStartCommand(). Type : 0
,W/ResourcesManager( 6693): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[Concierge]WebView( 2086): Return exist ConciergeWebView. Reuse : 485020996
D/[Concierge]WidgetView( 2086): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2086): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/ActivityManager( 1033): Killing 5903:com.lge.bnr/1000 (adj 15): empty #17
,I/[LgeWidgetLib]ExtViewHost( 2086): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@10b5f7ff
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
V/AudioFlinger(  315): 3839 died, releasing its sessions
V/AudioFlinger(  315):  pid 1857 @ 0
V/AudioFlinger(  315):  pid 2202 @ 1
V/AudioFlinger(  315):  pid 3386 @ 2
V/AudioFlinger(  315):  pid 3386 @ 3
D/LGBluetoothUserBindClient( 6597): [BTUI] onServiceDisconnected
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2086): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2086): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,D/AuthorizationBluetoothService( 2129): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager( 1033): Process com.android.bluetooth (pid 3839) has died
W/ActivityManager( 1033): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_5903/cgroup.procs: No such file or directory
,W/[Concierge]WidgetView( 2086): Widget kill message received. Destory myself. My : 1456842766686, New one : 1456842812576
D/[Concierge]WidgetView( 2086): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2086): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/ContextImpl( 6597): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ExternalStrings( 6669): load override strings
W/ExternalStrings( 6669): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6669): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6669): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6669): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6669): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6669): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6669): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6669): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6669): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6669): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6669): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6669): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6669): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6669): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6669): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6669): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6669): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6669): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 6669): onCreate
I/ActivityManager( 1033): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6715 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/DockEventReceiver( 6597): finishStartingService: stopping service
I/[LgeWidgetLib]LgeAppWidgetHostView( 2086): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2086): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume

```
