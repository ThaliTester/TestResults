#### Test 62509094c453ee6_thali01_samsung-SM-A500FU Logs


```
--------- beginning of system
W/ResourcesManager( 3998): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
--------- beginning of main
I/Gmail   ( 3851): getAccountsCursor
D/FactoryTestApp( 2673): [DummyFtClient$onDestroy](2673) Destroy DummyFtClient service
D/FactoryTestApp( 2673): [Support$Values.getString](2673) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2673): [ModuleCommon$isConnectionModeNone](2673) mConnectionMode = gsm
I/FactoryTestApp( 2673): [ModuleCommon$isRunningFtClient](2673) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2673): [DummyFtClient$onDestroy](2673) kill process
I/Process ( 2673): Sending signal. PID: 2673 SIG: 9
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.syncadapters.calendar, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.syncadapters.calendar, destAppInfo.processName = com.google.android.gms
W/GAV2    ( 3851): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/System.out( 2942): (HTTPLog)-Static: isSBSettingEnabled false
I/ActivityManager( 1016): Process com.sec.factory (pid 2673)(adj 0) has died(105,1129)
I/qtaguid ( 2942): Tagging socket 28 with tag 1000000400000000{268435460,0} for uid -1, pid: 2942, getuid(): 10102
I/qtaguid ( 2942): Tagging socket 32 with tag 1000000400000000{268435460,0} for uid -1, pid: 2942, getuid(): 10102
I/VlingoApplication( 3965): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
I/DBG_DM  ( 3231): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
I/VlingoAndroidCore( 3965): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/ActivityManager( 1016): Killing 3088:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
E/Gmail   ( 3851): Error finding the version of the Email provider.....
E/Gmail   ( 3851): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3851): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3851): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3851): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3851): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3851): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3851): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3851): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3851): We do not support migrating this version of the Email provider.
I/Gmail   ( 3851): getAccountsCursor
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
V/CalendarSyncAdapter( 2942): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2017-03-25T00:00:00.000Z, updatedMin=2016-02-15T23:58:22.671Z}
I/qtaguid ( 2942): Untagging socket 28
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/GoogleHttpClient( 1660): GMS http client unavailable, use old client
D/AndroidRuntime( 4028): 
D/AndroidRuntime( 4028): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
E/Zygote  ( 4047): MountEmulatedStorage()
E/Zygote  ( 4047): v2
I/libpersona( 4047): KNOX_SDCARD checking this for 10104
I/libpersona( 4047): KNOX_SDCARD not a persona
D/AndroidRuntime( 4028): CheckJNI is OFF
D/AndroidRuntime( 4028): readGMSProperty: start
D/AndroidRuntime( 4028): readGMSProperty: already setted!!
D/AndroidRuntime( 4028): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4028): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4028): readGMSProperty: end
D/AndroidRuntime( 4028): addProductProperty: start
I/SELinux ( 4047): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4047): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4047 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/SELinux ( 4047): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1016): failed to open /acct/uid_10085/pid_3088/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 4047): TimaSignature is unavailable
D/ActivityThread( 4047): Added TimaKeyStore provider
D/VlingoApplication( 3965): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 3965): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
W/ResourcesManager( 4047): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/DialogFlow( 3965): initQueue()
I/DBG_POLICYDM( 3305): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
I/DBG_POLICYDM( 3305): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
I/DBG_POLICYDM( 3305): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
I/DBG_POLICYDM( 3305): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
I/DBG_POLICYDM( 3305): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
I/DBG_POLICYDM( 3305): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/AffinityControl( 4028): AffinityControl: registerfunction enter
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 3305): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4072): MountEmulatedStorage()
E/Zygote  ( 4072): v2
I/libpersona( 4072): KNOX_SDCARD checking this for 10032
I/libpersona( 4072): KNOX_SDCARD not a persona
I/SELinux ( 4072): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4072): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4072 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 4072): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 4028): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TimaKeyStoreProvider( 4072): TimaSignature is unavailable
D/ActivityThread( 4072): Added TimaKeyStore provider
D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/FocusedStackFrame( 1016): Set to : 0
D/CalendarSyncAdapter( 2942): Found 0 events marked dirty & lastSynced
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 1504
D/Launcher.HomeView( 1504): onPause
D/Launcher( 1504): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/AndroidRuntime( 4028): Shutting down VM
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : -2122120936
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=10 createSurf (1x1),1 flag=404, uhalitest
E/Zygote  ( 4091): MountEmulatedStorage()
E/Zygote  ( 4091): v2
I/libpersona( 4091): KNOX_SDCARD checking this for 10155
I/libpersona( 4091): KNOX_SDCARD not a persona
I/SELinux ( 4091): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4091 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4091): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4091): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 3269:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
V/ActivityThread( 1504): updateVisibility : ActivityRecord{32ce821f token=android.os.BinderProxy@92ad608 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/art     (  308): Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 657us total 60.500ms
I/ActivityManager( 1016): Killing 3305:com.policydm/1000 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/TimaKeyStoreProvider( 4091): TimaSignature is unavailable
D/ActivityThread( 4091): Added TimaKeyStore provider
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 19.423ms
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1504): onStop
V/ActivityThread( 1504): updateVisibility : ActivityRecord{32ce821f token=android.os.BinderProxy@92ad608 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/Gmail   ( 3851): Observing account changes for notifications
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 21.893ms
D/PersonaManager( 1016): isKioskContainerExistOnDevice
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 3851): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@20417e0e that was originally bound here
E/ActivityThread( 3851): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@20417e0e that was originally bound here
E/ActivityThread( 3851): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3851): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3851): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3851): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3851): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3851): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3851): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3851): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3851): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3851): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3851): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3851): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3851): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3851): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3851): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3851): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1016): Unbind failed: could not find connection for android.os.BinderProxy@172af10a
D/SensorService( 1016): [SO] activate (ident=0xb8e95d40, enabled=0)
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/Finsky  ( 3983): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/SensorManager( 1016): unregisterListener ::   
I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1016): [SO] changed settle time [1]
D/SensorService( 1016): [SO] setDelay [66000000]
D/SensorService( 1016): [SO] activate (ident=0xb8e95d40, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/Launcher( 1504): onTrimMemory. Level: 20
W/art     ( 4028): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,E/SQLiteLog( 3851): (283) recovered 56 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3269/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3305/cgroup.procs: No such file or directory
,D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,I/ActivityManager( 1016): Killing 3322:com.google.android.configupdater/u0a86 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4115): MountEmulatedStorage()
,E/Zygote  ( 4115): v2,
,I/libpersona( 4115): KNOX_SDCARD checking this for 10033
,I/ActivityManager( 1016): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4115 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/libpersona( 4115): KNOX_SDCARD not a persona
,I/WebViewFactory( 4091): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/ActivityManager( 1016): Killing 3408:com.dropbox.android/u0a92 (adj 15): empty #31
,I/SELinux ( 4115): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4115): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4115): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/SensorService( 1016): [SO] 0.134 0.402 10.132
,D/SensorService( 1016): [SO] [100 -> 255]
,I/LibraryLoader( 4091): Time to load native libraries: 8 ms (timestamps 2639-2647)
I/LibraryLoader( 4091): Expected native library version number "",actual native library version number ""
,D/PowerManagerService( 1016): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1180 (0x0)
,D/AndroidHttpClient( 3381): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
D/TimaService( 1016): TIMA: in getTimaVersion
D/AndroidHttpClient( 3381): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 3381): Thread-528(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3381): Thread-528(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3381): Thread-528(ApacheHTTPLog):isShipBuild true
I/System.out( 3381): Thread-528(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3381): Thread-528(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): uids 10166
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10166
,D/TimaService( 1016): TIMA3: KeyStore3_init
,D/TimaService( 1016): TIMA: in getTimaVersion
,D/TimaKeyStoreProvider( 4115): TimaSignature is unavailable
,D/ActivityThread( 4115): Added TimaKeyStore provider
,E/TLC_TZ_KEYSTORE: ( 1016): Inside TZ_KEYSTORE_initialize(),
,I/TLC_TZ_KEYSTORE: ( 1016): creating new keystore context...
I/TLC_TZ_KEYSTORE: ( 1016): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 1016): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1016): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1016): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x880
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,V/WebViewChromiumFactoryProvider( 4091): Binding Chromium to main looper Looper (main, tid 1) {25794b57}
,I/LibraryLoader( 4091): Expected native library version number "",actual native library version number ""
,I/chromium( 4091): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 10
,I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
,I/TLC_TZ_KEYSTORE: ( 1016): ctx = 0xb8d54910, comm = 0xb8e5ad70, sendmsg = 0x9d795000, recvmsg = 0x9d795440
I/TZ_init: ( 1016): TZ_init: sending initialization request...
E/TZ_init: ( 1016): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1016): trustlet initialization failed
I/TZ_init: ( 1016): TZ_init_START...
,I/TZ_init: ( 1016): TZ_init_with_data: sending initialization request...
,I/TZ_init: ( 1016): TZ_init: successful initialization
D/QSEECOMAPI: ( 1016): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1016): QSEECom_shutdown_app, app_id = 10
,E/TLC_TZ_KEYSTORE: ( 1016): Count : 1, Ret : 0
,I/BrowserStartupController( 4091): Initializing chromium process, singleProcess=true
,W/art     ( 4091): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4091): ApplicationContext is null in ApplicationStatus
,E/File    ( 3851): fail readDirectory() errno=2
,W/chromium( 4091): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 4091): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 4091): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Gmail   ( 3851): notifyAccountChanged
,I/Adreno-EGL( 4091): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4091): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4091): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4091): Local Branch: 
I/Adreno-EGL( 4091): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4091): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4091):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/Gmail   ( 3851): getAccountsCursor
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3851): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/libprocessgroup( 1016): failed to open /acct/uid_10086/pid_3322/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_3408/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Killing 3457:com.fmm.dm/1000 (adj 15): empty #31
,I/SurfaceFlinger(  259): id=8 Removed Mauncher (5/8)
,I/SurfaceFlinger(  259): id=8 Removed Mauncher (-2/8)
,D/Finsky  ( 3983): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3457/cgroup.procs: No such file or directory
,I/Gmail   ( 3851): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/DBG_DM  ( 3231): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,W/ContextImpl( 3998): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,W/Settings( 3983): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3983): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Gmail   ( 3851): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3851): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ResourcesManager( 4115): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4115): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4115): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 39965(1988KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/40MB, paused 2.862ms total 167.965ms
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,W/ResourcesManager( 4115): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4115): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4115): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4115): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.,
W/ResourcesManager( 4115): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4115): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 4165): MountEmulatedStorage(),
,E/Zygote  ( 4165): v2,
I/libpersona( 4165): KNOX_SDCARD checking this for 1000
,I/libpersona( 4165): KNOX_SDCARD not a persona
,I/SELinux ( 4165): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4165): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4165 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 4165): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3934): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 3934): Resource data:2131165186
,W/ResourcesManager( 3934): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3934): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3934): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 4165): TimaSignature is unavailable
,D/ActivityThread( 4165): Added TimaKeyStore provider
,W/ResourcesManager( 4165): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/Volley  ( 3983): [603] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3983): [596] DiskBasedCache.clear: Cache cleared.
,W/chromium( 4091): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/ContextImpl( 4165): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 3381): Thread-528 calls detatch()
,I/F_PHONE ( 4165): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 4165): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,D/Ads     ( 3983): Skipping gmscore version check
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/art     ( 4091): Attempt to remove local handle scope entry from IRT, ignoring
,D/ActivityManager( 1016): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,W/SEAMService( 1016):  hashset_to_int_array returning null
,I/AMMetaDataParserService( 3934): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,W/SEAMService( 1016):  hashset_to_int_array returning null
,D/Finsky  ( 3983): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3983): [1] Libraries$2.run: Finished loading 1 libraries.
E/SQLiteLog( 3998): (284) automatic index on seams_container_info(seams_container_id)
,D/FileApkUtils( 2077): Optimizing (staging complete)
,D/FileApkUtils( 2077): Optimizing: DynamiteModules-prod.apk [0224a548494bce36274e23f9f1b42d4fbe3d4d8de53a7872e503f8974e43c3c3]
,I/art     ( 2077): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
E/SQLiteLog( 3998): (284) automatic index on seams_container_info(sp_id)
,D/F_PHONE ( 4165): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 4165): default registerAction()
I/F_PHONE ( 4165): [[com.sec.bcservice]] sendPendingMessage()
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3503): unregister AuthInfo UpdateReceiver v2.0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/AwContents( 4091): onDetachedFromWindow called when already detached. Ignoring
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3934): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,D/DexOptUtils( 2077): Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk appears to be unoptimized.
,D/DexOptUtils( 2077): Lollipop platform, using <isa> directory.
,D/DexOptUtils( 2077): Instantiating DexClassLoader to force creation of odex.
,W/SEAMService( 1016):  hashset_to_int_array returning null
,D/DexOptUtils( 2077): Primary ABI of odexing process is armeabi-v7a
,D/PhoneWindow( 4091): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 4091): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 4091): CordovaWebView is running on device made by: samsung
,I/AMMetaDataParserService( 3934): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,W/art     ( 4091): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4091): Attempt to remove local handle scope entry from IRT, ignoring
,I/Gmail   ( 3851): getAccountsCursor
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/Finsky  ( 3983): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/dex2oat ( 4195): ----------------------------------------------------
,I/dex2oat ( 4195): <SS>: S T A R T I N G . . .
I/dex2oat ( 4195): <SS>: Zip is absent. Canceled.
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
W/ContextImpl( 3934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/dex2oat ( 4195): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk --oat-fd=40 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectB,ookmarkFolderActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/OpenGLRenderer( 4091): Render dirty regions requested: true
D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,D/PhoneWindow( 4091): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 4091): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1016): Focus entered window: 4091
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:assistant
I/AMMetaDataParserService( 3934): Resource data:2131034113
,D/SRIB_DCS( 4091): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 4091): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4091): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 4091): Enabling debug mode 0
,W/ResourcesManager( 3934): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3934): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3934): getResourceTypeNamexml
,D/Finsky  ( 3983): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3934): took 2.118854ms for 0*0 texture 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX generate_partition_tables( 3934): took 6.246197ms for 0*0 texture 0
,I/GFX raster( 3934): took 9.635677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89e6058 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb89fd608 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1016): Displayed Component not be shown by security: +1s339ms
,I/SamsungIME( 1902): getCurrentCandidateView
,I/Timeline( 4091): Timeline: Activity_idle id: android.os.BinderProxy@15ea77e0 time:43659
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
,I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{333a468 u0 com.test.thalitest/.MainActivity t12} time:43662
W/ActivityManager( 1016): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
,E/SMD     (  292): DCD OFF
,D/ChimeraCfgMgr( 1924): Reading stored module config
,I/Babel   ( 4047): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4047): MmsConfig.loadMmsSettings
I/Babel   ( 4047): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 4047): MmsConfig.loadFromDatabase
,E/Babel   ( 4047): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4047): MmsConfig.loadFromResources
,E/Babel   ( 4047): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4047): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/WearableService( 1924): callingUid 10012, callindPid: 1924
,D/SSRM:n  ( 1016): SIOP:: AP = 390
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.813490ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89e6058 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a05700 counterpartCT=4 counterpartW=96 counterparth=96
,E/GmsWearableNodeHelper( 1924): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3934): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/art     ( 4047): Suspending all threads took: 6.588ms
,W/ResourcesManager( 4072): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/BindingManager( 4091): Cannot call determinedVisibility() - never saw a connection for the pid: 4091
,I/GFX construct_block_size_descriptor_2d second part( 3934): took 2.292345ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3934): took 7.547657ms for 0*0 texture 0
,I/GFX raster( 3934): took 10.757345ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8a020d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a02228 counterpartCT=4 counterpartW=96 counterparth=96
,I/SurfaceFlinger(  259): id=10 Removed uhalitest (7/8)
,W/Settings( 4047): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SurfaceFlinger(  259): id=10 Removed uhalitest (-2/8)
,I/AMMetaDataParserService( 3934): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/DBG_DM  ( 3231): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.606875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8a06a98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a06bf0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/ResourcesManager( 4072): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4072): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4072): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.814948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8a04900 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a049c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,W/InstanceID/Rpc( 2077): Found 10012
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.626927ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8a06188 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a062e0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SamsungIME( 1902): Dismiss ExpandCandiate
,I/AMMetaDataParserService( 3934): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/art     ( 4047): Suspending all threads took: 13.456ms
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3934): took 0.690312ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8a04c28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a04cf0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Babel_StickerModule( 4047): App launched.
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.535781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8a048a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89e6120 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3934): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:assistant
I/AMMetaDataParserService( 3934): Resource data:2131034113
,I/AMMetaDataParserService( 3934): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3934): getResourceTypeNamexml
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 1.133542ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89e6058 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb89e6120 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3934): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,V/Babel   ( 4047): babel boot account: SMS
,W/Babel   ( 4047): EsDatabaseHelper.static should not be called on main thread [called on main thread]
,W/Babel   ( 4047): java.lang.Exception
W/Babel   ( 4047): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4047): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 4047): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4047): 	at ckh.a(SourceFile:67)
W/Babel   ( 4047): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4047): 	at bhn.a(SourceFile:301)
W/Babel   ( 4047): 	at bhn.a(SourceFile:137)
W/Babel   ( 4047): 	at bhn.a(SourceFile:126)
W/Babel   ( 4047): 	at bhn.a(SourceFile:159)
W/Babel   ( 4047): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4047): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4047): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4047): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4047): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4047): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4047): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4047): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4047): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4047): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4047): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/Babel   ( 4047): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 4047): java.lang.Exception
W/Babel   ( 4047): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4047): 	at aes.a(SourceFile:145)
W/Babel   ( 4047): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4047): 	at ckh.a(SourceFile:67)
W/Babel   ( 4047): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4047): 	,at bhn.a(SourceFile:301)
W/Babel   ( 4047): 	at bhn.a(SourceFile:137)
W/Babel   ( 4047): 	at bhn.a(SourceFile:126)
W/Babel   ( 4047): 	at bhn.a(SourceFile:159)
W/Babel   ( 4047): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4047): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4047): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4047): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4047): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4047): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4047): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4047): 	at java.lang.reflect.Method.invoke(Native Method)
,W/Babel   ( 4047): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4047): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4047): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.812917ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89e6058 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb89e6120 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3934): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 2077): COMPAT: Multi user not supported
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/JsMessageQueue( 4091): Set native->JS mode to OnlineEventsBridgeMode
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.602760ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8a020d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89e6120 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3934): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
V/Babel   ( 4047): babel boot account: thalitester@gmail.com
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 2077): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,W/Babel   ( 4047): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Babel   ( 4047): java.lang.Exception
W/Babel   ( 4047): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4047): 	at aes.a(SourceFile:145)
W/Babel   ( 4047): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4047): 	at ckh.a(SourceFile:67)
W/Babel   ( 4047): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4047): 	at bhn.a(SourceFile:301)
W/Babel   ( 4047): 	at bhn.a(SourceFile:137)
W/Babel   ( 4047): 	at bhn.a(SourceFile:126)
W/Babel   ( 4047): 	at bhn.a(SourceFile:159)
W/Babel   ( 4047): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4047): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4047): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4047): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4047): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4047): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4047): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4047): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4047): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4047): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4047): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.788646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8a02098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a022b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/Process ( 4115): Sending signal. PID: 4115 SIG: 9
,I/AMMetaDataParserService( 3934): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/jxcore_app_log( 4091): JniHelper::setJavaVM(0xb8629450), pthread_self() = -1195862472
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4091): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4091):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4091):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4091):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4091):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4091): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d1f202f added. We now have 1 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091): setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4091): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4091): setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4091): setHandshakeRequired: true -> false
E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4091): setHandshakeRequired: true -> false
,I/GFX raster( 3934): took 1.007135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8a022b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a04860 counterpartCT=4 counterpartW=96 counterparth=96
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091):     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309b6d1a added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4091): addListener: New listener added - the number of listeners is now 1
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
I/CheckinService( 2077): Disabling old GoogleServicesFramework version
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4091): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4091): setScanMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4091): bind: Binding a new listener
,I/ActivityManager( 1016): Process com.sec.android.app.sns3 (pid 4115)(adj 0) has died(39,1158)
,I/AMMetaDataParserService( 3934): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4252): MountEmulatedStorage(),
E/Zygote  ( 4252): v2
,I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4252 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
I/libpersona( 4252): KNOX_SDCARD checking this for 10034
I/libpersona( 4252): KNOX_SDCARD not a persona,
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3934): took 0.696458ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89e52e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8982620 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4252): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4252): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,D/ChimeraCfgMgr( 2077): Reading stored module config,
,E/SELinux ( 4252): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4091): initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4263 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/AMMetaDataParserService( 3934): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/Zygote  ( 4263): MountEmulatedStorage()
I/libpersona( 4263): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4263): v2
I/libpersona( 4263): KNOX_SDCARD not a persona
,I/SELinux ( 4263): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4263): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4263): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 0
,I/GFX raster( 3934): took 0.689688ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89c7bc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8631ec0 counterpartCT=4 counterpartW=96 counterparth=96
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 4091): bind: Binding a new listener
,W/QCamera2Factory(  284): getCameraInfo: X
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3934): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4252): TimaSignature is unavailable
,D/ActivityThread( 4252): Added TimaKeyStore provider
W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  284): getCameraInfo: X
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.533698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8982620 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89e5eb8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4263): TimaSignature is unavailable
D/ActivityThread( 4263): Added TimaKeyStore provider
,D/BootCompletedReceiver( 2077): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 2077): Got an BootCompleted event.
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/VideoCapabilities( 4047): Unrecognized profile 2130706433 for video/avc
,I/DBG_DM  ( 3231): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/chromium( 4091): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/AudioCapabilities( 4047): Unsupported mime audio/evrc
,I/AMMetaDataParserService( 3934): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/BootCompletedReceiver( 2077): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SystemUpdateService( 2077): onCreate
,I/AMMetaDataParserService( 3934): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3934): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3934): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3934): getResourcePackageName:assistant
I/AMMetaDataParserService( 3934): Resource data:2131034112
,W/AudioCapabilities( 4047): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4047): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 4047): Unsupported mime audio/mpeg-L2
,I/AMMetaDataParserService( 3934): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3934): getResourceTypeNamexml
E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3934): took 0.603021ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8a02098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8631ec0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.631145ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8a02098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89e5eb8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4287 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 4287): MountEmulatedStorage()
E/Zygote  ( 4287): v2
I/libpersona( 4287): KNOX_SDCARD checking this for 1000
I/libpersona( 4287): KNOX_SDCARD not a persona
,I/SELinux ( 4287): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/SystemUpdateService( 2077): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/AudioCapabilities( 4047): Unsupported mime audio/x-ms-wma
,I/ActivityManager( 1016): Killing 3476:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/SELinux ( 4287): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4287): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/AudioCapabilities( 4047): Unsupported mime audio/x-ima
,W/AudioCapabilities( 4047): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4047): Unsupported mime audio/evrc
,V/AuthZen ( 2077): Handling intent: android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 4287): TimaSignature is unavailable
,D/ActivityThread( 4287): Added TimaKeyStore provider
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.671406ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8631ec0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb89e5eb8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.632032ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89e52e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89e5eb8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3934): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/SamsungIME( 1902): getDebugLevel  : 0x4f4c
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:assistant
I/AMMetaDataParserService( 3934): Resource data:2131034113
I/AMMetaDataParserService( 3934): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3934): getResourceTypeNamexml
E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3934): took 0.800261ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89e5eb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb89c7760 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3934): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
D/AuthZenEventHandler( 2077): Handling event: android.intent.action.BOOT_COMPLETED
,W/VideoCapabilities( 4047): Unsupported mime video/wvc1
,W/VideoCapabilities( 4047): Unsupported mime video/x-ms-wmv
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.864740ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89e5eb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb89c7760 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 4047): Unrecognized profile/level 32768/2 for video/mp4v-es
,I/AMMetaDataParserService( 3934): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/VideoCapabilities( 4047): Unsupported mime video/wvc1
,W/VideoCapabilities( 4047): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 4047): Unsupported mime video/x-ms-wmv7
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,I/SamsungIME( 1902): getDebugLevel  : 0x4f4c
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/VideoCapabilities( 4047): Unsupported mime video/x-ms-wmv8
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.608594ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8a020d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89c7760 counterpartCT=4 counterpartW=96 counterparth=96
,D/KnoxSetupWizardDbHelper( 4287): dbMigrationFlag : false
,W/VideoCapabilities( 4047): Unsupported mime video/mp43
,I/AMMetaDataParserService( 3934): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,E/Zygote  ( 4305): MountEmulatedStorage()
E/Zygote  ( 4305): v2
I/libpersona( 4305): KNOX_SDCARD checking this for 1000
I/libpersona( 4305): KNOX_SDCARD not a persona
,I/SELinux ( 4305): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4305): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4305): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4305 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1016): Killing 3340:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 4047): Unsupported mime video/sorenson
I/SamsungIME( 1902): KeybaordView init() : load resources
,D/ShortcutReceiver( 4287):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 4305): TimaSignature is unavailable
,D/ActivityThread( 4305): Added TimaKeyStore provider
,I/CheckinService( 2077): Checking schedule, now: 1458035920440 next: 1458246240395
W/VideoCapabilities( 4047): Unsupported mime video/mp4v-esdp
,I/SecDataIO(  258): Write to block
,I/CheckinService( 2077): active receiver: disabled
,W/ContextImpl( 2653): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/DBG_DM  ( 3231): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 3231): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 3231): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,W/BaseAppContext( 2077): Using Auth Proxy for data requests.
,I/Process ( 2653): Sending signal. PID: 2653 SIG: 9
,I/DBG_DM  ( 3231): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1902): getCurrentKeyboard
I/SamsungIME( 1902): getTextKeyboard
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.747237ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8a02098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89dd220 counterpartCT=4 counterpartW=96 counterparth=96
,D/KnoxShortcutUtil( 4287): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4287):  KnoxContainerVersion 2.4.0
,D/ShortcutReceiver( 4287):  shortcut migration not required 
,I/AMMetaDataParserService( 3934): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4323): MountEmulatedStorage()
,E/Zygote  ( 4323): v2
I/libpersona( 4323): KNOX_SDCARD checking this for 1000
I/libpersona( 4323): KNOX_SDCARD not a persona
,I/SELinux ( 4323): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4323 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/SamsungIME( 1902): [SwiftkeyWrapper] currentLangauge : 1701729619
I/SELinux ( 4323): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4323): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 3542:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.891979ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8a022b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89c7760 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Process com.sec.android.app.sysscope (pid 2653)(adj 0) has died(47,1143)
,W/libprocessgroup( 1016): failed to open /acct/uid_10003/pid_3476/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_3340/cgroup.procs: No such file or directory
,I/SystemUpdateService( 2077): cancelUpdate (empty URL)
,I/SystemUpdateService( 2077): active receiver: disabled
,I/AMMetaDataParserService( 3934): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/TimaKeyStoreProvider( 4323): TimaSignature is unavailable
,D/ActivityThread( 4323): Added TimaKeyStore provider
,I/VideoCapabilities( 4047): Unsupported profile 4 for video/mp4v-es
,W/art     ( 1902): Suspending all threads took: 12.728ms
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.638906ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89e52e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86304a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3934): took 0.781354ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89c7bc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89dd220 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.525260ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8982620 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89fd740 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1442): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1442): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/KnoxSetupWizardClient( 4323): isShipMode : 1
I/KnoxSetupWizardClient( 4323): onReceive : android.intent.action.BOOT_COMPLETED
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2692): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2692): Disconnected process message: 10
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
W/ContextImpl( 3934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,W/libprocessgroup( 1016): failed to open /acct/uid_10060/pid_3542/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/DBG_POLICYDM( 4305): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4305): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts,
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics,
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.DataConnection
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing,
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange,
W/ResourcesManager( 3934): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions,
,W/ResourcesManager( 3934): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
,W/ResourcesManager( 3934): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
,W/ResourcesManager( 3934): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering,
W/ResourcesManager( 3934): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity,
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup,
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity,
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.Debug
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
,I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3934): Resource data:2131165203
I/AMMetaDataParserService( 3934): getResourceName:com.android.email:xml/email_assistant_menu,
I/AMMetaDataParserService( 3934): getResourceTypeNamexml
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/DBG_DM  ( 3231): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/DBG_DM  ( 3231): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3231): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3231): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,I/GFX construct_block_size_descriptor_2d second part( 3934): took 2.719948ms for 0*0 texture 0
,E/BaseAppContext( 2077): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/GFX generate_partition_tables( 3934): took 10.089375ms for 0*0 texture 0
,I/GFX raster( 3934): took 13.617604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89dffb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb89e1588 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3934): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.763489ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89fd820 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d5d390 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4357 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/Zygote  ( 4357): MountEmulatedStorage()
E/Zygote  ( 4357): v2
I/libpersona( 4357): KNOX_SDCARD checking this for 10107
I/libpersona( 4357): KNOX_SDCARD not a persona
I/SELinux ( 4357): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4357): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4357): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3231): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/AMMetaDataParserService( 3934): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,I/DBG_DM  ( 3231): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 3
,I/ActivityManager( 1016): Killing 3526:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{2ae8a662 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.762865ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89fd820 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb89fff68 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,D/EnterpriseController(  279): uids 10012
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10012
W/System.err( 4323): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 4323): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4323): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4323): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 4323): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 4323): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4323): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.791823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89fd820 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb89fff68 counterpartCT=4 counterpartW=96 counterparth=96
,D/GCM     ( 1924): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 4357): TimaSignature is unavailable
,D/ActivityThread( 4357): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3934): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.593281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89fff68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d61058 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     ( 4091): Background sticky concurrent mark sweep GC freed 7886(785KB) AllocSpace objects, 0(0B) LOS objects, 4% free, 18MB/18MB, paused 11.376ms total 31.327ms
,I/AMMetaDataParserService( 3934): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 1.298437ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89fff68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a06818 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3231): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,I/DBG_DM  ( 3231): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/AMMetaDataParserService( 3934): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,I/GCoreUlr( 1924): DispatchingService.onCreate()
,D/SystemUpdateService( 2077): onDestroy
,I/DBG_POLICYDM( 4305): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 4305): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/dex2oat ( 4195): Verification of android.os.IBinder com.google.android.gms.maps.internal.x$a$a.asBinder() took 117.853ms
,W/dex2oat ( 4195): Verification of android.os.IBinder com.google.android.gms.maps.internal.y$a$a.asBinder() took 107.481ms
,I/DBG_DM  ( 3231): [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [3]
,I/DBG_POLICYDM( 4305): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_DM  ( 3231): [com.wssyncmldm.llIIllllIIlllIIIIlll(1140/handleMessage)] 
,I/DBG_DM  ( 3231): [com.wssyncmldm.XDMService(685/llIIlIlIIIllIIIIIllI)] 
,I/DBG_POLICYDM( 4305): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/AuthZen ( 2077): Fetching signing key...
,I/DBG_DM  ( 3231): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,W/dex2oat ( 4195): Verification of com.google.android.gms.maps.model.GroundOverlayOptions com.google.android.gms.maps.model.e.a(android.os.Parcel) took 109.853ms
,I/AuthZen ( 2077): Signing key fetched successfully!
,W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_3526/cgroup.procs: No such file or directory
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 37966(2MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 26MB/40MB, paused 2.509ms total 171.064ms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/BaseAppContext( 2077): Using Auth Proxy for data requests.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
,D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
,I/DBG_POLICYDM( 4305): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,I/GCM     ( 1924): GCM config loaded
,I/DBG_DM  ( 3231): [com.wssyncmldm.ui.XUIFotaPostponeActivity(501/llIIIIlllllIIllIIllI)] 
,I/art     ( 3934): WaitForGcToComplete blocked for 76.443ms for cause HomogeneousSpaceCompact
,I/DBG_DM  ( 3231): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,W/dex2oat ( 4195): Verification of void com.google.maps.api.android.lib6.gmm6.streetview.aa.a(javax.microedition.khronos.opengles.GL10, maps.ei.aq) took 128.614ms
,I/DBG_POLICYDM( 4305): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 4305): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 4305): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_DM  ( 3231): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/art     ( 1924): Explicit concurrent mark sweep GC freed 36329(2MB) AllocSpace objects, 39(816KB) LOS objects, 39% free, 12MB/20MB, paused 56.209ms total 156.610ms
,W/dex2oat ( 4195): Verification of void com.google.android.libraries.appstreaming.framework.g.<init>(com.google.android.libraries.appstreaming.framework.l, java.util.concurrent.ExecutorCompletionService, android.media.MediaCodec, android.view.SurfaceView, com.google.android.libraries.appstreaming.framework.g$a) took 222.072ms
,I/DBG_DM  ( 3231): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
,I/DBG_DM  ( 3231): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3231): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
W/ContextImpl( 3934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3934): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/art     ( 3934): WaitForGcToComplete blocked for 5.832ms for cause DisableMovingGc
,I/DBG_DM  ( 3231): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,W/jxcore-log( 4091): Initializing JXcore engine
W/jxcore-log( 4091): JXcore engine is ready
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 1016): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_POLICYDM( 4305): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!,
I/DBG_POLICYDM( 4305): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,W/ResourcesManager( 1180): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/audit   ( 1958): type=1400 msg=audit(1458035921.676:205): avc:  denied  { ioctl } for  pid=4283 comm="Thread-634" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1958):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1958): type=1300 msg=audit(1458035921.676:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9c24a8f8 items=0 ppid=308 ppcomm=main pid=4283 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-634" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1958): type=1320 msg=audit(1458035921.676:205): 
,E/SMD     (  292): DCD OFF
,W/Auth    ( 1924): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/jxcore-log( 4091): Starting JXcore engine
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3934): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3934): getResourcePackageName:assistant
I/AMMetaDataParserService( 3934): Resource data:2131099648
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3934): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3934): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3934): getResourceTypeNamexml
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.694896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89f65a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89cc7c8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/KnoxNotification( 1180): ----- inflateViews : modified publicViewLocal -----,
,E/Zygote  ( 4396): MountEmulatedStorage()
E/Zygote  ( 4396): v2
,I/libpersona( 4396): KNOX_SDCARD checking this for 10035
I/libpersona( 4396): KNOX_SDCARD not a persona
,I/SELinux ( 4396): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,D/KnoxNotification( 1180): ----- inflateViews : modified KnoxViewLocal -----
,I/SELinux ( 4396): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4396): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4396 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3570:com.fmm.ds/1000 (adj 15): empty #31
V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1924): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/PersonaManager( 1180): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
,W/GCoreFlp( 1924): No location to return for getLastLocation()
,W/FusedLocationProvider( 1924): location=null
,I/PhoneStatusBar( 1180): Icon Only
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,W/dex2oat ( 4195): Verification of void maps.ai.m.a(maps.bi.b, java.util.Map) took 110.578ms
,W/GCoreFlp( 1924): No location to return for getLastLocation()
,W/FusedLocationProvider( 1924): location=null
,D/TimaKeyStoreProvider( 4396): TimaSignature is unavailable
,D/ActivityThread( 4396): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3934): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
W/dex2oat ( 4195): Verification of java.lang.Object maps.bf.a.get() took 132.090ms
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/SQLiteLog( 4047): (284) automatic index on conversation_participants_view(conversation_id),
,I/GFX construct_block_size_descriptor_2d second part( 3934): took 2.779896ms for 0*0 texture 0
,I/GAV2    ( 3851): Thread[GAThread,5,main]: No campaign data found.,
,W/jxcore-log( 4091): Platform android,
W/jxcore-log( 4091): 
W/jxcore-log( 4091): Process ARCH arm
W/jxcore-log( 4091): 
,I/GFX generate_partition_tables( 3934): took 8.923593ms for 0*0 texture 0,
,I/GFX raster( 3934): took 12.878854ms for 96*96 texture 0,
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89e94b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb89e94f0 counterpartCT=4 counterpartW=96 counterparth=96,
,I/AMMetaDataParserService( 3934): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519,
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.664479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8f0c928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8f0ca60 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 4047): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 4047): (284) automatic index on conversation_participants_view(conversation_id)
,I/AMMetaDataParserService( 3934): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3570/cgroup.procs: No such file or directory
,E/SQLiteLog( 4047): (284) automatic index on conversation_participants_view(conversation_id)
,E/SPPClientService( 4396): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4396): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 4396): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,W/dex2oat ( 4195): Verification of maps.bc.a maps.au.a.b() took 107.244ms
,I/DBG_POLICYDM( 4305): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.633073ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8f0eb30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f0ebd8 counterpartCT=4 counterpartW=96 counterparth=96
,D/SPPClientService( 4396): PushLog.txt file is not deleted.
D/SPPClientService( 4396): PushLog.txt file is not deleted.
D/SPPClientService( 4396): ============PushLog. stop!
,I/DBG_POLICYDM( 4305): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4305): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 4305): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 4305): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,E/SQLiteLog( 4047): (284) automatic index on conversation_participants_view(conversation_id)
,W/art     ( 3965): Suspending all threads took: 415.865ms
,W/dex2oat ( 4195): Verification of com.google.android.gms.ads.internal.request.AdResponseParcel maps.ax.c.a(android.content.Context, com.google.android.gms.ads.internal.request.AdRequestInfoParcel, java.lang.String) took 131.689ms
,I/AMMetaDataParserService( 3934): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.624063ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89eb658 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89eb700 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/Zygote  ( 4426): MountEmulatedStorage()
,E/Zygote  ( 4426): v2
,I/libpersona( 4426): KNOX_SDCARD checking this for 10041
I/libpersona( 4426): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4426 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1016): Killing 3595:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,I/SELinux ( 4426): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4426): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4426): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 4305): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,D/TimaKeyStoreProvider( 4426): TimaSignature is unavailable
,D/ActivityThread( 4426): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4305): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/DBG_POLICYDM( 4305): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 4305): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 4305): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 4305): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4305): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4305): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0,
,I/DBG_POLICYDM( 4305): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 4305): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4305): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 4305): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 4305): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4305): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_POLICYDM( 4305): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 4305): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.811460ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89ec9d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89eca78 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/dex2oat ( 4195): Verification of void maps.br.d.a() took 111.766ms
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
,I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:assistant
I/AMMetaDataParserService( 3934): Resource data:2131099648
,I/AMMetaDataParserService( 3934): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3934): getResourceTypeNamexml
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.683490ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89f65a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4305): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
I/AMMetaDataParserService( 3934): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/DBG_POLICYDM( 4305): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/15/10:58:42
,I/DBG_POLICYDM( 4305): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 4305): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 4305): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,W/libprocessgroup( 1016): failed to open /acct/uid_10062/pid_3595/cgroup.procs: No such file or directory
,I/SA      ( 4426): [SSP] onCreated
,I/art     ( 1660): Explicit concurrent mark sweep GC freed 5323(216KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 920us total 1.008s
,I/DBG_POLICYDM( 4305): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,W/SQLiteConnectionPool( 1660): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.629791ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89e94b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/jxcore-log( 4091): JXcore Cordova bridge is ready!
I/jxcore-log( 4091): 
,W/jxcore-log( 4091): JXcore engine is started
,I/AMMetaDataParserService( 3934): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/org.thaliproject.p2p.ThaliPermissions( 4091): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 4091): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,E/jxcore  ( 4091): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4091): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
I/EventLogService( 2077): Aggregate from 1458033502581 (log), 1458033502581 (data)
,I/chromium( 4091): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,I/chromium( 4091): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
D/PersistentNotificationBroadcastReceiver( 1924): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/a       ( 2077): Opening database auth.proximity.permit_store...
I/GCoreUlr( 1924): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/FocusedStackFrame( 1016): Set to : 0
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 4091
D/AuthZenTransactionCache( 2077): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2077): Clearing transaction cache
D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (4794 us)
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3934): took 0.730833ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8f0c928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,W/PluginManager( 4091): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 68ms. Plugin should use CordovaInterface.getThreadPool().,
I/AMMetaDataParserService( 3934): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/DBG_POLICYDM( 4305): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1,
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1016): mDVFSHelper.acquire(),
,V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1016): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1504): onRestart, Launcher: 635258355
,I/DBG_POLICYDM( 4305): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized,
D/Launcher( 1504): onStart, Launcher: 635258355
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/Launcher.HomeView( 1504): onStart,
D/SensorService( 1016): [SO] activate (ident=0xb8e95d40, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0,
,D/Launcher( 1504): onResume, Launcher: 635258355,
I/ActivityManager( 1016): Killing 3624:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
D/SettingsProvider( 1016): name = kids_home_mode
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
,D/SettingsProvider( 1016): selectionArgs: 10007
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
D/Launcher.HomeView( 1504): onResume
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,D/SensorManager( 1016): unregisterListener ::   ,
,I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1016): [SO] changed settle time [0]
D/SensorService( 1016): [SO] setDelay [200000000],
D/SensorService( 1016): [SO] activate (ident=0xb8e95d40, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/SA      ( 4426): [TPM] There is no property file,
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  ,
,I/SA      ( 4426): [SCU] isHaveSA() - false,
D/Launcher( 1504): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0,
,I/SA      ( 4426): [TPM] getModelProperty : null
I/SA      ( 4426): [TPM] getCSCProperty : null
I/SA      ( 4426): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4426): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4426): [DM] TFT FEATURE: false
D/MenuAppsGridFragment( 1504): onResume
D/ActivityManager( 1016): handle home activity for 0
I/WallpaperManagerService( 1016): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1016): post home show event for user 0
D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
D/WallpaperManagerService( 1016):  force update = false; persona id = 0; current user =0; current persona = 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1016): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
,I/GCoreUlr( 1924): Unbound from all location providers,
I/GCoreUlr( 1924): Place inference reporting - stopped
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3934): took 0.651667ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8f0eb30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4426): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0,
I/SA      ( 4426): [DM] init START
,I/SurfaceFlinger(  259): id=12 createSurf (720x1280),1 flag=4, Mauncher,
,D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
,I/AMMetaDataParserService( 3934): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,I/System.out( 3965): INFO:Resource not found:/Common.properties Using default values
,D/InputDispatcher( 1016): Focus entered window: 1504
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1504): log_dcs ThreadedRenderer::initialize entered! 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 4426): [DM] This device is not a Vodafone
,D/StrictMode( 4357): StrictMode policy violation; ~duration=1157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4357): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4357): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4357): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4357): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4357): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4357): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4357): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4357): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4357): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4357): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4357): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4357): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4357): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4357): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4357): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4357): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4357): StrictMode policy violation; ~duration=1075 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4357): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4357): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4357): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4357): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4357): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4357): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4357): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4357): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4357): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4357): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4357): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4357): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4357): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4357): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4357),: 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4357): StrictMode policy violation; ~duration=769 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4357): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4357): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4357): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4357): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4357): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4357): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4357): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4357): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4357): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4357): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4357): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4357): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4357): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4357): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4357): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4357): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4357): StrictMode policy violation; ~duration=768 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4357): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4357): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4357): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4357): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4357): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4357): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4357): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4357): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4357): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4357): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4357): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4357): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4357): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4357): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4357): StrictMode policy violation; ~duration=767 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4357): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4357): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4357): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4357): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4357): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4357): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4357): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4357): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4357): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4357): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4357): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4357): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4357): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4357): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4357): StrictMode policy violation; ~duration=764 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4357): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4357): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4357): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4357): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4357): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4357): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4357): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4357): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4357): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4357): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4357): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4357): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4357): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4357): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4357): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4357): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4357): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4357): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4357): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4357): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4357): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4357): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4357): StrictMode policy violation; ~duration=762 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4357): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4357): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4357): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4357): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4357): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4357): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4357): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4357): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4357): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4357): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4357): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4357): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4357): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4357): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4357): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4357): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4357): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4357): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4357): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4357): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4357): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4357): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4357): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4357): StrictMode policy violation; ~duration=720 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4357): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4357): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4357): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4357): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4357): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4357): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4357): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4357): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4357): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4357): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4357): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4357): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4357): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4357): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4357): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4357): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4357): StrictMode policy violation; ~duration=719 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4357): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4357): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4357): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4357): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4357): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4357): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4357): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4357): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4357): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4357): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4357): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4357): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4357): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4357): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4357): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3624/cgroup.procs: No such file or directory
I/GFX raster( 3934): took 0.705208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89eb658 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
D/Launcher( 1504): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/AMMetaDataParserService( 3934): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
W/dex2oat ( 4195): Verification of java.lang.Object maps.db.ad$1.a(android.os.IInterface) took 116.144ms
W/dex2oat ( 4195): Verification of java.lang.Object maps.db.ad$2.a(android.os.IInterface) took 118.715ms
W/dex2oat ( 4195): Verification of java.util.Map maps.db.ad.a() took 118.279ms
W/IInputConnectionWrapper( 4091): showStatusIcon on inactive InputConnection
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ResourceType( 4426): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
D/SamsungIME( 1902): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
W/ResourceType( 4426): No package identifier when getting value for resource number 0x00000000,
W/ResourceType( 4426): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4426): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4426): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
I/ActivityManager( 1016): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4456 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ResourceType( 4426): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
I/ActivityManager( 1016): Killing 3654:com.wssnps/1000 (adj 15): empty #31
W/ResourceType( 4426): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4426): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4426): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4426): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
E/Zygote  ( 4456): MountEmulatedStorage()
,I/libpersona( 4456): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4456): v2
I/libpersona( 4456): KNOX_SDCARD not a persona
,I/SELinux ( 4456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GCoreUlr( 1924): DispatchingService.onDestroy()
I/GCoreUlr( 1924): Stopping handler for UlrDispSvcFast
,I/art     (  308): Explicit concurrent mark sweep GC freed 8758(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 664us total 31.537ms
,I/SA      ( 4426): [SCU] isHaveSA() - false
I/SA      ( 4426): support phone number id : false
I/SA      ( 4426): [DM] Supports Ref Jpn : true
,I/ActivityManager( 1016): Killing 3363:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,I/SA      ( 4426): [DM] init END
,I/Timeline( 1504): Timeline: Activity_idle id: android.os.BinderProxy@92ad608 time:47857
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 17.077ms
,D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,D/TimaKeyStoreProvider( 4456): TimaSignature is unavailable
D/ActivityThread( 4456): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 703us total 17.335ms
,W/dex2oat ( 4195): Verification of void maps.db.ab.<clinit>() took 238.015ms
W/dex2oat ( 4195): Verification of java.util.Map maps.db.t$c.a(maps.db.t$c, byte[]) took 114.333ms
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/GCoreUlr( 1924): Unbound from all location providers
I/GCoreUlr( 1924): Place inference reporting - stopped
,I/SA      ( 4426): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 4426): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
D/ActivityManager( 1016): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4426): [OR] onReceive END
,I/ActivityManager( 1016): Displayed Component not be shown by security: +361ms
,W/dex2oat ( 4195): Verification of void maps.dc.i.a(android.view.MotionEvent) took 149.360ms
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3934): took 0.839582ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89ec9d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,D/StatusChecker( 4456): onReceive : android.intent.action.BOOT_COMPLETED
I/SA      ( 4426): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4426): [ODM] queryOpenData(key= GEO_IP )
,I/StatusChecker( 4456): onReceive : net.mt.init : DONE,
,I/AMMetaDataParserService( 3934): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524,
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity,
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
,I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:assistant
I/AMMetaDataParserService( 3934): Resource data:2131099648
,D/AndroidRuntime( 4443): ,
D/AndroidRuntime( 4443): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4443): CheckJNI is OFF,
,D/AndroidRuntime( 4443): readGMSProperty: start,
D/AndroidRuntime( 4443): readGMSProperty: already setted!!
,D/AndroidRuntime( 4443): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4443): readGMSProperty: could not set the property(default)!!
,D/AndroidRuntime( 4443): readGMSProperty: end
D/AndroidRuntime( 4443): addProductProperty: start
,D/SensorService( 1016): [SO] currT = 48060085657, prevT = 47610073157, diff = 450012500, [0.134 0.421 10.132],
D/SensorService( 1016): [SO] 0.134 0.421 10.132
D/SensorService( 1016): [SO] [100 -> 255]
,I/AMMetaDataParserService( 3934): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3934): getResourceTypeNamexml
E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/SA      ( 4426): getMccForGalaxyJpn step2 GEO_IP MCC : 260,
I/SA      ( 4426): [LBE] REF_JPN : true
I/SA      ( 4426): [BDC] create
,I/GFX raster( 3934): took 1.000936ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89f65a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7,
W/ActivityManager( 1016): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,I/AMMetaDataParserService( 3934): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
,I/ActivityManager( 1016): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4475 uid=10116 gids={50116, 9997} abi=armeabi-v7a,
,I/ActivityManager( 1016): Killing 3723:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,E/Zygote  ( 4475): MountEmulatedStorage()
I/libpersona( 4475): KNOX_SDCARD checking this for 10116
E/Zygote  ( 4475): v2
I/libpersona( 4475): KNOX_SDCARD not a persona,
,I/SELinux ( 4475): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4475): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4475): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter,
I/SA      ( 4426): [DBMV2] getEmailID
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,I/SA      ( 4426): [DBMV2] getDataV02ForItems,
I/SA      ( 4426): [SSP] query invoked
,I/SA      ( 4426): [SCU] get signed id from samsung account2.0 DB.
,I/DBG_POLICYDM( 4305): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,D/TimaKeyStoreProvider( 4475): TimaSignature is unavailable,
D/ActivityThread( 4475): Added TimaKeyStore provider
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3934): took 0.856875ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89e94b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96,
,I/AMMetaDataParserService( 3934): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519,
I/SA      ( 4426): [SCU] get signed id from samsung account1.0 DB.,
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3654/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10009/pid_3363/cgroup.procs: No such file or directory
,I/SA      ( 4426): [BDC] destroy
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/ActivityManager( 1016): Killing 3708:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,I/GFX raster( 3934): took 0.806459ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8f0c928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/PageBuddyNotiSvc( 4475): Intent received : action=android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3934): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 4475): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/DBG_POLICYDM( 4305): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,I/PageBuddyNotiSvc( 4475): onCreate mCpBitFlag=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/AffinityControl( 4443): AffinityControl: registerfunction enter
,E/Zygote  ( 4500): MountEmulatedStorage(),
,E/Zygote  ( 4500): v2,
,I/libpersona( 4500): KNOX_SDCARD checking this for 10125,
E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/libpersona( 4500): KNOX_SDCARD not a persona
I/GFX raster( 3934): took 0.647917ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8f0eb30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96,
,I/SELinux ( 4500): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4500): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4500): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4500 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/AMMetaDataParserService( 3934): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/AndroidRuntime( 4443): Calling main entry com.android.commands.pm.Pm
,I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{19d03152 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:48313
,W/libprocessgroup( 1016): failed to open /acct/uid_10014/pid_3723/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10094/pid_3708/cgroup.procs: No such file or directory
,D/PackageManager( 1016): START PACKAGE DELETE: observer{965459249}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{2}
,I/SurfaceFlinger(  259): id=11 Removed NainActivit (7/8)
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.654167ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89eb658 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Killing 3759:com.sec.factory.camera/1000 (adj 15): empty #31
,D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
,I/AMMetaDataParserService( 3934): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/SurfaceFlinger(  259): id=11 Removed NainActivit (-2/8),
,D/TimaKeyStoreProvider( 4500): TimaSignature is unavailable
,D/ActivityThread( 4500): Added TimaKeyStore provider
,D/PackageManager( 1016): !@killApplicatoin: 10155, uninstall pkg
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.717761ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89ec9d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,I/ActivityManager( 1016): Killing 4091:com.test.thalitest/u0a155 (adj 9): stop com.test.thalitest cause uninstall pkg
,I/AMMetaDataParserService( 3934): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ResourcesManager( 4500): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4500): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:assistant
I/AMMetaDataParserService( 3934): Resource data:2131099648
,W/ResourcesManager( 4500): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3759/cgroup.procs: No such file or directory
,D/SamsungIME( 1902): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/AMMetaDataParserService( 3934): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3934): getResourceTypeNamexml
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.680521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89f65a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,D/PowerManagerService( 1016): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,I/AMMetaDataParserService( 3934): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/lights  ( 1016): lcd : 51 +
,W/ActivityThread( 4357): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1016): lcd : 51 -
,D/lights  ( 1016): lcd : 19 +,
,I/System.out( 4357): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 4357): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4357): (HTTPLog)-Static: isShipBuild true
I/System.out( 4357): (HTTPLog)-Thread-660-458336196: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4357): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): uids 10107
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10107
,D/lights  ( 1016): lcd : 19 -
,I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/QuickConnect( 4500): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 4500): Util.setSCRunningSetting - [value]0
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.629636ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89e94b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/com.google.a.a.b.d.a( 4357): Application name is not set. Call Builder#setApplicationName.
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.717968ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8f0c928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/System.out( 4357): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.726407ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8f0eb30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.783491ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89eb658 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1924): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 1902): mOCRHelper is null
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.725521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89ec9d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:assistant
I/AMMetaDataParserService( 3934): Resource data:2131099648
,I/AMMetaDataParserService( 3934): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3934): getResourceTypeNamexml
,D/RegisteredComponentCache( 1466): Collect Tech packages for Knox
,D/PersonaManager( 1466): isKioskContainerExistOnDevice
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.845104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89f65a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,D/SettingsProvider( 1016): name = scon_is_running
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10125
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/QuickConnect( 4500): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/QuickConnect( 4500): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/NetworkStats( 1016): removeUidsLocked() for UIDs [10155]
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked(flags=0x3)
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3934): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,V/NetworkStats( 1016): performPollLocked() took 28ms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,I/GFX raster( 3934): took 0.870467ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89e94b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4522): MountEmulatedStorage()
E/Zygote  ( 4522): v2
I/libpersona( 4522): KNOX_SDCARD checking this for 10131
,I/libpersona( 4522): KNOX_SDCARD not a persona
,I/SELinux ( 4522): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1016): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4522 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a,
,I/SELinux ( 4522): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/AMMetaDataParserService( 3934): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519,
E/SELinux ( 4522): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,I/GFX raster( 3934): took 0.866772ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8f0c928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,D/PersonaManager( 1466): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1466): empty dynamic service
,D/TimaKeyStoreProvider( 4522): TimaSignature is unavailable
,D/ActivityThread( 4522): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3934): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1016): no available spell checker services found
,W/ResourcesManager( 4522): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4522): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.795105ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8f0eb30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.846250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89eb658 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.895834ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89ec9d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/RCPManagerService( 1016): PackageReceiver onReceive()
,I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1016): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1016): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1016): DBIntegrity::getInstance - New instance created
,D/OTPFW   ( 1016): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,I/OTPFW   ( 1016): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1016): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10155
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:assistant
I/AMMetaDataParserService( 3934): Resource data:2131099648
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10155
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/AlarmManagerEXT( 1016): com.test.thalitest(10155) is removed.
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 3934): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3934): getResourceTypeNamexml
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/SBrowserFeatureFlag( 4522): initialized in static block : loadCscFeatureValue() succeed! 
,I/GFX raster( 3934): took 0.889479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89f65a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 3934): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ManifestProvider( 4522): onCreate()
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.638698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89e94b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/NetworkSettingsReceiver( 4522): onReceive: android.intent.action.BOOT_COMPLETED
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3934): took 0.631459ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8f0c928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3934): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,E/SBrowserFeatureFlag( 4522): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@25dd45f3
,D/SBrowserFeatureFlag( 4522): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4522): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/Watchdog( 1016): !@Sync 1
,I/GFX raster( 3934): took 0.792604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb8f0eb30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3934): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522,
,I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4543 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/SettingsProvider( 1016): name = audio_safe_volume_state
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3934): took 0.630260ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89eb658 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4543): MountEmulatedStorage(),
E/Zygote  ( 4543): v2
I/libpersona( 4543): KNOX_SDCARD checking this for 10135
,I/libpersona( 4543): KNOX_SDCARD not a persona
,I/SELinux ( 4543): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/AMMetaDataParserService( 3934): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/SELinux ( 4543): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 4543): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TaskPersister( 1016): removeObsoleteFile: deleting file=12_task.xml
,D/TaskPersister( 1016): removeObsoleteFile: deleting file=12_task_thumbnail.png
,I/ActivityManager( 1016): Killing 3792:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 4543): TimaSignature is unavailable
,D/ActivityThread( 4543): Added TimaKeyStore provider
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ResourcesManager( 4543): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4543): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4543): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/dex2oat ( 4195): dex2oat took 6.092s (threads: 4)
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/        ( 3934): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/WallpaperManager( 1504): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1504): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1504): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/GFX raster( 3934): took 0.934322ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3934): Bitmap=0xb89ec9d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a03900 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3934): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/DexOptUtils( 2077): Odex created at:/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex
,D/DexOptUtils( 2077): Set odex to world readable.
D/DexOptUtils( 2077): Renamed odex to /data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.odex
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/Herrevad( 2077): NQAS connected
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
W/ContextImpl( 3934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3934): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3934): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3934): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity,
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/daemonapp( 1306): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 57998(3MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 30MB/45MB, paused 4.755ms total 684.919ms
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1016): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1016): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3792/cgroup.procs: No such file or directory
,D/PackageManager( 1016): delete codoeFile: 
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
D/AASAuninstall( 1016): userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
I/AASA_removePackage( 1016): UID=10155 Target=com.test.thalitest
,D/PackageManager( 1016): result of delete: 1{965459249}
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/AndroidRuntime( 4443): Shutting down VM
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
,I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:assistant
I/AMMetaDataParserService( 3934): Resource data:2131165197
,W/ResourcesManager( 3934): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3934): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3934): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3934): getResourceTypeNamexml
,I/AMMetaDataParserService( 3934): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigService( 1924): onCreate
,I/AMMetaDataParserService( 3934): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3934): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,E/SMD     (  292): DCD OFF
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4570): MountEmulatedStorage()
E/Zygote  ( 4570): v2
I/libpersona( 4570): KNOX_SDCARD checking this for 10139
I/libpersona( 4570): KNOX_SDCARD not a persona
,I/SELinux ( 4570): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4570): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4570): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3934): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
I/ActivityManager( 1016): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4570 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3934): getResourcePackageName:assistant
I/AMMetaDataParserService( 3934): Resource data:2131165197
,I/AMMetaDataParserService( 3934): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3934): getResourceTypeNamexml
,I/AMMetaDataParserService( 3934): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/TimaKeyStoreProvider( 4570): TimaSignature is unavailable
,D/ActivityThread( 4570): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3934): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/art     ( 4443): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/PackageManager( 1016): [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
D/PackageManager( 1016): userId{-1}
D/PackageManager( 1016): andCode{true}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3934): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/ResourcesManager( 4570): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4570): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4570): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4570): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4570): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3934): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3934): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3934): getResourcePackageName:assistant
I/AMMetaDataParserService( 3934): Resource data:2131165197
,I/AMMetaDataParserService( 3934): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3934): getResourceTypeNamexml
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3934): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,E/Zygote  ( 4588): MountEmulatedStorage()
I/libpersona( 4588): KNOX_SDCARD checking this for 10145
E/Zygote  ( 4588): v2
I/libpersona( 4588): KNOX_SDCARD not a persona
I/SELinux ( 4588): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4588 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 4588): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 4588): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 3431:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,I/AMMetaDataParserService( 3934): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/ActivityManager( 1016): Killing 3815:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4588): TimaSignature is unavailable
,D/ActivityThread( 4588): Added TimaKeyStore provider
,E/SQLiteLog( 2077): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 2077): (3850) statement aborts at 43: [INSERT INTO local_reports(ssid,bssid,network_type,package,api,timestamp_millis,version_code,security_type,throughput_bps,latency_micros) VALUES (?,?,?,?,?,?,?,?,?,?)] disk I/O error
,E/SQLiteDatabase( 2077): Error inserting ssid=NG700 bssid=f4:f2:6d:22:99:3e network_type=1 package=com.google.android.apps.maps api=1 timestamp_millis=1458035924878 version_code=909010123 security_type=4 throughput_bps=2535 latency_micros=179624
E/SQLiteDatabase( 2077): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2077): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2077): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 2077): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2077): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2077): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 2077): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 2077): 	at com.google.android.gms.herrevad.services.g.a(:com.google.android.gms:206)
E/SQLiteDatabase( 2077): 	at com.google.android.gms.herrevad.services.g.a(:com.google.android.gms:38)
E/SQLiteDatabase( 2077): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/SQLiteDatabase( 2077): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2077): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2077): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/SQLiteDatabase( 2077): 	at java.lang.Thread.run(Thread.java:818)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/SharedPreferencesImpl( 2077): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/herrevad.xml to backup file /data/data/com.google.android.gms/shared_prefs/herrevad.xml.bak
,I/AMMetaDataParserService( 3934): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,E/SQLiteLog( 3934): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 3934): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 3934): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3934): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3934): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
E/SQLiteDatabase( 3934): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3934): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3934): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3934): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 3934): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 3934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 3934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/ResourcesManager( 4588): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/System.err( 3934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 3934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 3934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 3934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 3934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 3934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/ResourcesManager( 4588): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/System.err( 3934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/ResourcesManager( 4588): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/System.err( 3934,): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/ResourcesManager( 4588): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/System.err( 3934): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/ResourcesManager( 4588): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/System.err( 3934): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
W/System.err( 3934): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
W/System.err( 3934): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87),
W/System.err( 3934): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 3934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3934): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager( 1016): Killing 3836:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,E/SQLiteLog( 1924): (28) failed to open "/data/data/com.google.android.gms/databases/playlog.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 1924): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 1924): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1924): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1924): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 1924): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 1924): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 1924): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 1924): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 1924): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 1924): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 1924): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 1924): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 1924): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 1924): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 1924): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1924): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1924): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/SQLiteDatabase( 1924): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/SQLiteDatabase( 1924): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/SQLiteDatabase( 1924): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1924): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1924): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/SQLiteDatabase( 1924): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 1924): not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 1924): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 1924): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearcutLoggerIntentService( 1924): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/ClearcutLoggerIntentService( 1924): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/ClearcutLoggerIntentService( 1924): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/ClearcutLoggerIntentService( 1924): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/ClearcutLoggerIntentService( 1924): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/ClearcutLoggerIntentService( 1924): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/ClearcutLoggerIntentService( 1924): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/ClearcutLoggerIntentService( 1924): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/ClearcutLoggerIntentService( 1924): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/ClearcutLoggerIntentService( 1924): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/ClearcutLoggerIntentService( 1924): 	at android.content.ContextWrapper.open,OrCreateDatabase(ContextWrapper.java:282)
E/ClearcutLoggerIntentService( 1924): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 1924): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 1924): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/ClearcutLoggerIntentService( 1924): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/ClearcutLoggerIntentService( 1924): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/ClearcutLoggerIntentService( 1924): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1924): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1924): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/ClearcutLoggerIntentService( 1924): 	at java.lang.Thread.run(Thread.java:818)
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId

```
