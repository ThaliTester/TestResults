#### Test 58135655812b57f_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.phone
--------- beginning of system
W/ContextImpl( 5149): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
I/ActivityManager( 1016): Killing 4231:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
I/ActivityManager( 1016): Killing 4687:com.google.android.apps.plus/u0a120 (adj 15): empty #32
I/SettingSearchManagerReceiver( 1452): onReceive : com.samsung.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1452): addSearchInfoDB
I/SettingSearchManagerReceiver( 1452): endInsert
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5185): MountEmulatedStorage()
I/libpersona( 5185): KNOX_SDCARD checking this for 10101
E/Zygote  ( 5185): v2
I/libpersona( 5185): KNOX_SDCARD not a persona
I/SELinux ( 5185): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5185 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5185): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5185): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1016): failed to open /acct/uid_10120/pid_4687/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10125/pid_4231/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5185): TimaSignature is unavailable
D/ActivityThread( 5185): Added TimaKeyStore provider
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5185): getAccountsCursor
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5185): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5185): Observing account changes for notifications
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
E/Gmail   ( 5185): Error finding the version of the Email provider.....
E/Gmail   ( 5185): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5185): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 5185): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 5185): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 5185): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5185): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5185): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5185): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5185): We do not support migrating this version of the Email provider.
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/Gmail   ( 5185): getAccountsCursor
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5221): MountEmulatedStorage()
E/Zygote  ( 5221): v2
I/libpersona( 5221): KNOX_SDCARD checking this for 10033
I/libpersona( 5221): KNOX_SDCARD not a persona
I/SELinux ( 5221): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5221): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=5221 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 5221): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 4526:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
D/TimaKeyStoreProvider( 5221): TimaSignature is unavailable
D/ActivityThread( 5221): Added TimaKeyStore provider
W/libprocessgroup( 1016): failed to open /acct/uid_10009/pid_4526/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD OFF
I/art     ( 1016): Explicit concurrent mark sweep GC freed 229984(7MB) AllocSpace objects, 4(64KB) LOS objects, 25% free, 46MB/62MB, paused 3.864ms total 255.379ms
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 5185): (283) recovered 76 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/ResourcesManager( 5221): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5221): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5221): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 5221): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5221): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5221): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5221): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5221): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 5221): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/File    ( 5185): fail readDirectory() errno=2
I/Gmail   ( 5185): notifyAccountChanged
I/Gmail   ( 5185): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5185): getAccountsCursor
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/Gmail   ( 5185): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5185): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5185): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
I/Gmail   ( 5185): getAccountsCursor
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 5236): 
D/AndroidRuntime( 5236): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5236): CheckJNI is OFF
D/AndroidRuntime( 5236): readGMSProperty: start
D/AndroidRuntime( 5236): readGMSProperty: already setted!!
D/AndroidRuntime( 5236): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5236): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5236): readGMSProperty: end
D/AndroidRuntime( 5236): addProductProperty: start
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1016): Killing 4731:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
E/SPPClientService( 3992): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
E/AffinityControl( 5236): AffinityControl: registerfunction enter
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5263): MountEmulatedStorage()
E/Zygote  ( 5263): v2
I/libpersona( 5263): KNOX_SDCARD checking this for 10035
I/libpersona( 5263): KNOX_SDCARD not a persona
I/SELinux ( 5263): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=5263 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup( 1016): failed to open /acct/uid_10062/pid_4731/cgroup.procs: No such file or directory
I/SELinux ( 5263): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/AndroidRuntime( 5236): Calling main entry com.android.commands.am.Am
E/SELinux ( 5263): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
D/AndroidRuntime( 5236): Shutting down VM
D/TimaKeyStoreProvider( 5263): TimaSignature is unavailable
D/ActivityThread( 5263): Added TimaKeyStore provider
E/SPPClientService( 5263): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5263): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 5263): PushLog.txt file is not deleted.
D/SPPClientService( 5263): PushLog.txt file is not deleted.
D/SPPClientService( 5263): ============PushLog. stop!
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5285): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=5285 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5285): v2
I/libpersona( 5285): KNOX_SDCARD checking this for 10035
I/SELinux ( 5285): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5285): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Killing 4029:com.osp.app.signin/u0a41 (adj 15): empty #31
I/SELinux ( 5285): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5285): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5285): TimaSignature is unavailable
D/ActivityThread( 5285): Added TimaKeyStore provider
E/SPPClientService( 5285): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5285): [PushClientApplication] Push log off : This is Ship build version
E/LNoti   ( 5285): [PhoneStatusChangeReceiver] This device doesn't register yet.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
D/SPPClientService( 5285): PushLog.txt file is not deleted.
D/SPPClientService( 5285): PushLog.txt file is not deleted.
D/SPPClientService( 5285): ============PushLog. stop!
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/art     ( 5236): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1016): failed to open /acct/uid_10041/pid_4029/cgroup.procs: No such file or directory
I/ActivityManager( 1016): Killing 4072:com.android.providers.calendar/u0a42 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1767): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1767): No location to return for getLastLocation()
,W/FusedLocationProvider( 1767): location=null,
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10042/pid_4072/cgroup.procs: No such file or directory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/Zygote  ( 5309): MountEmulatedStorage(),
E/Zygote  ( 5309): v2
I/libpersona( 5309): KNOX_SDCARD checking this for 10104
I/libpersona( 5309): KNOX_SDCARD not a persona
,I/SELinux ( 5309): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5309 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,I/SELinux ( 5309): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5309): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/art     (  307): Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 22.416ms
,D/TimaKeyStoreProvider( 5309): TimaSignature is unavailable
,D/ActivityThread( 5309): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 16.922ms,
,W/ResourcesManager( 5309): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 16.744ms
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{bfe7047 u0 com.sec.bcservice/.BroadcastService},
,I/Babel   ( 5309): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5309): MmsConfig.loadMmsSettings
I/Babel   ( 5309): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel   ( 5309): MmsConfig.loadFromDatabase
,E/Babel   ( 5309): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5309): MmsConfig.loadFromResources
,E/Babel   ( 5309): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5309): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 5309): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 5309): App launched.
,W/art     ( 5309): Suspending all threads took: 17.949ms
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  282): getCameraInfo: X
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  282): getCameraInfo: X
,W/ContextImpl( 4780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.sm.base.a.a:307 com.samsung.android.sm.contextagent.ContextAgentReceiver.onReceive:124 android.app.ActivityThread.handleReceiver:3125 
,W/VideoCapabilities( 5309): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5309): Unsupported mime audio/evrc
,W/AudioCapabilities( 5309): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5309): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5309): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5309): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5309): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5309): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5309): Unsupported mime audio/evrc
,W/VideoCapabilities( 5309): Unsupported mime video/wvc1
,W/VideoCapabilities( 5309): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5309): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5309): Unsupported mime video/wvc1
,W/VideoCapabilities( 5309): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5309): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5309): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5309): Unsupported mime video/mp43
,W/VideoCapabilities( 5309): Unsupported mime video/sorenson
,W/VideoCapabilities( 5309): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5309): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/Babel   ( 5309): Creating RTCS
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5338): MountEmulatedStorage()
E/Zygote  ( 5338): v2
I/libpersona( 5338): KNOX_SDCARD checking this for 1000
I/libpersona( 5338): KNOX_SDCARD not a persona
,I/SELinux ( 5338): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5338): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=5338 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/Babel   ( 5309): Destroying RTCS,
I/ActivityManager( 1016): Killing 4270:com.android.calendar/u0a135 (adj 15): empty #31
E/SELinux ( 5338): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5338): TimaSignature is unavailable
,D/ActivityThread( 5338): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 5338): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1016): failed to open /acct/uid_10135/pid_4270/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 5338): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5338): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5338): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 1016): Killing 4393:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/DBG_DM  ( 3093): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5353): MountEmulatedStorage()
E/Zygote  ( 5353): v2
I/libpersona( 5353): KNOX_SDCARD checking this for 10135
I/libpersona( 5353): KNOX_SDCARD not a persona
,I/SELinux ( 5353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5353 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux ( 5353): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 5353): TimaSignature is unavailable
,D/ActivityThread( 5353): Added TimaKeyStore provider
,W/ResourcesManager( 5353): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5353): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
W/ResourcesManager( 5353): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4393/cgroup.procs: No such file or directory
,D/daemonapp( 1297): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/PolicyManagerBroadcastReceiver( 5102): This process will be killed soon.
,I/Process ( 5102): Sending signal. PID: 5102 SIG: 9
,E/Zygote  ( 5374): MountEmulatedStorage()
I/libpersona( 5374): KNOX_SDCARD checking this for 10142
E/Zygote  ( 5374): v2
I/libpersona( 5374): KNOX_SDCARD not a persona
I/SELinux ( 5374): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5374): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5374): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5374 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 4752:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5374): TimaSignature is unavailable
,D/ActivityThread( 5374): Added TimaKeyStore provider
,V/TaskCloserActivity( 5374): TaskCloserActivity enter()
,V/TaskCloserActivity( 5374): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5389): MountEmulatedStorage()
,E/Zygote  ( 5389): v2
I/libpersona( 5389): KNOX_SDCARD checking this for 10042
I/libpersona( 5389): KNOX_SDCARD not a persona
,I/SELinux ( 5389): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5389 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 4796:com.qualcomm.timeservice/1000 (adj 15): empty #31
I/SELinux ( 5389): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5389): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Process com.sec.android.app.wluc (pid 5102)(adj 15) has died(99,1159)
,D/TimaKeyStoreProvider( 5389): TimaSignature is unavailable
,D/ActivityThread( 5389): Added TimaKeyStore provider
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ResourcesManager( 5389): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5389): CalendarProvider2.onCreate() called
,W/libprocessgroup( 1016): failed to open /acct/uid_10157/pid_4752/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4796/cgroup.procs: No such file or directory
,I/art     ( 1016): Background sticky concurrent mark sweep GC freed 149385(5MB) AllocSpace objects, 16(5MB) LOS objects, 12% free, 54MB/62MB, paused 3.989ms total 100.345ms
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5407): MountEmulatedStorage()
E/Zygote  ( 5407): v2
I/libpersona( 5407): KNOX_SDCARD checking this for 1000
I/libpersona( 5407): KNOX_SDCARD not a persona
,I/SELinux ( 5407): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5407 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5407): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5407): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 5389): (284) automatic index on view_events(_id)
,D/TimaKeyStoreProvider( 5407): TimaSignature is unavailable
,D/ActivityThread( 5407): Added TimaKeyStore provider
,E/MTPRx   ( 5407): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1016): mCursor = null
,V/MTPRx   ( 5407): sealedState: false
V/MTPRx   ( 5407): sealedUsbMassStorageState: false
,E/MTPRx   ( 5407): check value of boot_completed is1
E/MTPRx   ( 5407): check booting is completed_sys.boot_completed
,E/MTPRx   ( 5407): Sd-Card path/storage/extSdCard
,D/CalendarAlarmManager( 5389): sys current time:1454948622258
E/MTPRx   ( 5407): Status for mount/Unmount :removed
E/MTPRx   ( 5407): SDcard is not available
,D/CalendarAlarmManager( 5389): reminder amount:0
,W/MTPRx   ( 5407): value of connected istrue
W/MTPRx   ( 5407): value of configured istrue
W/MTPRx   ( 5407): value of mtpEnabled istrue
W/MTPRx   ( 5407): value of ptpEnabled isfalse
,E/MTPRx   ( 5407): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 5407): mFirstTime: false
,D/        ( 5407): MTP: reading debug level property
,E/MTPJNIInterface( 5407): Getting CryptionKey from JAVA
,E/MTPRx   ( 5407): currentUserId is 0
,E/MTPRx   ( 5407): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 5407): cannot open file : /sys/class/android_usb/android0/bcdUSB
,E/MTPRx   ( 5407): is_Privatemode is NOT 1
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,D/SecContentProvider( 1016): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 5407): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,E/MTPRx   ( 5407): else part ... so first time!!!
,E/MTPPlaObsrvr( 5407): inside setContext()
E/MTPPlaObsrvr( 5407):  inside createplafiles
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 5407): playlist count is0
,E/MTPPlaObsrvr( 5407):  inside try branch createplafiles
,E/MTPPlaObsrvr( 5407):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 5407): Inside registerContentObserver
,E/MtpAdbObserver( 5407): inside setContext()
,E/MtpAdbObserver( 5407): Inside registerContentObserver
W/Settings( 5407): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,V/MtpMediaDBManager( 5407): inside deleteAllDB
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,E/MtpService( 5407): onCreate.
,E/MtpService( 5407): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 5407): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 5407): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,D/MtpService( 1222): updating state; isCurrentUser=true, mMtpLocked=false
,V/MtpMediaDBManager( 5407): inside Thread updateDB
,E/MtpService( 5407): onStartCommand.
W/MTPRx   ( 5407): calling native method
E/MTPJNIInterface( 5407): < MTP > Registering BroadCast receiver :::::
E/MtpService( 5407): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 5407): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 5407): noti = 10
E/MtpService( 5407): onStartCommand.
,W/MTPRx   ( 5407): calling native method
E/MTPRx   ( 5407): Checking the driver time out
E/MTPJNIInterface( 5407): noti = 2
D/        ( 5407): deleting sockets before message queue initialization
D/        ( 5407): event handler thread is created, so set the flag
,E/MTPRx   ( 5407): called native method
,E/MtpService( 5407): handleMessage. msg= { when=-3ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 5407): setting Media scanner status0
E/MTPJNIInterface( 5407): After setting Media scanner status0
,W/MTPRx   ( 5407): notification from stack 1
,E/MtpMediaDBManager( 5407): count : 27
,E/        ( 5407): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
,E/MTPJNIInterface( 5407): Getting media scanner status0
,D/MediaScannerReceiver( 1222): action: com.samsung.intent.action.MTP_FILE_SCAN
,E/MTPJNIInterface( 5407): DeviceName is A5-1
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/MtpMediaDBManager( 5407): sending db update complete noti to stack
E/MTPJNIInterface( 5407): noti = 29
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
E/MTPJNIInterface( 5407): Status for mount/Unmount :removed
E/MTPJNIInterface( 5407): SDcard is not available
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/        ( 5407): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,E/        ( 5407): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
E/MTPJNIInterface( 5407): Status for mount/Unmount :removed
E/MTPJNIInterface( 5407): SDcard is not available
E/SQLiteLog( 5407): (21) API call with NULL database connection pointer
E/SQLiteLog( 5407): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5407): (21) API call with NULL database connection pointer
E/SQLiteLog( 5407): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5407): (21) API call with NULL database connection pointer
E/SQLiteLog( 5407): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5407): (21) API call with NULL database connection pointer
E/SQLiteLog( 5407): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 5407): notification from stack 2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/        ( 5407): [mtp_init_device] Library open with 32 bits.
,D/        ( 5407): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 5407): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 5407): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 5407):  [sua_support_present:1287] returning false 
D/        ( 5407): *****Starting mtp_io()
,W/MTPRx   ( 5407): notification from stack 3
,D/        ( 5407): [mtp_start_io] source_thread Creation 
,D/        ( 5407): [mtp_start_io] sink_thread Creation 
D/        ( 5407): [mtp_start_io:376] sink thread created so set th_sink
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1767): callingUid 10012, callindPid: 1767
,I/MusicLeanback( 4517): Conditions not met for autocaching.
I/MusicLeanback( 4517): Stop autocaching.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/MediaScannerService( 1222): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SettingSearch/SearchIntentReceiver( 1313): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1313): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SettingSearch/SearchIntentReceiver( 1313): InitTitleDBThread start --> mDoingInitTitleDB : true
,D/MediaProvider( 1222): savePlaylistTableInBulkDeleter started
,I/SettingSearch/SearchIntentReceiver( 1313): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1313): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,D/MediaProvider( 1222): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1222): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1222): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1222): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1222): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1222): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1222): savePlaylistTableInBulkDeleter finished
,D/MediaScanner( 1222): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/MediaScanner( 1222): processDirectory :  /storage/emulated/0
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/MediaScanner( 1222): Skipping:
D/MediaScanner( 1222): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1222): Skipping:
D/MediaScanner( 1222): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1222): processDirectory :  /storage/extSdCard
W/MediaScanner( 1222): Error opening directory, reason : Permission denied.
W/MediaScanner( 1222): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 1222):  prescan time: 41ms (DB items: 27)
V/MediaScanner( 1222):     scan time: 24ms (Caching mode: true), (makeEntry time: 14ms ~58%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1222): postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1222):    total time: 67ms
V/MediaScanner( 1222): checked files: 10  directories : 17  (I: 0, U: 0)
,E/GmsUtils( 4517): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 4517): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/MTPJNIInterface( 5407): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/MediaScannerService( 1222): !@done scanning volume external
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SettingSearch/SettingsSearchManager( 1313): Infomation -> numtitleinfo : 0 numSearchinfo : 306
,I/iu.UploadsManager( 1937): End new media; added: 0, uploading: 0, time: 135 ms
,I/art     ( 1016): Background sticky concurrent mark sweep GC freed 76331(2MB) AllocSpace objects, 0(0B) LOS objects, 0% free, 62MB/62MB, paused 3.590ms total 123.757ms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SettingSearch/SettingsSearchManager( 1313):  Infomation -> getItem size : 306
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ResourcesManager( 1313): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 1313): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1313): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,E/CscFactoryReceiver( 1452): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1452): Media DB Scanner finished.
D/CscFactoryReceiver( 1452): start service to Set Ringtone
,D/ActivityManager( 1016): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1452): start service to Set Notification
D/ActivityManager( 1016): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1452): start service to Set Alarmtone
,D/ActivityManager( 1016): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/CscUpdateService( 1452): onStart
E/CscUpdateService( 1452): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1452): only ringtone update
,D/CscUpdateService( 1452): onStart
E/CscUpdateService( 1452): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1452): only notification update
,D/CscUpdateService( 1452): onStart
,E/CscUpdateService( 1452): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1452): only alarmtone update
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.indexservice, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/CscParser( 1452): update(): xml file exist
,E/CscParser( 1452): update(): xml file exist
,E/CscParser( 1452): update(): xml file exist
,E/Zygote  ( 5448): MountEmulatedStorage()
E/Zygote  ( 5448): v2
I/libpersona( 5448): KNOX_SDCARD checking this for 10006
I/libpersona( 5448): KNOX_SDCARD not a persona
,I/SELinux ( 5448): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5448): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5448): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/CSCSettings( 1452): Setting Ringtones (type) : 4
,D/CscParser( 1452): AlarmTone: null
W/CSCSettings( 1452): 1. Tag_Str: null
,W/CSCSettings( 1452): Setting Ringtones (type) : 1
D/CscParser( 1452): RingTone: null
W/CSCSettings( 1452): 1. Tag_Str: null
,W/CSCSettings( 1452): Setting Ringtones (type) : 2
D/CscParser( 1452): MessageTone: null
W/CSCSettings( 1452): 1. Tag_Str: null
,I/ActivityManager( 1016): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5448 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5448): TimaSignature is unavailable
D/ActivityThread( 5448): Added TimaKeyStore provider
,I/ThumbnailProvider( 5448): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver( 5448): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5448): [START] processBroadcastIntent ...
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/BroadcastProcessorService( 5448): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 5034): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,I/SystemInfo( 5448): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/art     ( 1016): Background partial concurrent mark sweep GC freed 348327(20MB) AllocSpace objects, 4(5MB) LOS objects, 27% free, 41MB/57MB, paused 5.587ms total 269.405ms
I/BroadcastProcessorService( 5448): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 5448): [START] DocumentService startDocumentService
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,I/DocumentService( 5448): DocumentService onCreate ... service
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,D/GalleryCacheReady( 5034): handleMeidaScanFinish()
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/FaceInterface( 5034): requestFaceScan() is called.
,W/LocalSuggestAlbumData( 5034): query fail: 
,W/LocalSuggestAlbumData( 5034): query fail: 
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/FaceInterface( 5034): startFaceScan() : waiting 5 sec
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5448): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5448): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/BluetoothMediaBrowser( 2623):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,D/BluetoothMediaBrowser( 2623): no now playing list
D/BluetoothMediaBrowser( 2623):  getNowPlayingId now playing id : -1
,E/SystemInfo( 5448): [SIOP LEVEL] : 0
,W/PackageManager( 1016): verifying app can be installed or not
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled
,D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  Checking SIG BL - true
,D/ApplicationPolicy( 1016): isApplicationInstallationEnabled :  enabled true
,I/AASAInstall( 1016): ship mode
,I/DocumentService( 5448): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5448): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files,
,E/SMD     (  287): DCD OFF
,I/MediaStoreImporter( 4517): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,E/File    ( 5448): fail readDirectory() errno=13
E/File    ( 5448): fail readDirectory() errno=13
,I/SystemInfo( 5448): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5448): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 5448): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :39
E/DocumentService( 5448): [THUMBNAIL] Total Time taken for each file :0
E/        ( 5448): [INDEX] Total time taken for each file :0
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/DocumentService( 5448): DocumentService onDestroy start
,I/DocumentService( 5448): DocumentService onDestroy end
,I/DocumentService( 5448): DocumentService cleanupEverything start
,I/IndexParserThreadsManager( 5448): InterruptedException: null
,I/SystemInfo( 5448): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5448): DocumentService cleanupEverything end
,I/Process ( 5448): Sending signal. PID: 5448 SIG: 9
,I/SettingSearch/SearchIntentReceiver( 1313): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1313): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 1313): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/ActivityManager( 1016): Process com.samsung.indexservice (pid 5448)(adj 11) has died(79,1160)
,I/SettingSearch/SearchIntentReceiver( 1313): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1313): LOCALE_CHANGED call search setting db finish!!
,I/CalendarProvider2( 5389): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/FaceInterface( 5034): startFaceScan() : going on
,D/FaceInterface( 5034): startFaceScan() is called.
,I/art     ( 1222): Explicit concurrent mark sweep GC freed 7088(501KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 705us total 24.145ms
,D/ContentApp( 1222): startScan() is called.
,D/FaceValue( 1222): mSleepTime: 800
D/FaceValue( 1222): mMaxThreadNum: 2
,W/FaceValue( 1222): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1222): startScan() is end.
,D/ContentApp( 1222): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1222): isNeedToRestore : start
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/PackageManager( 1016): Existing package
,D/PackageManager( 1016): Renaming /data/app/vmdl2113601122.tmp to /data/app/com.test.thalitest-1
,D/PackageManager( 1016): installNewPackageLI: Package{20cce793 com.test.thalitest}
,I/PackageManager( 1016): scanFileNewer : com.test.thalitest
,I/FaceInterface( 5034): startFaceScan() : going on
,D/FaceInterface( 5034): startFaceScan() is called.
,D/ContentApp( 1222): startScan() is called.
,D/ContentApp( 1222): startScan() is end.
,D/ContentApp( 1222): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1222): isNeedToRestore : start
,I/art     ( 1016): Background partial concurrent mark sweep GC freed 243805(14MB) AllocSpace objects, 4(6MB) LOS objects, 27% free, 41MB/57MB, paused 5.013ms total 216.324ms
,I/art     ( 1016): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     ( 1016): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
D/PackageManager( 1016): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,I/dex2oat ( 5478): ----------------------------------------------------
,I/dex2oat ( 5478): <SS>: S T A R T I N G . . .
I/dex2oat ( 5478): <SS>: going to process manifest for 32-bit...
,I/        ( 5478): SS_ART_lib [I]: Memory allocation: ctx
I/        ( 5478): SS_ART_lib [I]: Memory allocation: manifest_buf
,I/        ( 5478): SS_ART_lib [I]: Parsing Manifest for SS stuff
I/        ( 5478): SS_ART_lib [I]: Memory allocation: ctx->libs
I/        ( 5478): SS_ART_lib [I]: Memory allocation: ctx->package_name
I/        ( 5478): SS_ART_lib [I]: Parsing completed
I/        ( 5478): SS_ART_lib [I]: permission is absent: /data/app/com.test.thalitest-1/base.apk
I/        ( 5478): SS_ART_lib [I]: Closing zip file: /data/app/com.test.thalitest-1/base.apk
I/        ( 5478): SS_ART_lib [I]: access to SS denied
I/        ( 5478): SS_ART_lib [I]: ctx will be cleaned
I/        ( 5478): SS_ART_lib [I]: ctx component will be cleaned: ctx->libs
I/        ( 5478): SS_ART_lib [I]: ctx component is cleaned: ctx->libs
I/        ( 5478): SS_ART_lib [I]: ctx component will be cleaned: ctx->package_name
I/        ( 5478): SS_ART_lib [I]: ctx component is cleaned: ctx->package_name
I/        ( 5478): SS_ART_lib [I]: ctx is cleaned
I/dex2oat ( 5478): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/dex2oat ( 5478): dex2oat took 402.246ms (threads: 4),
I/PackageManager( 1016): do mInstaller.dexopt : 0
D/PackageManager( 1016): Time to dexopt: 0.463 seconds
,W/System.err( 1016): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1016): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 1016): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5140)
W/System.err( 1016): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:19520)
,W/System.err( 1016): 	at com.android.server.pm.PackageManagerService.access$5400(PackageManagerService.java:342)
W/System.err( 1016): 	at com.android.server.pm.PackageManagerService$19.run(PackageManagerService.java:19505)
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
,W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:446)
W/System.err( 1016): 	... 5 more
,I/HarmonyEASService( 1016): Updating for all 1
D/PackageManager( 1016): New package installed
,D/PackageManager( 1016): doPostInstall for uid{10155}
,D/PackageManager( 1016): token 1 to BM for possible restore
,V/BackupManagerService( 1016): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
V/BackupManagerService( 1016): Finishing install immediately
,D/PackageManager( 1016): BM finishing package install for 1
,D/PackageManager( 1016): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 1016): [MSG] MCS_UNBIND
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
,I/PageBuddyNotiSvc( 4215): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1452): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=5487 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 5487): MountEmulatedStorage()
I/libpersona( 5487): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5487): v2
,I/libpersona( 5487): KNOX_SDCARD not a persona
,I/SELinux ( 5487): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5487): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5487): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PackageManager( 1016): [MSG] POST_INSTALL: observer{112906651}
D/PackageManager( 1016):           Handling post-install for 1
D/RegisteredComponentCache( 1439): Collect Tech packages for Knox
,I/ActivityManager( 1016): Killing 4814:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5487): TimaSignature is unavailable
,D/ActivityThread( 5487): Added TimaKeyStore provider
,W/Settings( 1016): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1799): mOCRHelper is null
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1439): empty dynamic service
,D/RegisteredComponentCache( 1439): Collect Tech packages for Knox
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,I/GAV2    ( 5185): Thread[GAThread,5,main]: No campaign data found.
,D/AASAservice-UpdateReceiver( 5487): AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
,I/splitIntent( 1016): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher
I/splitIntent( 1016): other index=7, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher: pid=5507 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,E/Zygote  ( 5507): MountEmulatedStorage()
I/libpersona( 5507): KNOX_SDCARD checking this for 10057
E/Zygote  ( 5507): v2
I/libpersona( 5507): KNOX_SDCARD not a persona
I/SELinux ( 5507): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5507): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5507): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/IntentResolver( 1016): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/RegisteredServicesCache( 1439): empty dynamic service
,D/TimaKeyStoreProvider( 5507): TimaSignature is unavailable
D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,D/ActivityThread( 5507): Added TimaKeyStore provider
,D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService( 1016): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1016): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 33853(2MB) AllocSpace objects, 9(144KB) LOS objects, 27% free, 41MB/57MB, paused 4.935ms total 248.870ms
D/PackageManager( 1016): result of install: 1{112906651}
,I/PackageManager( 1016): Observer no longer exists.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManagerService( 1016): PackageReceiver onReceive()
D/RCPManagerService( 1016): App Installed with packageNAme = com.test.thalitest
,E/RCPManagerService( 1016):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService( 1016):  PackageReceiver onReceive() bundle null
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
,D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/BackupManagerService( 1016): Removing schedule queue dupe of com.test.thalitest
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy( 1016): uID is 10155
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PersonaPolicyManagerService( 1016): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,V/BackupManagerService( 1016): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1016): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3e1773c
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,V/AlarmManagerEXT( 1016): com.test.thalitest(10155) is added to mUserAppList
D/KnoxMUMContainerPolicy( 1016): packageInstalledForExternalStorage com.test.thalitest
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,I/GCoreNlp( 1767): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1016): no available spell checker services found
,I/ActivityManager( 1016): Killing 4831:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/LocationManagerService( 1016): getProviders()=[passive]
,E/Zygote  ( 5529): MountEmulatedStorage()
E/Zygote  ( 5529): v2
I/libpersona( 5529): KNOX_SDCARD checking this for 10015
I/libpersona( 5529): KNOX_SDCARD not a persona
,I/SELinux ( 5529): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5529): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5529): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5529 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
I/CrashAnrDetector( 1016): onPackageAdded : com.test.thalitest,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/TimaKeyStoreProvider( 5529): TimaSignature is unavailable
,D/ActivityThread( 5529): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GCoreNlp( 1767): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/libprocessgroup( 1016): failed to open /acct/uid_10085/pid_4814/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1016): applying state to connected service
D/LocationProviderProxy( 1016): applying state to connected service
,D/LocationProviderProxy( 1016): applying state to connected service
W/libprocessgroup( 1016): failed to open /acct/uid_10094/pid_4831/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Killing 4890:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5309): Creating RTCS
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5552): MountEmulatedStorage()
,I/libpersona( 5552): KNOX_SDCARD checking this for 10032
E/Zygote  ( 5552): v2
I/libpersona( 5552): KNOX_SDCARD not a persona
,I/SELinux ( 5552): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5552): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5552 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 5552): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Babel   ( 5309): Destroying RTCS
,I/ActivityManager( 1016): Killing 4909:com.wsomacp/u0a25 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5552): TimaSignature is unavailable
,D/ActivityThread( 5552): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_4890/cgroup.procs: No such file or directory
,I/FeatureConfig( 5552): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 1016): Killing 4929:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/PackagesMonitor( 5034): PackagesMonitor onReceive :com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 5552): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ResourcesManager( 5552): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 5507): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5552): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5552): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 5552): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 5571): MountEmulatedStorage()
E/Zygote  ( 5571): v2
I/libpersona( 5571): KNOX_SDCARD checking this for 10069
I/libpersona( 5571): KNOX_SDCARD not a persona
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SELinux ( 5571): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5571): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5571): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5571 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
W/libprocessgroup( 1016): failed to open /acct/uid_10025/pid_4909/cgroup.procs: No such file or directory
W/ResourcesManager( 5552): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_10003/pid_4929/cgroup.procs: No such file or directory
,W/ResourcesManager( 5552): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  307): Explicit concurrent mark sweep GC freed 8727(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 19.566ms
,D/TimaKeyStoreProvider( 5571): TimaSignature is unavailable
,D/ActivityThread( 5571): Added TimaKeyStore provider
,W/ResourcesManager( 5552): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{1c603af2 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 17.751ms
,D/FileShare-Server( 5571): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,W/ResourcesManager( 5552): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 606us total 16.764ms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5586): MountEmulatedStorage()
E/Zygote  ( 5586): v2
I/libpersona( 5586): KNOX_SDCARD checking this for 1000
I/libpersona( 5586): KNOX_SDCARD not a persona
W/ResourcesManager( 5552): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/SELinux ( 5586): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5586 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5586): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5586): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/UpdateIcingCorporaServi( 5507): UpdateCorporaTask done [took 120 ms] updated apps [took 120 ms] 
W/ResourcesManager( 5552): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Killing 4944:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5586): TimaSignature is unavailable
,D/ActivityThread( 5586): Added TimaKeyStore provider
,W/GalaxyFinderApplication( 5552): system/finder_cp/cpdata.xml file not found
,W/ResourcesManager( 5586): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5602): MountEmulatedStorage(),
E/Zygote  ( 5602): v2
I/libpersona( 5602): KNOX_SDCARD checking this for 1000
I/SELinux ( 5602): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5602): KNOX_SDCARD not a persona,
I/ActivityManager( 1016): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5602 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5056:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
,I/SELinux ( 5602): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5602): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5602): TimaSignature is unavailable
,D/ActivityThread( 5602): Added TimaKeyStore provider
,D/KnoxSetupWizardDbHelper( 5602): dbMigrationFlag : false
,D/ShortcutReceiver( 5602):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5618): MountEmulatedStorage()
E/Zygote  ( 5618): v2
I/libpersona( 5618): KNOX_SDCARD checking this for 10120
I/libpersona( 5618): KNOX_SDCARD not a persona
,I/SELinux ( 5618): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5618): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5618): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5618 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1016): Killing 4768:com.android.mms/u0a46 (adj 15): empty #31,
,D/TimaKeyStoreProvider( 5618): TimaSignature is unavailable
,D/ActivityThread( 5618): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10107/pid_4944/cgroup.procs: No such file or directory
,W/ResourcesManager( 5618): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CountryDetector( 1016): No listener is left
,W/libprocessgroup( 1016): failed to open /acct/uid_10153/pid_5056/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10046/pid_4768/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5641): MountEmulatedStorage(),
E/Zygote  ( 5641): v2
I/libpersona( 5641): KNOX_SDCARD checking this for 10028
I/libpersona( 5641): KNOX_SDCARD not a persona
I/SELinux ( 5641): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5641 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5641): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5641): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 5119:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5641): TimaSignature is unavailable
,D/ActivityThread( 5641): Added TimaKeyStore provider
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5119/cgroup.procs: No such file or directory
,D/Finsky  ( 5641): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5641): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5641): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5641): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 5641): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5641): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 5641): Skipping gmscore version check
,D/Finsky  ( 5641): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5641): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 1937): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/HomeSyncInstallReceiver( 1439): This pkg do not need BT addr. Do nothing
,I/PackageBroadcastService( 1937): Null package name or gms related package.  Ignoreing.
,I/splitIntent( 1016): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47
,I/splitIntent( 1016): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,I/PackagesMonitor( 5034): PackagesMonitor onReceive :com.test.thalitest
,D/AASAservice-UpdateReceiver( 5487): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
,I/AASAservice-TokenRule( 5487): parseToken()
W/System.err( 5487): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
W/System.err( 5487): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 5487): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 5487): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 5487): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
W/System.err( 5487): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
W/System.err( 5487): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 5487): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/System.err( 5487): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/System.err( 5487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5487): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5487): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 5487): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5487): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5487): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5487): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 5487): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 5487): 	at libcore.io.Posix.open(Native Method)
W/System.err( 5487): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 5487): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 5487): 	... 14 more
E/AASAservice-TokenRule( 5487): parseToken() : TokenFile is null
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/AASAservice-UpdateReceiver( 5487): AASARuleUpdateResult() : Rule file is not exist.
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5684): MountEmulatedStorage()
I/libpersona( 5684): KNOX_SDCARD checking this for 10152
E/Zygote  ( 5684): v2
I/libpersona( 5684): KNOX_SDCARD not a persona
I/SELinux ( 5684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5684 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 5684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5684): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5697): MountEmulatedStorage(),
,D/TimaKeyStoreProvider( 5684): TimaSignature is unavailable
I/ActivityManager( 1016): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=5697 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,E/Zygote  ( 5697): v2
I/libpersona( 5697): KNOX_SDCARD checking this for 10046
W/ActivityManager( 1016): userId = 0, bbcId = -10000
I/libpersona( 5697): KNOX_SDCARD not a persona
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
I/SELinux ( 5697): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityThread( 5684): Added TimaKeyStore provider
,I/SELinux ( 5697): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5697): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5697): TimaSignature is unavailable
,D/ActivityThread( 5697): Added TimaKeyStore provider
,W/ContextImpl( 5149): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,W/ResourcesManager( 5697): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5697): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5697): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5697): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5697): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5697): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/SQLiteLog( 5684): (284) automatic index on shooting_modes(title_id)
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5724): MountEmulatedStorage()
E/Zygote  ( 5724): v2
I/libpersona( 5724): KNOX_SDCARD checking this for 1000
I/libpersona( 5724): KNOX_SDCARD not a persona
,I/SELinux ( 5724): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5724): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5724): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1016): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5724 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,D/Mms/MmsApp( 5697): [start]    onCreate() consume time = 0.0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5736): MountEmulatedStorage()
E/Zygote  ( 5736): v2
I/libpersona( 5736): KNOX_SDCARD checking this for 1000
I/libpersona( 5736): KNOX_SDCARD not a persona
,I/SELinux ( 5736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5736): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5736 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5724): TimaSignature is unavailable,
D/ActivityThread( 5724): Added TimaKeyStore provider
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5751): MountEmulatedStorage()
I/libpersona( 5751): KNOX_SDCARD checking this for 10156
E/Zygote  ( 5751): v2
I/libpersona( 5751): KNOX_SDCARD not a persona
,I/SELinux ( 5751): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5751): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5751): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5751 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 5134:com.samsung.android.app.powersharing/u0a122 (adj 15): empty #31
,I/Icing   ( 1937): Storage manager: low false usage 1.73MB avail 10.16GB capacity 11.68GB
,D/TimaKeyStoreProvider( 5736): TimaSignature is unavailable
,D/ActivityThread( 5736): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 5751): TimaSignature is unavailable
,D/ActivityThread( 5751): Added TimaKeyStore provider
,W/ResourcesManager( 5736): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,I/PCWCLIENTTRACE_LOG( 5724): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5724): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5724): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 5724): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5724): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5724): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5724): [onReceive] - android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/TapandpayWidget:TapandpayAppWidgetProvider( 5751): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5751): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/TapandpayWidget:Utils( 5751): Clear T&P info.
,E/Zygote  ( 5774): MountEmulatedStorage(),
E/Zygote  ( 5774): v2
I/libpersona( 5774): KNOX_SDCARD checking this for 1000
I/libpersona( 5774): KNOX_SDCARD not a persona
I/SELinux ( 5774): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5774): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5774): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=5774 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5751): Widget is not attached.
I/ActivityManager( 1016): Killing 5221:com.sec.android.app.sns3/u0a33 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1016): failed to open /acct/uid_10122/pid_5134/cgroup.procs: No such file or directory
,E/Zygote  ( 5791): MountEmulatedStorage()
E/Zygote  ( 5791): v2
I/libpersona( 5791): KNOX_SDCARD checking this for 10091
I/libpersona( 5791): KNOX_SDCARD not a persona
,I/SELinux ( 5791): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/TimaKeyStoreProvider( 5774): TimaSignature is unavailable,
,D/ActivityThread( 5774): Added TimaKeyStore provider
I/SELinux ( 5791): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5791): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5791 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3992:com.sec.spp.push/u0a35 (adj 15): empty #31
,I/art     (  307): Explicit concurrent mark sweep GC freed 8764(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 653us total 22.560ms
,D/TimaKeyStoreProvider( 5791): TimaSignature is unavailable
D/ActivityThread( 5791): Added TimaKeyStore provider
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
W/art     ( 5697): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 153.559ms
,D/Finsky  ( 5641): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.852ms total 22.135ms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 16.920ms
,I/ActivityManager( 1016): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5806 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,E/Zygote  ( 5806): MountEmulatedStorage()
I/libpersona( 5806): KNOX_SDCARD checking this for 10010
E/Zygote  ( 5806): v2
I/libpersona( 5806): KNOX_SDCARD not a persona
I/SELinux ( 5806): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Killing 5263:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
,I/SELinux ( 5806): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5806): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5806): TimaSignature is unavailable
,D/ActivityThread( 5806): Added TimaKeyStore provider
,W/art     ( 5697): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 105.729ms
,D/Mms/TelephonyPermission( 5697): start operation mode monitor
,I/DBG_POLICYDM( 5774): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,W/ResourcesManager( 5697): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/ArtClassLoader( 5697): init before art
,I/DBG_POLICYDM( 5774): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,D/Mms/TelephonyPermission( 5697): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 5697): isDefault true
D/Mms/MmsApp( 5697): onCreate() com.android.mms
,I/DBG_POLICYDM( 5774): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/DBG_POLICYDM( 5774): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 5774): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 5774): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,W/libprocessgroup( 1016): failed to open /acct/uid_10035/pid_3992/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10033/pid_5221/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10035/pid_5263/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5774): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 5774): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,D/PackageBroadcastService( 1937): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1937): Loading module com.google.android.gms.games from APK com.google.android.play.games
,I/DBG_POLICYDM( 5774): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,D/ChimeraModuleLdr( 1937): Loading module APK com.google.android.play.games
,I/DBG_POLICYDM( 5774): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 5774): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5774): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 5774): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5833): MountEmulatedStorage()
E/Zygote  ( 5833): v2
I/libpersona( 5833): KNOX_SDCARD checking this for 10035
I/SELinux ( 5833): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5833): KNOX_SDCARD not a persona
I/SELinux ( 5833): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5833): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5833 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 5285:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5833): TimaSignature is unavailable
,D/ActivityThread( 5833): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5774): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 5774): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5774): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5774): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,W/libprocessgroup( 1016): failed to open /acct/uid_10035/pid_5285/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5774): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,E/SPPClientService( 5833): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5833): [PushClientApplication] Push log off : This is Ship build version
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5854): MountEmulatedStorage()
I/libpersona( 5854): KNOX_SDCARD checking this for 10038
E/Zygote  ( 5854): v2
I/libpersona( 5854): KNOX_SDCARD not a persona
I/SELinux ( 5854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5854 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 5854): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 5338:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/DBG_POLICYDM( 5774): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,D/TimaKeyStoreProvider( 5854): TimaSignature is unavailable
D/ActivityThread( 5854): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5774): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,D/SPPClientService( 5833): PushLog.txt file is not deleted.
D/SPPClientService( 5833): PushLog.txt file is not deleted.
D/SPPClientService( 5833): ============PushLog. stop!
,I/DBG_POLICYDM( 5774): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5774): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 5774): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,W/ResourcesManager( 5854): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5854): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5774): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5774): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5774): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/02/09/09:35:09
,I/DBG_POLICYDM( 5774): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/02/08/17:23:47
,E/DataBuffer( 1937): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@233f9fce)
I/DBG_POLICYDM( 5774): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5774): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 5774): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5774): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 5774): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5774): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5774): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5338/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5774): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 5774): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5774): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,E/PhotosPlugin( 5791): Loading PhotosPlugin
,D/Mms/MmsApp( 5697): [start]    initCountryIso consume time = 689.697969
,D/CountryDetector( 1016): The first listener is added
,D/Mms/MmsApp( 5697): [end]    initCountryIso consume time = 8.524114
,D/Mms/MmsConfig( 5697): [start]    MmsConfig.init() consume time = 0.178854
,I/DBG_POLICYDM( 5774): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,D/Mms/MmsConfig( 5697): before partial update
,I/DBG_POLICYDM( 5774): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,D/Mms/MmsConfig( 5697): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 5697): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 5697): isAuth is false
,D/Mms/MmsConfig( 5697): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1452): query,matched:2117, calling pid = 5697
,D/TP/MmsSmsProvider( 1452): match 2117:Elapsed time : 1.282 ms
,D/EasySignUpManager_1.0.1( 5697): isAuth is false
,D/EasySignUpManager_1.0.1( 5697): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 5697): mps_code.dat does not exist
,E/CscParser( 5697): customer_path =/system/csc/customer.xml
E/CscParser( 5697): fileName + /system/csc/customer.xml
,E/CscParser( 5697): mps_code.dat does not exist
,E/CscParser( 5697): customer_path =/system/csc/customer.xml
E/CscParser( 5697): fileName + /system/csc/customer.xml
,D/CscParser( 5697): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 5697):  enable multiwindow = true
,E/Mms/MessageUtils( 5697): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5697): updateCountryIso : update country iso info 
D/Mms/ArtClassLoader( 5697): init [DONE] art
,D/Mms/MmsConfig( 5697): [end]    init() consume time = 133.732344
,D/Mms/Contact( 5697): [start]    init() consume time = 0.918906
,D/TP/MmsSmsProvider( 1452): query,matched:13, calling pid = 5697
,D/TP/MmsSmsProvider( 1452): match 13:Elapsed time : 2.325 ms
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 203518(13MB) AllocSpace objects, 4(3MB) LOS objects, 33% free, 27MB/40MB, paused 2.869ms total 195.933ms
I/art     ( 1016): WaitForGcToComplete blocked for 173.863ms for cause HeapTrim
,D/Mms/Contact( 5697): [end]    init consume time = 18.854479
,D/Mms/DraftCache( 5697): [start]    rebuildCache consume time = 20.958334
,V/AlarmManager( 1016): waitForAlarm result :4
,D/TP/MmsSmsProvider( 1452): query,matched:12, calling pid = 5697
,D/TP/MmsSmsProvider( 1452): match 12:Elapsed time : 1.143 ms
,D/Mms/DraftCache( 5697): [end]    rebuildCache consume time = 16.038229
,D/Mms/MethodReflector( 5697): getSubId is called
,D/Mms/TelephonyUtils( 5697): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5697): getTelephonyProperty is called
,D/Mms/DownloadManager( 5697): roaming -> false (slotId = 0)
,D/Mms/DownloadManager( 5697): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5697): auto download without roaming -> true
D/Mms/DownloadManager( 5697): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5697): getSubId is called
,I/DBG_POLICYDM( 5774): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,D/Mms/MethodReflector( 5697): getDefaultSmsSubId is called
,E/Mms/TelephonyUtils( 5697): subID is null or 0 length, so get DefaultSubId!!
,D/Mms/TelephonyUtils( 5697): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 5697): getTelephonyProperty is called
D/Mms/DownloadManager( 5697): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5697): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5697): auto download without roaming -> true
D/Mms/DownloadManager( 5697): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5697): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5697): mAutoDownload ------> true
,D/ComposerPerformance( 5697): 1454948627499 ms / [DONE] Composer constructor
,E/CII     ( 5697): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 5697): ReservationManager()
,I/Mms/ReservationManager( 5697): resetAfterConnected()
,D/TP/MmsSmsProvider( 1452): query,matched:7, calling pid = 5697
,D/TP/MmsSmsProvider( 1452): match 7:Elapsed time : 1.935 ms
,D/Mms/Conversation( 5697): [start]    init() consume time = 69.383958
,D/TP/MmsSmsProvider( 1452): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1452): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1452): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1452): sUpgradeVersion = 0, db.getVersion() = 81
,I/Mms/ReservationManager( 5697): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsSmsProvider( 1452): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1452): need read changed broadcast:false
,D/Mms/Conversation( 5697): [end]    init consume time = 11.893594
,D/Mms/MmsApp( 5697): [end]    onCreate() consume time = 2.706198
,D/Mms/MessagingNotification( 5697): [start]    init() consume time = 0.705677
,D/Mms/MessagingNotification( 5697): [end]    init consume time = 2.341562
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1452): query,matched:0, calling pid = 5697
,D/Mms/SpamFilter( 5697): [start]    SpamFilter fill() begin consume time = 7.33073
D/Mms/Synchronizer( 5697): [start]    doSync consume time = 1.221093
V/TP/MmsSmsProvider( 1452): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1452): match 0:Elapsed time : 1.995 ms
,D/TP/MmsSmsProvider( 1452): update, matched:300, calling pid = 5697
,V/TP/MmsSmsProvider( 1452): syncDBData start
,V/TP/MmsSmsProvider( 1452): syncDBData sms end
D/Mms/DownloadManager( 5697): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 5697): roaming ------> false, mSimSlot = 0
,V/TP/MmsSmsProvider( 1452): syncDBData mms end
V/TP/MmsSmsProvider( 1452): syncDBData end
,D/Mms/MethodReflector( 5697): getSubId is called
D/Mms/TelephonyUtils( 5697): getLongSubId from simSlot 0, return Value = -1
,D/TP/MmsSmsProvider( 1452): query,matched:400, calling pid = 5697
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,D/Mms/Synchronizer( 5697): [end]    doSync consume time = 16.065261
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/Mms/MethodReflector( 5697): getTelephonyProperty is called
D/Mms/DownloadManager( 5697): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5697): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5697): auto download without roaming -> true
D/Mms/DownloadManager( 5697): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5697): mAutoDownload ------> true
,E/Zygote  ( 5883): MountEmulatedStorage()
,E/Zygote  ( 5883): v2
I/libpersona( 5883): KNOX_SDCARD checking this for 10072
I/libpersona( 5883): KNOX_SDCARD not a persona
,I/SELinux ( 5883): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5883): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5883): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5883 uid=10072 gids={50072, 9997} abi=armeabi-v7a,
,D/Mms/SpamFilter( 5697): [end]    SpamFilter fill() finished consume time = 26.065312
,I/DBG_POLICYDM( 5774): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,D/Mms/FreeMessageStatusReceiver( 5697): onReceive, action : android.intent.action.PACKAGE_ADDED
I/DBG_POLICYDM( 5774): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/ActivityManager( 1016): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/DBG_POLICYDM( 5774): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,D/TimaKeyStoreProvider( 5883): TimaSignature is unavailable
,D/ActivityThread( 5883): Added TimaKeyStore provider
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5774): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,E/Zygote  ( 5904): MountEmulatedStorage()
E/Zygote  ( 5904): v2
I/libpersona( 5904): KNOX_SDCARD checking this for 10047
I/libpersona( 5904): KNOX_SDCARD not a persona
,I/SELinux ( 5904): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5904): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5904): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,I/CheckinService( 1937): Done disabling old GoogleServicesFramework version
I/ActivityManager( 1016): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5904 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/ChimeraCfgMgr( 1937): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1937): Module APK com.google.android.play.games already loaded
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ChimeraCfgMgr( 1937): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/TimaKeyStoreProvider( 5904): TimaSignature is unavailable
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5904): Added TimaKeyStore provider
,D/AsyncTaskServiceImpl( 1937): Submit a task: k
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/FreeMessageReceiverService( 5697): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5697): onHandleIntent: ACTION_PACKAGE_ADDED
,W/ResourcesManager( 5904): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 1937): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/ActivityManager( 1016): Killing 5389:com.android.providers.calendar/u0a42 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 5374:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #32
,W/ResourcesManager( 5904): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5904): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 1937): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/BadgeProvider( 5883): onCreate
,D/BadgeProvider( 5883): DatabaseHelper
,D/Mms/MessagingNotification( 5697): checkBadgeCount unreadCount=0 badgeCount=0
,D/k       ( 1937): Processing package: com.test.thalitest
,D/TP/SmsProvider( 1452): query,matched:26, calling pid = 5697
,D/TP/SmsProvider( 1452): match 26:Elapsed time : 1.071 ms
,D/TP/MmsSmsProvider( 1452): query,matched:6, calling pid = 5697
,D/TP/MmsSmsProvider( 1452): match 6:Elapsed time : 0.868 ms
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/GassUtils( 1937): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,D/k       ( 1937): Found info for package com.test.thalitest in db.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10142/pid_5374/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10042/pid_5389/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5927): MountEmulatedStorage()
E/Zygote  ( 5927): v2
I/libpersona( 5927): KNOX_SDCARD checking this for 10025
I/libpersona( 5927): KNOX_SDCARD not a persona
,I/SELinux ( 5927): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5927): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5927): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5927 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,I/SL_DEBUG( 5854): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 5854): isLoggable:: SL_DEBUG_EXIST = false
,I/Icing   ( 1937): updateResources: need to parse f{com.google.android.gms}
,D/TimaKeyStoreProvider( 5927): TimaSignature is unavailable
,D/ActivityThread( 5927): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 5164:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/MyFiles ( 5904): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,W/ResourcesManager( 5927): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/BaseAppContext( 1937): Using Auth Proxy for data requests.
W/BaseAppContext( 1937): Using Auth Proxy for data requests.
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
,I/TactileAssist( 1016): enable value -1
,I/TactileAssist( 1016): internal enable value -1
I/TactileAssist( 1016): intensity value -1
,I/TactileAssist( 1016): saveAppList value true
,W/libprocessgroup( 1016): failed to open /acct/uid_10150/pid_5164/cgroup.procs: No such file or directory
,I/TactileAssist( 1016): List of disabled apps :
,D/PackageManager( 1016): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5946): MountEmulatedStorage()
E/Zygote  ( 5946): v2
I/libpersona( 5946): KNOX_SDCARD checking this for 10053
I/libpersona( 5946): KNOX_SDCARD not a persona
,I/SELinux ( 5946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5946 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a,
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 5946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5946): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 5927): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/Omacp( 5697): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/TimaKeyStoreProvider( 5946): TimaSignature is unavailable
,D/ActivityThread( 5946): Added TimaKeyStore provider
,I/FaceInterface( 5034): startFaceScan() : going on
D/FaceInterface( 5034): startFaceScan() is called.
,D/ContentApp( 1222): startScan() is called.
I/OMACP   ( 5927): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,D/ContentApp( 1222): startScan() is end.
,W/BaseAppContext( 1937): Using Auth Proxy for data requests.
,W/ResourcesManager( 5946): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ContentApp( 1222): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1222): isNeedToRestore : start
,I/OMACP   ( 5927): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 5927): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 5927): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,I/OMACP   ( 5927): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,W/ContextImpl( 5854): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,I/OMACP   ( 5927): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 5927): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 5927): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 5927): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 5927): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 5927): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,D/Compatibility( 5946): onReceive() it will make start service
,I/OMACP   ( 5927): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,I/OMACP   ( 5927): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/Compatibility( 5946): onHandleIntent()
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,D/Compatibility( 5946): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/Compatibility( 5946): found: 2
,I/UpdateIcingCorporaServi( 5507): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/Compatibility( 5946): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5946): skipping ResolveInfo{30c4417f com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5946): considering ResolveInfo{36bec54c com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5946): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5946): enabling receiver ResolveInfo{141f5995 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/PeopleDatabaseHelper( 1937): cleanUpNonGplusAccounts done.
,D/Compatibility( 5946): enabling receiver ResolveInfo{3ce2baaa com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5946): enabling receiver ResolveInfo{ae5769b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/Compatibility( 5946): enabling receiver ResolveInfo{24b8ea38 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5946): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,W/BaseAppContext( 1937): Using Auth Proxy for data requests.
,W/BaseAppContext( 1937): Using Auth Proxy for data requests.
W/BaseAppContext( 1937): Using Auth Proxy for data requests.
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5854): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,W/BaseAppContext( 1937): Using Auth Proxy for data requests.
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,I/UpdateIcingCorporaServi( 5507): UpdateCorporaTask done [took 121 ms] updated apps [took 121 ms] 
,I/ActivityManager( 1016): Killing 5015:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5970 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/Zygote  ( 5970): MountEmulatedStorage()
I/libpersona( 5970): KNOX_SDCARD checking this for 10041
E/Zygote  ( 5970): v2
I/libpersona( 5970): KNOX_SDCARD not a persona
,I/SELinux ( 5970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5970): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5970): TimaSignature is unavailable
,D/ActivityThread( 5970): Added TimaKeyStore provider
,I/Icing   ( 1937): Internal init done: storage state 0
,I/Icing   ( 1937): Post-init done
,I/Icing   ( 1937): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager( 1016): Killing 4517:com.google.android.music:main/u0a111 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10040/pid_5015/cgroup.procs: No such file or directory
,I/SA      ( 5970): [SSP] onCreated
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10111/pid_4517/cgroup.procs: No such file or directory
,W/SQLiteConnectionPool( 1937): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 5970): [TPM] There is no property file
,I/SA      ( 5970): [SCU] isHaveSA() - false
,I/SA      ( 5970): [TPM] getModelProperty : null
,I/SA      ( 5970): [TPM] getCSCProperty : null
,W/GAV2    ( 5791): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SA      ( 5970): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5970): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5970): [DM] TFT FEATURE: false
,I/SA      ( 5970): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 5970): [DM] init START
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 5970): [DM] This device is not a Vodafone
,W/ResourceType( 5970): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 5970): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5970): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 5970): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 5970): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5970): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 5970): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 5970): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 5970): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 5970): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 5970): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5970): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 5970): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5970): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 5970): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5970): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 5970): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 5970): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 5970): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 5970): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5970): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 5970): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5970): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 5970): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5970): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 5970): [SCU] isHaveSA() - false
I/SA      ( 5970): support phone number id : false
I/SA      ( 5970): [DM] Supports Ref Jpn : true
,I/SA      ( 5970): [DM] init END
,I/SA      ( 5970): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5970): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
,I/ActivityManager( 1016): Killing 5185:com.google.android.gm/u0a101 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1016): SIOP:: AP = 390
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1016): failed to open /acct/uid_10101/pid_5185/cgroup.procs: No such file or directory
,E/Zygote  ( 6002): MountEmulatedStorage()
E/Zygote  ( 6002): v2
I/libpersona( 6002): KNOX_SDCARD checking this for 10100
I/libpersona( 6002): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6002 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 6002): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Killing 4848:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31,
,I/SELinux ( 6002): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6002): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,D/TimaKeyStoreProvider( 6002): TimaSignature is unavailable
,D/ActivityThread( 6002): Added TimaKeyStore provider
,W/GAV2    ( 5791): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/libprocessgroup( 1016): failed to open /acct/uid_10134/pid_4848/cgroup.procs: No such file or directory
,D/PackageIntentReceiver( 6002): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 6002): Not GearManger package! 
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6023): MountEmulatedStorage()
,E/Zygote  ( 6023): v2
I/libpersona( 6023): KNOX_SDCARD checking this for 1000
I/libpersona( 6023): KNOX_SDCARD not a persona
,I/SELinux ( 6023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6023 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 6023): TimaSignature is unavailable
,D/ActivityThread( 6023): Added TimaKeyStore provider
,W/AccountFeatureHelper( 5791): Write apps_features disabled false
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6040 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
E/Zygote  ( 6040): MountEmulatedStorage()
E/Zygote  ( 6040): v2
I/libpersona( 6040): KNOX_SDCARD checking this for 1000
I/libpersona( 6040): KNOX_SDCARD not a persona
I/SELinux ( 6040): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Killing 5353:com.android.calendar/u0a135 (adj 15): empty #31
,I/SELinux ( 6040): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6040): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  307): Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 656us total 19.997ms
,D/TimaKeyStoreProvider( 6040): TimaSignature is unavailable
,D/ActivityThread( 6040): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 16.868ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 848us total 17.210ms
,W/libprocessgroup( 1016): failed to open /acct/uid_10135/pid_5353/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1937): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1937): Module APK com.google.android.play.games already loaded
,D/AcmsPackageEventListener( 6040): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 6040): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsService( 6040): Enter Oncreate
,D/AcmsServiceMonitor( 6040): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 6040): creating AcmsCore
,D/AcmsCore( 6040): AcmsCore.getAcmsCore() - Enter
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,D/AcmsCore( 6040): AcmsCore
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsCore( 6040): init
D/AcmsCore( 6040): Looper handler is not null
D/AcmsCore( 6040): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6040): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6040): Incrementing - Counter value: 1
D/AcmsCore( 6040): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 6040): onStartCommand
D/AcmsService( 6040): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6040): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6040): Incrementing - Counter value: 2
D/AcmsService( 6040): Incremented Counter Value : onStartCommand
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/AcmsCertificateMngr( 6040): AcmsCertificateMngr
,D/ActivityThread( 6040): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsRevocationMngr( 6040): AcmsRevocationMngr
,D/AcmsService( 6040): Inside handle Intent
D/AcmsService( 6040): App added - package name: com.test.thalitest
D/AcmsCore( 6040): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6040): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6040): Incrementing - Counter value: 3
D/AcmsCore( 6040): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6040): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6040): Decrementing - Counter value: 2
,W/GAV2    ( 5791): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1016): Killing 5309:com.google.android.talk/u0a104 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10104/pid_5309/cgroup.procs: No such file or directory
,D/SensorService( 1016): [SO] 0.019 0.096 10.132
,E/SMD     (  287): DCD OFF,
,I/Icing   ( 1937): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,I/Mms/MmsApp( 5697):  start initViewCache mms,
D/Mms/ComposeMessageFragment( 5697): [start]    fillCache consume time = 1947.024114
D/Mms/ComposeMessageFragment( 5697): fillCache, easy = false
,D/Icing   ( 1937): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1937): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 5571:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,D/AbsListView( 5697): Get MotionRecognitionManager
,D/MotionRecognitionService( 1016):  ssp status : false
,D/Mms/ComposeMessageFragment( 5697): [end]    fillCache consume time = 86.302448
,W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_5571/cgroup.procs: No such file or directory
,D/Mms/BubbleViewCache( 5697): fillCache bubble = 1
,D/AcmsKeyStoreHelper( 6040):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6040): Key Store exist
I/AcmsKeyStoreHelper( 6040): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6040):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 6040): getKeyStoreForApplication success 
D/AcmsCore( 6040): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
,D/AcmsServiceMonitor( 6040): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6040): Decrementing - Counter value: 1
D/AcmsCore( 6040): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6040): This is NOT a valid MirrorLink app
,D/AcmsCore( 6040): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6040): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6040): Decrementing - Counter value: 0
,D/AcmsServiceMonitor( 6040): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6040): getSvcCounter - Counter value: 0
,D/AcmsService( 6040): Enter onDestroy
I/AcmsService( 6040): cleanUp(): inside service clean up
D/AcmsCore( 6040): AcmsCore: inside DeInit
D/AcmsCore( 6040): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6040): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6040): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6040): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6040): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6040): getSvcCounter - Counter value: 0
,D/AcmsService( 6040): killing acms process
I/Process ( 6040): Sending signal. PID: 6040 SIG: 9
,I/ActivityManager( 1016): Process ACMS.Process (pid 6040)(adj 0) has died(57,1203)
,I/DBG_POLICYDM( 5774): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5774): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5774): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5774): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5774): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5774): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5774): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/iu.UploadsManager( 1937): End new media; added: 0, uploading: 0, time: 59 ms
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 5641): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 30227(1649KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 2.425ms total 136.136ms
,I/System.out( 5641): Thread-969(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5641): Thread-969(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5641): Thread-969(ApacheHTTPLog):isShipBuild true
,I/System.out( 5641): Thread-969(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5641): Thread-969(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028
,I/qtaguid ( 5641): Tagging socket 44 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5641, getuid(): 10028,
,I/qtaguid ( 5641): Tagging socket 48 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5641, getuid(): 10028
,I/qtaguid ( 5641): Untagging socket 44
,I/System.out( 5641): Thread-969 calls detatch()
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5641): Thread-968(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5641): Thread-968(ApacheHTTPLog):isShipBuild true
I/System.out( 5641): Thread-968(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5641): Thread-968(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5641): Untagging socket 44
,I/qtaguid ( 5641): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5641): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5641): untagSocket(44) failed with errno -22
I/System.out( 5641): Thread-968 calls detatch()
,D/Finsky  ( 5641): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{3945710 u0 com.samsung.android.MtpApplication/.MtpService}
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6075 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/Zygote  ( 6075): MountEmulatedStorage()
E/Zygote  ( 6075): v2
I/libpersona( 6075): KNOX_SDCARD checking this for 10012
I/libpersona( 6075): KNOX_SDCARD not a persona
,I/SELinux ( 6075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/SELinux ( 6075): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6075): TimaSignature is unavailable
,I/System.out( 5641): Thread-969(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5641): Thread-969(ApacheHTTPLog):isShipBuild true
I/System.out( 5641): Thread-969(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5641): Thread-969(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/ActivityThread( 6075): Added TimaKeyStore provider
,W/ResourcesManager( 6075): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6075): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6075): VM with version 2.1.0 has multidex support
I/MultiDex( 6075): install
I/MultiDex( 6075): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6075): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 5641): Untagging socket 44
,I/qtaguid ( 5641): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5641): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5641): untagSocket(44) failed with errno -22
I/System.out( 5641): Thread-969 calls detatch()
,W/ActivityThread( 6075): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6075): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@10c4dd9d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6075): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ChimeraCfgMgr( 6075): Reading stored module config
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1767): callingUid 10012, callindPid: 1767
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,E/MDM     ( 1767): [246] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6075): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1767): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1937): Restart initialization of location
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,D/NativeLibraryUtils( 6075): Install completed successfully. count=14 extracted=0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1767): No location to return for getLastLocation()
,W/FusedLocationProvider( 1767): location=null
,D/CAR.SERVICE( 6075): Connecting to CarCallService...
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 6075): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6075): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6075): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6075): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6075): Creating a new PhoneAdapter instance
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6075): setListener: com.google.android.gms.car.dn@4b14510
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6075): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6075): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 6075): Package validated; name: com.android.vending
,V/Finsky  ( 5641): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/PackageManager( 1016): [MSG] MCS_UNBIND
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5641): Thread-968(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5641): Thread-968(ApacheHTTPLog):isShipBuild true
,I/System.out( 5641): Thread-968(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5641): Thread-968(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5641): Untagging socket 44
,I/qtaguid ( 5641): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5641): Untagging socket 44 failed errno=-22
,W/NetworkManagementSocketTagger( 5641): untagSocket(44) failed with errno -22
I/System.out( 5641): Thread-968 calls detatch()
,D/SSRM:n  ( 1016): SIOP:: AP = 340
,W/ResourcesManager( 5641): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5641): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5641): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5641): [1] DailyHygiene.access$600: Logging device features
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1016): waitForAlarm result :4
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5641): [990] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5641): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5641): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/art     ( 1767): Explicit concurrent mark sweep GC freed 40705(2MB) AllocSpace objects, 16(256KB) LOS objects, 40% free, 12MB/21MB, paused 1.142ms total 74.455ms
,V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DeviceConnectionService( 1767): client connected with version: 8296000
,E/DataBuffer( 1767): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@eee760d)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 5641): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5641): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5641): (HTTPLog)-Static: isShipBuild true
I/System.out( 5641): (HTTPLog)-Thread-979-394899616: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 5641): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 5641): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/ActivityManager( 1016): Killing 5034:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 5602:com.sec.knox.foldercontainer/1000 (adj 15): empty #32
,W/libprocessgroup( 1016): failed to open /acct/uid_10044/pid_5034/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5602/cgroup.procs: No such file or directory
,D/SensorService( 1016): [SO] 0.019 0.057 10.075,
,V/AlarmManager( 1016): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/accuweather( 1723): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1723): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1723): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1723): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1723): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 17 24
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/PowerManagerService( 1016): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  ( 1016): lcd : 1 +
,D/lights  ( 1016): lcd : 1 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{3651b8ef u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/CAR.SERVICE( 6075): mConnectedToCar = false, abort
,E/ActivityThread( 6075): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@25ff8ef8 that was originally bound here
E/ActivityThread( 6075): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@25ff8ef8 that was originally bound here
E/ActivityThread( 6075): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6075): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6075): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6075): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6075): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6075): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6075): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6075): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6075): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6075): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6075): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6075): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6075): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6075): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 6075): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6075): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6075): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6075): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6075): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6075): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6075): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6075): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6075): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 6075): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@195d95d3 that was originally bound here
E/ActivityThread( 6075): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@195d95d3 that was originally bound here
E/ActivityThread( 6075): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6075): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6075): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6075): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6075): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6075): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6075): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6075): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6075): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6075): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6075): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6075): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6075): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6075): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6075): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6075): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6075): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6075): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6075): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6075): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6075): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6075): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1016): Unbind failed: could not find connection for android.os.BinderProxy@336de72d
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 1937): getNumBytesRead when not calculated.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8
,E/Watchdog( 1016): !@Sync 2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/PowerManagerService( 1016): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1016): Nap time (uid 1000)...
D/PowerManagerService( 1016): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false),
I/PowerManagerService( 1016): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
I/PowerManagerService( 1016): Going to sleep due to screen timeout (uid 1000)...
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1016): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 1016): SecHardwareInterface.setBatteryADC : false
,V/WindowOrientationListener( 1016): WindowOrientationListener disabled
D/PowerManagerService( 1016): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
,D/SensorService( 1016): [SO] activate (ident=0xb95af340, enabled=0),
D/PowerManagerService( 1016): handleSandman : startDream(true),
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
E/PowerManagerService( 1016): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService( 1016): Sleeping (uid 1000)...
I/SurfaceFlinger(  257): id=12 createSurf (720x1280),-1 flag=20004, DolorFade
D/PowerManagerService( 1016): [s] UserActivityState : 4 -> 0
,D/SensorManager( 1016): unregisterListener ::   
,D/KeyguardViewMediator( 1172): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1172): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1172): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1172): notifyScreenOffLocked
,I/DBG_DM  ( 3093): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,D/PowerManagerService( 1016): Excessive delay in ColorFade : createSurface: 20ms
,I/Adreno-EGL( 1016): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1016): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1016): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1016): Local Branch: 
I/Adreno-EGL( 1016): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1016): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1016):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/KeyguardViewMediator( 1172): timeout : 5000
,V/ActivityThread( 3093): updateVisibility : ActivityRecord{2524f3bc token=android.os.BinderProxy@c8799c3 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/KeyguardViewMediator( 1172): setting alarm to turn off keyguard, seq = 1
D/KeyguardViewMediator( 1172): handleNotifyScreenOff
,D/VolumePanel( 1172): onScreenTurnedOff()
D/VolumePanel( 1172): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF end
,E/SmartFaceService( 1016): onReceive: android.intent.action.SCREEN_ON
,D/SecKeyguardClockSingleView( 1172): onScreenTurnedOff
,W/System.err( 1016): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
,W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
,W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1016): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
,W/System.err( 1016): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1016): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
,W/System.err( 1016): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1016): 	... 10 more
E/SmartFaceService( 1016): fail to set sysfs 1
,D/PowerManagerService( 1016): Excessive delay in ColorFade : createEglContext: 49ms
,D/InputMethodManagerService( 1016): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_ON
,I/StatusBar( 1172): Icon Only
D/PowerManagerService( 1016): Excessive delay in ColorFade : createEglSurface: 18ms
D/PanelView( 1172): There is/are notification(s) 
,E/MotionRecognitionService( 1016):  handler : SCREEN_ON end
,D/PermissionCache(  257): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (311 us)
,D/NotificationService( 1016): ACTION_SCREEN_ON
,D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
,D/PowerManagerService( 1016): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 20ms
,E/WifiNative-wlan0( 1016): do suspend false
,I/wpa_supplicant( 2084): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2084): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2084): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2084): Scan requested (ret=0) - scan timeout 30 seconds
,D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1016): Bridge Server is not available
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1016): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1439): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/NfcService( 1439): call the applyRouting
,D/accuweather( 1723): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
,D/ActivityManager( 1016): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/PowerManagerService( 1016): Excessive delay in ColorFade : initGLShaders: 36ms
,D/PowerManagerService( 1016): Excessive delay in ColorFade prepare: 151ms
,D/DisplayPowerController( 1016): ColorFade: onAnimationStart
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
,I/SamsungIME( 1799): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1016): SIOP:: AP = 330,
,D/LightsService( 1016): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1016) 
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1016): turn on LED for fully charged
,D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1016): write_int failed to open -1
,D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SmartFaceService( 1016): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1016): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
,W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1016): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1016): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1016): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.Posix.open(Native Method)
E/SmartFaceService( 1016): fail to set sysfs 0
W/System.err( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1016): 	... 10 more
,I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
,D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1016):  handler : SCREEN_OFF end 
,D/daemonapp( 1297): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1297): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1297): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SamsungIME( 1799): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/NotificationService( 1016): ACTION_SCREEN_OFF
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/daemonapp( 1297): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
,V/voice   (  282): voice_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
,D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
,D/daemonapp( 1297): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1297): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1297): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1297): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1297): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
I/BackgroundCompactionService( 1016): Schedule Type1 BGCompaction
D/comsamsunglog( 1297): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1297): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1297): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1297): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1297): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1297): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1454970180000
,D/daemonapp( 1297): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1454948646492
,D/daemonapp( 1297): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1297): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1016): Bridge Server is not available
,D/daemonapp( 1297): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1297): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1297): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/daemonapp( 1297): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/PersonaManagerService( 1016): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_OFF called
,E/daemonapp( 1297): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1415): [EmergencyStateReceiver] binteractive [false] why[3]
,I/BatteryStatsDumper( 1016): In refreshStats isReason Screen ON/OFF: true
,E/WifiNative-wlan0( 1016): do suspend true
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,D/NfcService( 1439): call the applyRouting
,D/accuweather( 1723): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1723): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1723): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,I/BatteryStatsDumper( 1016): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1016): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1016): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1016): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1016): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1016): Previous Battery Level: 0 Current Level: 100 Delta: -100
,D/daemonapp( 1297): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/DisplayPowerState( 1016): !@ ColorFade entry
,D/DisplayPowerController( 1016): ColorFade: onAnimationEnd
,D/accuweather( 1723): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1723): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1723): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
D/lights  ( 1016): lcd : 0 +
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1297): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/lights  ( 1016): lcd : 0 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1016): Got set_interactive hint
,D/DisplayManagerService( 1016): !@display_state: ON -> OFF
,D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb7381690
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 0 on display: 0
I/DisplayManagerService( 1016): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SSRM:n  ( 1016): SIOP:: AP = 330
,V/ActivityManager( 1016): Display changed displayId=0
,E/LibSecureUISvc( 1963): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/daemonapp( 1297): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Broadcasts
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1723): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1723): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1723): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1723): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1723): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 0 on display 0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl( 1016): Excessive delay in setPowerMode(): 258ms
,D/PowerManagerService( 1016): Excessive delay in !@display_state: OFF: 261ms
,I/libsuspend( 1016): !@autosuspend_wakeup_count_enable
,I/libsuspend( 1016): !@autosuspend_wakeup_count_enable done
,I/PowerManagerService( 1016): [PWL] Off : 0s ago
,I/PowerManagerService( 1016): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1016): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1016, ws=null) (elapsedTime=384)
,D/PowerManagerService( 1016): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 282ms
,I/BatteryStatsDumper( 1016): Writing to database completed
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:a  ( 1016): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1016): SettingsAirViewInfo:: 000000000
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/wpa_supplicant( 2084): nl80211: Received scan results (3 BSSes),
,D/WifiP2pService( 1016): InactiveState{ what=147461 }
D/WifiP2pService( 1016): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1016): DefaultState{ what=147461 }
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5,
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardViewMediator( 1172): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1172): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1172): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1016): [PWL] Off : 5s ago
,V/AlarmManager( 1016): waitForAlarm result :4,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/SMD     (  287): DCD OFF
,D/Finsky  ( 5641): [981] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5641): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8,
,I/PowerManagerService( 1016): [PWL] Off : 15s ago
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 3,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1016): waitForAlarm result :4,
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1016): onStart. jobID=801
,I/BackgroundCompactionService( 1016): onStart done. jobID=801
,I/BackgroundCompactionService( 1016): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1016): compact_memory command done
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,I/PowerManagerService( 1016): [PWL] Off : 30s ago,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1767): Vacuum at: now=1454948681214 tag=VacuumService
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1767): Scheduling Phenotype for one-off execution 9499 seconds from now (1454948681707)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1767): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1767): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1767): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1767): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1767): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1767): (HTTPLog)-Static: isShipBuild true
I/System.out( 1767): (HTTPLog)-Thread-252-629903961: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 1767): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1767): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1767): Tagging socket 82 with tag 1000120100000000{268440065,0} for uid -1, pid: 1767, getuid(): 10012
,I/qtaguid ( 1767): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1767, getuid(): 10012
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1767): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1767): Tagging socket 82 with tag 1000120100000000{268440065,0} for uid -1, pid: 1767, getuid(): 10012
,D/FactoryTest( 5407): Not factory mode
,D/FactoryTest( 5407): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5407): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5407): still no open session command from host, so toast
,W/ContextImpl( 5407): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5407): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5407): Timeline: Activity_launch_request id:com.android.settings time:114863
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
,I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1016): mDVFSHelper.acquire()
,V/ActivityManager( 1016): Display changed displayId=0
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 3093
,E/MTPRx   ( 5407): started activity for popup
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5407): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5407): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5407): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5407): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5407): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5407): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5407): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/InputDispatcher( 1016): Focused application set to: xxxx
,D/InputDispatcher( 1016): Focus entered window: 3093
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1016): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3c765a27 attribute=android.view.inputmethod.EditorInfo@2f0674d4, token = android.os.BinderProxy@1956d068
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SamsungIME( 1799): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1767): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1767): Tagging socket 82 with tag 1000120100000000{268440065,0} for uid -1, pid: 1767, getuid(): 10012
,D/SettingsReceiverActivity( 5407): dev.kiessupport is : TRUE
,D/PhoneWindow( 5407): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5407): *FMB* installDecor flags : 8388610
,I/DBG_DM  ( 3093): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 30
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/System.out( 1767): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1767): Tagging socket 82 with tag 1000120100000000{268440065,0} for uid -1, pid: 1767, getuid(): 10012
,I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3093): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 30
,I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3093): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3093): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 30
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3093): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3093): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3093): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,I/DBG_DM  ( 3093): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/Timeline( 3093): Timeline: Activity_idle id: android.os.BinderProxy@c8799c3 time:115108
,V/ActivityThread( 3093): updateVisibility : ActivityRecord{2524f3bc token=android.os.BinderProxy@c8799c3 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ActivityManager( 1016): mDVFSHelper.release(),
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,D/TaskPersister( 1016): removeObsoleteFile: deleting file=7_task.xml,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/SSRM:n  ( 1016): SIOP:: AP = 270,
,I/PowerManagerService( 1016): [PWL] Off : 50s ago,
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 4
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 75s ago,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged,
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 5
,I/ClearcutLoggerApiImpl( 1767): disconnect managed GoogleApiClient,
,D/SSRM:n  ( 1016): SIOP:: AP = 270,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1016): [PWL] Off : 105s ago
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1016): !@Sync 6
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/Watchdog( 1016): !@Sync 7
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4,
,V/AlarmManager( 1016): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1016): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,V/AlarmManagerEXT( 1016): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1937): Aggregate from 1454947015567 (log), 1454947015567 (data)
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1016): waitForAlarm result :8
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1016): !@Sync 8
,I/PowerManagerService( 1016): [PWL] Off : 180s ago,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1016): !@Sync 9
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 225s ago,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/TLC_TIMA_PKM_initialize( 1016): initializing...
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
I/TLC_TIMA_PKM_initialize( 1016): root = /firmware/image, root_strlen = 15
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
I/TLC_TIMA_PKM_initialize( 1016): process = tima_pkm, process_strlen = 8
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_pkm, process_strlen = 8,
I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1016): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1016): Trustlet response is completed
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1016): !@Sync 10
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 11
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/PowerManagerService( 1016): [PWL] Off : 275s ago,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 12
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 13
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1016): [PWL] Off : 330s ago,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8,
V/AlarmManager( 1016): No more alarm at this time.nowELAPSED=432386 batch.start=797716
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 14
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 15
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1016): [PWL] Off : 390s ago,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/bootchecker(  313): bootchecker wake up!!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 16
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 17
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/PowerManagerService( 1016): [PWL] Off : 455s ago,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 18
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/Atfwd_Daemon(  316): Stop the daemon....
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 19
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 525s ago,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 20,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 21
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 22,
,I/PowerManagerService( 1016): [PWL] Off : 600s ago,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 23,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 24,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 680s ago,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 25,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8,
,E/Watchdog( 1016): !@Sync 26,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10,
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2623): Disconnected process message: 10
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 27,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged,
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 765s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 28,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 29,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 30,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1016): [PWL] Off : 855s ago
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 31
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,V/AlarmManager( 1016): waitForAlarm result :8,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 32
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 33
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 950s ago,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 34
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 35
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 36
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1016): !@Sync 37
,I/PowerManagerService( 1016): [PWL] Off : 1050s ago,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 38
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 39,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1016): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1016): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1016): Updating Usage Statistics in DB @ 1454949783266
,I/ApplicationPolicy( 1016): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1016): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1016): ::isTableExists: Table exists 
,I/ApplicationUsage( 1016): Done Updating Usage Statistics in DB @ 1454949783623
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 40,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1016): [PWL] Off : 1155s ago,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1016): !@Sync 41,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6628): 
D/AndroidRuntime( 6628): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6628): CheckJNI is OFF
D/AndroidRuntime( 6628): readGMSProperty: start
D/AndroidRuntime( 6628): readGMSProperty: already setted!!
D/AndroidRuntime( 6628): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6628): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6628): readGMSProperty: end
D/AndroidRuntime( 6628): addProductProperty: start
E/AffinityControl( 6628): AffinityControl: registerfunction enter
D/SSRM:n  ( 1016): SIOP:: AP = 260
D/AndroidRuntime( 6628): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1016): START PACKAGE DELETE: observer{959795635}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1016): !@killApplicatoin: 10155, uninstall pkg
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
I/art     ( 4780): Explicit concurrent mark sweep GC freed 15318(823KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 695us total 33.175ms
I/art     ( 4998): Explicit concurrent mark sweep GC freed 2384(135KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 689us total 27.659ms
I/art     ( 5507): Explicit concurrent mark sweep GC freed 353(25KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 730us total 35.068ms
I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1767): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1799): mOCRHelper is null
I/art     ( 1937): Explicit concurrent mark sweep GC freed 5080(338KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 14MB/18MB, paused 1.306ms total 81.675ms
I/KLMS-2.5.183: ( 3535): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Feb 08 17:43:51 GMT+01:00 2016
D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/RegisteredComponentCache( 1439): Collect Tech packages for Knox
D/PersonaManager( 1439): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3535): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1016): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1016): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6643): MountEmulatedStorage()
E/Zygote  ( 6643): v2
I/libpersona( 6643): KNOX_SDCARD checking this for 10094
I/libpersona( 6643): KNOX_SDCARD not a persona
I/KLMS-2.5.183: ( 3535): KLMSIntentService(): onCreate()
I/SELinux ( 6643): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6643): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6643): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6643 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3535): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.183: ( 3535): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3535): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.183: ( 3535): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3535): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3535): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
E/Zygote  ( 6654): MountEmulatedStorage()
I/libpersona( 6654): KNOX_SDCARD checking this for 10044
E/Zygote  ( 6654): v2
I/libpersona( 6654): KNOX_SDCARD not a persona
I/SELinux ( 6654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/RCPManagerService( 1016): PackageReceiver onReceive()
I/ActivityManager( 1016): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6654 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/SELinux ( 6654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6654): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
D/PersonaManager( 1439): isKioskContainerExistOnDevice
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1016): PackageRemovalReceiver::onReceive Enter
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6643): TimaSignature is unavailable
D/OTPFW   ( 1016): OtpDbHelper::getInstance New instance created
D/ActivityThread( 6643): Added TimaKeyStore provider
D/OTPFW   ( 1016): DBIntegrity::getInstance - New instance created
D/TimaKeyStoreProvider( 6654): TimaSignature is unavailable
D/ActivityThread( 6654): Added TimaKeyStore provider
D/OTPFW   ( 1016): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
E/Zygote  ( 6674): MountEmulatedStorage()
E/Zygote  ( 6674): v2
I/libpersona( 6674): KNOX_SDCARD checking this for 10149
I/libpersona( 6674): KNOX_SDCARD not a persona
I/SELinux ( 6674): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/OTPFW   ( 1016): ProvisionData::getAllEntries Enter
I/ActivityManager( 1016): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6674 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/RegisteredServicesCache( 1439): empty dynamic service
E/OTPFW   ( 1016): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10155
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
I/SELinux ( 6674): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6674): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/AlarmManagerEXT( 1016): com.test.thalitest(10155) is removed.
V/EnterpriseBillingPolicy( 1016): uID is 10155
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
D/TimaKeyStoreProvider( 6674): TimaSignature is unavailable
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
D/ActivityThread( 6674): Added TimaKeyStore provider
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
E/SQLiteLog( 4780): (284) automatic index on crash_info_summary(package_name_touched)
D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
W/ResourcesManager( 6654): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6654): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6654): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6654): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6654): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6654): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6654): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6654): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/KLMS-2.5.183: ( 3535): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.183: ( 3535): KLMSIntentService(): onDestroy()
D/elm:15183( 6643): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 6643): ELMEngine.ELMEngine( context ).
D/elm:15183( 6643): MDMBridge.setEnterpriseBridge()
D/ThemeInfoUtil( 6674): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6674): isCurrentFestival = false
I/art     ( 4780): Explicit concurrent mark sweep GC freed 1124(55KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 779us total 75.268ms
D/ActivityManager( 1016): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/BadgeProvider( 5883): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5883): sendNotify, [notify] : null
D/BadgeProvider( 5883): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5883): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5883): update, [UpdateCount] : 1
D/elm:15183( 6643): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
W/ContextImpl( 5149): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/elm:15183( 6643): ElmAgentService : onCreate()
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/elm:15183( 6643): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6643): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6643): MDMBridge.getInstance()
D/elm:15183( 6643): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 6643): MDMBridge.getAllLicenseInfoFromSDK()
D/AASAservice-UpdateReceiver( 5487): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 5487): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
D/elm:15183( 6643): ElmAgentService : onDestroy().
W/System.err( 5487): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 5487): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 5487): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 5487): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 5487): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 5487): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5487): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5487): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 5487): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5487): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5487): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5487): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/TapandpayWidget:TapandpayAppWidgetProvider( 5751): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5751): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 5751): Clear T&P info.
D/TapandpayWidget:TapandpayAppWidgetProvider( 5751): Widget is not attached.
D/RCPManager( 5586):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1016):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1016): queryAllProviders():  providerCallBack is not register for 0
I/art     ( 1016): Explicit concurrent mark sweep GC freed 61373(6MB) AllocSpace objects, 251(3MB) LOS objects, 33% free, 28MB/42MB, paused 4.190ms total 351.705ms
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6694): MountEmulatedStorage()
E/Zygote  ( 6694): v2
I/libpersona( 6694): KNOX_SDCARD checking this for 10160
I/libpersona( 6694): KNOX_SDCARD not a persona
I/SELinux ( 6694): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6694): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6694): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6694 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5529:com.google.android.partnersetup/u0a15 (adj 15): empty #31
D/TimaKeyStoreProvider( 6694): TimaSignature is unavailable
D/ActivityThread( 6694): Added TimaKeyStore provider
I/PCWCLIENTTRACE_PushUtil( 5724): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5724): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5724): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5724): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1016): delete codoeFile: 
W/ResourcesManager( 6694): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
I/AASA_removePackage( 1016): UID=10155 Target=com.test.thalitest
D/PackageManager( 1016): result of delete: 1{959795635}
D/AndroidRuntime( 6628): Shutting down VM
E/Zygote  ( 6711): MountEmulatedStorage()
E/Zygote  ( 6711): v2
I/libpersona( 6711): KNOX_SDCARD checking this for 1000
I/libpersona( 6711): KNOX_SDCARD not a persona
I/SELinux ( 6711): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6711 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6711): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6711): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 5552): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
W/ResourcesManager( 5552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/[0]UMC:UMCContentProvider( 6694): @onCreate
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 5552): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/Zygote  ( 6725): MountEmulatedStorage()
E/Zygote  ( 6725): v2
I/ActivityManager( 1016): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6725 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 6725): KNOX_SDCARD checking this for 10035
I/libpersona( 6725): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Killing 5736:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
I/SELinux ( 6725): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6725): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6725): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6711): TimaSignature is unavailable
D/ActivityThread( 6711): Added TimaKeyStore provider
D/NearbySource( 6654): Nearby Source Create!
D/NearbyContext( 6654): Nearby Context Create!
D/[0]UMC:Core( 6694): onCreate(): 
D/[0]UMC:Core( 6694): @isManagedProfileUser
D/[0]UMC:Core( 6694): userId: 0
W/ResourcesManager( 5552): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/[0]UMC:Core( 6694): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 6694): userInfo.isManagedProfile() : false
W/ResourcesManager( 5552): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 6725): TimaSignature is unavailable
D/ActivityThread( 6725): Added TimaKeyStore provider
W/ContextImpl( 6711): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1016): startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
W/ResourcesManager( 5552): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
D/[0]UMC:DeviceInfo( 6694): USA==US==
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6743): MountEmulatedStorage()
E/Zygote  ( 6743): v2
I/libpersona( 6743): KNOX_SDCARD checking this for 1000
I/libpersona( 6743): KNOX_SDCARD not a persona
I/SELinux ( 6743): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6743 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6743): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6743): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6654): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 6654): Samsung link source created
W/ResourcesManager( 5552): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/ActivityManager( 1016): Killing 5774:com.policydm/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 6743): TimaSignature is unavailable
D/ActivityThread( 6743): Added TimaKeyStore provider
W/ResourcesManager( 5552): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/SPPClientService( 6725): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6725): [PushClientApplication] Push log off : This is Ship build version
D/USER_AGENT( 6694): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
I/SA      ( 5970): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 5970): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10155 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
D/[0]UMC:AdminManager( 6694): init - start
W/art     ( 6628): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/ActivityManager( 1016): Killing 5806:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
D/SPPClientService( 6725): PushLog.txt file is not deleted.
D/SPPClientService( 6725): PushLog.txt file is not deleted.
D/SPPClientService( 6725): ============PushLog. stop!
D/ActivityManager( 1016): startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
D/[0]UMC:AdminManager( 6694): loadAdmins
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
W/ResourcesManager( 5552): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/AcmsPackageEventListener( 6743): Received: android.intent.action.PACKAGE_REMOVED
D/[0]UMC:AdminManager( 6694): init - end
W/ContextImpl( 6743): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
D/GSLBManager( 6694): migrateStoredUrlFromOldPref
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 5552): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ResourcesManager( 5552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/AcmsService( 6743): Enter Oncreate
D/AcmsServiceMonitor( 6743): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6743): creating AcmsCore
D/AcmsCore( 6743): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6743): AcmsCore
D/GSLBManager( 6694): migrateStoredUrlFromOldPref : Migration Not Needed
D/[0]UMC:UMCAdmin( 6694): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 6694): Admin not found in package com.samsung.knoxpb.mdm
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/[0]UMC:Utils( 6694): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 6694): deactivateUMCAdmin : -1
D/ContactProvider( 6654): getAllContactInfoList Start
D/[0]UMC:UMCAdmin( 6694): isContainer : 0
D/AcmsCore( 6743): init
D/AcmsCore( 6743): Looper handler is not null
D/AcmsCore( 6743): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6743): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6743): Incrementing - Counter value: 1
D/AcmsCore( 6743): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6743): onStartCommand
D/AcmsService( 6743): Action: android.intent.action.PACKAGE_REMOVED
D/AcmsServiceMonitor( 6743): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6743): Incrementing - Counter value: 2
D/AcmsService( 6743): Incremented Counter Value : onStartCommand
D/EnterpriseDeviceManagerService( 1016): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 6694): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 6694): isContainer : 0
D/[0]UMC:UMCAdmin( 6694): deactivateUMCAdmin - UMC App Admin deactivated
I/PackagesMonitor( 6654): PackagesMonitor onReceive :com.test.thalitest
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityThread( 6743): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/AcmsCertificateMngr( 6743): AcmsCertificateMngr
W/ResourcesManager( 5552): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/ActivityManager( 1016): startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
D/AcmsRevocationMngr( 6743): AcmsRevocationMngr
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
D/[0]UMC:GuardService( 6694): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
D/[0]UMC:CoreReceiver( 6694): Intent : android.intent.action.PACKAGE_REMOVED
D/[0]UMC:CoreReceiver( 6694): PackageName : com.test.thalitest
D/[0]UMC:CoreReceiver( 6694): Intent Replacing : false
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 5552): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/Zygote  ( 6771): MountEmulatedStorage()
I/libpersona( 6771): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6771): v2
I/libpersona( 6771): KNOX_SDCARD not a persona
I/SELinux ( 6771): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6771): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/[0]UMC:CoreReceiver( 6694): bulk enrolled package: null
V/[0]UMC:ProfileStorage( 6694): Enter loadList
E/SELinux ( 6771): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/[0]UMC:CoreReceiver( 6694): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 6694): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 6694): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 6694): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 6694): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 6694): isContainer : 0

```
