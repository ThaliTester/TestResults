#### Test 6012434713fea37_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
E/Zygote  ( 4155): MountEmulatedStorage()
E/Zygote  ( 4155): v2
I/SELinux ( 4155): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4155): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
--------- beginning of system
I/libpersona( 4155): KNOX_SDCARD checking this for 10012
I/libpersona( 4155): KNOX_SDCARD not a persona
E/SELinux ( 4155): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=4155 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
D/TimaKeyStoreProvider( 4155): TimaSignature is unavailable
D/ActivityThread( 4155): Added TimaKeyStore provider
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ResourcesManager( 4155): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4155): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 4155): VM with version 2.1.0 has multidex support
I/MultiDex( 4155): install
I/MultiDex( 4155): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 4155): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/Gmail   ( 4135): getAccountsCursor
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1671): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityThread( 4155): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4155): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3555f56d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4155): Installed default security provider GmsCore_OpenSSL
W/GAV2    ( 4135): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 4135): Observing account changes for notifications
I/ActivityManager( 1018): Killing 3352:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
E/Gmail   ( 4135): Error finding the version of the Email provider.....
E/Gmail   ( 4135): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4135): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 4135): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4135): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4135): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4135): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4135): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 4135): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4135): We do not support migrating this version of the Email provider.
I/Gmail   ( 4135): getAccountsCursor
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
V/GLSActivity( 1671): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Zygote  ( 4192): MountEmulatedStorage()
E/Zygote  ( 4192): v2
I/libpersona( 4192): KNOX_SDCARD checking this for 10092
I/libpersona( 4192): KNOX_SDCARD not a persona
E/SMD     (  290): DCD OFF
I/SELinux ( 4192): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=4192 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/SELinux ( 4192): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4192): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3352/cgroup.procs: No such file or directory
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4135): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3b455caf that was originally bound here
E/ActivityThread( 4135): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3b455caf that was originally bound here
E/ActivityThread( 4135): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 4135): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 4135): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 4135): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 4135): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 4135): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4135): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4135): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4135): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4135): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4135): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4135): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4135): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4135): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4135): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 4135): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1018): Unbind failed: could not find connection for android.os.BinderProxy@22d8cf5f
I/art     (  316): Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 25.782ms
D/TimaKeyStoreProvider( 4192): TimaSignature is unavailable
D/ActivityThread( 4192): Added TimaKeyStore provider
I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 18.475ms
I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 17.390ms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1671): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 4135): (283) recovered 63 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
D/AndroidRuntime( 4180): 
D/AndroidRuntime( 4180): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4180): CheckJNI is OFF
D/AndroidRuntime( 4180): readGMSProperty: start
D/AndroidRuntime( 4180): readGMSProperty: already setted!!
D/AndroidRuntime( 4180): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4180): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4180): readGMSProperty: end
D/AndroidRuntime( 4180): addProductProperty: start
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=4211 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 4211): MountEmulatedStorage()
E/Zygote  ( 4211): v2
I/libpersona( 4211): KNOX_SDCARD checking this for 10092
I/DBG_DM  ( 2820): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
I/libpersona( 4211): KNOX_SDCARD not a persona
I/SELinux ( 4211): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4211): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4211): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4211): TimaSignature is unavailable
D/ActivityThread( 4211): Added TimaKeyStore provider
E/File    ( 4135): fail readDirectory() errno=2
I/Gmail   ( 4135): notifyAccountChanged
I/Gmail   ( 4135): getAccountsCursor
I/Gmail   ( 4135): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1671): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
I/Gmail   ( 4135): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4135): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
I/Gmail   ( 4135): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/Gmail   ( 4135): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4135): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4135): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
I/ActivityManager( 1018): Killing 3290:com.google.android.partnersetup/u0a15 (adj 15): empty #31
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/com.dropbox.android.service.DropboxNetworkReceiver( 4192): Setting receiver enabled: false
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1018): Killing 3452:com.android.managedprovisioning/u0a22 (adj 15): empty #31
E/AffinityControl( 4180): AffinityControl: registerfunction enter
E/ActivityThread( 4192): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
D/AndroidRuntime( 4180): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/dbxyzptlk.db300200.aw.h( 4192): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_9807ade0d39f04306c7e28de04204d1f53ae2228_armv7a
D/breakpad( 4192): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
I/dbxyzptlk.db300200.aw.h( 4192): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_b492ffd532b8b6365d97439f842c164c3c90fd4e_armv7a
D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1018): mDVFSHelper.acquire()
I/dbxyzptlk.db300200.aw.h( 4192): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_e16babc055b114839529ea959e1ce06f2a593b63_armv7a
D/FocusedStackFrame( 1018): Set to : 0
D/Launcher.HomeView( 1503): onPause
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1503
D/Launcher( 1503): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/AndroidRuntime( 4180): Shutting down VM
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : -2122120936
W/libprocessgroup( 1018): failed to open /acct/uid_10015/pid_3290/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10022/pid_3452/cgroup.procs: No such file or directory
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=10 createSurf (1x1),1 flag=404, uhalitest
E/Zygote  ( 4242): MountEmulatedStorage()
E/Zygote  ( 4242): v2
I/libpersona( 4242): KNOX_SDCARD checking this for 10174
I/libpersona( 4242): KNOX_SDCARD not a persona
I/SELinux ( 4242): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4242 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4242): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4242): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/ActivityThread( 1503): updateVisibility : ActivityRecord{2a7cc5bb token=android.os.BinderProxy@336158d2 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/Gmail   ( 4135): getAccountsCursor
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1671): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 4242): TimaSignature is unavailable
D/ActivityThread( 4242): Added TimaKeyStore provider
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1503): onStop
V/ActivityThread( 1503): updateVisibility : ActivityRecord{2a7cc5bb token=android.os.BinderProxy@336158d2 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1503): onTrimMemory. Level: 20
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1018): [SO] activate (ident=0xb7fcf5a8, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/SensorManager( 1018): unregisterListener ::   
I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 66000000(ns)
I/libDropboxSync.so( 4192): Setting global terminate handler.
D/SensorService( 1018): [SO] changed settle time [1]
D/SensorService( 1018): [SO] setDelay [66000000]
D/SensorService( 1018): [SO] activate (ident=0xb7fa2cf0, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
I/dbxyzptlk.db300200.aw.h( 4192): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_aa417f8c60b792b71fc3cef90fc4bb8ddba4ea56_armv7a
W/art     ( 4180): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,I/com.dropbox.sync.android.L( 4192): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/WebViewFactory( 4242): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/com.dropbox.sync.android.L( 4192): Removing unclaimed file/directory in cache: "local-dbapp_noauth"
,I/LibraryLoader( 4242): Time to load native libraries: 2 ms (timestamps 4568-4570)
I/LibraryLoader( 4242): Expected native library version number "",actual native library version number ""
,I/com.dropbox.sync.android.bf( 4192): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/3.0.2 DropboxSync/3.1+dev (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,D/SensorService( 1018): [SO] currT = 44591046000, prevT = 44271273000, diff = 319773000, [0.211 0.460 10.190]
,D/SensorService( 1018): [SO] 0.211 0.460 10.190
D/SensorService( 1018): [SO] [100 -> 255]
,W/art     ( 4192): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 4192): Attempt to remove local handle scope entry from IRT, ignoring
,V/WebViewChromiumFactoryProvider( 4242): Binding Chromium to main looper Looper (main, tid 1) {3ad15d30}
,I/LibraryLoader( 4242): Expected native library version number "",actual native library version number ""
,I/chromium( 4242): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/com.dropbox.sync.android.aS( 4192): Created NativeDbappNoAuthClientProvider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.sync.android.DbxSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,I/BrowserStartupController( 4242): Initializing chromium process, singleProcess=true
,W/art     ( 4242): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4242): ApplicationContext is null in ApplicationStatus
,W/chromium( 4242): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,I/System.out( 4192): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 4192): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 4192): (HTTPLog)-Static: isShipBuild true
I/System.out( 4192): (HTTPLog)-Thread-672-914261276: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4192): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10092
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10092
,W/com.dropbox.sync.android.NativeHttp( 4192): GET failed: java.net.UnknownHostException: Unable to resolve host "api.dropbox.com": No address associated with hostname
,W/chromium( 4242): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4242): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 4242): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4242): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4242): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4242): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4242): Local Branch: 
I/Adreno-EGL( 4242): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4242): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4242):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/libDropboxSync.so(status)( 4192): NETWORK: CoreLogger.cpp:82: java.net.UnknownHostException: Unable to resolve host "api.dropbox.com": No address associated with hostname
,I/System.out( 4192): (HTTPLog)-Static: isSBSettingEnabled false
,W/com.dropbox.sync.android.NativeHttp( 4192): GET failed: java.net.UnknownHostException: Unable to resolve host "api.dropbox.com": No address associated with hostname
W/libDropboxSync.so(status)( 4192): NETWORK: CoreLogger.cpp:82: java.net.UnknownHostException: Unable to resolve host "api.dropbox.com": No address associated with hostname
,D/BluetoothAdapter( 4242): 519261029: getState() :  mService = null. Returning STATE_OFF
,I/com.dropbox.sync.android.DbxSyncService( 4192): DbxSyncService starting.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  256): id=8 Removed Mauncher (5/8)
,I/SurfaceFlinger(  256): id=8 Removed Mauncher (-2/8)
,E/Zygote  ( 4294): MountEmulatedStorage()
E/Zygote  ( 4294): v2
,I/libpersona( 4294): KNOX_SDCARD checking this for 10057
I/libpersona( 4294): KNOX_SDCARD not a persona
I/SELinux ( 4294): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4294 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,I/SELinux ( 4294): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4294): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/art     ( 4242): Attempt to remove local handle scope entry from IRT, ignoring,
,I/ActivityManager( 1018): Killing 3478:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,W/AwContents( 4242): onDetachedFromWindow called when already detached. Ignoring
,D/TimaKeyStoreProvider( 4294): TimaSignature is unavailable
,D/ActivityThread( 4294): Added TimaKeyStore provider
D/PhoneWindow( 4242): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 4242): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 4242): CordovaWebView is running on device made by: samsung
,W/art     ( 4242): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4242): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 4242): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
,D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,W/chromium( 4242): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/PhoneWindow( 4242): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 4242): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=11 createSurf (1x1),1 flag=404, NainActivit
W/libprocessgroup( 1018): failed to open /acct/uid_10131/pid_3478/cgroup.procs: No such file or directory
,D/InputDispatcher( 1018): Focus entered window: 4242
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 4242): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 4242): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4242): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 4242): Enabling debug mode 0
,I/DBG_DM  ( 2820): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1189): There is/are notification(s) 
,I/SamsungIME( 1799): getCurrentCandidateView
,I/ActivityManager( 1018): Displayed Component not be shown by security: +770ms
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/CustomFrequencyManagerService( 1018): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 1
,W/ActivityManager( 1018): mDVFSHelper.release()
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{1237806b u0 com.test.thalitest/.MainActivity t236} time:45094
,I/Timeline( 4242): Timeline: Activity_idle id: android.os.BinderProxy@282abedb time:45097
,D/LocationManagerService( 1018): getProviders()=[passive]
,D/SamsungIME( 1799): Dismiss ExpandCandiate
,I/SamsungIME( 1799): getDebugLevel  : 0x4f4c
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4326): MountEmulatedStorage()
E/Zygote  ( 4326): v2
I/libpersona( 4326): KNOX_SDCARD checking this for 10015
I/libpersona( 4326): KNOX_SDCARD not a persona
,I/SELinux ( 4326): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,W/BindingManager( 4242): Cannot call determinedVisibility() - never saw a connection for the pid: 4242,
,I/SELinux ( 4326): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4326): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4326 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,I/SamsungIME( 1799): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1799): KeybaordView init() : load resources
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/TimaKeyStoreProvider( 4326): TimaSignature is unavailable
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityThread( 4326): Added TimaKeyStore provider
,I/SamsungIME( 1799): getCurrentKeyboard
I/SamsungIME( 1799): getTextKeyboard
,D/SamsungIME( 1799): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/SurfaceFlinger(  256): id=10 Removed uhalitest (7/8)
,I/SurfaceFlinger(  256): id=10 Removed uhalitest (-2/8)
,D/JsMessageQueue( 4242): Set native->JS mode to OnlineEventsBridgeMode
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,I/splitIntent( 1018): Queue : backgroundsplit_2 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1018): Killing 3497:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 3078:com.sec.pcw.device/1000 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SIP     ( 1480): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/File    ( 1480): fail readDirectory() errno=2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/KeyguardUpdateMonitor( 1189): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1189): handleBatteryUpdate
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1189): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/SearchBackgroundTaskFac( 4294): Checking for language pack updates
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 207708(13MB) AllocSpace objects, 4(3MB) LOS objects, 33% free, 26MB/40MB, paused 2.693ms total 275.988ms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/VelvetNetworkClient( 4294): Network connection not availble
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1671): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/jxcore_app_log( 4242): JniHelper::setJavaVM(0xb7713450), pthread_self() = -1211659232
,I/GservicesUpdateTask( 4294): Updating Gservices keys
,I/VelvetNetworkClient( 4294): Network connection not availble
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1671): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3497/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3078/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1939): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4242): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4242):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4242):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4242):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4242):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4242): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94fef66 added. We now have 1 listener(s)
,I/VelvetNetworkClient( 4294): Network connection not availble
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4242): setBluetoothMacAddress: 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4242): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4242): setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4242): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4242):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4242):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4242):     - Bluetooth MAC address: 7C:F9:0E:51:18:22
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4242):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4242):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4242):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4242):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4242):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4242):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4242): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdb9bf2 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4242): addListener: New listener added - the number of listeners is now 1
,I/VelvetNetworkClient( 4294): Network connection not availble
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4242): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4242): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4242): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4242): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4242): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4388): MountEmulatedStorage()
E/Zygote  ( 4388): v2
I/libpersona( 4388): KNOX_SDCARD checking this for 10012
I/libpersona( 4388): KNOX_SDCARD not a persona
,I/SELinux ( 4388): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4388 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,I/SELinux ( 4388): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 4388): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/chromium( 4242): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4388): TimaSignature is unavailable
,D/LocationInitializer( 1939): Restart initialization of location
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 4388): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
,I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ResourcesManager( 4388): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4388): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/GCM     ( 1671): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1671): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GmsCoreStatsServiceLauncher( 1939): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/MultiDex( 4388): VM with version 2.1.0 has multidex support
I/MultiDex( 4388): install
I/MultiDex( 4388): VM has multidex support, MultiDex support library is disabled.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/art     ( 4294): Verification of void com.google.o.a.a.a.f.a(com.google.i.a.b) took 122.643ms
,I/DBG_DM  ( 2820): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/JNIHelp ( 4388): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/art     ( 4294): Verification of void com.google.android.apps.gsa.extradex.backgroundtasks.a.g(android.net.Uri) took 171.642ms
,D/LocationInitializer( 1939): Restart initialization of location
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityThread( 4388): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,V/AlarmManager( 1018): waitForAlarm result :4
W/System  ( 4388): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3555f56d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4388): Installed default security provider GmsCore_OpenSSL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1671): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1671): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1671): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1671): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/AuthorizationBluetoothService( 1671): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1671): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1939): Explicit concurrent mark sweep GC freed 25549(1902KB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 10MB/17MB, paused 1.173ms total 71.103ms
,D/GCM     ( 1671): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.voicesearch.logger.EventLoggerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1939): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 4388): callingUid 10012, callindPid: 4388
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 1939): End new media; added: 0, uploading: 0, time: 315 ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1939): Restart initialization of location
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 4294): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,E/MDM     ( 1693): [181] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/StatusBar( 1189): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Search.LoginHelper( 4294): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4294): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4294): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4294): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4294): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4294): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/MDM     ( 1693): [182] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
D/PersonaManager( 1189): isKioskContainerExistOnDevice
,D/PanelView( 1189): There is/are notification(s) 
D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,W/Search.LoginHelper( 4294): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4294): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4294): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4294): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4294): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4294): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,D/PersonaManager( 1189): isKioskContainerExistOnDevice
,D/PanelView( 1189): There is/are notification(s) 
D/PanelView( 1189): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,E/MDM     ( 1693): [183] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = flipboard.app
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4424): MountEmulatedStorage()
E/Zygote  ( 4424): v2
I/libpersona( 4424): KNOX_SDCARD checking this for 10098
I/libpersona( 4424): KNOX_SDCARD not a persona
,I/SELinux ( 4424): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc flipboard.app for broadcast flipboard.app/flipboard.gcm.FlipboardGCMBroadcastReceiver: pid=4424 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4424): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4424): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 4424): TimaSignature is unavailable
,D/ActivityThread( 4424): Added TimaKeyStore provider
,D/PanelView( 1189): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/LibraryLoader( 4294): Time to load native libraries: 6 ms (timestamps 6532-6538)
I/LibraryLoader( 4294): Expected native library version number "",actual native library version number ""
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/Search.LoginHelper( 4294): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4294): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4294): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4294): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4294): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4294): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/Search.LoginHelper( 4294): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4294): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4294): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4294): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4294): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4294): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4294): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4294): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/art     ( 4294): Attempt to remove local handle scope entry from IRT, ignoring
,E/SMD     (  290): DCD OFF
,W/art     ( 4294): Attempt to remove local handle scope entry from IRT, ignoring
,W/RefreshDomainCookieTask( 4294): Search parameters fetch failed: com.google.android.apps.gsa.shared.api.io.GsaIOException: Error code: 262160 | The connection was not attempted due to lack of network connectivity.
,W/RefreshDomainCookieTask( 4294): Search parameters fetch failed
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.android.gms
,I/System.out( 4424): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 4424): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4424): (HTTPLog)-Static: isShipBuild true
I/System.out( 4424): (HTTPLog)-Thread-698-562045721: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4424): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10098
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10098
,E/Fabric  ( 4424): Unknown error while loading Crashlytics settings. Crashes will be cached until settings can be retrieved.
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4424): Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4424): Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2820): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,I/System.out( 4424): Parsed section Cover Stories, private: false
,W/flip    ( 4424): [WARN:2] registerNotification failed: Network not available
,E/SQLiteLog( 1671): (10) POSIX Error : 11 SQLite Error : 3850
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1671): GcmService start Intent { act=com.google.android.c2dm.intent.UNREGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.UNREGISTER
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1671): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,W/jxcore-log( 4242): Initializing JXcore engine
W/jxcore-log( 4242): JXcore engine is ready
,I/WebViewFactory( 4424): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 4424): Time to load native libraries: 4 ms (timestamps 7382-7386)
I/LibraryLoader( 4424): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4424): Binding Chromium to main looper Looper (main, tid 1) {1093ddc9}
I/LibraryLoader( 4424): Expected native library version number "",actual native library version number ""
I/chromium( 4424): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/BrowserStartupController( 4424): Initializing chromium process, singleProcess=true
W/art     ( 4424): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4424): ApplicationContext is null in ApplicationStatus
,W/chromium( 4424): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,E/audit   ( 1851): type=1400 msg=audit(1457574238.020:203): avc:  denied  { ioctl } for  pid=4387 comm="Thread-699" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1851):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1851): type=1300 msg=audit(1457574238.020:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9bf888f8 items=0 ppid=316 ppcomm=main pid=4387 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-699" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1851): type=1320 msg=audit(1457574238.020:203): 
,W/chromium( 4424): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4424): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 4424): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4424): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4424): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4424): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4424): Local Branch: 
I/Adreno-EGL( 4424): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4424): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4424):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/jxcore-log( 4242): Starting JXcore engine
,D/PowerManagerService( 1018): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1018): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 19 -> 19
,D/lights  ( 1018): lcd : 19 +
,D/DisplayPowerController( 1018): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1018): lcd : 19 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1018): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/AudioManagerAndroid( 4424): Requires BLUETOOTH permission
,D/ActivityManager( 1018): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/jxcore-log( 4242): Platform android
W/jxcore-log( 4242): 
,W/jxcore-log( 4242): Process ARCH arm
W/jxcore-log( 4242): 
,I/ActivityManager( 1018): Killing 3412:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4515): MountEmulatedStorage()
E/Zygote  ( 4515): v2
I/libpersona( 4515): KNOX_SDCARD checking this for 1000
I/libpersona( 4515): KNOX_SDCARD not a persona
,I/SELinux ( 4515): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4515): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4515 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 4515): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4515): TimaSignature is unavailable
,D/ActivityThread( 4515): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3412/cgroup.procs: No such file or directory
,E/MTPRx   ( 4515): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1018): mCursor = null
,V/MTPRx   ( 4515): sealedState: false
V/MTPRx   ( 4515): sealedUsbMassStorageState: false
E/MTPRx   ( 4515): check value of boot_completed is1
E/MTPRx   ( 4515): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4515): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4515): Status for mount/Unmount :removed
E/MTPRx   ( 4515): SDcard is not available
,W/MTPRx   ( 4515): value of connected istrue
W/MTPRx   ( 4515): value of configured istrue
W/MTPRx   ( 4515): value of mtpEnabled istrue
W/MTPRx   ( 4515): value of ptpEnabled isfalse
,E/MTPRx   ( 4515): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4515): mFirstTime: false
,D/        ( 4515): MTP: reading debug level property
,E/MTPJNIInterface( 4515): Getting CryptionKey from JAVA
E/MTPRx   ( 4515): currentUserId is 0
,E/MTPRx   ( 4515): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4515): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 4515): is_Privatemode is NOT 1
,D/SettingsProvider( 1018): name = boot_time_connected
,E/MTPRx   ( 4515): Sending NORMAL_BOOT to stack,
E/MTPJNIInterface( 4515): noti = 17
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,D/SecContentProvider( 1018): uri = 18 selection = isUsbMediaPlayerAvailable
E/MTPRx   ( 4515): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1018): name = mtp_running_status
,I/ValidateNoPeople( 1018): mEvictionCount: 0
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,E/MTPRx   ( 4515): else part ... so first time!!!
,E/MTPPlaObsrvr( 4515): inside setContext()
E/MTPPlaObsrvr( 4515):  inside createplafiles
,I/SecKeyguardClockSingleView( 1189): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 4515): playlist count is0
,E/MTPPlaObsrvr( 4515):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4515):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4515): Inside registerContentObserver
,E/MtpAdbObserver( 4515): inside setContext()
,E/MtpAdbObserver( 4515): Inside registerContentObserver
,W/Settings( 4515): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,V/MtpMediaDBManager( 4515): inside deleteAllDB
,D/SettingsProvider( 1018): name = mtp_running_status
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,E/MtpService( 4515): onCreate.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/MtpService( 1241): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 4515): < MTP > Registering BroadCast receiver :::::
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/MtpService( 4515): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/Zygote  ( 4534): MountEmulatedStorage()
E/Zygote  ( 4534): v2
I/libpersona( 4534): KNOX_SDCARD checking this for 1000
I/libpersona( 4534): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4534 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4534): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
E/MtpService( 4515): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
I/SELinux ( 4534): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,V/MtpMediaDBManager( 4515): inside Thread updateDB
W/MTPRx   ( 4515): calling native method
E/MTPJNIInterface( 4515): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 4515): < MTP > Registering BroadCast receiver :::::::
E/SELinux ( 4534): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
E/MTPJNIInterface( 4515): noti = 10
E/MtpService( 4515): onStartCommand.
,E/MtpService( 4515): onStartCommand.,
W/MTPRx   ( 4515): calling native method,
E/MTPRx   ( 4515): Checking the driver time out
E/MTPJNIInterface( 4515): noti = 2,
D/        ( 4515): deleting sockets before message queue initialization
D/        ( 4515): event handler thread is created, so set the flag
,E/MtpMediaDBManager( 4515): count : 27
E/        ( 4515): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4515): Getting media scanner status0
,E/MTPRx   ( 4515): called native method
E/MTPJNIInterface( 4515): setting Media scanner status0
E/MTPJNIInterface( 4515): After setting Media scanner status0
W/MTPRx   ( 4515): notification from stack 1
E/MtpService( 4515): handleMessage. msg= { when=-11ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/MTPJNIInterface( 4515): DeviceName is Thali Test (Galaxy A5)
,E/MtpService( 4515): handleMessage. msg= { when=-12ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,D/TimaKeyStoreProvider( 4534): TimaSignature is unavailable
,D/ActivityThread( 4534): Added TimaKeyStore provider
,W/MtpMediaDBManager( 4515): sending db update complete noti to stack
E/MTPJNIInterface( 4515): noti = 29
,E/MTPJNIInterface( 4515): Status for mount/Unmount :removed
E/MTPJNIInterface( 4515): SDcard is not available
,E/        ( 4515): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 4515): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4515): SDcard is not available
E/SQLiteLog( 4515): (21) API call with NULL database connection pointer
E/SQLiteLog( 4515): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4515): (21) API call with NULL database connection pointer
E/SQLiteLog( 4515): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4515): (21) API call with NULL database connection pointer
E/SQLiteLog( 4515): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4515): (21) API call with NULL database connection pointer
E/SQLiteLog( 4515): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 4515): notification from stack 2
,D/        ( 4515): [mtp_init_device] Library open with 32 bits.
D/        ( 4515): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 4515): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 4515): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,E/        ( 4515):  [sua_support_present:1287] returning false 
D/        ( 4515): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,D/TMNetworkReceiver( 4534): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
D/TMNetworkReceiver( 4534): TMNetworkReceiver.onReceive() Enter
,D/TMNetworkReceiver( 4534): MirrorLink feauture level: using UEvent
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,I/ActivityManager( 1018): Killing 3556:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31

```
