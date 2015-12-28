#### Test 503880191ec81a5_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/QRemote ( 6540): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
--------- beginning of system
I/ActivityManager( 1036): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=6619 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 21762(1037KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 3.373ms total 158.397ms
I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6462): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/MusicStore( 6619): Database version: 100
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
D/LgDataFeature( 6619): LgDataFeature() Constructor: none
D/LgDataFeature( 6619): LgDataFeature() Constructor Done, null
I/ConfigStore( 6619): Config Database version: 1
D/AndroidRuntime( 6645): 
D/AndroidRuntime( 6645): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6645): CheckJNI is OFF
E/PlayEventLogger( 6619): Invalid device id bea67b7c50ddc6a9
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6619): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6462): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 6462): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 6462): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6619): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/Finsky  ( 6462): [1] DailyHygiene.reschedule: Giving up. (failures=6)
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6619): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/DeviceConnectionService( 1835): client connected with version: 7571000
I/ActivityManager( 1036): Killing 6229:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/AndroidRuntime( 6645): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1036): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1968): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1036): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{3ee73c78 #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{3ee73c78 #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1036): AppWindowTokenEx init.. 
E/GBMv2   (  337): DFP En is all cleared set to be enabled
I/ActivityManager( 1036): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6671 uid=10319 gids={50319, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 6645): Shutting down VM
W/libprocessgroup( 1036): failed to open /acct/uid_10011/pid_6229/cgroup.procs: No such file or directory
I/MediaRouter( 6619): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/DSDPConnection( 1870): Display #0 changed.
V/ActivityManager( 1036): Display changed displayId=0
I/NetworkMonitor( 6619): type=WIFI subType= reason=null isConnected=true
D/SplitWindowPolicy( 1968): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1968): topRunningActivity=ActivityInfo{3370d6f7 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1968): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1968): topRunningActivity=ActivityInfo{294f964 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6671): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/WebViewFactory( 6671): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/WearableService( 6153): callingUid 10005, callindPid: 6153
I/LibraryLoader( 6671): Loading: webviewchromium
I/NetworkMonitor( 6619): type=WIFI subType= reason=null isConnected=true
I/LibraryLoader( 6671): Time to load native libraries: 3 ms (timestamps 5754-5757)
I/LibraryLoader( 6671): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6671): Binding Chromium to main looper Looper (main, tid 1) {1875d467}
I/LibraryLoader( 6671): Expected native library version number "",actual native library version number ""
I/chromium( 6671): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager( 1036): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6695 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/BrowserStartupController( 6671): Initializing chromium process, renderers=0
W/art     ( 6671): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  311): registerClient() client 0xb101df20, uid 10319
I/MusicLeanback( 6619): Stop autocaching.
I/MusicLeanback( 6619): Stop autocaching.
W/chromium( 6671): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6671): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6671): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/MusicLeanback( 6619): Conditions not met for autocaching.
I/MusicLeanback( 6619): Stop autocaching.
D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@377a516:true
I/GoogleHttpClient( 6619): Falling back to old http client 0 java.lang.NoSuchMethodException: <init> [class android.content.Context, class java.lang.String, boolean, boolean]
I/Adreno-EGL( 6671): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6671): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6671): Build Date: 12/12/14 금
I/Adreno-EGL( 6671): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6671): Remote Branch: 
I/Adreno-EGL( 6671): Local Patches: 
I/Adreno-EGL( 6671): Reconstruct Branch: 
I/MusicLeanback( 6619): Stop autocaching.
I/MusicLeanback( 6619): Stop autocaching.
D/WearableClient( 6619): WearableClientImpl.onPostInitHandler: done
D/WearableClient( 6619): WearableClientImpl.onPostInitHandler: done
D/WearableClient( 6619): WearableClientImpl.onPostInitHandler: done
E/GmsUtils( 6619): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
E/GmsUtils( 6619): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
W/chromium( 6671): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6671): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6671): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6671): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6671): CordovaWebView is running on device made by: LGE
W/art     ( 6671): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6671): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1036): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/OpenGLRenderer( 6671): Render dirty regions requested: true
I/OpenGLRenderer( 6671): Initialized EGL, version 1.4
D/OpenGLRenderer( 6671): Enabling debug mode 0
D/Atlas   ( 6671): Validating map...
D/SplitWindow( 1036): check instance of lgWin Window{bcac19e u0 com.example.hello/com.example.hello.MainActivity}
W/ActivityManager( 1036): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/LgDataFeature( 6671): LgDataFeature() Constructor: none
D/LgDataFeature( 6671): LgDataFeature() Constructor Done, null
W/ActivityManager( 1036): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1469): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@34638d03,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1469): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1469):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1469): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Gmail   ( 6695): Observing account changes for notifications
I/Gmail   ( 6695): getAccountsCursor
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6695): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager( 1036): Displayed com.example.hello/.MainActivity: +511ms (total +643ms)
I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{39b17f51 u0 com.example.hello/.MainActivity t4} time:76163
I/Timeline( 6671): Timeline: Activity_idle id: android.os.BinderProxy@2886a557 time:76163
W/ActivityManager( 1036): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 6695): Error finding the version of the Email provider.....
E/Gmail   ( 6695): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6695): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6695): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
E/Gmail   ( 6695): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
E/Gmail   ( 6695): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6695): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6695): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6695): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6695): We do not support migrating this version of the Email provider.
I/Gmail   ( 6695): getAccountsCursor
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/chromium( 6671): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 6671): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/KeyguardViewMediator( 1469): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/KeyguardUpdateMonitor( 1469): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1469): doKeyguard: not showing because lockscreen is off
D/GCM     ( 2144): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2144): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2362): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/MDM     ( 1835): [82] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/chromium( 6671): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6671): 
E/SQLiteLog( 6695): (283) recovered 967 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
D/JsMessageQueue( 6671): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager( 1036): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6772 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/LocationInitializer( 2362): Restart initialization of location
I/chromium( 6671): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6671): 
D/jxcore_app_log( 6671): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435277568
D/JX-Cordova( 6671): jxcore cordova android initializing
I/Gmail   ( 6695): notifyAccountChanged
I/Gmail   ( 6695): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6695): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6695): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6695): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/art     ( 1036): Explicit concurrent mark sweep GC freed 13019(573KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.892ms total 126.866ms
I/Gmail   ( 6695): getAccountsCursor
W/jxcore-log( 6671): Initializing JXcore engine
W/jxcore-log( 6671): JXcore engine is ready
W/jxcore-log( 6671): Starting JXcore engine
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6772): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/m.example.hello( 6671): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9855]" dev="sockfs" ino=9855 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 6671): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 6671): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[7569]" dev="sockfs" ino=7569 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 6671): type=1400 audit(0.0:169): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/m.example.hello( 6671): type=1400 audit(0.0:170): avc: denied { ioctl } for path="socket:[32998]" dev="sockfs" ino=32998 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/Gmail   ( 6695): getAccountsCursor
D/LgDataFeature( 6772): LgDataFeature() Constructor: none
D/LgDataFeature( 6772): LgDataFeature() Constructor Done, null
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GAV2    ( 6314): Thread[GAThread,5,main]: No campaign data found.
W/jxcore-log( 6671): Platform android
W/jxcore-log( 6671): 
W/jxcore-log( 6671): Process ARCH arm
W/jxcore-log( 6671): 
I/jxcore-log( 6671): JXcore Cordova bridge is ready!
I/jxcore-log( 6671): 
W/jxcore-log( 6671): JXcore engine is started
I/Babel   ( 6772): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6772): MmsConfig.loadMmsSettings
I/Babel   ( 6772): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6772): MmsConfig.loadFromDatabase
E/jxcore-log( 6671): >> LGE-LG-D855
E/jxcore-log( 6671): 
I/jxcore-log( 6671): Total memory 2995761152
I/jxcore-log( 6671): 
I/jxcore-log( 6671): Free memory 551505920
I/jxcore-log( 6671): 
I/jxcore-log( 6671): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6671): 
I/jxcore-log( 6671): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6671): 
E/Babel   ( 6772): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6772): MmsConfig.loadFromResources
I/jxcore-log( 6671): userPath [ 'www' ]
I/jxcore-log( 6671): 
E/Babel   ( 6772): canonicalizeMccMnc: invalid mccmnc nullnull
I/jxcore-log( 6671): Size 1440 2392
I/jxcore-log( 6671): 
I/jxcore-log( 6671): Screen Brightness 50
I/jxcore-log( 6671): 
W/AudioCapabilities( 6772): Unsupported mime audio/evrc
E/jxcore-log( 6671): Dummy Error Log.
E/jxcore-log( 6671): 
I/Babel   ( 6772): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/AudioCapabilities( 6772): Unsupported mime audio/qcelp
W/VideoCapabilities( 6772): Unrecognized profile 2130706433 for video/avc
W/Settings( 6772): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 6772): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6772): Unsupported mime audio/qcelp
W/AudioCapabilities( 6772): Unsupported mime audio/evrc
W/VideoCapabilities( 6772): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6772): Unsupported mime video/divx
W/VideoCapabilities( 6772): Unsupported mime video/divx311
W/VideoCapabilities( 6772): Unsupported mime video/divx4
W/VideoCapabilities( 6772): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6772): Unsupported profile 4 for video/mp4v-es
W/AudioCapabilities( 6772): Unsupported mime audio/eac3
W/AudioCapabilities( 6772): Unsupported mime audio/ac3
W/AudioCapabilities( 6772): Unsupported mime audio/g726
W/AudioCapabilities( 6772): Unsupported mime audio/wma-voice
E/GBMv2   (  337): DFP En is all cleared set to be enabled
E/GBMv2   (  337): Set value is all cleared set the max
I/GBMv2   (  337): DFP Enabled. Ignore VFP set
W/AudioCapabilities( 6772): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6772): Unsupported mime audio/adpcm
W/VideoCapabilities( 6772): Unsupported mime video/theora
,W/VideoCapabilities( 6772): Unsupported mime video/mjpg
I/ActivityManager( 1036): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6806 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 6247:com.android.contacts/u0a19 (adj 15): empty #17
,I/AppUp4:AppBoxCP( 6806): onCreate
W/AppUp4:DB( 6806):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6806):  setFingerPrint start
,I/AppUp4:DB( 6806):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6806):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6806):  SDK version = 21
I/AppUp4:DB( 6806):  beforefinger == newfinger no write in DB
W/libprocessgroup( 1036): failed to open /acct/uid_10019/pid_6247/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6806): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6806): onReceive
E/UEI.SmartControl( 6371): file observer is disposed!
,D/LgDataFeature( 6806): LgDataFeature() Constructor: none
D/LgDataFeature( 6806): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6806): Context : android.app.ReceiverRestrictedContext@d5e0026
D/AppUp4:CustFacade( 6806): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6806): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6806): begin check event
I/AppUp4:CustModeStarterReceiver( 6806): Event For Nothing, skip.
I/ActivityManager( 1036): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6829 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6272:com.lge.email/u0a23 (adj 15): empty #17
,I/jxcore-log( 6671): getBuffer is called!!!!
I/jxcore-log( 6671): 
,I/CheckinService( 2362): Done disabling old GoogleServicesFramework version
,W/libprocessgroup( 1036): failed to open /acct/uid_10023/pid_6272/cgroup.procs: No such file or directory
,W/ResourcesManager( 6829): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6829): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6829): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6829): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6829): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 6829): BUILD Country: EU
I/SystemConfig( 6829): BUILD Operator: OPEN
,I/ActivityManager( 1036): Killing 5564:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10004/pid_5564/cgroup.procs: No such file or directory
,I/SystemConfig( 6829): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6829): existFile = false
I/SystemConfig( 6829): canReadFile = false
I/SystemConfig( 6829): systemFeature RCS result false
,D/SystemConfig( 6829): refreshRcsSupport() :false
I/ActivityManager( 1036): Killing 4982:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_4982/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4692): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/LockScreenSettings( 6349): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6349): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6349): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6349): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,D/LockScreenSettings( 6349): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 6349): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
D/PackageBroadcastService( 2362): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2362): Null package name or gms related package.  Ignoreing.
I/Icing   ( 2362): updateResources: need to parse f{com.google.android.gms}
D/WearableClient( 6619): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 6619): WearableClientImpl.onPostInitHandler: done
V/QRemote ( 6540): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:796
,I/MusicLeanback( 6619): Conditions not met for autocaching.
I/MusicLeanback( 6619): Stop autocaching.
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 77917330287; DSPS: 2693935; Offset : -4307448673
D/GCM     ( 2144): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2144): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/GmsUtils( 6619): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
V/GmsCoreStatsServiceLauncher( 2362): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1835): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2362): Restart initialization of location
,V/QRemote ( 6540): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6540): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6540): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1451341480765]
V/QRemote ( 6540): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6540): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6540): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6540): [RemoteAppWidgetManager.java:36:startLoading()] oooooo 140518:startLoading:sWidgetHandler has [3] at [1451341480777]. skip
V/QRemote ( 6540): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6540): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6540): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,V/QRemote ( 6540): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6540): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
I/art     ( 2144): Explicit concurrent mark sweep GC freed 13781(767KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 1.913ms total 57.681ms
D/QRemote ( 6540): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,I/UpdateIcingCorporaServi( 4692): UpdateCorporaTask done [took 445 ms] updated apps [took 445 ms] 
,D/UEI.SmartControl( 6371): Internal timer expired: 2
,D/UEI.SmartControl( 6371): unbind internal service
,D/serial_port( 6371): close(fd = 24)
,I/UEI.SmartControl( 6371): Serial port is closed.
,I/ConfigService( 2144): onDestroy
,D/WearableClient( 6619): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 6619): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 6619): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/MusicLeanback( 6619): Conditions not met for autocaching.
I/MusicLeanback( 6619): Stop autocaching.
,I/GAV2    ( 6695): Thread[GAThread,5,main]: No campaign data found.
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1036): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1905fa22 mBinding = false
D/LocationManagerService( 1036): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1036): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,D/Ulp_jni ( 1036): JNI:system_update. Event-4
D/BluetoothManagerService( 1036): Message: 2
D/BluetoothManagerService( 1036): Sending off request.
D/LGBluetoothServiceAdapter( 3777): [BTUI] Precleanup
D/BluetoothAdapterState( 3777): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3777): Setting state to 13
I/BluetoothAdapterState( 3777): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3777): onBluetoothDisable()
I/BluetoothAdapterState( 3777): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 3777): Scan Mode:20
D/BluetoothAdapterState( 3777): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 3777): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3777): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3777): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3777): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3777): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3777): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3777): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3777): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/btif_config_util( 3777): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothPbapService( 3777): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BtOppRfcommListener( 3777): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3777): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3777): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 3777): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3777): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3777): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3777): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3777): bta_gattc_deregister Deregister Failedm unknown client cif
D/BluetoothManagerService( 1036): Message: 60
D/BluetoothManagerService( 1036): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1036): Bluetooth State Change Intent: 12 -> 13
,D/WifiService( 1036): New client listening to asynchronous messages
,I/art     (  346): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 25.969ms
,I/ActivityManager( 1036): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6890 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 407us total 33.320ms
D/WifiServiceImplEx( 1036): setWifiEnabled: false pid=6671, uid=10319, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1036): setWifiEnabled: false pid=6671, uid=10319
E/WifiService( 1036): Invoking mWifiStateMachine.setWifiEnabled
I/[SystemUI]BluetoothHandler( 1469): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/BluetoothMapService( 3777): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothMapService( 3777): STATE_TURNING_OFF
V/BtOppService( 3777): Receiver DISABLED_ACTION 
V/BluetoothMapService( 3777): Handler(): got msg=4
D/BluetoothMapService( 3777): MAP Service closeService in
D/LGBluetoothAPIService( 1968): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapMasInstance( 3777): MAP Service shutdown
D/LGBluetoothMapAdapter( 3777): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3777): MAP Service closeService out
I/BtOppRfcommListener( 3777): stopping Accept Thread
V/BtOppRfcommListener( 3777): close mBtServerSocket
V/BtOppRfcommListener( 3777): waiting for thread to terminate
I/BtOppRfcommListener( 3777): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3777): done waiting for thread to terminate
D/LocationManagerService( 1036): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1036): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,I/jxcore-log( 6671): ****TEST TOOK:  5243  ms ****
I/jxcore-log( 6671): 
I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 445us total 22.486ms
I/jxcore-log( 6671): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6671): 
D/Ulp_jni ( 1036): JNI:system_update. Event-4
E/WifiStateMachine( 1036):  ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1036): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2663): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/CommandListener(  307): Clearing all IP addresses on wlan0
D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine( 1036): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2144): Read error: ssl=0xaf4d3400: I/O error during system call, Connection timed out
V/NativeCrypto( 2144): SSL shutdown failed: ssl=0xaf4d3400: I/O error during system call, Broken pipe
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/ActivityManager( 1036): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6925 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/BtOppService( 3777): onDestroy
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1036): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@22cb795b
D/LGWifiP2pService( 1036): P2pDisablingState
D/LGBluetoothOppAdapter( 3777): [BTUI] LGBluetoothOppAdapter cleanup
D/LGWifiP2pService( 1036): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): p2p socket connection lost
D/LGWifiP2pService( 1036): P2pDisabledState
D/ConnectivityService( 1036): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiStateMachine( 1036):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
V/WfdStateTracker( 1968): handleWifiStateChangedEvent: 0
D/WifiHS20( 1036): hidePasspointNotification off =false
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1036): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1036):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiHS20( 1036): hidePasspointNotification off =false
E/WifiStateMachine( 1036):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/LGWifiP2pService( 1036): P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2663): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService( 1036): SCAN_AVAILABLE : 1
D/RttService( 1036): SCAN_AVAILABLE : 1
,D/WifiScanningService( 1036): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1036): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/CommandListener(  307): Clearing all IP addresses on wlan0
V/WfdStateTracker( 1968): WfdStateTracker handleDirectStateChangedEvent: 0
,D/WfdsService( 1968): WifiP2pState is changed : false
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1036): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1036): disableDataServiceNotify
D/DSQN    ( 1036): stop dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WfdsService( 1968): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1968): Set the WFDS Monitor: false
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WfdsMonitor( 1968): WFDS Monitor is stopped
D/CtrlSupplicant( 1968): Received on exit socket, terminate
D/WfdsService( 1968): STATE : WfdsDisabledState - enter
E/CtrlSupplicant( 1968): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1968): Event [CTRL-EVENT-TERMINATING  - connection closed]
W/WfdsSession:Controller( 1968): DefaultState - msg [9441355] is not handled
D/WfdsMonitor( 1968): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1968): DefaultState - msg [9445378] is not handled
D/WifiNative-p2p0( 1036): doBoolean: TERMINATE
D/WifiNative-p2p0( 1036): TERMINATE: returned true
E/WifiStateMachine( 1036): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1036): useWiFiOffloading() : false
E/WifiStateMachine( 1036): CONFIG_LGE_WLAN_PATH : true
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1036): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/WfdStateTracker( 1968): WfdStateTracker handleDirectStateChangedEvent: 6
D/ConnectivityService( 1036): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/Nat464Xlat( 1036): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Disconnected - quitting
D/CSLegacyTypeTracker( 1036): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1036): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/WifiServerServiceExt( 1036): WIFI_STATE_CHANGED_ACTION [0]
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateDISCONNECTED
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1036): Removing idletimer
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
,D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
W/Settings( 1036): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1036): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1036): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WIFI    ( 1036): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/TelephonyNetworkFactory-1( 1870): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/ResourcesManager( 6925): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6925): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6925): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/wpa_supplicant( 2663): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2663): monitor socket send errors count : 1
I/wpa_supplicant( 2663): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1968-2\x00 that cannot receive messages
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1036): Dropping event because (p2p0) is stopped
,E/ActivityThread( 6890): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6890): No ProfileInfo entries
I/LG Account v2.2( 6890): isEnabled: false
I/Feature ( 6890): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6890): [Lifetracker]Country: EU
I/Feature ( 6890): [Lifetracker]Operator: OPEN
I/Feature ( 6890): [Lifetracker]Ranking support: false
I/Feature ( 6890): [Lifetracker]Comfort support: false
I/Feature ( 6890): [Lifetracker]Accessory: true
I/Feature ( 6890): [Lifetracker]Health device: true
I/Feature ( 6890): [Lifetracker]Extra Pedometer: false
I/Feature ( 6890): [Lifetracker]Blood glucose device: false
I/Feature ( 6890): [Lifetracker]Device Number: 3
D/DhcpStateMachine( 1036): StoppedState
D/DhcpStateMachine( 1036): StoppedState{ when=-180ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2663): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 2663): USIM:  scard_deinit function
D/Tethering( 1036): InitialState.processMessage what=4
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,E/WifiMonitor( 1036): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1036):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=82244
E/WifiStateMachine( 1036):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=82245
E/WifiStateMachine( 1036):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=82246  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1036):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=82247  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/ActivityManager( 1036): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6952 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 6314:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/ContextImpl( 6925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,D/AndroidRuntime( 6945): 
D/AndroidRuntime( 6945): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6945): CheckJNI is OFF
,D/Tethering( 1036): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine( 1036):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1036):  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
W/libprocessgroup( 1036): failed to open /acct/uid_10061/pid_6314/cgroup.procs: No such file or directory
,D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e88f9e9:true
V/BluetoothPbapReceiver( 3777): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3777): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3777): ***********state = 13
V/BluetoothPbapReceiver( 3777): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3777): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3777): state: 13
V/BluetoothPbapService( 3777): Pbap Service closeService in
V/BluetoothPbapService( 3777): successfully stopped pbap service
,V/BluetoothPbapService( 3777): Pbap Service closeService out
,V/BluetoothPbapService( 3777): Pbap Service onDestroy
V/BluetoothPbapService( 3777): Pbap Service closeService in
V/BluetoothPbapService( 3777): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3777): [BTUI] cleanup
D/BluetoothManagerService( 1036): Message: 30
D/BluetoothManagerService( 1036): Message: 30
W/ResourcesManager( 6952): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LocalBluetoothProfileManager( 6925): Adding local MAP profile
D/BluetoothMap( 6925): Create BluetoothMap proxy object
D/BluetoothManagerService( 1036): Message: 30
D/BluetoothManagerService( 1036): Message: 30
D/LocalBluetoothProfileManager( 6925): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 6925):  get() - isFeatureLoaded : false
,I/wpa_supplicant( 2663): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1036): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1036):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
D/PluginManager( 6952): init()
D/LGBluetoothUserBindClient( 6925): [BTUI] initUserBindClient
,W/ContextImpl( 6925): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6925): finishStartingService: stopping service
,D/BluetoothInputDevice( 6925): Proxy object connected
D/HidProfile( 6925): Bluetooth service connected
D/BluetoothPan( 6925): BluetoothPAN Proxy object connected
D/PanProfile( 6925): Bluetooth service connected
D/BluetoothMap( 6925): Proxy object connected
D/MapProfile( 6925): Bluetooth service connected
D/BluetoothMap( 6925): getConnectedDevices()
,D/BluetoothMap( 6925): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 6925): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 6925): [BTUI] cancel All Notification
D/BluetoothPermissionRequest( 6925): onReceive
D/LGBluetoothAuthorization( 6925): [BTUI] cancel All Notification
,D/LGBluetoothResetSettingReceiver( 6925): return without doing reset settings.
I/ActivityManager( 1036): Killing 6433:com.lge.eula/1000 (adj 15): empty #17
D/AndroidRuntime( 6945): Calling main entry com.android.commands.pm.Pm
,W/PackageSettings( 1036): Skipping PackageSetting{1e12f56a com.test.thalitest/10311} due to missing metadata
,V/BluetoothOppReceiver( 3777): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,D/BluetoothOppNotification( 3777): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 3777): [BTUI] cancel opp active transfer file notification
I/ActivityManager( 1036): Force stopping com.example.hello appid=10319 user=-1: uninstall pkg
,I/ActivityManager( 1036): Killing 6671:com.example.hello/u0a319 (adj 0): stop com.example.hello
I/WindowState( 1036): WIN DEATH: Window{bcac19e u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1036): Client connection lost with reason: 4
D/InputDispatcher( 1036): Window went away: Window{bcac19e u0 com.example.hello/com.example.hello.MainActivity}
,D/bt_hci_bdroid( 3777): cleanup
W/bt-btif ( 3777): ag scb idx 1 not allocated
E/bt-btif ( 3777): BTA AG is already disabled, ignoring ...
I/ActivityManager( 1036):   Force finishing activity ActivityRecord{39b17f51 u0 com.example.hello/.MainActivity t4}
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x0019
,W/bt-l2cap( 3777): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3777): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3777): L2CAP - PSM: 0x001b not found for deregistration
I/bt_lpm  ( 3777): LPM is already off!!!
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3777): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x0017
I/bt_userial_mct( 3777): exiting userial_read_thread
D/bt_userial_mct( 3777): Leaving userial_evt_read_thread()
W/bt-l2cap( 3777): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3777): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3777): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3777): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial_mct( 3777): userial_close_reader Joined userial reader thread: 0
W/bt-l2cap( 3777): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3777): L2CAP - PSM: 0x001b not found for deregistration
I/bt_vendor( 3777): hw_epilog_process
E/bt-btif ( 3777): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_hci_bdroid( 3777): cleanup Finalizing cleanup
D/bt_userial_mct( 3777): userial_close
E/bt_userial_mct( 3777): pthread_join() FAILED result:3
I/bt_vendor( 3777): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,E/GBMv2   (  337): DFP En is all cleared set to be enabled
D/WifiOffDelayIfNotUsed( 1036): stopMonitoring
E/WifiStateMachine( 1036): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1036): useWiFiOffloading() : false
E/WifiStateMachine( 1036): CONFIG_LGE_WLAN_PATH : true
,W/ActivityManager( 1036): Spurious death for ProcessRecord{2282ab8 6671:com.example.hello/u0a319}, curProc for 6671: null
I/ActivityManager( 1036): Force stopping com.example.hello appid=10319 user=0: pkg removed
I/ActivityManager( 1036):   Force finishing activity ActivityRecord{39b17f51 u0 com.example.hello/.MainActivity t4 f}
W/ActivityManager( 1036): Duplicate finish request for ActivityRecord{39b17f51 u0 com.example.hello/.MainActivity t4 f}
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6433/cgroup.procs: No such file or directory
V/BluetoothFtpReceiver( 3777): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3777): BluetoothFtpReceiver Start Service
I/[LGHome]EVENT( 2088): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2088): [Launcher.java:903:onResume()]onResume
V/BluetoothFtpService( 3777): Ftp Service onStartCommand
V/BluetoothFtpService( 3777): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3777): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3777): Shutdown
D/SplitWindowPolicy( 1968): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
V/BluetoothFtpService( 3777): successfully stopped ftp service
D/SplitWindowPolicy( 1968): topRunningActivity=ActivityInfo{4c2d7cd co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,V/BluetoothFtpService( 3777): Ftp Service onDestroy
V/BluetoothFtpService( 3777): Ftp Service closeService
I/[LGHome]EVENT( 2088): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
V/BluetoothSapReceiver( 3777): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3777): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3777): SapReceiver onReceive 
V/BluetoothSapReceiver( 3777): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3777):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3777): Calling SAP service start service with action = null
D/SplitWindowPolicy( 1968): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
V/BluetoothSapService( 3777): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3777): state: 13
V/BluetoothSapService( 3777): Stopping SAP server process
V/BluetoothSapService( 3777): Sap Service closeSapService in
V/BluetoothSapService( 3777): Close listen Socket : 
V/BluetoothSapService( 3777): Close rfcomm Socket : 
V/BluetoothSapService( 3777): Close sapd  Socket : 
D/SplitWindowPolicy( 1968): topRunningActivity=ActivityInfo{1a448882 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/art     ( 4692): Explicit concurrent mark sweep GC freed 7677(452KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 735us total 77.308ms
,I/ActivityManager( 1036): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6989 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 3777): Sap Service closeSapService out
V/BluetoothSapService( 3777): Sap Service onDestroy
V/BluetoothSapService( 3777): Sap Service closeSapService in
V/BluetoothSapService( 3777): Close listen Socket : 
,V/BluetoothSapService( 3777): Close rfcomm Socket : 
V/BluetoothSapService( 3777): Close sapd  Socket : 
I/[LGHome]GBoardWebView( 2088): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1921): notifyUserLog: 1000003
D/WfdsService( 1968): Supplicant Connection state is changed : false
D/WfdsService( 1968): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1968): Set the WFDS Monitor: false
D/WfdsMonitor( 1968): WFDS Monitor is stopped
D/LIA_Informant_ActionManagerMessageHandler( 3712): handleMessage: what(1000) actionID(0x1000003)
D/bt_hci_bdroid( 3777): set_power 0
I/bt_vendor( 3777): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3777): bluetooth satus is on
I/bt_vendor( 3777): bt-vendor : resetting BT status
I/bt_vendor( 3777): Starting hciattach daemon
I/bt_vendor( 3777): try to set false
V/BluetoothSapService( 3777): Sap Service closeSapService out
W/Settings( 1835): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/bt_vendor( 3777): Starting hciattach daemon
I/bt_vendor( 3777): try to set false
I/bt_vendor( 3777): cleanup
I/[LGHome]LGActivityUtil( 2088): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/GKI_LINUX( 3777): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3777): GKI_exit_task 0 done
I/GKI_LINUX( 3777): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 3777): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1968): WfdStateTracker handleDirectStateChangedEvent: 0
D/LIA_MrGDBLogger_PackageInfoDetector( 3712): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
W/Settings( 6772): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/LGBluetoothAvrcpQcomAdapter( 3777): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3777): [BTUI] [+] updateMediaPlayerInfo
I/[LGHome]EVENT( 2088): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2088): [Launcher.java:1114:onPause()]onPause
W/GeofencerStateMachine( 1835): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 2047): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
I/InputReader( 1036): Reconfiguring input devices.  changes=0x00000010
D/KeyguardModel( 1469): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]GBoardWebView( 2088): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,D/ActionManagerService( 1921): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3712): handleMessage: what(1000) actionID(0x1000004)
W/System.err( 4647): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 4647): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4647): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4647): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4647): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 4647): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4647): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4647): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4647): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4647): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4647): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4647): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/art     ( 1036): Explicit concurrent mark sweep GC freed 42032(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 4.207ms total 202.382ms
I/art     ( 1036): WaitForGcToComplete blocked for 191.594ms for cause Explicit
V/BoardContentProvider( 3712): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/WifiServerServiceExt( 1036): WIFI_STATE_CHANGED_ACTION [1]
,I/WifiServerServiceExt( 1036): batteryPsActivateMsgHandler : state:0 event:1
I/[SystemUI]QSlideListController( 1469): onReceive = android.intent.action.PACKAGE_REMOVED
W/ExternalStrings( 6952): load override strings
W/ExternalStrings( 6952): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6952): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6952): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6952): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6952): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6952): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6952): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6952): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6952): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6952): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6952): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6952): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6952): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6952): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6952): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6952): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6952): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6952): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/WifiServerServiceExt( 1036): batteryPsActivateMsgHandler : this is not treated
D/StatusProvider( 6952): onCreate
,W/ResourcesManager( 6989): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
D/BluetoothAdapterState( 3777): Stopping profile services that were post enabled
,I/GBoardWebViewUtils( 2088): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2088): , create_time: 1430558575574
I/GBoardWebViewUtils( 2088): , expire_time: 0
I/GBoardWebViewUtils( 2088): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2088): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2088): , display: false
I/GBoardWebViewUtils( 2088): , animation: false }
I/GBoardWebViewUtils( 2088): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2088): , create_time: 1430558575600
I/GBoardWebViewUtils( 2088): , expire_time: 0
I/GBoardWebViewUtils( 2088): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2088): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2088): , display: false
I/GBoardWebViewUtils( 2088): , animation: false }
I/GBoardWebViewUtils( 2088): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1450970832066
I/GBoardWebViewUtils( 2088): , create_time: 1450970832765
I/GBoardWebViewUtils( 2088): , expire_time: 0
I/GBoardWebViewUtils( 2088): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1450970832066&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2088): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2088): , display: false
I/GBoardWebViewUtils( 2088): , animation: false }
D/SplitUIManager( 1887): split_name #11 / not available #0
D/SplitUIService( 1887): removed split : 
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1469): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1469): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/WallpaperManager( 2088): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@34638d03,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/[LGHome]GBoardWebView( 2088): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/KeyguardModel( 1469): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1469): createShortcutInfo...
D/AuthorizationBluetoothService( 2144): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/KeyguardModel( 1469): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
D/SplitUIManager( 1887): split_name #11 / not available #0
I/SplitUIService( 1887): split app #11
,W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1469): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1469): createShortcutInfo...
,W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1469): createShortcutInfo...
I/ActivityManager( 1036): Killing 6025:com.lge.bnr/1000 (adj 15): empty #17
,V/Signer  ( 6952): override build config not found
D/Signer  ( 6952): value of property debug is false
I/[LGHome]EVENT( 2088): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/administrator( 1036): Handling package changes for user 0
,D/LGMDMWrapper( 6952): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 6952): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6952): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6952): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6952): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6952): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6952): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6952): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6952): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6952): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6952): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6952): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6952): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,V/LGMDMManager( 6952): Create singleton instance
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 9165(511KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.520ms total 323.538ms
,D/KeyguardModel( 1469): handleShortcutListChanged...
W/ActivityManager( 1036): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6025/cgroup.procs: No such file or directory
D/LGBluetoothAvrcpQcomAdapter( 3777): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3777): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3777): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3777): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3777): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3777): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3777): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3777): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3777): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3777): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3777): [BTUI] [-] updateMediaPlayerInfo
D/HeadsetService( 3777): Received stop request...Stopping profile...
I/[LGHome]EVENT( 2088): [Launcher.java:5349:onStop()]onStop
I/LGBluetoothHfpAdapter( 3777): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3777): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3777): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3099f8b2
D/BluetoothHeadset( 1870): Proxy object disconnected
D/BluetoothHeadset( 1870): Proxy object disconnected
D/BluetoothHeadset( 1870): Proxy object disconnected
D/HeadsetStateMachine( 3777): Exit Disconnected: -1
D/KeyguardModel( 1469): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1469): createShortcutInfo...
D/A2dpService( 3777): Received stop request...Stopping profile...
D/A2dpStateMachine( 3777): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 3777): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 3777): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3777): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3777): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3099f8b2
D/HidService( 3777): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3777): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3099f8b2
,D/HealthService( 3777): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3777): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3099f8b2
D/BluetoothInputDevice( 6925): Proxy object disconnected
D/HidProfile( 6925): Bluetooth service disconnected
D/LGMDMWrapper( 6952): LG MDM library v4.0.0 is available on this device.
D/KeyguardModel( 1469): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1469): createShortcutInfo...
D/PanService( 3777): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3777): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3099f8b2
D/BluetoothPan( 6925): BluetoothPAN Proxy object disconnected
D/PanProfile( 6925): Bluetooth service disconnected
D/BtGatt.DebugUtils( 3777): handleDebugAction() action=null
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/BtGatt.GattService( 3777): Received stop request...Stopping profile...
D/BtGatt.GattService( 3777): stop()
D/BtGatt.AdvertiseManager( 3777): advertise clients cleared
I/NotificationService( 1036): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1036): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1036): Receieved: android.intent.action.PACKAGE_REMOVED
D/BluetoothAdapterService( 3777): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3099f8b2
D/BluetoothHeadset( 1036): Proxy object disconnected
D/AudioService( 1036): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothA2dp( 1036): Proxy object disconnected
D/AudioService( 1036): onServiceDisconnected: Bluetooth profile: 2
D/PhoneStatusBar( 1469): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1469): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1469):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1469): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1036): removeObsoleteFile: deleting file=4_task.xml
D/KeyguardModel( 1469): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1469): createShortcutInfo...
D/BluetoothMapService( 3777): Received stop request...Stopping profile...
D/BluetoothMapService( 3777): stop()
D/BluetoothMapEmailAppObserver( 3777): deinitObservers()
D/BluetoothMapEmailAppObserver( 3777): removeReceiver()
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/BluetoothAdapterService( 3777): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3099f8b2
D/HeadsetStateMachine( 3777): Unbinding service...
,D/HeadsetPhoneState( 3777): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3777): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3777): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3777): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3777): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3777): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3777): [BTUI] LGBluetoothHfpAdapter cleanup
I/BluetoothA2dpServiceJni( 3777): cleanupNative
D/KeyguardModel( 1469): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
I/GKI_LINUX( 3777): gki_task task_id=2 [A2DP-MEDIA] terminating
D/KeyguardModel( 1469): createShortcutInfo...
I/GKI_LINUX( 3777): GKI_exit_task 2 done
I/GKI_LINUX( 3777): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3777): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3777): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3777): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3777): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3777): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3777): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3777): Cleaning up Bluetooth PAN callback object
D/BluetoothMap( 6925): Proxy object disconnected
D/MapProfile( 6925): Bluetooth service disconnected
V/BluetoothMapService( 3777): Handler(): got msg=4
D/BluetoothMapService( 3777): MAP Service closeService in
D/LGBluetoothMapAdapter( 3777): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3777): MAP Service closeService out
D/BluetoothAdapterState( 3777): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3777): Setting state to 10
I/BluetoothAdapterState( 3777): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService( 1036): Message: 60
I/BluetoothAdapterState( 3777): Entering OffState
D/BluetoothManagerService( 1036): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1036): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothA2dp( 1036): onBluetoothStateChange: up=false
D/BluetoothMapService( 3777): cleanup()
D/BluetoothMapService( 3777): MAP Service closeService in
D/LGBluetoothMapAdapter( 3777): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3777): MAP Service closeService out
D/BluetoothHeadset( 1036): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1870): onBluetoothStateChange: up=false
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/BluetoothMap( 6925): onBluetoothStateChange: up=false
D/KeyguardModel( 1469): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1469): createShortcutInfo...
D/BluetoothInputDevice( 6925): onBluetoothStateChange: up=false
D/BluetoothPbap( 6925): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1870): onBluetoothStateChange: up=false
D/BluetoothPan( 6925): onBluetoothStateChange on: false
D/BluetoothHeadset( 1870): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1036): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1036): Broadcasting onBluetoothServiceDown() to 7 receivers.
D/KeyguardModel( 1469): handleShortcutListChanged...
D/BluetoothManagerService( 1036): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1036): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1036): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1905fa22 mBinding = false
D/BluetoothManagerService( 1036): Sending unbind request.
D/BluetoothManagerService( 1036): Bluetooth State Change Intent: 13 -> 10
D/LGBluetoothAPIService( 1968): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1968): Message: 2
D/LGBluetoothAPIService( 1968): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2751eb93 mBinding = false
D/LGBluetoothAPIService( 1968): Sending unbind request.
I/[SystemUI]BluetoothHandler( 1469): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,I/GKI_LINUX( 3777): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3777): GKI_exit_task 1 done
I/GKI_LINUX( 3777): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3777): cleanupNative: return from cleanup
I/art     ( 3777): --- WEIRD: removing null entry 246
W/art     ( 3777): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3777): Cleaning up Bluetooth Service callback object
D/LGBluetoothFeatureConfig( 6925): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6925): [BTUI] resetProperty - success
E/LGBluetoothEventManager( 6925): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 6925): [BTUI] clear device connection state
D/LGBluetoothSettingsDBObserver( 3777): [BTUI] unregister observer for LG device name DB
D/BluetoothAdapter( 1469): 16192556: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1469): 16192556: getState() :  mService = null. Returning STATE_OFF
I/art     ( 3777): System.exit called, status: 0
I/AndroidRuntime( 3777): VM exiting with result code 0, cleanup skipped.
W/ContextImpl( 6925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/DockEventReceiver( 6925): finishStartingService: stopping service
E/Process ( 1036): Error getting pid for '0'
V/AudioFlinger(  311): 3777 died, releasing its sessions
V/AudioFlinger(  311):  pid 1870 @ 0
V/AudioFlinger(  311):  pid 2210 @ 1
V/AudioFlinger(  311):  pid 3285 @ 2
V/AudioFlinger(  311):  pid 3285 @ 3
D/LGBluetoothUserBindClient( 6925): [BTUI] onServiceDisconnected
,D/AndroidRuntime( 6945): Shutting down VM
D/PostponalbeReceiver( 6952): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6952): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2088): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2088): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/ActivityManager( 1036): Process com.android.bluetooth (pid 3777) has died
W/ActivityManager( 1036): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
W/ResourcesManager( 1036): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourceType( 1036): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[Concierge]WidgetView( 2088): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
I/ActivityManager( 1036): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7019 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6577:com.lge.clock/u0a10 (adj 15): empty #17
,W/ActivityThread( 6952): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/[Concierge]Service( 2615): onStartCommand(). Type : 8
I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{2b321664 u0 com.lge.launcher2/.Launcher t3} time:83775
W/libprocessgroup( 1036): failed to open /acct/uid_10010/pid_6577/cgroup.procs: No such file or directory
,D/[Concierge]Service( 2615): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]WidgetView( 2088): change position of spinner
D/[Concierge]Service( 2615): Update widget ID : 11
,I/[Concierge]WidgetView( 2088): initWebView(). Time : 1451341486586
D/[Concierge]Service( 2615): onStartCommand(). Type : 0
D/BluetoothPermissionRequest( 6925): onReceive
D/LGBluetoothUtils( 6925): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 6925): cancelDiscoverableAlarm(): Enter
,D/LGBluetoothResetSettingReceiver( 6925): return without doing reset settings.
I/PCSuite ( 7019): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,I/ActivityManager( 1036): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7045 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
I/[Concierge]WebView( 2088): Return exist ConciergeWebView. Reuse : 98425668
D/[Concierge]WidgetView( 2088): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2088): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2088): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1e92cb0f
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/PCSuite ( 7019): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7019): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/FileUtils( 7019): Failed to chmod(/data/data/com.lge.sync/databases/lgds.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,D/[Concierge]WidgetView( 2088): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2088): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
V/WiFiOffLoadBroadcast( 6925): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/[Concierge]WidgetView( 2088): Widget kill message received. Destory myself. My : 1451341430532, New one : 1451341486586
D/[Concierge]WidgetView( 2088): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2088): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]EVENT( 2088): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
E/SQLiteDatabase( 6952): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6952): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6952): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6952): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6952): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.notificationtray.e.<init>(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.notificationtray.e.a(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.notificationtray.NotificationComponent.a(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6952): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6952): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6952): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6952): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6952): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6952): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6952): 	at com.mcafee.d.c.run(Unknown Source)
,W/ResourcesManager( 7045): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/LgDataFeature( 6925): LgDataFeature() Constructor: none
D/LgDataFeature( 6925): LgDataFeature() Constructor Done, null
D/BluetoothAdapterApp( 7045): Loading JNI Library
,D/WiFiOffLoadBroadcast( 6925): MCCMNC not supported: null
D/QRemote ( 6540): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/SQLiteDatabase( 6952): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6952): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6952): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6952): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6952): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6952): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6952): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6952): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6952): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6952): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6952): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6952): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6952): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6952): 	at com.mcafee.d.c.run(Unknown Source)

```
