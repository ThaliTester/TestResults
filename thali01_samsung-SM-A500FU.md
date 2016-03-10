#### Test 613623667b1a8f4_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
D/LocationProviderProxy( 1014): applying state to connected service
I/PCWCLIENTTRACE_PushUtil( 3201): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3201): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3201): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3201): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3201): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3201): ACTION_BOOTUP - Push type: [SPP, GCM]
V/GLSActivity( 1903): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
--------- beginning of system
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2861/cgroup.procs: No such file or directory
I/ActivityManager( 1014): Killing 2919:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/TimaKeyStoreProvider( 3625): TimaSignature is unavailable
D/ActivityThread( 3625): Added TimaKeyStore provider
W/PCWCLIENTTRACE_PCWHandler( 3201): [ensureRegistration] - netwrok is not available. action ignored
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/GAV2    ( 3517): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/Zygote  ( 3644): MountEmulatedStorage()
E/Zygote  ( 3644): v2
I/SELinux ( 3644): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3644): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3644): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/libpersona( 3644): KNOX_SDCARD checking this for 10031
I/libpersona( 3644): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3644 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 2911:com.sec.android.diagmonagent/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 3644): TimaSignature is unavailable
D/ActivityThread( 3644): Added TimaKeyStore provider
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ResourcesManager( 3644): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/ActivityManager( 1014): Killing 2828:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/libprocessgroup( 1014): failed to open /acct/uid_10150/pid_2919/cgroup.procs: No such file or directory
E/Gmail   ( 3517): Error finding the version of the Email provider.....
E/Gmail   ( 3517): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3517): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3517): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3517): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3517): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3517): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
W/EmailMigration( 3517): We do not support migrating this version of the Email provider.
I/Gmail   ( 3517): getAccountsCursor
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1903): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1903): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2911/cgroup.procs: No such file or directory
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
W/libprocessgroup( 1014): failed to open /acct/uid_10072/pid_2828/cgroup.procs: No such file or directory
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/GoogleHttpClient( 1660): GMS http client unavailable, use old client
I/libpersona( 3676): KNOX_SDCARD checking this for 10104
E/Zygote  ( 3676): MountEmulatedStorage()
I/libpersona( 3676): KNOX_SDCARD not a persona
E/Zygote  ( 3676): v2
I/ActivityManager( 1014): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3676 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 3676): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3676): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3676): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/art     (  303): Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 685us total 25.022ms
D/TimaKeyStoreProvider( 3676): TimaSignature is unavailable
D/ActivityThread( 3676): Added TimaKeyStore provider
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 19.408ms
W/ResourcesManager( 3676): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 607us total 17.314ms
I/DBG_DM  ( 2897): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
I/VlingoApplication( 3644): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
D/AndroidRuntime( 3668): 
D/AndroidRuntime( 3668): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3668): CheckJNI is OFF
D/AndroidRuntime( 3668): readGMSProperty: start
D/AndroidRuntime( 3668): readGMSProperty: already setted!!
D/AndroidRuntime( 3668): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3668): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3668): readGMSProperty: end
D/AndroidRuntime( 3668): addProductProperty: start
D/BluetoothAdapter( 3644): 252574700: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3644): 252574700: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3644): 252574700: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 3644): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
D/VlingoApplication( 3644): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 3644): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
D/DialogFlow( 3644): initQueue()
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3708): MountEmulatedStorage()
I/ActivityManager( 1014): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3708 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/Zygote  ( 3708): v2
I/libpersona( 3708): KNOX_SDCARD checking this for 10032
I/libpersona( 3708): KNOX_SDCARD not a persona
I/SELinux ( 3708): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3708): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3708): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/AffinityControl( 3668): AffinityControl: registerfunction enter
D/AndroidRuntime( 3668): Calling main entry com.android.commands.am.Am
D/TimaKeyStoreProvider( 3708): TimaSignature is unavailable
D/ActivityThread( 3708): Added TimaKeyStore provider
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
E/SQLiteLog( 3517): (283) recovered 155 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 1014): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  pkgName : ACTIVITY_RESUME_BOOSTER@7
I/Gmail   ( 3517): Observing account changes for notifications
W/ActivityManager( 1014): mDVFSHelper.acquire()
D/FocusedStackFrame( 1014): Set to : 0
D/Launcher.HomeView( 1492): onPause
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/PhoneWindow( 1014): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1014): *FMB* installDecor flags : -2122120936
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus left window: 1492
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled return false
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/AndroidRuntime( 3668): Shutting down VM
D/Launcher( 1492): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/SurfaceFlinger(  256): id=10 createSurf (1x1),1 flag=404, uhalitest
E/ActivityThread( 3517): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@3010c652 that was originally bound here
E/ActivityThread( 3517): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@3010c652 that was originally bound here
E/ActivityThread( 3517): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3517): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3517): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3517): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3517): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3517): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3517): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3517): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3517): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3517): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3517): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3517): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3517): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3517): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3729): MountEmulatedStorage()
I/libpersona( 3729): KNOX_SDCARD checking this for 10155
E/Zygote  ( 3729): v2
I/libpersona( 3729): KNOX_SDCARD not a persona
I/SELinux ( 3729): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3729): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3729): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3729): TimaSignature is unavailable
D/ActivityThread( 3729): Added TimaKeyStore provider
I/ActivityManager( 1014): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3729 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/WindowOrientationListener( 1014): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1014): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1014): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1014): isKioskContainerExistOnDevice
W/ActivityManager( 1014): Unbind failed: could not find connection for android.os.BinderProxy@200a1ec1
D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1014): [SO] activate (ident=0xb8fc2970, enabled=0)
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/SensorManager( 1014): unregisterListener ::   
I/Sensors ( 1014): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1014): [SO] changed settle time [1]
D/SensorService( 1014): [SO] setDelay [66000000]
D/SensorService( 1014): [SO] activate (ident=0xb8fc2970, enabled=1)
D/SensorService( 1014): [SO] AR_init
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1014): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/Finsky  ( 3625): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/art     ( 3668): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ProcessCpuTracker( 1014): Skipping unknown process pid 3668
E/Zygote  ( 3748): MountEmulatedStorage(),
I/libpersona( 3748): KNOX_SDCARD checking this for 10033
E/Zygote  ( 3748): v2
I/libpersona( 3748): KNOX_SDCARD not a persona
I/SELinux ( 3748): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3748): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3748): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/SensorService( 1014): [SO] Reset Rotation Old [100], Init [1]
,I/ActivityManager( 1014): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3748 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 2773:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,E/SMD     (  286): DCD OFF
,D/TimaKeyStoreProvider( 3748): TimaSignature is unavailable
,D/ActivityThread( 3748): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_10085/pid_2773/cgroup.procs: No such file or directory,
,E/File    ( 3517): fail readDirectory() errno=2
,D/SensorService( 1014): [SO] 0.096 0.383 10.132
,D/SensorService( 1014): [SO] [100 -> 255]
,I/WebViewFactory( 3729): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/Gmail   ( 3517): notifyAccountChanged
,I/LibraryLoader( 3729): Time to load native libraries: 2 ms (timestamps 646-648)
I/LibraryLoader( 3729): Expected native library version number "",actual native library version number ""
,I/ActivityManager( 1014): Killing 2948:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1014): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/Gmail   ( 3517): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,E/Zygote  ( 3775): MountEmulatedStorage()
I/libpersona( 3775): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3775): v2
I/libpersona( 3775): KNOX_SDCARD not a persona
I/SELinux ( 3775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3775 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3775): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1903): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1014): Killing 3005:com.policydm/1000 (adj 15): empty #31
V/GLSActivity( 1903): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 3729): Binding Chromium to main looper Looper (main, tid 1) {34f1e9a}
,I/LibraryLoader( 3729): Expected native library version number "",actual native library version number ""
I/chromium( 3729): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/TimaKeyStoreProvider( 3775): TimaSignature is unavailable
,D/ActivityThread( 3775): Added TimaKeyStore provider
,I/BrowserStartupController( 3729): Initializing chromium process, singleProcess=true
,W/art     ( 3729): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3729): ApplicationContext is null in ApplicationStatus
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2948/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3005/cgroup.procs: No such file or directory
,W/chromium( 3729): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,W/chromium( 3729): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/Babel   ( 3676): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3676): MmsConfig.loadMmsSettings
I/Babel   ( 3676): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/chromium( 3729): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/Babel   ( 3676): MmsConfig.loadFromDatabase
I/chromium( 3729): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 3729): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3729): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3729): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3729): Local Branch: 
I/Adreno-EGL( 3729): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3729): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3729):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/SurfaceFlinger(  256): id=8 Removed Mauncher (5/8)
,I/SurfaceFlinger(  256): id=8 Removed Mauncher (-2/8)
,I/Gmail   ( 3517): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 3676): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothAdapter( 3729): 888811943: getState() :  mService = null. Returning STATE_OFF
,W/ContextImpl( 3775): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Babel   ( 3676): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3676): MmsConfig.loadFromResources
,E/Babel   ( 3676): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3676): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Gmail   ( 3517): calculateUnknownSyncRationalesAndPurgeInBackground: running,
I/Gmail   ( 3517): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/Zygote  ( 3820): MountEmulatedStorage()
E/Zygote  ( 3820): v2
I/libpersona( 3820): KNOX_SDCARD checking this for 1000
,I/libpersona( 3820): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3820 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3820): TimaSignature is unavailable
,D/ActivityThread( 3820): Added TimaKeyStore provider
,D/Finsky  ( 3625): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/DBG_DM  ( 2897): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,W/ResourcesManager( 3820): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,I/Babel_StickerModule( 3676): App launched.
,I/Babel_StickerModule( 3676): Sticker update initiated. last:1456825783062 empty:false
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/chromium( 3729): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/Settings( 3625): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3625): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/art     ( 3729): Attempt to remove local handle scope entry from IRT, ignoring
,D/TimaService( 1014): TIMA: in getTimaVersion
,D/TimaService( 1014): TIMA3: KeyStore3_init
,D/TimaService( 1014): TIMA: in getTimaVersion
,E/TLC_TZ_KEYSTORE: ( 1014): Inside TZ_KEYSTORE_initialize()
,I/TLC_TZ_KEYSTORE: ( 1014): creating new keystore context...
,I/TLC_TZ_KEYSTORE: ( 1014): initializing ccm context...
,I/TLC_TZ_KEYSTORE: ( 1014): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1014): process = tima_key, process_strlen = 8
,I/TZ: qc_tlc_communication( 1014): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication( 1014): process = tima_key, process_strlen = 8
,I/TZ: qc_tlc_communication( 1014): aligned max_sendmsg_size = 1088 = 0x440
,I/TZ: qc_tlc_communication( 1014): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1014): max_message_size = 2176 = 0x880
,D/QSEECOMAPI: ( 1014): QSEECom_get_handle sb_length = 0x880
,D/QSEECOMAPI: ( 1014): App is not loaded in QSEE
,W/ResourcesManager( 3748): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3748): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3748): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/AwContents( 3729): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 3729): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3729): *FMB* installDecor flags : -2139027200
,D/QSEECOMAPI: ( 1014): Loaded image: APP id = 8
,I/TZ: qc_tlc_communication( 1014): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
,I/TLC_TZ_KEYSTORE: ( 1014): ctx = 0xb8f2d100, comm = 0xb8e37310, sendmsg = 0x9ff11000, recvmsg = 0x9ff11440
,I/TZ_init: ( 1014): TZ_init: sending initialization request...
,D/SystemWebViewEngine( 3729): CordovaWebView is running on device made by: samsung
,E/TZ_init: ( 1014): TZ_init Process: Secure memory is not initialized!
,E/TZ_init: ( 1014): trustlet initialization failed
I/TZ_init: ( 1014): TZ_init_START...
,I/TZ_init: ( 1014): TZ_init_with_data: sending initialization request...
,I/TZ_init: ( 1014): TZ_init: successful initialization
,D/QSEECOMAPI: ( 1014): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1014): QSEECom_shutdown_app, app_id = 8
,E/TLC_TZ_KEYSTORE: ( 1014): Count : 1, Ret : 0
,W/art     ( 3729): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3729): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 34630(1774KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/39MB, paused 3.672ms total 173.625ms
,V/Babel   ( 3676): babel boot account: SMS
,W/Babel   ( 3676): EsDatabaseHelper.static should not be called on main thread [called on main thread]
,W/Babel   ( 3676): java.lang.Exception
W/Babel   ( 3676): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3676): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 3676): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3676): 	at ckh.a(SourceFile:67)
W/Babel   ( 3676): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3676): 	at bhn.a(SourceFile:301)
W/Babel   ( 3676): 	at bhn.a(SourceFile:137)
W/Babel   ( 3676): 	at bhn.a(SourceFile:126)
W/Babel   ( 3676): 	at bhn.a(SourceFile:159)
W/Babel   ( 3676): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3676): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3676): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3676): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3676): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3676): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3676): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3676): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3676): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3676): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3676): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/Volley  ( 3625): [551] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3625): [558] DiskBasedCache.clear: Cache cleared.
,W/Babel   ( 3676): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3676): java.lang.Exception
W/Babel   ( 3676): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3676): 	at aes.a(SourceFile:145)
W/Babel   ( 3676): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3676): 	at ckh.a(SourceFile:67)
W/Babel   ( 3676): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3676): 	at bhn.a(SourceFile:301)
W/Babel   ( 3676): 	at bhn.a(SourceFile:137)
W/Babel   ( 3676): 	at bhn.a(SourceFile:126)
W/Babel   ( 3676): 	at bhn.a(SourceFile:159)
W/Babel   ( 3676): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3676): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3676): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3676): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3676): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3676): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3676): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3676): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3676): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3676): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3676): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ResourcesManager( 3748): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3748): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3748): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/Ads     ( 3625): Skipping gmscore version check
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/OpenGLRenderer( 3729): Render dirty regions requested: true
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,D/PhoneWindow( 3729): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3729): *FMB* isFloatingMenuEnabled return false
,W/ResourcesManager( 3748): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3748): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3748): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/SurfaceFlinger(  256): id=11 createSurf (1x1),1 flag=404, NainActivit,
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,D/InputDispatcher( 1014): Focus entered window: 3729
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3729): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 3729): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3729): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3729): Enabling debug mode 0
,W/ContextImpl( 3820): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3851): MountEmulatedStorage()
E/Zygote  ( 3851): v2
I/libpersona( 3851): KNOX_SDCARD checking this for 1000
I/libpersona( 3851): KNOX_SDCARD not a persona
,I/SELinux ( 3851): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3851 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 3851): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3851): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,D/Finsky  ( 3625): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 3625): [1] Libraries$2.run: Finished loading 1 libraries.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/TimaKeyStoreProvider( 3851): TimaSignature is unavailable
,D/ActivityThread( 3851): Added TimaKeyStore provider
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,I/ActivityManager( 1014): Displayed Component not be shown by security: +1s222ms
V/Babel   ( 3676): babel boot account: thalitester@gmail.com
,I/Timeline( 3729): Timeline: Activity_idle id: android.os.BinderProxy@3b19dc84 time:41535
,W/ResourcesManager( 3851): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/CustomFrequencyManagerService( 1014): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  tag : ACTIVITY_RESUME_BOOSTER@7
,I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{b2648b7 u0 com.test.thalitest/.MainActivity t12} time:41537
W/ActivityManager( 1014): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1014): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/Launcher.HomeView( 1492): onStop
,V/ActivityThread( 1492): updateVisibility : ActivityRecord{35812049 token=android.os.BinderProxy@13fea62c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1492): onTrimMemory. Level: 20
,I/SamsungIME( 1812): getCurrentCandidateView
,W/ContextImpl( 3851): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1014): startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,W/Babel   ( 3676): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,W/Babel   ( 3676): java.lang.Exception
W/Babel   ( 3676): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3676): 	at aes.a(SourceFile:145)
W/Babel   ( 3676): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3676): 	at ckh.a(SourceFile:67)
W/Babel   ( 3676): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3676): 	at bhn.a(SourceFile:301)
W/Babel   ( 3676): 	at bhn.a(SourceFile:137)
W/Babel   ( 3676): 	at bhn.a(SourceFile:126)
W/Babel   ( 3676): 	at bhn.a(SourceFile:159)
W/Babel   ( 3676): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3676): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3676): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3676): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3676): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3676): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3676): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3676): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3676): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3676): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3676): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3775): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3775): Resource data:2131165186
,W/ResourcesManager( 3775): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3775): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3775): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3775): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3775): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,I/AMMetaDataParserService( 3775): getResourceTypeNamexml
,I/F_PHONE ( 3851): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 3851): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,D/ActivityManager( 1014): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,I/AMMetaDataParserService( 3775): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
I/AMMetaDataParserService( 3775): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,W/SEAMService( 1014):  hashset_to_int_array returning null
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  256): id=10 Removed uhalitest (7/8)
,I/SurfaceFlinger(  256): id=10 Removed uhalitest (-2/8)
,E/Zygote  ( 3884): MountEmulatedStorage()
E/Zygote  ( 3884): v2
I/libpersona( 3884): KNOX_SDCARD checking this for 1000
I/libpersona( 3884): KNOX_SDCARD not a persona
,I/SELinux ( 3884): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3884): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3884 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3884): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3775): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,W/SEAMService( 1014):  hashset_to_int_array returning null
,W/BindingManager( 3729): Cannot call determinedVisibility() - never saw a connection for the pid: 3729
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3884): TimaSignature is unavailable
,D/ActivityThread( 3884): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
W/ContextImpl( 3775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserSer,vice( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
D/F_PHONE ( 3851): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 3851): default registerAction()
I/F_PHONE ( 3851): [[com.sec.bcservice]] sendPendingMessage()
D/SamsungIME( 1812): Dismiss ExpandCandiate
E/SQLiteLog( 3820): (284) automatic index on seams_container_info(seams_container_id)
E/SQLiteLog( 3820): (284) automatic index on seams_container_info(sp_id)
I/art     ( 3179): WaitForGcToComplete blocked for 9.083ms for cause HomogeneousSpaceCompact
W/SEAMService( 1014):  hashset_to_int_array returning null
W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  281): getCameraInfo: X
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  281): getCameraInfo: X
,D/CustomFrequencyManagerService( 1014): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  tag : ACTIVITY_RESUME_BOOSTER@11
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1903): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
I/AMMetaDataParserService( 3775): Resource data:2131034113
,I/ActivityManager( 1014): Killing 2968:com.google.android.configupdater/u0a86 (adj 15): empty #31
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3775): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3775): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3775): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3775): getResourceTypeNamexml
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/Finsky  ( 3625): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,I/GFX construct_block_size_descriptor_2d second part( 3775): took 2.286458ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3775): took 7.006979ms for 0*0 texture 0
,I/GFX raster( 3775): took 10.753177ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a77f08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a77ed0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/VideoCapabilities( 3676): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 3676): Unsupported mime audio/evrc
,W/AudioCapabilities( 3676): Unsupported mime audio/qcelp
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/AudioCapabilities( 3676): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3676): Unsupported mime audio/mpeg-L2
,W/libprocessgroup( 1014): failed to open /acct/uid_10086/pid_2968/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3775): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/Finsky  ( 3625): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/DBG_DM  ( 2897): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,W/ResourcesManager( 3708): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.980052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a77f08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a77ed0 counterpartCT=4 counterpartW=96 counterparth=96
,I/Gmail   ( 3517): getAccountsCursor
,I/AMMetaDataParserService( 3775): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/WearableService( 1903): callingUid 10012, callindPid: 1903
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX construct_block_size_descriptor_2d second part( 3775): took 3.684167ms for 0*0 texture 0
,E/Zygote  ( 3915): MountEmulatedStorage()
E/Zygote  ( 3915): v2
I/libpersona( 3915): KNOX_SDCARD checking this for 1000
I/libpersona( 3915): KNOX_SDCARD not a persona
,W/AudioCapabilities( 3676): Unsupported mime audio/x-ms-wma
I/SELinux ( 3915): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3915): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/AudioCapabilities( 3676): Unsupported mime audio/x-ima
,E/SELinux ( 3915): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/JsMessageQueue( 3729): Set native->JS mode to OnlineEventsBridgeMode
,W/AudioCapabilities( 3676): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3676): Unsupported mime audio/evrc
,I/GFX generate_partition_tables( 3775): took 8.114792ms for 0*0 texture 0
,I/GFX raster( 3775): took 13.148749ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a77ed0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7c9c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1014): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3915 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3775): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/FileApkUtils( 3393): Spent 105ms computing apk sha1.
,D/FileApkUtils( 3393): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 3393): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-ca8b2a9144773fc3650c54ed299f2d4558171b12@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3775): took 0.658490ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a81568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a816c0 counterpartCT=4 counterpartW=96 counterparth=96
,E/GmsWearableNodeHelper( 1903): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/DexOptUtils( 3393): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 3393): Lollipop platform, using <isa> directory.
,D/DexOptUtils( 3393): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 3393): Primary ABI of odexing process is armeabi-v7a
,D/TimaKeyStoreProvider( 3915): TimaSignature is unavailable
,D/ActivityThread( 3915): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3775): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/VideoCapabilities( 3676): Unsupported mime video/wvc1
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.815052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7df70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7e0c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/VideoCapabilities( 3676): Unsupported mime video/x-ms-wmv
,I/Process ( 3748): Sending signal. PID: 3748 SIG: 9
,I/Gmail   ( 3517): getAccountsCursor
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1903): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.627240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a78358 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7ca50 counterpartCT=4 counterpartW=96 counterparth=96
,I/SamsungIME( 1812): getDebugLevel  : 0x4f4c
,I/AMMetaDataParserService( 3775): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/VideoCapabilities( 3676): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3676): Unsupported mime video/wvc1
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.711042ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7ca50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7ec38 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3676): Unsupported mime video/x-ms-wmv
,I/ActivityManager( 1014): Killing 3042:com.dropbox.android/u0a92 (adj 15): empty #31
,D/jxcore_app_log( 3729): JniHelper::setJavaVM(0xb86a2450), pthread_self() = -1195645320
,W/VideoCapabilities( 3676): Unsupported mime video/x-ms-wmv7
,D/KnoxSetupWizardDbHelper( 3915): dbMigrationFlag : false
,W/VideoCapabilities( 3676): Unsupported mime video/x-ms-wmv8
,I/ActivityManager( 1014): Process com.sec.android.app.sns3 (pid 3748)(adj 0) has died(112,1121)
,I/AMMetaDataParserService( 3775): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/VideoCapabilities( 3676): Unsupported mime video/mp43
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/ShortcutReceiver( 3915):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 3676): Unsupported mime video/sorenson
,W/VideoCapabilities( 3676): Unsupported mime video/mp4v-esdp
I/libpersona( 3938): KNOX_SDCARD checking this for 10034
E/Zygote  ( 3938): MountEmulatedStorage()
,I/libpersona( 3938): KNOX_SDCARD not a persona
E/Zygote  ( 3938): v2
,I/SELinux ( 3938): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/SELinux ( 3938): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3938 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
I/GFX raster( 3775): took 0.592969ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7c620 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7cf30 counterpartCT=4 counterpartW=96 counterparth=96
E/SELinux ( 3938): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/AMMetaDataParserService( 3775): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fd9d23 added. We now have 1 listener(s)
,D/KnoxShortcutUtil( 3915): getIsShortcutMigrationFor_2_3_0_Done true
,I/dex2oat ( 3931): ----------------------------------------------------
I/dex2oat ( 3931): <SS>: S T A R T I N G . . .
I/dex2oat ( 3931): <SS>: Zip is absent. Canceled.
D/ShortcutReceiver( 3915):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 3915):  shortcut migration not required 
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3775): Resource data:2131034113
,I/dex2oat ( 3931): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk --oat-fd=35 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
W/libprocessgroup( 1014): failed to open /acct/uid_10092/pid_3042/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3775): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3775): getResourceTypeNamexml
D/TimaKeyStoreProvider( 3938): TimaSignature is unavailable
D/ActivityThread( 3938): Added TimaKeyStore provider,
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.805885ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a77f08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a7cdc0 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 3954): MountEmulatedStorage(),
E/Zygote  ( 3954): v2
I/libpersona( 3954): KNOX_SDCARD checking this for 1000
I/SELinux ( 3954): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3954): KNOX_SDCARD not a persona,
I/SELinux ( 3954): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3954 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3954): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729):     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729):     - Scan report delay in milliseconds: 500
,I/SamsungIME( 1812): getDebugLevel  : 0x4f4c
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3902e87f added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3729): addListener: New listener added - the number of listeners is now 1
,I/AMMetaDataParserService( 3775): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/TimaKeyStoreProvider( 3954): TimaSignature is unavailable
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
D/ActivityThread( 3954): Added TimaKeyStore provider
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): setDiscoveryMode: Discovery mode BLE is supported
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/SamsungIME( 1812): KeybaordView init() : load resources
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.988438ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a77f08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a7e0c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/chromium( 3729): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/KnoxSetupWizardClient( 3954): isShipMode : 1
I/KnoxSetupWizardClient( 3954): onReceive : android.intent.action.BOOT_COMPLETED
,I/VideoCapabilities( 3676): Unsupported profile 4 for video/mp4v-es
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/SamsungIME( 1812): getCurrentKeyboard
I/SamsungIME( 1812): getTextKeyboard
,I/GFX raster( 3775): took 0.746042ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a77ed0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a78550 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,D/PowerManagerService( 1014): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1180 (0x0)
,I/AMMetaDataParserService( 3775): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/InstanceID/Rpc( 3393): Found 10012
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3975): MountEmulatedStorage()
E/Zygote  ( 3975): v2
I/libpersona( 3975): KNOX_SDCARD checking this for 10107
I/libpersona( 3975): KNOX_SDCARD not a persona
,I/SELinux ( 3975): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3975): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
E/SELinux ( 3975): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/GFX raster( 3775): took 0.745885ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a81568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a729b0 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1014): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=3975 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 2984:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/art     (  303): Explicit concurrent mark sweep GC freed 8780(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 29.638ms
,D/TimaKeyStoreProvider( 3975): TimaSignature is unavailable
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 652us total 18.689ms
,D/ActivityThread( 3975): Added TimaKeyStore provider
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 18.675ms
,I/AMMetaDataParserService( 3775): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/ActivityManager( 1014): Killing 3115:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,W/System.err( 3954): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 3954): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3954): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3954): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 3954): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 3954): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3954): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/SamsungIME( 1812): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 1.043594ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7df70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7ee58 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3708): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3708): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3708): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3775): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/Zygote  ( 3996): MountEmulatedStorage()
,E/Zygote  ( 3996): v2
,I/libpersona( 3996): KNOX_SDCARD checking this for 1000
I/libpersona( 3996): KNOX_SDCARD not a persona
,I/SELinux ( 3996): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=3996 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3996): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3996): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Killing 3136:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,I/Babel   ( 3676): Creating RTCS
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.640729ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7f8c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7f888 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.671928ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7f888 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a796d8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534,
,D/TimaKeyStoreProvider( 3996): TimaSignature is unavailable
,D/ActivityThread( 3996): Added TimaKeyStore provider
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.525052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a43598 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89b8218 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3775): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3775): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3775): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
I/AMMetaDataParserService( 3775): Resource data:2131034112
,I/AMMetaDataParserService( 3775): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3775): getResourceTypeNamexml
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.596250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a5fe78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7c620 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ChimeraCfgMgr( 3393): Reading stored module config
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2897): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,D/ChimeraCfgMgr( 3393): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 3393): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 3393): Got an BootCompleted event.
,D/BootCompletedReceiver( 3393): Will NOT schedule AdAttestation signal task because it's disabled.
,I/DBG_POLICYDM( 3996): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 3996): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.605678ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a5fe78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89b8218 counterpartCT=4 counterpartW=96 counterparth=96
,D/GCM     ( 3393): COMPAT: Multi user not supported
,I/AMMetaDataParserService( 3775): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1903): COMPAT: Multi user not supported
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3996): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 3996): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CheckinService( 3393): Checkin interval check for package: unspecified last checkin: 1456600236354 min interval config: 0 actual interval: 1023140623
,I/DBG_POLICYDM( 3996): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 3996): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.636823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a78358 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a7c620 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,I/GCoreUlr( 3393): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3996): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3996): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 3996): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3996): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 3996): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 3996): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4029 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,E/Zygote  ( 4029): MountEmulatedStorage()
I/libpersona( 4029): KNOX_SDCARD checking this for 10035
E/Zygote  ( 4029): v2
I/libpersona( 4029): KNOX_SDCARD not a persona
I/SELinux ( 4029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4029): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,E/SELinux ( 4029): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.625052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7f8c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89b8218 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4029): TimaSignature is unavailable
,D/ActivityThread( 4029): Added TimaKeyStore provider
,D/SSRM:n  ( 1014): SIOP:: AP = 390
,W/ResourcesManager( 3676): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3676): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/SQLiteLog( 3676): (284) automatic index on conversation_participants_view(conversation_id)
,I/AMMetaDataParserService( 3775): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/art     ( 1660): Explicit concurrent mark sweep GC freed 3746(157KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 115.631ms total 1.173s
,I/DBG_POLICYDM( 3996): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,W/SQLiteConnectionPool( 1660): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/DBG_POLICYDM( 3996): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 3996): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/SQLiteLog( 3676): (284) automatic index on conversation_participants_view(conversation_id)
,E/DBG_POLICYDM( 3996): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,E/SQLiteLog( 3676): (284) automatic index on conversation_participants_view(conversation_id)
,V/JNIHelp ( 3676): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/SMD     (  286): DCD OFF
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
I/AMMetaDataParserService( 3775): Resource data:2131034113
I/AMMetaDataParserService( 3775): getResourceName:com.android.contacts:xml/assistant_main
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/AMMetaDataParserService( 3775): getResourceTypeNamexml
E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3775): took 0.808958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb89b8218 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a7c620 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityThread( 3676): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3676): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3df4acd0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3676): Installed default security provider GmsCore_OpenSSL
I/Babel   ( 3676): Destroying RTCS
,I/AMMetaDataParserService( 3775): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/art     ( 3393): Suspending all threads took: 213.904ms
,E/SQLiteLog( 3676): (284) automatic index on conversation_participants_view(conversation_id)
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.823281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb89b8218 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a7c620 counterpartCT=4 counterpartW=96 counterparth=96
,E/SPPClientService( 4029): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4029): [PushClientApplication] Push log off : This is Ship build version
,E/SQLiteLog( 3676): (284) automatic index on conversation_participants_view(conversation_id)
,I/CheckinService( 3393): Disabling old GoogleServicesFramework version
,E/SPPClientService( 4029): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,D/SPPClientService( 4029): PushLog.txt file is not deleted.
D/SPPClientService( 4029): PushLog.txt file is not deleted.
D/SPPClientService( 4029): ============PushLog. stop!
,I/AMMetaDataParserService( 3775): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 3393): onCreate
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.596980ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7c620 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6c3c0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SystemUpdateService( 3393): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/AMMetaDataParserService( 3775): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,V/AuthZen ( 3393): Handling intent: android.intent.action.BOOT_COMPLETED
,E/Zygote  ( 4067): MountEmulatedStorage()
E/Zygote  ( 4067): v2
I/libpersona( 4067): KNOX_SDCARD checking this for 10041
I/libpersona( 4067): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4067 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 4067): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4067): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4067): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 3153:com.fmm.dm/1000 (adj 15): empty #31
,D/AuthZenEventHandler( 3393): Handling event: android.intent.action.BOOT_COMPLETED
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.813542ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a5fe78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6c3c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/DBG_DM  ( 2897): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.910990ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7df70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6c3c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.641874ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7f8c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6c3c0 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4067): TimaSignature is unavailable
,D/ActivityThread( 4067): Added TimaKeyStore provider
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3775): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 1.003959ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7f888 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a5ef48 counterpartCT=4 counterpartW=96 counterparth=96
,D/GCM     ( 1903): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,W/BaseAppContext( 3393): Using Auth Proxy for data requests.
,I/CheckinService( 3393): Checking schedule, now: 1457623377978 next: 1457139499243
I/CheckinService( 3393): active receiver: enabled
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/EnterpriseController(  275): uids 10012
D/EnterpriseController(  275): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  275): getNetworkForDns: using netid 0 for uid 10012
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3775): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 3625): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 3625): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3625): (HTTPLog)-Static: isShipBuild true
I/System.out( 3625): (HTTPLog)-Thread-563-363295982: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3625): (HTTPLog)-Static: isSBSettingEnabled false
,I/GCoreUlr( 1903): DispatchingService.onCreate()
,D/EnterpriseController(  275): uids 10028
D/EnterpriseController(  275): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  275): getNetworkForDns: using netid 0 for uid 10028
,I/SystemUpdateService( 3393): cancelUpdate (empty URL)
I/SystemUpdateService( 3393): active receiver: disabled
,W/jxcore-log( 3729): Initializing JXcore engine
W/jxcore-log( 3729): JXcore engine is ready
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.646250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a43598 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6c3c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/BaseAppContext( 3393): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,E/audit   ( 1928): type=1400 msg=audit(1457623378.231:203): avc:  denied  { ioctl } for  pid=3971 comm="Thread-589" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1928):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1928): type=1300 msg=audit(1457623378.231:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9c2e38f8 items=0 ppid=303 ppcomm=main pid=3971 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-589" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1928): type=1320 msg=audit(1457623378.231:203): 
,I/art     ( 1903): Explicit concurrent mark sweep GC freed 19928(1398KB) AllocSpace objects, 22(352KB) LOS objects, 39% free, 11MB/19MB, paused 1.111ms total 75.100ms
,W/jxcore-log( 3729): Starting JXcore engine
,I/art     ( 3393): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3393): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/AuthZen ( 3393): Fetching signing key...
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
W/ContextImpl( 3775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,W/jxcore-log( 3729): Platform android
W/jxcore-log( 3729): 
W/jxcore-log( 3729): Process ARCH arm
W/jxcore-log( 3729): 
,D/StrictMode( 3975): StrictMode policy violation; ~duration=1602 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3975): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3975): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3975): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3975): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3975): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 3975): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 3975): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 3975): StrictMode policy violation; ~duration=1530 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3975): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3975): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3975): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3975): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3975): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 3975): StrictMode policy violation; ~duration=1240 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3975): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3975): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3975): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 3975): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 3975): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 3975): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 3975): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 3975): StrictMode policy violation; ~duration=1238 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3975): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3975): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3975): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 3975): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 3975): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 3975): StrictMode policy violation; ~duration=1237 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3975): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3975): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3975): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 3975): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 3975): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 3975): StrictMode policy violation; ~duration=1235 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3975): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3975): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3975): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3975): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3975): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 3975): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 3975): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 3975): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 3975): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 3975): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 3975): 	at com.google.r.e.b(PG:170)
D/StrictMode( 3975): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 3975): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 3975): StrictMode policy violation; ~duration=1232 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3975): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3975): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3975): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3975): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3975): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 3975): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 3975): 	at com.google.r.k.c(PG:583)
D/StrictMode( 3975): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 3975): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 3975): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 3975): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 3975): 	at com.google.r.e.b(PG:170)
D/StrictMode( 3975): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 3975): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 3975): StrictMode policy violation; ~duration=1199 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3975): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3975): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3975): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 3975): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 3975): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 3975): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 3975): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/Str,ictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 3975): StrictMode policy violation; ~duration=1199 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3975): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3975): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 3975): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/art     ( 1014): Explicit concurrent mark sweep GC freed 34405(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 26MB/39MB, paused 2.822ms total 197.435ms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4107): MountEmulatedStorage()
E/Zygote  ( 4107): v2
I/libpersona( 4107): KNOX_SDCARD checking this for 1000
I/libpersona( 4107): KNOX_SDCARD not a persona
,I/SELinux ( 4107): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/SecurityLogAgent:SEDenialService( 1014): Got CLOSE_WRITE Event sk.log,
D/SecurityLogAgent:SEDenialService( 1014): Got CLOSE_WRITE Event sk.log,
,D/SecurityLogAgent:SEDenialService( 1014): Got CLOSE_WRITE Event sk.log
,I/ActivityManager( 1014): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4107 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 4107): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4107): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 3179:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,I/GCoreUlr( 1903): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 4107): TimaSignature is unavailable
,D/ActivityThread( 4107): Added TimaKeyStore provider
,I/SA      ( 4067): [SSP] onCreated
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
I/AMMetaDataParserService( 3775,): Resource data:2131165203
I/AuthZen ( 3393): Signing key fetched successfully!
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 3775): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3775): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3775): getResourceTypeNamexml
,W/BaseAppContext( 3393): Using Auth Proxy for data requests.
,D/StatusChecker( 4107): onReceive : android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/dex2oat ( 3931): Verification of android.os.Parcelable android.support.v4.app.v.h() took 101.722ms
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3775): took 2.879219ms for 0*0 texture 0
,I/StatusChecker( 4107): onReceive : net.mt.init : DONE
,I/GAV2    ( 3517): Thread[GAThread,5,main]: No campaign data found.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4130): MountEmulatedStorage(),
E/Zygote  ( 4130): v2
I/libpersona( 4130): KNOX_SDCARD checking this for 10116
I/libpersona( 4130): KNOX_SDCARD not a persona
,I/SELinux ( 4130): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4130): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4130): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4130 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,W/Auth    ( 1903): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/ActivityManager( 1014): Killing 3224:com.fmm.ds/1000 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 4067): [TPM] There is no property file
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1903): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 4130): TimaSignature is unavailable
,D/ActivityThread( 4130): Added TimaKeyStore provider
,I/GFX generate_partition_tables( 3775): took 11.139635ms for 0*0 texture 0
,I/GFX raster( 3775): took 15.002447ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8c304e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a5ef98 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3775): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,I/GAv4-SVC( 3393): Google Analytics 8.4.89 is starting up.
,D/a       ( 3393): Opening database auth.proximity.permit_store...
,I/SA      ( 4067): [SCU] isHaveSA() - false
,I/SA      ( 4067): [TPM] getModelProperty : null
I/SA      ( 4067): [TPM] getCSCProperty : null
,I/SA      ( 4067): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4067): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4067): [DM] TFT FEATURE: false
,I/SA      ( 4067): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,I/SA      ( 4067): [DM] init START
,I/SA      ( 4067): [DM] This device is not a Vodafone
,W/ResourceType( 4067): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4067): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4067): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4067): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4067): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4067): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4067): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4067): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4067): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4067): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4067): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4067): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4067): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4067): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4067): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4067): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4067): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,I/PageBuddyNotiSvc( 4130): Intent received : action=android.intent.action.BOOT_COMPLETED
,W/ResourceType( 4067): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4067): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4067): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4067): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4067): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4067): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4067): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4067): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 4067): [SCU] isHaveSA() - false
I/SA      ( 4067): support phone number id : false
I/SA      ( 4067): [DM] Supports Ref Jpn : true
,I/SA      ( 4067): [DM] init END
,D/AuthZenTransactionCache( 3393): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 3393): Clearing transaction cache
,I/SA      ( 4067): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 4067): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/ActivityManager( 1014): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4067): [OR] onReceive END
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3775): took 1.002968ms for 96*96 texture 0,
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a446a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a5ef98 counterpartCT=4 counterpartW=96 counterparth=96
,W/ContextImpl( 4130): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,E/Zygote  ( 4150): MountEmulatedStorage()
I/ActivityManager( 1014): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4150 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 4150): v2
I/libpersona( 4150): KNOX_SDCARD checking this for 10042
I/libpersona( 4150): KNOX_SDCARD not a persona
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/SA      ( 4067): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4067): [ODM] queryOpenData(key= GEO_IP )
I/SELinux ( 4150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
I/jxcore-log( 3729): JXcore Cordova bridge is ready!
I/jxcore-log( 3729): 
W/jxcore-log( 3729): JXcore engine is started
,I/DBG_DM  ( 2897): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,I/SA      ( 4067): getMccForGalaxyJpn step2 GEO_IP MCC : 260
E/SELinux ( 4150): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/SA      ( 4067): [LBE] REF_JPN : true
,I/SA      ( 4067): [BDC] create
,I/org.thaliproject.p2p.ThaliPermissions( 3729): execute: REQUEST_ACCESS_COARSE_LOCATION
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/PageBuddyNotiSvc( 4130): onCreate mCpBitFlag=0
,E/Zygote  ( 4164): MountEmulatedStorage(),
I/ActivityManager( 1014): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4164 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
D/TimaKeyStoreProvider( 4150): TimaSignature is unavailable
E/Zygote  ( 4164): v2
,D/ActivityThread( 4150): Added TimaKeyStore provider
,I/libpersona( 4164): KNOX_SDCARD checking this for 10125,
,I/libpersona( 4164): KNOX_SDCARD not a persona
,I/SELinux ( 4164): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4164): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/jxcore  ( 3729): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3729): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
E/SELinux ( 4164): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3775): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,I/chromium( 3729): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/FocusedStackFrame( 1014): Set to : 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1014): Focused application set to: xxxx
,D/InputDispatcher( 1014): Focus left window: 3729
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/TimaKeyStoreProvider( 4164): TimaSignature is unavailable
,D/ActivityThread( 4164): Added TimaKeyStore provider
,D/PermissionCache(  256): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1658 us)
,W/ResourcesManager( 4150): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/SA      ( 4067): [DBMV2] getEmailID
,I/SA      ( 4067): [DBMV2] getDataV02ForItems
,I/SA      ( 4067): [SSP] query invoked
,E/SQLiteLog( 3393): (10) POSIX Error : 11 SQLite Error : 3850
,W/PluginManager( 3729): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 62ms. Plugin should use CordovaInterface.getThreadPool().
,D/CustomFrequencyManagerService( 1014): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1014): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1014): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
I/SA      ( 4067): [SCU] get signed id from samsung account2.0 DB.
,V/WindowOrientationListener( 1014): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1014): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,I/SA      ( 4067): [SCU] get signed id from samsung account1.0 DB.
,W/ResourcesManager( 4164): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4164): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4164): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/GCoreUlr( 1903): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/SA      ( 4067): [BDC] destroy
,I/ActivityManager( 1014): Killing 3246:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,D/Launcher( 1492): onRestart, Launcher: 888811943
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.769010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a446a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a5ef98 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1014): [SO] activate (ident=0xb8fc2970, enabled=0)
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.771198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a446a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a5ef98 counterpartCT=4 counterpartW=96 counterparth=96
D/SensorManager( 1014): unregisterListener ::   
,I/Sensors ( 1014): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/Launcher( 1492): onStart, Launcher: 888811943
D/Launcher.HomeView( 1492): onStart
D/SensorService( 1014): [SO] changed settle time [0]
D/SensorService( 1014): [SO] setDelay [200000000]
D/SensorService( 1014): [SO] activate (ident=0xb8fc2970, enabled=1)
D/SensorService( 1014): [SO] AR_init
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/Launcher( 1492): onResume, Launcher: 888811943
,D/SettingsProvider( 1014): name = kids_home_mode
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
,D/SettingsProvider( 1014): selectionArgs: 10007
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
D/Launcher.HomeView( 1492): onResume
D/SensorManager( 1014): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,I/AMMetaDataParserService( 3775): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,D/Launcher( 1492): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1492): onResume
,D/ActivityManager( 1014): handle home activity for 0
I/WallpaperManagerService( 1014): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1014): post home show event for user 0
D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/WallpaperManagerService( 1014):  force update = false; persona id = 0; current user =0; current persona = 0
,D/KnoxTimeoutHandler( 1014): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
,D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,I/SurfaceFlinger(  256): id=12 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/GFX raster( 3775): took 0.709271ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a5ef98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c2f9b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/CalendarProvider2( 4150): CalendarProvider2.onCreate() called
,D/InputDispatcher( 1014): Focus entered window: 1492
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1492): log_dcs ThreadedRenderer::initialize entered! 
,D/Launcher( 1492): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/AMMetaDataParserService( 3775): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/GCoreUlr( 1903): Unbound from all location providers
I/GCoreUlr( 1903): Place inference reporting - stopped
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,W/IInputConnectionWrapper( 3729): showStatusIcon on inactive InputConnection,
,D/SamsungIME( 1812): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false,
,D/QuickConnect( 4164): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED,
D/QuickConnect( 4164): Util.setSCRunningSetting - [value]0
,D/SettingsProvider( 1014): name = scon_is_running
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10125
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/QuickConnect( 4164): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/SystemUpdateService( 3393): onDestroy
I/QuickConnect( 4164): PeriphStartReceiver.onReceive - no need to start
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,D/PersistentNotificationBroadcastReceiver( 1903): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/Timeline( 1492): Timeline: Activity_idle id: android.os.BinderProxy@13fea62c time:45494
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,W/art     ( 3644): Suspending all threads took: 727.239ms
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.687864ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a5ef98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a518c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,D/SensorService( 1014): [SO] Reset Rotation Old [100], Init [1]
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
W/ContextImpl( 3775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3775): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4190): MountEmulatedStorage(),
E/Zygote  ( 4190): v2
I/libpersona( 4190): KNOX_SDCARD checking this for 10131
I/libpersona( 4190): KNOX_SDCARD not a persona,
,I/SELinux ( 4190): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4190): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4190): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4190 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 3270:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,I/GCoreUlr( 1903): DispatchingService.onDestroy()
I/GCoreUlr( 1903): Stopping handler for UlrDispSvcFast
,I/ActivityManager( 1014): Displayed Component not be shown by security: +423ms
,I/GCoreUlr( 1903): Unbound from all location providers
,I/GCoreUlr( 1903): Place inference reporting - stopped
,D/TimaKeyStoreProvider( 4190): TimaSignature is unavailable
,D/ActivityThread( 4190): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3775): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
I/AMMetaDataParserService( 3775): Resource data:2131099648
,W/ResourcesManager( 4190): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4190): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4190): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4190): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/com.google.a.a.b.d.a( 3975): Application name is not set. Call Builder#setApplicationName.
,D/CustomFrequencyManagerService( 1014): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  tag : ACTIVITY_RESUME_BOOSTER@7
I/SecDataIO(  255): Write to block
,W/ActivityManager( 1014): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1014): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/ResourcesManager( 3775): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3775): getResourceName:com.android.mms:xml/assistant_messaging
W/ResourcesManager( 3775): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3775): getResourceTypeNamexml
W/ResourcesManager( 3775): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ResourcesManager( 3775): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/GFX raster( 3775): took 0.678125ms for 96*96 texture 0
W/ResourcesManager( 3775): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a77c08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a63c90 counterpartCT=4 counterpartW=96 counterparth=96
W/ResourcesManager( 3775): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/SensorService( 1014): [SO] currT = 45720103470, prevT = 45240114616, diff = 479988854, [0.096 0.383 10.132]
D/SensorService( 1014): [SO] 0.096 0.383 10.132
D/SensorService( 1014): [SO] [100 -> 255]
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 2514): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/DBG_DM  ( 2897): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/AMMetaDataParserService( 3775): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/DBG_DM  ( 2897): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 2897): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/DBG_DM  ( 2897): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,W/art     ( 3775): Suspending all threads took: 11.425ms
,I/Process ( 2514): Sending signal. PID: 2514 SIG: 9
,D/SBrowserFeatureFlag( 4190): initialized in static block : loadCscFeatureValue() succeed! 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,W/GCoreFlp( 1903): No location to return for getLastLocation()
,W/FusedLocationProvider( 1903): location=null
,I/ActivityManager( 1014): Killing 3085:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ManifestProvider( 4190): onCreate()
,I/ActivityManager( 1014): Process com.sec.android.app.sysscope (pid 2514)(adj 0) has died(46,1145)
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/NetworkSettingsReceiver( 4190): onReceive: android.intent.action.BOOT_COMPLETED
,W/GCoreFlp( 1903): No location to return for getLastLocation()
,W/FusedLocationProvider( 1903): location=null
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3775): took 2.466354ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3775): took 8.827239ms for 0*0 texture 0
,I/GFX raster( 3775): took 12.303646ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a5e920 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8c2f8e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/libprocessgroup( 1014): failed to open /acct/uid_10003/pid_3115/cgroup.procs: No such file or directory
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.641407ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a22188 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a57f50 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1014): failed to open /acct/uid_10057/pid_2984/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10092/pid_3136/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3153/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10060/pid_3179/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3224/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10062/pid_3246/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3270/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10009/pid_3085/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3775): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/CustomFrequencyManagerService( 1014): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  tag : ACTIVITY_RESUME_BOOSTER@11
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.691199ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a60670 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8c2f8e0 counterpartCT=4 counterpartW=96 counterparth=96
,E/SBrowserFeatureFlag( 4190): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@34fa31a7
,D/SBrowserFeatureFlag( 4190): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 4190): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/AMMetaDataParserService( 3775): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{13d4dd2c u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:46049
,I/SurfaceFlinger(  256): id=11 Removed NainActivit (7/8)
,I/SurfaceFlinger(  256): id=11 Removed NainActivit (-2/8)
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.630364ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a79288 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a80408 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1014): Killing 3289:com.wssnps/1000 (adj 15): empty #31
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2897): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec,
I/libpersona( 4218): KNOX_SDCARD checking this for 10135
I/AMMetaDataParserService( 3775): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
I/libpersona( 4218): KNOX_SDCARD not a persona,
E/Zygote  ( 4218): MountEmulatedStorage()
E/Zygote  ( 4218): v2,
I/DBG_DM  ( 2897): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/SELinux ( 4218): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4218): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4218): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4218 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 3317:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,I/DBG_DM  ( 2897): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.753541ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7cdc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7f700 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/ActivityManager( 1014): Killing 3352:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,V/AlarmManager( 1014): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
I/AMMetaDataParserService( 3775): Resource data:2131099648
,I/AMMetaDataParserService( 3775): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3775): getResourceTypeNamexml
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.700052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a77c08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c2f8e0 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4218): TimaSignature is unavailable
,D/ActivityThread( 4218): Added TimaKeyStore provider
E/DBG_DM  ( 2897): [IlIIlIIlIllllIlllIII(226/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,I/AMMetaDataParserService( 3775): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/libprocessgroup( 1014): failed to open /acct/uid_10014/pid_3317/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3289/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10094/pid_3352/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2897): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/accuweather( 1741): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1741): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1741): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1741): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1741): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1741): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1741): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1741): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1741): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1741): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 16 23
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.649532ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a5e920 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a7f700 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/SamsungIME( 1812): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/ResourcesManager( 4218): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4218): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4218): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/OpenGLRenderer( 1492): SFEffectCache::get: create texture(0xa1260724): name, size, mSize = 39, 144744, 315924
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.630937ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a22188 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a57f50 counterpartCT=4 counterpartW=96 counterparth=96
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/AMMetaDataParserService( 3775): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.849167ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a60670 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a7f700 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.751041ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a79288 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a57f50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3775): took 0.745052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7cdc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7f700 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3775): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,E/Zygote  ( 4241): MountEmulatedStorage(),
E/Zygote  ( 4241): v2
I/libpersona( 4241): KNOX_SDCARD checking this for 10139
I/libpersona( 4241): KNOX_SDCARD not a persona
,I/SELinux ( 4241): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4241): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
I/AMMetaDataParserService( 3775): Resource data:2131099648
E/SELinux ( 4241): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3775): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3775): getResourceTypeNamexml
I/ActivityManager( 1014): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4241 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3775): took 0.767865ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a77c08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c2f8e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/TimaKeyStoreProvider( 4241): TimaSignature is unavailable
,D/ActivityThread( 4241): Added TimaKeyStore provider
,I/dex2oat ( 3931): dex2oat took 4.042s (threads: 4)
,W/ResourcesManager( 4241): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4241): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4241): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4241): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4241): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/DexOptUtils( 3393): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.dex
D/DexOptUtils( 3393): Set odex to world readable.
,D/DexOptUtils( 3393): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.odex
,D/FileApkUtils( 3393): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,I/System.out( 3644): INFO:Resource not found:/Common.properties Using default values
,I/art     ( 1660): Explicit concurrent mark sweep GC freed 3964(154KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 773us total 23.588ms
,D/GmsModuleFndr( 3393): Beginning GMS chimera module scan
,I/ActivityManager( 1014): Killing 1230:com.android.defcontainer/u0a4 (adj 15): empty #31
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.665782ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a5e920 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a7f700 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/GmsModuleFndr( 3393): Module pkg com.google.android.apps.kids.familylink not installed, skipping
I/AMMetaDataParserService( 3775): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
D/ChimeraCfgMgr( 3393): Beginning module configuration check
,D/ChimeraCfgMgr( 3393): Module APKs unchanged, check complete
,E/Zygote  ( 4263): MountEmulatedStorage()
,E/Zygote  ( 4263): v2
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/libpersona( 4263): KNOX_SDCARD checking this for 10145
I/libpersona( 4263): KNOX_SDCARD not a persona
,I/GFX raster( 3775): took 0.644218ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a22188 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8c2f8e0 counterpartCT=4 counterpartW=96 counterparth=96
I/SELinux ( 4263): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4263): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4263 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/SELinux ( 4263): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3775): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/ActivityManager( 1014): Killing 3064:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,E/SMD     (  286): DCD OFF
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.662969ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a60670 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a7f700 counterpartCT=4 counterpartW=96 counterparth=96
D/TimaKeyStoreProvider( 4263): TimaSignature is unavailable
,D/ActivityThread( 4263): Added TimaKeyStore provider
I/art     (  303): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 662us total 33.070ms
,I/AMMetaDataParserService( 3775): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3775): took 0.654427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a79288 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c2f8e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 732us total 16.980ms
W/ResourcesManager( 4263): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4263): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4263): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4263): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4263): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3775): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/libprocessgroup( 1014): failed to open /acct/uid_10004/pid_1230/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10015/pid_3064/cgroup.procs: No such file or directory
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 17.001ms
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.722396ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7cdc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7f700 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
I/AMMetaDataParserService( 3775): Resource data:2131099648
,I/AMMetaDataParserService( 3775): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3775): getResourceTypeNamexml
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.700416ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a77c08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a80408 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.650417ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a5e920 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a7f700 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.627500ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a22188 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a6ab98 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.652084ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a60670 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a42350 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.640520ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a79288 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6ab98 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.725989ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7cdc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7f540 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
I/AMMetaDataParserService( 3775): Resource data:2131099648
,I/AMMetaDataParserService( 3775): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3775): getResourceTypeNamexml
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.717082ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a77c08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7e1d8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.800365ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a5e920 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a7f700 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.659219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a22188 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a57f50 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3775): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.666823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a60670 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a5f9e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.646251ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a79288 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a6ab98 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520,
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4288): MountEmulatedStorage()
,E/Zygote  ( 4288): v2,
I/SELinux ( 4288): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/libpersona( 4288): KNOX_SDCARD checking this for 10072
I/libpersona( 4288): KNOX_SDCARD not a persona
,I/SELinux ( 4288): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4288 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/SELinux ( 4288): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/GFX raster( 3775): took 0.839583ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7cdc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a80408 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
I/AMMetaDataParserService( 3775): Resource data:2131099648
,I/AMMetaDataParserService( 3775): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3775): getResourceTypeNamexml
E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/TimaKeyStoreProvider( 4288): TimaSignature is unavailable
,D/ActivityThread( 4288): Added TimaKeyStore provider
I/GFX raster( 3775): took 0.758855ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a77c08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c2f8e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/BadgeProvider( 4288): onCreate
,D/BadgeProvider( 4288): DatabaseHelper
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/ActivityManager( 1014): startService callerProcessName:com.android.email, calleePkgName: com.android.email
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,D/BadgeProvider( 4288): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.636563ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a5e920 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a6a818 counterpartCT=4 counterpartW=96 counterparth=96
,D/BadgeProvider( 4288): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4288): sendNotify, [notify] : null
D/BadgeProvider( 4288): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4288): update, [BadgeCount] : badgecount=0
D/Launcher.Model( 1492): reloadBadges entered.
D/BadgeProvider( 4288): update, [UpdateCount] : 1
,I/AMMetaDataParserService( 3775): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.756146ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a22188 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a42350 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/ActivityManager( 1014): Killing 3435:com.sec.factory.camera/1000 (adj 15): empty #31
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4310): MountEmulatedStorage()
I/libpersona( 4310): KNOX_SDCARD checking this for 10146
E/Zygote  ( 4310): v2
I/libpersona( 4310): KNOX_SDCARD not a persona
I/SELinux ( 4310): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4310 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 3475:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,I/SELinux ( 4310): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4310): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.663125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a60670 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a7f540 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3775): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/TimaKeyStoreProvider( 4310): TimaSignature is unavailable
,D/ActivityThread( 4310): Added TimaKeyStore provider
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.674219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a79288 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7e1d8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4310): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3775): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/GFX raster( 3775): took 0.754845ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb8a7cdc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7f700 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1014): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,I/Process ( 4263): Sending signal. PID: 4263 SIG: 9
,I/AMMetaDataParserService( 3775): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
W/ContextImpl( 3775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3775): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3775): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
I/CalendarProvider2( 4150): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/ActivityManager( 1014): Killing 3491:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
D/RCPManagerService( 1014): exchangeData() failure , invalid userId
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
I/AMMetaDataParserService( 3775): Resource data:2131165197
D/ActivityManager( 1014): startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
W/ResourcesManager( 3775): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3775): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3775): getResourceTypeNamexml
,I/AMMetaDataParserService( 3775): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
E/Zygote  ( 4327): MountEmulatedStorage()
E/Zygote  ( 4327): v2
I/libpersona( 4327): KNOX_SDCARD checking this for 1000
I/libpersona( 4327): KNOX_SDCARD not a persona
I/SELinux ( 4327): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4327): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4327 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 4327): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/lowmemorykiller(  253): Error writing /proc/4263/oom_score_adj; errno=22
I/ActivityManager( 1014): Killing 3502:com.android.managedprovisioning/u0a22 (adj 15): empty #31
I/AMMetaDataParserService( 3775): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
I/ActivityManager( 1014): Process com.android.email (pid 4263)(adj 11) has died(52,1161)
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.exchange, calleePkgName: com.android.email
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3775): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/TimaKeyStoreProvider( 4327): TimaSignature is unavailable
,D/ActivityThread( 4327): Added TimaKeyStore provider
,E/Zygote  ( 4342): MountEmulatedStorage()
E/Zygote  ( 4342): v2
I/libpersona( 4342): KNOX_SDCARD checking this for 10145
I/libpersona( 4342): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4342 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 4342): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4342): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4342): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3775): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3435/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10100/pid_3475/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
I/AMMetaDataParserService( 3775): Resource data:2131165197
,I/AMMetaDataParserService( 3775): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3775): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 4342): TimaSignature is unavailable
,D/ActivityThread( 4342): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3775): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3491/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10022/pid_3502/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3775): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
W/ResourcesManager( 4342): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4342): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4342): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 4342): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4342): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3775): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,E/Zygote  ( 4358): MountEmulatedStorage()
I/libpersona( 4358): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4358): v2
I/libpersona( 4358): KNOX_SDCARD not a persona
I/SELinux ( 4358): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4358): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4358): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3775): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
I/AMMetaDataParserService( 3775): Resource data:2131165197
,I/AMMetaDataParserService( 3775): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3775): getResourceTypeNamexml
,I/ActivityManager( 1014): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4358 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 3544:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,I/AMMetaDataParserService( 3775): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/TimaKeyStoreProvider( 4358): TimaSignature is unavailable
,D/ActivityThread( 4358): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3775): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3775): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3775): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 3775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,W/libprocessgroup( 1014): failed to open /acct/uid_10069/pid_3544/cgroup.procs: No such file or directory
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 31011(1651KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 29MB/44MB, paused 2.376ms total 142.410ms
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
I/AMMetaDataParserService( 3775): Resource data:2131099648
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,W/ResourcesManager( 3775): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3775): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3775): getResourceTypeNamexml
,D/SecurityLogAgent( 4358): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4358): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4358): StateMachine : Current State = 1
D/SecurityLogAgent( 4358): BootReceiver : completed task. Failed to return wakelock . 
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1014): Killing 3560:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3775): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,I/splitIntent( 1014): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1014): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,I/splitIntent( 1014): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3775): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1903): callingUid 10012, callindPid: 1903
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/MDM     ( 1903): [228] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BadgeProvider( 4288): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 3393): Restart initialization of location
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:assistant
I/AMMetaDataParserService( 3775): Resource data:2131165220
,I/Process ( 4310): Sending signal. PID: 4310 SIG: 9
,D/Launcher.Model( 1492): reloadBadges entered.
,D/BadgeProvider( 4288): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4288): sendNotify, [notify] : null
D/BadgeProvider( 4288): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4288): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4288): update, [UpdateCount] : 1
,W/ResourcesManager( 3775): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3775): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3775): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3775): getResourceTypeNamexml
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.919740ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb917bc40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb917b970 counterpartCT=4 counterpartW=96 counterparth=96
,E/lowmemorykiller(  253): Error writing /proc/4310/oom_score_adj; errno=22
,I/AMMetaDataParserService( 3775): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,E/        ( 3775): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3775): took 0.608021ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3775): Bitmap=0xb917ba90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb918edb8 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3775): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,D/TP/SmsProvider( 1469): query,matched:0, calling pid = 3393
,D/TP/SmsProvider( 1469): match 0:Elapsed time : 1.836 ms
,I/ActivityManager( 1014): Process com.android.exchange (pid 4310)(adj 13) has died(51,1162)
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity,
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity,
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check,
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.TetherSettings,
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.samsung.android.multiuser.install_only_owner,
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity,
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings,
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3560/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/ContextImpl( 3775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.LanguageSettings
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
D/TP/MmsProvider( 1469): Query uri=content://mms, match=0, calling pid = 3393
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.RunningServices
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS,
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ProxySelector
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
,I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
,I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3775): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3775): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3775): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
D/TP/SmsProvider( 1469): query,matched:0, calling pid = 3393
D/TP/SmsProvider( 1469): match 0:Elapsed time : 1.367 ms
D/TP/MmsProvider( 1469): Query uri=content://mms, match=0, calling pid = 3393
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AuthorizationBluetoothService( 1903): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/a       ( 1903): Opening database auth.proximity.permit_store...
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 3393): getNumBytesRead when not calculated.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1903): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PowerManagerService( 1014): [s] UserActivityState : 1 -> 2
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1014): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1014): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1014): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1014): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/lights  ( 1014): lcd : 44 +
,W/GCoreFlp( 1903): No location to return for getLastLocation()
,W/FusedLocationProvider( 1903): location=null
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1014): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1014): lcd : 44 -
D/lights  ( 1014): lcd : 19 +
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1903): [242] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,D/lights  ( 1014): lcd : 19 -
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1014): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 3393): Restart initialization of location
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1903): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,V/GLSActivity( 1903): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/GCoreFlp( 1903): No location to return for getLastLocation()
,W/FusedLocationProvider( 1903): location=null
,D/ActivityManager( 1014): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4410 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 4410): MountEmulatedStorage()
E/Zygote  ( 4410): v2
I/libpersona( 4410): KNOX_SDCARD checking this for 1000
I/libpersona( 4410): KNOX_SDCARD not a persona
,I/SELinux ( 4410): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4410): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4410): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4410): TimaSignature is unavailable
,D/ActivityThread( 4410): Added TimaKeyStore provider
,E/MTPRx   ( 4410): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedState
D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1014): mCursor = null
,V/MTPRx   ( 4410): sealedState: false
V/MTPRx   ( 4410): sealedUsbMassStorageState: false
,E/MTPRx   ( 4410): check value of boot_completed is1
E/MTPRx   ( 4410): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4410): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4410): Status for mount/Unmount :removed
E/MTPRx   ( 4410): SDcard is not available
,W/MTPRx   ( 4410): value of connected istrue
W/MTPRx   ( 4410): value of configured istrue
W/MTPRx   ( 4410): value of mtpEnabled istrue
W/MTPRx   ( 4410): value of ptpEnabled isfalse
,E/MTPRx   ( 4410): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4410): mFirstTime: false
,D/        ( 4410): MTP: reading debug level property
,E/MTPJNIInterface( 4410): Getting CryptionKey from JAVA
,E/MTPRx   ( 4410): currentUserId is 0
,E/MTPRx   ( 4410): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4410): cannot open file : /sys/class/android_usb/android0/bcdUSB
,E/MTPRx   ( 4410): is_Privatemode is NOT 1
,D/SettingsProvider( 1014): name = boot_time_connected
,E/MTPRx   ( 4410): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4410): noti = 17
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,D/SecContentProvider( 1014): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4410): sending MTP_ICON_ENABLED to stack
,I/ValidateNoPeople( 1014): mEvictionCount: 0
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1014): name = mtp_running_status
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,E/MTPRx   ( 4410): else part ... so first time!!!
,E/MTPPlaObsrvr( 4410): inside setContext()
E/MTPPlaObsrvr( 4410):  inside createplafiles
,E/MTPPlaObsrvr( 4410): playlist count is0
,E/MTPPlaObsrvr( 4410):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4410):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4410): Inside registerContentObserver
,E/MtpAdbObserver( 4410): inside setContext()
,E/MtpAdbObserver( 4410): Inside registerContentObserver
W/Settings( 4410): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1014): name = mtp_running_status
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,E/MtpService( 4410): onCreate.
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,V/MtpMediaDBManager( 4410): inside deleteAllDB
,E/MtpService( 4410): < MTP > Registering BroadCast receiver :::::
,D/MtpService( 1250): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 4410): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,E/MtpService( 4410): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MtpService( 4410): onStartCommand.
,W/MTPRx   ( 4410): calling native method
E/MTPJNIInterface( 4410): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4410): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 4410): < MTP > Registering BroadCast receiver :::::::
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1903): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,E/MTPJNIInterface( 4410): noti = 10
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/MtpMediaDBManager( 4410): inside Thread updateDB
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MtpService( 4410): onStartCommand.
,E/MtpService( 4410): handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/MTPRx   ( 4410): calling native method
,E/MTPRx   ( 4410): Checking the driver time out
E/MTPJNIInterface( 4410): noti = 2
D/        ( 4410): deleting sockets before message queue initialization
,D/        ( 4410): event handler thread is created, so set the flag
,E/MTPRx   ( 4410): called native method
E/MTPJNIInterface( 4410): setting Media scanner status0
E/MTPJNIInterface( 4410): After setting Media scanner status0
,E/MtpMediaDBManager( 4410): count : 27
W/MTPRx   ( 4410): notification from stack 1
,E/        ( 4410): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4410): Getting media scanner status0
,E/MTPJNIInterface( 4410): DeviceName is A5-1
,D/daemonapp( 1333): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1333): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/MtpMediaDBManager( 4410): sending db update complete noti to stack
E/MTPJNIInterface( 4410): noti = 29
,D/daemonapp( 1333): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1333): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1333): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1333): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1333): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1333): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1333): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1333): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1333): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1457644920000
D/daemonapp( 1333): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1457623382340
,D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1333): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,E/MTPJNIInterface( 4410): Status for mount/Unmount :removed
E/MTPJNIInterface( 4410): SDcard is not available
,D/daemonapp( 1333): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1333): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1333): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1333): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 4410): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,E/        ( 4410): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/Zygote  ( 4431): MountEmulatedStorage(),
E/Zygote  ( 4431): v2
I/libpersona( 4431): KNOX_SDCARD checking this for 10111
I/libpersona( 4431): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4431 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4431): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/MTPJNIInterface( 4410): Status for mount/Unmount :removed
E/MTPJNIInterface( 4410): SDcard is not available
E/SQLiteLog( 4410): (21) API call with NULL database connection pointer
E/SQLiteLog( 4410): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4410): (21) API call with NULL database connection pointer
E/SQLiteLog( 4410): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4410): (21) API call with NULL database connection pointer
E/SQLiteLog( 4410): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4410): (21) API call with NULL database connection pointer
E/SQLiteLog( 4410): (21) misuse at line 106108 of [9491ba7d73]
W/MTPRx   ( 4410): notification from stack 2
,D/        ( 4410): [mtp_init_device] Library open with 32 bits.
D/        ( 4410): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 4410): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
,D/        ( 4410): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4410):  [sua_support_present:1287] returning false 
D/        ( 4410): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
I/SELinux ( 4431): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4431): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL

```
